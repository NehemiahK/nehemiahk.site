# portfolio

Personal site for Nehemiah Kivelevitz. It's plain static HTML and CSS with no build step.

- `index.html`: all the content
- `styles.css`: theme (light/dark) and layout
- `cv.pdf`: downloadable CV

## Run locally

```bash
npx serve .
```

## Deploy

Any static host works. Point it at the repo root and leave the build command empty.

- **Cloudflare Pages:** `npx wrangler pages deploy . --project-name portfolio`
- **Vercel:** `npx vercel --prod`
