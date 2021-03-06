# pertemuan9-
### NAMA  : Denas Aria Pamungkas
### KELAS : TI. 20. A. 1
### NIM   : 312010089
_____________________________________________________________________________________________________________________
Pada di pertemuan ke 9 ini saya diberikan beberapa tugas oleh dosen saya, yaitu diantaranya:
## TUGAS PRAKTIKUM 4
Yang mana pada praktikum 4 ini terdapat beberapa soal seperti yang ada dibawah ini.

![SOAL](https://user-images.githubusercontent.com/72906579/100109596-9554b880-2e9e-11eb-87ef-13cdf5daede4.png)

Adapun hasil akhir yang diberikan dosen saya sebagai contoh output dari semua tugas diatas.

![hasil7](https://user-images.githubusercontent.com/72905634/100208870-0ce61000-2ebe-11eb-95c2-4e6ce39e180d.png)S
_________________________________________________________________________________________________
Pada soal pertama, yang dimana disini saya diminta untuk memasukan data sebanyak-banyaknya. Jadi disini saya akan mencoba memasukan beberapa data diantaranya seperti **NAMA, NIM, NILAI TUGAS, NILAI UTS** dan yang terakhir **NILAI UAS**

Dan untuk dapat menambahkan data-data tersebut maka kita perlu memasukan syntax seperti ini.
```python
nama = input("NAMA: ")
nim = input("NIM: ")
tugas = int(input("NILAI TUGAS: "))
uts = int(input("NILAI UTS: "))
uas = int(input("NILAI UAS: "))
```
Setelah memasukan syntax diatas dan kalian run, maka akan mendapatkan hasil output seperti gambar dibawah ini

![hasil8](https://user-images.githubusercontent.com/72905634/100209401-b1685200-2ebe-11eb-9b80-bedbe1e44b19.png)

______________________________________________________________________________________________________________________________________
Lanjut pada soal kedua, yang dimana saya diminta untuk membuat sebuah pernyataan **YA/TIDAK** pada pertanyaan 'apakah ingin menambahkan sebuah data?'

Dan untuk dapat menambahkan data-data tersebut maka kita perlu memasukan syntax seperti ini
```python
if (input("TAMBAHKAN DATA (Y/T)?") == ''):
    ulang = False
```
Setelah memasukan syntax diatas dan kalian run, maka akan mendapatkan hasil output seperti gambar dibawah ini

![YA TIDAK](https://user-images.githubusercontent.com/72906579/100116086-e9af6680-2ea5-11eb-8722-e735c46ef71f.png)

________________________________________________________________________________________________________________________________________

Setelah mengerjakan beberapa soal diatas, selanjutnya ada beberapa syntax yang saya tambahkan agar tampilan akhir dari ouput saya menjadi sama persis seperti yang ditunjukan oleh dosen saya. Oleh karena itu saya membutuhkan syntax seperti ini
```python
nilai = []
ulang = True

while ulang:
    nama = input("Masukkan Nama: ")
    nim = input("Masukkan NIM: ")
    tugas = int(input("Masukkan Nilai Tugas: "))
    uts = int(input("Masukkan Nilai UTS: "))
    uas = int(input("Masukkan Nilai UAS: "))
    akhir = (tugas * 30/100) + (uts * 35/100) + (uas * 35/100)

    nilai.append([nama, nim, tugas, uts, uas, int(akhir)])
    if (input("Tambah data (y/t)?") == 't'):
        ulang = False

print("\n                      Daftar Nilai Mahasiswa")
print("==================================================================")
print("|No. |     Nama     |    NIM    | Tugas |  UTS  |  UAS  |  Akhir |")
print("==================================================================")
i = 0
for item in nilai:
    i += 1
    print("| {no:2d} | {nama:12s} | {nim:9s} | {tugas:5d} | {uts:5d} | {uas:5d} | {akhir:6.2f} |"
          .format(no=i, nama=item[0], nim=item[1], tugas=item[2], uts=item[3], uas=item[4], akhir=item[5]))
print("==================================================================")
```
Setelah memasukan syntax diatas dan kalian run, maka akan mendapatkan hasil output seperti gambar dibawah ini

![TABEL 4](https://user-images.githubusercontent.com/72906579/100140013-ee364800-2ec2-11eb-97c8-97575e89fdd5.jpeg)

____________________________________________________________________________________________________________________________________________
Lanjut pada soal terakhir, yang dimana disini saya diminta untuk membuat sebuah Flowchart dari diatas

![FLOW](https://user-images.githubusercontent.com/72906579/100180603-15b10300-2f0b-11eb-9792-99324e3c9be6.png)

Dan kurang lebih seperti itulah bentuk flowchart yang sudah saya buat.

## *****************SELESAI!!***************** ##
## ***************TERIMAKASIH!!*************** ##