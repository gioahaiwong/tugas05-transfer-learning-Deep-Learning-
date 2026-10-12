# tugas05-transfer-learning-Deep-Learning-
Berikut adalah tugas GSLC Deep Learning mengenai pembelajaran tentang Transfer Learning + advanced CNN.
Tugas 05 — Transfer Learning untuk Klasifikasi Citra (Deep Learning)

Deskripsi
Eksperimen komparatif transfer learning untuk menbgklasifikasi 10 ras kucing
& anjing (Oxford-IIIT Pet) dengan menggunakan model ResNet-18 dan EfficientNet-B0.

Kondisi Eksperimen
- B1: From scratch
- B2: Feature extraction
- B3: Fine-tune layer4
- B4: Fine-tune layer4 + augmentasi
- B5: EfficientNet-B0 + augmentasi

Hasil
| Kondisi | Test Acc | Macro F1 |

| B1      | 38.26%   | 36.80% |
| B2      | 94.30%   | 94.35% |
| B3      | 94.30%   | 94.29% |
| B4      | 93.29%   | 93.30% |
| B5      | 93.62%   | 93.59% |

 Cara Menjalankan kodenya
1. Buka notebook di Google Colab.
2. Runtime → Change runtime type → T4 GPU.(Agar lebih cepat komputasinya)
3. Run all cells.(Membutuhkan lebih dari 10 menit untuk menyelesaikan semuanya)

Struktur File
- Tugas05_2802463812_gIOVAN.ipynb — notebook Utama untuk kode pythonnya sendii
- log_*.json — log mentah per kondisi tertentu
- consolidated_results.csv — tabel konsolidasi
- *.png — visualisasi gambar

Referensi
- Slide Sesi 05 — Advanced CNNs and Transfer Learning
- [PyTorch Documentation](https://pytorch.org/docs/)
-Deepseek and Gemini
