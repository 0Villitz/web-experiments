# WebExperiments

A collection of focused experiments exploring web development, graphics, and UI/UX workflows.  
This repository acts as a sandbox for testing ideas in JavaScript, Three.js, HTML/CSS, browser APIs, and frontend techniques.

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
    ...other experiments...
```

---

## Naming Conventions

This repository uses **kebab-case** for directories and file names:

```
threejs-playground
ui-prototype-01
texture-tests
raw-assets
```

JavaScript naming style:

- camelCase — variables and functions  
- PascalCase — classes  
- SCREAMING_SNAKE_CASE — constants (rare)  

Reasons:
- Platform-safe  
- URL-safe  
- Common in modern web development  
- Highly readable  

---

## Getting Started

Most experiments can be served locally with any simple HTTP server.

Recommended options:

- VSCode Live Server  
- Python HTTP server:  
  ```
  python -m http.server
  ```
- Serve (npm):  
  ```
  npx serve
  ```

Example:

```
cd experiments/threejs-playground
python -m http.server
```

Then visit:

```
http://localhost:8000
```

---

## Documentation

Extended notes and deeper study materials live in the [`docs/`](docs/) folder.

Useful starting points:

- [Documentation Index](docs/index.md)
- [Experiments Overview](docs/experiments-overview.md)
- [Repository Structure & Conventions](docs/structure-and-conventions.md)
- [Research References](docs/research-and-references.md)


---

## Tooling

Experiments may use:

- npm  
- Node.js (for local tooling only)  
- Three.js  
- HTML/CSS/JavaScript modules  
- VSCode  

Packages like `@types/three` improve IntelliSense inside VSCode.

---

## Future Experiments

Possible future additions:

- UI/UX layout prototypes  
- WebGL or Three.js visualizations  
- Shader and GPGPU tests  
- Canvas API experiments  
- React-based UI prototypes  
- Components for a portfolio website  

---

## License

This repository is private and intended for personal learning and experimentation.
