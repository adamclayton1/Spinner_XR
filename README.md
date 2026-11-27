# Spin Clash

A spinning-top battle game for the browser and Meta Quest (VR and mixed reality), built with Three.js and WebXR. Everything runs from a single `index.html` with no build step.

## Play

- **Browser / phone:** open the GitHub Pages site for this repo, choose your top, two special moves and an arena, then press **Play on screen**.
- **Meta Quest:** open the same link in the Quest Browser, then choose **Play in VR** or **Play in mixed reality**. You need the controllers; hand tracking isn't supported.

## Controls

| Action | Keyboard | Gamepad | Touch | Quest |
|---|---|---|---|---|
| Steer | WASD / arrows | Left stick | Left-side joystick | Left stick |
| Jump | Space | A | JUMP | A / X |
| Dash (slam in mid-air) | Shift | B / X | DASH | B / Y |
| Special moves 1 and 2 | 1 and 2 | LB / RB | Power buttons | Left and right triggers |
| Camera (chase, first-person, overview) | C, and Q/E to turn | Y, right stick | CAM | Right stick turns and resizes the arena; grip re-centres it |

## Features

- Three tops (Ember, Bastion, Gale), each built from tip, track, metal wheel, clear wheel and face bolt, ready for a future customisation screen.
- Three arenas: Crater, Skate Park and Sky City. Glass walls keep you in.
- Damage depends on where the hit lands: Stomp, Uppercut, Blindside, Smash or Clash. Only hits drain spin.
- Eight special moves: Inferno, Iron Wall, Vine Snare, Thunder Strike, Phantom, Meteor Slam, Frost Nova and Second Wind.
- Optional power-up drops, an embedded announcer voice, crowd audio, a stadium with crowd, a minimap and a first-person camera.

## Hosting

Enable **Settings → Pages → Deploy from a branch → `main` / root**. WebXR needs HTTPS, which GitHub Pages provides.
