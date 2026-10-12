# NUSANTARA TV — Starter Android Project

Kerangka UI awal aplikasi NUSANTARA TV untuk HP Android dan Android TV, dibuat dengan Kotlin dan Jetpack Compose.

## Cara membuat APK dari HP menggunakan GitHub

1. Unduh dan ekstrak ZIP proyek ini.
2. Buka GitHub dan masuk ke akun.
3. Buat repository baru bernama `NusantaraTV`. Untuk pemula, pilih Public agar unggah file mudah; jangan unggah rahasia atau data pribadi.
4. Pada halaman repository, pilih **Add file → Upload files**, lalu unggah semua isi folder proyek hasil ekstrak. Pastikan folder `.github/workflows` ikut terunggah. Jika file tersembunyi tidak terlihat di HP, buat file workflow secara terpisah dengan path `.github/workflows/build-apk.yml`, lalu salin isi file tersebut dari ZIP.
5. Tekan **Commit changes**.
6. Buka tab **Actions**. Pilih **Build NUSANTARA TV APK** dan tekan **Run workflow** jika build belum berjalan otomatis.
7. Tunggu sampai workflow selesai dengan tanda centang hijau.
8. Buka hasil workflow dan cari bagian **Artifacts**. Unduh `NusantaraTV-debug-apk`.
9. Ekstrak ZIP artifact dan temukan `app-debug.apk`. Buka file untuk memasang. Android mungkin meminta izin “Install unknown apps” untuk aplikasi yang digunakan mengunduh file.

## Fitur UI awal
- Beranda, Live TV, Film, Olahraga, Favorit, Pengaturan
- Navigasi fokus dasar untuk remote Android TV
- Layout adaptif untuk layar kecil dan layar lebar

## Penting
Ini adalah starter UI, bukan aplikasi streaming lengkap. Belum ada URL channel atau film, dan kartu contoh belum memutar konten. Tambahkan hanya sumber streaming resmi dan berizin. APK debug cocok untuk pengujian; rilis publik memerlukan pengujian, penandatanganan release, dan pemeriksaan persyaratan distribusi.
