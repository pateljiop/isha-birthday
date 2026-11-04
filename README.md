# Isha — A Little World of Happiness

A mobile-first birthday surprise website for Isha.

## Hosting
This is a static site and can be hosted directly with GitHub Pages.

1. Open repository **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch `main` and folder `/ (root)`.
4. Save. GitHub Pages will publish the site.

## Personal photos
The gallery currently contains four designed photo placeholders. Replace each placeholder inside the matching `<figure class="photo">` in `index.html` with an image tag, for example:

```html
<div class="photo-frame"><img src="assets/isha-01.jpg" alt="Isha smiling"></div>
```

Add selected photos to an `assets/` folder. Only use photos that Isha is comfortable having included.

## WhatsApp friendship response
The final friendship choices generate a pre-filled WhatsApp message to the configured number. Isha must review and press **Send** herself. The site does not send messages automatically or save answers in a database.

## Notes
- No backend, login, analytics, or tracking.
- Mobile-first and responsive.
- Reduced-motion preferences are respected.
- The site uses plain HTML, CSS, and JavaScript.
