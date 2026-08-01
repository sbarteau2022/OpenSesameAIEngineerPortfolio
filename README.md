# The Atlas Dossier

Stewart Barteau’s application package for a TLDR AI content-writer role.

**Live:** [https://ai-dev-resume-tldr-curator.sbarteau2022.workers.dev](https://ai-dev-resume-tldr-curator.sbarteau2022.workers.dev)

A single self-contained page (cover letter + 17 repositories + 76-paper catalog). No build step, no framework.

## Deploy

The repo is connected to a Cloudflare Worker. Every push to the production branch runs the Workers Builds workflow and publishes automatically.

Manual deploy from your machine:

```bash
npm install
npm run deploy
```
