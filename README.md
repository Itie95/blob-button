# Get in Touch blob button

A hover prototype for a "Get in touch" button. On hover, the arrow circle pulls out of the pill like a liquid blob. A soft membrane stretches between them and pinches off, and the pill shrinks and ripples. Once the circle settles, the arrow swings down into the envelope's flap and the envelope outline draws around it.

Open `index.html` in a browser. There are no dependencies or build steps.

- **Slow motion (4×)** plays the animation at quarter speed.
- **Hold open** freezes the open state.
- Touch screens: tap the button to toggle it.

## Tuning

All values are in the script at the bottom of `index.html`.

| Constant | What it controls |
|---|---|
| `TRAVEL` (and `--travel` in CSS) | How far the circle moves out |
| `SPREAD` | Gap at which the membrane breaks |
| `NECK` | Thinnest the membrane gets before it breaks |
| `spring(95, 11)` on `sBall` | Circle speed (lower first number = slower) |
| `sRipple.v -= 90` | Strength of the ripple when the membrane breaks |
| `spring(90, 16)` on `sMorph` | Speed of the arrow-to-envelope change |

Reference frames are in the Figma file: https://www.figma.com/design/sRlVGQRHZCWVLsVxFU9Z6Z/Untitled?node-id=0-1
