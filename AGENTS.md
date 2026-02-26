# AGENTS.md

## Cursor Cloud specific instructions

### Project overview
This is a static HTML/CSS personal dashboard website with no build system, package manager, or backend. The entire project consists of `index.html` and `style.css`.

### Running the dev server
Serve the site locally with Python's built-in HTTP server:
```
python3 -m http.server 8080
```
Then open `http://localhost:8080/` in Chrome.

### Lint / Test / Build
- **No linter, test suite, or build step is configured.** There is no `package.json`, no bundler, and no CI pipeline.
- HTML can be validated manually in the browser DevTools console.

### External dependencies
- Remix Icon CSS is loaded from `cdn.jsdelivr.net` at runtime. The page works without internet but loses icon rendering.
