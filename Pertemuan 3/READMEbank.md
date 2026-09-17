# Laporan Tugas — RekeningBank

## Identitas Mahasiswa

| Keterangan | Data |
|---|---|
| **Nama** | Muhamad Aria Khalil Mirzahamzah |
| **NPM** | 4525210094 |
| **Materi** | RekeningBank |
| **Bahasa Pemrograman** | Java dan PHP |

---

## Deskripsi

Program **RekeningBank** merupakan program yang dibuat untuk mengelola data rekening bank menggunakan bahasa pemrograman **Java** dan **PHP**.

Program ini menampilkan data rekening yang terdiri dari nomor rekening, nama pemilik, dan saldo. Selain itu, program menerapkan beberapa operasi seperti setor saldo, penarikan, pemotongan biaya administrasi, serta perhitungan bunga.

Program juga memiliki validasi untuk mencegah transaksi yang tidak sesuai dengan aturan, seperti penarikan melebihi batas transaksi dan saldo yang menjadi negatif.

---

# 1. Program Java

Program Java terdiri dari `RekeningBank.java` sebagai class untuk mengatur data dan operasi rekening, serta `Main.java` sebagai program utama.

## Cara Menjalankan Program Java

1. Buka **PowerShell** atau terminal.
2. Masuk ke folder Java:

```bash
cd java
```

3. Compile program:

```bash
javac Main.java
```

4. Jalankan program:

```bash
java Main
```

5. Hasil program akan ditampilkan pada terminal.

## Screenshot Running Java

<img width="1366" height="728" alt="image - 2026-09-18T010538 649" src="https://github.com/user-attachments/assets/500d25c6-2984-482f-9e84-9044daa531e3" />


### Penjelasan Hasil

Pada hasil running, program menampilkan jumlah rekening di awal, data rekening Ani, Budi, dan Citra, kemudian jumlah rekening setelah proses penambahan.

Program juga menjalankan operasi setor sebesar Rp500.000 ke rekening Ani, menolak penarikan yang melebihi batas transaksi, melakukan pemotongan biaya administrasi pada rekening Budi, dan menghitung bunga satu tahun dari saldo Ani.

---

# 2. Program PHP

Program PHP terdiri dari `RekeningBank.php` sebagai class untuk mengatur data dan operasi rekening, serta `main.php` sebagai program utama.

## Cara Menjalankan Program PHP

1. Buka **PowerShell** atau terminal.
2. Masuk ke folder PHP:

```bash
cd php
```

3. Jalankan program PHP:

```bash
php main.php
```

4. Program akan langsung berjalan dan hasilnya ditampilkan pada terminal.

## Screenshot Running PHP

<img width="1366" height="728" alt="image - 2026-09-18T010607 535" src="https://github.com/user-attachments/assets/557b1153-e210-448d-9bda-2c282beccc63" />


### Penjelasan Hasil

Program PHP menjalankan pengolahan data rekening dan beberapa operasi seperti setor saldo, penarikan, pemotongan biaya administrasi, serta perhitungan bunga.

Program juga melakukan validasi sehingga transaksi yang melanggar aturan akan ditolak.

---

# 3. Operasi pada RekeningBank

| Operasi | Penjelasan |
|---|---|
| **Setor** | Menambahkan sejumlah uang ke saldo rekening |
| **Tarik** | Mengurangi saldo berdasarkan jumlah uang yang ditarik |
| **Potong Admin** | Mengurangi saldo untuk biaya administrasi |
| **Bunga** | Menghitung bunga berdasarkan saldo rekening |
| **Validasi** | Memastikan data dan transaksi sesuai aturan |

---

# 4. Perbandingan Running Java dan PHP

| Bahasa | Perintah | Keterangan |
|---|---|---|
| **Java** | `javac Main.java` | Melakukan compile program |
| **Java** | `java Main` | Menjalankan program |
| **PHP** | `php main.php` | Langsung menjalankan file PHP |

---

# 5. Kesimpulan

Program **RekeningBank** berhasil dibuat menggunakan bahasa pemrograman Java dan PHP. Program dapat menampilkan data rekening serta menjalankan operasi setor, penarikan, pemotongan biaya administrasi, dan perhitungan bunga.

Program juga menerapkan validasi agar transaksi yang tidak sesuai dengan aturan dapat ditolak. Implementasi ini menunjukkan penerapan konsep class dan operasi rekening menggunakan Java dan PHP.
