# Continental Intertrade Ltd — Website

Official website for **Continental Intertrade Ltd**, a Nigerian maritime company working in boat manufacturing, marine engineering and maintenance, maritime training, and coastal community development, starting in Bayelsa State.

> Building Maritime Capacity. Connecting Communities. Transforming Lives.

## Pages

Single-page app with hash routes:

| Route | Content |
| --- | --- |
| `#home` | Hero, company facts, core business areas, vision and mission, Bayelsa, expansion phases |
| `#about` | Company story, vision, mission, value proposition, corporate values, safety, aspiration |
| `#boats` | A. Boat Manufacturing and Assembly |
| `#maintenance` | B. Boat Maintenance, Repair and Marine Engineering |
| `#training` | C. Maritime Training and Youth Empowerment |
| `#communities` | D. Riverine and Coastal Communities, Bayelsa commitment, social impact |
| `#partner` | Partnerships and investment, expansion strategy, target customers |
| `#contact` | Offices, phone, enquiry form |

## Stack

Plain HTML, CSS and JavaScript. No build step and no dependencies. The font (Plus Jakarta Sans) loads from Google Fonts.

```
index.html          the whole site
assets/favicon.svg  logo mark
assets/img/         photography and logo files
```

## Run locally

```bash
npx serve .
# or
python3 -m http.server 8000
```

## Deploy

Works on any static host: Vercel, Netlify, GitHub Pages or cPanel. Upload the folder as is, with `index.html` at the root.

## Contact form

The form validates input but does not send email yet. Before launch, connect it to a form service (for example Formspree or Netlify Forms) or to a backend endpoint in the `submit` handler at the bottom of `index.html`.

## Brand

| Colour | Hex |
| --- | --- |
| Delta Green | `#445E22` |
| Sunrise Orange | `#EE8A2A` |
| Laterite Red | `#C0392B` |
| Marine Blue | `#0754BE` |
| Night Charcoal | `#17140F` |
| Sand Cream | `#F6EFE2` |

Typeface: Plus Jakarta Sans.

## Contact

- Head Office: 3rd Floor, The Mall by Funab, First Avenue, Gwarimpa, Abuja
- Abuja Office: B66 Efab Mall, Area 11, Garki, Abuja
- Boatyard: Continental Boatyard, The Marine Base, Ovom, Yenagoa, Bayelsa State
- Phone: 0806 000 0399
- Web: www.africancontinentalintertrade.org

© 2026 Continental Intertrade Ltd. All rights reserved.
