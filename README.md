# monfortbrian.com

Portfolio of Monfort Brian - Product Design Engineer.

## Stack

Astro · Vanilla CSS · IBM Plex Mono · Lucide icons · Netlify

## Add a project

In `src/pages/index.astro`, add an entry to the `projects` array with `id`, `name`, `href`, `label`, `color`, `desc`, `tags`, and `svg`.

## Add a case study or post

1. Add a cover image to `public/work/` or `public/blog/`
2. Add an entry to `caseStudies` or `writing` in `index.astro`
3. Add the content to `src/pages/work/[slug].astro` or `src/pages/blog/[slug].astro`

## Deploy

Push to `main` - Netlify auto-deploys.

```
Build command:  npm run build
Publish dir:    dist
```