# Giovanni Ciandrini - Personal Website

Professional portfolio website showcasing expertise in Banking, Fintech, and Payment Systems.

## 🎯 Features

- ✅ Modern, professional design
- ✅ Smooth animations and transitions
- ✅ Fully responsive (mobile-friendly)
- ✅ Professional blue & tech grey color scheme
- ✅ Sections: Hero, About, Experience, Skills, Projects, Interests, Contact
- ✅ STAR methodology project showcase (ready to fill)
- ✅ Pure HTML, CSS, JavaScript (no frameworks)
- ✅ SEO-friendly
- ✅ Fast loading

## 📁 Structure

```
giovanni-website/
├── index.html          # Main HTML file
├── css/
│   └── style.css      # Stylesheet
├── js/
│   └── script.js      # JavaScript animations
├── img/
│   └── profile-placeholder.jpg  # Your profile photo
└── README.md          # This file
```

## 🚀 Quick Start

1. **Add Your Photo**
   - Replace `img/profile-placeholder.svg` with your professional photo
   - Recommended size: 500x500px or larger (square)
   - Format: JPG or PNG

2. **Add Your CV (PDF)**
   - Place your CV in `documents/` folder
   - Rename it to: `CV_Giovanni_Ciandrini.pdf`
   - Max size: 2MB recommended
   - The download button will appear in Hero and Contact sections

3. **Update Contact Information**
   - Edit `index.html`
   - Search for "your.email@example.com" and replace with your email
   - LinkedIn is already set to: linkedin.com/in/ciandrinigiovanni ✅
   - Update GitHub username if you have one

4. **Add Your Projects**
   - Find the "Projects & Results" section in `index.html`
   - Duplicate the project card template
   - Fill in using STAR methodology:
     - **S**ituation: Context and background
     - **T**ask: Your responsibility
     - **A**ction: What you did
     - **R**esult: Outcomes and impact

4. **Personalize Interests**
   - Update the "Beyond Code" section with your hobbies
   - You can add/remove interest cards as needed

## 🎨 Customization

### Colors

Edit CSS variables in `css/style.css`:

```css
:root {
    --primary-blue: #2563eb;     /* Main blue */
    --grey-dark: #1f2937;        /* Dark grey */
    /* ... other colors */
}
```

### Fonts

Change font in CSS:

```css
:root {
    --font-primary: 'Your Font', sans-serif;
}
```

### Content

All content is in `index.html` - simply edit the text within each section.

## 📝 Adding Projects (STAR Format)

Example:

```html
<div class="project-card fade-in-up">
    <div class="project-header">
        <h3>Payment Gateway Migration</h3>
        <span class="project-company">Cornèr Banca SA</span>
    </div>
    <div class="project-content">
        <div class="project-section">
            <h4>Situation</h4>
            <p>Legacy payment system needed modernization to support real-time transactions...</p>
        </div>
        <div class="project-section">
            <h4>Task</h4>
            <p>Led the technical design and implementation of new microservices architecture...</p>
        </div>
        <div class="project-section">
            <h4>Action</h4>
            <p>Designed event-driven system using RabbitMQ, implemented .NET Core services...</p>
        </div>
        <div class="project-section">
            <h4>Result</h4>
            <p>Reduced transaction processing time by 60%, increased system reliability to 99.9%...</p>
        </div>
    </div>
    <div class="project-tags">
        <span>.NET Core</span>
        <span>RabbitMQ</span>
        <span>Azure</span>
    </div>
</div>
```

## 🌐 Deployment

### Option 1: GitHub Pages (Free)

1. Create a GitHub repository
2. Upload all files
3. Go to Settings → Pages
4. Select main branch
5. Your site will be live at: `https://yourusername.github.io/repo-name`

### Option 2: Netlify (Free)

1. Drag and drop the folder to [Netlify](https://netlify.com)
2. Done! You'll get a URL like: `https://yoursite.netlify.app`

### Option 3: Vercel (Free)

1. Upload to GitHub
2. Import to [Vercel](https://vercel.com)
3. Deploy

### Option 4: Custom Domain

- Buy a domain (e.g., giovannician drini.com)
- Use any of the above services
- Point your domain to the service

## ✅ Pre-Deployment Checklist

- [ ] Replace profile photo
- [ ] Update email address
- [ ] Update GitHub link
- [ ] Add LinkedIn link (already in contacts)
- [ ] Fill in at least 2-3 STAR projects
- [ ] Test on mobile devices
- [ ] Check all links work
- [ ] Review all text content

## 🔧 Technical Details

- **No dependencies**: Pure HTML, CSS, JS
- **No build process**: Just open `index.html` in a browser
- **Lightweight**: Fast loading times
- **SEO optimized**: Proper meta tags and semantic HTML
- **Accessible**: Good contrast ratios and keyboard navigation

## 📱 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers

## 💡 Tips

1. **Professional Photo**: Use a high-quality, professional headshot
2. **Concise Content**: Keep descriptions clear and concise
3. **Quantify Results**: Use numbers in your STAR projects (e.g., "increased by 60%")
4. **Update Regularly**: Add new projects and experiences
5. **Test**: Check the site on multiple devices before deploying

## 📄 License

Feel free to use this template for your own personal website.

## 🤝 Support

For questions or issues, contact via LinkedIn or email.

---

**Built with passion** 🚀
