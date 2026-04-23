# My Affordable Roof – Alabama Website Specification

## 1. Project Overview
- **Project Name**: My Affordable Roof – Alabama Website
- **Type**: Premium luxury lead-generation website (single-page HTML)
- **Core Functionality**: High-converting roofing company website designed to rebuild trust through transparency, guarantees, and professional presentation
- **Target Users**: Alabama homeowners seeking roofing services who need reassurance after past negative experiences

## 2. Visual & Rendering Specification

### Scene Setup
- Single-page scrolling website with smooth anchor navigation
- Fixed sticky header with navigation
- Sticky mobile "Call Now" floating button

### Color Palette
- **Primary (Navy)**: `#0a1628` — deep navy for backgrounds and headers
- **Secondary (Charcoal)**: `#1a1a2e` — dark sections
- **Accent (Gold)**: `#c9a962` — CTAs, highlights, icons
- **Light Gray**: `#f8f9fa` — light section backgrounds
- **White**: `#ffffff` — text on dark, content areas
- **Text Dark**: `#2d3748` — body text on light backgrounds
- **Success Green**: `#22c55e` — trust badges, checkmarks

### Typography
- **Headlines**: Montserrat (Google Fonts) — bold, 700 weight
- **Body**: Inter (Google Fonts) — clean, readable, 400/500 weight
- **Scale**:
  - Hero headline: 3.5rem (clamp responsive)
  - Section titles: 2.5rem
  - Subheadlines: 1.5rem
  - Body: 1rem
  - Small: 0.875rem

### Layout
- Max content width: 1200px
- Section padding: 80px vertical on desktop, 48px on mobile
- Grid system: CSS Grid for services, Flexbox for alignment
- Responsive breakpoints: 768px (tablet), 480px (mobile)

### Visual Effects
- Subtle box shadows on cards: `0 4px 20px rgba(0,0,0,0.08)`
- Hover lift on cards: `translateY(-8px)` with shadow increase
- Gold gradient on CTA buttons: linear from `#c9a962` to `#b8944d`
- Smooth scroll behavior
- Fade-in animations on scroll using Intersection Observer
- Before/after image slider with CSS transitions

## 3. Structure Sections (in order)

### 3.1 Sticky Header
- Logo (text-based): "My Affordable Roof"
- Navigation: Home, Services, Why Us, Reviews, Contact
- CTA button: "Get Free Estimate"
- Phone number: +1 (918) 892-3358
- Background: navy with slight transparency on scroll

### 3.2 Hero Section
- Full viewport height (100vh)
- Background: dark navy with subtle texture/pattern overlay
- Large headline: "Roofing You Can Finally Trust in Alabama"
- Subheadline: "Affordable. Reliable. Done Right the First Time."
- Two CTA buttons: "Get Free Roof Inspection" (primary gold), "Call Now" (outline)
- Phone number prominently displayed
- Trust badges row: Licensed & Insured, Satisfaction Guarantee, Fast Turnaround
- Background image suggestion: clean roofing installation (placeholder gradient)

### 3.3 Trust Rebuild Section
- Light gray background
- Section title: "A New Standard of Roofing Service"
- Three-column feature grid:
  - New Processes
  - Improved Communication
  - Strict Quality Control
- Two highlighted promises in gold-accented boxes:
  - "We don't take deposits before work begins"
  - "Clear, itemized invoices every time"
- Subtle iconography for each feature

### 3.4 Services Section
- Navy background
- Section title: "Our Services"
- 5 service cards in responsive grid:
  1. Roof Repair — "Fast, reliable repairs that extend your roof's life"
  2. Roof Installation — "Professional installation with premium materials"
  3. Storm & Hail Damage Repair — "Expert damage assessment and restoration"
  4. Roof Inspections — "Thorough inspections with detailed reports"
  5. Insurance Claim Assistance — "We help navigate your claim process"
- Each card: icon, title, description, subtle hover effect

