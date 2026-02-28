# Yusupha Jammeh Birdwatching Services Website

## Project Overview
A single-page static website advertising professional birdwatching guide services in The Gambia and Senegal. The site showcases Yusupha Jammeh's 20 years of experience and features his bird photography in an interactive carousel.

**Live site:** [gambiabirdwatch.com](https://gambiabirdwatch.com)

## Tech Stack
- HTML5
- CSS3 (vanilla, no frameworks)
- JavaScript (vanilla, no dependencies)
- ImageMagick (for image resizing)
- Python `rembg` library (for background removal)

## File Structure
```
yusupha/
├── index.html          # Main HTML structure
├── styles.css          # All styling (earthy, minimalist theme)
├── script.js           # Carousel and smooth scrolling functionality
├── CNAME               # Custom domain for GitHub Pages
├── images/
│   ├── birds/          # Bird photography (29 images)
│   │   ├── thumb/      # Resized images for carousel (1200px wide)
│   │   ├── African Golden Oriole.jpg
│   │   ├── African River Eagle.jpg
│   │   ├── ... (29 species total)
│   │   └── oriole-vignette.jpg  # Footer vignette
│   ├── unused/         # Original 8 carousel images (archived)
│   ├── people/
│   │   ├── yusupha.jpg              # Original photo
│   │   ├── yusupha-nobg.png         # Background removed, cropped
│   │   └── yusupha_with_client.jpg  # Tour photo
│   ├── favicon.ico
│   ├── favicon-16.png
│   ├── favicon-32.png
│   ├── apple-touch-icon.png
│   └── bird-icon.svg   # Favicon source (raven icon)
```

## Site Sections

### 1. Hero Section
- Circular profile photo with background removed (120% zoom)
- Headline: "Professional Birdwatching Guide Services"
- Tagline about The Gambia's bird diversity
- CTA button linking to contact section

### 2. About & Services Section
- 20 years of experience highlight
- Description of The Gambia as a birdwatching destination
- Note that tours to Senegal are also available
- Expandable tour destinations accordion with 21 locations:
  - **The Gambia (15):** Kotu Creeks, Bijilo Forest Park, Brufut Woods, Abuko Nature Reserve, Tanji Bird Reserve, Marakisa Woods, Farasutu Community Forest, Pirang Forest, Kartong Bird Observatory, Tendaba Camp, Kiang West National Park, Morgan Kunda Woods, Janjanbureh River Excursion, Bansang Quarry, Basse Woods
  - **Senegal (6):** Wassudu Camp, Dindifelo Waterfall, Toubacouta Creeks, Njafate Semi-desert, Djoudj National Park, Podor Semi-desert
- Photo of Yusupha with a client on tour
- Four service cards:
  - Guided Bird Tours (full-day/half-day)
  - Photography Tours
  - Custom Itineraries
  - Bird Identification

### 3. Bird Gallery
- Interactive carousel with 29 bird photos
- Thumbnail images load for performance, click for full resolution
- Text notes photos were taken on tours
- Features:
  - Auto-advancement (2.5 second interval)
  - Manual navigation (prev/next buttons)
  - Dot indicators
  - Touch swipe support for mobile
  - Keyboard navigation (arrow keys)
  - Pause on hover

### 4. Contact Section
- WhatsApp: [+220 770 6348](https://wa.me/2207706348)
- Email: yuspha_jammeh704@yahoo.com
- Instagram: [@yuspha.jammeh.9](https://www.instagram.com/yuspha.jammeh.9)
- Facebook: [yuspha.jammeh.9](https://www.facebook.com/yuspha.jammeh.9)

### 5. Footer
- African Golden Oriole vignette image
- Copyright notice

## Design
- **Style:** Earthy, minimalist
- **Color Palette:**
  - Earth dark: `#3d2914`
  - Earth brown: `#5c4033`
  - Earth tan: `#8b7355`
  - Earth sand: `#c4a77d`
  - Earth cream: `#f5f0e8`
  - Forest green: `#4a5d23`
- **Typography:** Georgia (headings), system fonts (body)
- **Responsive:** Mobile-first with breakpoints at 600px, 768px, and 1024px
- **Favicon:** Raven icon with forest green background and white foreground

## Image Processing
- Hero profile image (`yusupha-nobg.png`): Background removed with `rembg`, cropped to upper 65%
- Carousel thumbnails: Resized to 1200px wide with ImageMagick for fast loading
- Full resolution images available on click (opens in new tab)
- Favicon generated from SVG at high density for crisp rendering

## Deployment
Deployed on GitHub Pages with custom domain:
1. Repository: GitHub
2. Branch: master
3. Custom domain: gambiabirdwatch.com (configured via CNAME file)
