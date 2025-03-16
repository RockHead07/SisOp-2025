<div align="center">

# TUGAS SISTEM OPERASI MINGGU KE-1

---

![Image](https://github.com/user-attachments/assets/3ad88b6e-7159-44a2-a004-c909b974a88c)

#### Dosen Pengampu :
**Dr. Ferry Astika Saputra ST, M.Sc.**

#### Disusun Oleh : 
**Bagus Insan Pradana** D3 IT A **(3214521007)**

> PROGRAM STUDI D3 TEKNIK INFORMATIKA PSDKU LAMONGAN
> DEPARTEMEN TEKNIK INFORMATIKA DAN KOMPUTER 
> POLITEKNIK ELEKTRONIKA NEGERI SURABAYA 
> 2025

---

</div>

#### SISTEM BILANGAN Desimal, Biner, Oktal, & Heksadesimal.

**Tujuan:**
Mahasiswa diharapkan setelah mempelajari Sistem Bilangan dapat menguasai beberapa aspek dari keseluruhan materi tersebut.

---

# Penugasan:
1. Mengerjakan seluruh latihan *sistembilangan.pdf* yang ada pada Ethol:[https://ethol.pens.ac.id/mahasiswa/kuliah/materi](https://ethol.pens.ac..id/mahasiswa/kuliah/materi). Dan dikumpulkan di ethol untuk pengumpulan (Docs / Word).
2. Membuat repository di GitHub untuk mengupload jawaban dan pertanyaan dari latihan soal *sistembilangan.pdf*. Hanya soal pertama, contoh:
   - 2a, 3a, dst. (Pengecualian untuk nomor 1)
   - Untuk format file di Github menggunakan format .markdown file (contoh: Latihan.md / "nama".md).

---

# Latihan Soal.

1. Soal nomor 1:
   - Bilangan Biner adalah bilangan yang berbasis: **<ins>Dua (2)</ins>**.
   - Bilangan Heksadesimal adalah bilang yang berbasis: **<ins>Enam belas (16)</ins>**

---

2. Konversikan bilangan desimal dibawah ini ke dalam bilangan biner!
    - 1234₁₀

**Jawaban:**

#### 1234₁₀ ke Biner

Langkah-langkah konversi:

| Pembagian | Hasil Bagi | Sisa |
|-----------|-----------|------|
| 1234 ÷ 2  | 617       | 0    |
| 617 ÷ 2   | 308       | 1    |
| 308 ÷ 2   | 154       | 0    |
| 154 ÷ 2   | 77        | 0    |
| 77 ÷ 2    | 38        | 1    |
| 38 ÷ 2    | 19        | 0    |
| 19 ÷ 2    | 9         | 1    |
| 9 ÷ 2     | 4         | 1    |
| 4 ÷ 2     | 2         | 0    |
| 2 ÷ 2     | 1         | 0    |
| 1 ÷ 2     | 0         | 1    |

Membaca dari bawah ke atas, hasil konversi **1234₁₀** menjadi **10011010010₂** (basis 2).

---

3. Konversikan bilangan biner di bawah ini ke dalam bilangan desimal!
    - 10101010₂

**Jawaban:**

#### 10101010₂ ke Desimal

Langkah-langkah konversi:

**10101010₂** = (1 × 128) + (0 × 64) + (1 × 32) + (0 × 16) + (1 × 8) + (0 × 4) + (1 × 2) + (0 × 1)

= 128 + 0 + 32 + 0 + 8 + 0 + 2 + 0  
= **170₁₀**

Jadi, bilangan biner **10101010₂** jika dikonversi ke desimal menjadi **<ins>170₁₀</ins>**.

---

4. Konversikan bilangan biner di bawah ini ke dalam bilangan oktal!
   - 101 011 111 001₂

**Jawaban:**

#### 101 011 111 001₂ ke Oktal

Pisahkan bilangan biner menjadi kelompok tiga bit dari kanan ke kiri:  
**101 011 111 001₂**  

Konversikan setiap kelompok ke dalam bilangan oktal:  

- **101₂** = **5₈**  
- **011₂** = **3₈**  
- **111₂** = **7₈**  
- **001₂** = **1₈**  

Jadi, hasil konversi bilangan biner **101 011 111 001₂** ke bilangan oktal adalah **<ins>5371₈**.

---

5. Konversikan bilangan oktal di bawah ini kedalam bilangan biner!
    - 2170₈

**Jawaban:**

#### 2170₈ ke Biner
 
Setiap digit oktal dikonversi ke dalam bentuk biner 3-bit:

- **2₈** = **010₂**  
- **1₈** = **001₂**  
- **7₈** = **111₂**  
- **0₈** = **000₂**  

Jadi, hasil konversi dari bilangan oktal **2170₈** ke dalam bilangan biner adalah **<ins>010 001 111 000₂</ins>**.

---

6. Konversikan bilangan desimal di bawah ini ke dalam bilangan heksadesimal!
    - 1780₁₀
  
**Jawaban:**

#### 1780₁₀ ke Heksadesimal

Setiap pembagian dilakukan dengan **basis 16** dan sisa dicatat:

1. **1780 ÷ 16** = **111**, sisa **4**  
2. **111 ÷ 16** = **6**, sisa **15** (**F**)  
3. **6 ÷ 16** = **0**, sisa **6**  

Jadi, hasil konversi **1780₁₀** ke dalam bilangan heksadesimal adalah **<ins>6F4₁₆</ins>**.

---

7. Konversikan bilangan heksadesimal di bawah ini ke dalam bilangan desimal!
    - ABCD₁₆

**Jawaban:**

#### ABCD₁₆ ke Desimal

| Digit | Heksadesimal | Desimal | Pangkat | Perhitungan |
|--------|-------------|---------|--------|-------------|
| A | 10 | 10 | 16³ = 4096 | 10 × 4096 = 40960 |
| B | 11 | 11 | 16² = 256  | 11 × 256 = 2816 |
| C | 12 | 12 | 16¹ = 16   | 12 × 16 = 192 |
| D | 13 | 13 | 16⁰ = 1    | 13 × 1 = 13 |

Total hasil:  
**40960 + 2816 + 192 + 13 = 43981₁₀**

Jadi, hasil konversi bilangan heksadesimal **ABCD₁₆** ke dalam **bilangan desimal** adalah **<ins>43981₁₀**.

---

8. Konversikan bilangan pecahan desimal dibawah ini ke dalam bilangan biner!
    - 0,3125₁₀

**Jawaban:**

Jawaban:

#### ABCD₁₆ ke Desimal

| Digit | Heksadesimal | Desimal | Pangkat | Perhitungan |
|--------|-------------|---------|--------|-------------|
| A | 10 | 10 | 16³ = 4096 | 10 × 4096 = 40960 |
| B | 11 | 11 | 16² = 256  | 11 × 256 = 2816 |
| C | 12 | 12 | 16¹ = 16   | 12 × 16 = 192 |
| D | 13 | 13 | 16⁰ = 1    | 13 × 1 = 13 |

Total hasil:  
**40960 + 2816 + 192 + 13 = 43981₁₀**

Jadi, hasil konversi bilangan heksadesimal **ABCD₁₆** ke dalam **bilangan desimal** adalah **43981₁₀**.

---

9. Konversikan bilangan desimal di bawah ini ke dalam bilangan biner!
    - 11,625₁₀

**Jawaban:**

#### 11,625₁₀ ke Biner

###### **Konversi 11₁₀ ke Biner**

| Langkah | Nilai Desimal | Dibagi 2 | Hasil Bagi | Sisa (Bit) |
|---------|--------------|----------|------------|-------------|
| 1       | 11           | ÷2       | 5          | **1**       |
| 2       | 5            | ÷2       | 2          | **1**       |
| 3       | 2            | ÷2       | 1          | **0**       |
| 4       | 1            | ÷2       | 0          | **1**       |

11₁₀ = **1011₂**

&nbsp;&nbsp;

###### **Konversi 0,625₁₀ ke Biner**

| Langkah | Nilai Desimal | Dikali 2 | Hasil | Digit Biner |
|---------|--------------|----------|-------|-------------|
| 1       | 0,625        | ×2       | 1,25   | **1** |
| 2       | 0,25         | ×2       | 0,5    | **0** |
| 3       | 0,5          | ×2       | 1,0    | **1** |

0,625₁₀ = **0,101₂**

Jadi hasil konversi bilangan desimal pecahan **11,625₁₀** ke bilangan **biner** adalah:  
**<ins>1011,101₂**

---

10.  Konversikan bilangan desimal di bawah ini ke dalam bilangan heksadesimal!
     - 348,645₁₀

**Jawaban:**

#### 348,654₁₀ ke Heksadesimal

###### **Konversi 348₁₀ ke Heksadesimal**
| Langkah | Nilai Desimal | Dibagi 16 | Hasil Bagi | Sisa (Digit Hex) |
|---------|--------------|-----------|------------|-------------------|
| 1       | 348          | ÷16       | 21         | **12 (C)**        |
| 2       | 21           | ÷16       | 1          | **5**             |
| 3       | 1            | ÷16       | 0          | **1**             |
 
348₁₀ = **15C₁₆**

&nbsp;&nbsp;

###### **Konversi 0,654₁₀ ke Heksadesimal**
Setiap hasil perkalian dengan 16 diambil bagian bulatnya sebagai digit heksadesimal.

| Langkah | Nilai Desimal | Dikali 16 | Hasil   | Digit Heksadesimal |
|---------|--------------|-----------|---------|--------------------|
| 1       | 0,654        | ×16       | 10,465  | **A (10)**         |
| 2       | 0,465        | ×16       | 7,424   | **7**              |
| 3       | 0,424        | ×16       | 6,784   | **6**              |

0,654₁₀ = **0.A76₁₆**

Jadi hasil konversi bilangan desimal pecahan **348,654₁₀** ke bilangan **heksadesimal** adalah:  
**15C.A76₁₆**

---

11.   Konversikan bilangan di bawah ini ke dalam bilangan desimal!
      - 010100011,001111101₂

**Jawaban:**

#### 010100011,001111101₂ ke Desimal

###### **Konversi 010100011₂ ke Desimal**

| Bit       | 0 | 1 | 0 | 1 | 0 | 0 | 0 | 0 | 1 |
|-----------|---|---|---|---|---|---|---|---|---|
| Posisi    | 8 | 7 | 6 | 5 | 4 | 3 | 2 | 1 | 0 |
| Nilai     | 0 | 1×128 | 0 | 1×32 | 0 | 0 | 0 | 1×2 | 1×1 |

**Perhitungan:**
(1 × 128) + (1 × 32) + (1 × 2) + (1 × 1) = 163₁₀

**010100011₂ = 163₁₀**.

&nbsp;

###### **Konversi 0,001111101₂ ke Desimal**

| Bit       | 0 | 0 | 1 | 1 | 1 | 1 | 1 | 0 | 1 |
|-----------|---|---|---|---|---|---|---|---|---|
| Posisi    | -1 | -2 | -3 | -4 | -5 | -6 | -7 | -8 | -9 |
| Nilai     | 0 | 0 | 1/8 | 1/16 | 1/32 | 1/64 | 1/128 | 0 | 1/512 |

**Perhitungan:**
(1 ÷ 8) + (1 ÷ 16) + (1 ÷ 32) + (1 ÷ 64) + (1 ÷ 128) + (1 ÷ 512) = 0.244140625₁₀

**0,001111101₂ = 0.244140625₁₀**.

&nbsp;

Jadi hasil konversi bilangan **010100011,001111101₂** ke **Desimal** adalah: **<ins>163,244140625₁₀</ins>**


---

12.  Rubahlah bilangan biner di bawah ini ke dalam bentu BCD (Binary Coded Decimal)!
     - 10100110000111₂
  
**Jawaban:**

#### 10100110000111₂  ke BCD

###### Kelompokkan Biner dalam 4-bit dari Kanan**

**10 1001 1000 0111**


Karena digit paling kiri tidak cukup 4-bit, kita tambahkan **0** di depannya:

**0010 1001 1000 0111**

&nbsp;

###### **Konversi Setiap 4-bit ke Desimal**
| 4-bit  | Desimal |
|--------|---------|
| 0010   | 2       |
| 1001   | 9       |
| 1000   | 8       |
| 0111   | 7       |

&nbsp;

Jadi hasil **Binary Coded Decimal (BCD)** dari **10100110000111₂** adalah: **<ins>2987**

---

13. Rubahlah bentuk BCD di bawah ini ke dalam bilangan biner!
    - 1987

**Jawaban:**

#### 1987 ke BCD

###### **Konversi Setiap Digit Desimal ke 4-bit Biner**
| Desimal | Biner (4-bit) |
|---------|--------------|
| 1       | 0001         |
| 9       | 1001         |
| 8       | 1000         |
| 7       | 0111         |



Jadi hasil **Binary Coded Decimal (BCD)** dari **1987₁₀** adalah: **<ins>0001 1001 1000 0111 (BCD)**

---

14.   Rubahlah bilangan biner di bawah ini kedalam BCO (Binary Coded Octal)!
      - 11111101001₂

**Jawaban:**

##### **Kelompokkan 3-bit dari Kanan**

11 111 101 001₂

Tambahkan nol di depan agar kelipatan 3-bit:  

011 111 101 001₂


##### **Konversi Setiap Grup ke Oktal**
| Biner (3-bit) | Oktal |
|--------------|------|
| 011         | 3    |
| 111         | 7    |
| 101         | 5    |
| 001         | 1    |

Jadi hasil **Binary Coded Octal (BCO)** dari **11111101001₂** adalah: **<ins>3751**

---

15. Rubahlah bilangan biner di bawah ini ke dalam BCH (Binhary Coded Hexadecimal)!
    - 1101111100101110₂

**Jawaban:**

##### **Kelompokkan 4-bit dari Kanan**

1101 1111 0010 1110₂

##### **Konversi Setiap Grup ke Heksadesimal**
| Biner (4-bit) | Heksadesimal |
|--------------|-------------|
| 1101         | D           |
| 1111         | F           |
| 0010         | 2           |
| 1110         | E           |

Jadi hasil **Binary Coded Hexadecimal (BCH)** dari **1101111100101110₂** adalah: **<ins>DF2E₁₆**

---

16.  Rubahlah bentuk BCH di bawah ini ke dalam bilangan heksadesimal!
     - F0DE₁₆

**Jawaban:**

#### **Konversi Setiap Digit Heksadesimal ke Biner**

| Heksadesimal | Biner (4-bit) |
|--------------|--------------|
| F (15)       | 1111         |
| 0 (0)        | 0000         |
| D (13)       | 1101         |
| E (14)       | 1110         |

Jadi hasil konversi **BCH F0DE₁₆** ke **bilangan biner** adalah: **<ins>1111 0000 1101 1110₂**

---

17.  Nyatakan positif / negatif bilangan biner di bawah ini!
     - 01111111 

**Jawaban:**

- Bit paling kiri (MSB) adalah **0**, menandakan bahwa bilangan ini adalah **positif**.


##### Konversi Biner ke Desimal:

| Bit         | 0 | 1 | 1 | 1 | 1 | 1 | 1 | 1 |
|------------|---|---|---|---|---|---|---|---|
| Nilai (2ⁿ) | 128 | 64 | 32 | 16 | 8 | 4 | 2 | 1 |

= (0 × 128) + (1 × 64) + (1 × 32) + (1 × 16) + (1 × 8) + (1 × 4) + (1 × 2) + (1 × 1)
= 0 + 64 + 32 + 16 + 8 + 4 + 2 + 1
= 127₁₀

Bilangan **01111111₂** adalah **positif** dan bernilai **<ins>127₁₀** dalam sistem desimal.

---

18.  Nyatakan bilangan biner negatif di bawah ini ke dalam bilangan desimal!
     - 10001000₂
  
**Jawaban:**

- Bit paling kiri (MSB) adalah **1**, menandakan bahwa bilangan ini adalah **negatif**.

##### Invers Semua Bit 
Mengubah semua bit (0 menjadi 1, dan 1 menjadi 0):  

10001000₂ menjadi 01110111₂
01110111₂ + 1₂ = <ins>01111000₂


##### Konversi Biner ke Desimal

| Bit         | 0 | 1 | 1 | 1 | 1 | 0 | 0 | 0 |
|------------|---|---|---|---|---|---|---|---|
| Nilai (2ⁿ) | 128 | 64 | 32 | 16 | 8 | 0 | 0 | 0 |

= (0 × 128) + (1 × 64) + (1 × 32) + (1 × 16) + (1 × 8) + (0 × 4) + (0 × 2) + (0 × 1)
= 0 + 64 + 32 + 16 + 8 + 0 + 0 + 0
= 120₁₀

Karena bilangan awal adalah **negatif**, maka:  

10001000₂ = -120₁₀


Bilangan **10001000₂** adalah **negatif** dan bernilai **<ins>−120₁₀** dalam sistem desimal.

---

19.  Nyatakan ASCII Code di bawah ini dalam bentuk karakter!
     - 14₁₆

**Jawaban:**

#### Konversi Heksadesimal ke Desimal  

| Digit Heksadesimal | Nilai Desimal |
|--------------------|--------------|
| 4 (×16¹)         | 4 × 16 = 64  |
| 1 (×16⁰)         | 1 × 1  = 1   |


= 64 + 1
= 65₁₀

Nilai **65** dalam **tabel ASCII** adalah huruf **'A'**.

Jadi bilangan **41₁₆** dalam **ASCII** merepresentasikan karakter **<ins>'A'**.

---

20.  Nyatakan karakter di bawah ini dalam ASCII Code!
     - a

**Jawaban:**

Dalam **tabel ASCII**, huruf kecil **'a'** memiliki nilai **97₁₀**.

Bilangan **9710** dikonversi ke **basis 16**:

97 ÷ 16 = 6, sisa 1
97₁₀ = 61₁₆

Jadi bilangan **ASCII** dari **'a'** dalam **heksadesimal** adalah **<ins>61₁₆**.

---

21.  Dengan keyboard standard ASCII, pada layar monitor nampak tulisan sebagai berikut:

>    **PRINT X**

Nyatakan keluaran output ASCII Biner pada keyboard tersebut!

**Jawaban:**

#### Keluaran output jika pada bentuk ASCII decimal:
P = 80₁₀
R = 82₁₀
I = 73₁₀
N = 78₁₀
T = 84₁₀
(SPASI) = 32₁₀
X = 88₁₀

Jadi keluaran output “PRINT X” pada bentuk ASCII Desimal, adalah **80 82 73 78 84 32 88₁₀**

#### Merubah seluruh “PRINT X” dari bentuk ASCII Desimal ke ASCII Biner:
80 = 01010000₂
82 = 01010010₂
73 = 01001001₂
78 = 01001110₂
84 = 01010100₂
32 = 00100000₂
88 = 01011000₂

#### Output "PRINT X":
Jadi, keluaran output ***“PRINT X”*** pada bentuk ASCII Biner, adalah:
**<ins>(P)01010000₂ (R)01010010₂ (I)01001001₂ (N)01001110₂ (T)01010100₂ (spasi)00100000₂ (X)01011000₂**
