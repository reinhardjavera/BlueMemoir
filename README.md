# UAS - IF570E - Mobile Application Programming (Lecture dan Lab)

# BlueMemoir: Save Memories with Location Details

## a. Deskripsi Singkat tentang Aplikasi

**BlueMemoir** adalah aplikasi foto diary yang dirancang untuk memudahkan pengguna menyimpan dan mengorganisir kenangan mereka dengan detail lokasi. Dengan integrasi GPS, aplikasi ini memungkinkan pengguna untuk tidak hanya menangkap momen, tetapi juga menyimpan konteks lokasi secara otomatis. Aplikasi ini membantu pengguna menciptakan diary yang diperkaya dengan tanggal, waktu, dan lokasi dari kenangan tersebut.

## b. Informasi Anggota Kelompok

- **Rich Marvin Lim** - 00000079061
- **Reinhard Javera Maheswara** - 00000077732
- **Ignatius Steven** - 00000070642
- **Muhamad Thaariq** - 00000070514

## c. Fitur-fitur yang Sudah Diimplementasikan

**NB: Jika terdapat error ataupun fitur yang dicoba tidak sesuai, mohon ditunggu sebentar ataupun direfresh-refresh, karena bisa karena kendala internet sehingga belum ke-load**

1. **Autentikasi Pengguna**:
   - Pendaftaran menggunakan email dan password.
   - Login menggunakan email dan password, dengan opsi autentikasi melalui Google.

2. **Halaman Utama (Home)**: 
   - Tombol pembuatan diary.
   - Tombol recent dan oldest untuk mengurutkan diary (akan bergantian contoh jika klik recent maka tombol akan berubah menjadi oldest, dan sebaliknya).
   - Tombol lihat semua.
   - Filter berdasarkan Tag.
   - Fitur search dinamis.

3. **Lihat Semua**:
   - Menampilkan seluruh diary yang dibuat.
   - Terdapat Slider otomatis.

4. **Filter Tag**:
   - Memungkinkan pengguna untuk filter diary berdasarkan tag pada diary tersebut.

5. **Search Dinamis**:
   - Fitur search diary berdasarkan judul, dimana diary yang disearch akan secara dinamis mengikuti ketikan pengguna.

6. **Detail Diary**:
   - Menampilkan detail diary, termasuk judul, foto, tanggal, tag, dan konten.

7. **Pembuatan Diary (Diary Entry)**:
   - Membuat diary tanggal secara otomatis.
   - Menambahkan foto melalui kamera atau galeri, serta menulis keterangan yang menyertai diary.
   - Mengambil lokasi saat ini menggunakan GPS, serta bisa mengedit lokasi dengan google maps.
   - Menambahkan Tag pada diary.

8. **Pengeditan Diary**:
   - Mengedit konten, judul, foto diary, tag, dan lokasi.

9. **Favorit**:
   - Menandai catatan sebagai favorit untuk akses mudah dari halaman favorit.

10. **Tampilan Peta**:
   - Menampilkan peta dengan diary-diary yang dimiliki sebagai Pin pada peta tersebut.
   - Pin bisa diklik dan akan muncul informasi singkat diary tersebut.
   - Informasi singkat tersebut bisa diklik dan akan mengarah ke halaman detail diary tersebut.

11. **Profil Pengguna**:
   - Melihat informasi profil pengguna, termasuk gambar profil, dan jumlah diary yang telah dibuat.

12. **Halaman Pengaturan**: 
   - Memungkinkan pengguna untuk mengelola informasi pribadi, termasuk mengganti gambar profil.

13. **Delete**:
   - Memungkinkan pengguna untuk menghapus diary.
   - Diary yang dihapus akan dihapus dari firebase, termasuk gambar yang ada di firestore.

