# UNHACKATHON Website

This is the static site for the UNHACKATHON project. It contains an index page, help pages, and a small quiz game.

How to publish to GitHub Pages

1. Create a repository on GitHub (e.g. `unhackathon-website`).
2. On your machine, from the project root, add the remote and push:

```bash
cd /Users/antonialeiva/Website
# if using SSH
git remote add origin git@github.com:yourusername/unhackathon-website.git
# or if using HTTPS
git remote add origin https://github.com/yourusername/unhackathon-website.git
git branch -M main
git push -u origin main
```

3. Enable GitHub Pages in the repo Settings → Pages and choose branch `main` (root). Wait a minute and open the provided URL.

Notes
- Make sure all asset links (images, `style.css`, `script.js`) are relative paths and not absolute file-system paths.
- If you want me to run the remote creation and push steps, tell me the repository name and whether you use SSH or HTTPS and I can provide exact commands or guide you step-by-step.

Sharing in Google Classroom

Once the site is published, copy the GitHub Pages URL (e.g. `https://yourusername.github.io/unhackathon-website/`) and add it to Google Classroom as a Link.

If you want, I can also generate a short ZIP of the site (command you can run) for uploading elsewhere.

---
Generated: October 30, 2025
