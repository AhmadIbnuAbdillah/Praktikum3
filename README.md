# Praktikum3

Ahmad Ibnu Abdillah

Bahasa Pemrograman

312410489

# Kode Pemrograman
```Python
max_number = int(0)
    
while True:
    number = int(input("Masukkan bilangan (input 0 untuk berhenti): "))
        
    if number == 0:
        break
        
    if number > max_number:
        max_number = number
    
print("Bilangan terbesar: ", max_number)

```

# Hasil Eksekusi Program
![Foto](https://github.com/AhmadIbnuAbdillah/Foto/blob/main/Screenshot%202024-10-22%20221323.png?raw=true)

# Penjelasan Kode
```Python
max_number = int(0)
```
Fungsi: Menginisialisasi variabel max_number dengan nilai 0. Variabel ini akan menyimpan bilangan terbesar yang ditemukan sejauh ini.

int(0): Fungsi int() mengonversi argumen di dalamnya menjadi tipe data integer (bilangan bulat). Namun, dalam konteks ini, karena 0 sudah bilangan bulat, ini sebenarnya tidak perlu, cukup menulis max_number = 0 juga sudah benar.

```Python
while True:
```
Fungsi: Ini memulai sebuah loop yang akan berjalan terus-menerus sampai ada perintah untuk berhenti. Loop ini adalah infinite loop karena kondisinya selalu True. Dalam kode ini, loop hanya akan dihentikan oleh perintah break.

```Python
number = int(input("Masukkan bilangan (input 0 untuk berhenti): "))
```
Fungsi: Kode ini meminta input dari pengguna berupa bilangan, mengonversinya menjadi tipe data int (bilangan bulat), dan menyimpannya di variabel number.

input(): Berfungsi untuk mengambil input dari pengguna, yang secara default berupa tipe data string.

int(): Mengonversi input string menjadi bilangan bulat.

```Python
if number == 0:
    break
```
Fungsi: Memeriksa apakah input dari pengguna adalah 0. Jika number == 0, program akan menghentikan loop dengan menggunakan perintah break.

break: Digunakan untuk keluar dari loop, menghentikan eksekusi loop saat ini.

```Python
if number > max_number:
    max_number = number
```
Fungsi: Memeriksa apakah bilangan yang baru dimasukkan (number) lebih besar dari bilangan terbesar yang tersimpan saat ini (max_number). Jika iya, maka nilai max_number diperbarui dengan nilai dari number.

```Python
print("Bilangan terbesar: ", max_number)
```
Fungsi: Setelah loop selesai (karena pengguna memasukkan 0), program mencetak nilai dari max_number, yaitu bilangan terbesar yang dimasukkan selama loop.
