# Bungee Jumping VR

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

An immersive WebXR bungee jumping simulation built with A-Frame, featuring physics-based motion and interactive controls.

## Demo

Experience it live in your VR browser: **https://code4fukui.github.io/bungee-jumping/**

## Features

- **Physics-Based Motion:** Simulates the jump using gravity, spring force (for the bungee cord), and air resistance.
- **Immersive First-Person View:** The perspective realistically simulates the fall and rebound sequence.
- **Interactive Skybox:** Change the 360° background environment using the VR controllers.
- **Countdown Timer:** A 3-second countdown prepares you before each jump.

## Requirements

- A VR headset with controllers (e.g., Oculus Quest/Rift).
- A WebXR-compatible browser.

## How to Experience

1.  Open the [Demo URL](https://code4fukui.github.io/bungee-jumping/) in your VR headset's browser.
2.  After the initial 3-second countdown, the simulation will start automatically.
3.  Use your controllers to interact with the scene.

### Controls (Oculus Touch)

-   **Reset Jump:** Press the **trigger** or **grip** button on either controller.
-   **Random Sky:** Press the **B button** (right controller) to load a random 360° photo from the dataset.
-   **Default Sky:** Press the **A button** (right controller) to switch to the default background.

## Technology & Data

-   **Framework:** Built with [A-Frame](https://aframe.io/).
-   **Skybox Images:** Random background images are sourced from the [vr-fukui.csv](https://code4fukui.github.io/vr-fukui/vr-fukui.csv) dataset.

## License

MIT License