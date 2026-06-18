# Tap Dash — Android APK

## App Info
- **Bundle ID:** com.tapdash.game
- **Unity Game ID:** 800005782
- **Placement ID:** Rewarded_Android
- **Min Android:** 6.0 (API 23)
- **Target Android:** 14 (API 34)

## How to get your APK (no PC needed)

### Step 1 — Push this folder to GitHub
1. Go to [github.com](https://github.com) → New repository → name it `tap-dash-android`
2. Upload all files from this folder (drag & drop in the GitHub web UI)
3. Click **Commit changes**

### Step 2 — GitHub Actions builds the APK automatically
1. Click the **Actions** tab in your GitHub repo
2. You'll see "Build Tap Dash APK" running
3. Wait ~5 minutes for it to finish ✅

### Step 3 — Download your APK
1. Click the finished workflow run
2. Scroll down to **Artifacts**
3. Download **TapDash-debug.apk** — install directly on your phone!

## Install on Android
1. Download the APK to your phone
2. Go to **Settings → Security → Unknown Sources** → Enable
3. Open the downloaded APK → Install
4. Play Tap Dash! 🎮

## Files
```
tap-dash-android/
├── .github/workflows/build-apk.yml   ← Auto-builds APK on push
├── android/                           ← Android project
│   ├── app/
│   │   ├── src/main/
│   │   │   ├── AndroidManifest.xml
│   │   │   ├── java/com/tapdash/game/MainActivity.java
│   │   │   └── assets/public/        ← Web app goes here
│   │   └── build.gradle
│   ├── build.gradle
│   └── settings.gradle
├── capacitor.config.json
└── package.json
```
