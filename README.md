# Amourly Events — Website

Source for amourlyevents.com, hosted on GitHub Pages.

## Structure
- `index.html`, `about.html`, `our-work.html`, `services-packages.html`, `contact.html` — the five pages of the site
- `images/` — all photography, referenced by plain filename (swap a file to change a photo, keeping the same filename)
- `fonts/` — Molen Surplus, used for the brand headings and the "a." watermark
- `CNAME` — tells GitHub Pages to serve this repo at amourlyevents.com

### Important: delete two old files
`services.html` and `packages.html` have been merged into one new page,
`services-packages.html`. When you push this update, delete the old
`services.html` and `packages.html` files from the repo so they don't
sit around as orphaned, unlinked pages.

### New images to add
Two new photos were added to the Our Work gallery. Add these two files to
your `images/` folder (included in this delivery):
- `wedding-garden-ceremony.jpg`
- `wedding-rooftop-moment.jpg`

## Contact form
The form on the Contact page posts to Formspree. Before this form will actually deliver
submissions, replace `YOUR_FORM_ID` in the form's `action` attribute (search for it in
`contact.html`) with your real Formspree form ID, after creating a form at formspree.io
connected to hello@amourlyevents.com. This has not been done yet; the form will not
deliver submissions until you complete this step.

## Pricing
All package pricing currently reads "Inquire for pricing" rather than showing dollar
amounts publicly. If you'd like real prices shown on the site, let your developer know
and they can be added to the tier cards on `services-packages.html`.

## Making changes
Edit any page's HTML directly, or swap files in `images/`, then commit and push —
GitHub Pages redeploys automatically within a minute or two.
