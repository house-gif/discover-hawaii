# AASEN Discover · Hawaiʻi

A refined editorial travel guide prototype, beginning with Kauaʻi.

## What is included

- React Native / Expo 54 application for iOS, Android and web
- Porcelain, linen and charcoal design system
- Island selector (Kauaʻi live; five future-island placeholders)
- Searchable, region- and category-filtered Kauaʻi directory
- Place detail pages with provenance labels and map-search handoff
- Saved places and personal itinerary shortlist, persisted locally
- Safety, cultural etiquette and travel-privileges editorial notes
- Seed directory with **user/team-submitted** places, services and leads

## Get started

1. Install Node.js LTS.
2. In this directory, run `npm install`.
3. Run `npx expo start`.
4. Open in Expo Go or a simulator. For browser preview, install `react-dom`, `react-native-web` and `@expo/metro-runtime` with `npx expo install react-dom react-native-web @expo/metro-runtime`, then run `npx expo start --web`.

**GitHub upload:** Create a repository or use `house-gif/discover-hawaii`. Upload the contents of this folder, keeping `App.js`, `app.json`, `package.json`, and `src/` at the repository root. GitHub's website supports uploading multiple files; for nested folders, desktop Git or GitHub Desktop is easier.

## Content integrity

This is a **functional editorial prototype**, not a completed production release. The source lists were supplied by the user and team. Some listings were deduplicated and some were simplified into seed descriptions. Do not treat a listed operator, location, service, opening time, price, certification or promotion as independently verified. Images are **generic category photography** from Unsplash, not photos of the named businesses or places. Replace with licensed, place-specific assets before public release.

For launch, verify each listing and maintain structured fields for addresses, geocoordinates, hours, booking URLs, access requirements, provenance, last verified date, photo rights, and safety notices. Add live weather/ocean/park information only with trustworthy providers and clear timestamps. Secure consent and privacy review before adding guest accounts, analytics, booking/payment flows or personalized location tracking.

## Next production milestones

1. Audit and import the remaining supplied entries (including all floral, nursery, cultural-calendar, seasonal-harvest, market-hour and concierge subcategories).
2. Add licensed location-specific imagery, offline-first caching, geocoded maps, verified opening hours and source attribution.
3. Add detailed venue profiles, quiz, seasonal calendar, itinerary ordering and estimated departure planner.
4. Implement accessibility, screen-reader testing, robust offline error states and privacy controls.
5. Validate on physical iOS and Android devices, then build release artifacts via EAS.

## Notes

- The app does not require GitHub write access to run.
- The current UI and code have been statically checked, but no physical-device build was performed in this environment.
- `src/data/places.js` is the editable source of the seed content.
