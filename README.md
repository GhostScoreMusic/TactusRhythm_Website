# Tactus — Website

Marketing site for **Tactus**, the rhythmic-mapping metronome for iOS.

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

All pages are static HTML — no build step. Open `index.html` in a browser to preview locally.

## Deploy (GitHub Pages)

1. Push this repo to GitHub.
2. **Settings → Pages → Build and deployment → Source: Deploy from a branch.**
3. Branch: `main`, folder: `/ (root)`. Save.
4. The site publishes at `https://<user>.github.io/<repo>/`.

## Before launch — TODO

- **Contact email:** `privacy.html` contains two `[INSERT CONTACT EMAIL]` placeholders. Replace them with the real address.
- **Signup form:** the launch-notify form on `index.html` posts to Formspree (`formspree.io/f/xbderwrg`). Confirm that endpoint is yours, or swap it.
- **Walkthrough video:** `assets/video/walkthrough.mp4` is the current cut — replace if you re-record.
