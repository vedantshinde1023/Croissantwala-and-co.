# Crosaaintwala

A TanStack Start (React 19 + TypeScript + Vite 7 + Tailwind v4) site, deployable to Cloudflare Workers.

## Stack
- TanStack Start v1 (file-based routing in `src/routes/`)
- React 19 + TypeScript (TSX)
- Tailwind CSS v4 (configured in `src/styles.css`)
- shadcn/ui components in `src/components/ui/`
- Cloudflare Workers runtime (`wrangler.jsonc`)

## Develop
```bash
bun install
bun dev
```

## Build
```bash
bun run build
```

## Deploy (Cloudflare)
```bash
bunx wrangler deploy
```

## Project layout
- `src/routes/` — pages (`index.tsx` is the home page, `__root.tsx` is the root layout)
- `src/components/` — UI components
- `src/assets/` — images and the hero video
- `src/styles.css` — design tokens + Tailwind layers
