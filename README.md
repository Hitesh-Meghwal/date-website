# A little something for Sariya

A mobile-first date invitation with hand-drawn details, real café photographs, an animated envelope reveal, background piano, and a WhatsApp response link.

## Files

- `index.html` contains the page, styles, animations, and JavaScript.
- `images/` contains the photographs used by the page.

There are no dependencies and no build step.

## Preview locally

Open `index.html` in your browser, or run this command from the project folder:

```sh
python3 -m http.server 8000
```

Then visit http://localhost:8000. Music begins after a tap and can be muted.

## Upload to GitHub

Create an empty GitHub repository, then run from this folder:

```sh
git add .
git commit -m "Add Sariya invitation website"
git remote add origin YOUR_REPOSITORY_URL
git push -u origin main
```

Replace `YOUR_REPOSITORY_URL` with your repository URL.

## Publish with GitHub Pages

In the repository settings, open Pages. Select **Deploy from a branch**, choose **main**, and choose **/(root)**. Save. GitHub displays the published URL when deployment finishes.

The same folder also works with static hosting services. Publish the root folder with no build command. Keep `images/` next to `index.html`.

## Personalize

Edit the wording and café cards in `index.html`. The WhatsApp recipient and message are in `updateWhatsApp()` and `whatsappMessage()`. The recipient phone number will be visible in the published source. The piano melody is generated in the browser; it needs no audio file.

## Photo sources

Coffee and cheesecake photographs: Unsplash. Café photographs: the official websites of Subko, Veronica’s, and Not Far.
