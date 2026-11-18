NO NAME ARENA — UPDATE 1.3.1 (VEX MODEL + ANIMATION)

FILES
- game.js: complete playable-demo script based on the latest available 1.3.0 patch, with VEX's visual model and skill animation updated.
- ash-blossom.png: Ash Blossom map background.
- vex-artist-reference.png: artist-provided VEX demon concept sheet, included as a reference asset (not loaded by the game).

WHAT CHANGED
- VEX visual redesign is based on the red demon / Malphas-like concept in the supplied artist sheet: red skin, curved horns, layered dark-and-bronze armor, trident on the back, and a floating infernal flame familiar.
- VEX's idle/walk pose animates the familiar and tail.
- J attack has a forward punch pose.
- K skill raises the familiar, expands its flame, and shows a fiery crescent during the rush.
- Existing VEX movement, hitboxes, damage values, and dash combo logic are preserved.
- Musashi, Katex, Ash Blossom, Soulbound free access, and Locke event-lock behavior from the 1.3.0 patch are retained.

INSTALL
1. Back up the current game.js.
2. Replace the existing game.js with this package's game.js.
3. Keep ash-blossom.png in the same folder as the page that loads game.js.
4. Keep the rest of your existing HTML/CSS files unchanged.
5. Run the website using your usual local server and open the demo.

VALIDATION
- JavaScript syntax checked with Node.js (node --check).
- The code update uses the existing canvas/vector-sprite renderer. It does not create a frame-by-frame sprite sheet from the concept art.
- Full website HTML/CSS were not included in the available source, so this is a game.js + asset update, not a replacement of the entire website project.
