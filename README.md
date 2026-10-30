# cloudyv

**Cloudy Tone** is a single-page portfolio for a Mirzapur-based creator, model, and event anchor. `index.html` contains About, Services, Selected Work, Collaborations, Recent Moments, and Contact sections, with five service types: business promo reels, fashion campaigns, event anchoring, runway/editorial shoots, and lifestyle storytelling.

## Preview locally

Open `index.html` in a browser, or serve the project folder over HTTP:

```sh
python -m http.server 8000
```

Then visit <http://localhost:8000>.

## Navigate and browse

Service rows expand when clicked; opening another closes the currently open row. Desktop section links and a mobile burger menu provide navigation; choosing a mobile menu link closes the menu. Selected Work contains seven clickable projects. Open one to view its caption and position count in a lightbox, navigate with its previous/next buttons or the left/right arrow keys, and close with Escape, the close button, or the backdrop.

The collaboration and contact calls to action open `instagram.com/cloudy2208/` in a new tab. Booking instructions direct visitors to send a DM on Instagram; the page does not provide a website booking form. Confirm the account and public contact details before publishing.

## Photo slots and local assets

The Photos panel includes Edit Mode, Folder Guide, and Reset All Photos. There are 15 photo slots. In Edit Mode, click a slot to choose an `image/*` file; the selected image is stored in IndexedDB (`cloudyTonePortfolio`, object store `photos`) under that slot’s `data-slot` key and read back when the page loads. This is browser-local storage, not an upload to a portfolio server. No application file-size limit is imposed, though browser memory and storage quotas still apply.

For repository images, put the folder beside `index.html` and name files `images/{slot-key}.jpg`, `.jpeg`, `.png`, or `.webp`; each slot checks those extensions in that order. The Folder Guide lists the expected slot filenames. If no matching file exists, the page uses its configured `image.qwenlm.ai` fallback URL. Reset All Photos requires a second click within three seconds, deletes the saved slot entries, and reloads folder images or fallbacks.

## Resources and publishing

Cormorant Garamond and Manrope load from Fontsource’s CDN; fallback images come from `image.qwenlm.ai`. Both require network access. The page has no other external API integration identified in its source. No deployment configuration or build step is documented. Review the portfolio media and its rights before publishing, and test the lightbox, photo editing, reset confirmation, navigation, and external links in the published context.