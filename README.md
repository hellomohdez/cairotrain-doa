# Projek Latihan AI untuk Pertanian Bersama CAIRO UTMKL

🚜💡 **Aplikasi Kecerdasan Buatan (AI) dalam Pertanian Pintar**  
Projek ini merupakan hasil kolaborasi latihan AI bersama [CAIRO UTMKL](https://utm.my/cairo/) yang memfokuskan kepada pembangunan penyelesaian AI untuk sektor pertanian. Ia bertujuan menyelesaikan isu-isu sebenar dalam bidang agro-teknologi dengan menggunakan teknik Machine Learning, Computer Vision, dan sistem IoT pintar.

---

## 🎯 Objektif Projek

- Membangunkan model AI yang berupaya mengenal pasti keadaan kesihatan tanaman secara automatik.
- Menggunakan pembelajaran mesin (ML) untuk ramalan hasil tuaian dan pengesanan penyakit tanaman.
- Membina prototaip sistem pengurusan ladang berasaskan data (data-driven farming).
- Menerapkan teknologi AI dalam amalan pertanian mampan.

---

## 🧠 Teknologi dan Perpustakaan

- Python 3.x
- TensorFlow / PyTorch
- OpenCV
- Scikit-learn
- FastAPI / Flask (untuk deployment API)
- Arduino/Raspberry Pi (untuk integrasi IoT jika berkaitan)

---

## 🗂️ Struktur Repositori

```bash
├── data/                   # Dataset latih & uji
├── notebooks/              # Fail Jupyter Notebook untuk analisis & training model
├── src/                    # Kod sumber model AI dan pipeline
│   ├── preprocessing/      # Kod pembersihan dan penyediaan data
│   ├── models/             # Arkitek dan training model
│   └── inference/          # Kod untuk inference dan integrasi dengan API
├── api/                    # REST API untuk deployment model
├── images/                 # Visualisasi hasil model
├── tests/                  # Ujian model dan API
├── requirements.txt        # Keperluan pustaka Python
└── README.md               # Dokumentasi projek

