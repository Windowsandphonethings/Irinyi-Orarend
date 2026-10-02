# Irinyi Órarend Android

Native Android WebView wrapper for the live IJROK / EduPage timetable:

https://irinyiref.edupage.org/timetable/

## Build in Android Studio
1. Open this folder in Android Studio.
2. Let Gradle sync.
3. Build > Build APK(s).
4. APK: `app/build/outputs/apk/debug/app-debug.apk`

## Build automatically on GitHub
This project contains `.github/workflows/build-apk.yml`.

1. Upload the entire project to a GitHub repository.
2. Open the repository's **Actions** tab.
3. Run **Build Android APK** (or push to main).
4. Download the `Irinyi-Orarend-APK` artifact.
5. Inside it is `app-debug.apk`, installable on Android.

App package:
`com.irinyi.orarend`

Minimum Android:
Android 7.0 (API 24)

Notes:
- The timetable itself is loaded live from EduPage.
- Internet access is required for fresh timetable data.
- External non-EduPage links open in the phone browser.
