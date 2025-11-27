# Contributing Guide

This repository is a personal sandbox for learning and experimentation in web development, graphics, and UI/UX.  
These guidelines help keep experiments organized and consistent.

---

## Repository Structure

Experiments should be added under:

```
experiments/<experiment-name>/
```

Use lower-case **kebab-case** for directories and files.

Examples:

```
experiments/threejs-playground
experiments/ui-prototype-01
experiments/webgl-shader-tests
```

Shared assets go in:

```
resources/
```

Heavy source files (Blender, Houdini, PSD, EXR) go in:

```
raw-assets/
```

Documentation lives in:

```
docs/
```

---

## Coding Conventions

### JavaScript
- camelCase for variables and functions  
- PascalCase for classes  
- Prefer `const`; use `let` only when needed  
- Avoid `var`  
- Prefer ES modules (import/export)  

### HTML / CSS
- Keep HTML structure minimal  
- Inline CSS is okay for tiny prototypes  
- Larger experiments should use separate `.css` files  

---

## Experiment Structure

A typical experiment contains:

```
index.html
main.js
styles.css   (optional)
README.md    (optional)
assets/      (optional)
```

---

## Branching and Commits

Branches are optional but recommended for larger features.

Example branch names:

```
feature/threejs-camera-tests
fix/orbit-controls-resize
```

Commit messages should be short and descriptive:

```
Add basic render loop to threejs-playground
Fix canvas resize behavior
Add UI prototype layout and assets
```

---

## Documentation

In-depth notes, diagrams, case studies, and research belong in:

```
docs/
```

---

## When to Create a New Experiment

Create a new experiment when:

- The idea is unrelated to existing experiments  
- I need isolated HTML/JS/CSS files  
- It may grow beyond a tiny snippet  

Small variations related to an existing experiment can stay within the same folder.

---

## License

This repository is private and for personal learning.
