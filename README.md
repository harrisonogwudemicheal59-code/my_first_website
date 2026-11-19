
## Update log (latest edit)
- Replaced the two illustrative IHS placeholder photos with 4 real site photos
  (`assets/projects/ihs-01.jpg` – `ihs-04.jpg`). Delete any old `ihs-1.jpg` /
  `ihs-2.jpg` files from your live `assets/projects` folder — they're no longer
  referenced.
- Phone number updated everywhere to +234 706 541 9496; the old +234 809 224 4866
  and +237 065 419 496 numbers were removed.
- WhatsApp removed from the social row; a YouTube icon was added alongside the
  existing Facebook, LinkedIn, X and Instagram icons (Facebook, LinkedIn, X,
  Instagram and YouTube still point to `#` placeholders — add your real profile
  URLs when ready).
- Each "Projects executed" gallery (Nokia, NCC, Nigerian Army) was trimmed to its
  best 5 photos for a tighter, faster-loading gallery. The unused image files
  are still in `assets/projects` but no longer referenced — delete them if you
  want to reclaim space, or keep them for later.
- Added SEO/meta standards: meta description, Open Graph and Twitter card tags,
  canonical link, theme-color, favicon links, an Organization JSON-LD block, plus
  `robots.txt` and `sitemap.xml`. These assume the site lives at
  `https://www.estadysta.com/` — update that domain in `index.html`,
  `robots.txt` and `sitemap.xml` if the real one differs.
- No changes were made to `style.css` — the site was already built mobile-first
  with responsive breakpoints at 1024/860/780/600/480/360px, so it already works
  well across devices.

## Update log (multi-page conversion)
- The site is now multi-page: `index.html` (home/hero), `about.html`,
  `services.html` (services + mission statement), `commitment.html`,
  `partners.html`, `projects.html` (project galleries + lightbox) and
  `contact.html` (contact details + form). Clicking a nav link now opens that
  page fully, instead of scrolling within a single page. The current page is
  marked in the nav via `aria-current="page"` (shown with a red underline).
- Each page has its own `<title>`, meta description and canonical URL for
  better SEO; the shared header/footer/scripts are duplicated across pages
  (no build step, so this is expected for a plain-HTML site).
- Mobile hero: below 780px the tower graphic now sits beside the headline as a
  small icon (not stacked above it), shrinking further at 480px and 360px.
  Desktop layout is unchanged.
- Replaced `assets/projects/ncc-01.jpg` (the NCC project's cover/front photo)
  with the new title-page photo supplied (Project Sponsor: NCC, Consultant:
  Estadysta), caption updated to describe it as the audit report's cover page.
