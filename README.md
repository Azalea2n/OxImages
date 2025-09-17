# oximages

oximages adalah aplikasi desktop berbasis Electron untuk mengonversi, mengelola, dan mengedit gambar sederhana. Aplikasi ini dibangun menggunakan Electron dan library Sharp untuk pemrosesan gambar yang efisien.

## Fitur Utama

- **Buka File atau Folder**: Dukung pembukaan file gambar individu atau seluruh folder.
- **Konversi Format**: Konversi gambar ke berbagai format termasuk PNG, JPG/JPEG, WebP, GIF, BMP, TIFF, AVIF, dan ICO.
- **Recent Files**: Akses cepat ke file terbaru yang dibuka (hingga 10 file).
- **Zoom dan Navigasi**: Zoom in/out dan reset zoom untuk melihat detail gambar.
- **Simpan dan Export**: Simpan gambar yang diedit atau ekspor ke format baru dengan pengaturan kualitas.
- **Pengaturan**: Akses preferences melalui menu Settings.
- **Menu Help**: Informasi About aplikasi.

Aplikasi mendukung ekstensi gambar umum seperti JPG, PNG, GIF, WebP, BMP, TIFF, AVIF, dan ICO.

## Persyaratan Sistem

- Sistem operasi: Windows, macOS, atau Linux.
- Ruang disk minimal 100 MB.
- RAM minimal 512 MB (disarankan 2 GB untuk performa optimal).

## Instalasi dan Penggunaan

Untuk pengguna akhir, unduh dan instal file executable dari paket distribusi (tersedia untuk Windows, macOS, dan Linux).

1. **Unduh Paket**: Dapatkan file installer (.exe untuk Windows, .dmg untuk macOS, atau .deb/.rpm untuk Linux) dari sumber resmi.
2. **Instalasi**:
   - Windows: Jalankan .exe dan ikuti wizard instalasi.
   - macOS: Buka .dmg dan seret aplikasi ke folder Applications.
   - Linux: Instal paket sesuai distribusi (misalnya, `sudo dpkg -i oximages.deb`).
3. **Jalankan Aplikasi**: Buka oximages dari menu Start, Launchpad, atau terminal dengan perintah `oximages`.

Untuk developer (mode pengembangan):
- Pastikan Node.js (versi 14+) dan npm terinstal.
- Jalankan `npm install` di direktori proyek.
- Jalankan `npm start` untuk mode development.

## Penggunaan

1. **Membuka Gambar**:
   - Pilih `File > Open File` (Ctrl+O) untuk membuka satu file.
   - Pilih `File > Open Folder` (Ctrl+Shift+O) untuk membuka folder.

2. **Konversi dan Export**:
   - Setelah gambar terbuka, pilih `File > Export` dan pilih format tujuan.
   - Atur kualitas jika diperlukan (untuk format seperti JPG, WebP).
   - Simpan melalui `File > Save` (Ctrl+S) atau `Save As` (Ctrl+Shift+S).

3. **Navigasi**:
   - Gunakan `View > Zoom In` (Ctrl++), `Zoom Out` (Ctrl+-), atau `Reset Zoom` (Ctrl+0).

4. **Recent Files**:
   - Akses melalui `File > Recent Files` untuk membuka file sebelumnya.

5. **Settings**:
   - Buka `Settings > Preferences` (Ctrl+,) untuk mengatur preferensi.

6. **Help**:
   - `Help > About` untuk informasi versi (oximages v1.0.0, built with Electron and Sharp).

## Troubleshooting

- **Aplikasi tidak terbuka**: Pastikan semua dependensi terinstal dan sistem memenuhi persyaratan. Coba jalankan sebagai administrator.
- **Error konversi gambar**: Periksa apakah file input tidak rusak dan format didukung. Update aplikasi ke versi terbaru jika tersedia.
- **Masalah performa**: Tutup aplikasi lain untuk membebaskan RAM. Gunakan format gambar yang lebih ringan jika memungkinkan.
- **File tidak tersimpan**: Periksa izin tulis di direktori tujuan. Gunakan `Save As` untuk memilih lokasi baru.
- **Recent Files kosong**: Hapus file `typography.json` di direktori userData (biasanya `%APPDATA%/oximages` di Windows) dan restart aplikasi.

Jika masalah berlanjut, hubungi developer untuk dukungan.

## Dependensi Utama

- Electron: Framework desktop cross-platform.
- Sharp: Pemrosesan gambar efisien.

## Lisensi

Proprietary Software - All Rights Reserved. Copyright © Azalea2n 2023. No part of this software may be reproduced, distributed, or transmitted in any form without prior written permission.

## Kontak

- Developer: Azalea2n

Terima kasih telah menggunakan oximages!