# Listen: simple mic-to-earbuds amplifier (PWA)

## Host it (needs HTTPS; the mic won't work from a local file)
Easiest options, all free:
- **Netlify Drop**: go to app.netlify.com/drop and drag this folder in.
- **GitHub Pages**: push the folder to a repo, enable Pages.
- **Cloudflare Pages / Vercel**: same idea.

## Install on the iPhone
1. Open the site in **Safari** (must be Safari, not Chrome).
2. Share button -> **Add to Home Screen**.
3. Open it from the home screen icon. Tap START, allow the microphone.

## Tips
- Wired earbuds = lowest delay. Bluetooth adds ~100-250 ms.
- If earbuds have their own mic, iOS may switch input to it. Test with yours.
- Keep the phone away from the earbuds to avoid squealing feedback.
- Volume is capped (6x gain) and run through a limiter. Start low.
- Settings > Control Center > Hearing also gives you Live Listen with AirPods.
