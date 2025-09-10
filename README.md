# Indrajit Biswas - Portfolio Website

A modern, responsive portfolio website showcasing my skills, projects, and achievements as a Computer Science Engineering student.

## 🌟 Features

- **Modern Design**: Clean, professional interface with smooth animations and transitions
- **Dark/Light Theme**: Toggle between themes with system preference detection
- **Fully Responsive**: Optimized for all devices - desktop, tablet, and mobile
- **Interactive Elements**: 
  - Typewriter effect for dynamic text
  - Particle cursor effects
  - Floating background elements
  - 3D hover effects on cards
- **Smooth Animations**: Intersection Observer API for scroll-triggered animations
- **Contact Form**: Functional contact form with validation
- **Performance Optimized**: Fast loading with optimized assets

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with custom properties, flexbox, and grid
- **JavaScript (ES6+)**: Interactive functionality and animations
- **Font Awesome**: Icons
- **Google Fonts**: Typography (Inter & Fira Code)

## 📱 Responsive Design

The website is fully responsive and tested across:
- Desktop (1200px+)
- Tablet (768px - 1024px)
- Mobile (320px - 768px)

## 🎨 Sections

1. **Hero/Home**: Introduction with animated typewriter effect
2. **About**: Personal information and statistics
3. **Skills**: Technical skills with animated progress bars
4. **Education**: Timeline of educational background
5. **Projects**: Showcase of key projects
6. **Achievements**: Awards and recognitions
7. **Video Demo**: Embedded project demonstration
8. **Contact**: Contact form and social links

## 🚀 Getting Started

### Prerequisites

- A modern web browser
- Basic web server (optional, for local development)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Indra-dev404/portfolio-website.git
```

2. Navigate to the project directory:
```bash
cd portfolio-website
```

3. Open `enhanced_portfolio.html` in your browser or set up a local server:

**Using Python (if installed):**
```bash
# Python 3
python -m http.server 8000

# Python 2
python -SimpleHTTPServer 8000
```

**Using Node.js (if installed):**
```bash
npx serve .
```

4. Visit `http://localhost:8000` in your browser

## 📁 File Structure

```
portfolio-website/
├── enhanced_portfolio.html    # Main HTML file
├── profile.jpg               # Profile image
├── photo2.jpg               # Additional photo
├── resume.pdf               # Resume file
├── icon.ico                 # Favicon
├── assets/
│   ├── images/
│   │   ├── mckvie.png       # Achievement logos
│   │   ├── iitm.png
│   │   ├── nitdgp.png
│   │   └── cmr.png
├── README.md               # This file
└── LICENSE                 # License file
```

## 🎯 Key Features Explained

### Theme System
- Automatic system theme detection
- Manual theme toggle
- Smooth theme transitions
- Persistent theme preference (ready for localStorage implementation)

### Performance Optimizations
- Lazy loading for images
- Efficient scroll event handling
- CSS animations instead of JavaScript where possible
- Minimal external dependencies

### Interactive Elements
- **Typewriter Effect**: Cycles through different roles/descriptions
- **Particle System**: Mouse-following particles for visual appeal
- **3D Card Effects**: Tilt effects on project cards
- **Progress Bars**: Animated skill level indicators
- **Counter Animations**: Animated statistics in about section

## 📧 Contact Form

The contact form includes:
- Client-side validation
- Email format validation
- Success/error notifications
- Loading states
- Form reset after submission

*Note: Backend integration required for actual email sending*

## 🔧 Customization

### Colors
Edit the CSS custom properties in the `:root` selector to change the color scheme:

```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #10b981;
    --accent-color: #f59e0b;
    /* ... other colors */
}
```

### Content
Update the HTML content in `enhanced_portfolio.html` to reflect your information:
- Personal details in the hero section
- Skills in the skills section
