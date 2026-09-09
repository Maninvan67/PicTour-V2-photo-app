# PicTour 4.0

Photography-first field companion PWA.

## What changed in 4.0
- Photo Lab: load a photo and run a local browser-side image diagnostic for highlight concentration, shadow concentration, tonal contrast and edge detail. The image is not uploaded by this feature.
- Craft progression: XP, levels and skill counters stored locally.
- Solar direction: target-time sun azimuth/elevation estimate shown in the Scout view.
- Stronger field workflow: recipe, light window, movement and reshoot guidance remain the core experience.
- Mobile-first polish and 4.0 cache/versioning.

## Important
The Photo Lab is deliberately honest: it is a local image diagnostic, not a claim of human artistic judgment or a cloud AI model. A future backend can add multimodal AI critique, EXIF-aware diagnosis, cloud sync and collaborative learning without changing the field workflow.

## Deploy
This is still a static PWA. Connect the repository to your Render Static Site and deploy the repository root. Render can auto-deploy from Git commits.

## APIs
- OpenStreetMap Nominatim: geocoding/reverse geocoding
- Open-Meteo: weather and solar timing data
- Wikimedia Commons: public visual references

## Android
Open the deployed site in Chrome on Android and use Chrome's install option to add PicTour to the launcher.
