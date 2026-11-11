# KEIVAL AI (Android)

## Cara membuat APK
1. Install Android Studio (https://developer.android.com/studio).
2. File > Open, pilih folder KeivalAI ini. Tunggu Gradle sync selesai (butuh internet).
3. Menu Build > Build Bundle(s) / APK(s) > Build APK(s).
4. APK ada di app/build/outputs/apk/debug/app-debug.apk. Kirim ke HP lalu install
   (izinkan "Install dari sumber tidak dikenal").

## Cara pakai
Saat pertama dibuka, masukkan API key Anthropic (console.anthropic.com).
Key disimpan di HP. Ketuk ikon gear untuk mengganti key.

## Ubah nama / model
- Nama aplikasi: app/src/main/AndroidManifest.xml (android:label)
- Model dan kepribadian AI: MainActivity.kt (MODEL dan SYSTEM_PROMPT)
- Tampilan: app/src/main/assets/index.html
