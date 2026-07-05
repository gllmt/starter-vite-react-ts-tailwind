# Vite React TypeScript Tailwind Starter

Minimal frontend starter for modern React apps. It ships Vite, React, TypeScript, Tailwind CSS v4, ESLint, and pnpm in a small project you can fork, rename, and build from without deleting a large demo app first.

![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![pnpm](https://img.shields.io/badge/pnpm-F69220?style=flat-square&logo=pnpm&logoColor=white)
![License: AGPL v3](https://img.shields.io/badge/License-AGPL_v3-blue.svg?style=flat-square)

## Features

- Vite 8 app shell with React 19 and TypeScript 6.
- Tailwind CSS v4 wired through `@tailwindcss/postcss`.
- Strict TypeScript project references for app and Vite config code.
- ESLint flat config with TypeScript, React Hooks, and React Refresh rules.
- pnpm lockfile and workspace settings committed for reproducible installs.
- Minimal `src/App.tsx` surface so the first real feature can replace it cleanly.

## Requirements

- Node.js compatible with the installed Vite version: `^20.19.0` or `>=22.12.0`.
- pnpm.

## Getting Started

```bash
git clone https://github.com/gllmt/starter-vite-react-ts-tailwind.git
cd starter-vite-react-ts-tailwind
pnpm install
pnpm dev
```

Then open the local URL printed by Vite.

## Commands

```bash
pnpm dev      # start the Vite dev server
pnpm build    # typecheck and build for production
pnpm preview  # preview the production build locally
pnpm lint     # run ESLint
```

## Project Layout

```text
starter-vite-react-ts-tailwind/
├── public/
├── src/
│   ├── assets/
│   ├── App.tsx
│   ├── index.css
│   ├── main.tsx
│   └── vite-env.d.ts
├── eslint.config.js
├── index.html
├── package.json
├── pnpm-lock.yaml
├── postcss.config.js
├── tsconfig.app.json
├── tsconfig.json
├── tsconfig.node.json
└── vite.config.ts
```

## Customization

- Edit `src/App.tsx` to replace the starter screen.
- Edit `src/index.css` for global Tailwind imports and base styles.
- Edit `postcss.config.js` if you need additional PostCSS plugins.
- Edit `vite.config.ts` for Vite plugins, aliases, and build options.
- Edit `eslint.config.js` to tune lint rules for your team.

## License

Licensed under the [GNU AGPL-3.0](LICENSE). You are free to use, study, modify, and redistribute it. Any distributed or network-hosted fork must also be released under the AGPL-3.0, which keeps derivatives open.

© 2026 Pierre Guillemot
