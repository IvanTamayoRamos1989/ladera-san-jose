# Ladera San José — deployment

Three files. Drop them at the root of a GitHub repo, connect to Vercel, done.

## Files
- `index.html` — the page (self-contained, all images embedded)
- `robots.txt` — allows Google, ChatGPT, Perplexity, Claude crawlers
- `sitemap.xml` — helps Google index faster

## Before deploying
In both `robots.txt` and `sitemap.xml`, replace `YOUR-DOMAIN.vercel.app`
with whatever Vercel gives you (or your custom domain once attached).

## Deploy path (mobile-friendly)
1. github.com — sign in, create new public repo `ladera-san-jose`
2. Upload all three files to the repo
3. vercel.com — sign in with GitHub, "Add New Project", import the repo
4. Click Deploy. No build config needed.
5. Live in ~30 seconds at `[repo-name].vercel.app`

## After deploy
- Update sitemap.xml + robots.txt with the live URL, re-upload to GitHub
- Submit URL to Google Search Console
- Attach custom domain (Vercel dashboard → Domains)
