# @sveltejs/site-kit changelog

## 6.0.0-next.17

### Patch Changes

- 2bdd8c8: Make backdrop blur more pronounced

## 6.0.0-next.16

### Patch Changes

- cd9443a: tick() before getting element

## 6.0.0-next.15

### Patch Changes

- 637073a: fix: horrifically stupid bug with scrolling to IDs

## 6.0.0-next.14

### Patch Changes

- 1f883c9: Wait for hash element to be created

## 6.0.0-next.13

### Patch Changes

- d997ad9: Fallthrough headings like Kit

## 6.0.0-next.12

### Patch Changes

- 3640de4: fix: body & html height 100%

## 6.0.0-next.11

### Patch Changes

- 88568b0: Only look at h2, OnThisPage

## 6.0.0-next.10

### Patch Changes

- 9cd354a: fix: remove debug logging

## 6.0.0-next.9

### Minor Changes

- 4c4d4f0: feat: markdown renderer

### Patch Changes

- 47075f4: fix: manually scroll to URL hash
- 0f4a684: fix: external links

## 6.0.0-next.8

### Patch Changes

- 7b60778: Relative heights and units, perf improvments on nav animation, more contrast on page indicator

## 6.0.0-next.7

### Patch Changes

- e601284: fix: Open context menu only if current link has sections

## 6.0.0-next.6

### Patch Changes

- d8d64f8: fix link styles inside blockquotes

## 6.0.0-next.5

### Patch Changes

- e4bcc56: Fix clicking on context menu arrow throws error

## 6.0.0-next.4

### Patch Changes

- 2911dad: require props to be set on <Nav> instead of reading $page.data

## 6.0.0-next.3

### Patch Changes

- 2422a25: fix homepage link colour, remove subtitle on desktop

## 6.0.0-next.2

### Patch Changes

- 3fce2fa: remove subtitle from desktop nav, separate it from homepage link

## 6.0.0-next.1

### Patch Changes

- ff16f3a: allow nav to scroll, fix JS/TS toggle position

## 6.0.0-next.0

### Major Changes

- 9ef4ece: - Mobile navbar
  - DocsMobileNav
  - Consistent sk-theme-1 using `color-mix` across all pages
  - Move Docs Contents and OnThisPage to here from svelte.dev
  - Blockquote styling
  - Move `Nav`, `NavItem`, `PreloadingIndicator`, `Separator`, `SkipLink` to `@sveltejs/site-kit/nav` export
  - Add `@sveltejs/site-kit/stores` export
  - Add `@sveltejs/site-kit/actions` export

## 5.2.2

### Patch Changes

- a6d1692: monochrome terminal chrome

## 5.2.1

### Patch Changes

- f4d6bd3: Fix link color

## 5.2.0

### Minor Changes

- d5eaf17: Restyle blockquotes, deprecated styles for blockquotes

## 5.1.0

### Minor Changes

- 6ac9a9f: Different color links, link underlines, custome focus outlines

### Patch Changes

- ccd5cca: chore: add IME support for SearchBox

## 5.0.4

### Patch Changes

- 909d06b: Fix some ThemeToggle/Nav a11y issues

## 5.0.3

### Patch Changes

- f869cee: Remove left-over legacy styles

## 5.0.2

### Patch Changes

- 18614db: Expose theme store

## 5.0.1

### Patch Changes

- c793472: fix Nav referencing wrong ThemeToggle path

## 4.1.1

### Patch Changes

- f25e098: Make twoslash hint underlines visible in dark mode too

## 4.1.0

### Minor Changes

- 13e760d: Add TSToggle

## 4.0.2

### Patch Changes

- 5f7d368: Fix: Don't hide navbar's home text label

## 4.0.1

### Patch Changes

- 05fb5f7: Include svelte-local-storage-store as dependency

## 4.0.0

### Major Changes

- 6c04846: Dark mode toggle, dark mode styles changed as well

  This is a breaking change because svelte.dev and kit.svelte.dev rely on variables changing based on `@media (prefers-color-scheme: dark)`, and the variables belonging to `:root` rather than `body`

### Minor Changes

- faff260: Ship media queries alongside classes on body

### Patch Changes

- 6c90b5d: Minor fixes to style

## 4.0.0-next.1

### Minor Changes

- faff260: Ship media queries alongside classes on body

## 4.0.0-next.0

### Major Changes

- 6c04846: Dark mode toggle, dark mode styles changed as well

  This is a breaking change because svelte.dev and kit.svelte.dev rely on variables changing based on `@media (prefers-color-scheme: dark)`, and the variables belonging to `:root` rather than `body`

## 3.4.0

### Minor Changes

- 68591be: Add TryTerminal component

## 3.3.7

### Patch Changes

- d47bd2c: fix: component docs, fix some type issues
- cb01ce4: Make dark mode diff code style easier on eyes

