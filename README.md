# Personal Cash Manager (Native Android App)

Complete offline native Android accounting app built with **Kotlin**, **Jetpack Compose**, and **Room Database**.

## Key Features
- 100% Offline with zero cloud tracking, zero login, and zero external APIs
- Room SQLite local database persistence
- Dashboard with real-time balance formula: `Opening Balance + Total Income - Total Expenses - Money Returned to Owner = Current Cash`
- Add income & expenses with shop name, invoice number, category, and camera invoice photo
- Custom accounting periods (Day 1–15, Day 16–end of month, or custom)
- Settlement flow: settle with owner, record money returned, archive and lock past records
- Bilingual English and Arabic RTL PDF export
- Local backup and restore

## How to Build the APK in Android Studio
1. Unzip this project folder.
2. Open **Android Studio** (Hedgehog, Iguana, or Koala+ recommended).
3. Select **File > Open** and pick the unzipped directory.
4. Let Gradle sync dependencies.
5. In the top menu, click **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
6. Android Studio will compile the app and show a popup notification: *"APK(s) generated successfully"*.
7. Click **locate** to find `app-debug.apk`.

## How to Sideload & Install on your Android Phone
1. Transfer `app-debug.apk` to your phone via USB cable, Google Drive, or Bluetooth.
2. On your Android phone, open the **Files** or **Downloads** app.
3. Tap on `app-debug.apk`.
4. If Android displays *"For your security, your phone is not allowed to install unknown apps from this source"*, tap **Settings** and toggle **Allow from this source**.
5. Tap **Install**.
6. Launch **Cash Manager** from your home screen. It will run completely offline!
