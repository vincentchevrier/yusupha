# Yuspha Jammeh Birdwatching Services Website

## Project Overview
A single-page static website advertising professional birdwatching guide services in The Gambia. The site showcases Yuspha Jammeh's 20 years of experience and features his bird photography in an interactive carousel.

## Tech Stack
- HTML5
- CSS3 (vanilla, no frameworks)
- JavaScript (vanilla, no dependencies)
- Python `rembg` library (for image processing)

## File Structure
```
yusupha/
├── index.html          # Main HTML structure
├── styles.css          # All styling (earthy, minimalist theme)
├── script.js           # Carousel and smooth scrolling functionality
├── images/
│   ├── birds/          # Bird photography (8 images)
│   │   ├── Bearded Barbet.jpg
│   │   ├── Blue-breasted Kingfisher.jpg
│   │   ├── Bronze-tailed Glossy Starling.jpg
│   │   ├── Brown Snake Eagle.jpg
│   │   ├── Bruces Green Pigeon.jpg
│   │   ├── Purple Glossy Starling.jpg
│   │   ├── Wolly-necked Stork.jpg
│   │   └── Yellow-billed  Stirk.jpg
│   └── people/
│       ├── yusupha.jpg              # Original photo
│       ├── yusupha-nobg.png         # Background removed, cropped
│       └── yusupha_with_client.jpg  # Tour photo
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
- Photo of Yuspha with a client on tour
- Four service cards:
  - Guided Bird Tours (full-day/half-day)
  - Photography Tours
  - Custom Itineraries
  - Bird Identification

### 3. Bird Gallery
- Interactive carousel with all 8 bird photos
- Text notes photos were taken on tours
- Features:
  - Auto-advancement (5 second interval)
  - Manual navigation (prev/next buttons)
  - Dot indicators
  - Touch swipe support for mobile
  - Keyboard navigation (arrow keys)
  - Pause on hover

### 4. Contact Section
- WhatsApp (click-to-chat link)
- Email (mailto link)
- Instagram
- Facebook

**Note:** Contact details are placeholders - update in `index.html`:
- WhatsApp: `https://wa.me/220XXXXXXX`
- Email: `your.email@example.com`
- Instagram: `https://instagram.com/yourprofile`
- Facebook: `https://facebook.com/yourprofile`

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

## Image Processing
The hero profile image (`yusupha-nobg.png`) was created by:
1. Using Python `rembg` library to remove background from `yusupha.jpg`
2. Cropping to upper 65% (torso)
3. CSS scales image to 120% for closer crop in circular frame

## Deployment
Ready for GitHub Pages deployment:
1. Push to GitHub repository
2. Enable GitHub Pages in repository settings
3. Select branch to deploy (main/master)

## Future Updates
- Replace placeholder contact information with real details
- Add more bird photos to the gallery as needed
- Consider adding testimonials section
