# MealFlow Legal Pages

Static legal/support pages for publishing with GitHub Pages or any simple static host.

## Files

- `index.html` - landing page linking to all legal/support pages
- `privacy.html` - privacy policy
- `terms.html` - terms and conditions
- `support.html` - support/contact page
- `impressum.html` - German legal notice / Impressum
- `styles.css` - shared styling

## Before publishing

The pages are configured for:

- GitHub repo: `https://github.com/davutklnc/privacy.git`
- GitHub Pages URL: `https://davutklnc.github.io/privacy/`
- Operator: `Davut Kilinc`
- Contact email: `support@lingotales.io`

If you later use a custom domain, update the canonical links from GitHub Pages URLs to the final domain.

## GitHub Pages setup

1. Use the public repository `https://github.com/davutklnc/privacy.git`.
2. Copy the contents of this folder into that repository root.
3. Commit and push.
4. In GitHub, open Settings > Pages.
5. Set the source to `Deploy from a branch`.
6. Select the `main` branch and `/root`.
7. Use the generated URLs in App Store Connect:
   - Privacy Policy URL: `https://davutklnc.github.io/privacy/privacy.html`
   - Support URL: `https://davutklnc.github.io/privacy/support.html`
   - Terms URL, if needed: `https://davutklnc.github.io/privacy/terms.html`
   - Impressum: `https://davutklnc.github.io/privacy/impressum.html`

## Notes

This is plain HTML and CSS. There is no build step, framework, analytics, tracking, or paid page system.
