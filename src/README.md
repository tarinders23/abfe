# Abhath Analytics Website

A professional, modern multi-page landing website for Abhath Analytics - a premier market research company.

## 🚀 Features

- **Modern Design**: Clean, professional design with gradient accents and smooth animations
- **Fully Responsive**: Mobile-first design that works perfectly on all devices
- **Multiple Pages**: 
  - Homepage (index.html)
  - Service Pages (CATI, Online Survey, Phone to Web, IDI, F2F, Data Processing)
  - About Us
  - Contact Us with functional form
- **Tailwind CSS**: Built with Tailwind CSS for modern styling
- **Animations**: Smooth transitions and animations for enhanced user experience
- **Stock Images**: Professional images from Unsplash
- **Interactive Components**: Dropdown menus, mobile navigation, contact form

## 📁 File Structure

```
src/
├── index.html              # Homepage
├── about.html              # About Us page
├── contact.html            # Contact Us page with form and map
├── cati.html              # CATI Services page
├── online-survey.html     # Online Survey Services page
├── phone-to-web.html      # Phone to Web Services page
├── idi.html               # In-Depth Interviews page
├── f2f.html               # Face-to-Face Interviews page
└── data-processing.html   # Data Processing & Analysis page
```

## 🎨 Design Features

### Color Scheme
- Primary: Blue (#2563eb to #1e40af)
- Secondary: Purple (#7c3aed to #6d28d9)
- Accent colors for different services (Green, Orange, Pink, etc.)

### Components
- Fixed navigation bar with dropdown menus
- Hero sections with gradient backgrounds
- Service cards with hover effects
- Statistics counters
- Contact form with validation
- Google Maps integration
- Responsive footer

### Animations
- Fade-in animations on page load
- Hover lift effects on cards
- Pulse animations on decorative elements
- Smooth transitions on all interactive elements
- Mobile menu slide-in

## 🌐 Pages Overview

### Homepage (index.html)
- Hero section with call-to-action buttons
- About section
- Services overview with 6 service cards
- Why Choose Us section
- Statistics section
- Call-to-action section

### Service Pages
Each service page includes:
- Hero section with service icon
- Detailed service description
- Key features and benefits
- Process/methodology breakdown
- Advantages section
- Call-to-action

### About Page (about.html)
- Company overview
- Core values
- What sets us apart
- Statistics
- Our approach
- Team section ready for expansion

### Contact Page (contact.html)
- Contact information
- Office address and details
- Business hours
- Contact form
- Google Maps integration
- Service areas

## 💻 Technologies Used

- **HTML5**: Semantic markup
- **Tailwind CSS**: Utility-first CSS framework via CDN
- **Font Awesome**: Icon library
- **Google Fonts**: Typography
- **Unsplash**: Stock images

## 🚀 How to Use

### Option 1: Open Directly in Browser
1. Navigate to the `src` folder
2. Double-click `index.html` to open in your default browser
3. All pages are linked and ready to navigate

### Option 2: Use a Local Server (Recommended)
Using Python:
```bash
cd src
python -m http.server 8000
```
Then open `http://localhost:8000` in your browser

Using Node.js (http-server):
```bash
cd src
npx http-server
```

### Option 3: Use VS Code Live Server
1. Install "Live Server" extension in VS Code
2. Right-click `index.html`
3. Select "Open with Live Server"

## 📱 Responsive Breakpoints

- Mobile: < 768px
- Tablet: 768px - 1024px
- Desktop: > 1024px

## 🎯 Key Features by Section

### Navigation
- Fixed header that becomes translucent on scroll
- Dropdown menu for services
- Mobile hamburger menu
- Smooth transitions

### Forms
- Contact form with validation
- Success message on submission
- Required field indicators
- Professional styling

### Images
All images are loaded from Unsplash via CDN:
- Data analytics visualizations
- Team collaboration photos
- Office and business scenes
- Technology and research imagery

## 🔧 Customization

### Update Contact Information
Edit the contact details in `contact.html` and footer sections:
- Email: support@abhathanalytics.com
- Phone: +91-8595788768
- Address: Update Google Maps embed URL

### Change Colors
The website uses Tailwind CSS classes. To change colors, update:
- `from-blue-600 to-purple-600` - Primary gradient
- `bg-blue-600` - Primary buttons
- Service-specific colors in respective pages

### Add Content
- All content is in standard HTML
- Add new sections by copying existing patterns
- Maintain consistent spacing with Tailwind classes

## 🌟 Best Practices Implemented

1. **SEO-Friendly**: Meta tags, semantic HTML, descriptive titles
2. **Accessibility**: ARIA labels, alt text for images, semantic structure
3. **Performance**: CDN resources, optimized images, minimal JavaScript
4. **Mobile-First**: Responsive design prioritizing mobile experience
5. **Clean Code**: Well-organized, commented, easy to maintain

## 📞 Contact Form Integration

The contact form currently shows a success message on submission. To connect it to a backend:

1. **Using Formspree**:
```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

2. **Using EmailJS**:
Add EmailJS script and update the JavaScript in contact.html

3. **Custom Backend**:
Update the form submission handler to POST to your API endpoint

## 🗺️ Google Maps

To update the map location:
1. Go to Google Maps
2. Find your location
3. Click "Share" → "Embed a map"
4. Copy the iframe code
5. Replace the iframe in `contact.html`

## 📈 Future Enhancements

- Add blog section
- Implement case studies page
- Add testimonials slider
- Integrate with analytics (Google Analytics)
- Add live chat widget
- Create careers page
- Add portfolio/past projects showcase

## 🐛 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📝 License

This website is created for Abhath Analytics. All rights reserved.

## 🤝 Support

For any questions or issues:
- Email: support@abhathanalytics.com
- Phone: +91-8595788768

---

**Built with ❤️ for Abhath Analytics**

*Transforming Data Into Actionable Intelligence*
