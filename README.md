# Splash App — Reactify TS

A **Next.js + TypeScript** project showcasing **modern web development practices** with a focus on reusability, responsive design, and clean architecture.

This project demonstrates:

- **Shared Layouts**: Reusable `Header`, `Footer`, and `Layout` components following DRY principles.
- **Type Safety**: Centralized interface management for maintainability.
- **Imperative Routing**: Using `useRouter` for programmatic navigation.
- **Custom Error Pages**: Friendly, branded 404 page.
- **Responsive UI**: TailwindCSS for consistent styling across devices.

---

## 📂 Project Structure

```bash
alx-project-0x03/
├── components/
│   ├── common/
│   │   └── Button.tsx
│   └── layouts/
│       ├── Header.tsx
│       ├── Footer.tsx
│       └── Layout.tsx
├── interfaces/
│   └── index.ts
├── pages/
│   ├── index.tsx
│   └── 404.tsx
├── styles/
│   └── global.css
└── (Next.js config files)
```

## 🚀 How to Use

1. Clone the repo

```bash
git clone https://github.com/Deremas/alx-project-0x03-setup.git
cd alx-project-0x03
```

2. Install dependencies

```bash
npm install
```

3. Run the development server

```bash
npm run dev
```

4. Visit `http://localhost:3000` to view the app.

## Tech Stack

- Next.js – React framework with SSR & file-based routing
- TypeScript – Type-safe codebase
- Tailwind CSS – Utility-first styling
- React Icons – Modern icon library
- Google Fonts – Montserrat typography
