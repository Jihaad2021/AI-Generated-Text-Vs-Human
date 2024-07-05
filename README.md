# AI-Generated-Text-Vs-Human-Text

## Gambaran Proyek
Perkembangan Artificial Intelligence (AI) yang semakin pesat menuntut kita untuk mampu membedakan teks buatan AI dengan teks buatan manusia. Hal ini penting terutama dalam konteks keamanan, kredibilitas informasi, dan identifikasi plagiarisme. Proyek ini bertujuan untuk mengembangkan model yang dapat secara efektif membedakan antara teks yang dihasilkan oleh AI dan teks yang ditulis oleh manusia. Dengan memanfaatkan kombinasi model RNN dan berbagai teknik pra-pemrosesan, proyek ini bertujuan untuk mencapai akurasi tinggi dalam klasifikasi teks.

## Tujuan
- Untuk membedakan antara teks buatan AI dan teks buatan manusia.
- Untuk mengevaluasi kinerja berbagai model jaringan saraf dalam tugas klasifikasi ini.
- Untuk menilai dampak dari berbagai teknik pra-pemrosesan teks terhadap kinerja model.

## Model yang Digunakan
- Long Short-Term Memory (LSTM)
- Gated Recurrent Unit (GRU)
- Bidirectional LSTM (BiLSTM)
- Bidirectional GRU (BiGRU)
- Kombinasi LSTM-GRU
- Kombinasi BiLSTM-BiGRU

## Teknik Pra-pemrosesan
- Konversi ke Huruf Kecil: Mengubah semua karakter menjadi huruf kecil.
- Menghapus Angka dan Tanda Baca: Menghilangkan angka dan tanda baca.
- Penghapusan Stopword: Menyaring stopword umum.

## Eksperimen
Pada setiap model dilakukan 3 jenis eksperimen pra-pemrosesan text
- Eksperimen 1: Tanpa pra-pemrosesan
- Eksperimen 2: Konversi ke Huruf Kecil, Menghapus Angka dan Tanda Baca
- Eksperimen 3: Konversi ke Huruf Kecil, Menghapus Angka, Tanda Baca dan Stopword

## Metodologi
- Pengumpulan Data: Dataset yang digunakan berasal dari kompetisi ALTA Shared Task, dengan 18.000 data training dan 2.000 data testing 
- Pra-pemrosesan Data: Menerapkan teknik pra-pemrosesan untuk membersihkan dan menormalisasi data teks.
- Pelatihan Model: Melatih setiap model (LSTM, GRU, BiLSTM, BiGRU, LSTM-GUR, BiLSTM-BiGRU) pada data yang telah diproses.
- Evaluasi Model: Mengevaluasi model menggunakan metriks akurasi dari website ALTA Shared Task.

## Hasil
| Model | Eksperimen 1 | Eksperimen 2 | Eksperimen 3 |
| --- | --- | --- | --- |
| LSTM | **94.75** | **95.05** | 92.70 |
| GRU | 93.35 | 93.65 | **93.70** |
| LSTM-GRU | 92.85 |93.05 | 93.20 |
| BiLSTM | 93.55 | 92.95 | 93.30 |
| BiGRU | 93.55 | 93.15 | 92.45 |
| BiLSTM-BiGRU | 93.80 | 93.55 |93. 55 |


- Model LSTM mencapai akurasi tertinggi sebesar 95.05% saat teknik pra-pemrosesan konversi ke huruf kecil, menghapus angka, dan menghapus tanda baca diterapkan.
- Model lain juga menunjukkan kinerja yang signifikan, namun model LSTM memiliki performa yang lebih unggul dalam hal akurasi.

## Kesimpulan
Proyek ini berhasil mengembangkan model yang kuat untuk membedakan teks buatan AI dengan teks buatan manusia. Model LSTM, dikombinasikan dengan teknik pra-pemrosesan yang efektif, menunjukkan kinerja yang superior dengan mencapai akurasi sebesar 95.05%.

