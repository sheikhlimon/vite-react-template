# Vite React Template

Modern React + TypeScript template with Vite, featuring automated dependency updates.

## 🚀 Quick Start

```bash
npx degit limon/vite-react-template my-project
cd my-project
npm install
npm run dev
```

## ✨ Features

- ⚡️ **React 19** + **TypeScript** - Latest React with full type safety
- 🔥 **Vite** - Lightning fast builds and HMR
- 🎨 **Modern Tooling** - ESLint 9, Prettier 3.7
- 🐶 **Git Hooks** - Husky + lint-staged for code quality
- 🤖 **Auto Updates** - Dependabot keeps dependencies current
- ⚙️ **Pre-configured** - Production-ready setup out of the box

## 📦 Scripts

```bash
npm run dev        # Start development server
npm run build      # Build for production
npm run lint       # Run ESLint
npm run preview    # Preview production build
```

## 🛠️ Code Quality

- **ESLint**: TypeScript + React best practices
- **Prettier**: Consistent code formatting
- **Husky**: Pre-commit hooks enforce quality
- **lint-staged**: Runs linters only on staged files

## 🔄 Auto Updates

This template includes Dependabot configuration that:
- Runs weekly (Mondays 9am UTC)
- Updates npm and GitHub Actions
- Creates pull requests automatically
- Assigns reviewers and labels

## 📁 Project Structure

```
src/
├── App.tsx          # Main app component
├── index.css        # Global styles
└── main.tsx         # Entry point

eslint.config.js     # ESLint configuration
tsconfig.*.json      # TypeScript configs
vite.config.ts       # Vite configuration
```
