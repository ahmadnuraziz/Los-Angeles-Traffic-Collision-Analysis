# Los Angeles Traffic Collision Analysis
File data_cleaning.ipynb sebagai proses membersihkan data untuk proses analisis ke Tableau. Lalu file analysis.ipynb berisi analisis dengan python.

### Tools
1. Python
2. Tableau

### Process
1. Gathering
2. Cleaning
3. Exploration
4. Visualization
5. Analysis

### Kesimpulan 
1. Paling banyak kecelakaan terjadi pada STREET (jalanan) dengan persentase ~90%.
2. Korban paling banyak adalah laki-laki.
3. Urutan terbanyak kecelakaan adalah afternoon, morning, evening, night.
4. area paling banyak terjadi kecelakaan adalah 77th Street, Southwest, Wilshire.
5. Paling banyak mengalami kecelakaan adalah orang dewasa (adult), masuk akal karena paling banyak beraktivitas dibanding yang lain.
6. Dari gambar densitas dapat terlihat daerah mana yang mengalami total kecelakaan paling banyak, hal ini dapat digunakan untuk monitoring.
7. Peningkatan total kecelakaan tiap tahun meningkat namun tidak terlalu besar.
8. Dari model, kemungkinan total kecelakaan pada tahun 2020-2021 mencapai 9000 orang laki-laki, dan 6000 orang perempuan.

### Hipotesis Baru
1. Dari file gambar 'memusat menyebar' dapat terlihat kecelakaan memiliki kecenderungan memusat di suatu daerah namun relatif menyebar di daerah lain, kemungkinan adalah karena daerah tersebut memang rawan kecelakaan sehingga cenderung memusat. Hal ini juga bisa saja terjadi karena daerah tersebut padat lalu lintas atau lebih sering dilewati dibanding daerah lain.
2. Kemungkinan lain adalah karena faktor topologi jalan. Daerah dengan kecelakaan yang menyebar dengan memusat berbeda karena topologi jalannya berbeda, terlihat bahwa topologi jalan 'persegi', walaupun banyak simpangan, mempengaruhi tingkat kecelakaan. Berbeda dengan daerah dengan kecelakaan yang memusat, topologi jalannya relatif acak.
3. Kemungkinan lain adalah karena banyaknya jalan alternatif di daerah dengan kecelakaan yang menyebar, akibatnya kendaraan akan lebih tersebar dengan melewati jalanan alternatif.
