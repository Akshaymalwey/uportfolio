<<<<<<< HEAD
# Updated_Portfolio
Updated Portfolio
=======
# Minimal Portfolio Website

A clean, modern, and responsive portfolio website built with HTML, CSS, and JavaScript.

## ✨ Features

- **Responsive Design** - Works perfectly on all devices
- **Modern UI/UX** - Clean and professional appearance
- **Smooth Animations** - Subtle animations and transitions
- **Mobile Navigation** - Hamburger menu for mobile devices
- **Contact Form** - Functional contact form with validation
- **Smooth Scrolling** - Navigation with smooth scroll behavior
- **Progress Bar** - Visual scroll progress indicator
- **SEO Optimized** - Semantic HTML structure

## 🚀 Quick Start

1. **Clone or Download** the project files
2. **Open** `index.html` in your web browser
3. **Customize** the content to match your information
4. **Deploy** to your preferred hosting service

## 📁 File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🎨 Customization Guide

### Personal Information

Edit the following sections in `index.html`:

#### Hero Section

```html
<h1 class="hero-title">Hi, I'm <span class="highlight">Your Name</span></h1>
<p class="hero-subtitle">Full Stack Developer & Designer</p>
<p class="hero-description">
  I create beautiful, functional, and user-centered digital experiences.
</p>
```

#### About Section

```html
<p>
  I'm a passionate developer with a love for creating elegant solutions to
  complex problems...
</p>
```

#### Skills

Update the skills in each category:

```html
<div class="skill-items">
  <span class="skill-item">Your Skill 1</span>
  <span class="skill-item">Your Skill 2</span>
  <!-- Add more skills -->
</div>
```

#### Projects

Replace the placeholder projects with your own:

```html
<div class="project-card">
  <div class="project-image">
    <!-- Add your project image here -->
    <img src="path/to/your/image.jpg" alt="Project Name" />
  </div>
  <div class="project-content">
    <h3>Your Project Name</h3>
    <p>Project description...</p>
    <div class="project-tech">
      <span>Technology 1</span>
      <span>Technology 2</span>
    </div>
    <div class="project-links">
      <a href="your-demo-link" class="project-link">Live Demo</a>
      <a href="your-github-link" class="project-link">GitHub</a>
    </div>
  </div>
</div>
```

#### Contact Information

```html
<span>your.email@example.com</span>
<span>+1 (555) 123-4567</span>
<span>Your City, State</span>
```

### Colors and Styling

Customize colors in `styles.css`:

```css
:root {
  --primary-color: #2563eb; /* Main brand color */
  --secondary-color: #fbbf24; /* Accent color */
  --text-color: #1f2937; /* Main text color */
  --bg-color: #f8fafc; /* Background color */
}
```

### Fonts

Change the font by updating the Google Fonts link in `index.html`:

```html
<link
  href="https://fonts.googleapis.com/css2?family=Your+Font:wght@300;400;500;600;700&display=swap"
  rel="stylesheet"
/>
```

Then update the font-family in `styles.css`:

```css
body {
  font-family:
    "Your Font",
    -apple-system,
    BlinkMacSystemFont,
    "Segoe UI",
    Roboto,
    sans-serif;
}
```

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: 480px - 767px
- **Small Mobile**: Below 480px

## 🌟 Advanced Customization

### Adding New Sections

1. Add a new section in `index.html`:

```html
<section id="new-section" class="new-section">
  <div class="container">
    <h2 class="section-title">New Section</h2>
    <!-- Your content here -->
  </div>
</section>
```

2. Add navigation link:

```html
<li><a href="#new-section" class="nav-link">New Section</a></li>
```

3. Style the section in `styles.css`

### Custom Animations

Add custom CSS animations:

```css
@keyframes yourAnimation {
  from {
    /* starting state */
  }
  to {
    /* ending state */
  }
}

.your-element {
  animation: yourAnimation 1s ease-out;
}
```

### Form Integration

Replace the form handling in `script.js` with your preferred backend:

```javascript
// Replace the setTimeout with actual form submission
fetch("/api/contact", {
  method: "POST",
  body: formData,
})
  .then((response) => response.json())
  .then((data) => {
    // Handle success
  })
  .catch((error) => {
    // Handle error
  });
```

## 🚀 Deployment

### GitHub Pages

1. Push your code to a GitHub repository
2. Go to Settings > Pages
3. Select source branch (usually `main`)
4. Your site will be available at `https://username.github.io/repository-name`

### Netlify

1. Drag and drop your project folder to Netlify
2. Your site will be deployed instantly
3. Customize the domain if needed

### Vercel

1. Connect your GitHub repository to Vercel
2. Vercel will automatically deploy your site
3. Get a custom domain and SSL certificate

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to submit issues and enhancement requests!

## 📞 Support

If you have any questions or need help customizing your portfolio, feel free to reach out!

---

**Happy coding! 🎉**
>>>>>>> c4fe8f2 (Initial Commit)
