# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is Happy Now Farm's website - a professional static website for an organic farm business operated by Conner Pangia. The site showcases the farm's story, produce, and directs customers to their online store at Pleasant Valley Farm's LocalLine platform.

## Project Structure

- `index.html` - Main landing page with complete farm information and online store integration
- `styles.css` - Responsive CSS with farm-themed color scheme and modern design
- `abundantStand.jpeg` - Primary farm stand image used in hero section (309KB)
- `marketStand.jpeg` - Secondary farm image used in about section (604KB)

## Technology Stack

- **Frontend**: Vanilla HTML5, CSS3 with CSS custom properties
- **Analytics**: Google Analytics (G-5PZ2GDSV0W)
- **Color Scheme**: Earth tones with primary green (#5a8f3d), accent orange (#e16f3b)
- **Typography**: Segoe UI font family for clean, readable design

## Development Commands

### Local Development
```bash
# Serve locally using Python (recommended)
python3 -m http.server 8000

# Alternative using Node.js
npx serve .

# View at http://localhost:8000
```

## Key Features & Business Integration

### Online Store Integration
- Primary CTA links to: `https://pleasantvalleyfarm.localline.ca/happynow`
- Multiple touchpoints throughout site directing to online store
- Enhanced button styling with hover effects for better conversion

### Business Information
- **Farm Name**: Happy Now Farm
- **Owner**: Conner Pangia
- **Location**: Argyle, NY (partnered with Pleasant Valley Farm)
- **Contact**: connerpangia@gmail.com, (631) 245-9093
- **Markets**: Huntington Farmers Market (every other week)
- **Specialties**: 100% organic vegetables, permaculture practices

### Content Sections
1. **Hero**: Compelling introduction with direct store access
2. **About**: Detailed farm story and owner background
3. **Services**: Three distribution channels (farmers market, online store, delivery)
4. **Products**: Organic farming highlights with icons
5. **Testimonials**: Customer social proof
6. **Contact**: Full contact information and message form

## Design Architecture

### CSS Organization
- CSS custom properties for consistent theming
- Mobile-first responsive design approach
- Flexbox layouts for service cards and product highlights
- Hover animations and transitions for engagement
- Background image overlays for text readability

### Image Implementation
- Hero section uses `abundantStand.jpeg` with dark overlay for text contrast
- About section uses `marketStand.jpeg` as background image
- Service cards reference actual farm images
- All images use `background-image` with `cover` sizing for consistency

### User Experience Flow
1. **Landing**: Immediate farm introduction with prominent "Shop Our Produce" CTA
2. **Story**: Detailed background building trust and credibility
3. **Services**: Clear explanation of how customers can access products
4. **Social Proof**: Customer testimonial for conversion
5. **Contact**: Multiple contact methods and inquiry form

## Deployment Notes

- Static website suitable for any hosting platform
- No build process required - files can be deployed directly
- Consider image optimization for faster loading
- Google Analytics already implemented
- Form submission requires backend implementation or third-party service

## Future Enhancement Opportunities

- Add form processing for contact form
- Implement social media integration
- Add more customer testimonials
- Consider adding blog/news section for farm updates
- Optimize images for different screen sizes