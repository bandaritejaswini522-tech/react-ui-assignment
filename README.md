# Frontend Assignment – React + TypeScript + Tailwind + Storybook

Two reusable components built with modern patterns and documented in Storybook.

## Components

### InputField
- Label, placeholder, helper text, error message
- States: disabled, invalid, loading
- Variants: filled, outlined, ghost
- Sizes: sm, md, lg
- Optional: clear button, password toggle
- Basic a11y with ARIA

### DataTable
- Displays tabular data
- Column sorting
- Row selection (multi)
- Loading & empty states
- Basic a11y with `aria-sort` and labels

## Getting Started

```bash
npm install
npm run dev          # Vite dev server
npm run storybook    # Storybook (local)
npm run build        # Vite build
npm run build-storybook
```

## Notes
- No Vercel config included.
- You can deploy Storybook via Chromatic if needed.
