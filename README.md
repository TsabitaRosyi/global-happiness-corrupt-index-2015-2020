# 🌍 World Happiness, CPI, GDP, and Health Analysis (2015–2020)

Proyek Analisis Data Eksploratif (EDA) untuk mengeksplorasi dan mengetahui pengaruh tingkat kebahagiaan (*happiness score*) terhadap Indeks Persepsi Korupsi (CPI), *Gross Domestic Product* (GDP) per kapita, serta kesehatan di berbagai benua pada rentang waktu 2015 hingga 2020[cite: 1, 5].

---

---

## 📌 Latar Belakang
Penelitian ini dilatarbelakangi oleh tantangan global terkait korupsi yang melibatkan berbagai entitas geopolitik di berbagai benua[cite: 4]. Fenomena ini memicu pertanyaan kritis mengenai hubungan antara tingkat kebahagiaan, kondisi ekonomi (GDP), kesehatan masyarakat, dan indeks persepsi korupsi (CPI)[cite: 4, 5]. Melalui pendekatan Data Science, proyek ini bertujuan untuk memberikan pemahaman komprehensif mengenai motivasi dan tren global dalam meningkatkan kualitas kepemimpinan serta kesejahteraan sosial[cite: 4].

---

## 🎯 Rumusan Masalah & Tujuan
1. **Pengaruh Kebahagiaan terhadap Indeks Korupsi (CPI):** Menganalisis seberapa besar hubungan tingkat kebahagiaan dengan skor CPI di setiap benua pada tahun 2015–2020[cite: 5].
2. **Pengaruh Kebahagiaan terhadap GDP:** Menganalisis korelasi dan dampak tingkat kebahagiaan terhadap *Gross Domestic Product* per kapita[cite: 5].
3. **Pengaruh Kebahagiaan terhadap Kesehatan:** Mengetahui sejauh mana faktor kesehatan memengaruhi skor kebahagiaan global[cite: 5].

---

## 🛠️ Metodologi & Tahapan Analisis
Proyek ini mengimplementasikan bahasa pemrograman **Python** melalui **VS Code** dengan tahapan kerja sebagai berikut[cite: 6]:
1. **Data Gathering:** Mengambil dataset *World Happiness & Corruption* dari Kaggle[cite: 6].
2. **Data Cleaning & Preprocessing:** Menangani *missing values* (imputasi menggunakan *mean*)[cite: 8].
3. **Data Transformation:** Melakukan analisis *time series*, *grouping data*, dan penyesuaian format[cite: 6].
4. **Data Integration:** Mendeteksi *outlier* menggunakan metode IQR (*Interquartile Range*) dan visualisasi *Boxplot*[cite: 6, 15].
5. **Statistika Deskriptif:** Pengujian normalitas menggunakan Shapiro-Wilk, QQ-Plot, dan analisis derajat Kurtosis (*Platykurtic*)[cite: 16, 18].
6. **Uji Hipotesis & Analisis Korelasi:** Menerapkan uji statistik (*T-test*) serta Analisis Korelasi Multivariat (Metode Pearson)[cite: 6, 20, 21].
7. **Visualisasi Data & Dashboard Interaktif:** Membangun visualisasi statis (Heatmap, Scatter Plot) serta Dashboard Interaktif menggunakan pustaka **Dash** Python[cite: 6, 22, 25].

---

## 📈 Kesimpulan Utama
* **Korelasi dengan GDP:** Terdapat korelasi positif yang **kuat** (r $\approx$ 0.79) antara skor kebahagiaan dan GDP per kapita, menunjukkan bahwa pertumbuhan ekonomi berkontribusi nyata terhadap kebahagiaan penduduk[cite: 21, 25].
* **Korelasi dengan CPI & Kesehatan:** Skor CPI dan kesehatan memiliki korelasi positif yang **sedang** terhadap tingkat kebahagiaan, yang mengindikasikan bahwa transparansi/anti-korupsi serta fasilitas kesehatan yang baik merupakan pilar penting dalam mewujudkan masyarakat yang bahagia[cite: 21, 25].

---

