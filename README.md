# emword67

the site lives at **https://rydhaani.github.io/emword67/** (once github pages is turned on in settings → pages).

## changing the words and photos

everything you'd want to change is in two text files and one folder:

| what | where |
|---|---|
| the list (80 points, polaroids, captions) | `content/list.txt` |
| the letter, its heading, sign-off and the 4 photobooth photos | `content/letter.txt` |
| every picture | `photos/` |

each text file has short instructions at the top. lines starting with `#` are notes and never show on the site.

**to edit a text file:** open it here on github → click the pencil icon (top right of the file) → make changes → click **commit changes**. the site updates about a minute later.

**to add photos:** open the `photos` folder → **add file → upload files** → drag them in → **commit changes**. then type each file name into the text file where you want it. big photos are shrunk automatically and iphone `.heic` photos are turned into `.jpg`.

## adding your photos and words (no code needed)

| what | photos go in | then list them in |
|---|---|---|
| day 3 museum pictures (+ the emote for each) | `museum/` | `content/museum.txt` |
| day 3 daisies (one compliment per daisy) | – | `content/compliments.txt` |
| day 7 sliding puzzle photos (+ caption) | `puzzles/` | `content/puzzles.txt` |
| day 9 list polaroids | `photos/` | `content/list.txt` |

1. **upload photos:** open the folder on github → **add file → upload files** → drag them in → **commit changes**. iphone `.heic` photos are turned into `.jpg` and big photos shrunk automatically about a minute later (so write `.jpg` in the text file).
2. **list them:** open the text file → pencil icon → one line per photo, e.g. `beach.jpg | 🥹` → **commit changes**. each file has short instructions at the top; lines starting with `#` are notes.
3. the site picks the changes up about a minute later. check with `countdown.html#day-3` (or `#day-7`).

## the countdown (nov 1–9)

`countdown.html` is the ten-candle countdown. from **nov 1** the locked site sends people there instead of the "come back later!" page. he blows one candle a day, each one opens that day's game, and candle 10 opens the cake on **nov 10**.

- **to change his name:** open `countdown.html`, find the `EDIT HERE` block near the top of the script, change the text between the quotes, commit.
- **day 9 is the list:** candle 9 opens `index.html#list` a day early (the music player comes with it; the globe game stays hidden until nov 10). on nov 10 the cake leads straight to the globe game, then the letter.
- **to try any day early:** add `#day-1` … `#day-10` to the address, e.g. `rydhaani.github.io/emword67/countdown.html#day-3`. this pretends it's that date and never touches his real progress.
- his pixel buddy and game progress are saved in his own browser.

## other pages

- `index.html` — the landing page, letter, list and music player (one page, so the music keeps playing)
- `map.html` — lovetap, the globe game
- `countdown.html` — the ten-candle countdown and daily games
