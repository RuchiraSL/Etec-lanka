# ETEC POS - Android Studio project

1. Install Android Studio (free): https://developer.android.com/studio
2. File > Open > choose THIS folder (the one containing settings.gradle). Wait for "Gradle sync" to finish (first time downloads ~1 GB).
3. Test: plug in your phone (USB debugging on) or create an emulator, then press the green Run button.
4. Make an installable APK:
   - Quick (debug) APK:  Build > Build Bundle(s) / APK(s) > Build APK(s)
     -> app/build/outputs/apk/debug/app-debug.apk
   - Release APK (for sharing):  Build > Generate Signed App Bundle / APK > APK > create a new key store
     (KEEP the key store file and passwords safe - you need them for every update).

Update the web app later: replace  app/src/main/assets/index.html  with your new file and build again.
Your Supabase URL/key are inside that index.html.
