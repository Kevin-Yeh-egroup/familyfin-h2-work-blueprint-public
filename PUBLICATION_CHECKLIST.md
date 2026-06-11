# Publication Checklist

## Sensitivity

- [x] Public-review wording only
- [x] No talent-pool personal data
- [x] No raw colleague-needs source text
- [x] No account, deployment, analytics, or backend credentials
- [x] No unverified performance metrics
- [ ] Kevin approves public GitHub repository creation
- [ ] Kevin approves Vercel public deployment

## Noindex Controls

- [x] HTML meta robots set to `noindex,nofollow,noarchive`
- [x] `robots.txt` disallows crawling
- [x] `vercel.json` sets `X-Robots-Tag`
- [ ] Production URL header verified after deployment
- [ ] Production `robots.txt` verified after deployment

## Visual QA

- [ ] Desktop viewport checked
- [ ] Mobile viewport checked around 390 px
- [ ] No horizontal overflow
- [ ] Hero visual loads
- [ ] Navigation links work

## Suggested Public Repo

- Repo slug: `familyfin-h2-work-blueprint-public`
- Vercel project slug: `familyfin-h2-work-blueprint-public`
- Production branch: `main`
