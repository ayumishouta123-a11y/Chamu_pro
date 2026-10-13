# Disney / USJ Accessibility Pages — axe-core integration

Six HTML pages have an on-demand accessibility scan button powered by **axe-core 4.10.3**. The checker runs when the visitor presses the button and displays detected violations and items needing manual review.

## How to use
1. Open a page in a browser with an internet connection (axe-core is loaded from cdnjs).
2. Press the “Check accessibility” button (wording varies by language).
3. Review each result and update the HTML/CSS; run the scan again.

## OSS used
- **axe-core** — https://github.com/dequelabs/axe-core
- Version: 4.10.3 (loaded from cdnjs CDN)
- License: Mozilla Public License 2.0 (MPL-2.0)
- CDN URL: https://cdnjs.cloudflare.com/ajax/libs/axe-core/4.10.3/axe.min.js

## Notes
- This adds axe-core to the pages via a CDN script; it does not bundle a local copy or use npm. Internet access is needed for the scanner to load.
- Automated scans do not identify every accessibility issue. Keyboard, screen-reader, zoom, contrast, and real-user checks are still important.
- Please verify scan findings manually before making changes.
