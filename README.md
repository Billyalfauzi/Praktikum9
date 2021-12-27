# Praktikum9
## Panjang Umur Untuk Hal Hal Baik :)

### Kode Eksepsinya

while True:
        try:
            nim = int(input("Masukan NIM\t: "))
            if nim == "":
                print("NIM tidak boleh kosong")
            else:
                break
        except:
            print("Harap Masukan Angka")
        else:
            break
        
while True:
        try:
            nilai = int(input("Masukan Nilai\t: "))
            if nilai == "":
                print("Nilai tidak boleh kosong")
            else:
                break
        except:
            print("Harap Masukan Angka")
        else:
            break

Dengan menambahkan Eksepsi maka, ketika input data kosong akan diminta memasukkan data kembali & saat input NIM menggunakan huruf atau karakter maka program otomatis akan meminta untuk memasukkan angka.

### Kurang lebih seperti ini tampilan nya.
![img]skrinsut/ss1.png
