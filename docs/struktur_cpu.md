# Apa itu struktur CPU

**Struktur CPU** (Central Processing Unit) adalah susunan dan organisasi komponen-komponen dalam CPU yang bekerja untuk mengeksekusi instruksi program. CPU adalah otak dari komputer yang melakukan sebagian besar proses komputasi. Struktur CPU terdiri dari beberapa bagian utama yang masing-masing memiliki fungsi tertentu.

### **Komponen Utama dalam Struktur CPU:**

1. **ALU (Arithmetic Logic Unit)**:
   - Bertanggung jawab untuk melakukan operasi aritmatika (penjumlahan, pengurangan, dll.) dan operasi logika (AND, OR, NOT, dll.).
   - ALU juga melakukan perbandingan dan keputusan berbasis logika.

2. **CU (Control Unit)**:
   - Mengontrol aliran instruksi dan data dalam CPU.
   - Membaca instruksi dari memori, mendekode instruksi tersebut, dan mengarahkan operasi yang harus dilakukan oleh ALU atau perangkat lainnya.
   - Mengatur timing dan urutan eksekusi instruksi.

3. **Register**:
   - Memori kecil dan cepat yang terletak di dalam CPU untuk menyimpan data sementara yang diperlukan oleh ALU atau CU.
   - Register dapat berupa register data (untuk menyimpan nilai data) atau register kontrol (untuk menyimpan status dan kontrol eksekusi).
   - Contoh register: **Program Counter (PC)**, **Accumulator (A)**, **Instruction Register (IR)**, dll.

4. **Cache**:
   - Memori berkecepatan sangat tinggi yang digunakan untuk menyimpan data atau instruksi yang sering diakses, untuk mempercepat akses.
   - Cache CPU biasanya terdiri dari beberapa tingkat (L1, L2, L3), dengan L1 yang paling cepat dan L3 yang lebih besar namun lebih lambat.

5. **Bus**:
   - Sistem jalur untuk menghubungkan berbagai komponen di dalam CPU dan memungkinkan komunikasi antara register, ALU, memori, dan perangkat lainnya.
   - Ada beberapa jenis bus: **data bus** (untuk mengirim data), **address bus** (untuk menentukan lokasi memori), dan **control bus** (untuk mengontrol operasi).

6. **Clock**:
   - Mengatur waktu dan sinkronisasi dalam eksekusi instruksi.
   - Kecepatan CPU, yang sering disebut **frekuensi clock**, mengukur berapa banyak siklus per detik (Hz) yang dapat diproses CPU.

### **Alur Eksekusi Instruksi (Fetch-Decode-Execute Cycle)**:
1. **Fetch**: CU mengambil instruksi berikutnya dari memori berdasarkan alamat yang diberikan oleh **Program Counter (PC)**.
2. **Decode**: CU mendekode instruksi untuk menentukan operasi yang perlu dilakukan dan perangkat mana yang terlibat.
3. **Execute**: ALU atau unit terkait lainnya melaksanakan instruksi tersebut (misalnya, menghitung, memindahkan data, atau memodifikasi register).

### **Arsitektur CPU**:
- **Von Neumann Architecture**: CPU, memori, dan perangkat input/output berbagi bus yang sama untuk komunikasi.
- **Harvard Architecture**: Memori terpisah untuk instruksi dan data, memberikan kecepatan lebih tinggi dalam pengolahan.

Struktur CPU terus berkembang seiring dengan inovasi dalam desain prosesor, seperti multi-core processing, pipeline execution, dan hyper-threading, yang memungkinkan eksekusi instruksi lebih cepat dan efisien.