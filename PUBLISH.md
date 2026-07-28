# Publish this site to GitHub Pages

## Live site (already published)

| Field | Value |
|--------|--------|
| **Support URL** | `https://dmstacey.github.io/family-pledge-support/` |
| **Privacy Policy URL** | `https://dmstacey.github.io/family-pledge-support/privacy.html` |
| **Web app** | `https://familypledge.app` |
| **Support email** | `support@familypledge.app` |
| **Copyright** | `© 2026 David Stacey` |

Use the Support and Privacy URLs in App Store Connect and Google Play Console.

## Update after content changes

```bash
cd ~/Code/family-pledge-support
git add .
git commit -m "Update support and privacy pages"
git push
```

GitHub Pages usually refreshes within a minute or two.

## First-time setup (already done for this repo)

1. Public GitHub repo: `dmstacey/family-pledge-support`
2. **Settings → Pages** → Deploy from branch `main`, folder `/ (root)`
3. Site URL: `https://dmstacey.github.io/family-pledge-support/`
