# Tactus Website

Marketing site for **Tactus**, the rhythmic-mapping metronome for iOS, with Android coming soon.

## Structure

```
.
├─ index.html          Landing page
├─ manual.html         Full app manual
├─ privacy.html        Privacy policy
└─ assets/
   ├─ tactus-tokens.css Design tokens / shared styles
   ├─ images/           Screenshots + video poster
   └─ video/            Walkthrough video
```

All pages are static HTML, no build step. Open `index.html` in a browser to preview locally.

## Deploy (GitHub Pages)

1. Push this repo to GitHub.
2. **Settings → Pages → Build and deployment → Source: Deploy from a branch.**
3. Branch: `main`, folder: `/ (root)`. Save.
4. The site publishes at `https://<user>.github.io/<repo>/`.

## Notes

- **Walkthrough video:** `assets/video/walkthrough.mp4` is the current cut, replace if you re-record.
- **Android:** the site currently says Android is coming soon (hero trust line, FAQ, and `privacy.html`). Once Android actually ships, update those three spots, the App Store link and price block, and the `SoftwareApplication` structured data in `index.html` (currently `"operatingSystem": "iOS"` only).
