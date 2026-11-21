# vinaymatsa.github.io

Personal website of **Vinay Matsa**, Microsoft Power Platform & Copilot Studio Developer.

Live site: https://vinaymatsa.github.io/

## Structure

| Path | What it is |
|---|---|
| `index.html` | Home page: about, projects, articles, skills, certifications, experience, contact |
| `404.html` | "Page not found" page |
| `assets/css/style.css` | All styles |
| `assets/img/` | Images and the favicon |
| `_templates/article.html` | Template for new articles (not published, because the folder starts with `_`) |

Plain HTML and CSS, no build step. GitHub Pages publishes the `main` branch.

## Common edits

- **Add your photo:** save it as `assets/img/profile.jpg`, then in `index.html` replace `VM` inside the `avatar` element with `<img src="assets/img/profile.jpg" alt="Vinay Matsa">`.
- **Add an article:** copy `_templates/article.html` to `articles/<short-name>.html`, fill in the bracketed parts, and add a card for it under "Latest articles" in `index.html`.
- **Use a custom domain later:** add it under Settings → Pages → Custom domain, then update the `canonical` and `og:url` links in `index.html`.
