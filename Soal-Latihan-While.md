# Latihan `while` PHP

Latihan berikut bertujuan untuk memahami penggunaan perulangan `while` pada PHP.

Pola dasar:

```php
while (syarat) {
    statement;
}
```

## Petunjuk

Tuliskan kode PHP untuk menyelesaikan setiap soal.

Fokus latihan:

- Membuat kondisi `while`
- Mengubah nilai variabel di dalam `while`
- Memahami kapan perulangan berhenti
- Menggunakan operator perbandingan
- Menghindari infinite loop

Belum diperbolehkan menggunakan:

- `for`
- `foreach`
- `do...while`
- `break`
- `continue`
- Array

---

# 🟢 Level Mudah

## Soal 1 — Menampilkan Angka 1 sampai 5

Buat program yang menampilkan angka `1` sampai `5` menggunakan `while`.

Output yang diharapkan:

```text
1
2
3
4
5

```

---

## Soal 2 — Menampilkan Angka 5 sampai 1

Buat program yang menampilkan angka `5` sampai `1` menggunakan `while`.

Output yang diharapkan:

```text
5
4
3
2
1
```

---

## Soal 3 — Menampilkan Angka Genap

Buat program yang menampilkan angka genap dari `2` sampai `10` menggunakan `while`.

Output yang diharapkan:

```text
2
4
6
8
10
```

---

## Soal 4 — Menampilkan Angka Ganjil

Buat program yang menampilkan angka ganjil dari `1` sampai `9` menggunakan `while`.

Output yang diharapkan:

```text
1
3
5
7
9
```

---

## Soal 5 — Menghitung dari 1 sampai 10

Buat program yang menampilkan angka dari `1` sampai `10`.

Gunakan variabel `$angka` sebagai penghitung.

---

## Soal 6 — Menghitung Mundur

Buat program yang melakukan hitung mundur dari `10` sampai `1`.

Output yang diharapkan:

```text
10
9
8
7
6
5
4
3
2
1
```

---

## Soal 7 — Menampilkan Kelipatan 5

Buat program yang menampilkan kelipatan `5` dari `5` sampai `50`.

Output:

```text
5
10
15
20
25
30
35
40
45
50
```

---

## Soal 8 — Menampilkan Nama 5 Kali

Diketahui:

```php
$nama = "Budi";
```

Gunakan `while` untuk menampilkan nama tersebut sebanyak `5` kali.

---

## Soal 9 — Menampilkan Pesan

Buat program yang menampilkan teks:

```text
Belajar PHP
```

sebanyak `3` kali menggunakan `while`.

---

## Soal 10 — Angka dengan Kelipatan 2

Buat program yang menampilkan angka dari `2` sampai `20` dengan kelipatan `2`.

Output:

```text
2
4
6
8
10
12
14
16
18
20
```

---

# 🟡 Level Sedang

## Soal 11 — Menjumlahkan Angka

Buat program yang menghitung jumlah angka dari `1` sampai `10`.

Hasil yang diharapkan:

```text
55
```

---

## Soal 12 — Menjumlahkan Bilangan Genap

Buat program yang menghitung jumlah semua bilangan genap dari `1` sampai `20`.

Hasil yang diharapkan:

```text
110
```

---

## Soal 13 — Menjumlahkan Bilangan Ganjil

Buat program yang menghitung jumlah semua bilangan ganjil dari `1` sampai `15`.

Hasil yang diharapkan:

```text
64
```

---

## Soal 14 — Perkalian

Diketahui:

```php
$angka = 5;
```

Gunakan `while` untuk menampilkan tabel perkalian angka tersebut dari `1` sampai `10`.

Output:

```text
5 x 1 = 5
5 x 2 = 10
5 x 3 = 15
...
5 x 10 = 50
```

---

## Soal 15 — Pangkat Dua

Buat program yang menampilkan hasil pangkat dua dari angka `1` sampai `5`.

Output:

```text
1
4
9
16
25
```

---

## Soal 16 — Menghitung Banyak Angka

Buat program yang menghitung berapa banyak angka dari `1` sampai `100` yang habis dibagi `5`.

