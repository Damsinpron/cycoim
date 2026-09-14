# CYCOIM

CYCOIM is a responsive Telegram Mini App prototype for a fictional crypto-mining experience. It presents balances and mining rates in USD through a dark cyber-mining dashboard designed around short, touch-friendly mobile sessions.

## What is included

- Live demo mining timer and incremental session rewards
- Start and stop mining controls
- Claim interaction and total mined balance
- Home, Mining, Wallet, and Profile views
- Referral invite panel with copy feedback
- Demo wallet activity and operator progression
- Responsive layout with Telegram safe-area support

All values and interactions are browser-local placeholders. The project does not perform cryptocurrency transactions, connect to a wallet, or persist user data.

## Technology

React 19, TanStack Start, TypeScript, Vite, Tailwind CSS 4, Lucide React, and Netlify.

## Local development

```bash
pnpm install
pnpm dev
```

Create a production bundle with `pnpm build`. Netlify deployment settings are already included in `netlify.toml`.
