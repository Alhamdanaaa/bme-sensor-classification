# 🌱 BME Sensor Classification  

Proyek ini membangun model machine learning untuk **klasifikasi kondisi lingkungan** menggunakan dataset dari sensor BME (misalnya BME280/BME680). Dataset yang digunakan berupa data **Smart Farm Zoning** yang berisi parameter lingkungan seperti suhu, kelembapan, dan tekanan udara.  

---

## 📌 Tujuan  
- Melakukan eksplorasi dan preprocessing dataset smart farm.  
- Membangun model klasifikasi menggunakan algoritma KNN.  
- Mengonversi model ke format **TensorFlow Lite** agar bisa digunakan pada perangkat IoT.  
- Mengevaluasi performa model dengan metrik machine learning.  

---

## 📂 Struktur Repository  
```bash
bme-sensor-classification/
├── data/
│   └── smart_farm_zoning_dataset.csv  # Dataset utama untuk proyek
│
├── notebooks/
│   ├── exploration.ipynb              # Notebook untuk eksplorasi dan analisis data
│   ├── knn_notebook.ipynb             # Notebook utama untuk training & evaluasi model KNN
│   ├── KNNSmartFarm.ipynb             # Notebook eksperimen tambahan dengan model KNN dan pipeline
│   ├── KNNModel.py                    # Implementasi kelas model KNN
│   ├── knn_model_smart_farm.pkl       # Model KNN yang sudah dilatih (format pickle)
│   ├── tfliteSmartFarm.ipynb          # Notebook untuk proses konversi model ke TFLite
│   ├── tflite_smart_farm_model.h5     # Model yang sudah dilatih (dalam format H5)
│   └── tflite_smart_farm_model.tflite # Model yang dikonversi ke TensorFlow Lite
│
├── requirements.txt                   # Daftar dependensi Python yang dibutuhkan
└── README.md                          # Berkas ini
