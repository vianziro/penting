# 3 Angka Zig-Zag

### Deskripsi

Petruk menuliskan N buah bilangan bulat berbeda, A1, A2, ..., AN, pada sebuah kertas. Kemudian, kertas tersebut diberikan ke Bagong. Bagong kemudian bertanya, "apa ini?". Petruk menjawab, "ini adalah kertas yang bertuliskan N buah bilangan bulat berbeda.". Tiba-tiba Gareng menghampiri mereka berdua, dan seketika melihat tulisan yang ada di kertas tersebut.

Dengan isengnya, Gareng menyeletuk, "ada berapa subbarisan zig-zag 3 bilangan yang bisa dibentuk dari N buah bilangan ini?". Gareng menjelaskan bahwa tiga buah bilangan a, b, c dikatakan subbarisan zig-zag 3 bilangan jika dan hanya jika memenuhi syarat: "a > b dan b < c" atau "a < b dan b > c". Petruk dan Bagong lalu terdiam kebingungan.

Sebagai peserta Gemastik 2018, bantulah Petruk dan Bagong menjawab pertanyaan yang diajukan oleh Gareng.

### Format Masukan

Baris pertama berisi sebuah bilangan T, yang menyatakan banyaknya kasus uji.

Setiap kasus uji diberikan dalam format berikut:

```
N
A1 A2 … AN
```

### Format Keluaran

T buah baris, masing-masing berisi jawaban dari pertanyaan yang diajukan oleh Gareng.

### Contoh Masukan

```
2
5
2 8 1 5 7
4
2 8 1 5
```

### Contoh Keluaran

```
8
4
```

### Penjelasan

Untuk contoh kasus uji pertama di atas, subbarisan zig-zag 3 bilangan yang bisa dibentuk adalah :

+ 2, 8, 1
+ 2, 8, 5
+ 2, 8, 7
+ 2, 1, 5
+ 2, 1, 7
+ 8, 1, 5
+ 8, 1, 7
+ 8, 5, 7

### Batasan (1)

+ 1 ≤ T ≤ 100
+ 3 ≤ N ≤ 100
+ 1 ≤ Ai ≤ 10.000

Dijamin seluruh Ai berbeda-beda

### Batasan (2)

+ 1 ≤ T ≤ 100
+ 3 ≤ N ≤ 1.000
+ 1 ≤ Ai ≤ 10.000

Dijamin seluruh Ai berbeda-beda