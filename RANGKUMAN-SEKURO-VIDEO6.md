> # RANGKUMAN MISI 1 PROGRAMMING SEKURO 


* ## Video Keenam : Git Branch dan Merge

    - Merge adalah menambahkan branch baru ke jalur utama (branch master)
    - merge ada 2 jenis yaitu :
        1. **Fast Forward** terjadi ketika branch yang ingin digabungkan berada dalam jalur langsung (direct path)
        2. **Three-way Merge** terjadi apabila tidak ada direct path, jadi saat melakukan merge, git juga melakukan commit

    - Langkah-langkah membuat branch dan merge branch tersebut :
        1. pertama-tama buat folder dan jadikan repo lalu buat file pada repo tersebut.
        2. lalu buat branch baru dengan **git branch (nama branch**), kalian bisa mengecek branch yang ada dengan **git branch** dan disana dapat melihat head pada branch apa
        3. untuk melihat visualisai dari commit branch dapat dengan **git log --all --decorate --oneline --graph** tetapi dapat disingkat dengan **alias graph="git log --all --decorate --oneline --graph"** sehingga hanya tinggal mengetik **graph** saja setelah itu untuk melihat visual branch
        4. jika ingin mengganti branch bisa dengan **git checkout (nama branch)** nantinya pointer head akan berpindah
        5. buat perubahan pada branch baru dengan menambah file pada code editor
        6. tambahkan file tersebut dan lakukan commit seeprti langkah sebelumnya di video 7. pindah lagi ke branch baru lain seperti sebelumnya dan buat file baru dalam branch tersebut lalu tambahakan dan commit perubahan tersebut
        8. ketik **garph** untuk melihat visualisasi dari commit yang dilakukan pada tiap cabang
        9. pindahkan branch pada jalur utama dulu (branch master), lalu gabung branch dan jalur utama dengan **git merge (nama branch yang ingin digabung)**
        10. jika ingin mengecek branch yang sudah di merge bisa dengan **git branch --merged**, karena kita sudah menggabungkan merge pertama, maka branch pertama bisa dihapus dengan **git branch -d (nama branch yang ingin dihapus)**

* gambar beberapa percobaan video 6 :

    - ![Percobaan video 6](https://drive.google.com/file/d/1SkId6p9RoGx3nmFd5XRDM8637U90rTUR/view?usp=sharing "percobaan video 6")
    - ![Percobaan1 video 6](https://drive.google.com/file/d/1Xv7cJ1cUne2r916MMmHsUmTS3XtllBdc/view?usp=sharing "percobaan1 video 6")