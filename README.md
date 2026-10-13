# Sarah Holdyn — Official Website

Static site for Sarah Holdyn, country / country-pop singer-songwriter (Upper Midwest). Plain HTML + CSS, hosted on GitHub Pages.

## Structure

```
index.html            Home — hero, next 3 shows, booking callout
about/index.html      About Sarah
shows/index.html      2026 show list
live/index.html       The band, live photos
contact/index.html    Booking contact + StaticForms form
assets/css/style.css  Brand tokens + all styles
assets/img/           Logos (cream / gold / navy), photos, favicon
```

## Brand (2026 guide)

| Token | Hex | Use |
|---|---|---|
| Midnight Navy | `#132A3D` | Primary — header, sections, logo ground |
| Night Sky | `#0E1C29` | Page background |
| Prairie Cream | `#E8E0D0` | Text on dark, light sections |
| Golden Hour | `#C9A46A` | Labels and buttons on dark |
| Saddle Leather | `#7E4E2E` | Labels and links on cream |

Fonts: **Cinzel** (headers) and **Work Sans** (body), via Google Fonts.

## Before launch

- [ ] Fill in show cards (`[DATE]`, `[VENUE NAME]`, `[CITY, STATE]`) in `shows/index.html`, and copy the next 3 to the home page's "Next Up"
- [ ] Booking email (`[BOOKING EMAIL]`) in `contact/index.html`
- [ ] StaticForms access key (`[STATICFORMS_ACCESS_KEY]`) and redirect URL (`[SITE_URL]`) in `contact/index.html`
- [ ] Swap photos for full-resolution originals from the photographer
- [ ] Point the domain (GoDaddy) and add a `CNAME` file

Header and footer are repeated in every page. Change one, change all five.
