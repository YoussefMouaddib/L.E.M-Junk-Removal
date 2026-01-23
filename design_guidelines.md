# ClearFlow Plumbing Co. - Design Guidelines

## Design Approach
**Reference-Based**: Local service business combining the clean professionalism of modern SaaS (Linear, Stripe) with the trust-building elements of successful service platforms (Thumbtack, HomeAdvisor). Focus on conversion optimization and credibility.

## Core Design Principles
1. **Trust First**: Every element reinforces professionalism and reliability
2. **Conversion Optimized**: Clear CTAs, minimal friction, obvious next steps
3. **Scannable**: Information hierarchy supports quick decision-making
4. **Mobile-First**: Primary user journey optimized for mobile devices

## Typography System
**Font Stack**: Inter or DM Sans (clean, professional sans-serif via Google Fonts)

**Hierarchy**:
- Hero Headline: text-5xl md:text-6xl, font-bold, leading-tight
- Section Headers: text-3xl md:text-4xl, font-bold
- Subheadings: text-xl md:text-2xl, font-semibold
- Body: text-base md:text-lg, leading-relaxed
- Small Print: text-sm
- CTA Buttons: text-base md:text-lg, font-semibold

## Layout & Spacing System
**Tailwind Units**: Consistently use 4, 6, 8, 12, 16, 20, 24 for spacing (as in py-8, px-6, gap-12)

**Container Strategy**:
- Max width: max-w-7xl for content sections
- Horizontal padding: px-6 md:px-8 lg:px-12
- Section vertical spacing: py-16 md:py-24

**Grid Patterns**:
- Services: grid-cols-1 md:grid-cols-2 lg:grid-cols-3, gap-8
- Testimonials: grid-cols-1 md:grid-cols-2 lg:grid-cols-3, gap-6
- Value props: grid-cols-1 md:grid-cols-3, gap-6

## Component Library

### Navigation
- Sticky header with white background, subtle shadow
- Logo left, navigation center/right, CTA button prominent
- Mobile: Hamburger menu, full-screen overlay

### Hero Section
- Large hero image showing professional plumber at work (bright, clean, trustworthy)
- Overlay with subtle gradient for text readability
- Headline + subheadline + dual CTA (primary: "Get Free Quote", secondary: "Call Now")
- Height: min-h-[600px] md:min-h-[700px]
- CTAs with backdrop-blur-sm bg-white/90 treatment

### Service Cards
- Bordered cards with subtle hover lift effect
- Icon at top, service name, brief description, "Learn More" link
- Consistent padding: p-6 md:p-8

### Testimonial Cards
- Quote icon, customer review text, name/location
- 5-star rating display
- Subtle background treatment: bg-gray-50

### Lead Form
- Single column layout, generous spacing between fields
- Input styling: border-2, rounded-lg, py-3 px-4
- Dropdown for service type with clear options
- Large submit button: py-4, full width on mobile
- Success state with checkmark icon and clear message

### Chatbot Widget
- Fixed position: bottom-right (bottom-4 right-4)
- Circular trigger button when closed (w-14 h-14)
- Chat window: w-80 md:w-96, rounded-lg, shadow-2xl
- Message bubbles: user (right-aligned), bot (left-aligned)
- Input field at bottom with send button

### CTAs
- Primary: Solid fill, py-3 px-8, rounded-lg, shadow-md
- Secondary: Outlined, py-3 px-8, rounded-lg
- Hover states: subtle scale and shadow increase

### Footer
- Multi-column on desktop (3-4 columns), stacked on mobile
- Contact info, quick links, service areas, business hours
- Trust badges: Licensed, Insured, 24/7 Emergency
- Copyright and legal links at bottom

## Page-Specific Layouts

### Home Page (6-7 sections)
1. Hero with image, headline, dual CTAs
2. Value Props: 3-column grid (Fast Response, Licensed, Fair Pricing)
3. Services Preview: 3-4 featured services with cards
4. Social Proof: Testimonials grid
5. Emergency Services CTA: Bold banner with phone number
6. Service Area: Brief mention with map or location indicator
7. Final CTA: Quote form preview or contact strip

### Services Page
- Service hero: Simple headline, brief intro
- Service grid: 6-8 services, each with icon, name, description, CTA
- Emergency services highlighted separately
- FAQ section at bottom

### About Page
- Company story: 2-column split (image + text) on desktop
- Team values: Icon grid highlighting professionalism, reliability
- Credentials: Licenses, certifications, years in business
- Final trust-building CTA

### Contact/Quote Page
- Hero: Simple, focused headline
- Form as primary element: generous spacing, clear labels
- Sidebar with contact methods, hours, service area info
- Confirmation overlay/modal after submission

## Images
**Hero Image**: Professional plumber working (bright, clean setting, tools visible, friendly expression) - full-width, ~700px height
**Service Icons**: Use Heroicons for consistency (wrench, fire, droplet, clock icons)
**About Page**: Team or work-in-progress photos showing professionalism
**Trust Badges**: Generic license/insurance badge graphics

## Animations
Minimal, performance-focused:
- Subtle hover lifts on cards (translate-y-1)
- Fade-in on scroll for sections (optional, use sparingly)
- Smooth page transitions
- Chatbot slide-in animation