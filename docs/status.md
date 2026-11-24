# Status

Changelog for this site, newest first.

## 2026-11-24: Template version 4 (branch `template-v4`)

- Upgraded to Vanilla Gorilla template version 4: blog posts can set `image:` and `badge:` in front matter. The blog index and the recent posts list show them.
- Replaced `build.js` with the template copy, added the "Post image and badge" CSS block, set `templateVersion` to 4.
- Added `test/post-image.test.js` and updated `test/build-site.js` from the template.
- Changed the gallery tests in `test/template.test.js` to use `test-gallery`, because the `earthy-lightshow` demo gallery was deleted.
- Docs: README, `docs/THEMING.md`, and `docs/UPGRADE-v3.md` and `docs/UPGRADE-v4.md` copied from the template.
