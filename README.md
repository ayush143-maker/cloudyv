# cloudyv

**Cloudy Tone** is a creator and model portfolio based in Mirzapur. The single-page site is in `index.html` and presents an introduction, services, selected work, collaboration information, and contact or booking sections.

## Preview locally

Open `index.html` in a browser, or serve the project folder over HTTP:

```sh
python -m http.server 8000
```

Then visit <http://localhost:8000>. After editing the page, reload it and review the portfolio sections. Verify contact and booking links before publishing.

## Personalizing the portfolio

Edit the introduction, service descriptions, selected-work text, and contact details in `index.html`, keeping information consistent across sections. The page references Cormorant Garamond and Manrope through Fontsource URLs; preserve those URLs unless you are intentionally changing the typography. No separate asset files are listed at the root. **Review suggestion:** inspect the page's existing image references before replacing portfolio media, and keep each relative path pointed at the correct file. Recheck contact and booking links after changing them.