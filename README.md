# Pitlochry Redefined – Static Site

## Setup

1. **Download assets** (images + fonts) by running the included script once:
   - **Mac/Linux:** `bash download-assets.sh`
   - **Windows:** `powershell -ExecutionPolicy Bypass -File download-assets.ps1`

   This downloads all images and fonts into `assets/images/` and `assets/fonts/`.
   The HTML files already point to these local paths.

2. **Deploy to GitHub Pages** – push the entire folder contents to your repo's
   `main` branch (or `gh-pages` branch), with GitHub Pages enabled.

## Contact form

The contact form uses [formsubmit.co](https://formsubmit.co). The first time
someone submits the form, you'll receive a confirmation email at
`hello@pitlochryredefined.co.uk` — click the link to activate it.

## Structure

```
index.html
404.html
contact/index.html
contact/success/index.html
become-a-civilian/index.html
privacy/index.html
assets/
  images/   ← populated by download-assets script
  fonts/    ← populated by download-assets script
.nojekyll
```
