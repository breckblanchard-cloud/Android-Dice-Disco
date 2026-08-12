# Android Disco Dice

A 70s game-show themed sales training game for Android device sales. Roll the
dice, pitch to whatever comes up, then handle the objection the red die throws
at you.

Built as a single-page web app — no install, no app store. Open the link on a
phone and shake to roll.

## How to play

1. Shake the phone (or tap the buzzer) to roll.
2. Each die lands in turn: who the customer is, which feature to sell, which
   device, and optionally an attach goal.
3. Deliver the pitch out loud.
4. Shake again — the red objection die drops and the room goes to alarm.
5. Handle the objection and close, then shake for the next round.

## Setup

Everything is configurable in **Backstage** (the Settings button):

- **Number of dice** — 2, 3, or 4 per round, and which ones are in play
- **Face text** — all six faces of every die are editable, so the same game
  works for any product line or training focus
- **Motion sensor meter** — a diagnostic bar for checking shake detection

Settings save to the browser on the device you're using.

## Running it

Two files, in the same folder:

- `index.html` — the whole app; the applause and alarm sounds are embedded in it
- `theme.mp3` — the backing track

It needs to be served over https, not opened as a local file — the motion
sensor and the audio both require it. GitHub Pages works: Settings → Pages →
deploy from `main` / root.

Once it's live, open it in Chrome and use **Add to Home screen** so it launches
without the address bar.

## Credits

The Android robot is reproduced or modified from work created and shared by
Google and used according to terms described in the Creative Commons 3.0
Attribution License.

Android is a trademark of Google LLC. This is an unofficial training tool and
is not affiliated with or endorsed by Google.

Theme song: "Game Show" by Silent Partner. Applause sound effect from Pixabay.
