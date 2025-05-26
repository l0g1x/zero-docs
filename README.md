# Zero Docs

A modern, versioned documentation site built with Next.js and MDX, designed for Zero and related projects.

---

## 📁 Project Structure

- **`app/`**: Next.js app directory. Main entry: `app/page.tsx`. Docs live under `app/docs/`.
- **`components/`**: React components (UI, navigation, docs, etc.)
  - `components/ui/`: Reusable UI elements (Button, Table, Dialog, etc.)
  - `components/hooks/`: Custom React hooks.
  - `components/logos/`: Project and company logos.
- **`lib/`**: Utilities for markdown, search, and config.
- **`contents/`**: All documentation content (MDX files).
  - `contents/docs/`: Main docs, guides, and reference.
- **`public/`**: Static assets (images, logos, etc.)

---

## 🚀 Getting Started

1. **Install dependencies:**
   ```bash
   npm install
   ```
2. **Run the development server:**
   ```bash
   npm run dev
   ```
   Visit [http://localhost:3000](http://localhost:3000).

3. **Build for production:**
   ```bash
   npm run build
   ```

---

## 📝 Writing & Editing Docs

- All documentation lives in `contents/docs/` as `.mdx` files.
- To add a new doc, create a new `.mdx` file in `contents/docs/`.
- Use standard MDX/Markdown syntax. Custom components are available for advanced formatting.

---

## 🤝 Contributing

We welcome contributions! To get started:

1. Fork this repo and create a new branch.
2. Make your changes (docs, code, or both).
3. Run `npm run lint` and `npm run format` to ensure code style.
4. Open a pull request with a clear description.

Please read and follow our [Code of Conduct](./CODE_OF_CONDUCT.md).

---

## 🛠️ Useful Scripts

- `npm run dev` – Start local dev server
- `npm run build` – Build for production
- `npm run lint` – Lint code
- `npm run format` – Format code with Prettier

---

## 📚 Features

- MDX support
- Nested pages & sidebar navigation
- Syntax highlighting & code titles
- Table of contents
- Static site generation
- Custom components
- Light & dark mode

---

## 📦 Dependencies

See [`package.json`](./package.json) for a full list.

---

## 📄 License

[MIT](./LICENSE)
