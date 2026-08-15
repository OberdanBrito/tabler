# @tabler/docs

## 1.5.0

### Minor Changes

- 4a97921: Added `Accordion` documentation page with usage variants and Bootstrap `collapse` behavior examples.
- 3277fa0: Added `Astro` icons library documentation page for the new `@tabler/icons-astro` package.
- d8956a0: Updated the `preview` and `docs` packages to build with Astro instead of Eleventy.
- 416ca63: Added framework integration guides for Laravel, React, Next.js, Vue, Angular, Nuxt, Symfony, Django, Rails, SvelteKit, and Astro.
- bd4e381: Added `Star Rating` documentation page with static and interactive rating examples based on existing classes.
- 8af57f9: Added `Tag` documentation page with examples for icon, media, badge, checkbox, and list usage.
- f4c514a: Added an `Upgrade to 1.5` page with the breaking changes, renamed classes and Sass updates from 1.4.

### Patch Changes

- 1effe22: Fixed the skip link to appear on focus and added missing `<main>` and labelled `<nav>` landmarks.
- dd4214b: Fixed accessibility issues in skip links, keyboard focus, `prefers-reduced-motion`, form labels and action controls.
- 100a37b: Added background pattern utilities and documentation, including updated preview demos.
- 46da1f7: Updated background patterns documentation with missing pattern variants, transparent utility usage, and size coverage.
- ffe3489: Updated `.badges-list` to `.badge-list` and `.tags-list` to `.tag-list`, keeping the old names as deprecated aliases.
- 1ec82d0: Updated the contributing guide, README and Docker setup for the Astro-based development toolchain.
- 8704725: Updated preview and docs examples to the unified demo component props: `variant`, `color`, `size`, `ariaLabel`.
- 1ec82d0: Updated dev servers to run on fixed ports: `3000` for preview and `3010` for docs.
- 684f40e: Updated the documentation to explain font sizing and system color CSS variables.
- a0d84f6: Updated the How to Contribute guide with starter issues, Codespaces setup, commands and PR conventions.
- 1ec82d0: Fixed documentation formatting issues: heading hierarchy, missing image alt texts and broken list structure across docs pages.
- c430cfe: Updated UI component docs to singular file names and frontmatter, with redirects from plural routes.
- 826a073: Added `sitemap.xml` and `robots.txt` endpoints for the docs site and fixed docs layout title rendering outside production.
- 0f8dcb0: Updated preview and docs to use the shared `date-format`, `string-format` and `pseudo-random` helpers.
- c547329: Fixed the `Plugins` card on the docs homepage linking to a 404 `/plugins` route instead of `/ui/plugins`.
- 9c78cf6: Fixed `.bg-gradient` conflicts that broke `from`/`via`/`to` rendering and updated the gradient docs.
- 6db32ea: Added root-level `lint-prettier` and `format-prettier` scripts and wired `check` to run lint and type-check.
- a198b0c: Added the Geist and Geist Mono fonts as the default `$font-family-sans-serif` and `$font-family-monospace`.
- f11ece4: Added `--pattern-opacity-factor` and `.bg-pattern-opacity-*` utilities for background patterns.
- 43eee38: Added `Progress Step` component documentation and cleaned up the progress steps preview markup for cleaner rendered output.
- 08cad98: Updated the `Progress Bar` documentation with new variants and full-width stacked previews.
- 1489b13: Added `.prose` alias for markdown content and updated preview/docs references and redirects.
- 4d04c10: Removed the unused `bootstrapLink` front matter field from `DocsLayout`, `DocsMdxLayout`, and all docs pages.
- ab8009b: Fixed the DocSearch search box and dropdown colors in dark mode.
- 8f86f1f: Updated Tabler Illustrations to v1.16.0 with 20 new illustrations.
