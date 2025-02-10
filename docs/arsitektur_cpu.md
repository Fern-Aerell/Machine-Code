# Apa itu arsitektur CPU?

**Arsitektur CPU** adalah desain dasar yang menentukan bagaimana sebuah prosesor (CPU) bekerja, termasuk cara eksekusi instruksi, pengelolaan data, dan komunikasi dengan perangkat lain. Ini mencakup **set instruksi (ISA - Instruction Set Architecture)**, **arsitektur mikro (Microarchitecture)**, serta **organisasi sistem komputer** yang digunakan.

---

### 🔹 **Komponen Utama Arsitektur CPU**
1. **Set Instruksi (ISA - Instruction Set Architecture)**  
   - Kumpulan instruksi dasar yang bisa dieksekusi CPU (misalnya: x86, ARM, RISC-V).  
   - Menentukan bagaimana software berinteraksi dengan hardware.  
   
2. **Arsitektur Mikro (Microarchitecture)**  
   - Implementasi fisik dari set instruksi.  
   - Berisi desain pipeline, jumlah core, cache, dan optimasi lain.  
   
3. **Organisasi CPU**  
   - Cara elemen-elemen CPU seperti register, ALU, cache, dan memori dihubungkan dan bekerja bersama.  

---

### 🔹 **Jenis Arsitektur CPU Berdasarkan ISA**
1. **CISC (Complex Instruction Set Computing)**  
   - Contoh: **x86 (Intel, AMD)**  
   - Instruksi kompleks, lebih sedikit instruksi yang dijalankan per program.  
   - Cocok untuk perangkat yang butuh kompatibilitas dan software legacy.  

2. **RISC (Reduced Instruction Set Computing)**  
   - Contoh: **ARM (Apple M1/M2, Snapdragon), RISC-V**  
   - Instruksi sederhana, tapi lebih cepat dieksekusi dengan pipeline.  
   - Hemat daya, sering dipakai di smartphone dan embedded systems.  

3. **VLIW (Very Long Instruction Word)**  
   - Contoh: **Itanium, DSP (Digital Signal Processor)**  
   - Mengeksekusi banyak operasi sekaligus dalam satu siklus.  

---

### 🔹 **Komponen Internal CPU**
- **ALU (Arithmetic Logic Unit)** → Menghitung operasi matematika & logika.  
- **Control Unit (CU)** → Mengatur eksekusi instruksi.  
- **Registers** → Penyimpanan data kecil berkecepatan tinggi.  
- **Cache** → Memori cepat untuk mempercepat akses data dari RAM.  
- **Pipeline** → Teknik untuk meningkatkan kecepatan eksekusi instruksi secara paralel.  

---

### 🔹 **Contoh Arsitektur CPU Populer**
- **x86/x86-64** (Intel, AMD) → Banyak digunakan di PC dan server.  
- **ARM** (Apple M-series, Snapdragon, Exynos) → Dipakai di smartphone dan tablet.  
- **RISC-V** → Arsitektur open-source yang mulai populer di embedded system.