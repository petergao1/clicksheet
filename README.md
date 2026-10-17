# ClickSheet

A click-to-shoot aim trainer that graphs your reaction time for every target.

Pick how many targets (20, 30 or 50) and a target size, press **Start** (or Space), and click each target as it appears. The graph under the arena fills in as you go, with your previous run drawn as a faint line for comparison. It tracks your average, fastest click, accuracy and personal-best average for each setup.

**Match sens** locks the mouse during a run and moves an on-screen crosshair with raw mouse input, scaled to the Valorant sensitivity you enter, so a swipe turns the same share of the arena as it does of your in-game view (DPI comes through the raw counts, so there's nothing to enter for it). Esc releases the mouse and stops the run.

**Keys:** Space starts a run, R restarts, Esc stops.

## Run it

It's a single `index.html` with no build step. Open it in a browser, or serve the folder:

```bash
python -m http.server 8000
```

Personal bests and settings are saved in your browser's local storage.

## Credits

Inspired by [BallSheet](https://helloimxtal.github.io/ballsheet/) by dphdmn and [Reaction Tester](https://github.com/narendrajethi220/Reaction-Tester) by narendrajethi220. No code from either project is used.
