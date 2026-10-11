# Clickie Club: Tiny Pals 🎀

*little things. big serotonin.*

A mobile-first virtual pet website. Adopt a tiny pal, name it, feed it, play with it, put it down for a nap, and decorate its room. Progress saves in the browser, so your pal is waiting when you come back.

## Run it

It's one static file with no build step and no dependencies.

1. Open `index.html` in a browser, or
2. Run `npx serve .` in this folder and open the link it prints.

## What's inside

- `index.html` holds the HTML, CSS and JavaScript.
- Three pals: Mochi, Pudding and Boba, drawn as soft clay-style inline SVG.
- Optional realistic art: add `assets/pets/mochi.png`, `pudding.png` and `boba.png` (transparent PNGs) and they replace the drawn pals automatically.
- Full-screen cozy room with big Feed and Play buttons, three stat bars, and a snack tray.
- Optional real room photo: add `assets/room.jpg` and it replaces the drawn room.
- Get a pal to 100 happiness to unlock the next one, and swipe between pals with the arrows.
- Feed, cuddle, sparkle catch, nap, and a decorate shop paid for with coins.
- Progress saved with `localStorage`. Nothing leaves the device.
- Fonts: Fredoka and Nunito from Google Fonts, with system fallbacks.

## Brand colors

| Name | Hex |
| --- | --- |
| Clickie Pink | `#F8BBD5` |
| Butter Pop | `#FFE5A8` |
| Lilac Dream | `#DCCEFF` |
| Mint Sprout | `#C9EEDC` |
| Vanilla Cloud | `#FFF9F0` |
| Berry Ink | `#563B50` |

## Deploy

Drag the folder into Netlify, or connect the GitHub repo. No build command is needed and the publish directory is the repo root.
