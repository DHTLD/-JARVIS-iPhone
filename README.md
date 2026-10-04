# JARVIS Mobile

Phone-first JARVIS PWA prototype. Host on HTTPS, open in iPhone Safari, then Share -> Add to Home Screen.

## Includes
- JARVIS mobile UI
- OpenRouter AI chat
- iPhone speech input where Safari/browser support permits
- slow/deep speech output
- local WhatsApp contacts
- WhatsApp chat links

## iOS limitation
A normal web app cannot silently control WhatsApp or place/send actions inside another iOS app. The user must complete the final WhatsApp action. For a production build, use a private backend and official integrations where available.

## Security
Do not use a production API key directly in a public frontend. Put OpenRouter behind your own authenticated backend for a real deployment.
