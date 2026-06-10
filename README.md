# Samuel Akinbode Asamu — Professional Dispatch Rider Portfolio

A modern, responsive HTML portfolio website for Samuel Akinbode Asamu, showcasing 25+ years of professional dispatch and logistics expertise across Lagos State.

## Features

### Hero Section
- **Animated carousel background** cycling between `about-me.jpg` and `checking-bike.jpg` with smooth fade transitions
- **Thin dark overlay** (16% opacity) for text readability
- Professional introductory text with call-to-action buttons
- Responsive typography and layout

### Key Sections
- **Navigation** — Sticky header with branding and WhatsApp CTA
- **Stats** — Key metrics (25+ years experience, 30+ corporate clients, 6 certifications, Lagos coverage)
- **About** — Career overview with professional photo (`about-me.jpg`) and detailed background
- **Services** — 6 service cards covering personal errands, document delivery, corporate dispatch, food logistics, inter-office runs, and flexible hire options
- **Experience** — Work history with route-line visual motif and detailed experience cards
- **Certifications** — 6 formal credentials from Lascofed Training & Development Centre
- **Why Choose** — 6 differentiators highlighting trust, discretion, punctuality, credentials, coverage, and track record
- **Testimonials** — Placeholder client testimonials (ready for real quotes)
- **Contact** — CTA section with WhatsApp and phone buttons
- **Footer** — Copyright and hire link

### Design
- **Color Palette**: Navy (#1A2744), Amber (#D4860B), White, Muted gray
- **Typography**: DM Serif Display (headings), Inter (body)
- **Responsive**: Mobile-first design with breakpoints for tablets and desktops
- **Accessibility**: Semantic HTML, ARIA labels, smooth scroll behavior
- **Animations**: Scroll-reveal effects, carousel fade transitions, hover states

## File Structure

```
Daddy's portfolio/
├── samuel-asamu.html          # Main portfolio page
├── about-me.jpg               # Hero carousel image 1 & About section photo
├── checking-bike.jpg          # Hero carousel image 2
└── README.md                  # This file
```

## Image Assets Required

Place these files in the same directory as `samuel-asamu.html`:

1. **about-me.jpg** — Used in:
   - Hero section carousel (first image)
   - About section professional photo
   - Recommended: 1200x800px minimum, portrait or landscape

2. **checking-bike.jpg** — Used in:
   - Hero section carousel (second image)
   - Recommended: 1200x800px minimum

Both carousel images fade between each other every 4 seconds (8-second total cycle).

## Customization

### Hero Section
- **Text**: Edit name, title, tagline in the hero markup
- **Carousel Images**: Replace `about-me.jpg` and `checking-bike.jpg` URLs in CSS
- **Carousel Speed**: Modify animation duration in `.hero-bg::before` and `.hero-bg::after` animation values (currently `8s` and `6s infinite 8s`)
- **Overlay Opacity**: Adjust `rgba(0,0,0,.16)` in `.hero-bg` (higher decimal = darker overlay)

### Contact Links
- **WhatsApp**: Replace `2348029448762` in all WhatsApp links
- **Phone**: Replace `+2348000000000` in all phone links
- **Hours/Service Area**: Update in Contact section metadata

### Testimonials
- Replace placeholder testimonial text, attributions, and roles in the Testimonials section
- Remove the placeholder warning when ready

### Colors
Edit CSS variables in `:root`:
```css
--navy:    #1A2744;      /* Primary dark color */
--amber:   #D4860B;      /* Accent color */
--amber-l: #F0A62A;      /* Light accent */
--bg:      #F7F6F2;      /* Light background */
```

## Deployment

### Local Testing
Open `samuel-asamu.html` directly in a web browser.

### Web Hosting
1. Upload all files (HTML + images) to your web hosting server
2. Ensure image paths match file locations
3. Test on multiple devices and browsers

### Performance Tips
- Optimize images: Compress JPGs to <200KB each
- Use modern image formats (WebP) for faster loading
- Test on slow connections to verify carousel smooth fade

## Browser Support

- Chrome/Edge: Full support
- Firefox: Full support
- Safari: Full support (iOS 12+)
- Mobile browsers: Full responsive support

## Notes

- All statistics and experience details should be verified/updated by client
- Certifications section contains placeholder titles — add specific certification names
- Professional driving certification uses a house icon; update icon if needed
- Grid background in hero is subtle (3% opacity lines) — adjust in `.hero::before` if needed

## Technical Details

- **Pure HTML/CSS/JavaScript** — No frameworks or build tools required
- **Responsive design** — Mobile-first approach with media queries at 600px and 760px+ breakpoints
- **Intersection Observer API** — Used for scroll-reveal animations
- **CSS Grid & Flexbox** — Modern layout techniques
- **CSS Custom Properties** — Easy theming and maintenance

## License

Custom portfolio for Samuel Akinbode Asamu. All content and design are proprietary.

---

**Last Updated**: June 10, 2026  
**Version**: 1.0
