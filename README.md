# Yichao Liu's Academic Website

Source code for [lyccc23.github.io](https://lyccc23.github.io/), the personal academic website of Yichao Liu.

The site is built with [Hugo](https://gohugo.io/) and [Hugo Blox](https://hugoblox.com/), and deployed with GitHub Pages.

## Local Development

Install Hugo Extended and pnpm, then run:

```bash
pnpm install
pnpm run dev
```

To build the static site:

```bash
pnpm run build
```

## Content

- Personal profile: `data/authors/me.yaml`
- Homepage layout: `content/_index.md`
- Publications: `content/publications/`
- CV PDF: `static/uploads/resume.pdf`
