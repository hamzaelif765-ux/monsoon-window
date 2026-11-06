# Monsoon Window

A calm, no-pressure browser game. You are looking through a foggy window while light rain falls outside. Wipe the fog, guide raindrops together, and water the plants on the sill. There is no score, timer or fail state. Everything (graphics and sound) is generated in the browser, so it works offline.

## Controls
- **Swipe / drag** on empty glass: wipe the fog.
- **Drag a raindrop**: move it; release to let it slide on. Two drops that touch merge and play a pentatonic note.
- **Guide drops to the bottom** above a pot: the plant is watered and grows (sprout, small, growing, full bloom).
- **Breathe** (hold): puffs fresh fog onto the glass.
- **Draw**: swipe to doodle in the fog, tap to stamp a heart. Doodles fade as the fog regrows.
- **Settings**: scene, rain intensity, volumes, fog regrow, merge sound, sleep timer, haptics, reduce motion, reset garden, save snapshot (PNG).

## Features
3 scenes (Sleepy city, Mountain dusk, Quiet village), parallax rain, lightning with distant thunder, refracting raindrops, 4 procedural plants saved in localStorage, procedural rain ASMR plus lo-fi music with reverb, adaptive quality, wake lock, mobile-first touch input.

## Deploy on GitHub Pages (works from a phone browser)
1. Sign in at github.com and tap **+** then **New repository**. Name it (for example `monsoon-window`), set it to **Public**, and create it.
2. Tap **Add file** then **Upload files** (on mobile: **creating a new file** also works). Choose `index.html` and, optionally, `README.md`. Tap **Commit changes**.
3. Open the repo's **Settings**, then **Pages** (in the left menu; on mobile scroll down to find it).
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**. Choose branch **main** and folder **/ (root)**, then tap **Save**.
5. Wait one to two minutes and refresh. Your game lives at:
   `https://<username>.github.io/<repo-name>/`

## Future ideas
1. Snow mode and seasons (autumn leaves, spring petals).
2. A day/night cycle that follows the real clock.
3. More plants (bonsai, cactus, sunflower) and a larger shelf.
4. New scenes: seaside lighthouse, train carriage, rooftop garden.
5. Shareable "garden cards" and a gentle journal of past blooms.
