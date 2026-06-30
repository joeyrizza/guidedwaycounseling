# Guided Way Counseling Website

A professional, responsive static website for Guided Way Counseling, a therapy practice in Biddeford, Maine specializing in trauma-informed, holistic mental health care.

## Overview

This website serves as the online presence for Casie Rizza, LCPC-C, MA, providing information about therapeutic services, specialties, and an easy way for potential clients to connect and schedule consultations.

### Core Messaging

The site is built around powerful therapeutic themes:

- **"Seen, Heard, Known, Accepted"** - Creating a safe space where clients feel fully understood
- **"Struggling doesn't mean you are defective—it just means you are human"** - Normalizing the therapy journey
- **"What's wounded in relationship must be healed in relationship"** - Emphasizing the healing power of therapeutic connection
- Featuring wisdom from Carl Rogers, Brené Brown, and other thought leaders in psychology and vulnerability

## Features

✅ **Fully Responsive Design** - Optimized for desktop, tablet, and mobile devices  
✅ **Modern, Calming Aesthetic** - Color palette inspired by the practice logo (sage greens, earth tones)  
✅ **Multiple Pages** - Home, About, Services, Contact  
✅ **Interactive Navigation** - Sticky navbar with mobile hamburger menu  
✅ **Contact Form** - mailto integration for easy client outreach  
✅ **SEO Optimized** - Meta descriptions and semantic HTML  
✅ **Accessibility** - ARIA labels and semantic structure  
✅ **Under Construction Page** - Professional landing page during development  
✅ **Smooth Animations** - Fade-in effects and hover states  

## Site Structure

```
GuidedWayCounseling/
├── index.html          # Under construction landing page
├── home.html           # Full homepage (development)
├── about.html          # About Casie Rizza - credentials, philosophy
├── services.html       # Detailed service descriptions
├── contact.html        # Contact form, FAQs, availability
├── css/
│   └── styles.css      # Complete responsive styling
├── js/
│   └── script.js       # Interactive features
├── Resources/
│   ├── logo.png        # Primary logo
│   ├── casie.jpeg      # Therapist photo
│   ├── flyer.pdf       # Marketing materials
│   └── [logo variants] # Various logo sizes
└── README.md           # This file
```

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Custom properties (variables), Grid, Flexbox
- **Vanilla JavaScript** - No dependencies or frameworks
- **Google Fonts** - Cormorant Garamond (headings) & Montserrat (body)

## Development Structure

### Current Setup

- `index.html` - Public-facing "Under Construction" page with contact information
- `home.html` - Full site homepage for development/preview
- All navigation links point to `home.html` to enable full site navigation during development

### When Ready to Launch

1. Delete the current `index.html` (under construction page)
2. Rename `home.html` to `index.html`
3. Update all navigation links from `home.html` back to `index.html`
4. Deploy to hosting

## Color Palette

```css
--primary-green: #5a7254   /* Main brand color */
--dark-green: #3d4d38      /* Headers, dark accents */
--light-green: #8b9d83     /* Light accents */
--sage: #a8b5a0            /* Borders, subtle highlights */
--cream: #f5f3ed           /* Background sections */
--beige: #e8e4d9           /* Alternate backgrounds */
--warm-brown: #8b7355      /* Accent color */
```

## Key Sections

### Homepage (`home.html`)
- Hero section with core messaging
- Specialties overview grid
- Approach/philosophy section
- Availability and fees
- Call-to-action

### About Page (`about.html`)
- Professional photo and bio
- Credentials (education, license, experience)
- Philosophy with therapeutic quotes
- Specialization areas
- Therapeutic approaches/modalities
- Professional endorsements

### Services Page (`services.html`)
- Detailed descriptions for each specialty:
  - Depression & Anxiety
  - Trauma & PTSD
  - Church Hurt / Religious Trauma
  - Motherhood & Postpartum
  - ADHD
  - Life Transitions
  - Grief & Loss
  - Highly Sensitive Persons
  - Relationship Issues & Codependency
- Session format information
- Fees and payment details

### Contact Page (`contact.html`)
- Free consultation information
- Multiple contact methods (email, phone, Psychology Today)
- Contact form with mailto integration
- Comprehensive FAQ section
- Location and availability details

## Contact Information

**Casie Rizza, LCPC-C, MA**  
Email: casie@guidedwaycounseling.com  
Phone: (207) 886-9114  
Location: Biddeford, ME 04005

**Availability:**
- Tuesdays: Telehealth (9am-2pm)
- Wednesdays: In-Person in Biddeford (9am-2pm)

**Psychology Today Profile:**  
https://www.psychologytoday.com/us/therapists/casie-rizza-biddeford-me/1425780

## Setup & Deployment

### Local Development

1. Clone this repository
2. Open `index.html` in a browser (shows under construction page)
3. Navigate to `home.html` via the development link or directly access `/home.html`
4. Make changes to HTML/CSS/JS files as needed
5. Test responsiveness using browser dev tools

### Deployment Options

**GitHub Pages:**
```bash
git add .
git commit -m "Ready for deployment"
git push origin main
# Enable GitHub Pages in repository settings
```

**Netlify/Vercel:**
- Connect repository
- Set publish directory to root
- Deploy automatically on push

**Traditional Web Hosting:**
- Upload all files via FTP/SFTP
- Ensure Resources folder and all assets are uploaded
- Point domain to hosting directory

### Pre-Launch Checklist

- [ ] Delete current `index.html`
- [ ] Rename `home.html` to `index.html`
- [ ] Update navigation links (home.html → index.html)
- [ ] Test all links and forms
- [ ] Verify contact information is correct
- [ ] Test on multiple devices/browsers
- [ ] Check page load speeds
- [ ] Validate HTML/CSS
- [ ] Set up analytics (optional)

## Customization

### Updating Content

- **Colors**: Edit CSS variables in `css/styles.css`
- **Fonts**: Change Google Fonts links in HTML `<head>` sections
- **Images**: Replace files in `Resources/` folder
- **Text**: Edit HTML files directly
- **Specialties**: Modify service sections in `services.html`

### Adding New Pages

1. Create new HTML file
2. Copy navigation structure from existing pages
3. Add link to navigation menu in all files
4. Update footer links
5. Follow existing CSS class patterns

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## License & Credits

**Website Design & Development:** Custom built for Guided Way Counseling  
**Practice Owner:** Casie Rizza, LCPC-C, MA  
**Logo & Branding:** Guided Way Counseling  
**Therapeutic Quotes:** Carl Rogers, Brené Brown, Richard Moss  

© 2026 Guided Way Counseling. All rights reserved.  
Maine License: XL8623

## Notes

- Form submission uses `mailto:` protocol - consider integrating with a form service (Formspree, Netlify Forms) for better tracking
- No analytics currently implemented - add Google Analytics or alternative if desired
- Contact form data is not stored - emails open in user's email client
- Psychology Today profile link should be kept updated
- Sliding scale pricing requires application - ensure process is clear to clients

## Future Enhancements

Consider adding:
- Blog section for mental health resources
- Client testimonials page (with proper consent)
- Online booking integration (SimplePractice, TherapyNotes)
- Newsletter signup
- Resources/downloads section
- Video introduction from therapist
- Live chat widget (optional)

## Support

For technical issues or questions about this website, contact the developer or refer to standard HTML/CSS/JavaScript documentation.

For therapy services and client inquiries, contact Casie Rizza directly using the information above.

---

**Built with care for those seeking to be seen, heard, known, and accepted.** 🌿