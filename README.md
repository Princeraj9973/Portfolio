# 3D Animated Portfolio

A stunning, modern portfolio website with advanced 3D animations and interactive elements.

## Features

### 🎨 Visual Effects
- **3D Card Animations**: All cards (skills, projects, achievements) have 3D tilt effects on hover
- **Glitch Effect**: Eye-catching glitch animation on the main heading
- **Gradient Backgrounds**: Beautiful gradient overlays throughout
- **Particle Effects**: Dynamic particles on skill card interactions
- **Cursor Trail**: Smooth cursor trail effect for enhanced interactivity
- **Scroll Progress Bar**: Visual indicator of page scroll progress

### 📱 Responsive Design
- Fully responsive layout that works on all devices
- Mobile-friendly navigation menu
- Optimized for tablets and desktops

### 🖼️ Photo Upload Feature
- Click on the profile image to upload your own photo
- Photo is saved in browser's localStorage
- Hover over the image to see upload overlay

### 📊 Organized Sections
1. **Home/Hero**: Profile photo, name, tagline, and contact links
2. **About**: Brief introduction
3. **Education**: Timeline view of educational qualifications
4. **Skills**: Grid of technical skills with 3D cards
5. **Projects**: Detailed project showcases
6. **Achievements**: Certifications and sports achievements
7. **Contact**: Contact information cards

### ⚡ Interactive Elements
- Smooth scrolling navigation
- Scroll-triggered animations
- Hover effects on all interactive elements
- Dynamic color changes
- Typing effect on tagline
- Floating animations

## How to Use

1. **Open the Portfolio**
   - Simply open `index.html` in your web browser
   - No server required - it's a static website

2. **Add Your Photo**
   - Hover over the profile image in the hero section
   - Click when you see the upload overlay
   - Select your photo from your computer
   - The photo will be saved automatically

3. **Customize Content**
   - Edit `index.html` to update your personal information
   - Modify contact links (email, GitHub, LinkedIn)
   - Add or remove projects, skills, and achievements

4. **Customize Styling**
   - Colors can be changed in `style.css` under `:root` variables
   - Adjust animation speeds and effects as needed

## File Structure

```
Portfolio new/
│
├── index.html          # Main HTML structure
├── style.css           # All styles and 3D animations
├── script.js           # Interactive JavaScript features
├── assets/             # Folder for images
│   └── profile.jpg     # Place your profile photo here
└── README.md           # This file
```

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Advanced animations, gradients, transforms
- **JavaScript**: Interactive features and DOM manipulation
- **Font Awesome**: Icons
- **LocalStorage**: Photo persistence

## Browser Support

Works best on modern browsers:
- Chrome (recommended)
- Firefox
- Safari
- Edge

## Customization Guide

### Change Colors
Edit the CSS variables in `style.css`:
```css
:root {
    --primary-color: #00f5ff;     /* Cyan */
    --secondary-color: #ff00ff;   /* Magenta */
    --accent-color: #ffd700;      /* Gold */
}
```

### Update Personal Information
1. Contact details in the hero section
2. Education timeline entries
3. Skills in the skills grid
4. Project details
5. Achievements

### Add New Sections
Follow the existing pattern in `index.html` and add corresponding styles in `style.css`.

## Performance

- Optimized animations using CSS transforms
- Efficient JavaScript with event delegation
- Minimal external dependencies
- Fast loading time

## License

Free to use and modify for personal and commercial projects.

---

**Created with ❤️ using 3D CSS animations and modern web technologies**
