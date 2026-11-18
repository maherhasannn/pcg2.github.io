# Piedmont Consulting Group — Website

Source for [piedmontgroup.org](https://piedmontgroup.org), the public website of **Piedmont Consulting Group (PCG)**, a student-run startup consultancy at UC Berkeley. The site is managed by the PCG team.

## What's here

A static HTML/CSS site, hosted on GitHub Pages (the `CNAME` file points the custom domain at this repo).

| Page | Purpose |
|------|---------|
| `index.html` | Home — mission, impact stats, client testimonial, community highlights |
| `about.html` | Our Team |
| `services.html` | Services offered to startups and established companies |
| `contact.html` | Contact |
| `recruitment-guide.html` | Recruitment guide for prospective members |
| `single.html` | Join Us / apply |
| `blog.html`, `main.html` | Leftover pages from the original template, not linked from the nav |

Shared styles live in `css/` (Bootstrap plus per-page stylesheets such as `home.css`, `team.css`, `join.css`, `services.css`, `contact.css`). Images, including team and client photos, are in `images/`. `fonts/` and `js/` hold the vendored template assets.

## Editing

There is no build step. Edit the HTML/CSS directly and push to `main`; GitHub Pages redeploys automatically. Recruitment status and application-cycle copy live in `index.html` and `contact.html`.

## Credits

Built on a Colorlib consulting template (see `readme.txt` for the template's license terms). PCG is student-run and independent of the University of California.
