# wenzhifang.github.io

Personal academic homepage — a single static page, no build tools.
Layout adapted from [Xingjian Diao's homepage](https://github.com/xid32/xid32.github.io).

## Editing

- `index.html` — all content (bio, news, publications, experience, service, contact)
- `index.css` — styling
- `images/` — avatar, icons, logos, publication thumbnails
- `uploads/resume.pdf` — CV

Preview locally: `python3 -m http.server` then open http://localhost:8000.
Push to `main` and GitHub Actions deploys it to GitHub Pages.

The previous Hugo version of the site is kept on the `hugo-backup` branch.
