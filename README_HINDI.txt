My IC Caller — Android Studio starter project

Is project mein:
- My IC Caller naam ka basic native Android UI
- iOS-inspired modern layout
- Light/Dark mode toggle
- Dial pad aur system dialer se call shuru karne ka option
- Recents, Contacts, Recordings aur Settings ke prototype screens

IMPORTANT:
Yeh abhi complete replacement phone app nahi hai aur call audio recording implement nahi karta.
Android par third-party apps ko phone-call audio capture karne se restrictions rok sakti hain.
Real call log/contacts ke liye runtime permissions, default-dialer role aur device testing chahiye.
Call recording feature ko device aur local laws ke mutabik implement/test karna hoga.

APK build:
1. Android Studio install karein (computer required).
2. File > Open se is folder ko select karein.
3. Gradle sync complete hone dein.
4. Build > Build Bundle(s) / APK(s) > Build APK(s).
5. APK app/build/outputs/apk/debug/app-debug.apk mein milegi.

Suggested test: Android 13+ device/emulator.
