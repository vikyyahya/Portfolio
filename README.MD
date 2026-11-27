# Viky Yahya — Portfolio

Static, bilingual personal portfolio for https://vikyyahya.my.id/, deployed with Cloudflare Pages. The website lives in `index.html`; no build process or application dependencies are required.

## Local preview

Run `python3 -m http.server 8000` from this directory and visit `http://localhost:8000`.

## Content

- Introduction and technical focus
- Selected professional projects: SIRUKIM, KoltiTrace MIS, and JAKHABITAT
- Professional experience, technical expertise, and development approach
- Email, GitHub, LinkedIn, and an email-based CV request

Project descriptions distinguish individual contributions within team projects. No private company source code, invented metrics, sample articles, or placeholder project links are published.

## Editing

Keep Indonesian and English copy in the `i18n` object synchronized. Each `data-i18n` key must exist in both languages. Also update the Indonesian HTML fallback so content remains readable without JavaScript. Language preference storage is optional; the page still works when browser storage is unavailable.

Use existing CSS variables to maintain the dark purple and teal theme. Keep visible keyboard focus, reduced-motion support, and mobile navigation when changing styles.

## Publication

Push the reviewed change to the connected GitHub repository. Cloudflare deployment depends on the repository's existing branch configuration; a branch push alone does not confirm a production deployment.
