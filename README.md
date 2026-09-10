# Locully Company Profile — mobile

Portrait build of the company profile deck, for phones.

Same content, same design language and the same `deck-stage` engine as the
desktop deck. The differences are structural, not cosmetic:

- Canvas is **1080 × 2280** portrait rather than 1920 × 1080.
- Every multi-column layout stacks to a single column.
- The type scale is lifted roughly 2× against the canvas, because a
  1080-wide canvas renders at about 0.36× on a 390px handset — anything
  under ~28 design px stops being legible there.
- Image panels are capped so a stacked column still lands inside the slide.
- The packages slide is split across two, since three cards will not fit a
  portrait screen without shrinking the type past readable.

27 slides against the desktop deck's 26, for that reason.

Desktop version: https://sunnysakchira1.github.io/profile-deck/
