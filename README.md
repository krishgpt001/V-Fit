# VR Fit Companion

A self-contained A-Frame WebXR workout companion designed for Meta Quest 3 and desktop browsers.

## Run locally

Because WebXR requires a secure context, use HTTPS or localhost. For example:

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080` in a compatible browser.

## Deploy to Vercel

1. Create a GitHub repository.
2. Put `index.html` and this README in the repository root.
3. Import the repository into Vercel.
4. Framework preset: **Other**.
5. Build command: leave empty.
6. Output directory: `.`
7. Deploy.

Vercel will serve `index.html` as the site root. WebXR support depends on the browser/device and HTTPS.

## Important limitation

The application provides a front-facing coaching overlay and a virtual gym. It does not claim that a normal web page can force Meta Quest camera passthrough. Actual passthrough depends on browser/device WebXR support and permissions.
