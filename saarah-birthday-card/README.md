# Saarah's Royal 17th Birthday Card ❤️👑

An interactive birthday card made from a single `index.html`, with no build step, no backend and no paid APIs.

**The sequence:** cover → wax-sealed envelope → 17 love letters (one per page) → cake to cut → celebration → special question → final love message → replay.

## Add Sarah's photos
1. Put the photos in the `photos/` folder using the names in `photos/README.txt` (`cover.jpg`, `message-01.jpg` … `message-17.jpg`, `final.jpg`, and so on).
2. That's it. Any missing photo shows a royal placeholder. Tap a photo to see it larger.
3. To use a different file name or a `.png`, edit the one line for it in the `const photos = { … }` block near the bottom of `index.html`.

## Change the messages
The 17 messages are listed in the `const messages = [ … ]` block in `index.html`. Each one has a `title` and a `text`. A blank line in `text` starts a new paragraph.

## Optional music
Put `music/birthday-song.mp3` in the `music/` folder. It never plays automatically; Sarah taps the **MUSIC** button.

## Open it on a phone
- **Easiest:** host the folder for free with GitHub Pages (repo Settings → Pages), Netlify Drop (drag the folder onto app.netlify.com/drop), or Vercel, then send Sarah the link.
- **Offline:** copy the whole folder to the phone and open `index.html` in Chrome or Files. Keep `index.html` and `photos/` together.
