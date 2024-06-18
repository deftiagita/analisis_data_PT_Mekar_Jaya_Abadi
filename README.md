# analisis_data_PT_Mekar_Jaya_Abadi

##Tentang Perusahaan
#PT. Mekar Jaya Abadi adalah sebuah perusahaan dagang yang bergerak di bidang distribusi produk elektronik dan peralatan rumah tangga. Selama lima tahun terakhir, perusahaan ini telah mengalami pertumbuhan signifikan namun juga menghadapi berbagai tantangan dalam operasionalnya. Manajemen ingin memahami lebih dalam mengenai performa penjualan dan faktor-faktor yang mempengaruhinya untuk mengambil keputusan yang lebih tepat dan strategis di masa depan.

##Visualisasi dan Interpretasi
#1)	Tren Penjualan dari Waktu ke Waktu
    ![Figure_1](https://github.com/deftiagita/analisis_data_PT_Mekar_Jaya_Abadi/assets/167218696/4035151e-52c1-480c-86e8-f97866548ec6)
Gambar di atas menunjukkan tren penjualan total dari waktu ke waktu. Dari grafik tersebut, dapat diideentifikasi pola musiman, tren jangka panjang, serta fluktuasi penjualan harian. Misalnya, terlihat lonjakan penjualan selama periode liburan atau penurunan selama musim tertentu. 
Dengan mengamati tren penjualan dari waktu ke waktu, dapat dipahami pola musiman dan fluktuasi jangka panjang. Yakni, jika ada lonjakan penjualan di akhir tahun atau penurunan penjualan pada musim hujan, hal ini bisa memberikan wawasan penting untuk strategi pemasaran dan manajemen stok.

2)	Matriks Korelasi
   ![Figure_2](https://github.com/deftiagita/analisis_data_PT_Mekar_Jaya_Abadi/assets/167218696/2eed3f17-b6a4-4e54-98a8-40804f87a719)
Matriks korelasi ini menggambarkan hubungan antara variabel-variabel dalam dataset. Nilai korelasi berkisar dari -1 hingga 1, di mana:
•	Nilai 1 menunjukkan korelasi positif yang sempurna.
•	Nilai -1 menunjukkan korelasi negatif yang sempurna.
•	Nilai 0 menunjukkan tidak ada korelasi.
Dari matriks ini, dapat dilihat variabel mana yang paling berkorelasi dengan penjualan total, seperti harga per unit, jumlah unit terjual, atau variabel ekonomi seperti inflasi.
Korelasi antara variabel membantu perusahaan mengidentifikasi hubungan penting yang mungkin tidak terlihat secara langsung. Misalnya, jika ada korelasi tinggi antara ketersediaan stok dan total penjualan, perusahaan harus memastikan bahwa stok selalu cukup tersedia untuk menghindari kehilangan penjualan.

3)	Pentingnya Fitur
   ![Figure_3](https://github.com/deftiagita/analisis_data_PT_Mekar_Jaya_Abadi/assets/167218696/ab45edf8-de6b-4a20-ad24-6dcb690bd54c)
Gambar di atas menampilkan pentingnya setiap fitur dalam model prediksi penjualan yang dibangun menggunakan Random Forest Regressor. Fitur dengan nilai penting yang lebih tinggi memiliki pengaruh yang lebih besar terhadap prediksi penjualan total. Dari grafik tersebut, dapat dilihat variabel mana yang paling berkontribusi terhadap model prediksi, seperti jenis promosi, harga per unit, atau ketersediaan stok.
Analisis pentingnya fitur membantu kita memahami variabel mana yang paling mempengaruhi penjualan. Jika harga produk memiliki pengaruh besar, perusahaan dapat fokus pada strategi penetapan harga untuk meningkatkan penjualan. Jika promosi tertentu menunjukkan dampak besar, itu bisa menjadi area fokus untuk kampanye pemasaran.


