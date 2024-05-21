# Pengenalan-Gestur-Tangan-dengan-TensorFlow

## Deskripsi Proyek
Proyek ini bertujuan untuk membangun model pembelajaran mesin yang dapat mengenali gestur tangan seperti batu, kertas, gunting, spock, dan kadal menggunakan TensorFlow.js dan webcam.

## Objective
Tujuan dari proyek ini adalah untuk mengembangkan sebuah model yang mampu mengenali berbagai gestur tangan

## Tools and Methodologies
- **TensorFlow.js**: Library untuk membangun dan melatih model jaringan saraf tiruan.
- **MobileNet**: Model pretrained yang digunakan untuk ekstraksi fitur.
- **Webcam**: Digunakan untuk menangkap gambar gestur tangan secara real-time.
- **RPSDataset**: Kelas untuk mengelola data latih dan label.

## Approach and Process
1. **Persiapan**: Mengatur webcam dan memuat model MobileNet yang telah dilatih sebelumnya.
2. **Pengumpulan Data**: Mengumpulkan contoh gambar gestur tangan dengan berbagai label (batu, kertas, gunting, spock, kadal).
3. **Pembentukan Dataset**: Mengkonversi data yang dikumpulkan menjadi format yang dapat digunakan untuk melatih model.
4. **Pembuatan Model**: Mengkonfigurasi arsitektur model jaringan saraf tiruan dengan menggunakan lapisan-lapisan yang sesuai untuk klasifikasi gambar tangan.
5. **Pelatihan**: Melatih model dengan menggunakan data yang telah dikumpulkan dan optimizer Adam.
6. **Evaluasi**: Mengevaluasi kinerja model dengan menggunakan metrik yang sesuai.
7. **Prediksi**: Mengintegrasikan model dengan aplikasi untuk memprediksi label dari gambar tangan secara real-time.
8. **Optimisasi**: Mengoptimalkan model dan proses pelatihan untuk meningkatkan kinerja dan efisiensi.

## Hasil
- Model yang dilatih dapat mengenali berbagai gestur tangan dengan tingkat akurasi yang memadai.
- Aplikasi yang mengintegrasikan model ini dapat memberikan respons yang cepat dan akurat terhadap gestur tangan pengguna.

## Cara Menjalankan Proyek
1. Clone repositori ini:
   ```bash
   git clone https://github.com/gardakhoerunnisa/repo-name.git
