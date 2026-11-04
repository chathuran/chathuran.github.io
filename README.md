# Chathuran Dannoruwa — portfolio

A buildless, responsive portfolio for software engineering, DevOps, cloud engineering, and a transition into cybersecurity analysis. Professional claims are grounded in the existing résumé and portfolio. Planned security projects are explicitly labelled as future work.

## Preview locally

Use your editor’s Live Server, or run:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Then visit `http://127.0.0.1:8000`. No package installation or build is required. Clipboard copying needs a secure context (HTTPS or localhost); the email link also works directly.

## Files

- `index.html` — content, structured data, social metadata, and accessible role tabs.
- `css/styles.css` — styling, responsive layouts, and reduced-motion support.
- `css/case-studies.css` — scoped case-study styling and responsive additions.
- `css/study-page.css` — shared layout for standalone case studies.
- `case-studies/` — five standalone HTML case-study pages.
- `js/main.js` — role switching with keyboard navigation, mobile menu, active navigation, email copying, and current year; shared with case-study pages.
- `assets/` — updated `profile.png` photo and downloadable `Chathuran Dannoruwa Resume.pdf`.
- `llms.txt`, `robots.txt`, `sitemap.xml` — discovery metadata for the existing GitHub Pages address.
- [PROJECT-ACTION-PLAN.md](PROJECT-ACTION-PLAN.md) — a proposed eight-week personal project roadmap with acceptance criteria and recruiter deliverables.
- [SEO-LAUNCH-CHECKLIST.md](SEO-LAUNCH-CHECKLIST.md) — publishing, Google Search Console, indexing, and name-search follow-up steps.

## Maintaining the content

Keep employment dates, metrics, and contact details consistent with the résumé. Update the résumé PDF separately when changing career positioning; the current PDF is the updated software engineering résumé at `assets/Chathuran Dannoruwa Resume.pdf`. All CV links use its URL-encoded filename. Add completed personal projects with real links and supporting evidence. Do not present proposed work as shipped work or claim certifications that have not been earned.

The two project illustrations are conceptual CSS visuals, not screenshots of the products. Fonts are served by Google Fonts with system fallbacks; other visual assets are local.

## Engineering case studies

The homepage links to five static case-study pages. Each covers the problem, contribution, approach, outcome, and takeaway, with in-page navigation, related studies, and a return link. All case-study content and links work without JavaScript.

- `case-studies/complexica.html` — backend performance optimisation.
- `case-studies/unifi.html` — automated AWS delivery.
- `case-studies/audience.html` — secure real-time integration.
- `case-studies/packtheapps.html` — independent travel product, linked from Selected Work.
- `case-studies/spring-boot-flow-visualizer.html` — published developer tool, linked from Selected Work.

Professional accounts are based on the résumé. Personal-project accounts use the existing portfolio’s product descriptions; they do not claim an unverified implementation stack or usage figures. The diagrams are simplified illustrations. Old homepage case anchors still lead to their overview cards; share the standalone page URL for the full account.

Edit the HTML files directly; no generator or build step is required. When adding a case, update its homepage link, previous/next navigation, `sitemap.xml`, and `llms.txt`.

## Hosting

The source remains compatible with GitHub Pages: publish the repository root with `index.html`, `case-studies/`, `css/`, `js/`, and `assets/`. The canonical address remains `https://chathuran.github.io/`. This change prepares the local source; it does not push or deploy it.
