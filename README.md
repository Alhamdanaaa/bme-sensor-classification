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
│── data/
│ └── smart_farm_zoning_dataset.csv # Dataset utama
│
│── notebooks/
│ ├── exploration.ipynb # Eksplorasi dataset
│ ├── knn_notebook.ipynb # Training & evaluasi model KNN
│ ├── KNNModel.py # Implementasi model KNN dalam Python
│ ├── KNNSmartFarm.ipynb # Eksperimen tambahan KNN
│ ├── knn_model_smart_farm.pkl # Model KNN terlatih (pickle)
│ ├── tflite_smart_farm_model.h5 # Model format H5 (TensorFlow)
│ ├── tflite_smart_farm_model.tflite # Model format TensorFlow Lite
│ └── tfliteSmartFarm.ipynb # Notebook untuk konversi & uji TFLite
│
│── requirements.txt # Dependencies Python
