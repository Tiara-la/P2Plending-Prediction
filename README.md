# Sistem-P2P-Lending-Pred

Implementasi sistem pada penelitian ini menggunakan framework Streamlit dan environment pada python.  
 
 
Gambar 4.19. Tampilan Halaman Home

Gambar 4.19 merupakan halaman Home dari web prediksi risiko gagal bayar pinjaman dimana pengguna dapat melihat informasi tentang web ini. Selain menu Home, pada bagian samping terdapat menu sidebar yang berisi menu Manual Input dan CSV Input. Tampilan menu Manual Input dapat dilihat pada Gambar 4.20.
 
Gambar 4.20. Tampilan Menu Manual Input
Pada menu Manual Input pengguna dapat melakukan prediksi dengan meng-input data secara manual satu persatu. Ada 3 data yang harus dimasukan sesuai dengan hasil seleksi fitur yang telah dilakukan sebelumnya. Data-data yang perlu pengguna input-kan adalah day past due, principal balance dan principal paid.
Setelah data dimasukan satu persatu, selanjutnya pengguna bisa menekan button “Predict” untuk mendapat hasil prediksi. Ketika pinjaman masuk kategori default maka akan muncul hasil berupa tulisan “Prediksi pinjaman ini adalah Default”. Namun jika pinjaman masuk kategori non-default makan akan muncul hasil berupa tulisan “Prediksi pinjaman ini adalah Non-Default”. Tampilan hasil prediksi dapat dilihat pada Gambar 4.21.
 
 
 
Gambar 4.21. Tampilan Hasil Prediksi pada Menu Manual Input

Kemudian pada bagian menu CSV Input pengguna dapat melakukan prediksi dengan banyak data sekaligus. Data yang dapat di-input-kan berformat csv. Caranya yaitu dengan meng-upload data yang berformat csv pada bagian Drag and drop file. Tampilan dari menu CSV Input dapat dilihat pada Gambar 4.22.
 
Gambar 4.22. Tampilan Menu CSV Input
Setelah data ter-upload, sistem akan otomatis mambaca file dan akan menampilkan tampilan file yang telah di-upload dan pengguna dapat langsung melakukan prediksi dengan menekan button “Predict”. Tampilan ketika data telah terbaca oleh sistem dapat dilihat pada Gambar 4.23.
 
Gambar 4.23. Tampilan Ketika Data Telah Terbaca Sistem
Proses prediksi akan berlangsung beberapa saat, hingga muncul tampilan data dengan kolom baru yaitu y_pred yang merupakan hasil prediksi dari data yang berisi kelas 0 dan 1. Tampilan dari hasil prediksi pada menu CSV Input dapat dilihat pada Gambar 4.24.
 
Gambar 4.24. Tampilan Hasil Prediksi pada Menu CSV Input
Setelah hasil prediksi keluar, pengguna juga dapat melihat visualisasi jumlah dan perbandingan dari jumlah kelas prediksi untuk memudahkan pengguna dalam melihat perbandingan jumlah data default dengan non-default. Tampilan dari hasil visualisasi hasil prediksi dapat dilihat pada Gambar 4.25. 
 
Gambar 4.25. Visualisasi Hasil Prediksi
