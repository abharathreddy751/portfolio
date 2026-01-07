# Professional Portfolio Website

A modern, clean, and professional portfolio website built with HTML, CSS, and JavaScript.

## 🎨 Features

- **Responsive Design** - Works perfectly on desktop, tablet, and mobile devices
- **Modern Aesthetics** - Clean, professional design with smooth animations
- **Smooth Navigation** - Auto-highlighting nav based on scroll position
- **Contact Form** - Functional contact form with validation
- **Performance Optimized** - Fast loading and smooth interactions
- **SEO Friendly** - Proper semantic HTML and meta tags

## 📁 File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # All styling and animations
├── script.js           # Interactive functionality
├── resume/
│   └── bharathresume.pdf  # Your resume (linked in HTML)
└── README.md          # This file
```

## 🚀 Quick Start

1. Open `index.html` in your web browser
2. Or use a local server: `python -m http.server 8000`
3. Navigate to `http://localhost:8000` in your browser

## 📝 Customization Guide

### Update Personal Information

In `index.html`, replace the following:

1. **Name & Title** (Line 40-41):
   ```html
   <h1 class="hero-title">Hi, I'm <span class="highlight">Bharath</span></h1>
   <p class="hero-subtitle">Full-Stack Developer | Problem Solver | Tech Enthusiast</p>
   ```

2. **Hero Description** (Line 42):
   ```html
   <p class="hero-description">Your professional tagline here</p>
   ```

3. **Contact Information** (Around line 206):
   ```html
   <a href="mailto:your.email@example.com">your.email@example.com</a>
   <p>Your City, Country</p>
   ```

4. **Social Links** (Around line 212):
   ```html
   <a href="https://linkedin.com/in/yourprofile" class="social-link" title="LinkedIn">in</a>
   <a href="https://github.com/yourprofile" class="social-link" title="GitHub">gh</a>
   ```

### Update Experience Section

Replace the timeline items (Lines 120-160) with your actual experience:

```html
<div class="timeline-item">
    <div class="timeline-marker"></div>
    <div class="timeline-content">
        <h3>Your Job Title</h3>
        <p class="timeline-company">Company Name</p>
        <p class="timeline-date">YYYY - Present</p>
        <ul class="timeline-description">
            <li>Achievement 1</li>
            <li>Achievement 2</li>
            <li>Achievement 3</li>
        </ul>
    </div>
</div>
```

### Update Skills

Modify the skills section (Lines 165-195) with your actual skills:

```html
<div class="skill-category">
    <h3>Category Name</h3>
    <div class="skill-tags">
        <span class="skill-tag">Skill 1</span>
        <span class="skill-tag">Skill 2</span>
        <span class="skill-tag">Skill 3</span>
    </div>
</div>
```

### Update About Section

Replace the about content (Lines 75-100) with your biography and stats.

## 🎯 Color Customization

In `styles.css`, modify the CSS variables (Lines 8-21):

```css
:root {
    --primary: #2563eb;           /* Main brand color */
    --primary-dark: #1e40af;      /* Darker shade */
    --primary-light: #3b82f6;     /* Lighter shade */
    --secondary: #1f2937;         /* Dark gray */
    --accent: #f59e0b;            /* Accent color */
    /* ... other colors ... */
}
```

### Color Palette Suggestions

**Professional Blue**: #2563eb, #3b82f6
**Modern Purple**: #7c3aed, #a855f7
**Tech Green**: #10b981, #14b8a6
**Sunset Orange**: #f59e0b, #f97316

## 📱 Responsive Breakpoints

- **Desktop**: 1200px+
- **Tablet**: 768px - 1199px
- **Mobile**: 480px - 767px
- **Small Mobile**: Below 480px

## ✨ JavaScript Features

- **Smooth Scrolling** - All anchor links scroll smoothly
- **Nav Highlighting** - Current section highlights in navigation
- **Scroll Animations** - Elements fade in as you scroll
- **Form Validation** - Contact form provides feedback
- **Intersection Observer** - Efficient scroll-based animations

## 🔗 Add External Links

To add project links or update social media:

1. LinkedIn: Update href in line ~212
2. GitHub: Update href in line ~214
3. Twitter/X: Update href in line ~216
4. Custom Links: Add new social icons in the same format

## 📧 Contact Form Setup

For a working email contact form, you can:

1. Use FormSubmit.co (free):
   ```html
   <form action="https://formsubmit.co/your@email.com" method="POST">
   ```

2. Use Netlify Forms (if hosting on Netlify)
3. Use Backend Service (Node.js, Python, etc.)

## 🎬 Animations

The portfolio includes several smooth animations:

- **Fade in on Scroll** - Elements appear as you scroll
- **Floating Cards** - Hero section has animated cards
- **Hover Effects** - Buttons and cards have hover animations
- **Gradient Shifts** - Text and elements shift on interaction

## 🚀 Deployment

### GitHub Pages (Free)
1. Create a GitHub repo named `yourname.github.io`
2. Push this folder to main branch
3. Visit `https://yourname.github.io`

### Netlify (Free)
1. Visit netlify.com
2. Drag and drop this folder
3. Get instant deployment with custom domain

### Vercel (Free)
1. Connect GitHub repo
2. One-click deployment
3. Automatic updates on push

## 📊 Performance Tips

1. Compress images before adding them
2. Minimize CSS/JS for production
3. Use CDN for fonts (already done with Google Fonts)
4. Lazy load images if adding many
5. Cache assets for faster repeat visits

## 🐛 Troubleshooting

**Navigation not highlighting?**
- Check that section IDs match nav href values

**Form not working?**
- Set up FormSubmit.co or backend service
- Check browser console for errors

**Styling looks off?**
- Clear browser cache (Ctrl+Shift+Delete)
- Check if CSS file is loading properly

**Animations not smooth?**
- Modern browsers only - test in Chrome/Firefox
- Check GPU acceleration in developer tools

## 📄 License

This portfolio template is free to use and modify for personal use.

## 💡 Pro Tips

1. **Add a photo** - Replace hero visual with a professional headshot
2. **Add projects** - Create a projects section with your work
3. **Blog section** - Add a blog to showcase expertise
4. **Dark mode** - Add toggle for dark/light themes
5. **PDF resume** - Link your actual resume (already linked!)

---

Built with ❤️ for professionals who want to stand out. Happy deploying! 🚀
