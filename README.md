# Jay Krisell — Portfolio Website

Personal portfolio site for Jay Krisell — Electrical Engineer, Robotics & Embedded Systems.

## Publishing to GitHub Pages

### Quick Setup (5 minutes)

1. **Create a new GitHub repository**
   - Go to [github.com/new](https://github.com/new)
   - Name it something like `portfolio` or `jaykrisell.github.io` (the second option gives you a cleaner URL)
   - Set it to **Public**
   - Click **Create repository**

2. **Push this code to the repo**
   ```bash
   cd Resume-App-main
   git init
   git add .
   git commit -m "Initial portfolio site"
   git branch -M main
   git remote add origin https://github.com/SpaceCadetJ/YOUR-REPO-NAME.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**
   - Go to your repo → **Settings** → **Pages**
   - Under "Source", select **GitHub Actions**
   - The workflow file (`.github/workflows/jekyll-gh-pages.yml`) will automatically deploy on push

4. **Your site will be live at:**
   - If repo is named `jaykrisell.github.io` → `https://spacecadetj.github.io/`
   - If repo is named anything else → `https://spacecadetj.github.io/REPO-NAME/`

### Updating the Site

Just push changes to the `main` branch — GitHub Actions will auto-deploy within ~60 seconds.

### Custom Domain (Optional)

To use a custom domain like `jaykrisell.com`:
1. Buy a domain from Namecheap, Google Domains, etc.
2. In repo Settings → Pages → Custom domain, enter your domain
3. Add a CNAME record pointing to `spacecadetj.github.io` at your domain registrar

## File Structure

```
├── index.html              # Main site
├── Jay_Krisell_CV_2025.pdf # Resume download
├── css/                    # Stylesheets
├── images/                 # Photos and project images
├── scripts/                # JavaScript (AOS animations)
└── .github/workflows/      # Auto-deploy config
```
