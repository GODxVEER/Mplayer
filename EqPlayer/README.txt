EQ Player - Android 10+ (minSdk 29)

1. Install Android Studio (Koala or newer) and open this folder.
2. Wait for Gradle sync to finish.
3. Build > Build Bundle(s) / APK(s) > Build APK(s).
4. The APK is in app/build/outputs/apk/debug/. Copy it to the phone and install it
   (allow "install unknown apps" when asked), or press Run with the phone connected by USB.

The player UI lives in app/src/main/assets/index.html.

NO ANDROID STUDIO? Build the APK online for free:
1. Create a free account at github.com and make a new repository.
2. Upload everything in this folder (including the hidden .github folder).
3. Open the repository's "Actions" tab. "Build APK" runs by itself (about 3-5 minutes).
4. Open the finished run, scroll to "Artifacts", download EQ-Player-apk, unzip it.
   Inside is app-debug.apk. Copy it to the phone and install it.
