# Javad Molatefi — Personal Portfolio

A one-page, responsive, dark portfolio website for GitHub Pages.

## Files

- `index.html` — page content and structure
- `css/style.css` — design, layout, and responsive styling
- `js/main.js` — mobile navigation, reveal animations, and current footer year
- `assets/Javad-Molatefi-CV.pdf` — original résumé supplied for this site

## Publish at `https://javadmolatefi.github.io`

1. Sign in to GitHub using the account whose username is exactly `javadmolatefi`.
2. Create a **public** repository named exactly `javadmolatefi.github.io`.
3. Upload the contents of this folder to the repository root. In particular, `index.html` must be at the root, not inside another nested folder.
4. In the repository, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Choose branch `main` and folder `/ (root)`, then save.
7. Wait for the Pages deployment to finish, then visit `https://javadmolatefi.github.io`.

## Before publishing

- Confirm the GitHub username and repository name are correct.
- Check that the email address and phone number are suitable for public display.
- The original CV is included as a public download. Remove `assets/Javad-Molatefi-CV.pdf` and the download links in `index.html` if you do not want your full CV publicly downloadable.
- The site uses Google Fonts; if those fonts cannot load, it falls back to system sans-serif fonts.
- Review all dates and wording. The source résumé lists years, not exact employment start/end months, so the site intentionally displays years only.

## Updating the website

Edit `index.html`, `css/style.css`, or `js/main.js`, then commit and push the changes to the `main` branch. GitHub Pages will publish the update automatically after deployment.
