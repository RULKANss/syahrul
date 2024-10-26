## 1. Program mencari bilangan terbesar
Program sederhana untuk mencari nilai terbesar dari sekumpulan bilangan yang dimasukkan oleh pengguna menggunakan loop while True dan break statement.


## Deskripsi program
Program ini dibuat menggunakan bahasa Python dengan fitur:
- Menggunakan while True untuk perulangan tak terbatas
- Menggunakan break statement untuk menghentikan program
- Membandingkan setiap input dengan nilai maksimum yang tersimpan
- Menampilkan bilangan terbesar yang ditemukan


## Flowchart program
![flowchart](/flocart2.png)


## Kode program
```
max = 0
bilangan = int(input("masukan bilangan : "))
while bilangan != 0 :
   if bilangan > max :
        max = bilangan
    bilangan = int (input("masukan bilangan : "))
print (f"bilangan terbesar= {max}")
```


## out-put program
```
PS C:\project ai> & C:/Users/Syahrul/AppData/Local/Microsoft/WindowsApps/python3.11.exe "c:/project ai/rul.py"
masukan bilangan : 111
masukan bilangan : 11
masukan bilangan : 10122
masukan bilangan : 1
masukan bilangan : 0
bilangan terbesar= 10122
```


## Cara kerja program
Kode ini menerima masukan bilangan dari pengguna dan mencetak bilangan terbesar yang dimasukkan. Kode ini berfungsi dengan menyimpan nilai terbesar dalam variabel 'max', dan membandingkannya dengan setiap bilangan baru yang dimasukkan. Jika bilangan baru lebih besar dari 'max', maka 'max' akan diperbarui dengan nilai bilangan baru. Kode ini akan terus meminta masukan hingga pengguna memasukkan 0. Setelah itu, bilangan terbesar yang dimasukkan akan dicetak.



## 2. Bilangan terbesar 3 variabel
Program sederhana untuk menentukan bilangan terbesar dari tiga angka yang diinputkan pengguna.

## Deskripsi program
Program ini sebagai berikut
- Meminta user memasukkan 3 bilangan berbeda
- Membandingkan ketiga bilangan tersebut
- Menentukan bilangan mana yang terbesar
- Menampilkan hasilnya ke layar

  
## Flowchart program
![flocart1](/flocart1.png)


## Kode program 
```
a = int(input("Masukkan bilangan A: "))
b = int(input("Masukkan bilangan B: "))
c = int(input("Masukkan bilangan C: "))

if a > b:
    if a > c:
        print("Terbesar adalah A")
        terbesar = a
    else:
        print("Terbesar adalah c")
        terbesar = c
else:
    if b > c:
        print("Terbesar adalah B")
        terbesar = b
    else:
        print("Terbesar adalah C")

print(f"Bilangan terbesar adalah: {terbesar}")
```


## Output program
```
PS C:\project ai> & C:/Users/Syahrul/AppData/Local/Microsoft/WindowsApps/python3.11.exe "c:/project ai/syahrul.py"
Masukkan bilangan A: 12112211111223312
Masukkan bilangan B: 10000002312122
Masukkan bilangan C: 232321
Terbesar adalah A
Bilangan terbesar adalah: 12112211111223312
```


## Cara kerja program
Input:
 diminta untuk memasukkan tiga bilangan (A, B, dan C) melalui fungsi input().
Setiap input yang diterima dikonversi menjadi tipe data int agar dapat dibandingkan secara numerik.
Logika Penentuan Bilangan Terbesar:

Kode menggunakan struktur if bersarang untuk membandingkan nilai dari ketiga bilangan.
Proses perbandingan dilakukan sebagai berikut:
- Pertama, kode memeriksa apakah A lebih besar dari B.
- Jika ya, maka kode memeriksa apakah A juga lebih besar dari C.
- Jika A lebih besar dari C, maka A adalah bilangan terbesar.
- Jika tidak, C adalah bilangan terbesar.
- Jika A tidak lebih besar dari B, maka kode memeriksa apakah B lebih besar dari C.
- Jika ya, maka B adalah bilangan terbesar.
- Jika tidak, C adalah bilangan terbesar.
- Hasil dari perbandingan ini disimpan dalam variabel terbesar.

   Hasil:
Setelah menentukan bilangan terbesar, kode mencetak hasilnya ke konsol dengan menyebutkan bilangan mana yang terbesar.
