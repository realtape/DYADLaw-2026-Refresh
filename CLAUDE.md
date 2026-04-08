# DYADLaw 2026 Refresh

## Project Overview
Static HTML/CSS/JS website for DYADLaw immigration law firm.
- **Live URL**: https://dyadlaw.vercel.app
- **GitHub**: https://github.com/realtape/DYADLaw-2026-Refresh
- **Managed by**: NetWebMedia

## Tech Stack
- Vanilla HTML5, CSS3, JavaScript (no build step)
- Google Fonts: Manrope, Sora
- Deployed via Vercel (auto-deploys on push to `main`)

## Site Structure
- Bilingual: Spanish (default) + English (`-en` suffix files)
- Root HTML pages: `index.html`, `servicios.html`, `blog.html`, `contacto.html`, etc.
- Service detail pages: `/servicios/[service-name]/index.html`
- Blog articles: `blog-[slug].html` + `blog-[slug]-en.html`
- Styles: `style.css` (single file, ~1155 lines)
- Scripts: `main.js` (nav, language switcher, WhatsApp bot, share/comment system)
- Assets: `wp-content/uploads/` (migrated from WordPress)

## Key Conventions
- Always update BOTH language versions when editing content
- Language switcher uses MX/US flags via flagcdn.com
- WhatsApp bot widget is site-wide (configured in main.js)
- Commit messages should describe what changed and why

## Workflow
Use the `netwebmedia-update-website` skill for the full edit-commit-deploy cycle.
