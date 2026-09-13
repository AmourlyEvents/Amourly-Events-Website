# Amourly Events — Website

Source for amourlyevents.com, hosted on GitHub Pages.

## Structure
- `index.html`, `services.html`, `our-work.html`, `about.html`, `packages.html`, `contact.html` — the six pages of the site
- `images/` — all photography, referenced by plain filename (swap a file to change a photo, keeping the same filename)
- `fonts/` — Molen Surplus, used for the brand headings and the "a." watermark
- `CNAME` — tells GitHub Pages to serve this repo at amourlyevents.com

## Contact form
The form on the Contact page posts to Formspree. Before this form will actually deliver
submissions, replace `YOUR_FORM_ID` in the form's `action` attribute (search for it in
`contact.html`) with your real Formspree form ID, after creating a form at formspree.io
connected to hello@amourlyevents.com.

## Making changes
Edit any page's HTML directly, or swap files in `images/`, then commit and push —
GitHub Pages redeploys automatically within a minute or two.
