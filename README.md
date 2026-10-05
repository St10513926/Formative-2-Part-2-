# Sneaker District SA — Part 1 & Part 2

## Student Information
- Student Name: Siyabonga Msimango
- Student Number: ST10513926
- Subject: WED5020
- Group: 1

## Project Overview
Sneaker District SA is a fictional South African sneaker and streetwear retailer created for the web-development portfolio. Part 1 established the HTML foundation, navigation, content plan, sitemap, sourcing notes and repository structure. Part 2 develops the visual layer with an external CSS stylesheet, desktop layout, typography, visual styling, responsive breakpoints, relative units, responsive images and interactive CSS states.

## Part 2 Scope
The Part 2 implementation addresses the brief by:
- Linking all pages to one external stylesheet: `css/style.css`.
- Applying a consistent base style, reset and design-token system.
- Using CSS Grid and Flexbox for page layouts.
- Applying a typography scale using `clamp()`, `rem`, line-height and letter-spacing.
- Using colour, borders, shadows and transitions for visual styling.
- Adding `:hover`, `:focus-visible` and `:active` states.
- Implementing desktop, tablet and mobile breakpoints.
- Switching multi-column layouts to single-column layouts on smaller screens.
- Using relative units and percentages for responsive sizing.
- Using `<picture>`, `srcset` and `sizes` for responsive image delivery.
- Including a reduced-motion accessibility preference.
- Preparing the website for browser developer-tool testing.

## Design System
### Colour Palette
- Charcoal: `#111111`
- Off-white: `#F7F5F0`
- White: `#FFFFFF`
- Accent orange-red: `#E94F37`
- Dark accent: `#B93422`
- Border: `#DEDBD4`

### Typography
- Primary font: Aptos
- Fallbacks: Segoe UI, Arial, sans-serif
- Headings: responsive `clamp()` scale, bold/black weights, tight line-height
- Body: approximately 1rem with 1.6 line-height
- Navigation: bold, compact and touch-friendly

## Layout Techniques
The website uses:
- Flexbox for the header/navigation.
- CSS Grid for cards, two-column content and footer.
- `min()`, `clamp()`, percentages, `rem` and `minmax()` for fluid sizing.
- Three main responsive states:
  - Desktop: above 64rem
  - Tablet: 48rem–64rem
  - Mobile: 30rem–48rem
  - Small mobile: below 30rem

## Responsive Images
The homepage hero uses a `<picture>` element with mobile, tablet and desktop SVG sources. The `srcset` and `sizes` attributes provide responsive image candidates. Product images also include `srcset` and `sizes`.

## Part 1 Feedback / Correction Log
No lecturer-specific Part 1 feedback was supplied with the Part 2 brief in this working package. Therefore, the following are self-review corrections/refinements rather than invented lecturer feedback:
- Improved content hierarchy and consistency across pages.
- Added stronger semantic/accessible focus treatment.
- Added SEO author metadata.
- Reworked the homepage visual hierarchy for the retail scenario.
- Added clearer product imagery and product cards.
- Prepared the site for responsive testing and Part 2 screenshots.
- Expanded the README documentation for Part 2.

If the lecturer provides specific Part 1 feedback, add each item here with the date and exact correction made.

## Screenshot Evidence
The following screenshots were produced from the Part 2 website at fixed browser viewport sizes:
- `images/screenshots/home-desktop-1440x900.png` — desktop
- `images/screenshots/home-tablet-1024x768.png` — tablet
- `images/screenshots/home-mobile-390x844.png` — mobile
- `images/screenshots/products-mobile-390x844.png` — mobile products page

### Desktop
![Desktop screenshot](images/screenshots/home-desktop-1440x900.png)

### Tablet
![Tablet screenshot](images/screenshots/home-tablet-1024x768.png)

### Mobile
![Mobile screenshot](images/screenshots/home-mobile-390x844.png)

### Mobile Products
![Mobile products screenshot](images/screenshots/products-mobile-390x844.png)

## Browser Developer Tools Testing Plan
Use Chrome/Edge DevTools to test:
1. 1440 × 900 desktop.
2. 1024 × 768 tablet.
3. 390 × 844 mobile.
4. Landscape mobile where available.
5. Keyboard-only navigation and visible focus.
6. Console for JavaScript errors.
7. Network panel to check that CSS and image assets load correctly.
8. Device emulation for different pixel ratios.

## Browser Compatibility
Recommended testing:
- Google Chrome
- Microsoft Edge
- Mozilla Firefox
- Safari where available

## Part 2 Changelog
### 2026-10-04 — Part 2 visual implementation
- Replaced the basic stylesheet with a structured external CSS system.
- Added a CSS reset and reusable design tokens.
- Added desktop layout using Flexbox and CSS Grid.
- Added responsive typography using `clamp()`.
- Added visual styling including colour, borders, shadows and transitions.
- Added interactive `:hover`, `:focus-visible` and `:active` states.
- Added tablet and mobile media queries.
- Added relative units including `rem`, `%`, `min()`, `minmax()` and `clamp()`.
- Added responsive `<picture>`, `srcset` and `sizes` image handling.
- Added original responsive hero and product SVG assets.
- Added reduced-motion accessibility support.
- Added screenshot evidence for desktop, tablet and mobile testing.
- Updated README documentation for Part 2.

## Suggested Git Commits
1. `Part 2: update stylesheet and design tokens`
2. `Part 2: add desktop grid and flexbox layouts`
3. `Part 2: add responsive typography and visual states`
4. `Part 2: add tablet and mobile breakpoints`
5. `Part 2: add responsive image assets`
6. `Part 2: update page content and accessibility`
7. `Part 2: add device screenshot evidence`
8. `Part 2: update README and references`

## Submission Requirements Checklist
- [x] Updated HTML files
- [x] External CSS stylesheet
- [x] Desktop styling
- [x] Responsive tablet styling
- [x] Responsive mobile styling
- [x] Relative units
- [x] Responsive images
- [x] Screenshot evidence
- [x] README updated
- [x] Changelog updated
- [x] References retained and updated
- [ ] Private GitHub repository created/updated
- [ ] GitHub repository link submitted to LMS
- [ ] Student details replaced in README

## References
- W3C Web Accessibility Initiative. (2026). W3C Accessibility Standards Overview. https://www.w3.org/WAI/standards-guidelines/
- W3C Web Accessibility Initiative. (2026). WCAG 2 Overview. https://www.w3.org/WAI/standards-guidelines/wcag/
- W3C Web Accessibility Initiative. (2026). Content Structure. https://www.w3.org/WAI/tutorials/page-structure/content/
- MDN Web Docs. (2026). CSS media queries. https://developer.mozilla.org/en-US/docs/Web/CSS/Guides/Media_queries
- MDN Web Docs. (2026). CSS Grid Layout. https://developer.mozilla.org/en-US/docs/Web/CSS/Guides/Grid_layout
- MDN Web Docs. (2026). CSS Flexible Box Layout. https://developer.mozilla.org/en-US/docs/Web/CSS/Guides/Flexible_box_layout
- MDN Web Docs. (2026). Responsive images. https://developer.mozilla.org/en-US/docs/Web/HTML/Guides/Responsive_images
- GitHub Docs. (2026). Quickstart for repositories. https://docs.github.com/en/repositories/creating-and-managing-repositories/quickstart-for-repositories
