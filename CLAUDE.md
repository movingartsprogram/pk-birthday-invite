# PK birthday invite

"Another year, another invite": PK's birthday invitation card, 17 Nov 2026, sunset onwards.
Served by GitHub Pages from `main`. Public repo — no private guest details in it.

## Flow
1. Pink + fluorescent-green envelope (tap to open).
2. Scratch card reveals PK with the gramophone (`pk.jpg`), title "Another year, another invite".
3. The handmade diary as a spiral-bound notebook: uniform cream pages with punched holes
   (`img/p00.jpg`–`img/p18.jpg`, cover → back) turning on a CSS coil, 0.5 s page turns.
4. Fluorescent-green pages, pink handwriting: the message, then 17 Nov + PEOPLE logo (`people.jpg`),
   venue "Waadi Beach, Benaulim" (Google Maps link) under the logo,
   "With whole lotta love, PK", winking smiley that laughs with `laugh.m4a` / `laugh.mp3`,
   then a blinking pink buzzer "I'M COMING!" — buzz sound + vibration, opens WhatsApp with
   "Yess, Bruh, I am coming..." (+ guest name). `PK_WHATSAPP` in index.html holds PK's number.
5. Sound: scratching the photo makes a scratch noise (Web Audio). `music.mp3` — Elvis Lobo's guitar,
   the audio of `feni-trail-reel.mp4` from `feni-trail-edition-2` — comes in when the photo is fully
   scratched, plays through the diary and messages, ducks under the laugh, fades out at the buzzer.
   The buzzer page says "To confirm you're coming, press the buzzer!"; pressing it vibrates.

Diary heading: "This card was made with love by Karen". A dog-ear "flip fast" button in the
diary's bottom-right corner whizzes through to the last two pages; normal turns stay 0.5 s.
Image URLs carry `?v=N` for cache-busting — bump it when images change.

## Ground rules
- One page, no build step. Media are separate files, never inline base64.
- `og.jpg` is the link-preview thumbnail; og:image / og:url use the absolute Pages URL.
- Personal links: `?to=Name` puts the guest's name on the envelope (max 40 chars).
- PK's wording in the messages is his own — don't rewrite it.

## Still open
- `PK_WHATSAPP` is 919849690077 (PK's Feni Trail booking number) — change it in index.html if PK wants another.
