
# 📊 Visualisasi Dataset Iris

Notebook Jupyter ini menyediakan visualisasi sederhana dan intuitif dari **dataset Iris** menggunakan alat-alat dari ekosistem data science Python.

## 📁 Berkas: `Untitled4.ipynb`

## 🧰 Ketergantungan

Pastikan Anda telah menginstal paket-paket Python berikut:

```bash
pip install pandas seaborn matplotlib scikit-learn
```

## 📌 Fitur

1. **Memuat Dataset Iris**  
   Menggunakan `sklearn.datasets.load_iris`, dataset dimuat ke dalam DataFrame Pandas untuk mempermudah manipulasi data.

2. **Visualisasi Pair Plot**  
   Menggunakan `seaborn.pairplot` untuk memvisualisasikan hubungan pasangan antar fitur, diwarnai berdasarkan spesies (target).

3. **Visualisasi PCA 3D**  
   Menerapkan Analisis Komponen Utama (PCA) untuk mereduksi dimensi data menjadi 3D dan memvisualisasikannya menggunakan plot sebar 3D dari `matplotlib`.

   - Sumbu mewakili tiga komponen utama pertama.
   - Titik-titik diwarnai berdasarkan kelas target (spesies).
   - Termasuk legenda yang menunjukkan label kelas.

## 📸 Contoh Output

- **Pair Plot:**  
  Membantu memahami korelasi dan pemisahan antar kelas.

- **Plot PCA 3D:**  
  Membantu visualisasi dataset dalam ruang berdimensi rendah sambil mempertahankan variasi data.

## ▶️ Cara Menggunakan

1. Kloning repositori ini:
   ```bash
   git clone https://github.com/your-username/iris-visualization.git
   cd iris-visualization
   ```

2. Buka notebook-nya:
   ```bash
   jupyter notebook Untitled4.ipynb
   ```

3. Jalankan semua sel untuk melihat visualisasinya.

## 📚 Info Dataset

- 150 sampel
- 4 fitur: panjang sepal, lebar sepal, panjang petal, lebar petal
- 3 kelas: `setosa`, `versicolor`, `virginica`
