# ClaimTracker website

The marketing site for [ClaimTracker](https://github.com/miles-howell/EDI837), a read-only viewer that renders X12 837 claims as UB-04 and CMS-1500 forms.

It's a single static page (`index.html`) with no build step. GitHub Pages serves it from the root of `main`, so a push to `main` is a deploy.

**Before you commit:** this repo and the site are public. Keep internal hostnames, database names, company branding and any real claim data out of it. Every form value on the page is synthetic.

To preview it locally, open `index.html` in a browser.
