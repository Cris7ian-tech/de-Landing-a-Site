# Prisma — Corporate Website

## 🌐 Overview

Prisma is a multi-page corporate website built with HTML, CSS, and Vanilla JavaScript.  
It evolved from a landing page into a structured website with a custom design system and an ongoing frontend architecture refactor.

The main goal is to build a scalable, maintainable frontend without frameworks, focusing on:
- clean structure
- reusable components
- consistent UI system
- performance and simplicity

---

## 🚀 Live Project

- Production: https://YOUR-VERCEL-URL.vercel.app

---

## 📄 Pages

- Home (`index.html`)
- Services (`servicios.html`)
- Portfolio (`portfolio.html`)
- About (`sobre-nosotros.html`)
- Contact (`contacto.html`)

---

## 🧱 Tech Stack

- HTML5 (semantic structure)
- CSS3 (design system with variables)
- Vanilla JavaScript
- Vercel (deployment)
- No frameworks (intentional)

---

## 🎨 Design System

Prisma is based on a custom CSS variable system:

- Color tokens in `:root`
- Consistent spacing scale
- Reusable UI components:
  - Buttons
  - Navigation
  - Footer
  - Section labels
  - Cards

The system is being progressively refactored into a modular architecture.

---

## 🏗️ Architecture Evolution

### Phase 0 — Initial Build
- Landing page expanded into multiple pages
- Full duplication of CSS and JS across files
- No shared architecture

### Phase 1 — Global Styles Refactor ✅
- Created `css/styles.css`
- Centralized:
  - reset
  - variables
  - navigation
  - footer
  - reveal animations
  - global media queries
- Removed ~600+ lines of duplicated CSS
- Established single source of truth for global styles

### Phase 2 — In Progress
- Extract reusable components:
  - `.btn`
  - `.section-label`
- Prepare shared JavaScript (`main.js`)
- Continue reducing duplication

### Phase 3 — Planned
- Fully modular CSS structure per page
- Shared JS architecture
- Final Design System consolidation

---

## ⚙️ Current Architecture
