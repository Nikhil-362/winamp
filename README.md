# WavePilot

A mobile-friendly, browser-based music player inspired by classic desktop audio players.

## Project structure

```text
.
├── index.html       # Complete static app (styles and JavaScript are included)
├── vercel.json      # Static-site routing and security headers
├── .gitignore       # Local tooling files excluded from Git
└── README.md        # Setup, deployment, and usage notes
```

## Run locally

Open `index.html` in a modern browser, or serve this folder with any static web server. There are no package installs or build steps.

## Deploy to Vercel

1. Create a GitHub repository and upload these files to its root.
2. In Vercel, choose **Add New → Project** and import that repository.
3. Keep the framework preset as **Other**. Leave Build Command and Output Directory empty, then deploy.
4. Vercel serves `index.html` from the project root.

## Player notes

- Music files are selected from the user's device in the browser. The audio files themselves are not uploaded to this site.
- Browser storage (such as preferences and playlists) stays in that browser on that device; it is not synced between devices.
- Playback and file selection depend on browser support and user interaction. Test on the mobile browsers you plan to support.
- This is a web app, not an Android APK or Google Play release.
