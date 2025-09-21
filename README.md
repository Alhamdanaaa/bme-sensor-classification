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
bme-sensor-classification/
├── data/
│   └── smart_farm_zoning_dataset.csv  # Dataset utama
│
├── notebooks/
│   ├── exploration.ipynb              # Notebook untuk eksplorasi data
│   ├── knn_notebook.ipynb             # Notebook untuk training dan evaluasi model KNN
│   ├── tflite_smart_farm_model.h5     # Model yang dilatih (format H5)
│   ├── tflite_smart_farm_model.tflite # Model yang dikonversi ke TensorFlow Lite
│   └── tfliteSmartFarm.ipynb          # Notebook untuk konversi model ke TFLite
│
├── requirements.txt                   # Daftar dependensi Python
└── README.md                          # Berkas ini
