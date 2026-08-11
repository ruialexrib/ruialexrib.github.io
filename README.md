# Rui Ribeiro — Personal Website

Static personal website focused on management, Business Intelligence, Artificial Intelligence, training, and applied research.

The project uses plain HTML, CSS, and JavaScript, includes Portuguese and English versions, and is hosted with GitHub Pages.

## Pages

- `index.html` — personal and professional profile
- `blog/index.html` — static list of externally published articles
- `en/` — English version of the website and blog

## Update the blog

The blog is a static collection of cards linking to articles published on external platforms such as LinkedIn.

When adding an article:

1. Duplicate an existing `post-card` in `blog/index.html`.
2. Update the date, category, title, short description, and external URL.
3. Add the translated card to `en/blog/index.html`.
4. Keep the newest article at the top of both pages.

The full article remains on the external platform; the website only displays its summary and a **Read more** link.

## Publish

Push the files to the `main` branch and enable GitHub Pages from the repository root.

[View the website](https://ruialexrib.github.io)
