# SPARK — legal pages (host on GitHub Pages)

These four files are the public Privacy Policy, Terms, Support, and a small landing
page. The app already points at them (`SparkLegal.legalBase`).

## Put them online (5 minutes, free)

1. On GitHub, create a **new PUBLIC repo** named exactly **`spark-legal`**.
   (Public is required so App Review and your users can open the pages without logging in.)
2. Upload the contents of this `legal/` folder to the repo **root** —
   `index.html`, `privacy.html`, `terms.html`, `support.html`.
3. Repo → **Settings → Pages → Build and deployment → Deploy from a branch →
   Branch: `main` / folder: `/ (root)` → Save**.
4. Wait ~1 minute, then open:
   - https://biswaskhatiwada.github.io/spark-legal/privacy.html
   - https://biswaskhatiwada.github.io/spark-legal/support.html

   These are the URLs already wired into the app and used in App Store Connect.

## Before you submit
- Replace **support@sparkcouples.com** in all three pages with a real inbox you check
  (your own email is fine until the domain email exists). A reviewer may email it.

## When the domain is ready
- Point `sparkcouples.com` at this repo (Pages → custom domain), **or** just change
  one line in `Relationship App/Backend/SparkLegal.swift`:
  `legalBase = "https://sparkcouples.com"`. No new build review needed for URL metadata.
