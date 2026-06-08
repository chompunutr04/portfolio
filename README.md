# Portfolio — Chompunut Rueangrit

This repository contains a static HTML portfolio site. To show your website on GitHub Pages and make `pkthumbnail.png` the site image when sharing, follow the steps below.

Quick steps (recommended):

1. Make sure `index.html` and `pkthumbnail.png` are in the repository root (they are already here).
2. Commit and push to GitHub:

   git add index.html pkthumbnail.png portfolio.html README.md .gitignore
   git commit -m "Publish portfolio site"
   git push origin main

3. Open your repository on github.com (https://github.com/chompunutr04/portfolio).
4. Go to Settings → Pages. Under "Source" choose the `main` branch and `/ (root)` folder, then Save.
   - After a moment, GitHub will provide a site URL like: `https://<your-username>.github.io/portfolio/`.

Notes and tips:
- `index.html` is the default file GitHub Pages serves. `portfolio.html` will still remain in the repo and can be visited directly.
- The `og:image` meta tag in `index.html` points to `pkthumbnail.png`. GitHub and social sites use the Open Graph tags to show the thumbnail when sharing.
- If the preview doesn't show immediately, wait a few minutes and clear caching, or use the Facebook/Twitter card debuggers to refresh the cache.

If you want, I can:
- Create a small GitHub Actions workflow that deploys the `main` branch to GitHub Pages automatically. (I can add this file for you.)
- Update the site copy, or add a custom domain setup guide.
