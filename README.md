# CodeSight — Inspection Field Guide

© 2026 Jonathan Pastore. All rights reserved.

## Current build

This package is the latest standalone CodeSight build, including the uniform dashboard and navigation icons. It includes residential and commercial electric/solar-ready sections, commercial EV-ready reference material and calculator, code definitions, inspection topics, Correction Writer, and the current Code Library framework. Some Code Library features remain planned or incomplete.

## Publish using GitHub Pages

1. On your Windows computer, extract `CodeSight_GitHub_Build.zip`.
2. Sign in to https://github.com and create a **new repository**, for example `codesight`. Choose **Private** if you do not want the source code public (GitHub Pages publication/visibility depends on plan and repository settings).
3. Open the repository and choose **Add file → Upload files**. Upload **index.html** and **README.md** from the extracted folder. Commit the files.
4. Open **Settings → Pages**. Under **Build and deployment**, select **Deploy from a branch**, then select `main` and `/ (root)` and click **Save**.
5. Wait for the deployment to finish, then open the URL shown in Pages. For a public repository named `codesight`, it is typically `https://YOUR-USERNAME.github.io/codesight/`.
6. Open that address in Safari on iPad/iPhone. Use Share → Add to Home Screen if desired.

## Updating the site

When a newer CodeSight version is ready, upload its HTML contents as `index.html` to the same repository and commit the change. GitHub Pages will republish it.

## Notes

- You **do not need to paste the HTML into Apple Notes**. Upload `index.html` directly.
- The app stores some drafts/checklist progress locally in each browser; those are not automatically shared across devices.
- This is a static HTML/CSS/JavaScript build and does not include a backend or account sync.
- Before using code references in actual inspections, verify requirements against the officially adopted code and local amendments.
- A publicly accessible GitHub Pages site makes the client-side HTML, JavaScript, and included reference text accessible to visitors. A copyright notice is not access control.
