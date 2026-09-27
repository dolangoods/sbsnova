# SBS Nova website

Static redesign of [sbsnova.com](https://www.sbsnova.com) for Smart Business Services.

Plain HTML and CSS with no build step. Open `index.html` in a browser, or serve the folder with any static host (GitHub Pages works out of the box).

## Pages

| File | Page |
| --- | --- |
| `index.html` | Home |
| `about.html` | About & team |
| `services.html` | Services overview |
| `accounting-financial-services.html` | Accounting & Financial Services |
| `payroll-benefits-management.html` | Payroll & Benefits Management |
| `tax-preparation-planning.html` | Tax Preparation & Planning |
| `marketing-administrative-services.html` | Marketing & Administrative Services |
| `association-services.html` | Association Services |
| `sbs-delmarva.html` | SBS Delmarva |
| `startup-services.html` | Startup Services |
| `contact.html` | Contact |

## Notes

- Scroll effects (parallax, fade-in) use CSS scroll-driven animations. They run in Chrome, Edge, and recent Safari; other browsers show the pages without motion. Motion is turned off for visitors who set "reduce motion".
- The contact form is not connected to anything yet. It needs a form service (for example Formspree or Netlify Forms) before it can send.
- Team headshots live in `assets/team/`.
- The header logo is `assets/sbs-logo.svg`, traced from `assets/sbs-logo.png` (which is still used as the favicon). The trace uses flat colours in the swoosh; replace it with the designer's original vector if one turns up.
- The header has no text links: a "Menu" button opens a panel (`assets/menu.css`) listing every page, including all services. On desktop it is a wide panel; below 1100px it becomes a stacked list.
- Tablet and phone layouts live in `assets/mobile.css`. Page styles are inline, so the overrides match on the inline style text and use `!important`.
