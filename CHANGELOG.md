# Changelog

## Part 2, September 2026

### Structure and stylesheet
- Kept seven separate HTML pages for the required website content.
- Linked the same external stylesheet, `css/style.css`, from every page.
- Added shared CSS variables for colours, sizing, borders, shadows and the content width.
- Added a consistent reset and default styling for body text, headings, links, images, forms and buttons.

### Responsive design
- Added three breakpoints at 980px, 760px and 520px.
- Changed multi-column grids to stacked layouts at smaller widths.
- Adjusted heading sizes and supporting text using `clamp()` and relative units.
- Changed the navigation from a desktop flex row to a tablet wrapped row and a mobile grid.
- Added responsive image sources with `picture`, `srcset` and `sizes`.

### Pseudo-classes and interaction
- Added `:hover`, `:active` and `:focus-visible` states to links and buttons.
- Added focus, valid and invalid styles to form controls.
- Added hover treatment for cards and gallery images.
- Added `aria-current="page"` to the current navigation link instead of using JavaScript.

### JavaScript decision
- Removed `js/script.js`.
- The Part 2 rubric assesses HTML and CSS skills, including external CSS, pseudo-classes, media queries and responsive navigation.
- The mobile navigation now uses CSS media queries and does not depend on JavaScript.
- The contact form uses normal HTML form controls and browser validation.

### Part 1 feedback record
The actual lecturer feedback from Part 1 was not included in the supplied files available for this build. It should be added here before final submission. Do not replace it with invented feedback.

| Part 1 feedback | Change made in Part 2 | Where to verify |
|---|---|---|
| Insert exact lecturer feedback here | Record the matching Part 2 change | Page or file |
| Insert exact lecturer feedback here | Record the matching Part 2 change | Page or file |
| Insert exact lecturer feedback here | Record the matching Part 2 change | Page or file |

### Evidence prepared
- Desktop screenshot: `docs/screenshots/home-desktop.png`
- Tablet screenshot: `docs/screenshots/home-tablet.png`
- Mobile screenshot: `docs/screenshots/home-mobile.png`

## CSS visibility update, September 2026
- Increased border visibility on cards, image blocks, inputs and gallery items.
- Made button styling more obvious through solid borders, background colours and hover states.
- Added clear navigation hover, active and focus-visible effects.
- Added visible card hover and active states using borders, shadows and transforms.
- Added clear form focus, valid and invalid states.
- Kept the responsive breakpoints at 980px, 760px and 520px so layout, typography and navigation changes remain easy to demonstrate.
- Removed JavaScript so the project relies on HTML and CSS for the Part 2 requirements.