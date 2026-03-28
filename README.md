# Muslims Fortress Legal Site

Static legal pages for Play Console:

- Privacy Policy: `/privacy.html`
- Terms of Service: `/terms.html`
- FAQ: `/faq.html`

## Quick deploy options

### Option A: GitHub Pages (recommended)

1. Create a new GitHub repo, e.g. `muslims-fortress-legal-site`.
2. Push this folder as the repo root.
3. In GitHub: `Settings -> Pages -> Build and deployment`.
4. Set source to `GitHub Actions`.
5. Push to `main`; workflow publishes automatically.
6. Use the published URLs in Play Console and in-app links.

### Option B: Any static host

Upload all files as-is to Netlify, Cloudflare Pages, Vercel static, S3 static hosting, etc.

## Required edits before publishing

- Replace `llegion40404@gmail.com` if needed.
- Replace `Lapidary` if legal entity name should be different.
- Set your final base URL in app code:
  - `app/src/main/java/com/muslimsfortress/ui/screens/settings/SettingsScreen.kt`

## Suggested final URLs

- `https://<your-domain>/privacy.html`
- `https://<your-domain>/terms.html`
- `https://<your-domain>/faq.html`

## Play Console mapping

- App content -> Privacy policy: put `privacy.html` URL
- Data safety: declare location and app activity collection (details in FAQ page)
