# AR setup

1. Pick a long random topic, e.g. `lameck-ar-7f3k9q2xw81`.
2. In index.html set `RELAY.topic` to that string.
3. On your laptop, open laptop.html#lameck-ar-7f3k9q2xw81 in Chrome, click "Connect to phone" once.
   (That click is what lets it open pages on its own later.)
4. Host index.html on HTTPS (GitHub Pages, Netlify, or Cloudflare Pages). Camera needs HTTPS.
5. Print AR-QR-print-sheet.pdf. The QR codes encode ar:card, ar:lights and ar:coffee.
   Those strings must not change, or the printed codes stop working.

Buttons:
- Business card: "Show on laptop" shows the card full screen on the laptop; "Open site on laptop" opens your website in a new tab.
- Room control: light button makes the laptop glow; "Flash laptop" flashes the screen.
