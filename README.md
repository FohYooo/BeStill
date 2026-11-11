# BE STILL

*a love story in oils*

A first-person horror game in one HTML file. All art and sound are generated in the browser. There are no assets.

## Play

Open `index.html` in Chrome or Edge. The game uses your microphone, so allow it when asked. Headphones are recommended.

Click things to look at them. The buttons at the edges, or the arrow keys, move you between rooms. **J** opens the journal, **M** mutes, **1–5** pick choices and **Space** continues. The title screen has a *Microphone & sound* menu where you can test your mic and change the sensitivity.

Progress saves automatically.

## For development

`?mute=1` silences the game. `?fast=1` shows text instantly. `?auto=1` auto-advances dialogue, choices and timed events. `window.BS` drives the game from the console:
`BS.start()`, `BS.spot(id)`, `BS.exit(dir)`, `BS.queue=[choice indexes]`, `BS.info()`.
