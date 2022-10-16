## Tugas1 

## tugas bahasa pemograman
## azra demasyahputra
## 312210105
## ti.22.a2

## MENGINSTAL GIT
membuka website resmi git yaitu (git-scm.com), lalu mendownload sesuai 05
|[gambar1](gambar/azra1.png)

## membuka git bash
setelah menginstal lalu membuka git bash
|[gambar2](gambar/azra2.png)

## menambahkan global config
pada saat pertama kali menggunakan git, perlu digunakan konfigurasi user.name dan user.email konfigurasi ini bisa dilakukan untuk global repositiry atau indovidual repository.apabila belum dilakukan konfigurasi, akan mengakibatkan terjadi kegagalan saat menjalankan printah git commit Config Global Repository
![gambar3](gambar/azra3.png)

## MEMBUAT REPOSITORY LOCAL
Buka direktory aktif, misal: /d/Tugas1
```
$ mkdir /d/Tugas1
$ cd /d/Tugas1
```
![gambar4](gambar/azra4.png)

## MENJALANKAN GIT INIT
Dengan perintah berikut:
```
$ git init
```
![gambar5](gambar/azra5.png)

## MENAMBAHKAN FILE BARU PADA REPOSITORY
Untuk membuat file dapat menggunakan text editor, lalu menyimpan filenya pada direktori aktif (repository)
```
$ echo "#Tugas1 " >> README.md
```
![gambar6](gambar/azra6.png)
```
Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah git add.
```
$ git add README.md
```
