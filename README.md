# Lumina Lens — Professional Photographer Portfolio Template

Thank you for purchasing **Lumina Lens**! This is a modern, responsive, luxury portfolio website template crafted specifically for photographers, videographers, visual artists, and creative professionals.

---

## 🌟 Key Features

- **100% Pure HTML5 & CSS3:** Strictly zero JavaScript dependencies, lightweight and lightning-fast loading speed.
- **Fully Responsive:** Flawless layout on desktop, laptop, tablet, and mobile displays.
- **Luxury Light Aesthetic:** Clean white & ivory background, crisp typography, and rich gold accents.
- **Pure CSS Mobile Navigation:** Smooth slide-out mobile drawer using pure CSS checkbox technique.
- **Curated Photography Sections:**
  - Hero Section with high-resolution photographer portrait & live availability badge
  - About Section with storytelling bio and achievement highlight cards
  - Experience Timeline with career milestones
  - Services Showcase with luxury gradient icon cards
  - Portfolio Showcase with category chips & hover zoom
  - Direct Contact Section with direct WhatsApp, Gmail, and Instagram action buttons (No backend database or form setup required!)
- **SEO & Social Friendly:** Clean semantic markup with OpenGraph meta tags.
- **Complete Documentation:** Includes both this quick-start `README.md` and an interactive browser-based `documentation/index.html` manual.

---

## 📁 Package Structure

```
lumina-lens/
├── index.html                   # Main website homepage
├── README.md                    # Quick-start documentation (this file)
├── documentation/
│   └── index.html               # Comprehensive user manual & setup guide
└── assets/
    ├── css/
    │   └── style.css            # Pure CSS3 stylesheet
    └── images/
        ├── favicon.svg          # Camera aperture browser icon
        ├── hero-photographer.jpg# Hero portrait photograph
        └── projects/            # Sample portfolio project cards
            ├── photo-1.svg
            ├── photo-2.svg
            ├── photo-3.svg
            ├── photo-4.svg
            ├── photo-5.svg
            └── photo-6.svg
```

---

## 🚀 Installation & Local Preview

1. **Extract the Package:** Unzip `lumina-lens-main-files.zip` to a folder on your computer.
2. **Open in Browser:** Double-click `index.html` to instantly run the website in any modern browser (Chrome, Firefox, Safari, Edge). No web server, Node.js, or build process is required!
3. **Open Documentation:** Double-click `documentation/index.html` for the complete visual documentation guide with code examples.

---

## 🛠️ Configuration & Customization Guide

### 1. Changing Your Name & Bio
Open `index.html` in any text editor (such as VS Code, Sublime Text, or Notepad):
- Search for `Kabir Varma` and replace it with your own name.
- Search for the bio paragraphs inside the `<section id="about">` and customize the text and quotes.

### 2. Replacing the Hero Photo
The hero section displays a stylish photographer portrait with a live availability badge:
- Location in `index.html`: lines 90–98.
- To replace: save your own portrait photo (recommended aspect ratio: 3:4, e.g. 900x1200px) as `assets/images/hero-photographer.jpg`.

### 3. Adding Your Own Photos to the Portfolio
In `index.html`, locate the `<section id="projects">` section (lines 200–315):
- Place your photography files inside `assets/images/projects/`.
- Update the `<img src="assets/images/projects/your-photo.jpg">` tags, category badges, and titles.

### 4. Configuring the Contact Section
The contact section in `index.html` (lines 401–436) uses a high-converting **direct contact system** with three pre-configured cards:

#### Card 1: Direct WhatsApp & Phone (Line 403)
- **Current HTML Code:**
  ```html
  <div class="contact-card">
    <div class="contact-icon-bubble">💬</div>
    <div class="contact-type">Direct WhatsApp &amp; Phone</div>
    <div class="contact-value">+91 98765 43210</div>
    <p class="contact-subtext">Available Mon — Sat, 10:00 AM – 7:00 PM IST</p>
    <a href="https://wa.me/919876543210" target="_blank" rel="noopener" class="contact-btn">
      <span>Chat on WhatsApp &rarr;</span>
    </a>
  </div>
  ```
- **How to customize:**
  - Replace `919876543210` in `href="https://wa.me/919876543210"` with your country code and phone number (no spaces, dashes, or `+` sign).
  - Update the displayed number `+91 98765 43210` to your phone number.
  - *(Optional)* If you prefer a direct phone call instead of WhatsApp, change `href="https://wa.me/919876543210"` to `href="tel:+919876543210"` and change the button text to `Call Now &rarr;`.

#### Card 2: Official Gmail / Email (Line 414)
- **Current HTML Code:**
  ```html
  <div class="contact-card">
    <div class="contact-icon-bubble">✉️</div>
    <div class="contact-type">Official Gmail</div>
    <div class="contact-value">kabir.photography@gmail.com</div>
    <p class="contact-subtext">Typically replies within 12 hours</p>
    <a href="mailto:kabir.photography@gmail.com" class="contact-btn">
      <span>Send Email &rarr;</span>
    </a>
  </div>
  ```
- **How to customize:**
  - In `href="mailto:kabir.photography@gmail.com"`, replace `kabir.photography@gmail.com` with your active email address.
  - Update the displayed email in `<div class="contact-value">` to match your email address.

#### Card 3: Studio Location & Instagram (Line 425)
- **Current HTML Code:**
  ```html
  <div class="contact-card">
    <div class="contact-icon-bubble">📍</div>
    <div class="contact-type">Studio &amp; Availability</div>
    <div class="contact-value">Mumbai &bull; New Delhi</div>
    <p class="contact-subtext">Available for Worldwide Destination Travel &bull; Instagram: @lumina.lens</p>
    <a href="https://instagram.com" target="_blank" rel="noopener" class="contact-btn">
      <span>Instagram Profile &rarr;</span>
    </a>
  </div>
  ```
- **How to customize:**
  - In `href="https://instagram.com"`, replace the URL with your full Instagram profile link (e.g. `https://instagram.com/your_handle`).
  - Update the displayed studio location and Instagram handle.

### 5. Customizing Colors & Fonts
All colors and fonts are centralized at the top of `assets/css/style.css` (lines 9–50):
- `--bg-dark`: Background color (`#f8f9fa`)
- `--bg-surface`: Card background (`#ffffff`)
- `--text-main`: Primary text color (`#111827`)
- `--accent-gold`: Gold accent color (`#b48a28`)
- `--font-serif`: Heading font family (`'Playfair Display', Georgia, serif`)
- `--font-sans`: Body font family (`'Plus Jakarta Sans', sans-serif`)

---

## 🌐 How to Publish / Host

This is a 100% static HTML template. You can host it for free on:
- **Vercel:** Drag-and-drop the unzipped folder into your Vercel dashboard.
- **Netlify:** Drag-and-drop the folder onto [app.netlify.com/drop](https://app.netlify.com/drop).
- **GitHub Pages:** Push to a repository and enable GitHub Pages in settings.
- **Standard Web Hosting (cPanel):** Upload `index.html`, `documentation/`, and `assets/` to your `public_html/` folder.

---

## 📄 License & Support

This item is sold under the standard Codester license. For any customization questions or support inquiries, please feel free to leave a comment on the Codester item page or refer to the interactive guide inside `documentation/index.html`.
