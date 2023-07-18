Tutorial for new user uuntuk membuat repositori di akun github

1. Buka akun GitHub:
   Jika Anda belum memiliki akun GitHub, buat akun baru di https://github.com.

2. Login ke GitHub:
   Masuk ke akun GitHub Anda.

3. Buat Repositori Baru:
   - Klik tombol "+" di pojok kanan atas layar dan pilih "New Repository" atau kunjungi tautan https://github.com/new.
   - Berikan nama untuk repositori Anda (misalnya "node-project").
   - Tambahkan deskripsi opsional untuk menjelaskan proyek Anda.

4. Pilih Opsi Inisialisasi:
   - Anda dapat memilih opsi untuk menginisialisasi repositori dengan file README, .gitignore, atau lisensi jika diperlukan. Jika proyek Node.js, pilih .gitignore untuk Node.

5. Pengaturan Repositori:
   - Pilih opsi pengaturan lainnya sesuai kebutuhan, misalnya aksesibilitas, batasan lisensi, dll.

6. Buat Repositori:
   - Klik tombol "Create repository" untuk membuat repositori baru.

7. Inisialisasi Proyek Node.js Lokal (Opsional):
   - Jika Anda belum memiliki proyek Node.js lokal, buat proyek di komputer Anda dengan struktur file yang diperlukan (package.json, node_modules, dan file JavaScript lainnya).

8. Tambahkan Remote Repository GitHub:
   - Dari proyek Node.js lokal Anda, lakukan inisialisasi Git jika belum dilakukan (`git init`).
   - Tambahkan URL repositori GitHub Anda sebagai remote repository dengan perintah:
     ```
     git remote add origin <URL_Repositori_GitHub_Anda>
     ```
     Gantilah `<URL_Repositori_GitHub_Anda>` dengan URL yang Anda dapatkan setelah membuat repositori GitHub.

9. Tambahkan, Commit, dan Push:
   - Tambahkan file dan direktori proyek Node.js lokal Anda ke repositori dengan perintah:
     ```
     git add .
     ```
   - Lakukan commit perubahan dengan pesan deskriptif:
     ```
     git commit -m "Tambahkan proyek Node.js pertama saya"
     ```
   - Push proyek Anda ke repositori GitHub dengan perintah:
     ```
     git push -u origin master
     ```
     Pastikan Anda mengganti "master" dengan nama cabang utama proyek Anda jika menggunakan nama cabang yang berbeda.

Sekarang, proyek Node.js Anda telah diunggah ke repositori GitHub baru Anda. Anda dapat terus mengembangkan proyek ini dengan melakukan commit dan push perubahan Anda ke repositori GitHub.
