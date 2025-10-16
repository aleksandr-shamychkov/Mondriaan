# Copilot Instructions for Mondriaan HTML-CSS Project

## Overview
This project is a static HTML/CSS implementation inspired by the style of Piet Mondriaan. It is intended for visual layout practice and does not include JavaScript, build tools, or external dependencies.

## Key Files
- `index.html`: Main entry point. Contains all markup for the Mondriaan-style layout.
- `README.md`: Minimal project description. No build/test instructions present.

## Architecture & Patterns
- **Single-page static site**: All content is in `index.html`. No routing, no dynamic content.
- **CSS organization**: If CSS is present, it is likely inline or in a `<style>` block within `index.html`. No external CSS files detected.
- **Mondriaan layout**: Use of HTML elements and CSS (likely flexbox or grid) to create geometric, colored block layouts. Follow the visual style of Mondriaan paintings.

## Developer Workflow
- **No build or test steps**: Open `index.html` directly in a browser to view changes.
- **No package management**: No `package.json`, `node_modules`, or other dependency managers.
- **No automated linting or formatting**: Manual code style only.

## Project Conventions
- **Semantic HTML**: Use appropriate tags for structure (e.g., `<div>`, `<section>`, `<main>`).
- **CSS best practices**: Prefer classes for styling blocks. Avoid inline styles unless necessary for layout precision.
- **Color palette**: Use primary colors (red, blue, yellow), black, and white to match Mondriaan's style.
- **Responsiveness**: If adding CSS, consider using `display: grid` or `flex` for layout. Mobile responsiveness is optional but encouraged.

## Examples
- To add a new block: Insert a `<div class="block block-red"></div>` in `index.html` and style with CSS.
- To change layout: Edit the CSS in the `<style>` section of `index.html`.

## Integration Points
- No external APIs or integrations.
- No cross-component communication (single file only).

## How to Contribute
- Edit `index.html` directly for all changes.
- Keep the layout visually consistent with Mondriaan's style.
- Document any major layout changes in `README.md`.

---
For questions or unclear conventions, ask for clarification or review Mondriaan paintings for visual reference.
