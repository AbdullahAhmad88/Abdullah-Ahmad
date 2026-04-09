# Changelog

## [4.28.0](https://github.com/mmistakes/minimal-mistakes/releases/tag/4.28.0)

### Enhancements
- Updated Traditional Chinese translation (#5250)
- Add built-in support for jekyll-gfm-admonitions (#5312)
- Add Latte and Mocha skins from Catppuccin project (#5341)
- Add support for Swetrix, a GDPR-compliant analytics provider (#5344)
- Support resolving `ui-text` using `page.locale` when available (#5439)
- Add `aria-label` to all nav elements for WCAG compliance (#5442)
- Add IndieWeb microformat support and configurable footer `rel` attribute (#5443)
- Add `og:image:alt` and `twitter:image:alt` support (#5444)
- Add `fediverse:creator` meta tag for link preview attribution (#5445)
- Update hardcoded icon classes for Font Awesome 6 (#5446)
- Add missing brand-color rules for newer social platforms (#5447)
- Add custom sidebar content hook (#5448)
- Add config toggle to suppress taxonomy display on posts (#5449)

**Special thanks to @bexelbie for their contributions in this release.**

### Bug Fixes
- Fix some social icon colors and missing Korean translations (#5103)

## [4.27.3](https://github.com/mmistakes/minimal-mistakes/releases/tag/4.27.3)

### Bug Fixes
- Add explicit CSS rules for `.sr-only` following Font Awesome 7's changes. (#5296)

## [4.27.2](https://github.com/mmistakes/minimal-mistakes/releases/tag/4.27.2)

### Enhancements
- Hide `.page__footer-follow` if there are no links nor atom feed. (#5279)
- Add HTML escaping for some titles, labels and metada that was missing. (#5276)
- Add optional `footer.since` for copyright time range. (#5275)

### Bug Fixes
- Add `escape_once` to gallery title and alt text.

## [4.27.1](https://github.com/mmistakes/minimal-mistakes/releases/tag/4.27.1)

### Enhancements
- Add a "Share on Bluesky" button (#5179)
- Add preset variables for modern font stack (#5033)
- Update X share button to match brand color (#5245)

### Bug Fixes
- Fix wrong icon and color for X share button.

## [4.27.0](https://github.com/mmistakes/minimal-mistakes/releases/tag/4.27.0)

### Enhancements
- Add RTL Support. [#4886](https://github.com/mmistakes/minimal-mistakes/pull/4886)
- Add missing Polish translation. [#4890](https://github.com/mmistakes/minimal-mistakes/pull/4890)
- Rewrite most directions with [CSS logical properties](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_logical_properties_and_values).
- Remove unnecessary "type" attribute (#4956)
- The "if" means the default is never used (#4955)
- For pages without a title, show the site title only once (#4959)
- Use `documents-collection.html` partial in `home` layout.
- Add Bulgarian translation. [#5003](https://github.com/mmistakes/minimal-mistakes/pull/5003)
- Add provider and comments info to `single.html` layout for non-production. (#5068)
- Tweak contrast skin $primary-color to adhere to WCAG guidelines. (#5126)
- Update social share buttons to reflect Twitter rebranding to X (#5210)

### Bug Fixes
- Replace a redirected link to MadeMistakes in footer. [#4882](https://github.com/mmistakes/minimal-mistakes/pull/4882)
- Fix wrong float direction for `feature_row` with `type="right"`. [#4061](https://github.com/mmistakes/minimal-mistakes/issues/4061)
- Fix reset stylesheet overruling `$doc-font-size`. [#4983](https://github.com/mmistakes/minimal-mistakes/issues/4983)
- Fix JavaScript null error on home and splash layouts. [#4938](https://github.com/mmistakes/minimal-mistakes/issues/4938), [#4939](https://github.com/mmistakes/minimal-mistakes/pull/4939)
- Fix bad `<figure>` HTML if "alt" contains quotes.
- Fix extra newline generated in `_includes/post_pagination.html`.
- Hide hidden links & remove the overlay when one is clicked. [#5042](https://github.com/mmistakes/minimal-mistakes/pull/5042)
- Fix typo in "Configuration" (#5106)
- bundle exec jekyll serve will fail if more than once (#5193)

## [4.26.2](https://github.com/mmistakes/minimal-mistakes/releases/tag/4.26.2)

### Enhancements
- Add Czech localization. [#4866](https://github.com/mmistakes/minimal-mistakes/pull/4866)
- Allow overriding HTML `lang` attribute on a per-page basis. [#4862](https://github.com/mmistakes/minimal-mistakes/pull/4862)

### Bug Fixes
- Figure helper breaks when using code markup in caption with `popup=true`. [#4841](https://github.com/mmistakes/minimal-mistakes/issues/4841)

## [4.26.1](https://github.com/mmistakes/minimal-mistakes/releases/tag/4.26.1)

### Bug Fixes
- Disable copy button on invalid syntax highlighting blocks to avoid positioning issues.
- Fix typo for `fa-dribbble` in `_utilities.scss`.
- Restrict "auto scroll sticky ToC to content" feature to Chromium browsers for now. [#4826](https://github.com/mmistakes/minimal-mistakes/issues/4826)

### Documentation & Maintenance
- Rewrite social icons SCSS with a loop.

### Enhancements
- Change the icon of a copy button into a tick for 1.5 seconds on successful copy.

## [4.26.0](https://github.com/mmistakes/minimal-mistakes/releases/tag/4.26.0)

### Bug Fixes
- Fix an unclosed `<p>` tag in `page__hero.html`, near `page.header.actions`.
- Remove overlay and revert X to hamburger icon when popup disappears. [#3958](https://github.com/mmistakes/minimal-mistakes/pull/3958)
- Fix SEO title when it contains a vertical bar. [#3094](https://github.com/mmistakes/minimal-mistakes/pull/3094) [#3113](https://github.com/mmistakes/minimal-mistakes/pull/3113)
- Remove "sticky sidebar" JS as it's now completely based on CSS media queries. [#4245](https://github.com/mmistakes/minimal-mistakes/issues/4245) [#4645](https://github.com/mmistakes/minimal-mistakes/pull/4645)

### Enhancements
- Add support for [Jekyll Paginate V2](https://github.com/sverrirs/jekyll-paginate-v2) 🎉 [#2636](https://github.com/mmistakes/minimal-mistakes/pull/2636)
- Add "copy to clipboard" button for code blocks 🎉 [#2812
