# mixcontext-web

Next.js 15 PWA front‑end for **MixContext**.  
Live demo → <https://mixcontext.ai>

---

## Dev Setup

```bash
pnpm install
pnpm dev
```

---

## Tech Stack

* Next 15 (App Router)  
* Tailwind CSS  
* Zustand store  
* `@mixcontext/core` for all parsing / bundling logic  

---

## Contributing

1. Fork → create branch `feat/<slug>`  
2. Run lint & type checks  

   ```bash
   pnpm lint && pnpm type-check
   ```  

3. Open a PR with before/after screenshots or GIFs.  
4. Ensure `pnpm test` & CI pass before merge.

---

## Project Structure

```
apps/web
 ├─ src/
 │   ├─ components/   ← PackPanel, Workspace, UI primitives
 │   ├─ hooks/        ← Zustand stores
 │   ├─ lib/          ← small web‑only helpers
 │   └─ app/          ← Next.js pages & layout
 └─ public/           ← logo, OG images
```

---

> **License:** MIT © 2025 MixContext.ai
