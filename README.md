# Tea Cozy — Responsive Design

A static recreation of the Tea Cozy café website, built from a wireframe as a hands-on exercise in turning a visual layout into a responsive page. The wireframe provides the blueprint; the work is in translating its sections, spacing, imagery, and content into HTML and CSS that hold together across screen sizes.

## From wireframe to webpage

Rather than starting with an open-ended design, this project follows an existing visual plan. The page is organized into the same clear sequence a visitor would expect from a café website: a branded navigation bar, a mission statement, featured tea, shop locations, and contact details. CSS Flexbox brings the repeated content into flexible rows that can wrap as the viewport narrows.

## What the page includes

- A sticky header with in-page navigation to the mission, featured tea, and locations.
- A mission section with a photographic background and centered text panel.
- A “Tea of the Month” gallery with five featured items.
- A locations section with three Portland, Maine shop cards.
- Contact information and a copyright footer.
- Responsive layout adjustments for compact screens.

## Responsive layout

The page uses flexible, wrapping layouts for the navigation, tea gallery, and location cards. At viewport widths of 540px and below, the header stacks vertically and the mission section becomes shorter. The sections also use maximum widths so the main content does not stretch indefinitely on wide screens.

## Run locally

This is a static HTML and CSS project with no build step or dependencies. Clone or download the repository, then open `index.html` in a browser. An internet connection is needed to load the logo and photography, which are linked from Codecademy-hosted assets.

## Project files

- `index.html` — page structure, content, and navigation.
- `style.css` — visual styling, Flexbox layouts, and responsive rules.

## Built with

- HTML
- CSS, including Flexbox and a media query

This project is part of a front-end learning journey: use the wireframe as a guide, then study how the markup and styles work together to create the finished page.
