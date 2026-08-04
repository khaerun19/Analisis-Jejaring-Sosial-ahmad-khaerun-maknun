# Analisis Jejaring Sosial (SNA) - Evaluasi Komunikasi Organisasi

Repository ini berisi Laporan Tugas Pra UAS Mata Kuliah **Analisis Jejaring Sosial** mengenai evaluasi efektivitas komunikasi internal organisasi kemahasiswaan berbasis *Social Network Analysis (SNA)*.

---

## 👤 Identitas Mahasiswa
* **Nama:** Ahmad Khaerun Maknun[cite: 9]
* **Kelas:** 8A - Analisis Jejaring Sosial[cite: 9]
* **Institusi:** Universitas Tangerang Raya[cite: 9]
* **Mata Kuliah:** Analisis Jejaring Sosial[cite: 9]

---

## 📌 Ringkasan Tugas
Penelitian ini bertujuan untuk menganalisis dan mengevaluasi alur komunikasi pada jaringan organisasi kemahasiswaan (skala $N = 1.000$ node) menggunakan pendekatan *Social Network Analysis (SNA)*[cite: 9]. Analisis mencakup pembentukan graf berarah dan berbobot, pengukuran metrik sentralitas, uji metrik makro jaringan, deteksi komunitas dengan algoritma Louvain, hingga simulasi penyebaran informasi[cite: 9].

### Ringkasan Poin Hasil Analisis:
1. **Representasi Graf & Matriks Adjacency:** Pemodelan graf berarah (*directed*) dan berbobot (*weighted*) dari 4 saluran interaksi (pesan digital, rapat, kegiatan, dan Twitter) dengan contoh matriks keterdampingan sampel 5 aktor[cite: 9].
2. **Sentralitas Aktor:** Kalkulasi *In-Degree*, *Out-Degree*, *Betweenness*, *Closeness*, dan *Eigenvector Centrality* untuk menentukan *Hub*, *Gatekeeper*, dan *Key Opinion Leader*[cite: 9].
3. **Metrik Global & Komunitas:** Nilai *Density* ($\rho \approx 0.012$), *Diameter* (8 hop), *Average Path Length* (3.42 langkah), serta segmentasi 4 komunitas utama menggunakan *Algoritma Louvain*[cite: 9].
4. **Simulasi Propagasi Pesan:** Pemodelan *Independent Cascade (IC)* dan *SIR Model* membuktikan bahwa penyebaran dari *Seed Sentral* mampu menjangkau 85% populasi dibanding *Seed Pinggiran* yang hanya 18%[cite: 9].
5. **Visualisasi & Rekomendasi:** Pemetaan visual *Core-Periphery Structure* menggunakan Gephi (layout *ForceAtlas2*) dan perancangan kebijakan *Liaison Officer* serta program lintas divisi[cite: 9].

---

## 📁 Struktur Repository

```text
├── Analisis_Jejaring_Sosial_Ahmad_Khaerun_Maknun_8A.pdf  # Laporan Lengkap PDF
├── jejaring_organisasi_8A.graphml                      # File data graf untuk Gephi
├── visualisasi_grafik.png                              # Gambar visualisasi jaringan
└── README.md                                           # Dokumentasi repository
