# WebExperiments

A collection of focused experiments exploring web development, graphics, and UI/UX workflows.  
This repository acts as a sandbox for testing ideas in JavaScript, Three.js, HTML/CSS, browser APIs, Flutter/Dart, and other frontend techniques.

Experiments live in separate folders under `experiments/` so each prototype can evolve independently.

---

## Repository Structure
```
WebExperiments/  
  README.md  
  .gitignore  
  .gitattributes  
  CONTRIBUTING.md  
  docs/  
  resources/  
  raw-assets/  
  experiments/  
    threejs-playground/  
    flutter-test-app/  
    ...other experiments...
```
---

## Naming Conventions

### Folder & file names (repository-wide)

This repository uses **kebab-case** for all directories and non-code filenames:
```
threejs-playground  
ui-prototype-01  
texture-tests  
raw-assets
```
This is platform-safe, URL-safe, and visually consistent.

---

### Per-language code conventions  
- Follow the style guide for each specific language/tool. Examples:

JavaScript / HTML / CSS:
- camelCase — variables and functions  
- PascalCase — classes  
- camelCase or SCREAMING_SNAKE_CASE — constants  
- kebab-case — CSS class names  
- lowercase — HTML tags  

Dart / Flutter:
- PascalCase — classes, enums, typedefs  
- lowerCamelCase — variables, fields, methods, constants  
- snake_case — Dart filenames and `lib/` directories  
- PascalCase — widget class names  

---

## Getting Started

Serve any web-based experiment using a simple HTTP server.

Examples:

VSCode Live Server  
Python: ``python -m http.server``  
npm: ``npx serve``

Example:
```
cd experiments/threejs-playground
python -m http.server
```
Open http://localhost:8000

---

## Documentation

The `docs/` folder contains extended study notes and reference material:

- Documentation Index
- Experiments Overview
- Repository Structure & Conventions
- Research References

---

## Tooling

Experiments may use:

- Node.js & npm
- Three.js
- HTML/CSS/JavaScript modules
- Flutter & Dart
- VSCode
- Type definitions such as @types/three for improved IntelliSense

---

## Future Experiments

Possible additions:

- UI/UX layout prototypes
- WebGL & Three.js visualizations
- Shader and GPGPU tests
- Browser interaction experiments
- React-based UI prototypes
- Flutter widget prototypes
- Components for a portfolio website

---

## License

This repository is intended for personal learning and experimentation.
