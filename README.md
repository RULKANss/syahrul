## Program mencari bilangan terbesar
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
masukan bilangan : 200000
masukan bilangan : 3000
masukan bilangan : 400
masukan bilangan : 22 
masukan bilangan : 0
bilangan terbesar= 1000000000
```


## Cara kerja program
Kode ini menerima masukan bilangan dari pengguna dan mencetak bilangan terbesar yang dimasukkan. Kode ini berfungsi dengan menyimpan nilai terbesar dalam variabel 'max', dan membandingkannya dengan setiap bilangan baru yang dimasukkan. Jika bilangan baru lebih besar dari 'max', maka 'max' akan diperbarui dengan nilai bilangan baru. Kode ini akan terus meminta masukan hingga pengguna memasukkan 0. Setelah itu, bilangan terbesar yang dimasukkan akan dicetak.
