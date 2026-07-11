---
name: 'Solvium'
description: 'A Solana DEX with an on-chain token manager program, Express backend with Redis killswitch, Google Gemini AI integration, and full analytics. My most ambitious project yet.'
tags: ['Solana', 'Anchor', 'Rust', 'Express', 'TypeScript']
image: '../../../public/static/solvium.png'
link: 'https://solviumswap.xyz?utm_source=souvikinator.xyz'
order: 0
highlighted: true
techStack:
  - category: 'On-Chain Program'
    items:
      - 'Anchor (Rust) — Solana program framework'
      - 'Program: token-manager (now closed on mainnet)'
  - category: 'Backend / Infra'
    items:
      - 'Express 4 — dev API server'
      - '@upstash/redis — Redis (killswitch / state)'
      - '@google/genai — Google Gemini AI'
      - 'PostHog — analytics'
      - '@vercel/analytics — Vercel analytics'
      - 'dotenv — env management'
  - category: 'Utilities'
    items:
      - 'class-variance-authority + clsx + tailwind-merge — styling utilities'
      - '@radix-ui/react-slot — slot component pattern'
      - 'vite-plugin-node-polyfills — Node polyfills for Vite'
  - category: 'Dev Tools'
    items:
      - 'tsx 4 — TypeScript execution'
      - 'autoprefixer — CSS post-processing'
      - 'TypeScript 5.8 (tsc --noEmit for linting)'
---
