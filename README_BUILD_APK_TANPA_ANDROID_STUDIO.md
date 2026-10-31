# Build APK tanpa Android Studio

Paket ini sudah dilengkapi GitHub Actions untuk membangun APK di cloud.

1. Ekstrak ZIP ini.
2. Buat repository baru di GitHub (boleh Private).
3. Upload seluruh isi folder `RED_PROJECT_PRO_ANDROID` ke repository, termasuk folder `.github`.
4. Buka tab **Actions** pada repository.
5. Pilih workflow **Build RED PROJECT PRO APK**, lalu klik **Run workflow**.
6. Setelah status selesai/sukses, buka hasil run tersebut.
7. Di bagian **Artifacts**, unduh `RED-PROJECT-PRO-APK`.
8. Ekstrak ZIP artifact. File `app-debug.apk` adalah aplikasi yang dipasang di HP Android.

Catatan: APK debug cocok untuk pemasangan dan pengujian langsung. Untuk distribusi publik/Play Store, diperlukan APK/AAB release yang ditandatangani dengan keystore milik pemilik aplikasi.
