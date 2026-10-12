# Subhanjan Shah — Personal Portfolio

A responsive personal portfolio built with HTML and CSS. No installation, JavaScript, or build step is required.

## Files

- `index.html`: page content and structure.
- `style.css`: colours, typography, layout, and mobile styling.
- `Subhanjan-Shah-CV.pdf`: downloadable résumé.
- `robot-certificate.pdf`: competition certificate.
- `.nojekyll`: tells GitHub Pages to serve the static files directly.

## Publish on GitHub Pages

1. Create a public repository named `portfolio` in your GitHub account.
2. Upload the **contents of this folder** to the repository root. `index.html` must appear directly in the repository, not inside an extra folder. Extract the ZIP first; uploading the ZIP itself will not publish the website.
3. Commit the uploaded files to `main`.
4. Open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select **main** and **/(root)**, then click **Save**.
7. Wait for deployment to finish. GitHub displays the live website link in the Pages settings.

With the account `subhanjanshah` and repository `portfolio`, the expected URL is:
https://subhanjanshah.github.io/portfolio/

For a website at https://subhanjanshah.github.io/ instead, use the repository name `subhanjanshah.github.io`.

Official guide: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Preview and edit

Open `index.html` in a browser to preview it locally. Edit text and links in `index.html`; edit the design in `style.css`. Keep the PDF filenames unchanged unless you update their links too.

Project details expand using the native HTML `details` and `summary` elements. Navigation uses page anchors, and the email link opens the visitor’s email application. Google Fonts supplies DM Sans and Manrope when an internet connection is available; local sans-serif fonts provide a fallback.

The internship prototype is not included. The résumé, certificate, and contact email are part of the published website.
