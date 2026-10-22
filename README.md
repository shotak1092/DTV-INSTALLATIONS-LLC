# DTV Installations — website

New site for dtv-installations.com: 33 pages, static HTML, no build step.

## Layout

| Folder | What it is |
|---|---|
| `site/` | **The website.** Deploy this folder. `index.html` is the homepage. |
| `site/assets/img/` | Images used by the page designs. |
| `site/assets/work/` | Real job photos shown in the "Our Work" galleries. |
| `photo-library/` | Job photos for the service pages, sorted by page, with alt text in `photo-manifest.csv`. Open `photo-library/index.html` to browse. **Not deployed.** |
| Hold photos | Kept out of this public repo. Listed in the manifest as "Hold - fix first"; originals are in the offline package. |

## Deploy

- **Netlify:** connect this repo. `netlify.toml` already points it at `site/`.
- **Any other host:** upload the contents of `site/`.
- **Preview locally:** open `site/index.html` in a browser.

## Pages

- **Home:** index
- **Residential:** residential, home-theater, led-walls, home-audio, streaming, smart-home, shading-lighting, intercom, cctv, tv-mounting, remote-control, access-control
- **Commercial:** commercial, conference-room, churches, gyms, restaurants, sports-bars, digital-signage, mirror-displays, hotels
- **Areas:** new-york-ny, brooklyn-ny, oceanside-ny, yonkers-ny, paramus-nj
- **Company:** services, about, gallery, blogs, reviews, contact

## Brand

- Background `#0d0b0a`, text `#ece6dc`, gold `#D4AF55`, green `#2FA36B`
- Fonts: Bodoni Moda (headings), Manrope (body), from Google Fonts

## Before launch

1. **Contact form** is wired for Netlify Forms (submissions land in the Netlify dashboard → Forms; set an email notification there). Thank-you page: `thank-you.html`.
2. **Hours** on the contact page still read `[YOUR HOURS]`.
3. **Homepage claims to verify:** "4.9 on Google", "500+ projects", "$2M liability", "Lutron Platinum Dealer 2026". Each must be true and current.
4. **Phone:** office (212) 540-1199 in the header and call buttons; toll-free (888) 428-3330 in the footer, contact page and closing section of every page.
5. Real job photos are live in an "Our Work" gallery on each service page and on `gallery.html` (`site/assets/work/`). Photos in `photo-library/_hold-needs-fix/` are not on the site.
6. Add `sitemap.xml`, meta descriptions and Open Graph tags per page.
