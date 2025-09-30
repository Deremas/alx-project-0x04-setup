## 📑 Table of Contents

- [🌊 Splash App — Reactify TS](#-splash-app--reactify-ts)
  - [📂 Project Structure](#-project-structure)
  - [🚀 How to Use](#-how-to-use)
  - [🛠 Tech Stack](#-tech-stack)

- [⚡ StateCraft — Mastering State Management](#-statecraft--mastering-state-management)
  - [🎯 Learning Objectives](#-learning-objectives)
  - [📂 Project Structure (StateCraft)](#-project-structure-statecraft)
  - [🚀 How to Use (StateCraft)](#-how-to-use-statecraft)
  - [🛠 Tech Stack (StateCraft)](#-tech-stack-statecraft)

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

---

# ⚡ StateCraft — Mastering State Management

A **Next.js + TypeScript** project series demonstrating **different approaches to state management in React applications** by building **an interactive counter app**.

This project walks through:

- React useState hook for local state.
- Context API for global state sharing.
- Redux Toolkit for scalable state management.

🎯 Learning Objectives

- By completing this project, you will:
- Understand React state management using useState.
- Implement global state with Context API.
- Master Redux for complex state management.
- Compare different state management solutions.
- Implement state persistence across components.
- Apply the single source of truth principle.
- Structure applications for scalability.

---

📂 Project Structure (StateCraft)
Each version of the project lives in its own directory:

```bash
alx-project-0x04/   # useState implementation
├── pages/
│   └── counter-app.tsx

alx-project-0x05/   # Context API implementation
├── context/
│   └── CountContext.tsx
├── components/
│   └── layouts/
│       └── Header.tsx
├── pages/
│   └── _app.tsx
│   └── counter-app.tsx

alx-project-0x06/   # Redux implementation
├── store/
│   └── store.ts
├── components/
│   └── layouts/
│       └── Header.tsx
├── pages/
│   └── counter-app.tsx
```

---

🚀 How to Use (StateCraft)

1. Clone the repo for the version you want:

```bash
git clone https://github.com/Deremas/alx-project-0x04-setup.git
cd alx-project-0x04   # or alx-project-0x05 / alx-project-0x06
```

2.

```bash
npm install
```

3. Run the dev server

```bash
npm run dev
```

4. Visit `http://localhost:3000/counter-app` and interact with the counter.

---

## 🛠 Tech Stack (StateCraft)

- Next.js – React framework with SSR & file-based routing
- TypeScript – Type-safe codebase
- React – Core library
- Context API – Global state without prop drilling
- Redux Toolkit + React-Redux – Scalable state management
- Tailwind CSS – Utility-first styling
