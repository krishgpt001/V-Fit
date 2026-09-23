# VR Fit Companion — AR-only Coach

This build is optimized for Meta Quest immersive AR.

## Experience
- Real-world passthrough is the main view when immersive AR is supported.
- The 3D coach stays on the front-left.
- Only the workout control surface remains visible on the right.
- The session-complete overlay is never shown during AR; ending a session simply returns to the compact controls.
- No VR/AR chooser is exposed. The app requests immersive AR from the workout start action.
- Quest laser pointer + trigger operate the AR controls.

## Deploy
Upload `index.html`, `README.md`, and `vercel.json` to a GitHub repository and import it into Vercel. No build command is required.

## Important
Immersive AR/passthrough availability is controlled by the browser/device WebXR implementation. The app does not fake a camera feed. It requests `immersive-ar` when available.
