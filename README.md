# Applied ML Engineer Portfolio

A modern, responsive portfolio website for showcasing machine learning projects, blog posts, and professional experience.

## 🚀 Features

- **Modern Design**: Clean, professional design with smooth animations
- **Responsive**: Works perfectly on desktop, tablet, and mobile devices
- **Interactive**: Hover effects, smooth scrolling, and dynamic content
- **SEO Optimized**: Meta tags, semantic HTML, and fast loading
- **Performance**: Optimized images, CSS, and JavaScript
- **Accessibility**: Proper contrast ratios and semantic markup

## 📁 Project Structure

```
yourusername.github.io/
├── index.html                 # Main portfolio page
├── assets/
│   ├── images/
│   │   ├── profile.jpg        # Your professional photo
│   │   ├── project1.jpg       # Project screenshot
│   │   ├── project2.jpg       # Project screenshot
│   │   └── project3.jpg       # Project screenshot
│   ├── css/
│   │   └── style.css          # Main stylesheet
│   └── js/
│       └── script.js          # Interactive functionality
├── blog/
│   ├── index.html             # Blog listing page
│   └── posts/                 # Individual blog posts
├── projects/
│   └── index.html             # Detailed projects showcase
└── README.md                  # This file
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and modern web standards
- **CSS3**: Flexbox, Grid, custom properties, animations
- **JavaScript**: ES6+, Intersection Observer API, smooth scrolling
- **Font Awesome**: Icons and visual elements
- **GitHub Pages**: Free hosting and deployment

## 📝 Customization Guide

### 1. Personal Information
Update the following in `index.html`:
- Replace "Your Name" with your actual name
- Update email, LinkedIn, GitHub links
- Modify the hero section description
- Update the about section with your story

### 2. Projects
- Add your project screenshots to `assets/images/`
- Update project descriptions, technologies, and links
- Add GitHub repository links
- Include live demo links if available

### 3. Blog Posts
- Create individual blog post HTML files in `blog/posts/`
- Update the blog index with your actual posts
- Add publication dates and categories

### 4. Skills & Technologies
Modify the skills section to reflect your expertise:
- Programming languages
- ML frameworks and libraries
- Cloud platforms and tools
- Specialized domains

### 5. Images
Replace placeholder images with your actual content:
- `profile.jpg`: Professional headshot
- `project1.jpg`, `project2.jpg`, etc.: Project screenshots
- Optimize images for web (WebP format recommended)

## 🚀 Deployment to GitHub Pages

### Step 1: Create Repository
```bash
# Create a repository named: yourusername.github.io
# Replace 'yourusername' with your actual GitHub username
```

### Step 2: Clone and Setup
```bash
git clone https://github.com/yourusername/yourusername.github.io.git
cd yourusername.github.io

# Copy all files from this project to your repository
```

### Step 3: Customize Content
1. Update personal information
2. Replace placeholder images
3. Modify project descriptions
4. Add your blog posts
5. Update contact information

### Step 4: Deploy
```bash
git add .
git commit -m "Initial portfolio website"
git push origin main
```

Your site will be live at: `https://yourusername.github.io`

## 🎨 Color Scheme

The website uses CSS custom properties for easy theme customization:

```css
:root {
    --primary-color: #2563eb;      /* Blue */
    --secondary-color: #64748b;    /* Gray */
    --accent-color: #f59e0b;       /* Amber */
    --dark-bg: #0f172a;            /* Dark blue */
    --light-bg: #f8fafc;           /* Light gray */
    --text-primary: #1e293b;       /* Dark gray */
    --text-secondary: #64748b;     /* Medium gray */
}
```

## 📱 Responsive Design

The website is fully responsive with breakpoints:
- **Desktop**: 1200px and above
- **Tablet**: 768px to 1199px
- **Mobile**: Below 768px

## ⚡ Performance Optimizations

- **Lazy Loading**: Images load only when needed
- **CSS Optimization**: Efficient selectors and minimal reflows
- **JavaScript**: Throttled scroll events and efficient DOM manipulation
- **Image Optimization**: Compressed images with appropriate formats

## 🔧 Local Development

To run the website locally:

```bash
# Option 1: Using Python
python -m http.server 8000

# Option 2: Using Node.js
npx serve .

# Option 3: Using Live Server (VS Code extension)
# Right-click index.html and select "Open with Live Server"
```

Visit `http://localhost:8000` to view the website.

## 📊 Analytics Setup (Optional)

Add Google Analytics to track visitors:

```html
<!-- Add to <head> section -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_TRACKING_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_TRACKING_ID');
</script>
```

## 🌟 Features to Add

Consider adding these features for enhancement:
- **Contact Form**: Using Netlify Forms or Formspree
- **Dark Mode Toggle**: Theme switching capability
- **Blog Search**: Search functionality for blog posts
- **Project Filtering**: Filter projects by technology or category
- **Performance Metrics**: Core Web Vitals tracking

## 🤝 Contributing

If you find bugs or want to contribute improvements:
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Support

If you need help customizing the website:
- Check the [GitHub Issues](https://github.com/yourusername/yourusername.github.io/issues)
- Review the documentation
- Contact me through the website

---

**Built with ❤️ for ML Engineers and Data Scientists**

Start building your professional online presence today!