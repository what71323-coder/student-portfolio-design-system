PROJECT TITLE
Day 12 - Student Developer Portfolio Design System

PROJECT DESCRIPTION
This is a one-page student developer portfolio built using HTML5
and CSS3. It includes a hero section, about section, six skills,
three project cards, a contact section and a footer.

The project demonstrates CSS custom properties, reusable component
classes, responsive layouts, hover effects and accessibility basics.

CSS VARIABLES CREATED
1. --color-primary: Main brand color and buttons.
2. --color-primary-dark: Darker button and link hover color.
3. --color-accent: Accent and status indicator color.
4. --color-background: Main page background.
5. --color-surface: Card and header backgrounds.
6. --color-text: Main text color.
7. --color-muted: Secondary text color.
8. --color-border: Borders.
9. --color-soft: Soft section and tag backgrounds.
10. --space-xs, --space-sm, --space-md, --space-lg, --space-xl:
    Reusable spacing values.
11. --space-section: Vertical section spacing.
12. --radius-sm, --radius-md, --radius-card, --radius-pill:
    Reusable corner radius values.
13. --shadow-card and --shadow-hover: Card shadow effects.
14. --container-width: Maximum content width.
15. --transition-fast: Shared transition duration and timing.

REUSABLE CLASSES
.container - Consistent content width.
.button - Shared button design.
.button-outline - Outline button variation.
.card - Shared card appearance and hover effect.
.section - Consistent section spacing.
.section-heading - Shared section heading layout.
.skills-grid - Responsive skills layout.
.projects-grid - Responsive project card layout.
.tag-list - Shared project technology tags.

RESPONSIVE DESIGN
Mobile: approximately 375px.
Tablet: approximately 768px.
Desktop: approximately 1280px.

The layout uses CSS Grid, Flexbox and media queries.
Project cards stack on small screens and display in columns
on larger screens.

ACCESSIBILITY
Semantic HTML sections and landmarks are used.
Visible keyboard focus styles are included.
Text links have descriptive labels.
Decorative initials are hidden from screen readers.
Project illustrations have descriptive accessible labels.
Reduced-motion preferences are respected.

HOW TO OPEN
1. Keep index.html and style.css in the same folder.
2. Open index.html in a web browser.
3. Resize the browser to test different screen widths.
4. Edit the variables inside :root in style.css to test
   consistent design changes.

TECHNOLOGIES
HTML5 and CSS3 only.
No JavaScript or CSS frameworks.