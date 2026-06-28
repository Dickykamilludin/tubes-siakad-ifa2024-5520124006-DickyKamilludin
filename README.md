## Deskripsi Singkat Aplikasi

Sistem Informasi Akademik (SIAKAD) adalah aplikasi berbasis **Laravel 12** yang dirancang untuk membantu pengelolaan data akademik di lingkungan kampus. Aplikasi ini menerapkan sistem **multi-role** yang membedakan hak akses antara **Admin** dan **Mahasiswa**.

Admin bertugas mengelola seluruh data akademik seperti data dosen, mahasiswa, mata kuliah, jadwal perkuliahan, dan Kartu Rencana Studi (KRS). Sementara itu, Mahasiswa hanya dapat melihat informasi akademik serta melihat data KRS yang dimiliki tanpa dapat mengubah data.

Aplikasi dibangun menggunakan **Laravel 12**, **PHP 8**, **MySQL**, **Bootstrap 5**, serta **Laravel Breeze Authentication** untuk proses autentikasi pengguna.

---

## Penjelasan Singkat Fungsi Masing-Masing Halaman

### 1. Halaman Login
Halaman login digunakan sebagai pintu masuk aplikasi. Pengguna masuk menggunakan email dan password sesuai hak akses yang dimiliki, kemudian sistem akan mengarahkan ke dashboard masing-masing.

### 2. Dashboard Admin
Dashboard Admin menampilkan halaman utama setelah admin berhasil login. Dari halaman ini admin dapat mengakses seluruh menu pengelolaan data akademik.

### 3. Data Dosen
Halaman ini digunakan untuk mengelola data dosen. Admin dapat menambahkan, mengubah, menghapus, serta melihat daftar dosen yang tersimpan dalam sistem.

### 4. Data Mahasiswa
Halaman ini digunakan untuk mengelola data mahasiswa. Admin dapat melakukan proses tambah, ubah, hapus, dan melihat seluruh data mahasiswa.

### 5. Data Mata Kuliah
Halaman ini digunakan untuk mengelola informasi mata kuliah seperti kode mata kuliah, nama mata kuliah, dan jumlah SKS. Data ini menjadi acuan dalam penyusunan jadwal dan KRS.

### 6. Data Jadwal Kuliah
Halaman ini digunakan untuk mengatur jadwal perkuliahan. Admin dapat menentukan mata kuliah, dosen pengajar, hari, jam, dan kelas sehingga jadwal dapat dilihat oleh mahasiswa.

### 7. Data KRS
Halaman ini digunakan untuk mengelola data Kartu Rencana Studi (KRS). Admin dapat melihat, menambah, maupun menghapus data pengambilan mata kuliah oleh mahasiswa.

### 8. Dashboard Mahasiswa
Dashboard Mahasiswa merupakan halaman utama setelah mahasiswa login. Halaman ini memberikan akses menuju informasi akademik yang dapat dilihat oleh mahasiswa.

### 9. Halaman Mata Kuliah (Mahasiswa)
Halaman ini menampilkan daftar mata kuliah yang tersedia sehingga mahasiswa dapat melihat informasi mata kuliah yang ditawarkan.

### 10. Halaman Jadwal Kuliah (Mahasiswa)
Halaman ini menampilkan jadwal perkuliahan yang telah ditentukan oleh admin sehingga mahasiswa dapat mengetahui hari, jam, dan mata kuliah yang akan diikuti.

### 11. Halaman KRS Mahasiswa
Halaman ini menampilkan daftar mata kuliah yang telah diambil oleh mahasiswa sebagai Kartu Rencana Studi (KRS). Mahasiswa hanya dapat melihat data tersebut sesuai hak akses yang diberikan.

---

## Teknologi yang Digunakan

- Laravel 12
- PHP 8
- MySQL
- Bootstrap 5
- Laravel Breeze Authentication
- Eloquent ORM
- Git & GitHub

---

## Akun Login

### Admin
- **Email:** admin@gmail.com
- **Password:** password

### Mahasiswa
- **Email:** mahasiswa@gmail.com
- **Password:** password