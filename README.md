**ICReport Full - Flutter (Project ZIP)**
Isi project:

Login (SQLite) - default user: admin / admin123
Scan barcode (mobile_scanner)
Input barang (manual or via scan)
List barang + filter (All / Near / Expired) + sorting
Export to Excel (.xlsx)
In-app notification banner for near/expired

**Cara menjalankan (Android Studio)**

Ekstrak icreport_full.zip
Buka folder proyek di Android Studio (Open)
Jalankan flutter pub get (Android Studio biasanya otomatis)
Jalankan emulator Android / hubungkan device
Tekan Run ▶ atau flutter run
Login: username admin, password admin123

**Catatan permission (Android)**

Untuk scan barcode, aplikasi butuh permission CAMERA.
Android Studio biasanya menambahkan permission ketika menggunakan mobile_scanner, namun jika diperlukan edit android/app/src/main/AndroidManifest.xml tambahkan: <uses-permission android:name="android.permission.CAMERA"/>

**Build APK**

Jalankan: flutter build apk --release
