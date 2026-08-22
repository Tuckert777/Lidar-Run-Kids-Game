# Drone Flight

A no-fail flying game for kids. Single HTML file, no dependencies, no
build step, no network calls.

Live: `https://YOUR-USERNAME.github.io/drone-flight/`

## Play

Hold anywhere to fly up, let go to come down. Collect stars. Every ten
gets a cheer. There is no timer, no lives and no game over.

## Safe by construction

There is no collision code in the file. Trees, clouds and planes are
scenery the drone passes straight through. Soft walls at both ends: a
400 ft ceiling above and a treetop floor below, so the drone can never
crash or leave the screen. Stars only spawn inside that band, so every
one is reachable.

The home button, top left, returns to the start screen at any time.

## Appearance

Six beam colours. Picking one tints the whole airframe to match.

## Files

    index.html       the whole game
    manifest.json    PWA metadata for Add to Home Screen
    icons/           app icons
