# Praktikum 3

## Latihan 1

### Penggunaan End

#### -Penggunaan end pada Python berfunngsi untuk memberi pemisah antara quotes yang kita buat

![gambar](file 1.png)

![gambar](file 1(1).png)

### Penggunaan Separator

#### -penggunaan separator pada python berfungsi sebagai pemisah dari setiap variabel yang telah di beri nilai

![gambar](file 2.png)

![gambar](file 2(1).png)

### String Format

#### -String Formatting memungkingkan kita untuk memberikan item kedalam string daripada kita mencoba menggabungkan string menggunakan koma atau striing concatenation

![gambar](file 3.png)

![gambar](file 3(1).png)

#### -ini contoh string concatenation

![gambar](file 4.png)

![gambar](file 4(1).png)

## Latihan 2

#### -Tentukan dahulu variabel yang akan di gunakan, misalnya a dan b

#### -Beri inputan pada variabel 

#### -Setelah diberi input, ekdpresikan variabel yang telah diberi inputan 

#### -Lalu gabungkan variabel a dan bdengan  Formatting String

![gambar](file 5.png)

### Konversi nilai Variabel 

#### -Konversi nilai variabel yang masih berbentuk 'string' pada 'integer'

### -Setelah itu menjumlahkan dan membagi dengan ekspresikan dalam bentuk Formatting String

![gambar](file 6.png)

![gambar](file 6(1).png)

## Latihan 3

### Buatlah kode program menggunakan string formatting untuk menghasilkan output seperti gambar dibawah ini

![gambar](file 7.png)

 #### string =""
 #### x = int(input("Masukkan angka :"))
 #### a = x
 #### while a >= 0:
    b = a
    while b > 0:
        #### string = string + "   "
        b = b - 1
    l = 1
    while l < (x - (a-1)):
        string = string + " * "
        l = l + 1
    r = 1
    while r < l -1:
        string = string + " * "
        r = r + 1
    string = string + "\n\n"
    a = a -1
 #### a = 1
 #### while a <= x:
    b = a + 1
    while b > 1:
        string = string + "   "
        b = b -1
    l = 0
    while l < (x - a):
        string = string + " * "
        l = l + 1
    r = l
    while r > 1:
        string = string + " * "
        r = r - 1
    string = string + "\n\n"
    a = a + 1
print(string)

#### -agar menampilkan output yang sama dengan contoh di atas, yaitu dengan menjalankan hasil daari statement yang telah dibuat lalu kita inputkan numeric 5

![gambar](file 8.png)

# Praktikum 3

![gambar](file 9.png)

#### -Program diatas saya mengimport modul math yang sudah di sediakan oleh python. Fungsinya supaya saya dapat menyertakan nilai phi yang sudah tersedia dalam modul tersebut dengan perintah math.pi jika kita coba mencetak fungsi tersebut maka akan menghasilkan nilai 3.14

#### -Selanjutnya kita memerlukan nilai jari-jari (r) yang nantinya akan di masukan oleh pengguna pada layar. Kita menggunakan fungsi input() yang nilainya di konversi ke tipe data float 




