# fastlearning — Git & GitHub Study Jam (HCM-UTE DSC 2026)

Initial frontend codebase for team **fastlearning**, participating in the **Git & GitHub Study Jam** organized by **HCM-UTE Developer Student Club (2026)**.

## Technology Stack

- **React 19** + **TypeScript** (strict mode)
- **Vite 6**
- **Tailwind CSS v4** (`@tailwindcss/vite`)
- **React Router 7** (`HashRouter`)
- **Motion for React** (`motion`)
- **Lucide React** (`lucide-react`)
- **ESLint** & **Prettier**

## Getting Started

```bash
# Install dependencies
npm install

# Start the development server
npm run dev

# Type-check and build for production
npm run build

# Run ESLint
npm run lint

# Format or verify code style with Prettier
npm run format
npm run format:check

# Preview the production build locally
npm run preview
```

## Initial Project Structure

```text
├── assets/                   # Original repository static assets
├── public/
│   └── images/
│       ├── dsc-logo.png      # Official HCM-UTE DSC logo
│       └── members/          # Reserved directory for member portraits
├── src/
│   ├── components/
│   │   ├── home/
│   │   ├── layout/
│   │   └── ui/
│   ├── data/
│   ├── layouts/
│   ├── pages/
│   │   └── HomePage.tsx      # Minimal starter screen
│   ├── types/
│   ├── App.tsx               # HashRouter root route setup
│   ├── index.css             # Tailwind CSS v4 entry
│   ├── main.tsx
│   └── vite-env.d.ts
├── .gitignore
├── .prettierrc
├── eslint.config.js
├── index.html
├── package.json
├── package-lock.json
├── tsconfig.json
├── tsconfig.app.json
├── tsconfig.node.json
└── vite.config.ts
```

## Creating Feature Branches

Create new feature branches from `init-codebase` after the initial setup is merged:

```bash
git checkout init-codebase
git pull origin init-codebase
git checkout -b feature/<feature-name>
```
