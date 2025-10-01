# Brew & Beans Coffee Shop - Website Build

A complete, production-ready three-page website built for a coffee shop. Uses Tailwind CSS via CDN and a coffee-focused design system.

What’s included
- index.html: Home with hero image, menu highlights, story preview, and gallery.
- about.html: Our story, team, sourcing, and philosophy.
- contact.html: Visit us, hours, and a contact form.
- README.md: This file.

Styling and assets
- All styling is done with Tailwind CSS utility classes. No external CSS files are required.
- Background hero images and gallery images are represented with placeholder templates:
  - https://pixabay.com/get/g6e5bebfcc57d4c97d096125b05844a154a06a9a0aad1857b305b086b9faf38a63eb184433ffa18eebbfae45f44f42f6b8ad3cf1c9705e7f6349353d956f49555_640.jpg placeholders for hero and gallery imagery.
- Typography: Heading font Montserrat, Body font Open Sans (via Tailwind arbitrary font classes).
- Color palette (coffee shop theme):
  - Primary: #3C2415
  - Secondary: #8B4513
  - Accent: #D2B48C
  - Background: #F5DEB3

How to customize
1) Update hero background image: replace the string in the hero section style attribute in index.html.
2) Replace placeholder images: replace each https://images.unsplash.com/photo-1756758766177-b1213e59c1ae?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w3ODkyNDZ8MHwxfHNlYXJjaHw4fHwuLi58ZW58MHwwfHx8MTc1OTMyNDgxOXww&ixlib=rb-4.1.0&q=80&w=1080 with real image URLs when you host assets.
3) Update content to your branding (name, descriptions, hours, locations).
4) If you want to add pages, follow the same pattern and link them in the navigation.

Accessibility & SEO
- Semantic HTML5: header, nav, main, section, article, footer.
- All images include descriptive alt text.
- Meta description tags present for each page.

Deployment
- Host the three HTML pages together on the same domain.
- Ensure Tailwind CDN remains accessible for styles.
- Optionally replace https://images.unsplash.com/photo-1577788228261-ffeb1410026f?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w3ODkyNDZ8MHwxfHNlYXJjaHwxfHwuLi58ZW58MHwwfHx8MTc1OTMyNDgxOXww&ixlib=rb-4.1.0&q=80&w=1080 placeholders with real image URLs.
