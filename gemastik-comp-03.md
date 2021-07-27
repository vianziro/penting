# Kuliner-an

### Deskripsi

Karena sedang marak start-up, Pak Blangkon tertarik untuk mencoba membuat sebuah start-up juga. Beliau menamakannya sebagai "Kuliner-an". Kuliner-an ini bertujuan untuk memudahkan pelanggan memesan sejumlah makanan, tentunya bisa lebih dari satu porsi makanan. Pembeli juga tidak perlu memikirkan akan memesan di restoran mana, karena hal ini sudah diatur oleh aplikasi Kuliner-an.

Akhirnya aplikasi yang dibuat pun telah jadi, dan tibalah saatnya untuk melakukan pengujian. Karena suatu alasan tertentu, aplikasi Kuliner-an hanya terhubung dengan N orang pembeli dan N buah restoran. Menu yang tersedia di aplikasi Kuliner-an juga hanya 1 macam, yaitu gudeg. Lebih anehnya lagi, setiap pembeli harus memesan tepat 2 porsi dan setiap restoran juga harus menerima pesanan tepat 2 porsi. Dua porsi yang dipesan oleh seorang pembeli bisa dipesankan ke 1 restoran saja, atau bisa dipesankan ke 2 restoran berbeda (masing-masing restoran menerima 1 pesanan).

Agar bisa melakukan optimasi, Pak Blangkon penasaran ada berapa banyak kemungkinan pengaturan seluruh pesanan tersebut. Pak Blangkon meminta Anda sebagai peserta Gemastik 2018 untuk membantunya.

### Format Masukan

Baris pertama berisi sebuah bilangan T, yang menyatakan banyaknya kasus uji.

Setiap kasus uji diberikan dalam format berikut:

```
N
```

### Format Keluaran

Untuk setiap kasus uji, keluarkan sebuah baris berisi banyak kemungkinan pengaturan seluruh pesanan tersebut. Karena bisa jadi jawabannya sangat besar, keluarkan jawabannya dalam modulo 1.000.000.007 (109+7).

### Contoh Masukan

```
2
2
1
```

### Contoh Keluaran

```
3
1
```

### Penjelasan

Misalkan kedua pembeli tersebut adalah Semar dan Gareng, dan dua restoran yang tersedia adalah Gudeg Pak Petruk dan Gudeg Pak Bagong. Seluruh kemungkinan pengaturan pesanan adalah sebagai berikut:

+ Semar mendapatkan 2 porsi dari Gudeg Pak Petruk dan Gareng mendapatkan 2 porsi dari Gudeg Pak Bagong.
+ Semar mendapatkan 2 porsi dari Gudeg Pak Bagong dan Gareng mendapatkan 2 porsi dari Gudeg Pak Petruk.
+ Semar mendapatkan 1 porsi dari masing-masing restoran (sehingga total mendapatkan 2 porsi) dan Gareng juga mendapatkan 1 porsi dari masing-masing restoran (sehingga total mendapatkan 2 porsi).

### Batasan (1)

+ 1 ≤ T ≤ 5
+ 1 ≤ N ≤ 5

### Batasan (2)

+ 1 ≤ T ≤ 100
+ 1 ≤ N ≤ 100.000
