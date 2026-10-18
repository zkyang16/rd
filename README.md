# Personal research website starter

A responsive, static personal website inspired by the quiet editorial style of Gabbard Lab. It uses plain HTML, CSS, and a small JavaScript file; it has no build step or paid hosting requirement.

## Preview

Open `index.html` in a browser. For GitHub Pages, copy these files to the root of your published repository (often `username.github.io`) or publish this folder from a branch/folder configured in the repository settings.

## Make it yours

Start in `index.html`:

1. Replace `Your Name`, `[Your field]`, `[role/title]`, and the bracketed copy with your own information.
2. Update the email address and social/profile links.
3. Rename or remove sections to fit your story. The three research cards can be expanded or deleted.
4. Replace the portrait in the hero: put your image at `assets/headshot.jpg` and change the image source from `assets/headshot-placeholder.svg` to `assets/headshot.jpg`. A portrait-oriented photo works best.
5. Add life photos to `gallery.html`. Put images in `assets/`, then change each `assets/gallery-placeholder.svg` source to its filename (for example, `assets/life-01.jpg`). Update the `alt` text and captions to describe the actual photos. You can duplicate or delete gallery `<figure>` blocks as needed.

Then adjust the palette and typography near the top of `styles.css`. The `--paper`, `--ink`, `--olive`, and `--gold` variables control most of the look. The fonts load from Google Fonts; if you prefer no external font request, remove the `@import` line and the fallback fonts will be used.

## Publishing on GitHub Pages

GitHub Pages can serve this site for free. Add the files to a GitHub repository and choose the publishing branch or folder in the repository's Pages settings. A custom domain is optional and may have a registration cost; the default `username.github.io` address does not require buying one.
