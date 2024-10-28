# BIODATA 
## NAMA : MUHAMMAD RAFI ALBANI RASYIN 
## NIM : 312410316
## KELAS : TI.24.A.4


# MENENTUKAN NILAI AKHIR

```python
nama = input("Masukkan nama:")
uts = input("Masukkan nilai UTS:")
uas = input("Masukkan nilai UAS:")
tugas = input("Masukkan nilai Tugas:")
akhir = (int(tugas) * .2) + (int(uts) * .4) + (int(uas) * .4)
keterangan = ("TIDAK LULUS", "LULUS")[akhir > 60.0]

if akhir > 80:
    huruf = "A"
elif akhir > 70:
    huruf = "B"
elif akhir > 50:
    huruf = "C"
elif akhir > 40:
    huruf = "D"
else:
    huruf = "E"

print("\nNama :",nama)
print("Nilai UTS :",uts)
print("Nilai UAS :",uas)
print("Nilai Tugas :",tugas)
print("Nilai Akhir :",akhir)
print("\nNilai Huruf :",huruf)
print("Keterangan :",keterangan)

nama = input("Masukkan nama:")
uts = input("Masukkan nilai UTS:")
uas = input("Masukkan nilai UAS:")
tugas = input("Masukkan nilai Tugas:")
````

fungsi input() digunakan untuk memasukkan data atau informasi ke dalam sistem atau program komputer,

```python
akhir = (int(tugas) * .2) + (int(uts) * .4) + (int(uas) * .4)
````

Fungsi dari integer dalam pemrograman adalah untuk merepresentasikan nilai bilangan bulat, baik positif maupun negatif, serta nol. Integer biasanya digunakan dalam operasi matematika seperti penjumlahan, pengurangan, perkalian, dan pembagian.

fungsi dari * untuk mengkalikan angka,dan fungsi dari  .2 adalah 0 koma 2

dan nilai tugas yang di masukan 90 ,maka akan dikalikan program di atas .2 yaitu( 0.2) maka keluar cetakan 18

```python
keterangan = ("TIDAK LULUS", "LULUS")[akhir > 60.0]
````

keterangan ini hanya sebuah variable yang nantinya akan di cetakan,dan hasil ahkir akan memproses

```python
if akhir > 80:
huruf = "A"
elif akhir > 70:
huruf = "B"
elif akhir > 50:
huruf = "C"
elif akhir > 40:
huruf = "D"
else:
huruf = "E"
````

ini adalah struktur kondisi yang menggunakan if, elif , danelse

```python
if akhir > 80:
huruf = "A"
````

jika hasil dari nilai tersebut lebih besar dari 80 maka output yang keluar (A)

```python
else:
huruf = "E"
````

jika tidak sesuai semuanya pada program di atas output akan keluar(E)

```python
print("\nNama :",nama)
print("Nilai UTS :",uts)
print("Nilai UAS :",uas)
print("Nilai Tugas :",tugas)
print("Nilai Akhir :",akhir)
print("\nNilai Huruf :",huruf)
print("Keterangan :",keterangan)
````

fungsi print() adalah mencetak variable-variable pada program tersebut


# menampilkan gaji karyawan

```python
gaji = int(input("Masukkan gaji:"))
berkeluarga = (False, True)[input("Sudah berkeluarga? (Y/T)") == "Y"]
punya_rumah = (False, True)[input("Punya rumah? (Y/T)") == "Y"]

if gaji > 3000000:
    print ("Gaji sudah diatas UMR")

    if berkeluarga:
        print ("Wajib ikutan asuransi dan menabung untuk pensiun")

    else:
         print ("Tidak perlu ikutan asuransi")

    if punya_rumah:
        print ("wajib bayar pajak rumah")

    else:
        print ("tidak wajib bayar pajak rumah")

else:
    print ("Gaji belum UMR")
````

struktur ini menggunakan kondisi if, elif, dan else

```python
gaji = int(input("Masukkan gaji:"))
````

inputan ini akan memasukan angka gaji,karena memiliki fungsi int

```python
berkeluarga = (False, True)[input("Sudah berkeluarga? (Y/T)") == "Y"]
punya_rumah = (False, True)[input("Punya rumah? (Y/T)") == "Y"]
````

inputan ini menggunakan fungsi string yang di masukan berupa huruf,dan (false,true) ini adalah fungsi pemilihan Ya atau Tidak,agar tidak meggunakan if di lanjutan program tersebut

