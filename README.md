# cloudyv

**Cloudy Tone** is a creator and model portfolio based in Mirzapur. The single-page site is in `index.html` and presents an introduction, services, selected work, collaboration information, and contact or booking sections.

## Preview locally

Open `index.html` in a browser, or serve the project folder over HTTP:

```sh
python -m http.server 8000
```

Then visit <http://localhost:8000>.

## Manual review checklist

Use these actions after editing the page; they are review steps, not verified results or performance measurements.

- [ ] Open `index.html` and review the introduction, services, selected work, collaboration information, and contact or booking sections.
- [ ] Try the contact and booking links. Check their destinations and confirm the displayed contact details before publishing.
- [ ] Inspect image, audio, video, font, stylesheet, and script references in `index.html`. Check each referenced local path against an existing file, especially when replacing portfolio media.
- [ ] The page references Cormorant Garamond and Manrope through Fontsource URLs. Confirm the font styles and weights actually used by the page before retaining or changing those external font requests; check that any other external script or font dependency is intentional.
- [ ] Check which portfolio assets are actually referenced. Remove an asset only after confirming it is unused, and consider whether large media is necessary before adding it. This checklist does not represent measured loading performance.
- [ ] Inspect the portfolio at narrow and wide viewport sizes. Check that sections, media, text, and contact links remain visible and usable.

## Accessibility review checklist

Use these as future review steps for the portfolio; they are not verified results or compliance claims:

- Navigate the page using a keyboard. Check that contact and booking links and any other interactive controls are reachable, operable, and show a visible focus indicator.
- Check that controls and links have meaningful names, and that section navigation, if present, communicates its purpose.
- Review text contrast across the introduction, services, selected work, and contact sections, including text placed over portfolio media.
- For portfolio images, check that informative work has useful text alternatives and that decorative imagery is not announced as meaningful content.
- If the page includes animated transitions or other motion, check that it responds to the user's reduced-motion preference.

## Personalizing the portfolio

Edit the introduction, service descriptions, selected-work text, and contact details in `index.html`, keeping information consistent across sections. The page references Cormorant Garamond and Manrope through Fontsource URLs; preserve those URLs unless intentionally changing the typography. No separate asset files are listed at the root. Inspect the page's actual image references before replacing portfolio media, keep each relative path pointed at the correct file, and recheck contact and booking links after changing them.