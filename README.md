# Aura Mobile Prototyping System

High-fidelity recreation of the three-screen **Mobile App Design Interface**.

## Live Preview (HTML)

**Open now:**  
https://uinpoland-ui.github.io/aura-mobile-prototyping/

*(If you see 404 — open repo **Settings → Pages → Source = Deploy from a branch → main / root**, save, wait ~60 seconds)*

Direct file: [index.html](https://github.com/uinpoland-ui/aura-mobile-prototyping/blob/main/index.html)

## React Native (Expo)

The React Native version is ready in the conversation artifacts (`aura-mobile-rn/`).  
To run locally:

```bash
cd aura-mobile-rn
npm install
npx expo start
```

Screens:
- **EventTimeline** — Floating Peach Card, timeline + avatars, upload zone
- **ImmersiveWorkshop** — full-bleed photo, live pulse, glass library card, action column
- **CourseDetails** — white top, **offset dark profile card** (right overflow), schedule list

## Design fidelity

- Tokens from original Aura system
- Complex multi-layer shadow on Peach Card
- Profile card intentionally overflows right edge
- no-scrollbar on schedule
- Original remote assets
- Unicorn Studio atmospheric background (HTML version)
