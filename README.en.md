<p align="center">
  <a href="README.md">Español</a> · <b>English</b>
</p>

# AGX Sports

**The endurance sports app built to train like you have a coach, without paying for one.**

AGX Sports is an app for running, cycling, triathlon and hybrid training, made by **AGX Tech And Code**. It records your activities, analyzes your performance, connects you with your community and builds a personalized training plan that adapts to what you actually do.

The features other apps charge for in their subscription are free in AGX Sports.

Born in Armenia, Quindío (Colombia), and designed from day one for athletes around the world: multiple languages, metric and imperial units, time zones and events from every country.

> **Status:** in design. Screenshots and GIFs will be added as each screen is finished.

> This repository is a showcase only. The app's source code is private.

## Key features

### Recording and analysis
- 30+ sports, auto-pause, splits, laps and configurable data screens.
- Reliable background GPS and offline recording that syncs later.
- Heart rate, power and pace zones, power curve, fitness, fatigue and form, grade-adjusted pace and FTP history.
- AI summary for every activity.

### AGX Coach (free)
- Personalized, adaptive plans for cycling, running, triathlon and hybrid training, based on public sports science.
- Initial assessment, guided tests (FTP, threshold, critical pace, swimming and strength) and goals by stage.
- Training calendar with structured sessions you can send to your watch, bike computer or smart trainer.
- Altitude and heat adjustment, injury prevention for load spikes and weekly feedback.
- Chat with the AI coach, nutrition and hydration guidance and race strategy.

### Cycling Zone
- Bluetooth sensors straight from your phone: power meter, HR strap, cadence, speed and radar.
- Climb analysis and iconic climbs from around the world, wind and weather on your route.
- Bike garage with per-component maintenance and **anti-theft registry** with serial number checker.

### Routes and maps
- Route builder, suggested routes, heatmaps and turn-by-turn navigation.
- Downloadable maps for use without signal, built for mid-range phones and low data.

### Community
- Follow athletes, activity feed, likes, comments and route sharing.
- Cups, trophies and medals with tiers, challenges, leagues and clubs.
- Ready-made cards for Instagram and TikTok stories.

### Import your history
- Bring all your activities from other apps' export file and from Garmin, Polar, Suunto, COROS or GPX, FIT and TCX files.

### Privacy and safety first
- Activities private or followers-only by default, and privacy zones to hide where you start and finish.
- Live location sharing with your contacts and crash detection.
- Export or delete your account and all your data in a few taps.

## Screenshots

*Coming soon.* Screenshots go in [`screenshots/`](screenshots/) and GIFs in [`gifs/`](gifs/).

## Tech stack

| Part | Technology |
|---|---|
| Mobile app (iOS and Android) | React Native + Expo + TypeScript |
| Web and dashboard | Next.js on Vercel |
| Backend | Supabase (Auth, Postgres with PostGIS, Storage, Edge Functions) |
| Maps | MapLibre + OpenStreetMap |
| Health data | Apple HealthKit and Health Connect |
| Languages | Spanish and English at launch, ready for more |

## Roadmap

- [ ] **Phase 0 — Design:** brand, research, specification and screen design.
- [ ] **Phase 1 — MVP (Android and iPhone, Spanish and English):** GPS recording, cycling sensors, history import, power and climb analysis, routes with offline maps, privacy, anti-theft garage, injury prevention, basic social, cups and medals, and AGX Coach for cycling and running.
- [ ] **Phase 2:** triathlon, smart trainer, segments, leagues, clubs, group rides, live safety, live tracking for family, worldwide event calendar and more languages.
- [ ] **Phase 3:** human coach marketplace and AGX store benefits.

## Contact

📧 **agxtechandcode@gmail.com**

## License

© 2026 AGX Tech And Code. All rights reserved. See [LICENSE](LICENSE).
