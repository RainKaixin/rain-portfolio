# Rain Wang Portfolio Website

A professional artist portfolio website inspired by Dylan Cole Studio's design aesthetic.

## 🎨 Design Features

- **Dark Minimal Theme**: Cinematic black background that highlights artwork
- **Tight Grid Layout**: Edge-to-edge artwork display with no gaps or spacing
- **Responsive Design**: Adapts seamlessly across all device sizes
- **Professional Typography**: Clean sans-serif fonts with proper hierarchy
- **Smooth Interactions**: Elegant hover effects and transitions

## 📁 Project Structure

```
portfolio_web/
├── index.html          # Main homepage
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
├── README.md           # This file
└── works_jpg/          # Artwork assets
    └── concept_art_works/  # 2D concept art works
```

## 🚀 Getting Started

1. **Open the website**: Simply open `index.html` in your web browser
2. **Local server** (recommended): Use a local server to avoid CORS issues with image loading

### Using a Local Server

**Option 1: Python**

```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

**Option 2: Node.js**

```bash
# Install http-server globally
npm install -g http-server

# Run server
http-server
```

**Option 3: Live Server (VS Code Extension)**

- Install "Live Server" extension in VS Code
- Right-click on `index.html` and select "Open with Live Server"

## 🎯 Current Features

### Homepage Layout

- **Header**: Fixed navigation with artist name and menu
- **Artwork Grid**: Dynamic loading of concept art works
- **Responsive**: Adapts to desktop, tablet, and mobile screens

### Navigation

- **Artwork**: Currently active (homepage)
- **About**: Placeholder for future implementation
- **Social Links**: Instagram, ArtStation, Behance (placeholder links)

### Artwork Display

- **Source**: Loads from `works_jpg/concept_art_works/` folder
- **Layout**: Tight grid with no spacing between images
- **Loading**: Smooth fade-in effect for images
- **Error Handling**: Graceful fallback for missing images

## 🎨 Artwork Categories

Currently displaying works from:

- **Concept Art Works**: 2D concept art and environment designs
- **File Types**: JPG and PNG formats
- **Content**: Sci-fi environments, historical symbolism, mythological storytelling

## 📱 Responsive Breakpoints

- **Desktop**: 3+ columns, 300px row height
- **Tablet**: 2-3 columns, 280px row height
- **Mobile**: 1 column, 200-250px row height

## 🔧 Technical Details

### CSS Grid System

- Uses CSS Grid for responsive artwork layout
- `gap: 0` ensures tight, edge-to-edge display
- `object-fit: cover` maintains aspect ratio consistency

### JavaScript Features

- Dynamic image loading from local folder
- Responsive grid adjustments
- Smooth navigation interactions
- Image loading optimization

### Performance

- Optimized image loading with fade-in effects
- Minimal animations for smooth performance
- Efficient DOM manipulation

## 🚧 Future Enhancements

- **About Page**: Artist biography and information
- **Artwork Detail Views**: Modal or dedicated pages for individual works
- **Additional Categories**: 3D works, illustrations, fine art
- **Contact Information**: Professional contact details
- **SEO Optimization**: Meta tags and structured data

## 🎯 Design Philosophy

This portfolio follows the cinematic, professional aesthetic of Dylan Cole Studio:

- **Minimalism**: Clean, uncluttered design
- **Visual Impact**: Artwork takes center stage
- **Professional Polish**: High-end production design feel
- **User Experience**: Intuitive navigation and smooth interactions

## 📄 License & Copyright

### Website Code

- This website code is open source and available under MIT License
- Feel free to use the code structure for your own projects
- Please give credit if you use significant portions of this code

### Artwork & Content

- **ALL ARTWORK IS COPYRIGHTED** © Rain Wang (Shu Wang)
- All images, videos, and creative content are the exclusive property of Rain Wang
- **Unauthorized use, reproduction, or distribution is strictly prohibited**
- For licensing inquiries, contact: rainshuwangca@gmail.com

### Legal Notice

- This portfolio showcases original artwork created by Rain Wang
- Any unauthorized use of these works may result in legal action
- Respect for intellectual property rights is expected

---

**Built with**: HTML5, CSS3, Vanilla JavaScript  
**Design Inspiration**: Dylan Cole Studio  
**Artist**: Rain Wang - Concept Artist · Compositor · 3D Environment Artist
