# Family Pledge — Support site (GitHub Pages)

Static support + privacy pages for App Store Connect and Google Play.

**Live URLs**

- Support: https://dmstacey.github.io/family-pledge-support/
- Privacy: https://dmstacey.github.io/family-pledge-support/privacy.html
- Web app: https://familypledge.app
- Support email: support@familypledge.app

## Local preview

```bash
cd ~/Code/family-pledge-support
python3 -m http.server 8080
```

Then visit http://localhost:8080

## Publish

Push to `main` on GitHub. Pages deploys from the repo root.

```bash
cd ~/Code/family-pledge-support
git add .
git commit -m "Update support and privacy copy"
git push
```

See **PUBLISH.md** for first-time setup details.

## Store Connect fields

| Field | Value |
|--------|--------|
| Support URL | `https://dmstacey.github.io/family-pledge-support/` |
| Privacy Policy URL | `https://dmstacey.github.io/family-pledge-support/privacy.html` |
| Copyright | `© 2026 David Stacey` |
