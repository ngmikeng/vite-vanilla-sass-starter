# Vite + Vanilla + SASS Starter

A lightweight starter project powered by [Vite](https://vitejs.dev/) using plain JavaScript and SASS. It includes modern CSS normalization and uses the modern `@use` rule for SASS modules instead of the deprecated `@import`.

## Features

- ⚡ Fast development with Vite
- 🎨 SASS support with `@use` syntax
- 🌐 Includes [`modern-normalize`](https://github.com/sindresorhus/modern-normalize) for consistent styling across browsers
- 🧼 Clean, minimal setup

## Getting Started

1. **Install dependencies**

   ```bash
   npm install
   ```

2. **Start the development server**

   ```bash
   npm run dev
   ```

3. **Build for production**

   ```bash
   npm run build
   ```

## Folder Structure

```
├── public
├── src
│  |── main.js
│  |── sass
├── index.html
└── package.json
```

## Notes

- SASS is configured to use `@use` for modular and scoped styling.
- `modern-normalize` is imported in your main SASS file for browser consistency.

---

Happy coding!