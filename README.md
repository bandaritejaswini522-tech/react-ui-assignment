# React UI Assignment — InputField & DataTable

This repository contains two polished UI components built with **React + TypeScript + TailwindCSS**, documented in **Storybook**, tested with **Vitest + Testing Library**, and showcased in a small demo app (Vite).

## Tech Stack
- React 18 + TypeScript
- Vite (dev server + build)
- TailwindCSS
- Storybook 8
- Vitest + @testing-library/react

## Getting Started
```bash
# 1) Install deps
npm install

# 2) Run demo app
npm run dev

# 3) Run tests
npm test

# 4) Storybook
npm run storybook
```

## Components

### InputField
- Label, placeholder, helper, error
- States: disabled, invalid, loading
- Variants: filled, outlined, ghost
- Sizes: sm, md, lg
- Optional: clear button, password toggle
- A11y: proper `aria-*` attributes, focus management

### DataTable
- Tabular display
- Column sorting
- Row selection (single/multi via checkbox)
- Loading & Empty states
- A11y: `aria-sort`, row checkboxes with labels

## Design & Accessibility
- Semantic HTML elements and ARIA attributes
- Keyboard operable (checkboxes, sortable column headers)
- Responsive layout with Tailwind utilities
- Dark mode ready (toggle by applying `dark` class on `<html>`)

## Project Structure
```
react-ui-assignment/
  src/
    components/
      InputField.tsx
      DataTable.tsx
      *.stories.tsx
      *.test.tsx
    App.tsx
    main.tsx
    index.css
  .storybook/
  index.html
  tailwind.config.js
  postcss.config.js
  vite.config.ts
  tsconfig.json
  package.json
  README.md
```

## Approach
- Strong TypeScript typings with generics for `DataTable<T>`
- Controlled/Uncontrolled friendly `InputField`
- Clean separation of concerns; presentational + small state for UX
- Storybook documents each interactive state
- Tests focus on core interactions and rendering

## Deploy
- Demo: build with `npm run build` and host `dist/` on Vercel/Netlify.
- Storybook: `npm run build-storybook` and publish to Chromatic or Vercel.

---

Crafted to meet and exceed the **Front-End Assignment** requirements.
