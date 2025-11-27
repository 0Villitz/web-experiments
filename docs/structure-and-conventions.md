# Repository Structure and Conventions

This document expands on the folder structure and per-language naming conventions used in WebExperiments.

---

## Folder Structure

Root layout:

WebExperiments/  
  README.md  
  docs/  
  experiments/  
  resources/  
  raw-assets/  
  .gitignore  
  .gitattributes  

### experiments/

Each experiment is isolated in its own folder:

experiments/  
  threejs-playground/  
  flutter-test-app/  
  ui-prototype-01/  

This keeps unrelated prototypes separated and maintainable.

---

## Naming Conventions

### Folder & asset names

All folders and non-code files use **kebab-case**:

threejs-playground  
ui-prototype-01  
webgl-tests  
raw-assets

Kebab-case is cross-platform-safe and highly readable.

---

## Per-language Code Conventions

Different languages follow their **official style guides**.  
This prevents confusion and ensures idiomatic code in each ecosystem.

### JavaScript / HTML / CSS
- camelCase — variables & functions  
- PascalCase — classes  
- camelCase or SCREAMING_SNAKE_CASE — constants  
- kebab-case — CSS class names  
- lowercase — HTML tags  

### Dart / Flutter
- PascalCase — classes, enums, typedefs  
- lowerCamelCase — variables, fields, methods, constants  
- snake_case — Dart filenames and directories in `lib/`  
- PascalCase — widget class names  

---

## Summary

- Repo-wide structural naming uses **kebab-case**  
- JavaScript/HTML/CSS follow modern web naming conventions  
- Dart/Flutter follow official Dart style guidelines  
- Each experiment remains idiomatic to its language by design
