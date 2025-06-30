# Tailwind Next.js Monorepo Repro

# Steps to reproduce
1. Clone the repository
2. `pnpm i`
3. ` pnpm web`
5. Observe that the style is not applied because its variables (colors) are missing from the css file. Only the variables from apps/web are available.
