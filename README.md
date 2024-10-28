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
