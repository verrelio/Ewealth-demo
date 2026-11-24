# [Brand Name] – Fintech Landing Page

Static, single-file site (`index.html`): HTML + CSS + vanilla JS. No build step, no dependencies. Only external request is Google Fonts (Plus Jakarta Sans), with system-font fallback.

## Deploy on Cloudflare Pages
1. Push this folder to a GitHub repo.
2. Cloudflare dashboard → Workers & Pages → Create → Pages → Connect to Git.
3. Select the repo. Framework preset: **None**. Build command: *(leave empty)*. Build output directory: `/`.
4. Save and Deploy.

Or with no Git: Pages → Upload assets → drag in this folder.

## Run locally
Open `index.html` in a browser, or run `npx serve .`
