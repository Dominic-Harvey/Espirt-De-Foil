# Esprit De Fencing Landing Page

> **Note on Configuration:** This project uses **Tailwind CSS v4**, which is **CSS-first**. There is no `tailwind.config.js`. All themes, colors (including the `brand`, `navy`, and `purple` scales), and fonts are defined directly in `styles.css` using the `@theme` block.

A modern, responsive landing page built with TypeScript, Vite, and Tailwind CSS.

## 🚀 Tech Stack

- **TypeScript** - Type safety
- **Vite** - Fast build tool and dev server
- **Tailwind CSS v4** - Utility-first CSS framework (CSS-first configuration)
- **Bun** - Fast JavaScript runtime and package manager
- **Prettier** - Code formatting

## 📦 Prerequisites

- [Bun](https://bun.sh) v1.3.6 or higher
- Git

## 🛠️ Installation

1. Clone the repository:

```bash
git clone https://github.com/Dominic-Harvey/Esprit-De-Foil.git
cd "Esprit De Foil"
```

2. Install dependencies:

```bash
bun install
```

## 🏃 Development

Start the development server:

```bash
bun run dev
```

The site will be available at `http://localhost:5173/`

## 🏗️ Build

Build for production:

```bash
bun run build
```

Preview the production build:

```bash
bun run preview
```

## 🧹 Code Quality

### Linting

```bash
bun run lint          # Check for issues
bun run lint:fix      # Auto-fix issues
```

### Formatting

```bash
bun run format        # Format all files
bun run format:check  # Check formatting
```

## 🚢 Deployment

This project is configured for deployment on [Vercel](https://vercel.com).

### Deploy via Vercel Dashboard

1. Push your code to GitHub
2. Go to [vercel.com](https://vercel.com)
3. Import your repository
4. Vercel will auto-detect the settings from `vercel.json`
5. Click "Deploy"

### Deploy via Vercel CLI

```bash
npm i -g vercel
vercel
```
