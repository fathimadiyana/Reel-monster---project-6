# Reel Monster — Project 6, Level 1

## What it does
- Native Android app written in Kotlin.
- Floating, draggable monster bubble displayed over other apps.
- Manual Level 1 counter: tap once after each reel.
- Monster appearance grows/changes as the count rises and shows playful messages.
- Today's count, estimated time lost, and last seven days.
- Counts persist locally using SharedPreferences.
- No account, network calls, analytics or internet permission.

## Build and install
1. Install Android Studio (or Android command-line tools) and a compatible JDK (17).
2. Open this `Reel_Monster_Project6_Level1` folder as an existing Gradle project.
3. Allow Gradle to sync and install Android SDK Platform 35 if prompted.
4. Connect an Android phone with USB debugging enabled, or use an emulator.
5. Run the `app` configuration to install the app.
6. Open Reel Monster and tap **Enable floating monster**.
7. Android Settings opens the **Display over other apps** permission. Allow it.
8. Return to Reel Monster and tap **Enable floating monster** again.
9. Open Instagram or YouTube. Tap the monster once after each reel.
10. Return to the app to see today's count, estimated time and seven-day history.

## Important Android notes
- Android only. Overlay permission is required and must be granted by the user.
- The service runs as a foreground service with an ongoing notification so Android is less likely to stop it.
- This Level 1 build counts manually. It does not inspect Instagram/YouTube screens or automatically detect reels (that is Level 2).
- Estimated time lost is a rough display estimate: 30 seconds per manually counted reel. It is not measured screen time.
- Test on a real device. Some manufacturers apply extra background-service restrictions; allow the app to run in the background if necessary.
- The project source is provided; an APK is not included because APK signing/building requires the Android SDK and local build environment.
