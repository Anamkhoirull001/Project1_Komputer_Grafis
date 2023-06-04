# Visualisasi Data Mini Project 1
Hallo perkenalkan saya ***Khoirul Anam*** dalam repo ini berisi tugas project 1 dari matakuliah komputer grafis tahun 2023 terkhusus
untuk ***Bu RASTRI PRATHIVI, S.Kom., M.Kom*** bisa langsung kujungi link dibawah untuk mempermudah penilaian, terspesial untuk anda
dapat juga bisa langsung kunjungi akun **google colab** saya pada link https://colab.research.google.com/drive/1fxzmpVRgrf-13PXQ1PRuh2HmsK0MVbvV?usp=sharing 
untuk melihat lengkap kodingan berserta semua  instruksinya

***1: Menentukan brand top 5***
Lakukan analisis untuk top brands di bulan Desember 2019, di bawah ini adalah beberapa hal yang perlu
dilakukan. Silahkan ditambahkan dengan visualisasi-visualisasi lain yang kira-kira dapat memberikan insight
tambahan.

***Case 1:***
Buat variabel baru (e.g. dataset_top5brand_dec) yang berisi data penjualan bulan Desember 2019, hanya
untuk top 5 brand dengan quantity terjual terbanyak selama bulan Desember 2019. Sebutkan top 5 brands
tersebut! Untuk visualisasi-visualisasi selanjutnya, hanya gunakan data frame ini.

***Case 2: Multi-line chart daily quantity untuk brand top 5***
Buat visualisasi multi-line chart untuk daily quantity terjualnya, breakdown per brand. Maka, akan terlihat 1
tanggal di mana ada salah satu brand yang mengalami lonjakan (quantity lebih tinggi dari tanggal-tanggal lain).
Beri anotasi untuk titik lonjakan tersebut.

***Case 3:***
Cari tahu jumlah product untuk masing-masing brand yang laku selama bulan Desember 2019. Gunakan
barchart untuk visualisasinya, urutkan dengan yang kiri adalah brand dengan product lebih banyak.
***Case 4: Penjualan produk diatas 100 dan dibawah 100 selama Desember 2019***
Gunakan stacked chart, untuk breakdown barchart yang di Case 3, antara product yang terjual >= 100 dan < 100 di
bulan Desember 2019. Apakah ada pola yang menarik

***Case 5: Murah atau mahalkah harga produk brand top 5***
Gunakan histogram untuk melihat distribusi harga product-product yang ada di top 5 brand tersebut (untuk tiap
product_id, ambil median harganya). Bagaimana persebaran harga product nya? Cenderung banyak yang murah
atau yang mahal?

***Case 6a: Korelasi quantity vs GMV***
Untuk setiap product_id, cek scatterplot antara quantity dan GMV, apakah ada korelasi? Bagaimana dengan
median harga vs quantity? Apakah product yang murah cenderung dibeli lebih banyak?

****Case 6b: Korelasi median harga vs quantity***
Untuk setiap product_id, cek scatterplot antara quantity dan GMV sudah kamu lakukan pada Case 6a? Untuk Case
6b ini bagaimanakah dengan median harga vs quantity? Apakah product yang murah cenderung dibeli lebih
banyak?

Kesimpulan Case Study:

**Dapat disimpulkan bahwa dari kelima top brand, brand S memiliki kuantitas top brands yang paling besar sebesar 2.197. Kemudian,
Lonjakan yang cukup drastis ditunjukkan oleh brand P pada tanggal 6 Desember 2019 sebesar 300. Dimana lonjakan ini lebih tinggi
sehingga perlu diberikan anotasi. Kemudian, dilihat dari sisi kuantitas produk yang laku terjual, brand S lebih banyak kuantitasnya.
Berdasarkan stacked bar-chart top 5 brands, terdapat pola yang menarik. Brand S lebih banyak menjual kuantitas produknya dibawah 100. Sedangkan, brand P lebih banyak menjual kuantitas lebih dari sama dengan 100. Terdapat hubungan positif antara kuantitas dengan
GMV yang artinya semakin banyak customer yang membeli produk dalam jumlah yang besar, dapat disimpulkan GMV yang dihasilkan
juga akan semakin besar. Terdapat hubungan pula antara median harga dengan kuantitas produk. Hal tersebut berkorelasi positif yang
artinya bahwa semakin murah harga suatu produk maka customer berpeluang besar untuk membeli jumlah produk dengan jumlah yang
banyak.**