Output:

```text
20
```

---

## Soal 17 — Kelipatan 3

Buat program yang menampilkan semua angka dari `1` sampai `30` yang habis dibagi `3`.

Output:

```text
3
6
9
12
15
18
21
24
27
30
```

---

## Soal 18 — Menghitung Mundur Kelipatan 5

Buat program yang menampilkan angka:

```text
50
45
40
35
30
25
20
15
10
5
```

Gunakan `while`.

---

## Soal 19 — Total Harga

Diketahui:

```php
$harga = 10000;
$jumlah = 5;
```

Gunakan `while` untuk menghitung total harga berdasarkan jumlah barang.

Hasil:

```text
50000
```

---

## Soal 20 — Menghitung Bilangan Tertentu

Buat program yang menghitung jumlah semua angka dari `1` sampai `100` yang lebih besar dari `50`.

Hasil yang diharapkan:

```text
3825
```

---

# 🔴 Level Sulit

## Soal 21 — Faktorial

Diketahui:

```php
$angka = 5;
```

Gunakan `while` untuk menghitung faktorial dari angka tersebut.

Rumus:

```text
5! = 5 × 4 × 3 × 2 × 1
```

Hasil:

```text
120
```

---

## Soal 22 — Menghitung Jumlah Digit

Diketahui:

```php
$angka = 12345;
```

Gunakan `while` untuk menghitung berapa banyak digit yang dimiliki angka tersebut.

Hasil:

```text
5
```

---

## Soal 23 — Membalik Angka

Diketahui:

```php
$angka = 12345;
```

Gunakan `while` untuk membalik angka tersebut.

Hasil:

```text
54321
```

---

## Soal 24 — Menjumlahkan Digit

Diketahui:

```php
$angka = 12345;
```

Gunakan `while` untuk menjumlahkan setiap digit dari angka tersebut.

Perhitungannya:

```text
1 + 2 + 3 + 4 + 5
```

Hasil:

```text
15
```

---

## Soal 25 — Mencari Pangkat

Diketahui:

```php
$angka = 2;
$pangkat = 5;
```

Gunakan `while` untuk menghitung:

```text
2⁵
```

Hasil:

```text
32
```

---

## Soal 26 — Fibonacci

Buat program menggunakan `while` untuk menampilkan `10` angka pertama dari deret Fibonacci.

Deret Fibonacci dimulai dari:

```text
0 1 1 2 3 5 8 13 21 34
```

Output yang diharapkan:

```text
0
1
1
2
3
5
8
13
21
34
```

---

## Soal 27 — Mencari Bilangan Terbesar

Gunakan `while` untuk mencari bilangan terbesar dari angka `1` sampai `100`.

Simpan hasil terbesar ke dalam variabel `$terbesar`.

Output:

```text
100
```

---

## Soal 28 — Menghitung Bilangan yang Habis Dibagi

Gunakan `while` untuk menghitung berapa banyak angka dari `1` sampai `100` yang habis dibagi `3` dan `5`.

Hasil yang diharapkan:

```text
6
```

---

## Soal 29 — Menghitung Sampai Batas Tertentu

Diketahui:

```php
$saldo = 100000;
$pengeluaran = 15000;
```

Gunakan `while` untuk menghitung berapa kali pengeluaran dapat dilakukan sampai saldo tidak lagi mencukupi.

Setiap perulangan mengurangi saldo sebesar `$pengeluaran`.

Tampilkan jumlah transaksi yang dapat dilakukan.

Hasil:

```text
6
```

---

## Soal 30 — Menentukan Bilangan Prima

Diketahui:

```php
$angka = 17;
```

Gunakan `while` untuk menentukan apakah angka tersebut merupakan bilangan prima.

Jika bilangan tersebut prima, tampilkan:

```text
17 adalah bilangan prima
```

Jika bukan bilangan prima, tidak perlu menampilkan apa pun.

> **Catatan:** Tetap gunakan `while` sebagai perulangan utama. Jangan menggunakan `for`, `foreach`, atau `break`.
