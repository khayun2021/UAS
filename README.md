# UAS
PEMROGRAMAN WEB 2

Selamat malam Pak, terlampir adalah file project "Aplikasi PHP Sederhana Untuk Penerimaan Bantuan Sosial Covid-19." berformat .rar

Berikut adalah beberapa fungsi dari php yang ada didalamnya :

#Login
- Membuat suatu akses terhadap form login dan logut menggunakan pemrograman PHP dan database MySQL. Login adalah proses terbatas yang hanya dapat dilakukan oleh pengguna yang telah memiliki akun otoritas, umumnya adalah username dan password.

#Login controller
- Tentunya kita harus membuat login controllernya, fungsi nya untuk proses cek n ricek apakah data username dan password udah benar atau belum.

#File halaman admin
- Jadi ini halaman tujuan kita, hanya yang mempunyai session sudah login yang bisa akses
- Disini untuk menampilkan nama yang login atau username, cukup pakai variable $_SESSION['nama']; atau apa saja yang ingin ditampilkan. Sesuai dengan variable yang kita tampung disession pada logincontroller tadi.
- Misal ada tambahan kolom hak_akses, kamu cukup tambahkan disession login controller dengan $_SESSION[‘’];

#Dashboard
- Halaman home.php adalah halaman yang diakses ketika proses login berhasil, silahkan buka file home.php

#Koneksi
- Koneksinya untuk menghubungkan form login ke tabel di database kamu, biar dia bisa cek apakah user ditemukan atau tidak

#Membuat Laporan PDF dengan PHP
- Dalam sebuah aplikasi laporan merupakan hal yang sangat penting karena dengan laporan kita bisa tahu data dari suatu database. Biasanya bentuk laporan akan berupa PDF, Excel dan lain sebagainya. Nah, pada kesempatan kali ini saya akan membahas tutorial bagaimana cara membuat laporan PDF dengan PHP.

#Logout
- Fungsi logout agar kita keluar dari session yang ada kalau kita klik logout otomatis kita keluar dari halaman admin, dan kembali ke halaman login. Makanya disitu ada session_destroy(), untuk menghapus semua data session yang tadi kita tampung.

Terima kasih
