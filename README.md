# Personal Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. Features a clean design with smooth animations, mobile-first approach, and professional styling.

## 🚀 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: Hover effects, scroll animations, and mobile navigation
- **Contact Form**: Functional contact form with validation
- **Smooth Scrolling**: Seamless navigation between sections
- **Performance Optimized**: Fast loading with optimized assets

## 📁 Project Structure

```
portfolio-site/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
└── README.md          # Project documentation
```

## 🛠️ Setup Instructions

1. **Clone or Download**: Download the project files to your local machine
2. **Open in Browser**: Simply open `index.html` in your web browser
3. **Customize**: Edit the content in `index.html` to personalize your portfolio
4. **Deploy**: Upload the files to your web hosting service

## 🎨 Customization Guide

### Personal Information
Edit the following sections in `index.html`:

- **Name**: Replace "Your Name" with your actual name
- **Title**: Update the hero subtitle with your professional title
- **Description**: Modify the about section with your personal story
- **Contact Info**: Update email, phone, and location in the contact section

### Skills & Technologies
In the skills section, you can:
- Add/remove skill categories (Frontend, Backend, Tools)
- Update skill items with your specific technologies
- Change icons using Font Awesome classes

### Projects
For each project card:
- Update project title and description
- Add your actual project images (replace placeholder divs)
- Update technology tags
- Add real links to live demos and GitHub repositories

### Styling
In `styles.css`, you can customize:
- **Colors**: Update the gradient colors in CSS variables
- **Fonts**: Change the font family (currently using Inter)
- **Layout**: Modify spacing, padding, and grid layouts
- **Animations**: Adjust animation timing and effects

## 🎯 Sections Included

1. **Hero Section**: Eye-catching introduction with call-to-action buttons
2. **About Section**: Personal story with statistics
3. **Skills Section**: Organized by categories (Frontend, Backend, Tools)
4. **Projects Section**: Showcase of your work with descriptions
5. **Contact Section**: Contact form and social media links

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px
- **Small Mobile**: Below 480px

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Internet Explorer 11+

## 🚀 Deployment Options

### GitHub Pages
1. Create a new repository on GitHub
2. Upload your portfolio files
3. Go to Settings > Pages
4. Select source branch and save

### Netlify
1. Drag and drop your project folder to Netlify
2. Your site will be live instantly
3. Get a custom domain or use the provided URL

### Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in your project directory
3. Follow the prompts to deploy

## 📝 Customization Tips

### Adding Your Photo
Replace the placeholder div in the hero section:
```html
<div class="profile-placeholder">
    <img src="path/to/your/photo.jpg" alt="Your Name" style="width: 100%; height: 100%; object-fit: cover; border-radius: 50%;">
</div>
```

### Adding Project Images
Replace placeholder divs in project cards:
```html
<div class="project-image">
    <img src="path/to/project-image.jpg" alt="Project Name" style="width: 100%; height: 100%; object-fit: cover;">
</div>
```

### Updating Social Links
In the contact section, update the social media links:
```html
<a href="https://github.com/yourusername" class="social-link">
    <i class="fab fa-github"></i>
</a>
```

## 🎨 Color Scheme

The current color scheme uses:
- **Primary Gradient**: #667eea to #764ba2
- **Accent Gradient**: #ffd89b to #19547b
- **Background**: #f8f9fa
- **Text**: #333 (dark) and #666 (light)

## 📞 Contact Form

The contact form includes:
- Name, email, subject, and message fields
- Client-side validation
- Success/error notifications
- Form reset after successful submission

**Note**: The form currently shows a success message. To make it functional, you'll need to:
1. Set up a backend service (Node.js, PHP, etc.)
2. Configure email sending (SendGrid, Nodemailer, etc.)
3. Update the form action and method

## 🔍 SEO Optimization

To improve search engine visibility:
1. Add meta tags for description and keywords
2. Include Open Graph tags for social sharing
3. Add structured data markup
4. Optimize images with alt tags
5. Ensure proper heading hierarchy

## 📈 Performance Tips

- Compress images before uploading
- Minify CSS and JavaScript for production
- Use a CDN for external resources
- Enable browser caching
- Optimize font loading

## 🤝 Contributing

Feel free to fork this project and customize it for your needs. If you make improvements, consider sharing them with the community!

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Font Awesome for icons
- Google Fonts for typography
- Inter font family for clean design
- CSS Grid and Flexbox for layouts

---

**Happy coding! 🎉**

If you have any questions or need help customizing your portfolio, feel free to reach out! 