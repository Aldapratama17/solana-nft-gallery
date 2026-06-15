# solana-nft-gallery

> On-chain NFT portfolio viewer for Solana wallets. Fast, mobile-first, no wallet connection required — just paste an address and explore.

![Solana](https://img.shields.io/badge/Solana-mainnet-9945FF?logo=solana&logoColor=white)
![Status](https://img.shields.io/badge/status-live-brightgreen)
![Built with](https://img.shields.io/badge/built%20with-pure%20HTML%2FJS-orange)
![Grant](https://img.shields.io/badge/Superteam-Agentic%20Engineering%20Grant-blue)

## What this is

A lightweight NFT gallery and portfolio viewer for any Solana wallet address. No login, no wallet connection needed — paste an address, see everything onchain.

Built mobile-first because most users in emerging markets browse on phones.

**Live demo:** `[your-deployed-url-here]`

## Features

- View all NFTs held by any Solana wallet
- Collection grouping — see NFTs organized by project
- Floor price display via Magic Eden API
- Portfolio value estimate (SOL + USD)
- Share-ready gallery view
- Works on mobile without app install

## Stack

- Pure HTML + Vanilla JS
- Helius RPC / Metaplex DAS API for NFT data
- Magic Eden API for floor prices
- Built and tested on Android via Termux

## Project structure

```
solana-nft-gallery/
├── index.html          # App shell + gallery layout
├── app.js              # Wallet lookup + NFT fetch
├── gallery.js          # Render + collection grouping
├── pricing.js          # Floor price integration
├── styles.css          # Mobile-first styles
└── README.md
```

## Getting started

```bash
git clone https://github.com/Aldapratama17/solana-nft-gallery
cd solana-nft-gallery
# Open index.html or serve locally
npx serve .
```

No build step. Paste any Solana address into the input field to explore.

## Design decisions

- **No wallet required** — reduces friction, works for explorers and researchers
- **Mobile-first layout** — grid adapts to small screens without horizontal scroll
- **Collection grouping** — makes large wallets readable instead of overwhelming
- **Shareable** — URL updates with wallet address so you can share a link

## Built by

[@aldapratama47](https://twitter.com/aldapratama47) — solo builder, Solana ecosystem, 5 years.  
Founder of [Onchainhunt](https://github.com/Aldapratama17/onchainhunt-core) · CMO at [Union Build](https://union.build)
