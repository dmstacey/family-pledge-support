# Publish this site to GitHub Pages

## 1. Create a GitHub repository

1. Sign in at [https://github.com](https://github.com) (create an account if needed).
2. Click **+** → **New repository**.
3. Repository name: **`family-pledge-support`** (recommended).
4. Public.
5. **Do not** add a README, .gitignore, or license (this folder already has files).
6. Click **Create repository**.

## 2. Push this folder from your Mac

Open **Terminal** and run (replace `YOUR_GITHUB_USERNAME`):

```bash
cd ~/Code/family-pledge-support

git init
git add .
git commit -m "Add Family Pledge support and privacy pages"

git branch -M main
git remote add origin https://github.com/YOUR_GITHUB_USERNAME/family-pledge-support.git
git push -u origin main
```

GitHub will ask you to sign in (browser or personal access token).

### If you use SSH instead

```bash
git remote add origin git@github.com:YOUR_GITHUB_USERNAME/family-pledge-support.git
git push -u origin main
```

## 3. Turn on GitHub Pages

1. On GitHub, open the **family-pledge-support** repo.
2. **Settings** → **Pages** (left sidebar).
3. Under **Build and deployment**:
   - **Source:** Deploy from a branch  
   - **Branch:** `main`  
   - **Folder:** `/ (root)`  
4. Click **Save**.
5. Wait 1–2 minutes, then refresh.

Your site will be at:

```text
https://YOUR_GITHUB_USERNAME.github.io/family-pledge-support/
```

Privacy policy:

```text
https://YOUR_GITHUB_USERNAME.github.io/family-pledge-support/privacy.html
```

## 4. Use in App Store Connect

| Field | Value |
|--------|--------|
| **Support URL** | `https://YOUR_GITHUB_USERNAME.github.io/family-pledge-support/` |
| **Privacy Policy URL** | `https://YOUR_GITHUB_USERNAME.github.io/family-pledge-support/privacy.html` |
| **Copyright** | `© 2026 David Stacey` |

## 5. Optional: change the contact email

Edit `index.html` and `privacy.html` and replace `dstacey25@gmail.com` if you want a different address, then:

```bash
cd ~/Code/family-pledge-support
git add .
git commit -m "Update support email"
git push
```

GitHub Pages updates within a minute or two.
