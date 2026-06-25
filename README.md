# CHHENG Sothean — Data Science Portfolio

A clean, modern, dark-themed personal portfolio website built with HTML, CSS, and JavaScript. Designed to showcase Data Science, Data Analysis, Data Engineering, and Machine Learning projects for internship applications.

## 🚀 Live Demo

> _Replace this with your GitHub Pages URL after deployment:_  
> `https://thean16.github.io/portfolio/`

## 📸 Preview

![Portfolio Screenshot](assets/air-quality-dashboard.png)

## ✨ Features

- **Dark theme** with blue/cyan data-tech accent
- **Responsive design** — works on desktop, tablet, and mobile
- **Typing animation** cycling through focus areas
- **Smooth scroll reveal** animations on all sections
- **Sticky navbar** with active section highlighting
- **Mobile hamburger menu** for small screens
- **Project detail modals** with full workflow descriptions
- **Downloadable resume** button
- **Back-to-top** button
- **SEO-optimized** meta tags and semantic HTML
- **No dependencies** — runs by opening `index.html` directly

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Semantic structure |
| CSS3 | Styling, animations, responsive layout |
| JavaScript | Interactivity, typing effect, scroll reveal |
| Google Fonts | Inter & JetBrains Mono typography |

## 📁 Folder Structure

```
portfolio/
├── index.html                  # Main HTML page
├── style.css                   # Complete stylesheet
├── script.js                   # JavaScript functionality
├── assets/
│   ├── resume.pdf              # Your resume (PDF)
│   ├── air-quality-dashboard.png   # Project 1 screenshot
│   ├── aba-dashboard.png       # Project 2 screenshot
│   ├── covid-dashboard.png     # Project 3 screenshot
│   └── profile.png             # Profile photo
└── README.md                   # This file
```

## 💻 Run Locally

No build tools or dependencies required.

1. Clone the repository:
   ```bash
   git clone https://github.com/thean16/portfolio.git
   cd portfolio
   ```

2. Open `index.html` in your browser:
   ```bash
   open index.html        # macOS
   start index.html       # Windows
   xdg-open index.html    # Linux
   ```

That's it — no `npm install`, no server needed.

## 🌐 Deploy on GitHub Pages

1. Push this repository to GitHub:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/thean16/portfolio.git
   git push -u origin main
   ```

2. Go to your repository on GitHub → **Settings** → **Pages**

3. Under **Source**, select:
   - Branch: `main`
   - Folder: `/ (root)`

4. Click **Save**. Your site will be live at:
   ```
   https://thean16.github.io/portfolio/
   ```

## ✏️ Customization

### Update Links
- **GitHub**: Search for `https://github.com/thean16` and update if needed
- **LinkedIn**: Search for `href="#"` in contact/hero sections and replace with your LinkedIn URL
- **Project GitHub links**: Update the `href="#"` in each project card

### Update Assets
- Replace `assets/profile.png` with your profile photo
- Replace `assets/resume.pdf` with your actual resume
- Replace project screenshots in `assets/`

### Add Projects
Copy an existing `<article class="project-card">` block in `index.html` and update the content. Also add a corresponding modal.

## 📬 Contact

- **Email**: thean160220@gmail.com
- **GitHub**: [github.com/thean16](https://github.com/thean16)
- **LinkedIn**: _Add your LinkedIn URL_
- **Location**: Phnom Penh, Cambodia

---

© 2026 CHHENG Sothean. Built with HTML, CSS, and JavaScript.
