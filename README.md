# Vafaei Intelligent Consulting — Website

Marketing site for Vafaei Intelligent Consulting (VIC), founded by Reihaneh Vafaei.

## Structure
```
.
├── index.html       # Homepage
├── about.html        # About page
├── work.html          # Selected work / case studies
├── image-slot.js      # Custom <image-slot> element used on work.html
├── assets/            # Images, icons, favicons
├── sitemap.xml
├── robots.txt
└── CNAME              # Custom domain config for GitHub Pages (vafaei.ai)
```

## Deployment
Hosted on GitHub Pages, served at the custom domain `vafaei.ai` via the `CNAME` file.

To deploy changes:
```bash
git add .
git commit -m "describe your change"
git push
```

GitHub Pages will rebuild automatically within a minute or two of a push to `main`.

## TODO before launch
- [ ] Add `assets/og-cover.jpg` (referenced in Open Graph / Twitter meta tags for social share previews)
- [ ] Replace the placeholder `#` LinkedIn link in `index.html` with the real profile URL
