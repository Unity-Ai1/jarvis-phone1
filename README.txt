PROJECT JARVIS — PHONE BUILD 0.2

Files:
- index.html: mobile-first interface and demo commands
- manifest.json + icon.svg: installable web-app metadata
- sw.js: basic offline caching for a hosted secure site

IMPORTANT:
This is a prototype, not yet a full AI assistant. Replies are predefined demo responses.
Microphone speech recognition generally requires a supported browser and a secure HTTPS origin.
The web app does not continuously listen for “Hey JARVIS”; that needs a more advanced native Android implementation and background-microphone handling.

To make it accessible from your Samsung A05 home screen:
1. Host these files on a secure HTTPS static site (for example, a GitHub Pages site).
2. Open the HTTPS site in Chrome on your phone.
3. Use Chrome's menu and choose “Add to Home screen” or “Install app” if offered.
4. Grant microphone permission when asked, if you want voice input.

Never put private API keys in index.html. Connecting a real AI model requires a secure backend or a provider-supported secure approach.
