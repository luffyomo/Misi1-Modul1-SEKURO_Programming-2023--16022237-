> # RANGKUMAN MISI 1 PROGRAMMING SEKURO 


* ## Video Kelima : BEEKRJA DENGAN GIT

    - Didalam Git terdapat GUI (*Git Client*) yaitu sebuah software untuk menggunakan git tanpa console tapi melalui interface seperti github tetapi tidak dipelajari dalam rangkuman ini

    - Beberapa git commond (lokal) yang dapat dijalankan :

        1. **$ git init** : untuk menginisiasi repo git dalam repo kita

        2. **$ git add <file(s)>** : untuk menambahkan suatu file ke dalam staging area

        3. **$ git status** : untuk mengetahui status repo kita saat ini

        4. **$ git commit** : untuk melakukan commit

        5. **$ git config** : untuk memasukkan konfigurasi ke dalam git nya

        6. **$ git branch** : untuk membuat branch

        7. **$ git help** : untuk mengetahui cara memakai sebuah perintah dengan cepat

        8. dan masih banyak lagi

    - Setelah Git terinstal dalam komputer kita, Git akan mengenali 3 area setelah membuat repo yaitu :

        1. **Working Tree** adalah folder tempat kalian bekerja yang disi dengan file-file projek

        2. **Stage area** adalah perintah untuk memberitahu Git bahwa kita sudah melakukan perubahan pada repo

        3. **History** adalah tempat untuk menyimpan perubahan yang dilakukan setelah melakukan commit

    - Cara kerja git :
        1. Git akan memantau apakah ada perubahan yang terjadi pada **working tree**

        2. Setelah terdapat perubahan yang terpantau, maka perubahan tersebut akan disimpan di **stage area**

        3. Setelah melakukan commit pada perubahan tersebut maka Git akan menyimpan perubahan pada **history**

    - Langkah-langkah menggunakan Git di dalam komputer :

        1. Instal Git ke dalam komputer melalui link berikut <https://git-scm.com/>

        2. Masuk ke dalam gitbash untuk menjalankan git dengan console

        3. Ketik git untuk meminta bantuan penggunaan, git ini juga bisa dijalankan dengan terminal prompt dari komputer

        4. Untuk membersihkan terminnal agar tidak terlihat banyak bisa mengertik clear

        5. Untuk mengetahui tempat pada git, ketik pwd

        6. Untuk membuat repo kalian bisa membuat folder terlebih dahulu untuk menjadi repo 

        7. Lalu ketik **cd (lokasi-nama folder)** untuk masuk ke dalam folder tersebut

        8. Ketik **git init** untuk mengubah folder menjadi repo

        9. Buka folder melalui code editor yang digunakan untuk membuat file baru

        10. Setelah membuat file baru, masuk kedalam terminal/gitbash pastikan sudah masuk ke dalam repo dan bisa mengecek status repo dengan **git status**, disana akan terlihat  perubahan penambahan file yang belum ditambahkan dan di commit

        11. Sebelum melakukan commit bisa melakukan konfigurasi nama dan email dengan **git config --global user.nama "(nama pengguna)"** dan **git config --global user.email "(email pengguna)"**

        12. Ketik **git add (nama file)** atau **git add .**  untuk menambahkan file tersebut ke dalam **staging area**

        13. Lakukan commit dengan **git commit** atau **git commit -m "(deskripsi commit)"** agar perubahan tersimpan ke dalam **history** dan bisa melakukan perubahan berkali-kali tetapi jangan lupa untuk menambahkan dan commit perubahan tersebut

        14. Jika ingin melihat riwayat commit dapat mengetik **git log**, jika hanya ingin melihat sedikit riwayat yaitu 3 riwayat terakhir yaitu **git log -3**, dan apabila hanya ingin melihat riwayat commit file tertentu dengan **git log --(nama file)**

        15. Lalu jika ingin kembali ke perubahan tertentu dapat melakukan **git checkout (5 digit awal kode hash dari commit yang dituju) --nama file**
    
* Berikut tautan untuk melihat gambar percobaan untuk video 5 :

    - ***[Percobaan 1 video 5](https://drive.google.com/file/d/1OExcG7K-uwJRaezWD2neCMUCGW5WlOt7/view?usp=sharing)***

    - ***[Percobaan 2 video 5](https://drive.google.com/file/d/12vNq2_b3JS7OSVhwKdrskrqYLr50i281/view?usp=sharing)***

    - ***[Percobaan 3 video 5](https://drive.google.com/file/d/1eO54hmCWnCx1UKiZy3iuhKsC8Gw_JC1H/view?usp=sharing)***

    - ***[Percobaan 4 video 5](https://drive.google.com/file/d/1665BDb0LGic0fVrkKa2y3XwSad3taXEy/view?usp=sharing)***