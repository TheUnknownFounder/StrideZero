<div align="center">

# StrideZero

**Walk, run, ride and train. Keep your progress yours.**

![Android](https://img.shields.io/badge/Android-8.0%2B-20D4FF?style=flat-square&logo=android&logoColor=white)
![Version](https://img.shields.io/badge/Version-11.2.4-168BFF?style=flat-square)
![Status](https://img.shields.io/badge/Build-Debug%20Preview-7F52FF?style=flat-square)
![Price](https://img.shields.io/badge/Free-No%20Ads-0B1F3A?style=flat-square)

[Download releases](https://github.com/TheUnknownFounder/StrideZero/releases) · [Report an issue](https://github.com/TheUnknownFounder/StrideZero/issues) · [Developer](https://github.com/TheUnknownFounder)

</div>

StrideZero is an Android fitness app for outdoor tracking and guided home workouts. Record a walk, follow a yoga session, explore your history or train with friends nearby—all without creating a StrideZero account.

Your workout history stays on your phone. Core tracking, guided training and on-device coaching work offline; maps, destination searches and optional online services use an internet connection.

## What's new in 11.2.4

- **Training replaces Plan:** personalized recommendations, quick starts, workout search, body-focus filters and weekly progress.
- **Optional first-time setup:** choose your goals, experience and profile details, skip any questions and edit them later in Settings.
- **Offline posture previews:** exercise-specific visuals and form cues for guided sessions.
- **Focused indoor workouts:** yoga, strength, gym and HIIT screens show relevant session information without unnecessary GPS, steps or pace cards.
- **Nearby Party:** approved nearby connections, shared workout progress and optional live friend locations with temporary paths.
- **Tracking improvements:** faster location acquisition, speed smoothing, GPS-jump filtering and useful early-session pace estimates.
- **Maps and appearance:** satellite workout maps by default, improved Indian destination search and 14 unified app themes.

## Outdoor tracking

Track **walking, running and cycling** with native MapLibre maps, recorded route lines and configurable workout metrics. Pause, resume and finish from the app, with foreground-service controls available while a workout is active.

Walking and running support hardware step counting with a motion-sensor fallback. Location filtering helps reduce stationary GPS drift, while speed smoothing and stale-value decay reduce spikes and lingering readings. Accuracy still depends on your phone, permissions and GPS conditions.

Save completed sessions with a name, notes and rating. Review your history, export GPX files or transfer data through a PIN-encrypted `.szbackup` file.

## Guided home training

Choose from **14 no-equipment programs** spanning cardio, core, strength, yoga, mobility and low-impact recovery.

- Recommendations based on your chosen goals, focus areas and activity level.
- Weekly training targets and progress.
- Guided timers or repetition targets, posture previews and form cues.
- Previous, pause and next controls during a session.
- Indoor tracking that keeps irrelevant outdoor metrics out of the way.

Core workouts build strength; they do not guarantee fat loss from one specific body area.

## Train together with Nearby Party

Nearby Party connects compatible phones through Google Play services Nearby Connections using local Bluetooth and Wi-Fi transports.

1. One person selects **Host party**; friends select **Find nearby**.
2. Compare the displayed authentication code on both phones before accepting.
3. Share live workout progress with accepted members.
4. During an outdoor workout, each person can separately enable live location sharing.
5. Shared friends appear on the workout map with temporary paths.

Location sharing starts **off**. Friend paths stay in memory for the nearby session and clear when sharing stops or the connection ends. They are not added to workout history or transfer backups.

This feature works with people physically nearby. It is not remote tracking or an emergency-location service.

## Stride AI

Stride AI provides on-device coaching without an account, API key or internet connection. It can summarize recent workouts, compare activity trends, highlight training balance and suggest a next session.

Optional Gemini coaching uses your own API key. The key is protected with Android Keystore and excluded from transfer backups. The cloud-coaching request uses a limited workout summary rather than GPS tracks or personal profile details.

## Privacy and connectivity

| Feature | How it works |
| --- | --- |
| Workout history and fitness profile | Stored locally on your device |
| Core tracking, guided training and Stride AI | Work offline |
| Street and satellite maps | Internet needed for fresh map tiles; some previously viewed tiles may be cached |
| Destination search and route generation | Use external online providers |
| Nearby Party | Local device connections, explicit approval and optional location sharing |
| GPX and encrypted backups | Export only when you choose a destination |
| Gemini | Optional online coaching with your own key |

Version 11 has **no ads and no automatic StrideZero analytics SDK**. Third-party services have their own privacy practices; Google's Nearby Connections SDK may collect usage diagnostics according to the device's Google usage and diagnostics settings.

There is no StrideZero cloud-account backend or automatic cross-device sync. You can use Android's document picker to save an encrypted backup locally or through an installed storage provider.

## Download and install

1. Open [Releases](https://github.com/TheUnknownFounder/StrideZero/releases).
2. Select the version you want and download its `.apk` from **Assets**.
3. Open the APK on your Android phone and follow the installation prompts.
4. If Android requests it, allow installation from the browser or file manager you used.

**Requires Android 8.0 or newer.** Nearby Party depends on compatible Google Play services and available Bluetooth/Wi-Fi capabilities.

The v11.2.4 APK is a **debug preview build**. Back up your history before updating. If Android rejects an update because the signing certificate differs, keep the installed app until you have secured your backup.

Download the APK asset to install the app; GitHub's automatic “Source code” archives are not Android installers.

## Feedback

Found a bug? [Open an issue](https://github.com/TheUnknownFounder/StrideZero/issues) with your app version, phone model, Android version and steps to reproduce it. A screenshot or short recording helps—remove personal information and location details first.

## About this repository

This public repository hosts release information, downloads and feedback. The current application source is maintained privately. Downloading this repository does not provide a complete buildable copy of the current app.

StrideZero is proprietary freeware. Public downloads do not grant permission to redistribute, modify or resell its source code.

## Developer and support

Created by **Vishnu Raj · [@TheUnknownFounder](https://github.com/TheUnknownFounder)**.

Optional UPI support: **`vishnubhaii@fam`**. Donations do not unlock features.

Copyright © 2026 Vishnu Raj. All rights reserved.
