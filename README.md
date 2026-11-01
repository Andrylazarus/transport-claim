# Transport Claim Report

Halaman input untuk Transport Claim Report mingguan: tol, bensin, dan odometer per hari, lalu download sebagai file Excel dengan format laporan yang biasa.

## Fitur

- **New week**: langsung menyiapkan Senin sampai Jumat. Odometer awal diambil dari odometer akhir minggu lalu.
- **Tombol route tol**: satu klik mengisi tol pergi dan pulang (Cikarang/Cibitung, Karawang Barat, Karawang Timur, Citra). Klik lagi untuk menghapus.
- **Harga tol diingat**: ketik nama gerbang tol, harganya terisi sendiri.
- **Repeat a past day**: menyalin customer, job, dan tol dari hari sebelumnya.
- **Download .xlsx**: format sama dengan laporan asli (font Arial 17, zoom 46%, kotak replacement day, calibration claim, dan Tamura claim).
- **Backup / Restore**: simpan semua data ke file `.json`, lalu muat lagi di browser atau perangkat lain.

## Penting: data tersimpan di browser

Versi GitHub ini menyimpan data di browser yang dipakai (localStorage). Kalau cache browser dihapus atau Anda pindah perangkat, data tidak ikut. Tekan **Backup** tiap minggu, dan pakai **Restore** untuk memuat data di perangkat lain.

## Menjalankan

Buka `index.html` di browser, atau aktifkan GitHub Pages:
Settings → Pages → Source: *Deploy from a branch* → Branch: `main`, folder `/ (root)` → Save.