```python
if gaji > 3000000:
    print ("Gaji sudah diatas UMR")

    if berkeluarga:
        print ("Wajib ikutan asuransi dan menabung untuk pensiun")
    else:
        print ("Tidak perlu ikutan asuransi")
````

jika angka gaji angka gaji lrbih dari 3 juta maka output yang keluar"gaji sudah diatas UMR" dan jika tidak,output yang keluar"Tidak perlu ikut asuransi"

```python
if punya_rumah:
        print ("wajib bayar pajak rumah")

    else:
        print ("tidak wajib bayar pajak rumah")
````

Jika memiliki rumah maka output yang keluar adalah"Wajib bayar pajak", Jika tidak mempunyai rumah maka output yang keluar ialah "Tidak wajib bayar pajak"

```python
else:
    print ("Gaji belum UMR")
````

else yang berada di paling bawah ini terhubung dengan if Gaji > 3000000: apabila gaji tidak melebihi dari 3 juta output yang keluar"gaji belum UMR"


# Menggunakan kondisi OR dengan menginputkan 3 bilangan


```python
a = int(input("Masukkan bilangan A: "))
b = int(input("Masukkan bilangan B: "))
c = int(input("Masukkan bilangan C: "))
if a+b == c or b+c == a or c+a == b:
    print("BENAR")
else:
    print("SALAH")
````

operator OR dalam python merubah beberapa kondisi dan mengembalikan true jika salah satu benar.

```python
a = int(input("Masukkan bilangan A: "))
b = int(input("Masukkan bilangan B: "))
c = int(input("Masukkan bilangan C: "))
````

Program ini menginputkan sesuatu integer yang menggunakan variable a,b,c.

```python
if a+b == c or b+c == a or c+a == b:
    print("BENAR")
else:
    print("SALAH")
````

jika (A) ditambah (B) haslnya (C) atau bahasa pemograman itu OR ,dan apabila (B) ditambah (C) hasilnya (A),dan (C) ditambah (A) maka hasilnya (B). maka output yang keluar adalah "benar"

# Latihan 3

## Pemesanan tiket bioskop

Kasus 1: Program Pemesanan Tiket Bioskop Buat program yang menghitung harga tiket bioskop. Tiket reguler berharga Rp50.000, sedangkan tiket VIP berharga Rp100.000. Jika user memiliki kartu member, mereka mendapatkan diskon 20% dari harga tiket. Program ini harus meminta tipe tiket dan status member dari user, lalu menghitung total harga yang harus dibayar.

Petunjuk:

```python
● Gunakan if else dan operator ternary.
````

```python
harga_reguler = 50000
harga_vip = 100000

tipe_tiket = (input("Masukkan tipe tiket (reguler/VIP): "))
status_member = (input("Apakah Anda memiliki kartu member? (ya/tidak): "))

 Menghitung total harga
if tipe_tiket == "reguler":
    total_harga = harga_reguler
elif tipe_tiket == "vip":
    total_harga = harga_vip
else:
    print("Tipe tiket tidak valid.")
    exit()

 Menghitung diskon jika pengguna memiliki kartu member


if status_member == "ya":
        total_harga *= 0.8  # Diskon 20%
    
        print(f"Total harga yang harus dibayar: Rp{total_harga:.2f}")
elif status_member == "tidak":
            total_harga
            print(f"total harga yang harua dibayar: Rp{total_harga:.2f}")
else:
    print("Harga tidak dapat dihitung.")
````

Program ini akan menentukan harga pesanan tiket bioskop, Yang reguler/Vip, dan jika Vip harga 100.000, dan jika reguler 80.0000, dan jika memiliki kartu member pelanggan tersebut akan mendapatkan diskon 20%

```python
harga_reguler = 50000
harga_vip = 100000
````

variable ini menentukan harga tiket bioskop

```python
tipe_tiket = (input("Masukkan tipe tiket (reguler/VIP): "))
status_member = (input("Apakah Anda memiliki kartu member? (ya/tidak): "))
````

memasukan inputan sesuai Output Program (Reguler/Vip) di variable (Tipe_Tiket), dan Memasukan inputan yang output tersebut Bertanya memiliki kartu member atau tidak.

```python
if tipe_tiket == "reguler":
    total_harga = harga_reguler
elif tipe_tiket == "vip":
    total_harga = harga_vip
else:
    print("Tipe tiket tidak valid.")
    exit()
````

Jika tipe tiket reguler total harga proses ke Harga reguler, dan jika tiket vip Total harga proses keharga vip

dan jika Selain memasukan inputan reguler/vip Output yang keluar "Tipe tiket tidak valid" dan berproses ke fungsi exit() yang artinya program dihentikan.

```python
if status_member == "ya":
        total_harga *= 0.8  # Diskon 20%
    
        print(f"Total harga yang harus dibayar: Rp{total_harga:.2f}")
elif status_member == "tidak":
            total_harga
            print(f"total harga yang harua dibayar: Rp{total_harga:.2f}")
