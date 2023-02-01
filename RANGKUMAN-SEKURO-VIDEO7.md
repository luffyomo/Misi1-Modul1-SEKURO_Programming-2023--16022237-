> # RANGKUMAN MISI 1 PROGRAMMING SEKURO 


* ## Video Ketujuh : Git Merge conflict

    - mengapa terjadi merge conflict?

        karena saat melakukan merge terdapat 2 branch yang mengerjakan baris yang sama sehingga terjadi kendala dalam menggabungkan dan harus di selesaikan dengan mengganti perubahan antar 2 branch tersebut

    - Langkah-langkah melakukan merge tetapi dengan conflict :
    
        petama-tama buat/masuk ke dalam repo, lalu buat branch baru jika belum ada, ubah head ke branch baru, lalu lakukan perubahan pada cabang baru dan commit

        kedua ubah kembali head ke branch master, lalu buat  perubahan pada baris yang sama pada branch master lalu commit,untuk melihat visualisasi dari branch dengan mudah dan simple dapat mengubah perintah dengan **alias graph="git log --all --decorate --oneline --graph"** lalu beri perintah graph

        ketiga jika sudah selesai melakukan perubahan maka lakukan merge dengan **git merge (nama branch yang ingin di merge)**, dan ternyata terjadi conflict sehingga harus melakukan perubahan yang diinginkan dengan code editor

        lalu perubahan untuk menyelesaikan conflict harus ditambahkan ke stage area lalu commit perubahan tersebut, dan merge telah diselesaikan, setelah itu branch yang sudah di merch bisa di hapus 

    * jika kalian ingin kembali ke commit sebelumnya, kalian bisa mengecek dulu di history  commit yang ingin dilakukan, dengan perintah **git log** lalu cek 5 digit terakhir dari hash commit yang ingin kita kembalikan, lalu beri perintah  **git checkout (5 digit terakhir hash commit yang diinginkan)**

- ![Percobaan video 7](https://drive.google.com/file/d/186kIyGP8oFNnb6EM6r1Eic_Xh1Xd85KK/view?usp=sharing "percobaan video 7")


- ![Percobaan video 7(1)](https://drive.google.com/file/d/1_qBNzA4FZ7RDUE21LQ7O4msqgqwwXWMm/view?usp=sharing "percobaan video 7(1)")

- ![Percobaan1 video 7](https://drive.google.com/file/d/1O9SJt4aVGBjUwJeiQUW7qWLyKgRg3Vyz/view?usp=sharing "percobaan1 video 7(1)")
