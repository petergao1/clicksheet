# ClickSheet

A click-to-shoot aim trainer that graphs your reaction time for every target.

Pick how many targets (20, 30 or 50) and a target size, press **Start** (or Space), and click each target as it appears. The graph under the arena fills in as you go, with your previous run drawn as a faint line for comparison. Each target's bar splits into flick time (until your crosshair first lands on the target) and click time (from there to the shot, overshoots included), and both get their own average. It tracks your average, fastest click, accuracy and personal-best average for each setup.

**Match sens** turns the arena into a first-person view: the mouse is locked, the crosshair stays in the middle, and each raw mouse count turns the view 0.07° × the Valorant sensitivity you enter, with targets drawn through Valorant's 103° perspective at your monitor's scale, so reaching a target takes the same hand movement as in game (DPI comes through the raw counts, so there's nothing to enter for it). Esc releases the mouse and stops the run.

**Keys:** Space starts a run, R restarts, Esc stops.

## Run it

It's a single `index.html` with no build step. Open it in a browser, or serve the folder:

```bash
python -m http.server 8000
```

Personal bests and settings are saved in your browser's local storage.

## Credits

Inspired by [BallSheet](https://helloimxtal.github.io/ballsheet/) by dphdmn and [Reaction Tester](https://github.com/narendrajethi220/Reaction-Tester) by narendrajethi220. No code from either project is used.
