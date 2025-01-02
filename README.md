# Pneumonia Detection Using CNN  

Proyek ini bertujuan untuk mendeteksi pneumonia dari citra X-ray menggunakan Convolutional Neural Network (CNN). Model dikembangkan menggunakan dataset Chest X-Ray Images (Pneumonia) dan dievaluasi untuk memastikan performanya dalam mendeteksi kondisi kesehatan paru-paru.  

---

## Tautan Penting  
- **Dataset**: [Chest X-Ray Images (Pneumonia)](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)  
- **Model yang Telah Dilatih**: [pneumonia_cnn.h5](https://drive.google.com/file/d/1l27iOAa1za2CPkKn73cPDC5R9-kGPYbk/view?usp=sharing)  

---

## Persyaratan Sistem  

Proyek ini menggunakan versi spesifik dari pustaka berikut untuk memastikan kompatibilitas:  
- **Python**: 3.10.16  
- **TensorFlow**: 2.10.0  
- **NumPy**: 1.26.4  
- **Pandas**: 2.2.3  
- **Matplotlib**: 3.10.0  
- **Keras**: 2.10.0  

Pastikan Anda memiliki semua pustaka ini sebelum menjalankan notebook.  

---

## Cara Menjalankan Program  

### 1. Persiapkan Dataset  
- Buat folder bernama `dataset` di lokasi yang sama dengan notebook `pneumonia_cnn.ipynb`.  
- Unduh dataset dari tautan di atas dan simpan di folder `dataset`.  
- Ubah nama file ZIP menjadi `chest_xray.zip` setelah berhasil diunduh.  

### 2. Struktur Folder  
Pastikan struktur folder Anda seperti berikut:  
```plaintext
dataset/
  chest_xray.zip
pneumonia_cnn.ipynb
```  

### 3. Jalankan Notebook  
- Buka file `pneumonia_cnn.ipynb` menggunakan Jupyter Notebook atau editor yang mendukung Jupyter (seperti VSCode).  
- Jalankan setiap sel dalam notebook secara berurut dari awal hingga akhir.  

---

## Catatan Tambahan  

- **Perubahan Topik**:  
  Topik proyek ini berubah dari rencana awal karena terdapat error dan ketidakcocokan pustaka pada topik sebelumnya.  

- **Model Tidak Disimpan di Repository**:  
  Model yang sudah dilatih tidak disimpan di GitHub karena ukurannya melebihi batas upload GitHub (25MB). Anda dapat mengunduh dataset dari tautan yang disediakan untuk melatih model ulang.  

- **Kinerja Model**:  
  Untuk hasil evaluasi model dapat ditemukan di notebook `pneumonia_cnn.ipynb`.
