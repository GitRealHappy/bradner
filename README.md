# Bradner Countryside Smokehouse Website

A professional Jekyll website for Bradner Countryside Smokehouse, located in Abbotsford, British Columbia.

## Project Overview

**Business:** Bradner Countryside Smokehouse  
**Location:** Abbotsford, BC (serving Aldergrove, Langley, Chilliwack, Mission area)  
**Services:** Artisanal smoked meats and products (wholesale & retail)  
**Primary Goals:** Drive in-store visits and phone orders  

## Site Structure

### Core Pages
1. **Home Page** (`/`)
   - Hero section with compelling imagery
   - Brief business introduction
   - Featured products showcase
   - Primary CTAs (Visit Store, Call to Order)
   - Location/hours quick reference

2. **About Page** (`/about/`)
   - Business story and history
   - Smokehouse process and craftsmanship
   - Quality commitments and certifications
   - Team/owner introduction

3. **Products & Services** (`/products/`)
   - Product categories (to be defined)
   - Service offerings (wholesale/retail)
   - Quality descriptions
   - "Contact for Pricing" messaging
   - Photo gallery integration

4. **Location & Contact** (`/location/`)
   - Store address and directions
   - Operating hours
   - Service area map
   - Pickup/delivery information
   - Contact form
   - Phone and email contact

### Additional Sections
5. **Photo Gallery** (`/gallery/`)
   - Product photography
   - Smokehouse process images
   - Behind-the-scenes content

## Technical Specifications

### Jekyll Setup
- **Framework:** Jekyll (latest stable version)
- **Theme:** Custom theme optimized for local business
- **Hosting:** GitHub Pages compatible
- **Domain:** TBD
- **SSL:** Required for contact forms

### Key Features
- **Responsive Design:** Mobile-first approach
- **Contact Form:** Integrated with form handler (Formspree/Netlify)
- **Image Optimization:** Responsive images with lazy loading
- **SEO Optimization:** Local business schema markup
- **Social Media Integration:** Instagram/Facebook links
- **Google Analytics:** Traffic tracking
- **Google My Business:** Integration ready

### Performance Requirements
- **Page Load Speed:** < 3 seconds
- **Mobile Performance:** 90+ Lighthouse score
- **Accessibility:** WCAG 2.1 AA compliance
- **Cross-browser:** Support for modern browsers

## Content Strategy

### SEO Keywords (Primary)
- "smoked meats Abbotsford"
- "smokehouse British Columbia"
- "artisanal smoked products BC"
- "custom smoking services Abbotsford"
- "wholesale smoked meats Fraser Valley"

### SEO Keywords (Secondary)
- "Aldergrove smokehouse"
- "Langley smoked meats"
- "Chilliwack artisanal foods"
- "Mission BC specialty meats"
- "Fraser Valley local food"

### Content Tone
- Professional yet approachable
- Emphasis on craftsmanship and quality
- Local community focus
- Traditional smokehouse heritage

## Design Direction

### Visual Style
- **Theme:** Rustic elegance with modern functionality
- **Colors:** Warm earth tones, smoky grays, rich browns
- **Typography:** Readable sans-serif with rustic accent fonts
- **Imagery:** High-quality product photos, process shots, local scenery

### Layout Principles
- Clean, uncluttered design
- Clear navigation and CTAs
- Mobile-first responsive design
- Fast loading with optimized images

## File Structure

```
BCSS/
├── _config.yml              # Jekyll configuration
├── _includes/               # Reusable components
│   ├── header.html
│   ├── footer.html
│   ├── contact-form.html
│   └── social-links.html
├── _layouts/                # Page templates
│   ├── default.html
│   ├── page.html
│   └── gallery.html
├── _sass/                   # Stylesheets
│   ├── _variables.scss
│   ├── _base.scss
│   ├── _layout.scss
│   └── _components.scss
├── assets/                  # Static assets
│   ├── css/
│   ├── js/
│   └── images/
├── _data/                   # Site data
│   ├── navigation.yml
│   ├── products.yml
│   └── contact.yml
├── index.html               # Temporary "Coming Soon" page
├── full-site.html           # Complete site preview (staging)
├── about.html               # About page
├── products.html            # Products page
├── location.html            # Location page
├── gallery.html             # Photo gallery
└── README.md                # This file
```

## Development Phases

