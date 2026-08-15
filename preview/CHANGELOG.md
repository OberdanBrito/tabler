# @tabler/preview

## 1.5.0

### Minor Changes

- 5e119d4: Added Pay page with dedicated layout, navigation link, and card/PayPal payment form.
- d8956a0: Updated the `preview` and `docs` packages to build with Astro instead of Eleventy.
- 100a37b: Added background pattern utilities and documentation, including updated preview demos.
- ec94693: Added new `card-gradients` page showcasing various gradient card styles and components.
- b0fa655: Added Change Password modal with a strength indicator, confirm validation and show/hide toggles.
- ad22d04: Added a color palette to the signature pad component for selecting the pen color.
- b0fa655: Added Confirm Delete modal with a warning icon and a checkbox that enables the delete button.
- 62178f8: Added new `dashboard-crm` page with reusable CRM cards.
- 4ce08ca: Added new Crypto Dashboard page with cryptocurrency portfolio overview, market data, and order history.
- 118ca4b: Updated the demo pages to show their title and description in the page header, with `pageHeader` falling back to `title`.
- b0fa655: Added Edit Profile modal with avatar upload, personal information fields, social links, and date of birth.
- 8d8727f: Added language selector dropdown to navbar with flag indicators for multilingual support.
- 4ce08ca: Updated the page-menu structure for dashboards and reorganized the navigation menu.
- 4ce08ca: Updated the navbar-side component and reorganized its apps, language, notifications and user sections.
- b0fa655: Added New Task modal with fields for task name, description, assigned user, priority, due date, and category tags.
- 9c5d729: Added new onboarding page with progress indicator and navigation layout.
- 118ca4b: Removed the `actions` preset prop from `DefaultLayout`; pages now fill a `page-header-actions` slot instead.
- cc298a6: Added a `PageTitle` component and used it with `CardSubtitle` in place of raw `.page-title` and `.card-subtitle` markup.
- 9c5d729: Added Progress Background component with text labels and value display.
- 9c5d729: Added Progress Steps component for step-by-step navigation indicators.
- 5363668: Added the missing Prose demo page, linked from the menu but not previously built.
- 99b9ea4: Added a Task List page with tasks grouped by status and a modal for adding new tasks.
- 7556ae2: Added an `auto` color mode to theme settings with system `prefers-color-scheme` support.
- e3d86c5: Updated `apexcharts` from `3.54.1` to `5.3.6` and added `--chart-{id}-color-{index}` variables.

### Patch Changes

- 1effe22: Fixed keyboard access by turning JavaScript-only `<a href="#">` controls into real `<button>` elements.
- 1effe22: Added missing ARIA roles and states to `Pagination`, `NavSegmented`, `Accordion`, `Steps`, tabs, `Modal`, `Offcanvas` and `CarouselCard`.
- 1effe22: Added `aria-label` to the `Datepicker` navigation buttons and made the `Dropzone` upload area keyboard-operable.
- 1effe22: Added `<fieldset>` and `<legend>` around radio and checkbox groups so screen readers announce the group purpose.
- 1effe22: Fixed form accessibility with matching `for`/`id` labels, `aria-invalid`, `aria-describedby` and `autocomplete` tokens.
- 1effe22: Fixed the skip link to appear on focus and added missing `<main>` and labelled `<nav>` landmarks.
- 1effe22: Added a `label` prop to `Flag`, `Payment`, `StatusDot`, `Trending` and `Avatar` status badges for screen readers.
- dd4214b: Fixed accessibility issues in skip links, keyboard focus, `prefers-reduced-motion`, form labels and action controls.
- 0fd35c3: Updated the `active-users-2` card chart to use `chart-id="active-users-2"` with `height="11"` for a more compact layout.
- ffe3489: Updated `.badges-list` to `.badge-list` and `.tags-list` to `.tag-list`, keeping the old names as deprecated aliases.
- 8704725: Fixed root-absolute `Button` hrefs in demos, so error-page links work in the downloadable package.
- da11f08: Added a short description and a docs link to each card on the Buttons demo page, grouped into Styles and Colors.
- 118ca4b: Fixed heading order by making `CardTitle` and `CardHeader` render `h2`, so cards no longer skip a level under the page `h1`.
- 4ce08ca: Added `crypto-markets.json` and `crypto-orders.json` data files for the crypto dashboard.
- 8704725: Updated preview and docs examples to the unified demo component props: `variant`, `color`, `size`, `ariaLabel`.
- 1ec82d0: Updated dev servers to run on fixed ports: `3000` for preview and `3010` for docs.
- 0f8dcb0: Updated preview and docs to use the shared `date-format`, `string-format` and `pseudo-random` helpers.
- 3f1ad9d: Fixed the navbar not highlighting the active page for nested, RTL and settings pages.
- f2004da: Fixed payment icons on the all-elements page by rendering separate light and dark variants.
- f2004da: Fixed the ribbon example background on the all-elements page to use `var(--tblr-bg-surface-secondary)`.
- 6db32ea: Added root-level `lint-prettier` and `format-prettier` scripts and wired `check` to run lint and type-check.
- ac87b76: Updated preview templates to replace deprecated `font-weight-*` classes with Bootstrap-compatible `fw-*` utility classes.
- 8704725: Fixed icon-only demo buttons rendering a generic `aria-label="Button"` instead of a real label.
- 8f86f1f: Updated Tabler Icons to v3.45.0 and restored the `import-icons` and `import-illustrations` scripts.
- 5363668: Made Interface demo pages consistent with the Buttons page: card subtitles, one docs link, responsive grids.
- 5e119d4: Added `bg-blur` utility and increased `container-tight` width for layout flexibility.
- 8704725: Updated the marketing CTA `Learn more` button to the `.btn-ghost` style.
- 7cadbb8: Updated `New` badges in `menu.json` to mark only pages added since 1.4, and dropped them from older pages.
- 8947d7c: Updated the activity feed messages in `activity.json` and the activity preview page.
- 863884e: Added `DocsLink` to the header of 20 more demo pages, including Cards, Charts, Tables and Typography.
- f11ece4: Added `--pattern-opacity-factor` and `.bg-pattern-opacity-*` utilities for background patterns.
- 118ca4b: Added a `meta` description tag, filled from the page `description` prop.
- 7305d84: Fixed Vercel deployment to serve `error-404.html` as the custom 404 page.
- 43eee38: Added `Progress Step` component documentation and cleaned up the progress steps preview markup for cleaner rendered output.
- 1489b13: Added `.prose` alias for markdown content and updated preview/docs references and redirects.
- bea97f8: Removed `@hotwired/turbo` integration, including `.turbo-progress-bar` styles and the Turbo loader preview demo.
- da11f08: Replaced lorem ipsum with unique placeholder text on the Scroll spy demo page and fixed its menu highlight.
- 83ec6f8: Added Driver.js library integration and Tour demo page for interactive product tours and onboarding guides.
- da11f08: Reorganized the Star Ratings demo page into Basic/Icons/Sizes and Colors cards with short descriptions.
- 9c5d729: Updated trending component to use `arrow-up`/`arrow-down` instead of `trending-up`/`trending-down`.
- bd35fd3: Fixed responsive layouts on the Form Elements page.
- 41fd82b: Updated `@tabler/icons` to v3.36.1.
- 8f86f1f: Updated Tabler Illustrations to v1.16.0 with 20 new illustrations.
- c707018: Added an All Elements page showing every UI component and Bootstrap element.
