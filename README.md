# Next.js Starter Template

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Next.js](https://img.shields.io/badge/Next.js-13+-black?logo=next.js)](https://nextjs.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.3-blue?logo=tailwind-css)](https://tailwindcss.com/)
[![Prisma](https://img.shields.io/badge/Prisma-4.15-blueviolet?logo=prisma)](https://www.prisma.io/)

A minimal, opinionated starter template for Next.js 13+ apps with:

- `src/` directory structure  
- Tailwind CSS configured  
- Prisma ORM ready (optional, configure `prisma/schema.prisma`)  
- React Strict Mode enabled in `next.config.js`  
- `tsconfig.json` configured with path aliasing (`@/` → `src/`)  
- Basic `.gitignore`  
- Preconfigured layouts and example pages using the Next.js App Router

---

## Quickstart: Scaffold a New Project

Use [`degit`](https://github.com/adeepika1991/degit) to create a new project without cloning git history:

```bash
npx degit adeepika1991/nextjs-starter-repo my-new-project
cd my-new-project
npm install
npm run dev
