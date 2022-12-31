# Praktikum9

## PERTEMUAN KE 14

## Python String

- String adalah jenis yang paling populer di Python.
- Untuk membuatnya hanya dengan melampirkan karakter dalam tanda kutip.
- Python memperlakukan tanda kutip tunggal (' ') sama dengan tanda kutip ganda (" ").
- Membuat string semudah memberi nilai pada sebuah variabel.

Contoh :
var1  # penggunaan petik tunggal = 'Hello World!' 
var2 =  # penggunaan petik ganda =  "Python Programming"
# Latihan 1

```bash
txt = 'Hello World'
```

1. Hitung jumlah karakter

    Untuk menghitung jumlah karakter, gunakan fungsi len()

```bash
         print(len(txt))
```

dengan kode program di atas maka akan menghasilkan output sebagai berikut:
! [image1](Screenshot/ss1.png)


2. Ambil karakter terakhir

    Untuk mengambil satu karakter dengan Cara mengambil satu karakter pada string yaitu dengan menggunakan kurung siku [] dan deklarasi nomor di dalam kurung siku dengan urutan ARRAY dan menggunakan titik dua lalu masukan nomor ARRAY selanjutnya. Untuk mengambil karakter terakhir, gunakan *index [-1]**.

```bash
     print(txt[-1])
```

dengan kode program di atas maka akan menghasilkan output sebagai berikut:
! [image2](Screenshot/ss2.png)
    
3. Ambil karakter index ke-2 sampai index ke-4 (llo)

    Untuk mengambil satu karakter dengan Cara mengambil satu karakter pada string yaitu dengan menggunakan kurung siku [] dan deklarasi nomor di dalam kurung siku dengan urutan ARRAY dan menggunakan titik dua lalu masukan nomor ARRAY selanjutnya. Untuk mengambil karakter *index ke-2 sampai index ke-4 gunakan *index [2:5]**.

```bash
    print (txt[2:5])
```

dengan kode program di atas maka akan menghasilkan output sebagai berikut:
! [image3](Screenshot/ss3.png)

4. Hilangkan spasi pada text tersebut (HelloWorld)

    Jika ingin menghilangkan spasi pada string, gunakan method replace(). Method replace() mengganti semua kemunculan string lama dengan yang baru atau paling banyak kemunculan. Di dalam method replace, kita dapat menggunakan 2 cara, yang pertama bisa menggunakan 
    (txt.replace(" ", "")) dan kedua dengan cara txt.replace(txt[5], "")).

```bash
    print(txt.replace(txt[5], "")).
```

dengan kode program di atas maka akan menghasilkan output sebagai berikut:
! [image4](Screenshot/ss4.png)


5. Ubah text menjadi huruf besar
    Untuk mengubah text menjadi huruf besar, gunakan method upper(). 

```bash
     print(txt.upper())
```

   dengan kode program di atas maka akan menghasilkan output sebagai berikut:
! [image5](Screenshot/ss5.png)

6. Ubah text menjadi huruf kecil

    Untuk mengubah text menjadi huruf kecil, menggunakan method lower().


```bash 
   print(txt.lower()) 
   ```
            
 dengan kode program di atas maka akan menghasilkan output sebagai berikut:
! [image6](Screenshot/ss6.png)

7. Ganti karakter H menjadi karakter J

    Untuk mengganti karakter 'H' menjadi karakter 'J 'gunakan metode replace()

```bash
    print(txt.replace("H" , "J"))
    print() 
```

dengan kode program di atas maka akan menghasilkan output sebagai berikut:
! [image7](Screenshot/ss7.png)

# Latihan 2

Lengkapi kode berikut :
```bash
umur = 21
txt = 'Hello, nama saya Shanti, dan umur saya adalah ... tahun'
```

```bash
    print(txt.format(umur))
```

- Penjelasan Latihan 2

Untuk memasukan variabel kedalam string, tambahkan kurung kurawal {} untuk menempatkan variabel sebelumnya.

```bash
    umur = 21
    txt = "\nHello, Nama Saya Krisno, dan umur saya adalah {0} tahun\n"

    print(txt.format(umur))
```

    dengan kode program di atas maka akan menghasilkan output sebagai berikut:
! [image8](Screenshot/ss8.png)

# TERIMA KASIH
