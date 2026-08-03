# Operator → Engineer

Stewart Barteau's Forward Deployed / Solutions Engineering portfolio.

**Live:** [https://OpenSesameAIEngineerPortfolio.sbarteau2022.workers.dev](https://OpenSesameAIEngineerPortfolio.sbarteau2022.workers.dev)

A single self-contained page: 11+ years of operations leadership, 17 repositories, and the AI/math thread of a 76-paper written corpus. No framework. The only build step is `npm run build`, which writes the Reach section (the reader-city map and the city/country figures beside it) from `data/reader-cities.json`; `npm run check` fails if the page has drifted from that data.

## Deploy

The repo is connected to a Cloudflare Worker. Every push to the production branch runs the Workers Builds workflow and publishes automatically.

Manual deploy from your machine:

```bash
npm install
npm run deploy
```
