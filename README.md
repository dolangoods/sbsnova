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
- Team photos on the About page are placeholders showing initials.
- Layouts are designed for desktop widths; mobile breakpoints are still to do.
