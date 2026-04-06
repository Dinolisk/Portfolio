# Frontend Developer Portfolio

A modern, responsive portfolio website built with HTML, CSS, and JavaScript, featuring TailwindCSS for styling and smooth animations.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with gradient accents
- **Smooth Animations**: Parallax effects, fade-in animations, and hover states
- **Interactive Navigation**: Sticky header with active state indicators
- **Project Showcase**: Beautiful card layout for displaying projects
- **Skills Section**: Animated skill bars showing proficiency levels
- **Contact Section**: Easy ways for potential clients to reach you
- **Mobile Menu**: Hamburger menu for mobile devices

## Technologies Used

- **HTML5**: Semantic markup
- **TailwindCSS**: Utility-first CSS framework
- **JavaScript ES6+**: Modern JavaScript features
- **Font Awesome**: Icon library
- **Intersection Observer API**: For scroll animations

## Getting Started

1. Clone or download this repository
2. Open `index.html` in your web browser
3. Customize the content with your personal information

## Customization

### Personal Information

Update the following placeholders in `index.html`:

- Replace "Your Name" with your actual name
- Update email address: `your.email@example.com`
- Update phone number: `+1 (234) 567-890`
- Add your social media links

### Projects Section

Modify the project cards in the projects section:

```html
<div class="card-hover bg-gray-50 rounded-lg overflow-hidden">
    <div class="h-48 bg-gradient-to-br from-purple-400 to-pink-400"></div>
    <div class="p-6">
        <h3 class="text-xl font-bold mb-2">Your Project Name</h3>
        <p class="text-gray-600 mb-4">Project description</p>
        <div class="flex flex-wrap gap-2 mb-4">
            <span class="px-3 py-1 bg-purple-100 text-purple-600 rounded-full text-sm">Technology</span>
        </div>
        <div class="flex space-x-4">
            <a href="#" class="text-purple-600 hover:text-purple-700">
                <i class="fas fa-external-link-alt"></i> Live Demo
            </a>
            <a href="#" class="text-purple-600 hover:text-purple-700">
                <i class="fab fa-github"></i> Code
            </a>
        </div>
    </div>
</div>
```

### Skills Section

Update the skill bars with your actual skill levels:

```html
<div>
    <div class="flex justify-between mb-2">
        <span>Your Skill</span>
        <span class="text-purple-600">85%</span>
    </div>
    <div class="w-full bg-gray-200 rounded-full h-3">
        <div class="skill-bar bg-purple-600 h-3 rounded-full" style="width: 85%"></div>
    </div>
</div>
```

### Colors and Styling

The main color scheme uses purple gradients. To customize:

1. Change gradient colors in the `.gradient-text` class
2. Update hover colors throughout the HTML
3. Modify skill bar colors in the CSS

## Deployment

### GitHub Pages

1. Push the code to a GitHub repository
2. Go to repository settings
3. Enable GitHub Pages
4. Select the main branch as source

### Netlify

1. Drag and drop the project folder to Netlify
2. Or connect your GitHub repository

### Vercel

1. Import the project from GitHub
2. Deploy with one click

## File Structure

```
Portfolio/
├── index.html          # Main HTML file
├── script.js           # JavaScript functionality
├── README.md           # This file
└── assets/             # Images and other assets (if needed)
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Performance

- Optimized images (add your own optimized images)
- Minified CSS and JavaScript (can be further optimized)
- Lazy loading ready (implement as needed)
- SEO friendly meta tags

## Contributing

Feel free to fork this project and make it your own! If you find any issues or have suggestions for improvements, please open an issue.

## License

This project is open source and available under the [MIT License](LICENSE).

---

**Built with ❤️ for frontend developers**
