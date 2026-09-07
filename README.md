# A542i Bubble Mermaid Android

Android overlay desktop-pet prototype. It uses the validated A542i v20 HTML runtime locally inside a transparent WebView; Chrome is not involved.

## Behavior
- 220dp round/transparent pet window
- A542i animation keeps playing over other apps
- drag anywhere
- release snaps to nearest screen edge
- launcher app asks for Android overlay permission
- persistent foreground-service notification while active

## Build
Open this folder in Android Studio, let Gradle sync, then Build > Build APK(s).
Minimum Android 8 (API 26). Target/compile SDK 35.

## Runtime semantics preserved
A542i v20: guide artwork hidden, guide parent not treated as mask, hard display-reference swaps, typed alpha, mask semantics, strict duration, transform defaults, linear tween.
