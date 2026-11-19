# Deployment checklist - estadysta.com.ng

## 1. Upload EVERYTHING in this folder to your site's root (where index.html lives)
`index.html, about.html, services.html, commitment.html, partners.html, projects.html, contact.html, 404.html, style.css, manifest.json, robots.txt, sitemap.xml`

**Always upload `style.css` together with the HTML pages.** The pages load it as `style.css?v=20261014`; new pages with an old stylesheet look broken.

## 2. Image files the pages expect
Included in this package:
- `assets/projects/ihs-01.jpg`
- `assets/projects/ihs-02.jpg`
- `assets/projects/ihs-03.jpg`
- `assets/projects/ihs-04.jpg`
- `assets/projects/ncc-01.jpg`

Already part of your original site (not in this package). Confirm they exist on the server with EXACTLY these names - file names are case-sensitive on most hosts:

**assets/**
- `logo.png`

**assets/hero/**
- `engineer.jpg`

**assets/partners/**
- `airtel.jpg`
- `glo.webp`
- `huawei.png`
- `ihs.png`
- `molcom.jpeg`
- `mtn.jpg`
- `ncc.png`
- `nigerian-air-force.png`
- `nigerian-army.png`
- `nokia.png`
- `rea.png`
- `sungold.png`

**assets/projects/**
- `army-01.jpg`
- `army-04.jpg`
- `army-09.jpg`
- `army-12.jpg`
- `army-18.jpg`
- `ncc-02.jpg`
- `ncc-04.jpg`
- `ncc-05.jpg`
- `ncc-08.jpg`
- `nokia-02.jpg`
- `nokia-03.jpg`
- `nokia-06.jpg`
- `nokia-08.jpg`
- `nokia-10.jpg`

**assets/services/**
- `general-supplies.jpg`
- `grid-power.jpg`
- `ict.jpg`
- `network-quality.jpg`
- `property.jpg`
- `renewable.jpg`
- `telecom.jpg`

If an image is missing, the site now degrades gracefully (alt text shows instead of a broken icon), but add the file to restore the picture.

## 3. Optional
- Rename `htaccess-optional.txt` to `.htaccess` for compression, caching, security headers and the custom 404 page. If your host shows a 500 error afterwards, delete it.
- `.well-known/security.txt` is a standard contact file for security researchers.

## 4. After uploading
1. Hard-refresh (Ctrl+Shift+R).
2. Visit `/nonexistent-page` to confirm the 404 page appears (needs .htaccess).
3. Submit `https://estadysta.com.ng/sitemap.xml` in Google Search Console.
4. Replace the `#` social links in the footer and contact page with your real profile URLs.
