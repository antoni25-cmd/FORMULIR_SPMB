# Aplikasi Pendataan Siswa

Aplikasi web modern untuk pendataan siswa, dibuat dengan React dan Vite. Aplikasi ini siap untuk di-deploy ke Vercel!

## Fitur
- Form input lengkap untuk data siswa (berdasarkan format KK dan Dapodik)
- Penyimpanan lokal (Local Storage)
- Ekspor data ke file Excel (.xlsx)

## Panduan Upload ke GitHub
1. Buka akun [GitHub](https://github.com/).
2. Buat repository baru (klik tombol **New**). Beri nama misal: `pendataan-siswa`.
3. Buka Terminal/Command Prompt di folder ini (`d:\DATA\data-siswa-app`).
4. Jalankan perintah berikut secara berurutan:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/[USERNAME_ANDA]/pendataan-siswa.git
   git push -u origin main
   ```
*(Ganti [USERNAME_ANDA] dengan username GitHub Anda yang sesungguhnya)*

## Panduan Deploy ke Vercel
1. Buka [Vercel](https://vercel.com/) dan login menggunakan akun GitHub Anda.
2. Klik tombol **Add New...** > **Project**.
3. Cari repository `pendataan-siswa` yang baru saja Anda buat di GitHub, lalu klik **Import**.
4. Di bagian *Configure Project*, Vercel akan otomatis mendeteksi bahwa ini adalah proyek **Vite**. Biarkan pengaturan default-nya.
5. Klik **Deploy** dan tunggu 1-2 menit.
6. Selesai! Aplikasi Anda sudah online dan dapat diakses dari mana saja.
