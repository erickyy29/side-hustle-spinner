# Side Hustle Spinner

A "random side hustle" slot reel for UGC and short-form video. It's one `index.html` file: open it in Chrome, film your screen, done.

- iOS-picker-style drum with speed-scaled motion blur
- Tick sound on every item and a punchy hit on landing, all generated with Web Audio
- Confetti and a glowing label when it lands
- Green screen mode for keying in CapCut
- **Settings for rigging the result**, so you don't have to spin 20 times to get the one you want

## Use it

Open `index.html` in Chrome. Press **F** for fullscreen and **Space** to spin.

## Settings: names and odds

Press **E**, or move the mouse and click the gear in the top-right. The gear hides itself after 2 seconds so it won't show up in your recording.

| Setting | What it does |
| --- | --- |
| **Name** | Rename any item, or add your own with **+ Add item** |
| **Odds %** | How likely each item is to win. The **Chance** column shows what it works out to |
| **◎** | Always land on this item: sets it to 100% and everything else to 0% |
| **Equal odds** | Back to a fair, fully random spin |
| **Label under the winner** | The text in the red pill (default `YOUR SIDE HUSTLE`) |
| **Reset to defaults** | Built-in list, equal odds |

Example: you want the video to land on **DOG TOY SELLING**. Add it, press its ◎, then Save. Every spin lands there until you change it back.

If the odds don't add up to 100%, they're scaled proportionally. With equal odds the spin never lands on the same item twice in a row. Settings are saved in your browser.

## Keys

| Key | Action |
| --- | --- |
| Space / click | Spin |
| 1–9 | Secretly force the *next* spin onto item #1–9 (one spin only, nothing shows on screen) |
| R | Reset |
| F | Fullscreen |
| G | Green screen (#00FF00) for keying |
| M | Sound on/off |
| E | Settings |

## Customize the defaults

The built-in list is the `ITEMS` array at the top of `index.html`, and the default label is `PILL_TEXT`. Spin timing (`SPIN_MS`, `MIN_ROWS`, `OVERSHOOT`) is at the top of the main script.
