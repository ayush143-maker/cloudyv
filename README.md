# cloudyv

**Cloudy Tone** is a creator and model portfolio based in Mirzapur. The single-page site is in `index.html` and presents an introduction, services, selected work, collaboration information, and contact or booking sections.

## Preview locally

Open `index.html` in a browser, or serve the project folder over HTTP:

```sh
python -m http.server 8000
```

Then visit <http://localhost:8000>.

## Manual review checklist

Use these actions after editing the page; they are not verified results.

- Open the known entry page, `index.html`, and review the introduction, services, selected work, collaboration information, and contact or booking sections.
- Try the contact and booking links. Check their destinations and confirm the displayed contact details before publishing.
- Inspect image and media references in the page. Check each local path against the intended file, particularly when replacing portfolio media, and review any external resources in the browser.
- Inspect the portfolio at narrow and wide viewport sizes. Check that sections, media, text, and contact links remain visible and usable.

## Personalizing the portfolio

Edit the introduction, service descriptions, selected-work text, and contact details in `index.html`, keeping information consistent across sections. The page references Cormorant Garamond and Manrope through Fontsource URLs; preserve those URLs unless you are intentionally changing the typography. No separate asset files are listed at the root. Inspect the page's existing image references before replacing portfolio media, and keep each relative path pointed at the correct file. Recheck contact and booking links after changing them.