# Nurxan Baydjayev - Personal Portfolio Website

A professional, fully responsive multilingual personal portfolio website built with pure HTML, CSS, and JavaScript.

## 🌟 Features

### ✨ Core Features
- **100% Frontend Only** - No backend or database required
- **Multilingual Support** - 4 languages (Turkmen 🇹🇲, Uzbek 🇺🇿, English 🇬🇧, Russian 🇷🇺)
- **Auto Language Detection** - Detects browser language and defaults to Turkmen
- **Dark/Light Mode** - Toggle with saved preference
- **Fully Responsive** - Works on all devices (mobile, tablet, desktop)
- **Smooth Animations** - Scroll animations, fade-ins, hover effects
- **GitHub Integration** - Auto-fetches projects from GitHub API

### 📱 Sections
1. **Header** - Fixed navigation with language switcher and theme toggle
2. **Hero** - Animated background with typing animation
3. **About** - Professional bio with stats counter
4. **Skills** - Progress bars with animated percentages
5. **Projects** - Auto-loaded from GitHub API
6. **Experience** - Timeline with professional history
7. **Services** - Service cards with descriptions
8. **Testimonials** - Client reviews with ratings
9. **Blog** - Sample blog posts
10. **Contact** - Contact form and social links
11. **Footer** - Social links and scroll-to-top button

### 🎨 Design Features
- Modern gradient backgrounds
- Floating animated shapes
- Smooth hover effects
- Card-based UI design
- Professional typography
- Soft shadows and rounded corners

## 🚀 Deployment

### Deploy to Vercel
1. Push your code to GitHub
2. Visit [vercel.com](https://vercel.com)
3. Click "New Project"
4. Import your GitHub repository
5. Deploy!

### Alternative Hosting
- GitHub Pages
- Netlify
- Any static hosting service

## 📂 File Structure

```
PORTFOLIO/
├── index.html      # Main HTML structure
├── styles.css      # All styles and animations
├── script.js       # JavaScript functionality and translations
└── README.md       # Documentation
```

## 🌐 Supported Languages

- **Turkmen (TM)** 🇹🇲 - Default language
- **Uzbek (UZ)** 🇺🇿
- **English (EN)** 🇬🇧
- **Russian (RU)** 🇷🇺

## 🎯 Customization

### Update Personal Information
Edit the `translations` object in `script.js` to update:
- Bio text
- Experience
- Services
- Testimonials
- Blog posts

### Change Colors
Modify CSS variables in `styles.css`:
```css
:root {
    --primary-color: #4A90E2;
    --secondary-color: #7B9FD6;
    --accent-color: #AED4E6;
}
```

### GitHub Username
Update GitHub API call in `script.js`:
```javascript
const response = await fetch('https://api.github.com/users/YOUR_USERNAME/repos');
```

## 📧 Contact

- **Telegram**: [@baydjayevv](https://t.me/baydjayevv)
- **Email**: nurxan314@gmail.com
- **GitHub**: [baydjayevv](https://github.com/baydjayevv)

## 📄 License

© 2025 Nurxan Baydjayev — All rights reserved.

## 🛠️ Technologies Used

- HTML5
- CSS3 (Grid, Flexbox, Animations)
- Vanilla JavaScript (ES6+)
- GitHub API

---

**Made with ❤️ by Nurxan Baydjayev**
