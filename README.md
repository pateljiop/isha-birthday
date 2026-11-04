# For Isha — A Little World of Happiness

A mobile-first, responsive birthday surprise made with warm wishes.

## GitHub Pages deployment

1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch `main` and folder `/ (root)`.
4. Save and wait for GitHub Pages to finish publishing.

## Add Isha's photos

The gallery currently contains four elegant photo placeholders. Once you have the photos she is comfortable sharing on this page:

1. Create a folder named `assets` in the repository.
2. Add the selected images with these filenames:
   - `isha-01.jpg`
   - `isha-02.jpg`
   - `isha-03.jpg`
   - `isha-04.jpg`
3. In `index.html`, replace each matching `<div class="photo-frame"> ... </div>` placeholder with:

```html
<div class="photo-frame">
  <img src="assets/isha-01.jpg" alt="A happy memory" loading="lazy">
</div>
```

Use the corresponding filename for each photo. Portrait images around 4:5 work best. Only include photos she is comfortable having on the website.

## WhatsApp friendship response

The final friendship choices create a pre-filled WhatsApp message to the configured number. The visitor reviews the message and must press **Send** themselves. The website does not send messages automatically and does not save answers in a database.

## Privacy and implementation

- Static HTML, CSS and JavaScript — no backend or database.
- No login, analytics, or tracking.
- No answer is sent until the visitor chooses to send it in WhatsApp.
- Mobile-first layout, keyboard focus styles, and reduced-motion support.
- The website can be hosted on GitHub Pages.
