# PI // Infinite Series Lab

A polished, responsive browser UI that calculates π step by step using the Chudnovsky series.

## Run it
Open `index.html` in a modern browser, or enable GitHub Pages:
**Settings → Pages → Deploy from a branch → main → /(root)**

## Features
- Adjustable target precision: 15, 30, 50, 100, or 200 decimal places
- Adjustable delay between terms, so the calculation is visible rather than instant
- Live progress, elapsed time, term count, and copy-result button
- Vanilla HTML, CSS, and JavaScript; no build tools or external dependencies

## Formula note
The supplied constant `545140343` appears to be a typo. The standard Chudnovsky series uses `545140134`, which is used here so the result converges to π. The implementation uses fixed-point `BigInt` arithmetic with guard digits.
