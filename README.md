# AI-Generated-Text-Vs-Human

## Gambaran Proyek
Proyek ini bertujuan untuk mengembangkan model yang dapat secara efektif membedakan antara teks yang dihasilkan oleh AI dan teks yang ditulis oleh manusia. Dengan memanfaatkan kombinasi model RNN dan berbagai teknik pra-pemrosesan, proyek ini bertujuan untuk mencapai akurasi tinggi dalam klasifikasi teks.

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

## Metodologi
- Pengumpulan Data: Mengumpulkan dataset yang seimbang yang terdiri dari teks buatan AI dan teks buatan manusia.
- Pra-pemrosesan Data: Menerapkan teknik pra-pemrosesan untuk membersihkan dan menormalisasi data teks.
- Pelatihan Model: Melatih setiap model (LSTM, GRU, BiLSTM, BiGRU, LSTM-GUR, BiLSTM-BiGRU) pada data yang telah diproses.
- Evaluasi Model: Mengevaluasi model berdasarkan akurasi, presisi, recall, dan skor F1.

## Hasil
- Model LSTM mencapai akurasi tertinggi sebesar 96% saat teknik pra-pemrosesan konversi ke huruf kecil, menghapus angka, dan menghapus tanda baca diterapkan.
- Model lain juga menunjukkan kinerja yang signifikan, namun model LSTM memiliki performa yang lebih unggul dalam hal akurasi.

## Kesimpulan
Proyek ini berhasil mengembangkan model yang kuat untuk membedakan teks buatan AI dengan teks buatan manusia. Model LSTM, dikombinasikan dengan teknik pra-pemrosesan yang efektif, menunjukkan kinerja yang superior dengan mencapai akurasi sebesar 96%.

