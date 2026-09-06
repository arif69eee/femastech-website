# femastech.com

Static marketing site for **FEMAS Tech** — an electro-mechanical engineering consultancy in
Mirpur, Dhaka, Bangladesh. Published with GitHub Pages at <https://femastech.com>.

## Structure

| File | Purpose |
|---|---|
| `index.html` | Home — hero, six electrical disciplines, MEP, featured projects, clients |
| `services.html` | Six electrical services in detail + mechanical / plumbing / HVAC / fire / PMC |
| `projects.html` | 157 projects, searchable and filterable by sector |
| `about.html` | About, vision, company snapshot, divisions, key personnel |
| `contact.html` | Phone, email, address, pre-filled enquiry |
| `404.html` | Not-found page |
| `assets/style.css` | All styling (single stylesheet, no build step) |
| `assets/logo.png` | FEMAS wordmark (dark) |
| `assets/logo-light.png` | FEMAS wordmark (for dark backgrounds) |
| `assets/favicon.png` | Favicon |
| `CNAME` | Custom domain for GitHub Pages |
| `.nojekyll` | Skip Jekyll processing |

No frameworks, no build step. Edit the HTML directly and push to `main` — GitHub Pages redeploys
automatically.

## Editing content

- **Add a project:** add an `<li data-c="SLUG">` inside the matching `<section class="pgroup">`
  in `projects.html`, then bump the group's `<i data-gc>` count and the totals in the hero and
  `#count`. Filtering and search pick it up automatically.
- **Change contact details:** they appear in the footer of every page and in `contact.html`.
- **Colours and type:** the CSS custom properties at the top of `assets/style.css`.

## Deliberately not published

Trade licence number, TIN, BIN (VAT), bank details and staff dates of birth from the company
profile are intentionally left off the public site.
