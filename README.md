# Sivaraman Siddha Research Foundation

A responsive, multi-page website for Sivaraman Siddha Research Foundation (SSRF), built as a dependency-free static site.

## Run locally

Open `index.html` in a browser and use the navigation to move between pages. No package installation, build step, or development server is required.

The inquiry form validates required fields and submits them to `ssrf@arogyahealthcare.com` through FormSubmit. On first use, the recipient must activate FormSubmit using the verification email it sends.

## Pages

- `index.html` — Home
- `about.html` — About SSRF
- `focus-areas.html` — Focus areas
- `research.html` — Research and innovation
- `conferences.html` — Conferences and AURA 2027 registration form
- `collaborations.html` — Institutional collaborations
- `impact.html` — Community impact
- `leadership.html` — Leadership and governance
- `partnerships.html` — Partnerships, CSR, and compliance
- `contact.html` — Contact details and inquiry form

All pages share `styles.css` and `site.js`. Keep these files, the `assets` folder, and the HTML pages together when moving or publishing the site.

AURA 2027 registration is embedded from Google Forms and also linked externally as a fallback. Google Forms may require sign-in depending on the form's access settings.

The homepage also features a direct AURA 2027 registration link and a link to the full conference details and embedded form.
