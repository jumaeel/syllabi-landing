# Syllabi — Landing Page

Marketing landing page for **Syllabi**, a study companion app for Maldivian students
(O Level & A Level Islam and Dhivehi). Imported from a Claude Design project and
hosted on GitHub Pages.

## Structure

```
index.html              Landing page (root)
store/store.html        Merch / store page
assets/
  logo/                 Logo + app icon
  illustrations/        Section illustrations
  screenshots/          App screen mockups (light / dark)
  products/             Store product art (SVG)
```

It is a static site — no build step. Open `index.html` directly or serve the folder:

```
python3 -m http.server
```

## Notes

- `assets/screenshots/app-screen-light.png` and `app-screen-dark.png` are on-brand
  placeholder mockups. The original high-resolution screenshots exceeded the design
  import tool's per-file size limit, so swap these for the real exports when available.
- Footer links to careers / contact / redeem / legal pages point to `#` — those
  pages are not part of this landing-only build.
