# 10 SECONDS — MVP v0.1

A mobile-first playable prototype of the game concept we designed together.

## Included
- 20 challenge types
- 10-second challenge timer
- 3 lives
- score + best score
- coins
- revive placeholder
- shop placeholder
- daily challenge entry point
- offline localStorage persistence
- mobile-first UI
- Capacitor project config for Android/iOS packaging

## Run immediately
Open `www/index.html` in a browser, preferably in a mobile-sized viewport.

Or with Node:
1. `npm install`
2. `npm run web`

## Package as Android/iOS
Install Node.js and Android Studio/Xcode, then:
- `npm install`
- `npx cap add android`
- `npx cap sync android`
- `npx cap open android`

For iOS on a Mac:
- `npm install`
- `npx cap add ios`
- `npx cap sync ios`
- `npx cap open ios`

The App Store / Google Play accounts, signing, real ads, in-app purchases, privacy policy, store screenshots and final QA are still required before release.

## Important
This is an MVP source project, not a compiled APK/IPA. Real AdMob and App Store/Google Play Billing should be integrated after gameplay testing.
