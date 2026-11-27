# Wedding invitation website

Open `index.html` in any current browser to preview the invitation.

## Personalise it

At the bottom of `index.html`, update the `WEDDING` object with the couple's names, date, time, venue, Google Maps link, and a real ISO date/time for the live countdown. The nearby comments show the exact format.

Place the supplied photos and music in `assets/` using the filenames listed in `assets/ADD-YOUR-ASSETS-HERE.txt`. The design will switch from its polished placeholders to the real media automatically.

## Share on WhatsApp

After publishing to a public HTTPS domain, create a 1200 × 630 JPG named `assets/social-preview.jpg`, then replace `https://your-domain.example` in the Open Graph meta tag at the top of `index.html` with the site’s actual public domain. WhatsApp will use those tags for a rich sharing preview.

For a fresh preview after changing those tags, use the Meta Sharing Debugger to refresh the public URL.
