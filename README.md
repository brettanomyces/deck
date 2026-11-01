# Deck concept

[Open the interactive 3D demo](https://brettanomyces.github.io/deck/)

A rear-deck concept with right-hand stairs, open railings, an illustrative stair-support frame, folding doors and dining furniture. Rotate the model, switch views or hide the deck to inspect the supports.

## Files

- `index.html`: the self-contained viewer and editable source. Opens offline in a browser.
- `southernhay-deck-concept.glb`: static 3D export, in metres with Y up.
- `model-notes.txt`: measurements, assumptions and limitations.

This is a layout visualisation, not an engineered construction design. Member sizes, foundations, connections and clearances require verification.

## Updating

Make changes in this repository. If geometry changes, regenerate the GLB from the viewer's `window.exportDeckGLB()` function in the default view state, with the deck visible, doors closed, two chairs, office hidden and patio at lawn level.

GitHub Pages publishes the root of `main`. Pushing updates to `main` updates the demo after deployment. `.nojekyll` allows the HTML to be served directly.

The Dropbox deck folder holds the original photographs and a text link to the live demo; exported copies are maintained here.
