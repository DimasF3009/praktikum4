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
![pic6](https://user-images.githubusercontent.com/115356128/199867176-3651b62d-6eae-4860-a160-a77509f5a65f.png)

### Hasil program / Output
![pic7](https://user-images.githubusercontent.com/115356128/199867234-a0844ac6-9482-4353-b117-36e638a97b78.png)

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





