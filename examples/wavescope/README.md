# WaveScope — local Elliott Wave research prototype

This directory contains an independently authored, self-contained offline research front end, not a copy of the publisher's copyrighted articles, images, or branding.

## Open

Open `WaveScope_Offline.html` in a local browser, then navigate to `#/studio` for the 21-timeframe research interface. The file bundles HTML, CSS, JavaScript, selected historical article links, CSV OHLC import, BBMA calculations, six-pivot wave checks, Fibonacci projections, source metadata comparisons and replay evaluation.

## Boundaries

- Research/education only, no broker order execution, no financial advice, no live price or tick feed.
- User-selected historical source levels are not forecasts of future performance.
- English/partial Arabic RTL navigation; 14 selectively indexed historical source references.
- The exact original publisher page was not available for pixel-level DOM capture; visual parity is unverified.
- Local source/test bundle and MT4/MT5 export scripts are delivered separately as a ZIP. MQL source has not been compiled in MetaEditor.
- Repository `main` is intentionally untouched, with no deployment, CI dispatch, billing or PR merge.

## Verification

The local package passed 23 unit tests, 25 DOM smoke assertions, and 13 static security/packaging gates. Headless Chromium navigation was blocked by this environment, so real-browser layout QA is pending.

