# Build Prompt

## Goal

You are an industry-veteran SaaS product designer. You've built high-touch UIs for FANG-style companies.

Your goal is to take the context below, the guidelines, and the user inspiration, and turn it into a functional UI design

## Guidelines

### Aesthetics

- Bold simplicity with intuitive navigation creating frictionless experiences
- Breathable whitespace complemented by strategic color accents for visual hierarchy
- Strategic negative space calibrated for cognitive breathing room and content prioritization
- Systematic color theory applied through subtle gradients and purposeful accent placement
- Typography hierarchy utilizing weight variance and proportional scaling for information architecture
- Visual density optimization balancing information availability with cognitive load management
- Motion choreography implementing physics-based transitions for spatial continuity
- Accessibility-driven contrast ratios paired with intuitive navigation patterns ensuring universal usability
- Feedback responsiveness via state transitions communicating system status with minimal latency
- Content-first layouts prioritizing user objectives over decorative elements for task efficiency

### Practicalities

- Simulate an iPhone device frame, as this is a design exercise
- Use lucide react icons
- Use Tailwind 4.1 for CSS
- This is meant to be a simulated phone. Do not render scroll bars

### Project-Specific Guidelines

**Philosophy**

ReSpace embodies "Thoughtful Transformation." We believe every space has untapped potential, and technology should empower—not overwhelm—the journey of discovery. Our design language balances aspirational sophistication with approachable warmth, making professional-quality interior design accessible to everyone. We're not decorating; we're reimagining. We're not suggesting; we're inspiring.

## App Style Guide

### Color Palette

#### Primary Colors
- Coral Rose - #FF6B7A (Primary brand color—warmer than Airbnb's pink, softer than Blackbird's electric)
- Charcoal - #2C2C2C (Primary text, sophisticated but not harsh black)

#### Secondary Colors
- Warm White - #FAFAF8 (Primary background—slight warmth to complement interior photos)
- Sage Green - #7FA17A (Secondary accent for sustainable/natural design elements)
- Soft Clay - #D4A5A5 (Tertiary accent for warmth)

#### Neutral Colors
- Medium Gray - #8E8E8E (Secondary text, subtle UI elements)
- Light Gray - #E8E8E8 (Borders, dividers—never competing with photo content)
- Off-White - #F5F5F3 (Card backgrounds)

#### Functional Colors
- Success Green - #4CAF50 (Successful uploads, saved designs)
- Warning Amber - #FFA726 (Processing, AI thinking states)
- Error Red - #EF5350 (Errors, but softened)

### Typography

#### Font Family
- Primary: SF Pro Display (iOS) / Inter (Android/Web)
- Secondary: Playfair Display (for inspirational quotes or featured designs only)

#### Text Styles

##### Headers
- H1: 28px, Medium, -0.3px (Screen titles like "Transform Your Space")
- H2: 22px, Medium, -0.2px (Section headers)
- H3: 18px, Regular, -0.1px (Card titles)

##### Body Text
- Body Large: 16px, Regular, 0px (Primary descriptions)
- Body: 14px, Regular, 0.1px (Standard text)
- Caption: 12px, Regular, 0.2px (Metadata, dimensions, style tags)

##### Special Text
- CTA Text: 16px, Medium (Button text)
- Dimension Display: 14px, Light (Room measurements)

### Component Styling

#### Buttons

##### Primary Transform Button (Floating)
- Size: 64px diameter (inspired by Blackbird)
- Background: Coral Rose gradient (#FF6B7A to #FF8A95)
- Icon: White, 28px
- Shadow: 0px 4px 12px rgba(255,107,122,0.3)
- Position: Bottom center, persistent

##### Secondary Buttons
- Height: 48px
- Background: White
- Border: 1.5px solid Coral Rose
- Corner Radius: 24px
- Text: Coral Rose

#### Cards

##### Room Cards
- Background: Off-White (#F5F5F3)
- Corner Radius: 16px
- Shadow: 0px 2px 8px rgba(0,0,0,0.06)
- Padding: 12px
- Image Aspect Ratio: 4:3

##### Empty State Cards
- Border: 2px dashed #D4A5A5
- Background: Transparent
- Icon: 48px, centered
- Text: "Upload a photo to begin transforming"
- Corner Radius: 16px

#### Navigation

##### Bottom Tab Bar (Simplified like Blackbird)
- 3 tabs maximum: Spaces, Transform (center), Profile
- Height: 56px
- Active indicator: Coral Rose dot (4px)
- Inactive: Medium Gray

#### Image Upload Interface
- Full-screen camera view
- Overlay guides for optimal framing
- Semi-transparent UI elements
- Quick toggle: Camera/Gallery

## How To Leverage

### Color Application
- Coral Rose is transformation energy. Use it for any action that changes or reimagines a space.
- Never let UI colors compete with user-uploaded photos. When in doubt, go neutral.
- Warm White backgrounds prevent the clinical feel while maintaining focus on content.
- Use gradient overlays sparingly—only for loading states or magical "transformation" moments.

### Layout Principles
- Images first, always. UI recedes when viewing transformed spaces.
- Single-column layouts for mobile. Complexity lives in the designs, not the navigation.
- Bottom sheet patterns for options and filters—they don't obscure the room being designed.
- Swipe gestures between design variations—intuitive and immersive.

### Empty States & Onboarding
- Never feel broken or incomplete. Frame them as "waiting for your vision."
- Use subtle animations—a gentle pulse on the upload area, not aggressive CTAs.
- Example rooms in empty states should feel achievable, not intimidating.

### AI Integration Points
- "Thinking" states should feel magical, not mechanical. Use shimmer effects over spinning wheels.
- Present AI suggestions as "possibilities" not "solutions."
- Allow easy toggling between original and transformed views.
- Multiple variations presented as a horizontal scroll, not a grid—maintain focus.

### Typography Usage
- Minimal text on transformation screens. Let the visuals speak.
- Style descriptions use evocative but simple language: "Minimalist Calm" not "Scandinavian-Inspired Modern Minimalism"
- Measurements and practical info in captions, inspiration in headers.

### Motion & Microinteractions
- Transformation reveals: 600ms dissolve transition
- Card appearances: 300ms fade-up
- Navigation: 200ms ease-out
- Upload progress: Smooth gradient animation along bottom edge
- Success states: Subtle confetti particles in brand colors

### Content Hierarchy
1. Hero image (original or transformed space)
2. Transformation controls
3. Style options/variations
4. Technical details
5. Share/Save actions

### Key Differentiators from References
- Navigation simplicity, emotional warmth
- Cards feel like design magazines, not listings or rewards
- Empty states inspire rather than welcome or exclude
- Colors support but never overshadow user content

## Context

### App Overview

We are building a consumer focused interior design app for Home Owners and Renters. The idea is that users can upload images of a space (either empty or filled), and the app can help them re-imagine the space using LLMs

### Task

Follow the guidelines above precisely to ensure correctness. Your output should be a horizontal series of vertical screens showcasing each view specified below:

**Give me 3 looks of the following screen. Each should be a unique take on the core concept, but conform to the overall app style and philosophy:**

#### 1. First-Time Empty State
- Large dashed border area with subtle pulse animation
- Camera icon with "Tap to photograph your space"
- Carousel below showing "Before/After" examples from other users
- "Or browse inspiration" secondary CTA

## Output

Make sure your outputs are being properly rendered via the main app root of Create React App. Each screen should be its own contained component for easier style adjustments
