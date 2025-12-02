# Jujutsu Kaisen Themed 3D Wedding Invitation

## Overview
This is a fully interactive 3D wedding invitation website with an anime Jujutsu Kaisen theme featuring Gojo Satoru as the main design motif. The website implements WebGL/Three.js for 3D effects and includes URL parameter functionality for dynamic guest name customization.

## Features

### Design & Theme
- **Jujutsu Kaisen Theme**: Gojo's Infinity Domain color scheme (blue, purple, red)
- **Responsive Design**: Works on all devices from mobile to desktop
- **Anime-style Typography**: Custom fonts and styling to match the theme
- **3D Elements**: Three.js implementation for cover page animation
- **Custom Cursor**: Six Eyes theme inspired cursor effects

### Interactive Elements
- **Cover Page Lock System**: 
  - Full-screen 3D animation of Gojo's Infinity Domain effect
  - Displays "The Wedding of [Groom's Name] & [Bride's Name]"
  - Dynamic guest display: "Untuk: [Guest Name]" from URL parameter
  - Central "Buka Undangan" button with hover animation
  - Main content remains hidden until user clicks the button

### Sections
1. **Home**: Opening greeting, biodata cards for groom and bride, 3D countdown timer
2. **Wedding Ceremony & Reception**: Jujutsu-themed titles with event details and maps
3. **Gallery**: 3D photo grid with hover effects and lightbox functionality
4. **Our Story**: Vertical timeline with parallax effect
5. **Guest Book**: Real-time comment system with localStorage
6. **RSVP**: Form with WhatsApp integration
7. **Love Gift**: Bank account displays with copy-to-clipboard functionality
8. **Footer**: Credit and thank you message

### Technical Features
- **URL Parameter Handling**: ?guest=Name auto-populates guest name
- **LocalStorage**: For guest book persistence
- **WhatsApp API Integration**: For RSVP submissions
- **Clipboard API**: For bank account copying
- **Intersection Observer**: For scroll animations
- **Responsive Design**: Mobile-first approach with breakpoints

## How to Use

### Basic Usage
1. Open `index.html` in a web browser
2. Access with URL parameter: `website.com?guest=YourName`
3. Click "Buka Undangan" to unlock content

### Customization
- Edit names, dates, and details in the HTML
- Update bank account numbers in the JavaScript
- Modify the wedding date in the countdown function
- Change Instagram handles and other details

### URL Parameters
- `?guest=Name` - Sets the guest name displayed on the cover page

## Technical Implementation

### Dependencies
- Three.js (via CDN) - For 3D graphics and animations
- Font Awesome (via CDN) - For icons

### Color Palette
- Primary: #4169e1 (Gojo Blue)
- Secondary: #9370db (Infinity Purple)
- Accent: #ff4757 (Cursed Red)
- Background: #0a0a2a to #1a1a3a gradient

### Responsive Breakpoints
- Mobile: < 768px
- Tablet: 768px - 1024px
- Desktop: > 1024px

## Sections Details

### Cover Page
- 3D floating geometric shapes (Gojo's Infinity Domain effect)
- Blue energy particles animation
- Dynamic guest name display
- "Buka Undangan" button with pulse animation

### Home Section
- Parent blessing message
- Biodata cards with anime-style portraits
- Instagram links
- 3D countdown timer with floating digits

### Ceremony & Reception
- "Domain Expansion: Sacred Vows" for ceremony
- "Domain Expansion: Celebration Infinity" for reception
- Date, time, venue, and address details
- Interactive 3D maps

### Gallery
- "Cursed Technique Showcase" caption
- Hover effects on images
- Lightbox functionality

### Our Story
- Vertical timeline with parallax effect
- "First Encounter", "Training Together", "Special Grade Bond", "Eternal Vow" sections
- Large images with bold titles

### Guest Book
- Real-time comment display with anime-style speech bubbles
- LocalStorage implementation
- Form with name and message fields

### RSVP
- WhatsApp integration
- Pre-filled messages with guest name
- Attendance and guest count options

### Love Gift
- Two bank account displays (BCA and Mandiri)
- Copy-to-clipboard functionality
- Success notifications

## Browser Compatibility
- Modern browsers with WebGL support
- Chrome, Firefox, Safari, Edge (latest versions)
- Mobile browsers (iOS Safari, Chrome for Android)

## Performance Considerations
- Optimized 3D animations with Three.js
- Responsive images
- Efficient JavaScript with event delegation
- CSS animations instead of JavaScript where possible

## Anime-Specific Elements
- Gojo's Infinity Domain visual effects
- Cursed Energy particle animations
- Jujutsu terminology integration
- Character-themed design elements
- Anime-style illustrations and icons

## License
This project is created for personal use. Please credit the original author if you use this as inspiration for your own project.

## Credits
Created by bimaraweb.com
