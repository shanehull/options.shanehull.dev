# Options Calculator

A real-time options trading calculator deployed on Cloudflare Pages.

## Setup

```bash
yarn install
```

## Local Development

```bash
yarn run dev
```

Visit `http://localhost:8788`

## Deploy

```bash
yarn run deploy
```

Or push to main/master branch for automatic GitHub Actions deployment.

## GitHub Actions Setup

1. Get your Cloudflare API token and Account ID from the dashboard
2. Add to GitHub repository secrets:
   - `CLOUDFLARE_API_TOKEN` - Your API token
   - `CLOUDFLARE_ACCOUNT_ID` - Your account ID

3. Push to main/master to auto-deploy
