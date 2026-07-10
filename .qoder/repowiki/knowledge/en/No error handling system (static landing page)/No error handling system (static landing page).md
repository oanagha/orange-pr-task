---
kind: error_handling
name: No error handling system (static landing page)
category: error_handling
scope:
    - '**'
---

This repository is a static Orange PR landing page composed of HTML, CSS, and vanilla JavaScript. It contains no server-side code, no API layer, no middleware, no error types or sentinel errors, and no panic/recover strategy. The only JavaScript files are `js/script.js` (a single console.log) and `components/hero/hero.js` (a DOM slider with defensive null checks like `if (!slides.length) return;`). There are no error-handling conventions, frameworks, or patterns to document.