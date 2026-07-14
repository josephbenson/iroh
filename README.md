# Iroh

A single-page internal draft site for Iroh — an African engineering talent marketplace connecting companies, engineers, and investors.

## Deploy with Netlify Drop

1. Go to [app.netlify.com/drop](https://app.netlify.com/drop).
2. Drag the `iroh` folder onto the page.
3. Netlify will give you a live URL immediately — no build step required.

## Deploy with GitHub Pages

1. Create a new repository on GitHub (do not initialize it with a README).
2. Add it as a remote and push:
   ```
   git remote add origin <repo-url>
   git push -u origin main
   ```
3. In the repository settings, go to **Pages** and enable GitHub Pages, deploying from the `main` branch, root directory.

## Before going live

The three `[FORMSPREE_ENDPOINT_PLACEHOLDER]` tokens in `index.html` (one per form in the Get Involved section) need to be replaced with real Formspree endpoints before the forms will work.