### 3.5 Why Choose Us Section
- White/light background
- Section title: "Why Choose My Affordable Roof"
- 6-item grid with checkmark icons:
  - Transparent Pricing
  - No Hidden Fees
  - Fast Response Time
  - Skilled & Certified Team
  - Written Agreements Only
  - Real-Time Project Updates

### 3.6 Social Proof Section
- Light gray background
- Section title: "What Our Customers Are Saying"
- 3 testimonial cards with star ratings:
  - Quote, customer name, location, star rating
- Transparency disclaimer: "We are committed to improving and value all customer feedback."
- Optional: Google rating badge

### 3.7 Process Section
- Navy background
- Section title: "Our Simple 4-Step Process"
- Horizontal stepper (vertical on mobile):
  1. Free Inspection — "We assess your roof thoroughly"
  2. Clear Estimate — "Detailed, no-obligation quote"
  3. Professional Installation — "Expert craftsmen at work"
  4. Final Walkthrough — "Your complete satisfaction guaranteed"
- Connecting line between steps

### 3.8 Guarantee Section
- Gold accent background (subtle)
- Section title: "Our Guarantees"
- 3 guarantee cards:
  - Workmanship Guarantee
  - No Payment Until Work Begins
  - Detailed Contracts & Documentation
- Emphasized with icons and premium styling

### 3.9 Before/After Section
- White background
- Section title: "Our Work"
- Before/after image slider comparison
- Labels: "Before" / "After"
- CSS-based slider with drag handle

### 3.10 FAQ Section
- Light gray background
- Section title: "Frequently Asked Questions"
- Accordion-style FAQ items:
  - Do you require a deposit?
  - How long does a typical roof installation take?
  - Do you help with insurance claims?
  - What areas do you serve?
  - What if I'm not satisfied with the work?

### 3.11 Contact/CTA Section
- Dark navy background
- Large headline: "Don't Risk Your Roof — Work With a Team That Shows Up"
- Quick contact form:
  - Name (required)
  - Phone (required)
  - Service dropdown
  - Message textarea
  - Submit button
- Direct phone number
- Optional: Google Maps embed placeholder

### 3.12 Footer
- Dark charcoal background
- Logo and tagline
- Contact info: Phone, Email (placeholder)
- Service Area: Alabama
- Quick links: Home, Services, About, Contact
- Trust badges: Licensed, Insured, Guarantee
- Copyright

## 4. Extra Conversion Features
- Sticky floating "Call Now" button (bottom-right, mobile-friendly)
- Smooth scroll navigation
- Intersection Observer for fade-in animations
- Form validation (HTML5 + basic JS)
- Mobile hamburger menu

## 5. Interaction Specification

### Navigation
- Smooth scroll to sections on nav link click
- Active section highlighting (optional)
- Mobile hamburger menu toggle

### Forms
- HTML5 validation attributes
- Required field indicators
- Submit feedback (alert/success message)

### Before/After Slider
- CSS-only horizontal slider
- Range input overlay for dragging
- Labels for before/after

### FAQ Accordion
- Click to expand/collapse
- Smooth height animation
- Plus/minus icon toggle

## 6. Technical Implementation
- Single HTML file with embedded CSS and JavaScript
- No external frameworks (vanilla HTML/CSS/JS)
- Google Fonts via CDN (Montserrat, Inter)
- Font Awesome via CDN for icons
- Fully responsive (mobile-first approach)
- Accessibility: proper ARIA labels, semantic HTML

## 7. Acceptance Criteria
- [ ] Hero section renders with headline, subheadline, CTAs, and trust badges
- [ ] All 8+ sections are visible and properly styled
- [ ] Navigation smooth-scrolls to correct sections
- [ ] Mobile hamburger menu works on small screens
- [ ] Floating call button is visible on all screen sizes
- [ ] Before/after slider is interactive
- [ ] FAQ accordion expands/collapses
- [ ] Contact form has validation
- [ ] All colors match the specified palette
- [ ] Typography hierarchy is clear and readable
- [ ] Site is fully responsive on mobile, tablet, desktop
- [ ] No console errors
- [ ] All external resources (fonts, icons) load successfully
