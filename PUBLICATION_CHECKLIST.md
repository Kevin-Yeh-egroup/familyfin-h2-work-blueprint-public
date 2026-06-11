# Publication Checklist

## Sensitivity

- [x] Public-review wording only
- [x] No talent-pool personal data
- [x] No raw colleague-needs source text
- [x] No account, deployment, analytics, or backend credentials
- [x] No unverified performance metrics
- [x] Kevin approved public GitHub repository creation
- [x] Kevin approved Vercel public deployment

## Noindex Controls

- [x] HTML meta robots set to `noindex,nofollow,noarchive`
- [x] `robots.txt` disallows crawling
- [x] `vercel.json` sets `X-Robots-Tag`
- [x] Production URL header verified after deployment
- [x] Production `robots.txt` verified after deployment

## Visual QA

- [x] Desktop viewport checked by local Chrome screenshot
- [x] Mobile viewport checked around 390 px by local Chrome screenshot
- [x] No obvious horizontal overflow in captured viewports
- [x] Hero visual loads on desktop and mobile
- [x] Navigation anchor links are present in the HTML

## Suggested Public Repo

- Repo slug: `familyfin-h2-work-blueprint-public`
- Vercel project slug: `familyfin-h2-work-blueprint-public`
- Production branch: `main`
- Stable production URL: `https://familyfin-h2-work-blueprint-public.vercel.app/`
