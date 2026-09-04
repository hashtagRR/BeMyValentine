# BeMyValentine

A single-page animated Valentine's proposal, contained entirely in one `index.html` file (inline CSS and vanilla JavaScript, no build step, no dependencies).

Live demo: https://hashtagrr.github.io/BeMyValentine/

## What it does

On load, JavaScript builds an animated flower (stem grows, leaves appear, petals bloom one by one) and a background of floating flower emoji drifting across the page, then fades in a "Will you be my Valentine?" prompt with Yes/No buttons. The No button dodges to a random spot whenever the cursor (or a touch) gets near it. Clicking Yes fades out the flower and prompt and plays an "I Love You" text animation with three animated hearts.

## Running it

There's nothing to build or install — just open the file in a browser:

```bash
git clone https://github.com/hashtagRR/BeMyValentine.git
cd BeMyValentine
xdg-open index.html   # or open index.html / just double-click it
```

## Customizing

Everything lives in `index.html`:

- The prompt text is the `<h1>Will you be my Valentine?</h1>` line.
- The final message is spelled out letter-by-letter in the `handleYesButton()` function's `loveContainer.innerHTML`.
- The number of floating background flowers is the loop bound in `createFloatingFlowers()` (`for (let i = 0; i < 20; i++)`).

## License

GPL-3.0 — see [LICENSE](LICENSE).
