# Get in Touch Blob Button: Design Process

Oct 23, 2026 · Shikha

## The brief

I built a "Get in touch" button where, on hover, the arrow circle pulls out of the pill like a liquid blob and turns into an email icon. I started from five Figma frames: the resting pill, two stretching teardrops, the arrow sliding away from the mail icon, and the separated circle. I built it with Claude Code in 1.1 hours, spread across two days, through nine rounds of feedback.

## How it evolved

1. **First build.** A blur-based "goo" effect melted the pill and circle together, and timed transitions moved them. It worked but felt mechanical.
2. **Make it fluid.** Using a screen recording of liquid blobs as reference, I switched the motion to spring physics, so the circle overshoots and settles.
3. **Simplify to two shapes.** Helper shapes kept showing up as extras, so I cut them. That left the pill, the circle and a hand-drawn bridge that narrows as they part, while the pill loses volume and ripples.
4. **Tune the feel.** I slowed it down and had the arrow change into the mail icon. I tried a honey-like version and rolled it back, then made the bridge a thicker, softer membrane.
5. **Polish frame by frame.** I removed spikes and flickers, thickened the pinch point, and made the arrow swing down to become the envelope flap.

## What I learned

- **Starting in Figma gave me clarity.** Laying out the frames first helped me visualize the motion and build the vocabulary I needed to direct Claude. It also saved tokens.
- **Springs beat timed curves for liquid motion.** Overshoot and settle are what make it read as fluid.
- **Fewer shapes look cleaner.** Every helper shape I added, like droplets, a neck or a blur, showed up as something extra. Two shapes plus a drawn bridge looked right.
- **The icon should carry the story.** The arrow's 45° angle becomes the flap's angle, so the change from arrow to mail reads as one idea.
- **Check it frame by frame.** The spikes and flickers only showed up in single frames, so I reviewed rendered frames before shipping each fix.

## Tools and links

| What | Where |
| --- | --- |
| Code | [github.com/Itie95/blob-button](https://github.com/Itie95/blob-button) (private) |
| Build | Claude Code; HTML, SVG and JavaScript with no libraries |
