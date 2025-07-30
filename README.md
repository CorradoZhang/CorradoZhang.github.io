# Academic Personal Homepage

A modern, responsive academic personal homepage designed for researchers, professors, and academics. Built with HTML, CSS, and JavaScript, featuring a clean design and professional layout.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Academic Sections**: Research, Publications, Teaching, and Contact information
- **Interactive Elements**: Smooth scrolling, hover effects, and mobile navigation
- **SEO Friendly**: Semantic HTML structure for better search engine optimization
- **Fast Loading**: Optimized CSS and minimal JavaScript for quick page loads

## Sections Included

1. **Hero Section**: Introduction with name, title, and call-to-action buttons
2. **About**: Personal background and research interests
3. **Research**: Research areas with icons and descriptions
4. **Publications**: Selected publications with DOI and PDF links
5. **Teaching**: Course information with student counts and ratings
6. **Contact**: Office information and social media links

## Quick Start

1. **Download the files** to your local machine
2. **Open `index.html`** in your web browser to preview
3. **Customize the content** by editing the HTML file
4. **Deploy** to your web server or hosting platform

## Customization Guide

### 1. Personal Information

Replace the placeholder text in `index.html`:

```html
<!-- Replace [Your Name] with your actual name -->
<h1 class="hero-title">Dr. [Your Name]</h1>
<p class="hero-subtitle">Assistant Professor</p>
<p class="hero-department">Department of [Your Field]</p>
<p class="hero-institution">[Your University]</p>
```

### 2. About Section

Update the about section with your personal information:

```html
<p>I am an Assistant Professor in the Department of [Your Field] at [Your University]. 
My research focuses on [brief description of your research area]. 
I received my Ph.D. from [University] in [Year] and my B.S./M.S. from [University] in [Year].</p>
```

### 3. Research Interests

Modify the research interests list:

```html
<ul>
    <li>Your Research Area 1</li>
    <li>Your Research Area 2</li>
    <li>Your Research Area 3</li>
    <li>Your Research Area 4</li>
</ul>
```

### 4. Publications

Replace the sample publications with your actual publications:

```html
<div class="publication-item">
    <div class="publication-year">2024</div>
    <div class="publication-content">
        <h3>"Your Publication Title"</h3>
        <p class="publication-authors">Your Name, Co-author, Co-author</p>
        <p class="publication-journal">Journal Name</p>
        <div class="publication-links">
            <a href="YOUR_DOI_LINK" class="publication-link"><i class="fas fa-external-link-alt"></i> DOI</a>
            <a href="YOUR_PDF_LINK" class="publication-link"><i class="fas fa-file-pdf"></i> PDF</a>
        </div>
    </div>
</div>
```

### 5. Teaching

Update the course information:

```html
<div class="course-item">
    <h3>Course Code: Course Title</h3>
    <p class="course-term">Semester Year</p>
    <p class="course-description">Course description here.</p>
    <div class="course-stats">
        <span class="stat">Number Students</span>
        <span class="stat">Rating/5</span>
    </div>
</div>
```

### 6. Contact Information

Update your contact details:

```html
<div class="contact-item">
    <i class="fas fa-envelope"></i>
    <div>
        <h3>Email</h3>
        <p>your.email@university.edu</p>
    </div>
</div>
```

### 7. Social Media Links

Update the social media links in `script.js`:

```javascript
if (platform.includes('google-scholar')) {
    url = 'https://scholar.google.com/citations?user=YOUR_USER_ID';
} else if (platform.includes('researchgate')) {
    url = 'https://www.researchgate.net/profile/YOUR_PROFILE';
} else if (platform.includes('linkedin')) {
    url = 'https://linkedin.com/in/YOUR_USERNAME';
}
```

### 8. Profile Picture

Replace the placeholder icon with your actual profile picture:

```html
<!-- Replace this -->
<div class="profile-placeholder">
    <i class="fas fa-user-graduate"></i>
</div>

<!-- With this -->
<div class="hero-image">
    <img src="path/to/your/photo.jpg" alt="Dr. Your Name" class="profile-photo">
</div>
```

Then add this CSS to `styles.css`:

```css
.profile-photo {
    width: 300px;
    height: 300px;
    border-radius: 50%;
    object-fit: cover;
    border: 3px solid rgba(255, 255, 255, 0.2);
}
```

## Color Scheme

The website uses a professional color scheme with:
- Primary: Blue gradient (#667eea to #764ba2)
- Text: Dark gray (#1f2937, #4b5563)
- Background: Light gray (#f8fafc)
- Accent: Blue (#3b82f6)

To change colors, edit the CSS variables in `styles.css`.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Deployment

### GitHub Pages
1. Create a new repository on GitHub
2. Upload all files to the repository
3. Go to Settings > Pages
4. Select source branch (usually `main`)
5. Your site will be available at `https://username.github.io/repository-name`

### Netlify
1. Drag and drop the folder to [Netlify](https://netlify.com)
2. Your site will be deployed instantly
3. Customize the URL in the site settings

### Traditional Web Hosting
1. Upload all files to your web server
2. Ensure `index.html` is in the root directory
3. Your site will be accessible at your domain

## File Structure

```
academic-homepage/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Customization Tips

1. **Keep it professional**: Use high-quality images and maintain consistent formatting
2. **Update regularly**: Keep publications and teaching information current
3. **Optimize images**: Compress images for faster loading
4. **Test responsiveness**: Check how your site looks on different devices
5. **Add analytics**: Consider adding Google Analytics to track visitors

## Support

If you need help customizing your academic homepage:

1. Check the HTML comments for guidance
2. Review the CSS classes for styling options
3. Modify the JavaScript for additional functionality
4. Test changes in a local environment before deploying

## License

This template is free to use for personal and academic purposes. Please credit the original design if you modify and redistribute.

---

**Happy customizing!** 🎓 