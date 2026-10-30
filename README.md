# saintpatrick

the site lives at **https://rydhaani.github.io/saintpatrick/** (once github pages is turned on in settings → pages).

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

## the countdown (nov 1–9)

`countdown.html` is the ten-candle countdown. from **nov 1** the locked site sends people there instead of the "come back later!" page. he blows one candle a day, each one opens that day's game, and candle 10 opens the cake on **nov 10**.

- **to change the words, his name or the messages:** open `countdown.html`, find the `EDIT HERE` block near the top of the script, change the text between the quotes, commit.
- **to try any day early:** add `#day-1` … `#day-10` to the address, e.g. `rydhaani.github.io/saintpatrick/countdown.html#day-3`. this pretends it's that date and never touches his real progress.
- his pixel buddy and game progress are saved in his own browser.

## other pages

- `index.html` — the landing page, letter, list and music player (one page, so the music keeps playing)
- `map.html` — lovetap, the globe game
- `countdown.html` — the ten-candle countdown and daily games
