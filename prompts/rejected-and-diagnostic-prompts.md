# Rejected and diagnostic prompt variants

## Rejected exterior escape wording

“The protagonist bursts from the entrance and struggles away from the building while the camera remains locked off; he becomes smaller and disappears.”

### Problem

This combines incompatible screen directions. In a locked-off shot, moving away from the building toward the camera makes the protagonist larger, while becoming smaller implies movement deeper into the background. Flux.3 often resolves this by moving the man toward the door, changing the camera, or deforming the building.

## Rejected officials movement wording

“The officials rise and move toward the protagonist, then go through the tiny door.”

### Problem

The direction is ambiguous and makes the men approach the protagonist or turn to face him. The tiny door may also become a normal-sized doorway.

## Rejected alarm wording

“The light flashes, the man escapes, and the door makes a loud metallic sound.”

### Problem

The timing is underspecified. Flux.3 may flash the light continuously, close the door too early, omit the silence, or generate multiple impacts.

## Rejected lighting wording

“A warning light flickers during the escape.”

### Problem

This can create lightning-like exposure changes across the entire image. The corrected version specifies one saturated red lamp, discrete flashes tied to countdown numbers, and otherwise stable monochrome exposure.

## Corrective principles

- State the officials’ facing direction in every action sentence.
- Give their route and destination explicitly: straight to the far-right wall, approximately 20 metres away.
- Specify one-at-a-time entry through the exact 20 cm door.
- Keep the protagonist seated until the countdown starts.
- Give the countdown, door closure, two-second silence and single `KLONK` explicit time windows.
- Use a locked camera and forbid teleportation, morphing, scale changes, lightning and exposure pulsing.