else:
    print("Harga tidak dapat dihitung.")
````

desision ini menentukan mempunyai kartu member atau tidak, Jika Inputan status member menjawab "ya", maka total harga akan di kalikan dengan operator * 0,8 yang disebut diskon 20%

dan jika inputan status member "tidak", maka total harga normal

jika menginputkan selain (ya/tidak) output yang keluar "Harga tidak dapat dihitung"

Dan ini hasil program tersebut:

![Screenshot 2024-10-28 162355](https://github.com/user-attachments/assets/e4057785-2ed4-4997-890b-8d8d87ffd3a4)

Eksekusi dari program tersebut:

![Screenshot 2024-10-28 162642](https://github.com/user-attachments/assets/f42b1569-6ea3-4139-a70e-d87fb5a6b74b)

Dan flowchartnya:

![380424445-19f37011-2198-4889-8b5c-01199022dc09](https://github.com/user-attachments/assets/169d966b-4e9b-4206-8274-757ac0f0acbd)

# Kalkulator sederhana

## Kasus 2: Program Kalkulator Sederhana

Buat program kalkulator yang menerima dua angka dan satu operator aritmatika dari pengguna (penjumlahan, pengurangan, perkalian, atau pembagian). Program akan menghitung hasil sesuai dengan operator yang dipilih.

## Petunjuk:

```python
● Gunakan if elif else untuk menentukan operasi aritmatika.

angka1 = float(input("Masukkan angka pertama: "))
````

operator = input("Masukkan operator (+, -, *, /): ") angka2 = float(input("Masukkan angka kedua: "))

## Menghitung hasil berdasarkan operator

```python
if operator == '+':
    hasil = angka1 + angka2
    print(f"Hasil penjumlahan: {hasil}")
elif operator == '-':
    hasil = angka1 - angka2
    print(f"Hasil pengurangan: {hasil}")
elif operator == '*':
    hasil = angka1 * angka2
    print(f"Hasil perkalian: {hasil}")
elif operator == '/':
    if angka2 != 0:
        hasil = angka1 / angka2
        print(f"Hasil pembagian: {hasil}")
    else:
        print("Error: Pembagian dengan nol tidak diperbolehkan.")

else:
    print("Error: Operator tidak valid. Silakan gunakan +, -, *, atau /.")
````

Program kalkulator sederhana dalam Python adalah proyek yang baik untuk pemula dan programmer tingkat lanjut. Program ini memungkinkan pengguna untuk melakukan operasi matematika seperti penjumlahan, pengurangan, perkalian, dan pembagian.

```python

angka1 = float(input("Masukkan angka pertama: "))
operator = input("Masukkan operator (+, -, *, /): ")
angka2 = float(input("Masukkan angka kedua: "))
````

fungsi yang digunakan dalam inputan ini menggunakan float mengubah nilai menjadi angka floating point, yaitu angka desimal atau pecahan, dan variable operator yang menginputkan suatu operator fungsi berupa (+, -, *, /) yang artinya pertambahan, perkurang, perkali, pembagian.

```python
if operator == '+':
    hasil = angka1 + angka2
    print(f"Hasil penjumlahan: {hasil}")
````

Jika operator (+), maka hasil tersbur inputan variable angka1 ditambahkan angka2, dan Output akan mengeluarkan hasil program tersebut, Hingga seterusnya dengan (*) perkalian, dan (-) perkurangan

```python
elif operator == '/':
    if angka2 != 0:
        hasil = angka1 / angka2
        print(f"Hasil pembagian: {hasil}")
    else:
        print("Error: Pembagian dengan nol tidak diperbolehkan.")
````

Jika oprator (/), maka Inputan Variable angka1 dibagi angka2, dan dicetak semestinya, untuk desision (angka2 !=0:) tidak diperkenankan oleh program, karna output yang keluar "Error: Pembagian dengan nol tidak diperbolehkan"

```python
else:
    print("Error: Operator tidak valid. Silakan gunakan +, -, *, atau /.")
````

saya memasukan desision else ini Karna jika menjawab selain fungsi operator ini Output yang keluar "Error: Operator tidak valid. Silakan gunakan +, -, *, atau /."

dan ini hasil program tersebut:

![Screenshot 2024-10-28 195754](https://github.com/user-attachments/assets/0313daca-1c4f-4548-9061-041ddff98f44)

Eksekusi program tersebut:

![Screenshot 2024-10-28 195351](https://github.com/user-attachments/assets/1d558d25-e5fe-41b2-be29-cd8331db56ca)

dan flowchartnya

![380426864-94b3f701-54fe-4e56-bf46-2354363fcfc2](https://github.com/user-attachments/assets/63b04482-cf7d-4e29-a09e-314ac7c71b85)






