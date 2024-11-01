# labpy03
TUGAS PRAKTIKUM 3
Nama : Noviza Diana

Nim : 352310890

Kelas : IE.23.C12

LATIHAN 1
intruksi perintah :

Tampilkan nilai n bilangan acak yang lebih kecil dari 0.5
nilai n diisi saat run time
menggunakan while atau for
menggunakan fungsi random
Screenshoot Hasil Program yang dibuat
![Screenshot 2024-11-01 231047](https://github.com/user-attachments/assets/aa7b2486-ee6e-4ce8-8aec-29b30a958f83)
Algoritma dan penjelasan
pertama kita buat program terlebih dahulu menggunakan Idle

saat membuat program, yang pertama kita buat sistem input terlebih dahulu agar kita bisa menginput suatu bilangan
saat di runtime dengan rumus n = int(input("Masukkan jumlah bilangan acak yang ingin ditampilkan: "))

selanjutnya kita nisialisasi variabel untuk menghitung jumlah bilangan yang telah ditampilkan dengan rumus count = 0

selanjutnya kita akan Menggunakan while untuk terus menghasilkan bilangan acak sampai mencapai n, dengan rumus while count < n:

selanjutya kita akan menghasilkan bilangan acak dengan a = random()

selanjutnya Memeriksa apakah bilangan acak kurang dari 0.5,
rumus: if a < 0.5: count += 1 # Menambah hitungan bilangan yang ditampilkan
print(f"Data ke : {count} => {a}") 
# Menampilkan bilangan acak dengan format yang diinginkan

selesai

LATIHAN 2
Intruksi : Buat program untuk menampilkan bilangan terbesar dari n buah data yang diinputkan.
Masukkan angka 0 untuk berhenti.

Screenshot Hasil Dari Program yang dibuat
![Screenshot 2024-11-01 235701](https://github.com/user-attachments/assets/a6e1bd05-0d68-49bb-b2af-bc5952dc2777)

Algoritma dan penjelasan
pertama kita buat program terlebih dahulu menggunakan Idle
kita buat Inisialisasi variabel untuk menyimpan bilangan terbesar dengan rumus max_number = None
selanjutnya kita buat while true : Mengambil input dari pengguna,
Memeriksa apakah pengguna memasukkan 0, 
Memperbarui bilangan terbesar jika diperlukan
selanjutnya kita akan menamplkan bilangan terbesarnya dengan rumus, 
if max_number is not None: print("Bilangan terbesar adalah:", max_number) else: print("Tidak ada angka yang dimasukkan.")
selesai

PROGRAM 1
Intruksi : Seorang pengusaha menginvestasikan uangnya untuk memulai usahanya dengan modal awal 100 juta, 
pada bulan pertama dan kedua belum mendapatkan laba.
pada bulan ketiga baru mulai mendapatkan laba sebesar 1% dan pada bulan ke 5, 
pendapatan meningkat 5%, 
selanjutnya pada bulan ke 8 mengalami penurunan keuntungan sebesar 2%,
sehingga laba menjadi 3%.
Hitung total keuntungan selama 8 bulan berjalan usahanya.

Screenshot Hasil Dari Program yang dibuat
![Screenshot 2024-11-02 000414](https://github.com/user-attachments/assets/a9d540aa-62a7-4fd9-9a4c-007ca7d00ec6)

Algoritma dan penjelasan
pertama kita buat program terlebih dahulu menggunakan Idle
buat print modal awal,
rumus :modal_awal = 100_000_000
kita buat nisialisasi list untuk menyimpan laba setiap bulan dengan menggunakan statement for, in, If, elif
menghitung total laba dengan rumus SUM
menampilkan hasil dengan rumus For 1 in
selesai


