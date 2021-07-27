# Maxmin

### Deskripsi

Diberikan sebuah persegi berukuran NxN yang berisi angka-angka berbeda dari 1 hingga N2. Anda diminta untuk menemukan angka maksimal pada setiap baris, kemudian keluarkan angka minimal dari angka-angka tersebut.

Kawan Anda juga sedang mengerjakan soal yang sama, namun ternyata ia melakukan kesalahan! Algoritma yang ia buat adalah sebagai berikut: temukan angka minimal pada setiap kolom, kemudian keluarkan angka maksimal dari angka-angka tersebut.

Anda ingin membuktikan bahwa kawan Anda melakukan kesalahan dengan cara memberikan K buah kasus uji berbeda yang mana solusi yang dihasilkan kawan Anda adalah salah.

Jika ada banyak keluaran, keluarkan yang mana saja.

### Format Masukan

Sebuah baris berisi N dan K.

### Format Keluaran

K buah persegi berukuran NxN (sehingga terdapat KxN buah baris).

### Contoh Masukan

```
10 2
```

### Contoh Keluaran

```
89 6 91 50 7 58 83 61 3 49
78 55 90 62 4 77 27 10 85 80
25 76 23 22 45 52 88 67 11 40
16 98 17 59 66 34 18 2 97 43
71 35 100 38 1 69 86 31 33 51
64 87 84 14 48 99 60 53 92 75
46 70 94 72 29 82 36 74 21 5
73 9 26 47 20 41 65 54 24 93
95 96 37 32 56 57 63 12 30 19
28 44 79 39 42 13 81 15 8 68
84 4 68 96 79 48 18 3 43 83
82 77 42 22 95 69 92 58 55 81
66 62 93 41 30 38 28 70 37 17
29 34 51 91 87 1 60 8 26 100
19 11 35 21 64 94 65 14 72 74
86 78 40 54 47 31 27 88 90 20
61 57 99 89 52 10 97 24 45 44
13 12 23 15 33 2 80 85 25 16
5 56 49 75 73 7 59 36 67 50
39 71 76 46 63 32 9 53 6 98
```

### Penjelasan

+ Pada persegi pertama, keluaran yang benar adalah 81 namun kawan Anda mengeluarkan 18.
+ Pada persegi kedua, keluaran yang benar adalah 75 namun kawan Anda mengeluarkan 30.

### Batasan (1)

+ 5 ≤ N ≤ 10
+ K = 1

### Batasan (2)

+ 5 ≤ N ≤ 10
+ 1 ≤ K ≤ 10.000