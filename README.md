# 🎨 WestFace - პროფესიონალური ფოტოების ბეჭდვა

მაღალი ხარისხის ფოტოსტუდიის თანამედროვე ვებსაიტი პროფესიონალური ფუნქციებით.

## ✨ ფუნქციები

- 📸 **ფოტოების ბეჭდვა** - ყველა ზომის ფოტოების პრინტი
- 🖼️ **პოსტერების დამზადება** - მაღალი ხარისხის პოსტერები
- 🎨 **დიზაინის სერვისი** - პროფესიონალური დიზაინი
- 🚚 **უფასო მიწოდება** - თბილისში
- 💼 **Netlify CMS** - მარტივი კონტენტის მართვა

## 🚀 ტექნოლოგიები

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **CMS**: Netlify CMS
- **Hosting**: Netlify (რეკომენდებული)
- **API**: GitHub API (გალერეისთვის)
- **Analytics**: Google Analytics (მზადაა)

## 📦 ინსტალაცია

### 1. ლოკალურად გაშვება

```bash
# პროექტის ჩამოტვირთვა
git clone https://github.com/ggko-16/westt.git
cd westt

# გახსენი index.html ბრაუზერში
# ან გამოიყენე live server
```

### 2. Netlify-ზე Deploy

1. **Fork repository** GitHub-ზე
2. **Connect Netlify**:
   - netlify.com > New site from Git
   - აირჩიე repository
   - Build command: (დატოვე ცარიელი)
   - Publish directory: `.`

3. **Enable Identity**:
   - Site settings > Identity > Enable Identity
   - Registration preferences: Invite only
   - External providers: (optional)

4. **Enable Git Gateway**:
   - Site settings > Identity > Services > Git Gateway
   - Enable Git Gateway

### 3. Admin Access

1. `https://yoursitename.netlify.app/admin`
2. პირველი ადმინის დამატება invitation-ით
3. შესვლა და კონტენტის რედაქტირება

## 📁 სტრუქტურა

```
westt-main/
├── index.html              # მთავარი გვერდი
├── style.css               # სტილები
├── admin/                  # Netlify CMS
│   ├── config.yml
│   └── index.html
├── assets/                 # სურათები, icons
│   └── westf.png
├── content/                # JSON ფაილები
│   ├── contact.json
│   ├── team.json
│   └── prices/
│       ├── photo.json
│       ├── printing.json
│       └── frames.json
├── netlify.toml            # Netlify config
├── robots.txt              # SEO
├── sitemap.xml             # SEO
├── manifest.json           # PWA
├── .htaccess               # Apache config
├── IMPROVEMENTS.md         # ცვლილებების დოკუმენტაცია
└── README.md               # ეს ფაილი
```

## 🎨 კონტენტის რედაქტირება

### Netlify CMS-ით (რეკომენდებული):

1. გადადი `/admin`
2. შესვლა
3. აირჩიე სექცია (ფასები, გუნდი, კონტაქტი, გალერეა)
4. რედაქტირება და შენახვა

### მანუალურად (JSON ფაილები):

```json
// content/contact.json
{
  "phone": "+995 574 80 7066",
  "email": "westfaceshop@gmail.com",
  "address": "თბილისი",
  "facebook": "https://facebook.com/..."
}
```

## 🔧 კონფიგურაცია

### 1. Domain-ის შეცვლა

**netlify.toml**:
```toml
# არ დაგჭირდება, Netlify ავტომატურად აკეთებს
```

**index.html** (meta tags):
```html
<meta property="og:url" content="https://yourdomain.com/">
<link rel="canonical" href="https://yourdomain.com/">
```

**sitemap.xml**:
```xml
<loc>https://yourdomain.com/</loc>
```

### 2. Google Analytics დამატება

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

### 3. ფერების შეცვლა

**style.css**:
```css
/* მთავარი ფერი */
--primary-color: #667eea;
--secondary-color: #764ba2;

/* ან პირდაპირ შეცვალე */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

## 🔒 უსაფრთხოება

- ✅ Content Security Policy (CSP)
- ✅ Security Headers
- ✅ XSS Protection
- ✅ HTTPS (Netlify-ით ავტომატურად)
- ✅ Admin Panel Protection

## 📱 Responsive Design

- ✅ Mobile First
- ✅ Tablet ოპტიმიზაცია
- ✅ Desktop view
- ✅ Burger Menu
- ✅ Touch-friendly

## ♿ Accessibility

- ✅ ARIA Labels
- ✅ Keyboard Navigation
- ✅ Screen Reader Support
- ✅ Focus States
- ✅ Alt Attributes
- ✅ Semantic HTML

## 🚀 Performance

- ✅ Lazy Loading Images
- ✅ CSS/JS Minification (რეკომენდებული)
- ✅ Gzip Compression
- ✅ Browser Caching
- ✅ Loading States

## 📊 SEO

- ✅ Meta Tags
- ✅ Open Graph
- ✅ Twitter Cards
- ✅ Sitemap.xml
- ✅ Robots.txt
- ✅ Canonical URLs
- ✅ Structured Data (შემდეგი ნაბიჯი)

## 🐛 Troubleshooting

### გალერეა არ ჩაიტვირთა?

1. შეამოწმე GitHub repository path: `ggko-16/westt`
2. დარწმუნდი რომ `content/gallery/` არსებობს
3. შეამოწმე browser console errors

### CMS არ მუშაობს?

1. დარწმუნდი რომ Netlify Identity არის enabled
2. შეამოწმე Git Gateway settings
3. გადადი `/admin` და სცადე თავიდან შესვლა

### ფორმები არ იგზავნება?

1. შეამოწმე Google Forms URL
2. დარწმუნდი რომ ფორმა არის public
3. შეამოწმე browser console

## 📈 შემდეგი ნაბიჯები

### Immediate:
- [ ] Custom Domain დამატება
- [ ] Google Analytics
- [ ] Google Search Console
- [ ] Facebook Pixel (optional)

### Short-term:
- [ ] WebP ფორმატის გამოყენება
- [ ] Service Worker (PWA)
- [ ] Contact Form Validation
- [ ] Newsletter Integration

### Long-term:
- [ ] Online Payment
- [ ] Customer Dashboard
- [ ] Review System
- [ ] Blog Section

## 📞 Support

- **Email**: westfaceshop@gmail.com
- **Phone**: +995 574 80 7066
- **Facebook**: [WestFace Shop](https://facebook.com/...)

## 📄 License

© 2026 WestFace Shop. All Rights Reserved.

---

**ვერსია**: 2.0  
**ბოლო განახლება**: 8 თებერვალი, 2026  
**Developer**: [Your Name]
