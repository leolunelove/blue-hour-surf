# Blue Hour

A two-minute browser surfing game. Carve for speed, link moves, bank your line and earn your next board.

Play: http://surf.leolune.fun/

## Controls

- A / Left: drop and load the rail.
- D / Right: drive a bottom turn back up the face.
- S: snap near the lip (also automatic at the crest).
- Space: aerial from the upper face with speed. Release steering to line up a clean landing.
- B: bank a line on the lower face, or exit onto the shoulder.
- P / Escape: pause. R: restart. M: sound.
- Touch buttons and gamepad support are included.

## First Break

Six waves in a two-minute session, each with an open face, lip line and closing section. Different moves build the multiplier; repeats lose value. A wipeout loses the unbanked line. Progress and personal best save locally on this browser.

Earn any two beach stamps to unlock Reef: a quicker-turning mint board with stronger pumps, a higher top speed and less forgiving landings. Sunfish stays available as the stable starter.

The three stamps reward a varied three-move line, a snap-to-clean-air line, and 6,000 banked points against Pip's local score.

## Release

The verified static source is in blue-hour.zip, including tests and the bundled MIT-licensed Three.js. GitHub Actions extracts it, runs session and rider tests and publishes to GitHub Pages. To work locally, extract the archive and serve its directory with any static HTTP server. Run node tests/session.mjs and node tests/rider.mjs to verify the controller and rig.
