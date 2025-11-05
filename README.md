# Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. Perfect for showcasing your projects, skills, and experience.

## Features

- 🎨 Modern and clean design with gradient accents
- 📱 Fully responsive layout (mobile, tablet, desktop)
- 🌙 Dark theme with smooth animations
- 🚀 Fast and lightweight
- 📧 Contact form section
- 💼 Project showcase cards
- 🛠️ Skills and technologies display
- 🔗 Social media links

## Sections

1. **Home/Hero** - Eye-catching introduction with call-to-action buttons
2. **About** - Personal information and statistics
3. **Projects** - Showcase of your work with tags and links
4. **Skills** - Display of your technical skills organized by category
5. **Contact** - Contact information and form

## Customization

### Update Personal Information

Edit `index.html` to customize:

- **Name**: Replace "Your Name" in the hero section and footer
- **Title/Role**: Update "Full Stack Developer | Designer | Problem Solver"
- **About Text**: Modify the about section paragraphs
- **Statistics**: Update project count, years of experience, etc.
- **Contact Info**: Add your email, phone, and location
- **Social Links**: Update href attributes with your social media profiles

### Update Projects

In the projects section, modify each project card with:
- Project name
- Description
- Technologies used (tags)
- Live demo and GitHub links

### Update Skills

Edit the skills section to add or remove:
- Frontend technologies
- Backend technologies
- Tools and platforms

### Color Scheme

To change colors, edit the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #8b5cf6;
    --dark-bg: #0f172a;
    --light-bg: #1e293b;
    --text-primary: #f1f5f9;
    --text-secondary: #cbd5e1;
}
```

## Local Development

1. Open `index.html` in your web browser
2. Or use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js (http-server)
   npx http-server
   ```

## Deployment to GitHub Pages

### Method 1: Direct Upload

1. Create a new repository on GitHub
2. Upload all files to the repository
3. Go to Settings → Pages
4. Select the branch (usually `main`) and root folder
5. Click Save
6. Your site will be available at `https://yourusername.github.io/repository-name`

### Method 2: Using Git

```bash
# Initialize git repository
git init

# Add all files
git add .

# Commit changes
git commit -m "Initial commit"

# Add remote repository
git remote add origin https://github.com/yourusername/repository-name.git

# Push to GitHub
git branch -M main
git push -u origin main
```

Then enable GitHub Pages in repository settings.

### Custom Domain (Optional)

1. Add a `CNAME` file with your domain name
2. Configure DNS settings with your domain provider
3. Enable custom domain in GitHub Pages settings

## Contact Form Integration

The contact form is currently a demo. To make it functional, integrate with:

- **Formspree**: https://formspree.io/
- **EmailJS**: https://www.emailjs.com/
- **Netlify Forms**: If deploying to Netlify
- **Google Forms**: Embed a Google Form

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

Feel free to use this template for your personal portfolio. No attribution required.

## Credits

- Icons: Font Awesome
- Fonts: System fonts (Segoe UI)

---

Made with ❤️ for GitHub Pages
