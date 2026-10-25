# toBATO.to Dashboard

A responsive and accessible dashboard interface inspired by a manga and web-comic reading platform. The project demonstrates semantic HTML5, responsive CSS3 design, and JavaScript-based sidebar interactions.

##  About the Project

**toBATO.to Dashboard** is a responsive web interface containing a collapsible sidebar navigation and category cards for Manga, Manhwa, Manhua, Webtoon, Webnovel, and Novel.

The project focuses on clean layout, accessibility, responsive behavior, and smooth sidebar and card animations.

##  Features

- Responsive sidebar navigation
- Open/close sidebar toggle
- Mobile-friendly navigation
- Manga, Manhwa, Manhua, Webtoon, Webnovel, and Novel category cards
- Category banner images
- Keyboard support using the `Escape` key
- ARIA attributes for accessibility
- Focus management when opening and closing the sidebar
- Responsive layout using CSS Grid and Flexbox
- Smooth transitions and animations
- Reduced-motion support
- Light and dark color-scheme support

##  Technologies Used

- **HTML5** – Semantic page structure and accessible navigation
- **CSS3** – Responsive layout, Grid, Flexbox, transitions, media queries, and custom properties
- **JavaScript ES6+** – DOM manipulation, event handling, sidebar state management, and responsive behavior

##  Project Structure

```text
toBATO/
│
├── index.html
├── style.css
├── script.js
├── problem statement.md
│
└── images/
    ├── logo1.png
    ├── tobatomanga.png
    ├── tobatomanhwa.png
    ├── tobatomanhua.png
    ├── tobatowebtoon.png
    ├── tobatowebnovel.png
    └── tobatonovels.png
```

##  HTML Structure

The HTML provides a semantic layout containing:

- Sidebar navigation
- Logo and brand area
- Navigation links
- Sidebar toggle buttons
- Main dashboard content
- Category cards
- Footer

The category cards use background images through CSS custom properties.

##  CSS Features

The stylesheet uses CSS custom properties, Flexbox, CSS Grid, responsive media queries, transitions, focus indicators, and dark-mode support.

The sidebar changes between a desktop collapsible layout and a mobile slide-out navigation. 

The category cards display their banner images when hovered, focused, or activated.

##  JavaScript Functionality

JavaScript controls the sidebar state and user interactions.

Main functionality includes:

- Opening and closing the sidebar
- Updating `aria-expanded`
- Managing sidebar focus
- Closing the sidebar with the `Escape` key on mobile
- Automatically closing the sidebar after selecting a navigation item on mobile
- Detecting screen-size changes

These behaviors are implemented using DOM manipulation, event listeners, and `matchMedia()`. 

##  Accessibility

Accessibility considerations include:

- Semantic HTML elements
- ARIA labels
- `aria-expanded`
- `aria-current`
- Keyboard navigation
- Visible focus indicators
- Focus management
- `inert` sidebar state when closed
- Reduced-motion support

##  Responsive Design

The interface adapts to different screen sizes.

On desktop, the sidebar appears alongside the main content. On smaller screens, the sidebar becomes a slide-out panel with a menu button and overlay.


##  Project Objective

The objective is to develop a responsive and accessible sidebar navigation component using HTML5, CSS3, and JavaScript ES6+, while applying semantic HTML, WCAG/ARIA practices, responsive design, DOM manipulation, event handling, and smooth CSS transitions.

##  Author

**Mahmuda Adeeba Tul Husna**

© 2026 toBATO | Adeeba
