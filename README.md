# Latihan 1
## Buat program sederhada dengan input 2 buah bilangan, kemudian tentukan bilangan terbesar dari kedua bilangan tersebut menggunakan statement if.
### Penjelasan program
1. user1=int(input("Masukan bil pertama = ")) Untuk menentukan jumlah input yang di inginkan sesuai tipe data yaitu interger tipe data bilangan bulat

2. user2=int(input("Masukan bil kedua = ")) Untuk menentukan jumlah input yang di inginkan sesuai tipe data yaitu interger tipe data bilangan bulat

3. if untuk membandingkan kedua bilangan user1 dan user2 jika true maka akan mencetak 
print(f"{user1} lebih besar dari {user2}")

4. Jika false maka program akan mencetak
print(f"{user1} lebih kecil dari {user2}")
### Gambar program
![pic1](https://user-images.githubusercontent.com/115356128/199863645-851f4cad-0cb7-41de-b7a7-f99e20eaeb8e.png)

### Hasil Program / Output
jika program false

![pic2](https://user-images.githubusercontent.com/115356128/199864521-13d1f4d7-c79f-4b2d-a4f2-65e60bc6ab09.png)

jika program true

![pic3](https://user-images.githubusercontent.com/115356128/199864860-48c7e5ea-cd8e-4e86-8642-08913b33ab16.png)

# Latihan 2
## Buat program untuk mengurutkan data berdasarkan input sejumlah data (minimal 3 variable input atau lebih), kemudian tampilkan hasilnya secara berurutan mulai dari data terkecil.
### Gambar Program
![pic4](https://user-images.githubusercontent.com/115356128/199866098-13cd8d7c-d41d-4c6b-bd77-be22e88ee774.png)

### Hasil program / Output
![pic5](https://user-images.githubusercontent.com/115356128/199866441-c5b28c6f-a23f-43b4-95c6-f7c7d8f04ffc.png)

# Latihan 1 (Perulangan)
## Buat program dengan perulangan bertingkat (nested) for
### Gambar Program
![pic6](https://user-images.githubusercontent.com/115356128/200099905-ec2c54a3-c4cf-4997-8390-480325164f72.png)

### Hasil program / Output
![pic7](https://user-images.githubusercontent.com/115356128/200099918-50a64294-05f4-4c4a-a1cc-f961a9e45adf.png)

# Latihan 2 (Perulangan)
## 1. Tampilkan n bilangan acak yang lebih kecil dari 0.5.
## 2. Nilai n diisi pada saat runtime
## 3. Anda bisa menggunakan kombinasi while dan for untuk menyelesaikannya

### Gambar program
![pic8](https://user-images.githubusercontent.com/115356128/199867953-796794d8-9fc3-4d7d-8ddf-685d7e70fa92.png)

#### Penjelasan  Program
1. Import random dari library python 
2. user=int(input("Masukan angka = ")) Untuk menentukan jumlah input yang di inginkan sesuai tipe data yaitu interger tipe data bilangan bulat
3. for i in range ( user ) : Untuk Pengulangan dengan range user
4. lalu cetak print("Data ke", i+1, "=",(random.uniform (0.1,0.5))) dan memanggil random dengan range 0.1 sampai 0.5

#### Hasil program / Output
![pic9](https://user-images.githubusercontent.com/115356128/199868656-726aafac-d0f4-4e15-bfeb-063659d2e54a.png)

# Tugas Praktikum 2
## Buat program sederhana dengan input tiga buah bilangan, dari ketiga bilangan tersebut tampilkan bilangan terbesarnya. Gunakan statement if.
### Gambar Program
![pic10](https://user-images.githubusercontent.com/115356128/200053973-ff8d77b6-a71b-4d43-a966-4bbe9b09a50d.png)

### Penjelasan Program
1. a=int(input("Masukan angka = ")) Untuk menentukan jumlah input yang di inginkan sesuai tipe data yaitu interger tipe data bilangan bulat.
2. b=int(input("Masukan angka = ")) Untuk menentukan jumlah input yang di inginkan sesuai tipe data yaitu interger tipe data bilangan bulat.
3. c=int(input("Masukan angka = ")) Untuk menentukan jumlah input yang di inginkan sesuai tipe data yaitu interger tipe data bilangan bulat.
4. if a>b and a>c:
    print(f"Dari bilangan '{a} {b} {c}' bilangan yang terbesar adalah", a)
  Artinya jika a lebih besar dari b dan, a lebih besar dari c maka print a
5. elif b>a and b>c or a>c:
   print(f"Dari bilangan '{a} {b} {c}' bilangan yang terbesar adalah", b)
  Artinya jika b lebih besar dari a dan, b lebih besar dari c, atau a lebih besar dari c maka print b
6. Jika bilangan a atau b lebih kecil dari c maka print c

### Flowchart
![pic11](https://user-images.githubusercontent.com/115356128/200065861-68769a3b-fe56-49cc-8888-471cfea820ea.png)

### Hasil Program / Output
![pic12](https://user-images.githubusercontent.com/115356128/200062999-a3fd5da2-d019-4f0d-968a-a442a5f8d7b6.png)

![pic13](https://user-images.githubusercontent.com/115356128/200063032-e9531625-6c4d-4894-bbee-0ec5c3e2bb75.png)

![pic14](https://user-images.githubusercontent.com/115356128/200063060-6e6689c4-2a02-48c2-b85e-d36f5d3258cb.png)

# Tugas Praktikum 3
## Program Sederhana Untuk Menghitung Jumlah Laba Hasil Investasi Seorang Pengusaha Selama 8 Bulan
### Gambar Program
![pic15](https://user-images.githubusercontent.com/115356128/200071722-cd94a6fd-27c1-4860-a34e-030871b3b161.png)

### Penjelasan Program
1. x=100000000 Dengan pemisalan atau dideklarasikan x adalah 100000000
2. print (" Modal Awal:",x) Menampilkan kalimat Modal Awal : dan data yang berisi di x yaitu 100000000
3. a=0x, b=0x, c=0.01x, d=0.01x, e=0.05x, f=0.05x, g=0.05x, h=0.03x Untuk Mendeklarasikan presentase laba tiap bulan dan di kali dengan x atau data inputan modal investasi yaitu 100000000
4. y=[a,b,c,d,e,f,g,h] untuk menentukan syarat y= yang berisi a,b,c,d,e,f,g,h
5. For i in range (len (y)) Print (“laba bulan ke-“,i+1,”sebesar:” ,y[i]) untuk perulangan data dengan isi data yaitu Ydengan menampilkan urutan laba perbulan sesuai range yang di tentukan dengan hasil ke untukan yang di inpput dari data Y
6. Z= (a+b+c+d+e+f+g+h) Print (“jumlah laba selama 8 bulan adalah:”) Z berisi data penjumlahan data angka yang ada didalam kode a,b,c,d,e,f,g,h yang akan di tampilakan atau dicetak di jumlah laba selama 8 bulan

### Flowchart
![pic16](https://user-images.githubusercontent.com/115356128/200099410-ec8cf8bd-adad-4069-8398-b1e256eb2ba8.png)

### Hasil Program / Output
![pic17](https://user-images.githubusercontent.com/115356128/200099661-c334b308-ec7a-460c-aba8-d9319a5bf321.png)








