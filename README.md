# dyakubu.github.io

Personal website built with [Hugo](https://gohugo.io) and [Tailwind CSS](https://tailwindcss.com), modeled on the structure of trevorkask.github.io: Home, Projects, Blogs, Classes, Bookshelf.

## Develop locally

```
npm install
npm run dev
```

Visit http://localhost:1313.

## Content

Each section lives under `content/<section>/` as Markdown files with frontmatter (`title`, `date`, `summary`, optional `link`). New drafts are created with `draft: true` — remove that line to publish them.

Site-wide info (name, tagline, bio, socials) lives in `hugo.toml` under `[params]`. Several values are still marked `TODO` and need to be filled in.

## Deploy

Pushing to `main` triggers `.github/workflows/deploy.yml`, which builds the site with Hugo and publishes it to GitHub Pages.
