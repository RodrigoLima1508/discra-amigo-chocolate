# Easter Campaign Website - Specification

## 1. Project Overview
- **Project name**: Páscoa Defense Campaign
- **Type**: Single-page website
- **Core functionality**: A fun, interactive Easter-themed page to defend a friend for a chocolate prize
- **Target users**: Friends and colleagues

## 2. UI/UX Specification

### Layout Structure
- Full-width header with centered content
- Central card-based layout
- Sections: Header, Main Card, Defense Section, Legend Section, Prize Section, CTA Button
- Mobile-first responsive design

### Responsive Breakpoints
- Mobile: < 640px
- Tablet: 640px - 1024px
- Desktop: > 1024px

### Visual Design

#### Color Palette
- Primary: `#FFB6C1` (Light Pink)
- Secondary: `#E6E6FA` (Lavender)
- Accent 1: `#FFFACD` (Lemon Chiffon - Yellow)
- Accent 2: `#98FB98` (Pale Green)
- Accent 3: `#FFDAB9` (Peach)
- Dark text: `#4A3728` (Chocolate brown)
- Card background: `#FFFFFF` with soft shadows

#### Typography
- Headings: 'Fredoka One', cursive (fun, rounded)
- Body: 'Nunito', sans-serif (friendly, readable)
- Sizes:
  - H1: 2.5rem (mobile: 1.8rem)
  - H2: 1.8rem (mobile: 1.4rem)
  - Body: 1rem
  - Small: 0.875rem

#### Spacing System
- Section padding: 3rem (mobile: 1.5rem)
- Card padding: 2rem (mobile: 1.5rem)
- Element gap: 1.5rem

#### Visual Effects
- Card shadows: `0 10px 40px rgba(74, 55, 40, 0.15)`
- Border radius: 20px for cards, 50px for buttons
- Floating egg animations in background
- Confetti/egg drop animation on load
- Smooth hover transitions (0.3s ease)
- Fade-in animations on scroll

### Components

#### Header
- Centered title with emoji decorations
- Subtitle below
- Decorative eggs floating around

#### Main Card
- White card with pink border
- Two lines: Name and friend's name
- Rabbit emoji decorations

#### Defense Section
- Cream/pink tinted background
- Decorative quotation marks
- Long text with good readability

#### Legend Section
- Different background shade
- Bullet points with emojis
- More playful layout

#### Prize Section
- Highlighted with gold/yellow accent
- Trophy emoji
- Larger text
- Pulse animation on important elements

#### CTA Button
- Large, prominent
- Pink gradient background
- Scale on hover
- Emoji decoration

#### Background Elements
- Floating eggs at various positions
- CSS-only animated elements
- Different sizes and rotation speeds

## 3. Functionality Specification

### Core Features
- Fully static page (no backend)
- Smooth scroll behavior
- Intersection Observer for scroll animations
- Confetti/egg animation on page load
- Continuous floating egg background animation

### User Interactions
- Hover effects on cards and buttons
- Button click (visual feedback only)
- Smooth scroll for any internal links

### Animations
1. **Page Load**: Confetti/eggs drop from top
2. **Scroll**: Elements fade in and slide up
3. **Hover**: Cards lift, buttons scale
4. **Background**: Floating eggs drift slowly

## 4. Acceptance Criteria
- [ ] Header displays correctly with title and subtitle
- [ ] Main card shows both names clearly
- [ ] Defense section text is fully readable
- [ ] Legend section has bullet points with emojis
- [ ] Prize section is visually highlighted
- [ ] Button has hover effect
- [ ] Floating egg animation works
- [ ] Page is responsive on mobile
- [ ] Colors match pastel Easter theme
- [ ] Fonts are loaded correctly