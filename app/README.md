# Straiton assessment landing

This is the coded challenge landing in active production. It implements the Confidence-first direction: UAE → India corridor clarity, quote anatomy, process, FAQ and a two-step assessment demonstration with local validation and success confirmation. It is not connected to a payment system or backend.

Node 24 compatible runtime. `npm ci`, then `npm run dev`. `npm run build` includes TypeScript verification; `npm run preview` serves the built lab locally. No environment variables, external services or remote font calls.

Vercel settings when the preview gate is met: root `app`, build `npm run build`, output `dist`. No payment processing, credentials or backend.
