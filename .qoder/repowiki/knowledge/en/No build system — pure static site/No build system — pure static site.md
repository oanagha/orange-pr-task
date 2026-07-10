---
kind: build_system
name: No build system — pure static site
category: build_system
scope:
    - '**'
---

This repository is a minimal, hand-written static landing page with no build tooling whatsoever. There are no Makefiles, Dockerfiles, CI pipelines, package manifests (package.json, Cargo.toml, go.mod, etc.), task runners (Webpack, Gulp, Vite), or deployment scripts anywhere in the tree. The site consists of plain HTML, CSS, and JS files served directly from the repository root, intended to be deployed as-is (e.g., via GitHub Pages or any static host). Consequently, there is no build system to document.