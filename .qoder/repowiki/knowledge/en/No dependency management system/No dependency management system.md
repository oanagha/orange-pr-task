---
kind: dependency_management
name: No dependency management system
category: dependency_management
scope:
    - '**'
---

This repository is a static HTML/CSS/JS landing page with no package manager, lockfile, or vendoring strategy. There are no manifest files (package.json, go.mod, requirements.txt, etc.), no node_modules/vendor directories, and no external library imports — all CSS and JS are authored in-house under css/, js/, and components/. The .gitignore file is empty, so nothing is being excluded from version control. Dependencies are effectively non-existent for this project.