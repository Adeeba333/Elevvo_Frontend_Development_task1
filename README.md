# toBATO.to — Responsive Sidebar Dashboard

A responsive dashboard interface for **toBATO.to**, designed as a frontend development task focusing on sidebar navigation, responsive layouts, accessibility, and smooth UI interactions.

## Overview

This project implements a clean dashboard layout with a collapsible sidebar and content cards for different reading categories such as Manga, Manhwa, Manhua, Webtoon, Webnovel, and Novel.

The interface is built using **HTML5, CSS3, and vanilla JavaScript**, with a strong focus on semantic structure, responsive behavior, keyboard accessibility, and reusable styling.

## Features

- Responsive collapsible sidebar navigation
- Desktop and mobile sidebar behavior
- Dashboard category cards with image backgrounds
- SVG-based navigation icons
- Accessible buttons and navigation using ARIA attributes
- Keyboard support with the `Escape` key
- Responsive behavior using `matchMedia()`
- Smooth sidebar and card animations
- Hover, focus, and tap interactions
- `prefers-reduced-motion` support
- CSS custom properties for reusable design values
- Mobile overlay/scrim when the sidebar is open
- Safe-area support for modern mobile devices

## Technologies Used

- **HTML5** — Semantic page structure and accessible navigation
- **CSS3** — Grid, Flexbox, custom properties, media queries, transitions, and responsive design
- **JavaScript ES6+** — DOM manipulation, event handling, `matchMedia()`, and state management
- **SVG** — Lightweight reusable navigation icons

## Project Structure

```text
toBATO/
│
├── index.html
├── style.css
├── script.js
│
└── images/
    ├── logo1.png
    ├── tobatomanga.jpg
    ├── tobatomanhwa.jpg
    ├── tobatomanhua.jpg
    ├── tobatowebtoon.jpg
    ├── tobatowebnovels.jpg
    └── tobatonovels.jpg
```

## Technical Implementation

### Responsive Sidebar

The sidebar uses a data attribute to manage its state:

```html
<div class="app" data-sidebar="open">
```

JavaScript switches the state between `open` and `closed`, while CSS controls the corresponding layout and animation.

On smaller screens, the sidebar becomes a fixed off-canvas navigation panel with an overlay behind it.

### Accessibility

The project uses ARIA attributes such as:

- `aria-label`
- `aria-expanded`
- `aria-controls`
- `aria-current`
- `aria-hidden`

This allows the sidebar controls and navigation to provide clearer information to assistive technologies.

### Responsive JavaScript

The project uses:

```javascript
window.matchMedia("(max-width: 48rem)")
```

to detect the mobile breakpoint and automatically adjust the sidebar state when the viewport changes.

### Keyboard Interaction

Pressing **Escape** closes the sidebar on mobile devices.

Navigation links also close the mobile sidebar after selection, improving the mobile browsing experience.

### CSS Architecture

The stylesheet uses CSS custom properties for reusable values such as:

- Colors
- Sidebar width
- Header height
- Animation duration
- Transition timing

The card components also use CSS variables to control their interactive image banner behavior.

### Reduced Motion

The project respects users who prefer reduced animation through:

```css
@media (prefers-reduced-motion: reduce)
```

Animations are minimized for a more accessible experience.

## Learning Focus

This project demonstrates practical frontend development concepts including:

- Semantic HTML structure
- Responsive CSS layouts
- CSS Grid and Flexbox
- DOM manipulation
- Event listeners
- Responsive JavaScript
- Accessibility and ARIA
- CSS animations and transitions
- Mobile-first interaction patterns
- Reusable component styling

## Author

**Mahmuda Adeeba Tul Husna**

Frontend Development Task — toBATO.to
