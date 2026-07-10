---
kind: configuration_system
name: No configuration system — static landing page
category: configuration_system
scope:
    - '**'
---

This repository is a plain static HTML/CSS/JS landing page for an Orange PR hero section. It contains no application runtime, server-side code, environment files (.env), YAML/TOML/JSON config manifests, feature flags, or any configuration-loading logic. All behavior and content are hard-coded directly in index.html, components/hero/hero.js, and js/script.js. Therefore the configuration_system category does not apply to this repo.