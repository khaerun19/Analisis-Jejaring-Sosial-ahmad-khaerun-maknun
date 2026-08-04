# 📊 Analisis Jejaring Sosial (SNA) - Evaluasi Komunikasi Organisasi

Repository ini berisi Laporan Tugas Pra UAS Mata Kuliah **Analisis Jejaring Sosial** mengenai evaluasi efektivitas komunikasi internal organisasi kemahasiswaan berbasis *Social Network Analysis (SNA)*.

---

## 👤 Identitas Mahasiswa
* **Nama:** Ahmad Khaerun Maknun
* **Kelas:** 8A - Analisis Jejaring Sosial
* **Mata Kuliah:** Analisis Jejaring Sosial
* **Institusi:** Universitas Tangerang Raya

---

## 📌 Ringkasan Tugas
Penelitian ini menganalisis jaringan komunikasi organisasi kemahasiswaan (skala $N = 1.000$ node) menggunakan pendekatan *Social Network Analysis (SNA)* dengan bantuan pustaka `NetworkX` dan `python-louvain`.

### Poin Utama Pembahasan:
1. **Representasi Graf & Matriks Adjacency:** Pemodelan graf berarah (*directed*) dan berbobot (*weighted*) dari 4 saluran komunikasi serta matriks keterdampingan $5 \times 5$.
2. **Metrik Sentralitas:** Perhitungan *In-Degree*, *Out-Degree*, *Betweenness*, *Closeness*, dan *Eigenvector Centrality* untuk pemetaan *Gatekeeper* dan *Hub*.
3. **Metrik Global & Louvain:** Evaluasi *Density* ($\rho \approx 0.012$), *Diameter* (8 hop), *Average Path Length* (3.42 langkah), dan segmentasi 4 komunitas.
4. **Simulasi Propagasi:** Pengujian model *Independent Cascade (IC)* dan *SIR* (Seed Sentral 85% vs Seed Pinggiran 18%).
5. **Visualisasi & Rekomendasi:** Pemetaan *Core-Periphery Structure* dan perancangan kebijakan *Liaison Officer*.

---

## 📁 File dalam Repository Ini

| Nama File | Keterangan |
| :--- | :--- |
| `analisis jejaring sosial_ahmad khaerun maknun.ipynb` | File kode program Python Google Colab |
| `Analisis_Jejaring_Sosial_Ahmad_Khaerun_Maknun_8A.pdf` | Laporan lengkap tugas pra UAS |
| `jejaring_organisasi_8A.graphml` | File data graf untuk Gephi |
| `ajs_khaerun.png` | Gambar hasil visualisasi jaringan |

---

