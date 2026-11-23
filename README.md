# QR Digital Contact Card

A mobile-first landing page shared through a printed QR code. It gives visitors
two one-tap actions: visit the business Facebook page, or start a WhatsApp chat.

## Files
- `index.html` - the whole site (markup, styles and icons in one file, no build step)

## Update the Facebook or WhatsApp link (QR stays the same)
The QR code points at this site's URL only, never at Facebook or WhatsApp
directly. To change where the buttons go:
1. Open `index.html` in the repository (pencil icon on GitHub).
2. Find the Facebook anchor (`facebook.com/share/...`) or the WhatsApp anchor
   (`wa.me/201097872574`) and replace the `href` value.
3. Commit. GitHub Pages redeploys in about a minute; the printed QR code keeps
   working unchanged.

## Hosting
Deployed with GitHub Pages from the `main` branch root.
