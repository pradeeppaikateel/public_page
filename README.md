# Pradeep Pai Kateel - Interactive Resume

An interactive, modern resume website built for GitHub Pages.

## 🚀 Features

- **Modern Design**: Clean, professional layout with smooth animations
- **Dark/Light Mode**: Toggle between themes with automatic system preference detection
- **Fully Responsive**: Works beautifully on desktop, tablet, and mobile
- **Interactive Elements**:
  - Animated skill progress bars
  - Smooth scroll navigation
  - Timeline with hover effects
  - Card tilt effects
  - Animated counters
  - Parallax background effects
- **Performance Optimized**: Lazy loading, debounced scroll events
- **Accessible**: Semantic HTML, ARIA labels, keyboard navigation

## 📁 Project Structure

```
copilot_try/
├── index.html      # Main HTML file
├── styles.css      # All styling and animations
├── script.js       # Interactive functionality
└── README.md       # This file
```

## 🛠️ Deployment to GitHub Pages

### Option 1: Deploy from Repository Root

1. **Create a GitHub Repository**
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Interactive resume website"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   git push -u origin main
   ```

2. **Enable GitHub Pages**
   - Go to your repository on GitHub
   - Navigate to **Settings** → **Pages**
   - Under "Source", select **Deploy from a branch**
   - Select **main** branch and **/ (root)** folder
   - Click **Save**

3. **Access Your Site**
   - Your site will be live at: `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/`

### Option 2: Use as a Personal GitHub Pages Site

1. **Create a repository named `YOUR_USERNAME.github.io`**

2. Push your code to this repository

3. Your site will automatically be live at `https://YOUR_USERNAME.github.io/`

## 🎨 Customization

### Change Colors
Edit the CSS variables in `styles.css`:

```css
:root {
    --accent-primary: #6366f1;    /* Primary accent color */
    --accent-secondary: #8b5cf6;  /* Secondary accent color */
    /* ... other variables */
}
```

### Add Your Photo
Replace the icon in the hero section (`index.html`) with your photo:

```html
<div class="profile-avatar">
    <img src="your-photo.jpg" alt="Your Name">
</div>
```

### Update Content
All content is in `index.html`. Simply edit the text to update your information.

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contact

**Pradeep Pai Kateel**
- Email: pradeeppaikateel@gmail.com
- LinkedIn: [linkedin.com/in/pradeeppaikateel](https://linkedin.com/in/pradeeppaikateel/)
- Location: Hyderabad, India
