# 🖼️ ვიზუალური გზამკვლევი - ნაბიჯ-ნაბიჯ

## 🎯 GitHub-ზე ფაილების განახლება (ბრაუზერით)

---

## 📍 **ᲜᲐᲑᲘᲯᲘ 1: Repository-ზე გადასვლა**

```
1. გახსენი ბრაუზერი (Chrome, Firefox, etc.)
2. გადადი: https://github.com/ggko-16/westt
3. Login გააკეთე თუ საჭიროა

დაინახავ:
┌─────────────────────────────────────────┐
│ ggko-16 / westt                         │
│ [Code ▼] [Add file ▼] [<> Code]       │
│                                         │
│ 📁 admin/                               │
│ 📁 assets/                              │
│ 📁 content/                             │
│ 📄 index.html                           │
│ 📄 style.css                            │
└─────────────────────────────────────────┘
```

---

## 📍 **ᲜᲐᲑᲘᲯᲘ 2: ძველი ფაილების წაშლა (Option A)**

### ვარიანტი A: ფაილები ცალ-ცალკე

```
1. დააჭირე index.html
2. ზედა მარჯვენა კუთხეში სამი წერტილი "..." → Delete file
3. ქვემოთ commit message: "Remove old index.html"
4. დააჭირე [Commit changes]

გაიმეორე ყველა ფაილისთვის:
- style.css
- admin/config.yml
- admin/index.html
- assets/westf.png
- content/contact.json
- content/team.json
- content/prices/*.json
```

### ვარიანტი B: ყველაფერი ერთად (სწრაფი!)

```
თუ Git-ი იცი, შენს კომპიუტერში:

1. გახსენი Terminal (Mac/Linux) ან Git Bash (Windows)
2. ჩაწერე:
   
   git clone https://github.com/ggko-16/westt.git
   cd westt
   rm -rf * .*
   # (ეს წაშლის ყველაფერს გარდა .git-ისა)
```

---

## 📍 **ᲜᲐᲑᲘᲯᲘ 3: ახალი ფაილების ატვირთვა**

### 3.1 ფაილების მომზადება

```
1. გახსენი westt-improved.zip
2. Extract files → დაინახავ westt-main ფოლდერს
3. გახსენი westt-main ფოლდერი

დაინახავ ფაილებს:
westt-main/
├── index.html          ← ახალი
├── style.css           ← ახალი
├── admin/              ← ახალი
├── assets/             ← ახალი
├── content/            ← ახალი
├── netlify.toml        ← ✨ ახალი!
├── robots.txt          ← ✨ ახალი!
├── sitemap.xml         ← ✨ ახალი!
├── manifest.json       ← ✨ ახალი!
├── .htaccess           ← ✨ ახალი!
├── README.md           ← ✨ ახალი!
└── სხვა .md ფაილები
```

### 3.2 GitHub-ზე ატვირთვა

```
1. GitHub repository-ზე დააჭირე [Add file ▼]
2. აირჩიე [Upload files]

დაინახავ გვერდს:
┌─────────────────────────────────────────┐
│ Drag files here to add them to your    │
│ repository or choose your files         │
│                                         │
│    [📁 Choose files]                    │
│                                         │
│ Commit changes                          │
│ ┌─────────────────────────────────────┐ │
│ │ Add files via upload                │ │
│ └─────────────────────────────────────┘ │
│                                         │
│ [Commit changes]                        │
└─────────────────────────────────────────┘
```

### 3.3 ფაილების არჩევა

```
ვარიანტი A - Drag & Drop (მარტივი!):
1. გახსენი westt-main ფოლდერი
2. აირჩიე ყველა ფაილი (Ctrl+A or Cmd+A)
3. გადაათრიე GitHub-ის გვერდზე

ვარიანტი B - Manual:
1. დააჭირე [Choose files]
2. Navigate to westt-main
3. აირჩიე ყველა ფაილი
4. დააჭირე [Open]
```

### 3.4 Commit შექმნა

```
1. ქვემოთ დაინახავ commit form:

   Commit changes
   ┌──────────────────────────────────────┐
   │ Update site v2.0 - SEO, A11y, Security│
   └──────────────────────────────────────┘
   
   Extended description (optional)
   ┌──────────────────────────────────────┐
   │ - Added SEO optimization             │
   │ - Added Accessibility features       │
   │ - Improved error handling            │
   │ - Added security headers             │
   └──────────────────────────────────────┘

2. დააჭირე [Commit changes] ღილაკს (მწვანე)
```

---

## 📍 **ᲜᲐᲑᲘᲯᲘ 4: შემოწმება**

### 4.1 GitHub-ზე შემოწმება

```
1. Refresh GitHub repository page
2. დაინახავ ახალ ფაილებს:

┌─────────────────────────────────────────┐
│ ggko-16 / westt                         │
│ Latest commit: Update site v2.0         │
│ 2 minutes ago                           │
│                                         │
│ 📄 .htaccess                 ← ✅ ახალი │
│ 📁 admin/                               │
│ 📁 assets/                              │
│ 📄 CHECKLIST.md             ← ✅ ახალი │
│ 📁 content/                             │
│ 📄 GITHUB_UPDATE_GUIDE.md   ← ✅ ახალი │
│ 📄 IMPROVEMENTS.md          ← ✅ ახალი │
│ 📄 index.html                           │
│ 📄 manifest.json            ← ✅ ახალი │
│ 📄 netlify.toml             ← ✅ ახალი │
│ 📄 README.md                ← ✅ ახალი │
│ 📄 robots.txt               ← ✅ ახალი │
│ 📄 sitemap.xml              ← ✅ ახალი │
│ 📄 style.css                            │
│ 📄 SUMMARY.md               ← ✅ ახალი │
└─────────────────────────────────────────┘
```