### Phase 1: Foundation (Week 1)
- [ ] Jekyll site setup and configuration
- [ ] Basic file structure creation
- [ ] Core layout templates
- [ ] Navigation system
- [ ] Responsive grid system

### Phase 2: Core Pages (Week 2)
- [ ] Home page development
- [ ] About page content structure
- [ ] Products page framework
- [ ] Location page with contact form
- [ ] Basic styling and branding

### Phase 3: Enhancement (Week 3)
- [ ] Photo gallery implementation
- [ ] Contact form integration
- [ ] SEO optimization
- [ ] Performance optimization
- [ ] Cross-browser testing

### Phase 4: Content & Launch (Week 4)
- [ ] Content population
- [ ] Image optimization and upload
- [ ] Final testing and QA
- [ ] Domain setup and deployment
- [ ] Analytics and tracking setup

## Content Requirements

### Immediate Needs
- [ ] Business description and story
- [ ] Product categories and descriptions
- [ ] High-quality product photography
- [ ] Logo and branding assets
- [ ] Contact information and hours
- [ ] Social media account links

### Future Additions
- [ ] Newsletter integration
- [ ] Online ordering system (future phase)
- [ ] Delivery service expansion
- [ ] Additional product lines
- [ ] Customer testimonials

## Contact Information Placeholders

- **Phone:** [To be provided]
- **Email:** [To be provided]
- **Address:** [To be provided]
- **Hours:** [To be provided]
- **Instagram:** [To be provided]
- **Facebook:** [To be provided]

## Current Build Plan & Staging Setup

### Staging Approach (Temporary)
The website is currently set up with a dual-page system to handle the construction phase:

1. **Public Landing Page** (`index.html`)
   - Simple "Coming Soon" page for public visitors
   - Basic business information and contact details
   - Professional messaging about site under construction
   - Minimal content to avoid showing incomplete sections

2. **Full Site Preview** (`full-site.html`)
   - Complete website with all sections and features
   - Contains "To be provided" placeholders for missing content
   - Accessible via hidden link in footer for client review
   - Shows the full scope of work and content requirements

### Hidden Access Method
- **Location:** Footer of the main site
- **Method:** Subtle "Preview" link in copyright section
- **Styling:** Blends with footer text (low opacity, no underline)
- **Purpose:** Allows client to access full site without exposing it to public

### Content Migration Plan
Once all content is provided and approved:
1. Replace `index.html` with content from `full-site.html`
2. Remove the hidden preview link
3. Delete `full-site.html` 
4. Update README to remove staging references

### Missing Content Tracking
The full site currently shows "[To be provided]" for:
- Business phone number
- Business email address
- Physical address and postal code
- Operating hours
- Social media links (Instagram, Facebook)
- High-quality product photography
- Detailed product descriptions and pricing
- Business story and owner background
- Google Analytics tracking code

### Development Priority
1. **Content Collection** - Gather all missing business information
2. **Photography** - Professional product and location photos
3. **Content Review** - Client approval of all text and messaging
4. **Testing** - Full site functionality and mobile responsiveness
5. **Launch** - Switch to full site and remove staging setup

### Staging Setup Details
**Header Navigation Changes:**
- Coming Soon page: No navigation menu (simplified header)
- Full Site preview: Navigation "Home" redirects to `/full-site/` instead of `/`
- Logo link: Redirects to `/full-site/` when on full-site preview
- Mobile navigation: Same conditional logic as desktop

**Launch Checklist (When Ready to Go Live):**
1. **Replace index.html content:**
   ```bash
   cp full-site.html index.html
   ```
2. **Remove staging navigation logic from header:**
   - Remove conditional checks for `page.body_class == 'home-page'`
   - Restore standard navigation links
   - Remove conditional logo redirects
3. **Remove hidden preview link:**
   - Remove "Preview" link from `_includes/footer.html`
4. **Delete staging file:**
   ```bash
   rm full-site.html
   ```
5. **Update README:**
   - Remove staging setup sections
   - Update file structure documentation
6. **Test and commit:**
   ```bash
   git add -A
   git commit -m "Launch: Remove staging setup and activate full site"
   git push origin main
   ```

## Next Steps

1. Review and approve this structural plan
2. Gather business content and imagery
3. Begin Jekyll site development
4. Set up hosting and domain
5. Implement design and functionality
6. Content population and testing
7. Launch and optimization

---

**Project Start Date:** December 2024  
**Target Launch Date:** January 2025  
**Last Updated:** December 2024 