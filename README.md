# FlipVPN - GitHub Pages

This repository hosts the FlipVPN website and `ads.txt` file via GitHub Pages.

## Setup Instructions

1. **Create a new GitHub repository** named `yourusername.github.io`
   - Replace `yourusername` with your actual GitHub username

2. **Copy all files** from this `github-pages` folder into the repository:
   - `index.html` — Landing page
   - `privacy.html` — Privacy policy
   - `ads.txt` — Your ad network entries
   - `_config.yml` — Jekyll configuration

3. **Edit `ads.txt`** — Paste your actual ads.txt entries into the file

4. **Push to GitHub**:
   ```bash
   git init
   git add .
   git commit -m "Initial GitHub Pages setup with ads.txt"
   git branch -M main
   git remote add origin https://github.com/yourusername/yourusername.github.io.git
   git push -u origin main
   ```

5. **Enable GitHub Pages**:
   - Go to repository **Settings** → **Pages**
   - Source: **Deploy from a branch**
   - Branch: **main** / **(root)**
   - Click **Save**

6. **Verify**: Visit `https://yourusername.github.io/ads.txt` after a few minutes

## In Google Play Console

Set your **Developer Website** to: `https://yourusername.github.io`
