# 1. Urutan Aneh

### Deskripsi

Buatlah program yang melakukan pengurutan N (2≤N≤1000) buah bilangan seperti pada contoh kasus di bawah ini.

### Format Masukan

+ Baris pertama berisi satu buah bilangan N. 

+ Baris kedua berisi N buah bilangan bulat Xi. 

+ Setiap bilangan dipastikan hanya antara 0-100.

### Format Keluaran

N buah baris berisi urutan bilangan sesuai dengan contoh

### Contoh Masukan

```

10

1 11 12 2 13 23 31 62 71 81

```

### Contoh Keluaran

```

1

11

31

71

81

2

12

62

13

23

```

# 2. Pohon

### Deskripsi

Untuk menghilangkan penat Pak Blangkon sering sekali jalan-jalan ke pekarangan di belakang rumahnya. Saat berada di posisi tertentu Pak Blangkon menyadari bahwa di sekelilingnya ada N buah pohon. Namun, karena terbatasnya pandangan hanya beberapa pohon saja yang bisa terlihat oleh Pak Blankon, karena pohon tertentu berada tepat di belakang pohon lainnya saat pandangan tertuju pada arah tertentu. Jika dilihat dari atas dalam koordinat dua dimensi, Pak Blangkon ada di posisi (x,y) sedangkan pohon-pohonnya ada di posisi (pi,qi). Seperti contoh pada gambar di bawah ini:

![Pohon](https://image.ibb.co/d297Uz/pohon.png)

Seperti terlihat pada gambar di atas dari 8 pohon, hanya 5 yang bisa dilihat secara langsung oleh Pak Blangkon, sedangkan tiga pohon lainnya terhalang oleh pohon di depannya. Jika diketahui lokasi Pak Blangkon beserta N buah pohon, buatlah program untuk menghitung banyaknya pohon yang bisa terlihat secara langsung oleh Pak Blangkon.

### Format Masukan

Baris pertama adalah N, X dan Y yang menyatakan banyaknya pohon dan posisi Pak Blangkon di mana 2 ≤ N ≤ 100. N baris berikutnya berisi pi dan qi yang menyatakan posisi pohon ke-i, di mana 0 ≤ X,Y,pi,qi ≤ 1000.

### Format Keluaran

Banyaknya pohon yang dapat dilihat Pak Blangkon.

### Contoh Masukan

```

8 4 2

1 5

2 1

2 4

3 3

6 3

6 6

7 7

10 5

```

### Contoh Keluaran

```

5

```

# 3. Pertandingan

### Deskripsi

Dalam sebuah pertandingan olahraga, Budi diberikan kesempatan untuk memilih urutan pemain yang harus dilawannya. Asumsikan ada N orang lawan yang masing-masing memiliki tingkat kemahiran Ai. Setelah Budi berhasil mengalahkan pemain ke-i, tingkat kemahirannya akan bertambah sebanyak Bi yang akan digunakan untuk melawan pemain selanjutnya. Perlu diingat bahwa Budi hanya bisa mengalahkan pemain dengan tingkat kemahiran yang lebih rendah atau sama dengan dirinya sendiri. Jika Budi memiliki tingkat kemahiran awal M, tentukan pemain manakah yang harus dilawan Budi secara berurutan sampai dia tidak bisa lagi mengalahkan lawannya sehingga Budi mendapatkan tingkat kemahiran yang maksimal.

### Format Masukan

+ Baris pertama dua buah bilangan N dan M (1≤N, M≤100)

+ Baris kedua N buah bilangan Ai (1≤Ai≤1000)

+ Baris ketiga N buah bilangan Bi (1≤Bi≤1000)

### Format Keluaran

+ Tingkat kemahiran maksimal yang akan didapatkan Budi.

### Contoh Masukan 1

```

4 2

8 9 3 2

5 4 1 3

```

Contoh Keluaran 1

```

6

```

Contoh Masukan 2

```

5 3

8 4 5 6 7

9 8 7 5 6

```

Contoh Keluaran 2

```

3

```

Contoh Masukan 3

```

5 9

2 3 6 7 8

3 4 2 2 3

```

Contoh Keluaran 3

```

23

```