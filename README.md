# biscuitbot

Prototype simulations for a physical air hockey table where the robot player is a
carriage driven by 4 cable spools (servo motors) and the puck is tracked by a camera.

- **`demo.html`** — phone-friendly game: you vs the cable robot (portrait, touch controls).
- **`index.html`** — engineering simulator: tuning sliders for puck physics, servo RPM / drum
  size, carriage limits, camera fps / latency / noise, plus live cable lengths, ΔL/Δt,
  tensions and peak motor requirements.

Both are single self-contained HTML files — open them in a browser, no build step.
