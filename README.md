**Kuis Interaktif Mekanika Tanah Berdasarkan Buku Principle of Geotechnic Engineering - Braja M. DAS**
========================================================

**1\. Pendahuluan**
-------------------

Selamat datang di Web Aplikasi Kuis Interaktif Mekanika Tanah. Aplikasi ini dirancang sebagai alat bantu belajar dan evaluasi yang dinamis bagi para mahasiswa, praktisi, dan siapa saja yang tertarik dengan bidang rekayasa geoteknik.

Akses aplikasi di [https://kuismektanbraja.isparmo.com/](https://kuismektanbraja.isparmo.com/)

Tujuan utama dari aplikasi ini adalah untuk menyediakan platform kuis yang tidak statis. Berbeda dengan kuis konvensional, aplikasi ini menggunakan kekuatan **Google Gemini API** untuk menghasilkan soal-soal yang selalu baru dan relevan setiap kali sesi kuis dimulai. Materi soal dibuat berdasarkan referensi dari buku **"Principles of Geotechnical Engineering" karya Braja M. Das**, mencakup 17 bab utama dalam ilmu mekanika tanah.

**2\. Fitur Utama**
-------------------

Aplikasi ini dilengkapi dengan berbagai fitur untuk memberikan pengalaman yang interaktif dan informatif.

#### **a. Kuis Dinamis Berbasis AI**

Setiap kali pengguna memulai kuis baru, aplikasi akan mengirim permintaan ke Google Gemini untuk membuat satu set soal yang unik berdasarkan topik yang dipilih. Ini memastikan bahwa pengguna tidak akan mendapatkan soal yang sama berulang kali, sehingga proses belajar menjadi lebih efektif.

#### **b. Input Data Pengguna**

Sebelum memulai kuis, pengguna diwajibkan untuk mengisi data diri yang meliputi:

*   Nama Lengkap
    
*   Instansi/Perusahaan
    
*   Email
    
*   No. Telepon/WA
    

Data ini digunakan untuk personalisasi hasil akhir kuis.

#### **c. Pemilihan Topik Kuis yang Fleksibel**

Pengguna memiliki kebebasan penuh untuk memilih materi yang akan diujikan. Terdapat 17 topik yang sesuai dengan bab-bab dalam buku referensi. Pengguna dapat memilih satu, beberapa, atau semua topik sekaligus dengan mencentang kotak **"Pilih Semua Topik"**.

#### **d. Kustomisasi Jumlah Soal**

Pengguna dapat menentukan jumlah soal yang diinginkan untuk setiap sesi kuis, dengan pilihan 5, 10, 15, atau memasukkan jumlah soal secara manual.

#### **e. Penilaian dan Level Keahlian**

Setelah kuis selesai, aplikasi akan secara otomatis menghitung skor dalam bentuk persentase (tanpa tanda %) dan memberikan level keahlian berdasarkan rentang nilai berikut:

*   **0 - 50:** Engineer Pemula
    
*   **51 - 70:** Engineer Biasa
    
*   **71 - 100:** Engineer Ahli
    

#### **f. Umpan Balik dan Penjelasan Instan**

Setiap kali menjawab pertanyaan, pengguna akan langsung menerima notifikasi **BENAR** atau **SALAH**. Jika jawaban salah, akan muncul kotak penjelasan dari "Ahli Geoteknik" (yang dihasilkan oleh AI) untuk memberikan pemahaman yang lebih dalam mengenai konsep yang diujikan.

#### **g. Tinjauan Jawaban**

Pada halaman hasil, pengguna dapat meninjau kembali semua soal, jawaban yang mereka berikan, jawaban yang benar, serta penjelasan untuk setiap soal yang dijawab salah.

#### **h. Fitur "Tanya Ahli"**

Jika ada pertanyaan lebih lanjut setelah melihat hasil, pengguna dapat menggunakan tombol melayang **"Tanya Ahli"**. Fitur ini akan membuka jendela _pop-up_ di mana pengguna bisa mengetik pertanyaan apa pun terkait geoteknik. Pertanyaan tersebut akan dijawab langsung oleh Gemini, dengan jawaban yang ditampilkan dalam format _rich text_ (mendukung teks tebal, daftar, dll.) dan dilengkapi dengan _scrollbar_ jika jawabannya panjang.

#### **i. Unduh Hasil (CSV)**

Pengguna dapat mengunduh ringkasan hasil kuis mereka dalam format file .csv. File ini berisi data diri yang telah diisi beserta skor dan level keahlian yang dicapai. File CSV ini kompatibel dengan Microsoft Excel dan Google Sheets.

**3\. Cara Menggunakan Aplikasi**
---------------------------------

Berikut adalah panduan langkah demi langkah untuk menggunakan aplikasi kuis.

1.  **Mengisi Data Diri dan Kunci API**
    

*   Buka aplikasi. Anda akan disambut oleh halaman awal.
    
*   Isi semua kolom data diri yang tersedia.
    
*   Masukkan **Kunci API Gemini** Anda. Jika Anda belum memilikinya, ikuti petunjuk yang tersedia di bawah kolom input untuk mendapatkannya dari Google AI Studio. Semua kolom wajib diisi.
    

1.  **Memilih Jumlah Soal**
    

*   Pilih jumlah soal yang Anda inginkan dengan mengklik salah satu opsi radio (5, 10, atau 15).
    
*   Jika Anda ingin jumlah soal yang berbeda, pilih opsi terakhir dan ketikkan angka yang Anda inginkan di kolom yang tersedia.
    

1.  **Memilih Topik Kuis**
    

*   Di bawah bagian jumlah soal, Anda akan menemukan daftar 17 topik.
    
*   Centang kotak di sebelah topik yang ingin Anda ujikan. Anda harus memilih minimal satu topik.
    
*   Untuk menguji semua materi, cukup centang kotak **"Pilih Semua Topik"**.
    

1.  **Memulai Kuis**
    

*   Setelah semua data dan pilihan terisi, klik tombol **"Mulai Kuis"**.
    
*   Aplikasi akan menampilkan layar pemuatan sementara Gemini menghasilkan soal untuk Anda.
    

1.  **Menjawab Pertanyaan**
    

*   Soal akan ditampilkan satu per satu.
    
*   Baca pertanyaan dengan saksama, lalu klik pada salah satu pilihan jawaban (a, b, c, atau d).
    
*   Setelah Anda memilih jawaban, semua pilihan akan dinonaktifkan, dan umpan balik (BENAR/SALAH) akan muncul. Jika jawaban salah, penjelasan akan ditampilkan.
    
*   Klik tombol **"Lanjut"** untuk beralih ke soal berikutnya.
    

1.  **Melihat Hasil Akhir**
    

*   Setelah semua soal terjawab, Anda akan diarahkan ke halaman hasil.
    
*   Di sini, Anda akan melihat skor akhir, level keahlian, dan ringkasan tinjauan jawaban Anda.
    

1.  **Menggunakan Fitur Tambahan**
    

*   **Unduh Hasil:** Klik tombol **"Unduh (CSV)"** untuk menyimpan data dan hasil kuis Anda.
    
*   **Tanya Ahli:** Klik tombol melayang ungu di pojok kanan bawah untuk bertanya langsung kepada AI.
    
*   **Coba Lagi:** Klik tombol **"Coba Lagi"** untuk kembali ke halaman awal dan memulai sesi kuis yang baru dan dinamis.
    

**4\. Catatan Teknis**
----------------------

*   **Kunci API Gemini:** Aplikasi ini memerlukan kunci API yang valid dari Google AI Studio untuk dapat berfungsi. Kunci API ini bersifat rahasia dan hanya digunakan selama sesi kuis untuk berkomunikasi dengan model AI.
    
*   **Koneksi Internet:** Diperlukan koneksi internet yang stabil untuk menghasilkan soal dan menggunakan fitur "Tanya Ahli".