### 4.2 Netlify-ზე შემოწმება

```
1. გადადი https://app.netlify.com
2. გახსენი შენი site
3. დაინახავ "Deploys" tab-ზე:

┌─────────────────────────────────────────┐
│ Production deploys                      │
│                                         │
│ 🟢 Published   Update site v2.0         │
│    2 minutes ago                        │
│    Deploy time: 32s                     │
│    [View deploy]                        │
└─────────────────────────────────────────┘
```

### 4.3 საიტის შემოწმება

```
1. დააჭირე site URL-ს (e.g., yoursite.netlify.app)
2. შეამოწმე:
   ✅ გვერდი იხსნება
   ✅ ნავიგაცია მუშაობს
   ✅ სურათები ჩაიტვირთა
   ✅ ფასები ჩანს
   ✅ გალერეა მუშაობს
   
3. დააჭირე Ctrl+U (View Source) და შეამოწმე:
   ✅ <meta name="description" ...> არსებობს
   ✅ Open Graph tags არსებობს
   ✅ robots.txt ხელმისაწვდომია (/robots.txt)
   ✅ sitemap.xml ხელმისაწვდომია (/sitemap.xml)
```

---

## 🔧 **ᲜᲐᲑᲘᲯᲘ 5: URL-ების შეცვლა**

თუ შენი domain არ არის `westface.ge`, შეცვალე:

### 5.1 index.html რედაქტირება GitHub-ზე

```
1. გადადი repository: https://github.com/ggko-16/westt
2. დააჭირე index.html
3. დააჭირე ✏️ (Edit) ზედა მარჯვნივ

4. იპოვე ეს ხაზები (~20-25):
   
   <meta property="og:url" content="https://westface.ge/">
   <link rel="canonical" href="https://westface.ge/">
   
5. შეცვალე შენი URL-ით:
   
   <meta property="og:url" content="https://yoursite.netlify.app/">
   <link rel="canonical" href="https://yoursite.netlify.app/">

6. Commit: "Update domain URLs"
```

### 5.2 sitemap.xml რედაქტირება

```
1. დააჭირე sitemap.xml
2. დააჭირე ✏️ (Edit)
3. Find & Replace (Ctrl+F):
   - ძებნა: westface.ge
   - შეცვლა: yoursite.netlify.app
4. Commit: "Update sitemap URLs"
```

---

## ✅ **დასრულებული!**

შენი საიტი ახლა:
- ✅ განახლებულია GitHub-ზე
- ✅ დარედეპლოებულია Netlify-ზე
- ✅ SEO-ოპტიმიზებული
- ✅ Accessible
- ✅ უსაფრთხო
- ✅ Production-ready

---

## 📊 **შემდეგი ნაბიჯები (არასავალდებულო)**

1. **Google Search Console**
   - https://search.google.com/search-console
   - Add property → yoursite.netlify.app
   - Submit sitemap: yoursite.netlify.app/sitemap.xml

2. **Google Analytics**
   - https://analytics.google.com
   - Create account
   - დააკოპირე tracking code
   - დაამატე index.html-ში

3. **Custom Domain** (თუ გაქვს)
   - Netlify → Domain settings
   - Add custom domain
   - Configure DNS records

---

## 🆘 **ხშირი შეცდომები და გადაწყვეტები**

### ❌ "Files not showing on GitHub"
```
✅ გადაწყვეტა:
- Hard refresh: Ctrl+Shift+R (Windows) or Cmd+Shift+R (Mac)
- დაელოდე 1-2 წუთს
- შეამოწმე commits tab
```

### ❌ "Netlify says 'Build failed'"
```
✅ გადაწყვეტა:
- Site settings → Build & deploy
- Build command: (leave empty)
- Publish directory: . (just a dot)
- Redeploy
```

### ❌ "Site shows 404"
```
✅ გადაწყვეტა:
- შეამოწმე index.html არის root-ში
- არა westt-main/index.html
- უნდა იყოს: yourrepo/index.html
```

### ❌ "Hidden files (.htaccess) not uploaded"
```
✅ გადაწყვეტა:
Mac/Linux:
1. Terminal: ls -la westt-main/
2. ნახავ .htaccess-ს
3. კოპირება: cp westt-main/.htaccess destination/

Windows:
1. Folder options → Show hidden files
2. დაინახავ .htaccess
3. კოპირება როგორც ჩვეულებრივ
```

---

## 🎓 **Pro Tips**

💡 **Tip 1**: გამოიყენე GitHub Desktop - უფრო ვიზუალურია
💡 **Tip 2**: დააკოპირე backup ფაილები Google Drive-ზე
💡 **Tip 3**: ყოველთვის Test ლოკალურად deployment-მდე
💡 **Tip 4**: გააკეთე commit-ები პატარა ნაწილებად (არა ყველაფერი ერთად)

---

**არის კითხვები? დამიწერე! 📧**
