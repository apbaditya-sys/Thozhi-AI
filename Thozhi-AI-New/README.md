# Thozhi AI — Hackarena prototype

A new responsive React + Vite website with first-visit native-script language selection, eight language interface dictionaries (English fallback for untranslated text), a browser-based voice assistant, scheme explorer, illustrative eligibility wizard, document checklist, accessibility settings and a local dashboard.

## Run in VS Code (Windows)
1. Extract the ZIP and open the **Thozhi-AI-New** folder in VS Code.
2. Install Node.js 20.19+ or 22.12+ if necessary.
3. Open Terminal → New Terminal and run:

```bash
npm install
npm run dev
```

4. Open the local URL shown in the terminal (normally http://localhost:5173).

To build: `npm run build`. To preview the build: `npm run preview`.

## Important demonstration notes
- Choose a language when the site first opens. The selection persists; click the language button in the header to change it.
- The microphone button appears at the bottom right on all pages. Chrome or Edge on localhost/HTTPS generally offers the best Web Speech API support. Allow microphone permission. Available recognition languages and text-to-speech voices vary by browser and operating system; the assistant provides a text-command fallback. Some translations fall back to English, especially example scheme data.
- The scheme catalogue is **demonstration data**, not a verified list of current government benefits. Buttons link to genuine official government starting-point domains, not necessarily scheme-specific application pages. The eligibility questionnaire is illustrative and always directs users to confirm official requirements. The app does not submit applications.
- Preferences, saved schemes and checklist completion are stored only in your browser's localStorage. No identity documents or ID numbers are collected. No API key is required.
- Fonts are loaded from Google Fonts when internet access is available; system fonts are used otherwise.
