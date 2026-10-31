# RED PROJECT PRO — Android

Project Android Studio pembungkus WebView untuk HTML RED PROJECT PRO yang diberikan.

## Cara membuat APK
1. Ekstrak ZIP ini.
2. Buka Android Studio → **Open** → pilih folder `RED_PROJECT_PRO_ANDROID`.
3. Tunggu Gradle Sync selesai (perlu internet).
4. Pilih **Build → Build Bundle(s) / APK(s) → Build APK(s)**.
5. APK debug tersedia di `app/build/outputs/apk/debug/app-debug.apk`.

## Catatan
- Aplikasi memuat HTML lokal dari assets dan menggunakan internet untuk Supabase serta pustaka Supabase JS dari jsDelivr.
- Login admin tetap memakai Supabase Authentication; data tetap tersimpan di project Supabase yang sudah tertanam di HTML.
- Penyimpanan browser (localStorage/cookies) diaktifkan.
- Fitur yang bergantung pada browser desktop seperti jendela cetak/PDF dan unduhan CSV mungkin memerlukan penyesuaian native Android. Uji semua menu di perangkat sebelum dipakai operasional.
- Untuk rilis publik, ganti applicationId bila diperlukan, siapkan ikon, privacy policy, dan signing key.
