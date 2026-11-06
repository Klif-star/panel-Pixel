# Pixel Panel

Aplikasi Android dengan panel melayang untuk game Pixel Arena: kursor kustom dan auto shoot.

## Fitur

- **Panel melayang**: geser lewat judulnya, lipat dengan tombol –.
- **Kursor kustom**: putih di tengah layar, 8 bentuk bawaan, 6 warna, ukuran bisa diatur.
- **Upload gambar kursor**: PNG/JPG, latar dihapus otomatis (ada slider toleransi).
- **Auto shoot**: tap otomatis di titik merah yang kamu tentukan sendiri, jeda 30–1000 ms.

## Build APK (dari HP, lewat GitHub)

1. Push proyek ini ke repo GitHub (atau cukup file `.github/workflows/build.yml`).
2. Buka tab **Actions**, tunggu build selesai (±3–5 menit).
3. Unduh artifact **PixelPanel-APK**, ekstrak, lalu install `app-debug.apk`.

Build manual: tab Actions → **Build APK** → **Run workflow**.

## Cara pakai

1. Buka app, lalu **1. Izinkan tampil di atas aplikasi lain**.
2. **2. Aktifkan Aksesibilitas** dan nyalakan "Pixel Panel Auto Shoot".
   - Kalau tombolnya abu-abu (Android 13+): Info Aplikasi → ⋮ → *Izinkan setelan terbatas*.
3. **3. Mulai Panel Melayang**, lalu buka game.
4. Auto shoot: ketuk "Atur posisi tembak", geser titik merah ke tombol tembak, lalu nyalakan **Auto shoot**.

## Catatan

- Auto shoot hanya tap otomatis di posisi yang kamu atur. Tidak ada deteksi target.
- Min. Android 7.0 (API 24).
- Hentikan panel lewat tombol "Tutup panel" atau notifikasi "Pixel Panel aktif".
