# Instalasi Git
Git tersedia untuk berbagai sistem operasi. Git bisa menggunakan antarmuka _GUI_ maupun _CLI_. 

## Instalasi Git pada Windows
Sebelum menginstal Git harus mempunyai editor teks disini saya menggunakan **Visual Studio Code**. Berikut langkah-langkah instalasi Git:

1. Setelah download Git, double click pada file yang telah didownload.
![gambar 1](./1.PNG)
2. Setelah itu, pilih lokasi instalasi.
![gambar 2](./2.PNG)
3. Pilih komponen. Tidak perlu diubah.
![gambar 3](./3.PNG)
4. Mengisi shortcut untuk menu start.
![gambar 4](./4.PNG)
5. Pilih editor teks akan digunakan. Menggunakan Visual Studio Code.
![gambar 5](./5.PNG)
6. Git menyediakan dua pilihan untuk mengakses git. Bash adalah shell di Linux sedangkan Command Prompt di Windows.
![gambar 6](./6.PNG)
7. Pilih OpenSSL untuk HTTPS digunakan untuk mengakses repo GitHub
![gambar 7](./7.PNG)
8. Pilih pilihan pertama untuk konversi akhir baris.
![gambar 8](./8.PNG)
9. Pilih PuTTY untuk terminal yang digunakan untuk mengakses Git Bash.
![gambar 9](./9.PNG)
10. Untuk opsi ekstra, pilih dan aktifkan pilihan 1.
![gambar 10](./10.PNG)
11. Proses instalasi akan dilakukan, jika sudah selesai klik **Finish**.
![gambar 11](./11.PNG)
12. Search "Git", pilih "Git Bash".
![gambar 12](./12.PNG)
13. Tampilan jika menggunakan "Git Bash".
![gambar 13](./13.PNG)
14. Ketikkan "git --version" pada command prompt untuk melihat apakah sudah terinstal atau belum
![gambar 14](./14.PNG)

## Konfigurasi Git
User harus memberitahu Git username serta email yang akan digunakan setiap kali terjadi perubahan pada repo Git. Konfigurasi ini akan disimpan **C:\users\NamaUser** dengan nama file **.gitconfig**. Menggunakan perintah berikut:
```
[user]
    name = nama user
    email = email user
```

## Membuat Repo
Berikut langkah-langkah membuat repo:

1. Klik tanda + pada bagian atas, pilih **New repository**.
![gambar 15](./15.PNG)
2. Isikan nama, keterangan, serta lisensi. Klik **Create Repository**.
![gambar 16](./16.PNG)

## Clone Repo
Proses clone adalah proses untuk menduplikasi repo di GitHub ke komputer lokal. Untuk melakukan proses clone menggunakan perintah berikut:

1. Copy url repo yang akan di clone. 
2. Buka Visual Studio Code klik **View** kemudian **Command Pallete** ketikkan clone lalu masukkan urlnya.
![gambar 17](./17.PNG)
3. Membuat folder untuk menyimpan clone tersebut. Jika sudah tunggu sampai proses clone selesai.
![gambar 18](./18.PNG) 

## Upload File ke GitHub
Berikut langkah-langkah mengupload file ke GitHub:

1. Klik kanan pada file yang akan diupload, pilih Git Bash here.
![gambar 19](./19.PNG)
2. Melakukan inisialisasi terlebih dahulu dengan perintah:
    ```
    git init
    ```
3. Menambahkan semua file dengan perintah:
    ```
    git add .
    ``` 
4. Melihat status dengan perintah:
    ```
    git status
    ```
5. Commit pesan dengan perintah:
    ```
    git commit -m "menuliskan pesan"
    ```
6. Git remote dengan perintah:
    ```
    git remote add origin https://github.com/shofinurfaldini/01-git-github.git
    ```
7. Git push -u origin master lalu ketikkan username dan password dengan perintah:
    ```
    Git push -u origin master
    ```
8. Yang terakhir refresh halaman GitHub.