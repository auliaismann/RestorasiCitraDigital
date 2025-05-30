# RestorasiCitraDigital

---

# 🖼️ Image Deblurring using Lucy-Richardson and Wiener Filter


## 📌 Deskripsi

Program ini merupakan aplikasi sederhana berbasis Python yang bertujuan untuk melakukan **restorasi citra buram (blurred image)** menggunakan dua metode deblurring populer, yaitu:

* **Lucy-Richardson Deconvolution** (iteratif),
* **Wiener Filter** (frekuensi domain).

Program ini berjalan di lingkungan **Google Colab**, menggunakan pustaka seperti OpenCV, NumPy, SciPy, dan Matplotlib.

---

## ⚙️ Fitur Utama

* Upload gambar buram (format `.jpg` / `.png`) melalui Google Colab.
* Deblurring menggunakan algoritma Lucy-Richardson.
* Deblurring menggunakan Wiener Filter.
* Perbandingan hasil berdasarkan nilai **PSNR** (Peak Signal to Noise Ratio).
* Visualisasi hasil deblurring secara berdampingan (input, hasil Lucy, hasil Wiener).

---

## 🛠️ Teknologi & Pustaka yang Digunakan

* Python 3.x
* Google Colab
* [OpenCV](https://opencv.org/)
* NumPy
* SciPy
* Matplotlib
* `skimage.metrics` untuk PSNR

---

## 🚀 Cara Menjalankan Program

1. Buka Google Colab dan unggah notebook `.ipynb` yang berjudul:
   **`D121221044_Aulia_Khairunnisa_Isman__Tugas_Besar_Visi_Komputer.ipynb`**
2. Jalankan semua sel secara berurutan.
3. Ketika diminta, upload gambar buram yang ingin direstorasi.
4. Program akan menampilkan:

   * Gambar asli buram,
   * Hasil deblurring Lucy-Richardson,
   * Hasil deblurring Wiener Filter,
   * Nilai PSNR dari masing-masing metode.

---

## 📈 Contoh Output

```text
PSNR Lucy-Richardson: 18.65 dB  
PSNR Wiener Filter: 16.02 dB  
```

Gambar hasil ditampilkan dalam 3 kolom:

* Gambar Buram
* Hasil Lucy-Richardson
* Hasil Wiener Filter

---

## 📊 Evaluasi

* **Lucy-Richardson** lebih unggul dalam ketajaman dan detail visual.
* **Wiener Filter** lebih cepat namun kurang tajam.
* PSNR digunakan sebagai metrik pembanding kualitas hasil restorasi.

---

## 👩‍💻 Penulis

**Aulia Khairunnisa Isman**
Universitas Hasanuddin
Program Studi Teknik Informatika
Tugas Besar Mata Kuliah Visi Komputer

---

## 📝 Lisensi

Proyek ini dibuat untuk keperluan akademik. Bebas digunakan untuk pembelajaran dan pengembangan lanjutan dengan mencantumkan atribusi yang sesuai.

