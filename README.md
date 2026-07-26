# Baby Babble Safari Web App

A standalone iPhone-friendly Baby Babble translator.

## Features

- Light, Medium, and Full babble modes
- Copy button
- iPhone share sheet support
- Speak-aloud button
- Draft saved locally on the device
- Add to Home Screen support
- Offline support after the first successful load
- No login, Firebase, analytics, or server processing

## Quick test on a computer

Open `index.html` in a browser.

Most functions will work immediately. Service-worker offline support and full PWA installation
require the app to be served through HTTPS or localhost.

## Put it online

Upload the entire folder to any static web host, including:

- GitHub Pages
- Netlify
- Vercel
- Cloudflare Pages
- Your existing website

The host must preserve the folder structure.

## Add to an iPhone Home Screen

1. Open the hosted app in Safari.
2. Tap Share.
3. Tap Add to Home Screen.
4. Tap Add.

The app will then open without Safari's normal browser bars.

## Share into Messenger

1. Convert the text.
2. Tap Share.
3. Choose Messenger from the iPhone share sheet.

If Messenger is not shown, tap Copy and paste the text into Messenger.

## Privacy

All conversion happens in the browser on the device. No typed text is uploaded.
