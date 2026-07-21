# 📅 Sistem Penjadwalan Otomatis Mata Kuliah Menggunakan Algoritma Genetika
**Ujian Akhir Semester (UAS) - Kecerdasan Buatan (SIF210)**

---

## 👤 Identitas Mahasiswa
* **Nama:** TS.Rahmat Karim
* **NIM:** 24146047
* **Dosen Pengampu:** Teuku Rizky Noviandy, S.Kom., M.Kom.

---

## 📌 Deskripsi Proyek
Proyek ini bertujuan untuk membangun sistem **penjadwalan otomatis 24 mata kuliah** secara optimal dengan meminimalkan penalti konflik menggunakan **Algoritma Genetika (Genetic Algorithm)**. 

### Batasan Constraint (Konflik) yang Dihindari:
1. **Konflik Ruang:** Dua mata kuliah tidak boleh menggunakan ruang yang sama pada slot waktu yang sama.
2. **Konflik Dosen-Waktu:** Seorang dosen tidak boleh mengajar lebih dari satu mata kuliah pada slot waktu yang sama.
3. **Konflik Dosen-Hari:** Seorang dosen tidak boleh mengajar lebih dari satu kali pada hari yang sama.

---

## ⚙️ Parameter Algoritma Genetika
* **Jumlah Mata Kuliah:** 24 MK (6 Dosen Tetap)
* **Jumlah Ruangan:** 4 Ruang (`R1`, `R2`, `R3`, `R4`)
* **Jumlah Slot Waktu:** 12 Timeslot (Senin–Kamis)
* **Ukuran Populasi:** 60 Individu
* **Jumlah Generasi:** 100 Generasi
* **Crossover Rate ($p_c$):** 85%
* **Mutation Rate ($p_m$):** 20%
* **Rumus Fitness:** $\text{Fitness} = \frac{100}{1 + \text{Jumlah Konflik}}$

---

## 📊 Tampilan Grafik Evolusi Fitness
Program akan menghasilkan grafik dua garis (*Fitness Maksimum* dan *Fitness Rata-rata*) yang menunjukkan peningkatan performa penjadwalan dari generasi ke-1 hingga generasi ke-100.
