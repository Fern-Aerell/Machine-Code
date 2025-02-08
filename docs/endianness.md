# Apa itu endianness

**Endianness** adalah cara menyusun urutan byte dalam sebuah bilangan atau data yang lebih besar dari 1 byte di memori komputer. Ini menentukan urutan byte dalam representasi data multibyte (seperti 16-bit, 32-bit, atau 64-bit) saat disimpan atau diproses.

Ada dua jenis utama **endianness**:

1. **Big-endian**:
   - **Most significant byte (MSB)** disimpan di alamat memori yang lebih rendah (paling depan).
   - Byte dengan nilai terbesar disimpan terlebih dahulu.
   - Contoh:  
     Untuk angka **0x12345678** (4 byte), di memori:
     ```
     [0x12] [0x34] [0x56] [0x78]
     ```

2. **Little-endian**:
   - **Least significant byte (LSB)** disimpan di alamat memori yang lebih rendah (paling depan).
   - Byte dengan nilai terkecil disimpan terlebih dahulu.
   - Contoh:  
     Untuk angka **0x12345678** (4 byte), di memori:
     ```
     [0x78] [0x56] [0x34] [0x12]
     ```

### **Mengapa Endianness Penting?**
- **Kompatibilitas**: Sistem dengan endianness yang berbeda bisa menghasilkan interpretasi data yang salah jika tidak ditangani dengan benar.
- **Transmisi Data**: Saat mengirim data antar sistem (misalnya, melalui jaringan atau file), endianness harus konsisten agar data diterima dengan benar.
  
### **Contoh Sistem Endianness**:
- **Big-endian**: Beberapa arsitektur seperti **Motorola 68k**, **SPARC**.
- **Little-endian**: Beberapa arsitektur seperti **Intel x86**, **AMD64**.

Beberapa sistem juga menggunakan **mixed-endian** atau **bi-endian**, yang dapat beroperasi dalam kedua mode tergantung pada konfigurasi atau aplikasi.