# @refai.code/vite-boost

CLI tool to supercharge **Vite Vanilla JavaScript** projects.

---

## 🚀 What it does
`vite-boost` helps you quickly scaffold and enhance a **Vite Vanilla JS** project with a clean architecture and optional features.

### It can:
- Create a clean project structure:
  - `router/`, `pages/`, `components/`, `services/`, `utils/`, `styles/`
- Optionally add:
  - 🎨 TailwindCSS
  - 📡 Axios (Fetch is default)
  - 📱 PWA support
  - 🗄️ JSON Server (`db.json` + dev scripts)

---

## 📦 Requirements
- Node.js **>= 18**
- A **Vite Vanilla JavaScript** project
  (must contain: `package.json`, `index.html`, `src/`)

> ❌ Not intended for React or TypeScript templates.

---

## ▶️ Usage (recommended)

Inside your Vite project folder:

```bash
npm i -D @refai.code/vite-boost
npx vite-boost
```
## ▶️ Run without installing

```bash
npx @refai.code/vite-boost
```

## 🏃 After running

### Start dev server:

```bash
npm run dev
```
### If you enabled JSON Server:
```bash
npm run dev:full
```

## ⚠️ Important Notes

- This tool targets Vanilla JavaScript only
- Some files under src/ may be overwritten
- Existing files are backed up before modification when possible
- Safe to re-run (will not blindly duplicate router code)

## 🧑‍💻 Author

Created by **Refai.Code**
CLI & tooling for modern Vite projects
