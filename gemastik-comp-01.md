# Tarung

### Deskripsi

Terdapat N petarung. Petarung ke-i memiliki kekuatan Pi. Jika dua petarung i dan j bertarung, maka petarung dengan kekuatan lebih tinggi akan menang, dan kekuatan dari petarung pemenang tersebut menjadi abs(Pi - Pj). Jika kekuatan mereka sama, maka petarung dengan indeks lebih kecil akan menang namun kekuatannya akan menjadi 0.

Mula-mula, petarung pertama akan melawan petarung kedua. Pemenangnya akan melawan petarung ketiga, dan seterusnya hingga petarung ke-N. Juara akhirnya adalah pemenang dari pertarungan terakhir.

Anda adalah petarung dengan indeks 1 dan ingin memenangkan pertandingan. Anda dapat mengubah urutan petarung-petarung lainnya (petarung indeks 2 sampai dengan N). Bisakah Anda memenangkan pertandingan?

### Format Masukan

Masukan diberikan dalam format berikut:
```
N
P1 P2 … PN
```
### Format Keluaran

Jika terdapat permutasi yang sehingga Anda dapat memenangkan pertandingan, keluarkan:
```
menang
Q1 Q2 … QN
```
dengan Q merupakan permutasi dari P.

Jika ada banyak kemungkinan, keluarkan yang mana saja.

Jika tidak ada permutasi yang memungkinkan Anda menang, keluarkan:

```
kalah
```

### Contoh Masukan 1

```
5
3 4 2 -4 1
```

### Contoh Keluaran 1

```
menang
3 1 2 -4 4
```

### Contoh Masukan 2

```
2
3 4
```

### Contoh Keluaran 2

```
kalah
```

### Batasan (1)

+ 1 ≤ N ≤ 10
+ -109 ≤ Pi ≤ 109

### Batasan (2)

+ 1 ≤ N ≤ 100.000
+ -109 ≤ Pi ≤ 109