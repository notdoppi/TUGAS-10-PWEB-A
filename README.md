# TUGAS-10-PWEB-A
pada tugas kali ini kita diminta untuk menganalisis studi kasus CRUD pendaftaran siswa

## Deskripsi Umum
Web pendaftaran siswa merupakah sebuah web untuk membantu proses pendaftara calon siswa secara digital dan terintegrasi dengan database. web ini dibangun dengan mennggunakan PHP sebagai backend dan database MySQL sebagai database.

website ini dirancang untuk proses pendaftaran siswa yang lebih efisien, cepat, aman, dan meminimalisir kesalahan pencatatan data. Seluruh data pendaftaran akan dikelola melalui sistem oleh admin.

## Tujuan
1. Menyediakan media pendaftaran siswa secara online agar mudah untuk digunakan
2. Mempermudah pengolahan data pendaftar
3. Mengurangi risiko kehilangan dan kesalahan data
4. mempercepat proses administrasi

## Fitur
- Pendaftaran siswa (Create)
- Melihat daftar pendaftar (Read)
- Mengedit data (Update)
- Menghapus data (Delete)

## Peran pengguna 
admin :
- menginput data pendaftar
- melihat seluruh data pendaftar
- mengedit data
- menghapus data
- bertanggungjawab atas validitas, keamanan, dan pengelolaan data

## Struktur Database
- `id` = sebagai primary key
- `nama` = menyimpan nama siswa
- `alamat` = menyimpan alamat siswa
- `jenis_kelamin` = menyimpan jenis kelamin siswa
- `agama` = menyimpan agama siswa
- `sekolah_asal` = menyimpan sekolah asal siswa

## Alur Proses Sistem
1. admin membuka sistem (web)
pada tab ini terdapat dua menu utama yaitu:
- daftar baru
- pendaftar
3. admin memilih menu `daftar baru`
- sistem akan menampilkan form pendaftaran siswa
- admin mengisi data siswa
- admin menekan tombol dafta
- sistem akan menyimpan data ke dalam database
4. admin membuka menu `pendaftar`
sistem akan menampilkan seluruh data siswa yang terdaftar. pada menu ini, admin dapat melihat data, mengedit data, dan menghapus data
5. jika ingin mengupdate data maka admin memilih `edit` dalam menu `pendaftar`
- sistem akan menampilkan data lama dalam form
- admin melakukan perubahan
- data baru disimpan ke dalam database dan menggantikan data yang lama
6. jika ingin menghapus data maka admin memilih `delete` dalam menu `pendaftar`
sistem akan menghapus data dari database
