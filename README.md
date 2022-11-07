# Cross Platform Browser Extension template repository

React + TailwindCSS bundled with Vite.

# Installation
```
npm i
```

# Building the Extension:

## Firefox
`npm run build` builds the extension by default for Firefox.

The generated files are in `dist/`.

To load the extension in Firefox go to `about:debugging#/runtime/this-firefox` or

Firefox > Preferences > Extensions & Themes > Debug Add-ons > Load Temporary Add-on...

Here locate the `dist/` directory and open `manifest.json`

## Chrome
`npm run build:chrome` builds the extensions for Google Chrome.

The generated files are in `dist/`.
To load the extensions in Google Chrome go to `chrome://extensions/` and click `Load unpacked`. Locate the dist directory and select `manifest.json`.

# Files:

 - content-script - UI files
 - background.ts - Background script/Service worker
 - index.html - popup UI

If you have any questions feel free to open an issue.