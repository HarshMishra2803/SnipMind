<!-- BEGIN:nextjs-agent-rules -->

# This is NOT the Next.js you know

This version has breaking changes — APIs, conventions, and file structure may all differ from your training data. Read the relevant guide in `node_modules/next/dist/docs/` (resolved from this file's directory; in monorepos the `next` package may not be visible from the repo root) before writing any code. Heed deprecation notices.

This block is written and re-added by `next dev` — verify at `node_modules/next/dist/server/lib/generate-agent-files.js`. Removing it from a diff only re-creates the uncommitted change; committing it with your work keeps the tree clean.

<!-- END:nextjs-agent-rules -->

PROJECT: SnipMind, a snippet manager (Next.js dashboard + Chrome extension).

STACK (do not change without asking):
- Next.js App Router, JavaScript only (no TypeScript)
- Plain CSS Modules + CSS variables. No Tailwind, no shadcn, no UI libraries
- Postgres on Neon, Prisma ORM, pgvector for search
- NextAuth (Google login), Zod for input validation
- Gemini API, server side only. Keys only in .env, never in client code
- Chrome Extension Manifest V3

DESIGN RULES (strict):
- No purple gradients. No pill-shaped buttons (max border-radius 8px)
- No emoji as icons. Use inline SVG icons only
- No em dashes anywhere in code, UI text or docs
- No fake reviews, fake metrics, fake customer counters, placeholder stats
- No vague hero text. Every sentence must state a concrete thing the product does
- No cursor animations, no heavy scroll animations. Only subtle 150ms transitions
- No AI-generated photos. No stock imagery. Use real screenshots later
- Copy must be plain, specific and written like a human developer wrote it

WORKING RULES:
- Build only what the current prompt asks. Do not add extra features
- Explain every new concept in 3-5 simple lines before writing code
- Add short comments on non-obvious lines
- After finishing, list: files created, files changed, how to test, what could break
- If something is unclear, ask. Do not guess