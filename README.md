# Professional Portfolio - Suman Rana

A modern, professional portfolio website showcasing my skills as a Laravel Developer, WordPress Developer, and SEO Analyst.

## 🚀 Features

- **Modern Design**: Clean, professional interface with gradient accents and smooth animations
- **Fully Responsive**: Optimized for all devices (desktop, tablet, mobile)
- **Interactive Elements**: Typing effect, skill bars, smooth scrolling, and parallax effects
- **SEO Optimized**: Semantic HTML, meta tags, and performance-focused
- **Accessibility**: WCAG compliant with keyboard navigation support
- **Fast Loading**: Optimized assets and efficient code

## 📁 Project Structure

```
professional-portfolio/
├── index.html              # Main HTML file
├── assets/
│   ├── css/
│   │   ├── main.css       # Main stylesheet with design system
│   │   └── responsive.css # Responsive breakpoints
│   └── js/
│       └── main.js        # Interactive functionality
└── README.md              # This file
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with CSS Grid, Flexbox, and animations
- **JavaScript**: Vanilla JS for interactivity
- **Font Awesome**: Icon library
- **Google Fonts**: Inter & JetBrains Mono

## 🎨 Design Features

- **Color Scheme**: Dark theme with vibrant gradient accents
- **Typography**: Inter for body text, JetBrains Mono for code
- **Animations**: Smooth transitions, fade-ins, and parallax effects
- **Glassmorphism**: Modern frosted glass effects
- **Gradient Orbs**: Dynamic floating background elements

## 📱 Sections

1. **Hero**: Eye-catching introduction with typing effect
2. **About**: Personal information and statistics
3. **Skills**: Technical expertise with animated progress bars
4. **Experience**: Timeline of work history and education
5. **Portfolio**: Featured projects showcase
6. **Contact**: Contact form and social links

## 🚀 Getting Started

1. Clone or download this repository
2. Open `index.html` in your browser
3. Customize the content with your own information

## ✏️ Customization

### Update Personal Information

Edit the following in `index.html`:

- Name and title in the hero section
- About section details
- Skills and percentages
- Work experience timeline
- Project information
- Contact details and social links

### Modify Colors

Update CSS variables in `assets/css/main.css`:

```css
:root {
  --primary: #6366f1;
  --secondary: #8b5cf6;
  --accent: #ec4899;
  /* ... more variables */
}
```

### Add Projects

Add new project cards in the portfolio section:

```html
<div class="project-card">
  <!-- Project content -->
</div>
```

## 📧 Contact Form

The contact form currently uses a simulated submission. To make it functional:

1. Set up a backend endpoint (PHP, Node.js, etc.)
2. Update the form submission handler in `assets/js/main.js`
3. Replace the simulated API call with your actual endpoint

Example PHP integration:
```javascript
const response = await fetch('contact.php', {
  method: 'POST',
  body: JSON.stringify(data),
  headers: { 'Content-Type': 'application/json' }
});
```

## 🌐 Deployment

### GitHub Pages
1. Push to GitHub repository
2. Go to Settings > Pages
3. Select main branch
4. Your site will be live at `https://username.github.io/repo-name`

### Netlify
1. Drag and drop the folder to Netlify
2. Or connect your GitHub repository
3. Automatic deployment on every push

### Traditional Hosting
1. Upload all files via FTP
2. Ensure proper file permissions
3. Point domain to the directory

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 📄 License

This project is open source and available for personal and commercial use.

## 👨‍💻 Author

**Suman Rana**
- Email: sumanrana2062@gmail.com
- GitHub: [@Suman-Rana-Magar](https://github.com/Suman-Rana-Magar)
- LinkedIn: [suman-rana-334ba02a3](https://linkedin.com/in/suman-rana-334ba02a3/)

---

Built with ❤️ in Kathmandu, Nepal
