MAE (Mean Absolute Error) dan MSE (Mean Squared Error) adalah metrik untuk mengukur eror (kesalahan) prediksi model. Nilai MAE dan MSE tidak harus lebih dekat dengan angka 1, melainkan harus sedekat mungkin dengan angka 0. Semakin kecil nilainya (mendekati 0), artinya prediksi model semakin akurat karena erornya semakin sedikit. Sementara itu, R² (R-squared atau Koefisien Determinasi) memiliki aturan yang berbeda. Nilai R² justru harus sedekat mungkin dengan angka 1 (atau 100%) agar model dianggap sangat baik. Berikut adalah penjelasan ringkas untuk masing-masing metrik:

1. MAE (Mean Absolute Error)
- Definisi: Rata-rata dari selisih mutlak (absolut) antara nilai prediksi yang dihasilkan model dan nilai aktual sebenarnya.
- Target Nilai: Mendekati 0**. Semakin kecil nilai MAE, semakin akurat model karena rata-rata selisih kesalahan prediksinya sangat kecil.
- Analogi: Seperti mengukur rata-rata jarak melesetnya lemparan anak panah dari titik tengah papan target. Jika rata-rata melesetnya 0 cm (mendekati 0), artinya setiap lemparan selalu tepat mengenai sasaran.

2. MSE (Mean Squared Error)
- Definisi: Rata-rata dari kuadrat selisih antara nilai prediksi dan nilai aktual. Karena dikuadratkan, MSE memberikan penalti yang jauh lebih berat pada kesalahan prediksi berukuran besar (outlier).
- Target Nilai: Mendekati 0. Semakin mendekati 0, artinya tidak hanya rata-rata kesalahannya kecil, tetapi juga tidak ada kesalahan ekstrem (outlier) yang mencolok.
- Analogi: Seperti sistem denda pelanggaran lalu lintas di mana semakin parah pelanggarannya, hukumannya bertambah secara kuadrat. Jika total skor denda mendekati 0, berarti pengemudi hampir tidak pernah melakukan kesalahan, terutama kesalahan fatal/besar.

. R² (R-squared)
- Definisi: Ukuran statistik yang menunjukkan seberapa besar persentase variansi data target yang berhasil dijelaskan oleh variabel-variabel bebas di dalam model.
- Target Nilai: Mendekati 1 (atau mendekati 100%). Nilai mendekati 1 menandakan bahwa model mampu menjelaskan hampir seluruh pola dan variasi data dengan sangat baik.
- Analogi: Seperti nilai ujian seorang siswa dari skala 0 sampai 1. Jika siswa mendapat skor 1 (atau 100%), artinya siswa tersebut berhasil memahami seluruh materi pelajaran tanpa ada pola soal yang membingungkan.