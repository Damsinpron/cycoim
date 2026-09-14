# CYCOIM Project Guide

## Architecture

CYCOIM is a mobile-first demo mining dashboard built with React 19, TanStack Start, TypeScript, Vite, Tailwind CSS 4, and Lucide icons. It deploys to Netlify as a static-first web application. No backend, authentication, database, cryptocurrency transaction, or real wallet connection is present.

## Key files

- `src/routes/__root.tsx` defines document metadata and the root shell.
- `src/routes/index.tsx` contains the four-view Mini App UI and all browser-local demo interactions.
- `src/styles.css` contains the visual system, responsive layouts, animation, and Telegram-safe-area handling.
- `netlify.toml` and `vite.config.ts` contain deployment and framework configuration.

## Conventions

- Keep the UI mobile-first and usable from 320px upward.
- Use `Chakra Petch` for display type and `DM Mono` for data and body copy.
- Reuse the CSS tokens in `:root`; cyan communicates active mining and purple communicates rewards or tiers.
- Use Lucide icons rather than emoji or text symbols.
- Keep demo-only behavior clearly labeled until a backend milestone is explicitly requested.
- Preserve reduced-motion support, keyboard focus styles, and bottom safe-area padding.

## Development

Run `pnpm dev` for local development and `pnpm build` for a production build. The main experience is intentionally kept in one route while it remains a prototype; extract components when adding production integrations or tests.
