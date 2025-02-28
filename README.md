Prediksi Restock Produk Menggunakan Decision Tree Classifier

Proyek ini menggunakan Decision Tree Classifier untuk memprediksi apakah suatu produk perlu di-restock berdasarkan data Jumlah Terjual dan Stok. Model ini dilatih dengan dataset yang telah dibersihkan, kemudian dievaluasi menggunakan akurasi. Setelah pelatihan selesai, pengguna dapat memasukkan data produk baru untuk memperoleh prediksi otomatis mengenai kebutuhan restock.
   1. Instalasi Library: Pastikan Anda telah menginstal pustaka yang diperlukan sebelum menjalankan program. Gunakan perintah berikut untuk menginstalnya: pip install pandas scikit-learn.
   2.  Menyiapkan Dataset Siapkan file CSV yang berisi data produk dengan format "sold" dan "stock".
   3.  Bagi Data: Pisahkan data menjadi fitur ("sold", "stock") dan target (apakah stok < 5).
   4.  Latih Model: Gunakan Decision Tree Classifier untuk melatih model dengan data yang sudah dibersihkan.
   5.  Evaluasi: Hitung akurasi model menggunakan data uji.
   6.  Input Pengguna: Masukkan jumlah terjual dan stok produk, kemudian model akan memprediksi apakah produk perlu di restock atau tidak.
   7.  Jalankan: Lakukan prediksi dan tampilkan hasilnya.





      
    
