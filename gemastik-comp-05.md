# Surabaya Town Square

### Deskripsi

Kota Surabaya adalah kota pahlawan yang terkenal dengan tata kota yang indah serta taman-tamannya yang bersih, rapi, dan nyaman. Salah satu yang menyebabkan keindahan tersebut adalah  penataan warna keramik yang digunakan.

Suatu hari, Ibu Walikota Surabaya sedang ingin menghias area terbuka berukuran N x M petak dengan cara mengkeramik lantai-lantainya. Beliau juga mengusulkan untuk membuat hiasan ornamen menarik pada lantainya menggunakan keramik-keramik spesial. Berikut adalah aturan pemasangan keramik yang Ibu Walikota usulkan:

Lantai area akan dikeramik dengan dua jenis keramik, yakni keramik dasar dan keramik spesial untuk ornamen. Masing-masing keramik berukuran 1x1 petak.

Ornamen adalah sebuah pola berukuran T x T petak yang disusun secara selang-seling antara keramik spesial dan dengan keramik dasar, sehingga tidak ada dua keramik spesial yang bersinggungan. Contoh di bawah tampak dua bentuk ornamen berukuran 3 x 3 petak yang memenuhi syarat di atas (keramik berwarna oranye dan keramik dasar berwarna putih):

![](https://image.ibb.co/nyhGDe/image1.png)

Area tersebut akan diberi beberapa ornamen yang memiliki ukuran dan bentuk yang sama. Ornamen-ornamen tersebut dipasang secara berulang agar memenuhi area yang memungkinkan, meskipun ada bagian ornamen yang terpotong oleh tepi area. Proses pengulangan dilakukan secara sejajar dengan tepi area.

Dua ornamen yang berdekatan terpisah tepat D petak secara horizontal dan vertikal. Area kosong diantaranya yang tidak diisi dengan ornamen akan diisi menggunakan keramik dasar.

Berikut contoh pengulangan ornamen dengan T=3 dan D=1 pada area 10 x 15 petak:

![](https://image.ibb.co/i5S56z/image2.png)

Perlu diperhatikan, pada area yang akan dikeramik terdapat beberapa petak yang tidak dapat dikeramik karena keberadaan bangunan atau pohon. Keindahan suatu area ditentukan dari banyaknya keramik khusus yang tampak setelah pemasangan. Tugas Anda sebagai programmer di Surabaya adalah membantu menghitung berapa maksimal keramik khusus yang tampak setelah pemasangan. 

Berikut adalah contoh area berukuran 8 x 16 petak yang akan diberi keramik. Petak berwarna abu-abu adalah petak yang tidak dapat dipasang keramik.

![](https://image.ibb.co/mONBye/satu.png)

Dan di bawah ini adalah pemilihan dan peletakan keramik yang optimal dengan T=3 dan D=2 sehingga diperoleh tampilan keramik spesial paling banyak.

![](https://image.ibb.co/cdiJde/dua.png)

### Format Masukan

Masukan diberikan dalam format berikut:

```
N M T D
L
X11 Y21 X21 Y21
X12 Y22 X22 Y22
...
X1L Y2L X2L Y2L
```

X1i Y2i X2i Y2i adalah koordinat pojok kiri atas (X1, Y1) dan pojok kanan bawah (X2, Y2) area ke-i yang tidak dapat dipasang keramik. Area-area tersebut diinputkan dengan membagi menjadi L buah segiempat yang saling lepas. Petak paling kiri atas berkoordinat (0, 0) dan petak paling kanan bawah berkoordinat (N-1, M-1).

### Format Keluaran

Keluarkan sebuah bilangan bulat yang merupakan banyak maksimum keramik spesial yang dapat terlihat setelah dipasang.

### Contoh Masukan (1)

```
10 10 3 2
0
```

### Contoh Keluaran (1)

```
20
```

### Batasan (1)

+ 1 ≤ N, M ≤ 50.000
+ 1 ≤ T, D ≤ 500
+ T ≤ N, M
+ L = 0
+ 0 ≤ X1i, X2i < N
+ 0 ≤ Y1i, Y2i  < M

Semua area yang tidak dapat dikeramik pada masukan, dijamin saling lepas

### Contoh Masukan (1)

```
8 16 3 2
13
0 2 0 3
0 6 0 7
0 12 0 13
6 1 7 2
6 5 7 6
6 9 7 10
6 13 7 14
1 2 1 3
2 0 3 7
4 2 4 3
1 12 1 13
2 10 3 15
4 12 4 13
```

### Contoh Keluaran (2)

```
22
```

### Batasan (2)

+ 1 ≤ N, M ≤ 50.000
+ 1 ≤ T, D ≤ 500
+ T ≤ N, M
+ 0 ≤ L ≤ 100
+ 0 ≤ X1i, X2i < N
+ 0 ≤ Y1i, Y2i  < M

Semua area yang tidak dapat dikeramik pada masukan, dijamin saling lepas