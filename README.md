# Pulse — Week 5 Final Project Integration

A responsive mini web application that integrates the major frontend skills developed during the internship.

## Features
- Fetches static project data from `data.json`
- Dynamic dashboard metrics
- Search by project, owner, or category
- Filter by project status
- Sort by progress, name, or budget
- Responsive project table
- CSS-based progress visualization
- Mobile navigation
- Keyboard-friendly controls and visible focus
- Semantic HTML and ARIA attributes
- `defer` JavaScript and lightweight SVG/CSS approach
- Error handling when JSON cannot be loaded
- Reduced-motion support

## Run locally
Because browsers can block `fetch()` for local `file://` pages, serve the folder using a local static server.

Example:
`python3 -m http.server 8000`

Then open:
`http://localhost:8000`

## Files
- `index.html`
- `app.min.css`
- `app.min.js`
- `data.json`
- `README.md`

## Testing checklist
- Desktop and mobile responsive layouts
- Search, filter and sorting
- JSON loading and fallback error state
- Keyboard navigation and Escape menu close
- Focus visibility
- Table readability and horizontal overflow on small screens
- Lighthouse/PageSpeed audit readiness
