# utranscribe GitHub Pages website

Static HTML/CSS. No build, dependencies, cookies, analytics or JavaScript.

## Before publishing

The public support email is `ivanenko.businesssolver@gmail.com` and appears on the support and privacy pages.

The homepage deliberately says the store release is in preparation. Add the real Chrome Web Store link and update that text after approval.

## New repository setup

1. Create your new public GitHub repository.
2. Upload the **contents of this folder** into the repository root. `index.html` must be at the root, not inside another `githubpage` directory. Include `assets`, `styles.css`, `privacy.html`, `support.html` and `.nojekyll`.
3. Commit to `main`.
4. Open Settings → Pages → Build and deployment.
5. Select **Deploy from a branch**, then **main** and **/(root)**. Save.
6. Wait for the deployment and open the URL GitHub displays. Check all three pages on desktop and mobile.

Official instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Chrome Web Store URLs

For a project repository, substitute your actual username and repository name:

- Homepage: `https://USERNAME.github.io/REPOSITORY/`
- Privacy policy: `https://USERNAME.github.io/REPOSITORY/privacy.html`
- Support: `https://USERNAME.github.io/REPOSITORY/support.html`

These are examples, not live URLs. Use the actual address from GitHub Pages. For a `USERNAME.github.io` repository, omit `/REPOSITORY`.

## Local preview

From this folder run `python3 -m http.server 8080`, then open http://localhost:8080.

All internal links and assets use relative paths, so project repository subpaths work without configuration. Publish only this folder; the extension source and release ZIP are not required for this site.
