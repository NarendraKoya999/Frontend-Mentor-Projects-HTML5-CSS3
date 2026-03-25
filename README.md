<div align="center">

<img src="https://img.shields.io/badge/Frontend%20Mentor-UI%20Component%20Challenges-3F54A3?style=for-the-badge&logo=frontendmentor&logoColor=white" alt="Frontend Mentor Projects"/>

# Frontend Mentor — UI Component Challenges
### 7 Real-World Component Builds · Pixel-Perfect Implementations

A curated collection of professionally designed UI components built from real-world briefs
provided by [Frontend Mentor](https://www.frontendmentor.io/) — the industry-standard platform
for practicing production-quality frontend development.

<br/>

[![Frontend Mentor](https://img.shields.io/badge/Platform-Frontend%20Mentor-3F54A3?style=flat-square)](https://www.frontendmentor.io/)
[![Components](https://img.shields.io/badge/Components-7%20Completed-27ae60?style=flat-square)](/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](/)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](/)
[![Responsive](https://img.shields.io/badge/Responsive%20Design-✓-8e44ad?style=flat-square)](/)
[![Pixel Perfect](https://img.shields.io/badge/Pixel--Perfect-✓-e67e22?style=flat-square)](/)

<br/>

> *"Real design briefs. Real constraints. Real components —*
> *built to match professional Figma specs without any framework assistance."*

<br/>

🔗 **[View Frontend Mentor Profile](https://www.frontendmentor.io/)**

<br/>

[Overview](#overview) &nbsp;•&nbsp; [Skills](#skills-demonstrated) &nbsp;•&nbsp; [Components](#component-gallery) &nbsp;•&nbsp; [What This Shows](#what-this-demonstrates)

</div>

---

## Overview

This repository contains **7 UI component projects** completed on [Frontend Mentor](https://www.frontendmentor.io/) — a platform trusted by over 500,000 developers worldwide for practicing frontend skills against professionally designed, real-world briefs.

Each challenge provides a Figma or image design specification and requires the developer to implement a pixel-accurate, responsive HTML and CSS solution entirely from scratch — no starter CSS, no component libraries, no UI frameworks.

These projects demonstrate the ability to translate a visual design into clean, semantic, maintainable frontend code — a core skill evaluated in frontend engineering interviews and client projects globally.

---

## Skills Demonstrated

| Category | Skills |
|----------|--------|
| **HTML5** | Semantic structure, accessibility, image handling, proper element hierarchy |
| **CSS3** | Flexbox layout, custom properties, hover states, `border-radius`, `box-shadow` |
| **Responsive Design** | Fluid layouts that adapt across mobile, tablet, and desktop breakpoints |
| **Visual Precision** | Matching typography, spacing, color, and layout to professional design specs |
| **Component Architecture** | Self-contained, reusable UI components with clean, maintainable code |
| **UI/UX Awareness** | Translating design intent into interactive, accessible web components |

---

## Component Gallery

---

### 1. 3-Column Preview Card Component

> **Multi-column layout component for a vehicle category showcase.**

A three-panel card component presenting Sedans, SUVs, and Luxury vehicles in a horizontally arranged layout. Each column features a category icon, descriptive body copy, and a styled "Learn More" CTA button — with distinct color themes per column.

**Design challenge:** Managing equal-height columns with independent color schemes while maintaining consistent internal spacing and button alignment across all three panels.

| Detail | Implementation |
|--------|---------------|
| Layout | CSS Flexbox — three equal-width columns |
| Hover states | Button hover with color inversion effect |
| Responsive | Stacks to single column on mobile |
| Typography | Weight and size hierarchy per design spec |

**Key Skills:** CSS Flexbox · Multi-column layout · Hover interactions · Color theming per column · Responsive stacking

[![HTML5](https://img.shields.io/badge/HTML5-%23E34F26.svg?style=flat-square&logo=html5&logoColor=white)](/)
[![CSS3](https://img.shields.io/badge/CSS3-%231572B6.svg?style=flat-square&logo=css3&logoColor=white)](/)

---

### 2. NFT Preview Card Component

> **Digital collectible card with overlay interaction and creator attribution.**

A polished NFT preview card displaying a digital artwork image, token name, description, ETH price, time remaining, and creator profile. Features an image overlay effect on hover — revealing a view icon over the NFT artwork.

**Design challenge:** Implementing the image hover overlay using CSS `position`, `opacity`, and transition — without JavaScript — while maintaining exact color values and spacing from the design file.

| Detail | Implementation |
|--------|---------------|
| Hover overlay | CSS `position: absolute` with `opacity` transition |
| ETH + clock icons | Inline SVG icons with precise sizing |
| Creator row | Flex row with circular avatar, border, and attribution text |
| Color accuracy | Dark navy background `hsl(217, 54%, 11%)` matched to spec |

**Key Skills:** CSS overlay effect · Opacity transitions · Flexbox for metadata rows · SVG icon integration · Dark theme implementation

[![HTML5](https://img.shields.io/badge/HTML5-%23E34F26.svg?style=flat-square&logo=html5&logoColor=white)](/)
[![CSS3](https://img.shields.io/badge/CSS3-%231572B6.svg?style=flat-square&logo=css3&logoColor=white)](/)

---

### 3. Order Summary Card

> **E-commerce subscription summary card with interactive call-to-action elements.**

A payment confirmation UI component presenting a subscription plan summary — service description, pricing tier, plan change option, payment CTA, and a cancel link. Designed to match the kind of confirmation screen seen in SaaS and subscription-based products.

**Design challenge:** Achieving the layered card appearance with a background illustration, internal pricing row with distinct background, and precisely styled primary and ghost CTA buttons.

| Detail | Implementation |
|--------|---------------|
| Background art | Hero image positioned above the card using CSS |
| Pricing row | Nested flex container with icon, plan details, and change link |
| Primary CTA | `box-shadow` and `border-radius` with hover color shift |
| Cancel link | Subtle text link with hover underline behavior |

**Key Skills:** Layered card composition · Nested Flexbox · Button states · Background image integration · Subscription UI patterns

[![HTML5](https://img.shields.io/badge/HTML5-%23E34F26.svg?style=flat-square&logo=html5&logoColor=white)](/)
[![CSS3](https://img.shields.io/badge/CSS3-%231572B6.svg?style=flat-square&logo=css3&logoColor=white)](/)

---

### 4. Product Preview Card Component

> **E-commerce product card with responsive image swap and pricing display.**

A luxury perfume product card component of the kind found on e-commerce product listing pages. Displays a product image, category label, product name, description, discounted price with original strikethrough, and an add-to-cart button with a shopping cart icon.

**Design challenge:** Implementing a responsive image swap — different images served at mobile vs desktop breakpoints using `<picture>` and `srcset` — without any JavaScript or layout shift.

| Detail | Implementation |
|--------|---------------|
| Responsive image | `<picture>` with `<source media="(min-width: 600px)">` for desktop art |
| Pricing display | Discounted price prominent; original price in muted strikethrough |
| Add-to-cart button | Flex row with SVG cart icon, hover color transition |
| Two-column layout | CSS Grid at desktop; single column stacked at mobile |

**Key Skills:** `<picture>` element for responsive images · CSS Grid for two-column card · Strikethrough pricing pattern · Hover CTA states · E-commerce UI conventions

[![HTML5](https://img.shields.io/badge/HTML5-%23E34F26.svg?style=flat-square&logo=html5&logoColor=white)](/)
[![CSS3](https://img.shields.io/badge/CSS3-%231572B6.svg?style=flat-square&logo=css3&logoColor=white)](/)

---

### 5. Profile Card Component

> **Social media profile card with background pattern and social statistics.**

A personal profile card displaying a user avatar, name, age, location, and a three-column social statistics row (followers, likes, photos). Features a two-tone background with intersecting curved SVG shapes — a precise CSS positioning challenge.

**Design challenge:** Positioning two decorative background circle SVGs — one in the top-left, one in the bottom-right — so they appear to extend beyond the card boundaries without causing scroll or overflow at any viewport size.

| Detail | Implementation |
|--------|---------------|
| Background pattern | Two SVG circles positioned with `position: absolute` at card corners |
| Avatar border | Circular `border-radius: 50%` with `border: 3px solid white` |
| Stats row | Three-column Flex layout with vertical label+value pairs |
| Dividers | `border-right` separators between stat columns |

**Key Skills:** Absolute positioning for decorative elements · `overflow: hidden` management · Circular avatar styling · Stat grid layout · Social card UI pattern

[![HTML5](https://img.shields.io/badge/HTML5-%23E34F26.svg?style=flat-square&logo=html5&logoColor=white)](/)
[![CSS3](https://img.shields.io/badge/CSS3-%231572B6.svg?style=flat-square&logo=css3&logoColor=white)](/)

---

### 6. Results Summary Component

> **Assessment results card with category breakdown and score visualization.**

A two-panel results card of the type used in ed-tech and assessment platforms. The left panel shows an overall score inside a circular gradient display; the right panel lists four performance categories (Reaction, Memory, Verbal, Visual) each with an icon, category score, and color-coded background.

**Design challenge:** Creating the circular score display using CSS — achieving the gradient ring effect and centered score percentage — and matching the four individually color-themed category rows without repeating CSS unnecessarily.

| Detail | Implementation |
|--------|---------------|
| Circular score | CSS `border-radius: 50%` with `background: linear-gradient()` |
| Category rows | Four flex rows, each with unique `background-color` at low opacity |
| Color coding | Reaction (red), Memory (yellow), Verbal (teal), Visual (blue) |
| Two-panel layout | CSS Grid — score panel left, summary list right |
| Responsive | Stacks vertically on mobile; two columns on desktop |

**Key Skills:** Circular gradient UI element · CSS Grid two-panel layout · Color-coded category rows · `rgba` tinted backgrounds · Assessment dashboard UI pattern

[![HTML5](https://img.shields.io/badge/HTML5-%23E34F26.svg?style=flat-square&logo=html5&logoColor=white)](/)
[![CSS3](https://img.shields.io/badge/CSS3-%231572B6.svg?style=flat-square&logo=css3&logoColor=white)](/)

---

### 7. Stats Preview Card Component

> **Business analytics card with image overlay tint and three-column statistics.**

A data analytics marketing card featuring a headline, body copy, a three-column statistics row, and a product image with a colored overlay tint — the kind of component seen on SaaS and analytics platform landing pages.

**Design challenge:** Applying a specific violet color overlay tint to the image without altering the underlying image file — achieved using CSS `mix-blend-mode` or an absolutely positioned pseudo-element with `opacity`.

| Detail | Implementation |
|--------|---------------|
| Image tint overlay | `::after` pseudo-element with `mix-blend-mode: multiply` |
| Two-column layout | CSS Grid — content left, image right at desktop |
| Stats row | Three inline stat blocks with label and large numeric value |
| Responsive | Image moves above content at mobile; full-width stacked layout |

**Key Skills:** CSS `mix-blend-mode` for image tinting · Pseudo-element overlays · CSS Grid for content/image split · Statistics display layout · B2B SaaS card UI pattern

[![HTML5](https://img.shields.io/badge/HTML5-%23E34F26.svg?style=flat-square&logo=html5&logoColor=white)](/)
[![CSS3](https://img.shields.io/badge/CSS3-%231572B6.svg?style=flat-square&logo=css3&logoColor=white)](/)

---

## What This Demonstrates

Frontend Mentor challenges are specifically designed to evaluate skills that matter in professional frontend roles:

- **Design fidelity** — working from a Figma or image spec and producing a pixel-accurate implementation without any guessing
- **No training wheels** — no Bootstrap, no Tailwind, no pre-built components — every visual detail achieved with hand-written HTML and CSS
- **Component thinking** — each build is a self-contained, reusable module with clear structure and clean code
- **Responsive behavior** — every component adapts correctly across mobile, tablet, and desktop without layout breakage
- **Attention to detail** — hover states, opacity transitions, spacing, border-radius, and color values matched to specification
- **Real-world UI patterns** — e-commerce cards, profile components, assessment dashboards, subscription summaries — the actual components that appear in production applications internationally

---

## Tech Stack

<div align="center">

| Technology | Usage | Level |
|-----------|-------|-------|
| **HTML5** | Semantic structure, `<picture>` element, accessible markup | Advanced |
| **CSS3** | Flexbox, Grid, custom properties, transitions, pseudo-elements | Advanced |
| **CSS Flexbox** | Component internal layouts, metadata rows, stat columns | Advanced |
| **CSS Grid** | Two-column card layouts, responsive reflow | Proficient |
| **CSS Transitions** | Hover states, overlay reveals, button interactions | Proficient |
| **Responsive Design** | Mobile-first media queries, viewport-aware layouts | Advanced |
| **SVG Integration** | Inline icons, background decorative elements | Intermediate |

</div>

---

## Repository Structure

```
frontend-mentor-challenges/
│
├── 01-3-column-preview-card/
│   ├── index.html
│   ├── styles.css
│   └── assets/
│
├── 02-nft-preview-card/
│   ├── index.html
│   ├── styles.css
│   └── assets/
│
├── 03-order-summary-card/
│   ├── index.html
│   ├── styles.css
│   └── assets/
│
├── 04-product-preview-card/
│   ├── index.html
│   ├── styles.css
│   └── assets/
│
├── 05-profile-card-component/
│   ├── index.html
│   ├── styles.css
│   └── assets/
│
├── 06-results-summary-component/
│   ├── index.html
│   ├── styles.css
│   └── assets/
│
├── 07-stats-preview-card/
│   ├── index.html
│   ├── styles.css
│   └── assets/
│
└── README.md
```

Each project is self-contained and runs directly in the browser — no build tools, bundlers, or package managers required.

---

## Running Locally

```bash
# Clone this repository
git clone https://github.com/NarendraKoya999/Frontend-Mentor-Projects-HTML5-CSS3.git

# Navigate to any component folder
cd Frontend-Mentor-Projects-HTML5-CSS3/stats-preview-card-component-main

# Open directly in your browser
open index.html

# Recommended: use VS Code Live Server for instant live reload during review
```

---

## About Frontend Mentor

[Frontend Mentor](https://www.frontendmentor.io/) provides professionally designed UI challenges across all difficulty levels — from beginner card components through advanced multi-page applications with API integrations. It is used by developers worldwide to build a portfolio of real-world components that demonstrate client-ready frontend skills.

Every challenge in this repository was completed against a professional design specification without using any CSS framework, component library, or template — only hand-written HTML and CSS.

---

## Connect With Me

<div align="center">

I am actively open to frontend development roles, UI engineering positions, freelance component work, and international client collaborations.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/narendra-koya)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/NarendraKoya999)
[![Frontend Mentor](https://img.shields.io/badge/Frontend%20Mentor-Profile-3F54A3?style=flat-square)](https://www.frontendmentor.io/profile/your-username)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-ff6b6b?style=flat-square&logo=vercel&logoColor=white)](https://narendrakoya999.github.io/Personal-Portfolio-Website/)
[![Email](https://img.shields.io/badge/Email-Contact-D44638?style=flat-square&logo=gmail&logoColor=white)](mailto:narendra.koya.in@gmail.com)

</div>

---

<div align="center">

**Built to specification · No frameworks · Pure HTML and CSS**

*Every component was implemented by hand against a professional design brief —*
*matching layout, spacing, color, typography, and interaction states to pixel-level accuracy.*

<br/>

⭐ If this work impressed you, a star on the repository is always appreciated.

</div>
