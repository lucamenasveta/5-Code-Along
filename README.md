# 5-Code-Along: Copper City Makerspace

Copper City Makerspace started as a single-page website telling the community about its services. In this code-along it grew into a four-page, responsive website published with GitHub Pages.

## Pages
- `index.html`: Home page with a welcome, overview cards linking to each section, and the upcoming event.
- `about.html`: Mission, who we serve, and community impact.
- `workshops.html`: Digital fabrication, electronics and coding, and wood and metal shops.
- `memberships.html`: Getting started, hours and location, and volunteering.

## What changed
- **Multi-page structure:** Each section of the original single page was moved into its own HTML file. Every page shares the same header, navigation, and footer for a consistent experience.
- **Relative links:** The navigation uses relative paths (`about.html`, `workshops.html`, etc.) instead of `#` anchors, so the project works on any computer or server as a self-contained folder. The current page is marked with `aria-current="page"` and highlighted.
- **Mobile-first CSS:** Base styles in `styles.css` target small screens (stacked nav and single-column cards). A `min-width: 768px` media query adds a horizontal nav and three-column card rows for medium screens and up.
- **Accessibility:** Every image now has meaningful alt text describing its content and purpose. The HTML stays semantic (`header`, `nav`, `main`, `section`, `aside`, `footer`).

## Workflow
1. Forked the starter repository on GitHub.
2. Cloned the fork with GitHub Desktop and opened it in VS Code.
3. Created the new pages, updated navigation on all four files, and added the media query.
4. Documented the project in this README.
5. Committed with a descriptive message, pushed to origin, and published with GitHub Pages (Settings > Pages > Deploy from branch `main` / root).
6. Checked the live site on every page to confirm navigation and images load.

## Tech
- HTML5 (semantic, validated)
- CSS3 (Flexbox, mobile-first media query)
- No JavaScript
