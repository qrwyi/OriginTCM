# Origin Chinese Medicine Website
## 源·中医 · Singapore

A clean, bilingual (English + Simplified Chinese), mobile-friendly static website.
No monthly fees. Free to host forever.

---

## Files

```
origin-tcm/
├── index.html          ← Homepage (hero, services, about, contact)
├── blog.html           ← Blog image gallery
├── css/
│   └── style.css       ← All styles
└── images/
    └── blog/           ← Put your Canva blog images here
```

---

## How to deploy FREE on Netlify (recommended)

1. Go to https://netlify.com and sign up free
2. Click "Add new site" → "Deploy manually"
3. Drag and drop the entire `origin-tcm` folder
4. Your site is live instantly at a free Netlify URL (e.g. origin-tcm.netlify.app)
5. To use a custom domain (e.g. originchinese.com.sg):
   - Buy domain at https://www.vodien.com (Singapore registrar)
   - In Netlify: Site settings → Domain management → Add custom domain

---

## How to deploy FREE on GitHub Pages

1. Create a free account at https://github.com
2. Create a new repository called `origin-tcm`
3. Upload all files
4. Go to Settings → Pages → Source: main branch → /root
5. Your site is live at: https://yourusername.github.io/origin-tcm

---

## How to add a new blog post

1. Export your Canva design as JPG or PNG
2. Save the image file to: `images/blog/your-filename.jpg`
3. Open `blog.html` in any text editor (Notepad is fine)
4. Find the last `<div class="post-card">` block
5. Copy it and paste it below — then update:
   - The image: change `post-placeholder` div to `<img src="images/blog/your-filename.jpg" alt="Post title">`
   - `data-category`: choose from: womens / sleep / digestion / stress / immunity / seasonal
   - Post title (English and Chinese)
   - Date

---

## Things to personalise before launch

- [ ] Replace "Practitioner photo" placeholder with a real photo
- [ ] Update practitioner name and bio text
- [ ] Update qualifications (registration number, exact degree)
- [ ] Add real phone number and email
- [ ] Update exact location/clinic address
- [ ] Replace stat numbers (years experience, patients) with real figures
- [ ] Update operating hours
- [ ] Connect enquiry form to email (use https://formspree.io — free tier)

---

## Connecting the contact form to your email (free)

1. Go to https://formspree.io and sign up free
2. Create a new form — you'll get a form endpoint like: https://formspree.io/f/xabcxyz
3. In index.html, find the `<form>` tag and add: `action="https://formspree.io/f/xabcxyz" method="POST"`
4. Done — enquiries go straight to your email

---

## SEO tips for Singapore

- Register on Google Business Profile (free): https://business.google.com
- Submit your site to Google Search Console (free): https://search.google.com/search-console
- The meta tags in index.html are already set up with Singapore TCM keywords

---

Built with pure HTML/CSS/JS. No frameworks. No dependencies. No monthly fees.
