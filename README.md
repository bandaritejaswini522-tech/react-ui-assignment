# Frontend Assignment – React + TypeScript + Tailwind + Storybook

This project was created as part of a **Frontend Development Assignment**.  
It includes two reusable UI components with documentation in **Storybook**.

---

## 📂 Project Structure

```
frontend-assignment/
├── src/
│   ├── components/              # All reusable components
│   │   ├── InputField/          # Component 1: InputField
│   │   │   ├── InputField.tsx
│   │   │   └── InputField.stories.tsx
│   │   ├── DataTable/           # Component 2: DataTable
│   │   │   ├── DataTable.tsx
│   │   │   └── DataTable.stories.tsx
│   │   └── index.ts             # Central exports
│   ├── App.tsx                  # Demo usage of components
│   ├── main.tsx                 # React entry point
│   └── index.css                # TailwindCSS entry file
├── .storybook/                  # Storybook configuration
│   ├── main.ts
│   └── preview.ts
├── package.json
├── tsconfig.json
├── tailwind.config.js
└── README.md                    # Setup & usage instructions
```

---

## 🎯 Components

### 1. InputField
- Flexible input field with label, placeholder, helper/error text.
- Supports **variants** (`filled`, `outlined`, `ghost`).
- Supports **sizes** (`sm`, `md`, `lg`).
- Accessible (`aria-invalid`, `aria-disabled`).

### 2. DataTable
- Displays tabular data.
- Features:
  - Sorting by columns.
  - Row selection (single/multiple).
  - Loading state.
  - Empty state.

---

## 🚀 Getting Started

### Install dependencies
```bash
npm install
```

### Run development server
```bash
npm run dev
```

### Run Storybook
```bash
npm run storybook
```

---

## 📘 Notes

- Built with **React + TypeScript + TailwindCSS**.
- Storybook configured with **@storybook/react-vite**.
- Code is organized in a **scalable structure** (each component in its own folder).
- This project can be deployed to **Chromatic** or **Vercel** for a live Storybook preview.

---

## 📤 Submission

For assignment submission, please provide:
1. **GitHub repository link** with this project structure.  
2. **Storybook deployment link** (Chromatic or Vercel).  

