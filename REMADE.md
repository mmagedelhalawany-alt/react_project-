# React + Vite + TypeScript Training Workspace

Ongoing internship / training workspace for frontend engineering practice. This repository serves as a permanent root for completing a series of structured training assignments while maintaining a clean, modular, and scalable codebase.

---

## 📋 Assignment History

| Task | Title | Status | Completion Date |
| :---: | :--- | :---: | :---: |
| **01** | React Project Structure | **Completed** | October 14, 2026 |

---

## 🚀 Tech Stack

* **React 19** — UI library.
* **TypeScript** — Type-safe application code.
* **Vite** — Development server and production bundler.
* **npm** — Package manager (`package-lock.json` is committed).
* **ESLint** — Linting and code quality checks.

---

## 📁 Project Structure

```text
react_project/
├── public/
│   └── .gitkeep
├── src/
│   ├── components/
│   │   ├── ui/
│   │   │   └── Button.tsx
│   │   ├── layout/
│   │   │   ├── Navbar.tsx
│   │   │   └── Footer.tsx
│   │   ├── providers/
│   │   │   └── AppProvider.tsx
│   │   ├── skeleton/
│   │   │   └── LoadingSkeleton.tsx
│   │   └── common/
│   │       └── EmptyState.tsx
│   ├── hooks/
│   │   └── useDebounce.ts
│   ├── api/
│   │   └── users.api.ts
│   ├── types/
│   │   └── user.types.ts
│   ├── store/
│   │   └── index.ts
│   ├── pages/
│   │   ├── Home.tsx
│   │   └── About.tsx
│   ├── constants/
│   │   └── routes.ts
│   ├── i18n/
│   │   ├── config.ts
│   │   └── en.json
│   ├── assets/
│   │   └── .gitkeep
│   ├── schemas/
│   │   └── user.schema.ts
│   ├── utils/
│   │   └── formatDate.ts
│   ├── App.tsx
│   ├── main.tsx
│   └── index.css
├── .gitignore
├── index.html
├── package.json
├── package-lock.json
├── tsconfig.json
├── tsconfig.app.json
├── tsconfig.node.json
├── vite.config.ts
└── README.md
