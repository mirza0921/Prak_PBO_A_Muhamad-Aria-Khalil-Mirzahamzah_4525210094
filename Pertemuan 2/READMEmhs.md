# Laporan Tugas — Nilai Mahasiswa

## Identitas Mahasiswa

| Keterangan | Data |
|---|---|
| **Nama** | Muhamad Aria Khalil Mirzahamzah |
| **NPM** | 4525210094 |
| **Materi** | Nilai Mahasiswa |
| **Bahasa Pemrograman** | Java dan PHP |

---

## Deskripsi

Program **Nilai Mahasiswa** merupakan program yang dibuat untuk mengolah data nilai mahasiswa menggunakan bahasa pemrograman **Java** dan **PHP**.

Program menampilkan data mahasiswa berupa NIM, nama, nilai akhir, dan mutu. Program juga menerapkan validasi untuk menolak data yang tidak sesuai dengan aturan, seperti nilai di luar rentang 0–100 dan NIM yang kosong.

---

## 1. Program Java

Program Java terdiri dari file `Mahasiswa.java` sebagai class untuk data mahasiswa dan `Main.java` sebagai program utama.

### Cara Menjalankan Program Java

1. Buka **PowerShell** atau terminal pada folder `java`.
2. Masuk ke folder Java jika belum berada di dalamnya:

```bash
cd java
```

3. Compile program Java:

```bash
javac Main.java
```

4. Setelah berhasil di-compile, jalankan program:

```bash
java Main
```

5. Program akan menampilkan rekap nilai mahasiswa dan pesan penolakan apabila terdapat data yang melanggar aturan.

### Screenshot Running Java

<img width="1366" height="728" alt="image - 2026-09-18T002817 850" src="https://github.com/user-attachments/assets/0b8b6812-301a-4034-840c-8d8ab8127bdd" />


Pada hasil running terlihat rekap nilai tiga mahasiswa, yaitu Ani Lestari, Budi Santoso, dan Citra Wijaya. Program juga menolak nilai tugas `150.0` karena nilai harus berada di antara `0.0` sampai `100.0`, serta menolak data dengan NIM kosong.

---

## 2. Program PHP

Program PHP terdiri dari file `Mahasiswa.php` sebagai class untuk data mahasiswa dan `Main.php` sebagai program utama.

### Cara Menjalankan Program PHP

1. Buka **PowerShell** atau terminal pada folder `php`.
2. Masuk ke folder PHP:

```bash
cd php
```

3. Jalankan program PHP:

```bash
php Main.php
```

4. Program akan langsung menampilkan hasil rekap nilai mahasiswa pada terminal.

### Screenshot Running PHP

<img width="1366" height="728" alt="image - 2026-09-18T003049 994" src="https://github.com/user-attachments/assets/789b49b3-6595-42d6-93ba-0daf14054a17" />


Pada hasil running terlihat rekap nilai mahasiswa dan validasi data. Program menolak nilai tugas `150` karena berada di luar rentang nilai `0–100`, serta menolak data karena NIM tidak boleh kosong.

---

## 3. Perbandingan Running Java dan PHP

| Bahasa | Perintah Menjalankan | Hasil |
|---|---|---|
| **Java** | `javac Main.java` kemudian `java Main` | Program di-compile terlebih dahulu, kemudian dijalankan |
| **PHP** | `php Main.php` | Program dapat langsung dijalankan melalui terminal |

---

## 4. Kesimpulan

Program **Nilai Mahasiswa** berhasil dibuat menggunakan bahasa Java dan PHP. Kedua program menghasilkan rekap nilai mahasiswa serta menerapkan validasi terhadap data yang tidak sesuai dengan aturan. Perbedaan utama pada proses running adalah Java perlu melalui tahap compile, sedangkan PHP dapat langsung dijalankan menggunakan perintah `php`.
