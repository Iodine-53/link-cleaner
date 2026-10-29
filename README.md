# Link Cleaner

Paste a link, strip the tracking codes from it, copy the clean link, and share it to your apps.

Live demo: https://link-cleaner.vercel.app

## What it does

- Removes tracking parameters from a pasted link, including X's `s=`, `t=` and `si=`, plus `utm_*`, `fbclid`, `gclid` and other click IDs.
- Keeps the parts a page needs, like a YouTube video ID and timestamp.
- Shows exactly what was removed and why.
- Copy clean link button at the top of the result, plus share buttons for X, WhatsApp, Telegram, Facebook, LinkedIn, Reddit, Bluesky, Threads, Pinterest, email and SMS, with an optional note.

Cleaning happens entirely in the browser. Nothing you paste is sent anywhere.

## Run it

Open `index.html` in a browser, or deploy this folder as a static site. No build step and no server needed.
