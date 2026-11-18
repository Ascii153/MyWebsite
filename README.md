# Khatib Mbwana - Portfolio

## Run it
Open `index.html`, or upload the whole folder to your hosting (cPanel public_html, Vercel, Netlify). Internet is needed for the GSAP library (CDN).

## Contact form (sends email to khatibsaid153@gmail.com)
Uses the free FormSubmit service, no server code needed. **One-time activation:** after you upload the site, send yourself one test message from the form. FormSubmit emails khatibsaid153@gmail.com an activation link (check Spam). Click it once; every message after that arrives in your inbox. If sending ever fails, the visitor sees your email as a fallback.
Change the address in `CFG.email` inside `index.html`.

## Where things are
- `assets/projects/` web-optimised project screenshots (used by the site). Originals stay in `assets/complite project/`.
- `assets/video/behind-the-code.mp4` + `poster.jpg` self-hosted video in the Technical Support section
- `assets/img/services/`, `assets/img/gallery/`, `assets/img/banner-world.jpg` service, gallery and banner images
- `assets/cv/Khatib-Said-Resume.pdf` the CV behind Download CV

## Edit content (inside the `<script>` of index.html)
- `PJ` projects: `[name, category, English text, tags, Swahili text, image, live URL, "soon"]`
- `CFG` email/WhatsApp, `LV` skill levels, `SV` services, `T.sw` Swahili text.

## Clean URLs (no .html)
Apache/cPanel: `.htaccess`. Vercel: `vercel.json`. Netlify: automatic.
