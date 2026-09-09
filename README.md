# PicTour V2

Photography-first PWA for Android and desktop.

## Fastest path to a working product

1. Upload the contents of this folder to the PicTour GitHub repository.
2. In Render, create a **Static Site** from that GitHub repository.
3. Build command: leave blank.
4. Publish directory: `.`
5. Deploy.
6. Open the Render URL on Android Chrome and choose **Install** / **Add to home screen**.

## V2 features

- Photography-first dark cinematic interface
- Location lookup
- Current-location button
- Shoot date
- Camera + lenses + tripod + extra gear
- Genre and creative-goal selection
- Live sunrise/sunset and weather via Open-Meteo
- Starting exposure/focus/drive recipe
- Photographer-style composition advice
- “Teach me” explanations for settings
- Public visual references via Wikimedia Commons
- Location scout information
- Field checklist
- Save shots locally on the device
- PWA install/offline shell

## Architecture decision

V2 deliberately has **no custom backend**. That is intentional: it reduces deployment time and removes server/API-key setup for the first working product. The external API calls are isolated in the front-end and can be moved behind a PicTour backend later without redesigning the user experience.

## Next production layer

After V2 is field-tested, the highest-value backend additions are user accounts/cloud saves, richer place/POI data, forecast history, route planning, AI-assisted shot coaching, and subscription/billing.
