**ICReport Full - Flutter (Project ZIP)**
Isi project:

1. Login (SQLite) - default user: admin / admin123
2. Scan barcode (mobile_scanner)
3. Input barang (manual or via scan)
4. List barang + filter (All / Near / Expired) + sorting
5. Export to Excel (.xlsx)
6. In-app notification banner for near/expired

**Cara menjalankan (Android Studio)**

1. Ekstrak icreport_full.zip
2. Buka folder proyek di Android Studio (Open)
3. Jalankan flutter pub get (Android Studio biasanya otomatis)
4. Jalankan emulator Android / hubungkan device
5. Tekan Run ▶ atau flutter run
6. Login: username admin, password admin123

**Catatan permission (Android)**

Untuk scan barcode, aplikasi butuh permission CAMERA.
Android Studio biasanya menambahkan permission ketika menggunakan mobile_scanner, namun jika diperlukan edit android/app/src/main/AndroidManifest.xml tambahkan: <uses-permission android:name="android.permission.CAMERA"/>

**Build APK**

Jalankan: flutter build apk --release
