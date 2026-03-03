# lam

Astro site with Vercel Speed Insights integration.

## Features

- ⚡️ Astro 5.x
- 📊 Vercel Speed Insights for performance monitoring
- 🎨 Component-based architecture with layouts

## Project Structure

```text
/
├── public/          # Static assets
├── src/
│   ├── components/  # Reusable components
│   │   └── BaseHead.astro
│   ├── layouts/     # Layout components
│   │   └── Layout.astro
│   └── pages/       # Page routes
│       └── index.astro
└── package.json
```

## Commands

All commands are run from the root of the project:

| Command                | Action                                           |
| :--------------------- | :----------------------------------------------- |
| `pnpm install`         | Installs dependencies                            |
| `pnpm dev`             | Starts local dev server at `localhost:4321`      |
| `pnpm build`           | Build your production site to `./dist/`          |
| `pnpm preview`         | Preview your build locally, before deploying     |

## Vercel Speed Insights

This project includes Vercel Speed Insights for automatic performance monitoring. The integration is added in `src/components/BaseHead.astro` and will track Core Web Vitals when deployed to Vercel.
