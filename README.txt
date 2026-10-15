CAPTIONX AI STUDIO — MVP
========================

Included:
- Responsive app UI for laptop and Android browsers
- Installable PWA structure (manifest + service worker)
- Local video preview
- Caption styling presets, font/color/size/shadow controls
- Manual caption lines and SRT export
- Text-to-video prompt builder (up to 60-second target)
- External links to video tools

Important honest limitations:
- This MVP does NOT automatically transcribe uploaded video/audio.
- It does NOT automatically convert every language into Roman Hinglish.
- It does NOT generate videos itself; the prompt builder prepares prompts for external services.
- It does NOT burn captions into a video or export a rendered MP4.
- Free services may impose credits, queues, watermarks, region restrictions, or duration limits.

Install / publish:
1. Extract the ZIP.
2. Upload the contents of this folder to a static host such as Netlify (drag the folder or deploy the ZIP according to the host's current workflow).
3. Open the HTTPS site in Chrome.
4. On Android: Chrome menu (⋮) > Install app or Add to Home screen.
5. On laptop: use the install icon in Chrome's address bar or menu > Install CaptionX AI Studio.

PWA install requires HTTPS hosting or localhost. Opening index.html directly from a file manager will not provide full PWA installation/offline behavior.
