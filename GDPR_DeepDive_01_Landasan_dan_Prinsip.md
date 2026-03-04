# Deep Dive Bab 1 & 2: Landasan Hukum dan Prinsip Utama

## Bab 1: Ketentuan Umum (Pasal 1 - 4)
Bab ini menentukan "siapa" dan "apa" yang diatur.

### Pasal 1: Subjek dan Tujuan
- Melindungi hak asasi dan kebebasan dasar individu, khususnya hak atas perlindungan data pribadi.
- Memastikan aliran bebas data pribadi di dalam Uni Eropa tidak dibatasi demi perlindungan ini.

### Pasal 2 & 3: Cakupan
- **Materiil:** Berlaku untuk data digital dan data fisik yang diarsipkan secara sistematis.
- **Teritorial:** Berlaku jika perusahaan Anda memiliki "establishment" di UE, atau jika Anda berada di luar UE tetapi memproses data orang di UE untuk:
  - Penawaran barang/jasa.
  - Pemantauan perilaku (tracking/profiling).

### Pasal 4: Definisi Teknis untuk Governance
- **Pseudonymisation:** Pengolahan data sedemikian rupa sehingga data tidak lagi dapat dikaitkan dengan subjek data tanpa informasi tambahan (kunci terpisah). Ini adalah teknik mitigasi risiko yang sangat dianjurkan.
- **Biometric Data:** Data hasil pemrosesan teknis khusus terkait karakteristik fisik, fisiologis, atau perilaku (wajah, sidik jari).
- **Genetic Data:** Data terkait karakteristik genetik yang memberikan informasi unik tentang fisiologi atau kesehatan.

---

## Bab 2: Prinsip-Prinsip (Pasal 5 - 11)
Ini adalah "konstitusi" bagi Data Governance Anda.

### Pasal 5: Prinsip Pemrosesan
1. **Lawfulness, Fairness, Transparency:** Harus ada dasar hukum, tidak menipu, dan terbuka.
2. **Purpose Limitation:** Tujuan harus spesifik. Data yang dikumpulkan untuk "analitik website" tidak boleh tiba-tiba digunakan untuk "penilaian kredit" tanpa izin baru.
3. **Data Minimisation:** Hanya data yang *necessary* yang diambil. Contoh: Aplikasi senter tidak butuh data lokasi.
4. **Accuracy:** Data harus mutakhir. Jika user pindah alamat, sistem harus mampu memperbaruinya.
5. **Storage Limitation:** Harus ada *Retention Policy*. Contoh: Data transaksi disimpan 10 tahun (karena hukum pajak), lalu dihapus/dianonimkan.
6. **Integrity and Confidentiality:** Keamanan teknis (Encryption, Access Control).
7. **Accountability:** Pengendali harus bisa membuktikan kepatuhan (dengan audit trail, dokumentasi, dll).

### Pasal 6: Dasar Hukum (Penting!)
Pemrosesan hanya sah jika memenuhi setidaknya satu:
1. **Consent:** Persetujuan eksplisit.
2. **Contract:** Diperlukan untuk pelaksanaan kontrak (misal: butuh alamat untuk kirim barang).
3. **Legal Obligation:** Diperlukan oleh hukum (misal: laporan pajak).
4. **Vital Interests:** Untuk menyelamatkan nyawa.
5. **Public Task:** Tugas otoritas publik.
6. **Legitimate Interests:** Kepentingan bisnis yang sah, selama tidak mengesampingkan hak individu (memerlukan *Legitimate Interest Assessment* / LIA).

### Pasal 9: Data Kategori Khusus (Sensitif)
Melarang pemrosesan data ras, etnis, politik, agama, biometrik, kesehatan, dan orientasi seksual, KECUALI ada pengecualian ketat (seperti persetujuan eksplisit atau kebutuhan medis).
