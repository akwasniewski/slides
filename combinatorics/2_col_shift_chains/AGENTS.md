# Repository instructions

- Never rebuild or compile LaTeX.

## Slide style

- Keep text minimal; show proof steps primarily with coloured vertex dots, edge rows, and switches.
- Reveal proof steps progressively; diagrams may change between overlays when useful.
- Keep diagrams fixed in position and size across overlays. Reserve the full drawing area, including labels, annotations, and any rows revealed later, so images do not flicker or jump between slides.
- Keep successive argument steps visible as they build, using cumulative `itemize` bullets when presenting a multi-step proof.
- Title proof frames with the relevant claim label and a short description of what the frame establishes.
- At the top of each proof frame, show the full statements of the earlier claims used in that argument (such as Y2 and X2), and keep them visible across overlays. Put the proof steps below them.
- After a claim X1--X3, Y1--Y6, or Z1--Z4 first appears, show its full statement in the same top-right reminder box whenever a later frame uses it. Keep every reminder visible on all overlays of that frame, including recap and concluding frames.
- On non-recap proof frames, put the claim being established in a `lemma` environment titled `Claim`, above its separate `proof` environment. Keep recap reminders in their top-right outline boxes.
