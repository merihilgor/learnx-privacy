# LearnX — Privacy & Data Page

Single-page Privacy Policy and Data Management for the LearnX app. Required for Google Play and App Store submission.

## Deploy to GitHub Pages

1. **Create a new GitHub repo** (e.g. `learnx-privacy`).

2. **Replace placeholders** in `index.html` before first push:
   - `[APP_NAME]` → `LearnX`
   - `[YOUR_SUPPORT_EMAIL]` → your support email
   - `[LAST_UPDATED]` → date (e.g. `March 2, 2026`)

3. **Push to the repo:**
   ```bash
   cd learnx-privacy-page
   git init
   git add .
   git commit -m "Initial privacy & data page"
   git remote add origin https://github.com/YOUR_USERNAME/learnx-privacy.git
   git branch -M main
   git push -u origin main
   ```

4. **Enable GitHub Pages:** Repo → **Settings** → **Pages** → Source: **Deploy from branch** → Branch: `main`, folder: `/ (root)` → Save.

5. **Your URL:** `https://YOUR_USERNAME.github.io/learnx-privacy/`

## Use in Store Listings

- **Google Play:** App content → Store listing → Privacy policy URL
- **App Store Connect:** App Information → Privacy Policy URL

Set the field to: `https://YOUR_USERNAME.github.io/learnx-privacy/`

## Updating

Edit `index.html`, commit, and push. GitHub Pages updates automatically within a few minutes.
