# CLAUDE.md - BrightPath Foundation

## Project Overview
Professional website for BrightPath Foundation - a charitable organization supporting young people who have experienced parental loss. Deployed at brightpathfoundation.ca.

## Tech Stack
- **Framework**: React + Vite (JavaScript)
- **Styling**: Tailwind CSS + shadcn/ui
- **Package Manager**: pnpm (preferred) or npm
- **Hosting**: GitHub Pages (via `/dist`)

## Commands
```bash
pnpm install         # Install dependencies
pnpm run dev         # Start dev server
pnpm run build       # Production build to /dist
pnpm run preview     # Preview production build
```

## Project Structure
```
src/
├── components/      # React components
├── assets/          # Images, fonts
├── pages/           # Route components
└── App.jsx          # Main app component
dist/                # Built output (committed for GitHub Pages)
public/              # Static assets
```

## Code Conventions
- JavaScript (not TypeScript) for this project
- Prefer shadcn/ui components
- Keep components focused and reusable
- Commit `/dist` folder for GitHub Pages deployment

## Domain Context
- **Mission**: Supporting young people who have experienced parental loss
- **Programs**: Scholarships, mentorship, grief support resources
- **Tone**: Warm, hopeful, supportive—never clinical or cold
- **Audience**: Potential beneficiaries, donors, volunteers, partners

## When Working on This Project
- Imagery should be uplifting and diverse
- Accessibility is critical (WCAG AA minimum)
- Contact forms should be simple and non-intimidating
- Avoid corporate/business language—this is a caring organization
- Respect privacy—no survivor stories without explicit framing
