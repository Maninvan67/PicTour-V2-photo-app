# PicTour V5

Photography-first field companion PWA. V5 is built directly from the V4.2 codebase, not the older V4.0 package.

## V5 direction
PicTour exists to inspire and assist the art of photography. AI is an assistant, never a replacement for the photographer. The app keeps human creative decisions at the centre: seeing, choosing, composing, timing, shooting, reviewing and reshooting.

## Included from the V4.x line
- Shot Builder with light, location, intent and actual-kit awareness
- Field Mode for use while shooting
- Photo Lab with local browser-side image diagnostics
- Wide Shot Scout
- Daily practice / shot missions
- Project Assistant for deliberate multi-shot projects
- XP and skill progression stored locally
- Save/share shot recipes
- Solar direction and field conditions

## New in V5
- Explicit Free → Pro → Photographer craft path inside the app
- Clear AI-assistance principle: AI supports the photographer rather than replacing creative judgment
- Fresh V5 PWA cache/versioning so deployments do not silently reuse the V4 service-worker cache
- Progress storage moved to `pictourProgress5` to prevent stale V4 state from being treated as V5

## Deploy
Static PWA. Connect the repository to your Render Static Site and deploy the repository root.

## Android
Open the deployed site in Chrome on Android and use Chrome's install option to add PicTour to the launcher.
