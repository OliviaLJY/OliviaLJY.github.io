# Olivia Li - Personal Portfolio Website

This is a modern, responsive personal portfolio website showcasing my experience as a Data Science & Machine Learning Engineer.

## 🌐 Live Website

Visit the live website at: [https://olivialjy.github.io](https://olivialjy.github.io)

## 🚀 Features

- **Modern Design**: Clean, professional layout optimized for HR and professionals
- **Responsive**: Fully responsive design that works on all devices
- **Interactive**: Smooth scrolling navigation and hover effects
- **Comprehensive**: Showcases work experience, projects, research, and technical skills
- **Fast Loading**: Optimized performance with minimal dependencies

## 📁 Project Structure

```
├── index.html          # Main HTML file
├── style.css           # CSS styling
├── script.js           # JavaScript functionality
└── README.md          # Project documentation
```

## 🛠️ Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript
- **Icons**: Font Awesome
- **Fonts**: Google Fonts (Inter)
- **Hosting**: GitHub Pages

## 📄 Sections

1. **Hero**: Introduction with call-to-action buttons
2. **About**: Brief personal introduction
3. **Experience**: Detailed work experience timeline
4. **Projects**: Key projects with technical details
5. **Research**: Research experience and publications
6. **Skills**: Technical skills organized by category
7. **Contact**: Contact information and social links

## 🔧 Setup & Deployment

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/OliviaLJY/OliviaLJY.github.io.git
   ```

2. Navigate to the project directory:
   ```bash
   cd OliviaLJY.github.io
   ```

3. Open `index.html` in your browser or use a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   ```

### GitHub Pages Deployment

1. Push your changes to the `main` branch
2. Go to repository Settings > Pages
3. Set source to "Deploy from a branch"
4. Select `main` branch and `/ (root)` folder
5. Your site will be available at `https://yourusername.github.io`

## 🎨 Customization

### Updating Contact Information

Edit the contact section in `index.html`:

```html
<a href="mailto:your.email@example.com" class="contact-link">
    <i class="fas fa-envelope"></i>
    <span>your.email@example.com</span>
</a>
```

### Adding New Experience

Add new experience items to the timeline in `index.html`:

```html
<div class="experience-item">
    <div class="experience-date">Month Year - Month Year</div>
    <div class="experience-content">
        <h3>Job Title</h3>
        <h4>Company Name</h4>
        <ul>
            <li>Achievement or responsibility</li>
        </ul>
        <div class="tech-tags">
            <span class="tag">Technology</span>
        </div>
    </div>
</div>
```

### Color Scheme

The primary color can be changed by updating the CSS custom properties in `style.css`:

```css
:root {
    --primary-color: #2563eb;  /* Blue */
    --primary-hover: #1d4ed8;
}
```

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to fork this repository and submit pull requests for any improvements.

## 📞 Contact

- **Email**: lij234152@gmail.com
- **Phone**: (434) 999-7600
- **LinkedIn**: [Jiayu Li](https://www.linkedin.com/in/jiayu-li-49441223a/)
- **GitHub**: [OliviaLJY](https://github.com/OliviaLJY?tab=repositories)

---

*Built with ❤️ by Olivia Li* 
