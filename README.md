# BeeCyberSafe

Website for **BeeCyberSafe** — free, friendly online-safety sessions for the
Brentford community. BeeCyberSafe is a community programme from **BlueHive
Security** (the parent company; its own corporate site is not built yet and is
linked as a placeholder in the nav).

## Structure

A single static page, no build step:

- `index.html` — all markup and copy
- `styles.css` — all styling (design tokens live in `:root` custom properties)
- a tiny inline `<script>` at the foot of `index.html` for the mobile menu,
  active-nav highlighting, and scroll reveals (motion-safe only)

The visual system (Fraunces + Public Sans; warm cream / canal-green /
terracotta palette; the bee mark and quiet canal band) follows the agreed
BeeCyberSafe brand foundations.

## Local development

Open `index.html` in a browser. No tooling, no build.

## Updating content

- **Session dates / venue** — edit the `.session-when` lines and the
  "Where & when" card in `index.html`.
- **Colours / type** — change the CSS custom properties in `:root` at the top
  of `styles.css`.

## Deployment

Hosted on GitHub Pages.

- `CNAME` sets the custom domain. Canonical domain is **bluehivesecurity.co.uk**;
  `beecybersafe.co.uk` (and the `.com`) should redirect to it at the DNS / domain
  registrar level.
- `nojekyll` disables Jekyll processing (the site is plain static files).

## Privacy

No tracking, no analytics, no cookies, no forms. The site collects no data.
