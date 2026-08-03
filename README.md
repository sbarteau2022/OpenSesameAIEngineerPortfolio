# Operator → Engineer

Stewart Barteau's Forward Deployed / Solutions Engineering portfolio.

**Live:** [https://OpenSesameAIEngineerPortfolio.sbarteau2022.workers.dev](https://OpenSesameAIEngineerPortfolio.sbarteau2022.workers.dev)

A single self-contained page: 11+ years of operations leadership, 17 repositories, and the AI/math thread of a 76-paper written corpus. No build step, no framework.

## Deploy

Every push to `main` runs the Deploy Worker workflow (`.github/workflows/deploy.yml`), which validates the page and publishes it to the `opensesameaiengineerportfolio` Cloudflare Worker with `wrangler deploy`. It needs two repository secrets — `CLOUDFLARE_API_TOKEN` (with the "Workers Scripts — Edit" permission) and `CLOUDFLARE_ACCOUNT_ID`; until they're set, the workflow passes with a warning instead of deploying.

Manual deploy from your machine:

```bash
npm install
npm run deploy
```
