## Part 02 — CommonJS vs ESModules

- nodemon → auto restarts server on file change
- nvm use 16 → switch Node versions
- CommonJS → `require()`
- ESModules → `import http from 'http'`
- Named export → `{ a, b, c }` exact name required
- Default export → any name on import
- `__dirname`, `__filename`, `require` → injected by Node.js wrapper function
