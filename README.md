# Personal Portfolio Website

A clean, modern, and fully responsive personal portfolio website built with pure HTML, CSS, and JavaScript.

## 🌟 Features

- **Modern UI Design**: Clean and professional interface
- **Fully Responsive**: Works perfectly on all devices (mobile, tablet, desktop)
- **Smooth Animations**: Fade-in effects, hover animations, and smooth scrolling
- **Interactive Navigation**: Mobile-friendly hamburger menu
- **Project Showcase**: Beautiful project cards with hover effects
- **Skills Section**: Animated progress bars showing skill levels
- **Contact Form**: Functional contact form with validation
- **Scroll Effects**: Navigation bar shadow, active link highlighting, and scroll-to-top button

## 📁 Folder Structure

```
portfolio/
│
├── index.html          # Main HTML file (structure of website)
├── css/
│   └── style.css       # Styling and animations
├── js/
│   └── script.js       # JavaScript for interactivity
├── images/             # Folder for all images
│   ├── profile.jpg     # Your profile photo
│   ├── about.jpg       # About section image
│   ├── project1.jpg    # Project 1 image
│   ├── project2.jpg    # Project 2 image
│   └── project3.jpg    # Project 3 image
│
└── README.md           # This file (documentation)
```

## 🚀 How to Use

### Option 1: Open Locally
1. Download all the files maintaining the folder structure
2. Add your own images to the `images` folder:
   - `profile.jpg` - Your profile photo (recommended: 500x500px)
   - `about.jpg` - About section image (recommended: 800x600px)
   - `project1.jpg`, `project2.jpg`, `project3.jpg` - Project screenshots (recommended: 800x600px)
3. Open `index.html` in any web browser

### Option 2: Host Online
1. Upload all files to a web hosting service (GitHub Pages, Netlify, Vercel)
2. Your portfolio will be live on the internet!

## ✏️ Customization Guide

### 1. Personal Information (index.html)
- **Line 36-38**: Change name and tagline
  ```html
  <h1 class="name">Your Name</h1>
  <p class="tagline">Your Title | Your Specialty</p>
  ```

- **Line 48-50**: Update About Me text
- **Line 137-139**: Update contact information (email, phone, location)

### 2. Projects (index.html)
- **Line 62-92**: Edit project cards
  - Change project titles (h3 tags)
  - Update descriptions (p tags)
  - Modify technology tags (span tags)
  - Add your project links

### 3. Skills (index.html)
- **Line 100-126**: Update skill names and percentages
  - Change skill names in span tags
  - Update `data-progress` values (0-100)

### 4. Colors (css/style.css)
- **Line 9-15**: Change color scheme
  ```css
  :root {
      --primary-color: #6366f1;    /* Main color */
      --secondary-color: #8b5cf6;  /* Accent color */
      --text-dark: #1f2937;        /* Text color */
  }
  ```

### 5. Fonts (css/style.css)
- **Line 26**: Change font family
  ```css
  font-family: 'Your Font', sans-serif;
  ```

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px
- **Small Mobile**: Below 480px

## 🎨 Sections Explained

### 1. Navigation Bar
- Fixed at the top of the page
- Smooth scroll to sections
- Hamburger menu for mobile devices
- Active link highlighting

### 2. Home Section
- Eye-catching gradient background
- Profile photo with floating animation
- Name and tagline
- Call-to-action button

### 3. About Section
- Two-column layout (text and image)
- Introduction text
- Hover effect on image

### 4. Projects Section
- Grid layout of project cards
- Hover effects (lift and scale)
- Project images, titles, descriptions
- Technology tags
- Project links

### 5. Skills Section
- Three skill categories
- Animated progress bars
- Percentage indicators
- Icon for each category

### 6. Contact Section
- Contact form with validation
- Contact information cards
- Social media links
- Hover effects

### 7. Footer
- Copyright information

## 🔧 JavaScript Features (script.js)

1. **Mobile Menu Toggle**: Opens/closes navigation on mobile
2. **Smooth Scrolling**: Smooth navigation between sections
3. **Scroll Effects**: Navbar shadow, active link highlighting
4. **Intersection Observer**: Fade-in animations when scrolling
5. **Skill Bar Animation**: Progress bars animate when visible
6. **Form Validation**: Checks if all form fields are filled
7. **Scroll to Top Button**: Appears after scrolling down
8. **Typing Effect**: Animated tagline typing
9. **Cursor Trail**: Decorative mouse trail effect

## 🎯 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## 📝 Tips for Beginners

### Understanding HTML (index.html)
- HTML creates the structure of your website
- `<section>` tags divide your page into different parts
- `<div>` tags are containers for grouping content
- `<h1>`, `<h2>`, `<h3>` are headings (bigger to smaller)
- `<p>` tags contain paragraphs of text
- `<a>` tags create links
- `<img>` tags display images

### Understanding CSS (style.css)
- CSS styles your HTML elements (colors, sizes, positions)
- `.class-name` targets elements with that class
- `#id-name` targets elements with that ID
- `:hover` applies styles when you hover over an element
- `@media` creates responsive designs for different screen sizes
- `@keyframes` creates animations

### Understanding JavaScript (script.js)
- JavaScript adds interactivity to your website
- `querySelector` finds HTML elements
- `addEventListener` waits for user actions (clicks, scrolls)
- `classList.toggle` adds/removes CSS classes
- `setTimeout` delays code execution
- Functions are reusable blocks of code

## 🐛 Common Issues & Solutions

**Issue**: Images not showing
- **Solution**: Make sure image files are in the `images` folder with correct names

**Issue**: Website looks broken on mobile
- **Solution**: Make sure viewport meta tag is in HTML head (already included)

**Issue**: JavaScript not working
- **Solution**: Check browser console for errors (F12 key)

**Issue**: Animations not smooth
- **Solution**: Clear browser cache and refresh

## 🎓 Next Steps

Once you're comfortable with this portfolio:
1. Add a blog section
2. Integrate a real contact form backend (FormSpree, EmailJS)
3. Add dark mode toggle
4. Create more project pages
5. Add testimonials section
6. Implement loading animations

## 📚 Learning Resources

- **HTML**: [MDN Web Docs - HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- **CSS**: [MDN Web Docs - CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
- **JavaScript**: [MDN Web Docs - JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- **Responsive Design**: [CSS-Tricks - A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

## 📄 License

Free to use for personal and commercial projects.

## 🤝 Credits

Created as a learning project for beginners.

---

**Happy Coding! 🚀**