## 3.3.6

### Patch Changes

- bf48152: fix: import name

## 3.3.5

### Patch Changes

- e054c00: fix: generate d.ts files for .js files

## 3.3.4

### Patch Changes

- 497e1df: fix: use default slot content as fallback for NavItem small view
- 497e1df: chore: provide barrel exports for components, search and actions
- 497e1df: fix: remove SearchBox from Shell for broader reuse

## 3.3.3

### Patch Changes

- f31eefc: fix: remove $lib aliases for now

## 3.3.2

### Patch Changes

- 22c98a8: fix: add svelte and sveltekit as peerDeps

## 3.3.1

### Patch Changes

- d749be7: fix: adjust import path

## 3.3.0

### Minor Changes

- 72a9a1b: feat: add shell component and adjust related components
- ba90252: feat: add actions and search for reuse

## 3.2.2

### Patch Changes

- 8d1661d: Fix accessibility bug

## 3.2.1

### Patch Changes

- 179d5dc: Fix publishDir

## 3.2.0

### Minor Changes

- 295e194: Add Blurb component(barebones), update dependencies, and export components from index.js

## 3.1.0

- Remove space for top banner ([#57](https://github.com/sveltejs/site-kit/pull/57))

## 3.0.3

- Change blockquote styles

## 3.0.2

- Undo last change, which fails for bewildering reasons

## 3.0.1

- Make everything `position: relative` by default

## 3.0.0

- Overhaul

## 2.1.4

- Decouple from SvelteKit ([#390](https://github.com/sveltejs/sites/pull/390))

## 2.1.3

- Remove `<Hero>` component
- Improve image caching
- Update dependencies

## 2.1.2

- Fix `<Hero>` component

## 2.1.1

- Update `<Hero>` component
- Remove `sveltekit:prefetch`

## 2.1.0

- Tweak sidebar styles

## 2.0.3

- Revert CSS logical properties change, which breaks in some browsers ([#303](https://github.com/sveltejs/sites/pull/303))

## 2.0.2

- Add `id` attributes to `<h2>` elements, instead of using offset anchors

## 2.0.1

- Remove `z-index` from `<ul>` in nav component

## 2.0.0

- New `latest` version

## 2.0.0-next.7

- Rebuilt using SvelteKit
- Shipped with declaration files
- Added `<SkipLink>`
- Various

## 2.0.0-next.6

- Remove some problematic CSS

## 2.0.0-next.5

- Tweak docs `h1` styles

## 2.0.0-next.4

- Fix home link
- Centralise more styles and icons
- Allow headings to have their own `id` attributes
- Add permalinks dynamically
- Support more flexible doc data sources

## 2.0.0-next.3

- Move nav styles out of app into `<Nav>` component
- add some common icons

## 2.0.0-next.2

- Fix exports

## 2.0.0-next.1

- Various

## 2.0.0-next.0

### Major Changes

- Change slug generation logic, tweak some styles

## 1.2.5

- Fix menu scrolling behaviour ([#29](https://github.com/sveltejs/site-kit/pull/29))

## 1.2.4

- Fix anchor placements ([#28](https://github.com/sveltejs/site-kit/pull/28))

## 1.2.3

- Fix iOS input styles ([#23](https://github.com/sveltejs/site-kit/pull/23))

## 1.2.2

- Use `dir` prop to `<Docs>` component in constructing nav links

## 1.2.1

- Add `diff` language

## 1.2.0

- Add `noopener noreferrer` to links ([#6](https://github.com/sveltejs/site-kit/pull/6))
- Fix blurb layout bug ([#9](https://github.com/sveltejs/site-kit/pull/9))
- Fix REPL toggle CSS ([#14](https://github.com/sveltejs/site-kit/pull/14))
- Preserve outlines on focus ([#15](https://github.com/sveltejs/site-kit/pull/15))
- Fix size of arrow in blurb ([#18](https://github.com/sveltejs/site-kit/pull/18))
- Expose `title` prop on `<NavItem>` ([#17](https://github.com/sveltejs/site-kit/pull/17))

## 1.1.5

- Allow Svelte syntax highlighting in code blocks ([#12](https://github.com/sveltejs/site-kit/pull/12))

## 1.1.4

- i18n changes

## 1.1.3

- Fix iOS styles

## 1.1.2

- Squelch a11y warning

## 1.1.1

- Add `dir` prop to Docs

## 1.1.0

- Add `project` prop to Docs component
- Use HTML tags for doc titles

## 1.0.4

- Prevent `<pre>` in homepage blurb breaking grid layout

## 1.0.3

- Missing sidebar text

## 1.0.2

- Various CSS tweaks

## 1.0.1

- Add `base.css` to `pkg.files`

## 1.0.0

- First release
