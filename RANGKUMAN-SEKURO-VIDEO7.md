> # RANGKUMAN MISI 1 PROGRAMMING SEKURO 


* ## Video Ketujuh : GIT MERGE CONFLICT

    - Mengapa terjadi merge conflict?

        Karena saat melakukan merge terdapat 2 branch yang mengerjakan baris yang sama sehingga terjadi kendala dalam menggabungkan dan harus di selesaikan dengan mengganti perubahan antar 2 branch tersebut

    - Langkah-langkah melakukan merge tetapi dengan conflict :
    
        - Pertama-tama buat/masuk ke dalam repo, lalu buat branch baru jika belum ada, ubah head ke branch baru, lalu lakukan perubahan pada cabang baru dan commit

        - Kedua ubah kembali head ke branch master, lalu buat  perubahan pada baris yang sama pada branch master lalu commit,untuk melihat visualisasi dari branch dengan mudah dan simple dapat mengubah perintah dengan **alias graph="git log --all --decorate --oneline --graph"** lalu beri perintah graph

        - Ketiga jika sudah selesai melakukan perubahan maka lakukan merge dengan **git merge (nama branch yang ingin di merge)**, dan ternyata terjadi conflict sehingga harus melakukan perubahan yang diinginkan dengan code editor

        - Lalu perubahan untuk menyelesaikan conflict harus ditambahkan ke stage area lalu commit perubahan tersebut, dan merge telah diselesaikan, setelah itu branch yang sudah di merch bisa di hapus 

    * jika kalian ingin kembali ke commit sebelumnya, kalian bisa mengecek dulu di history  commit yang ingin dilakukan, dengan perintah **git log** lalu cek 5 digit terakhir dari hash commit yang ingin kita kembalikan, lalu beri perintah  **git checkout (5 digit terakhir hash commit yang diinginkan)**

- Berikut tautan untuk melihat gambar percobaan untuk video 7 :

    - ***[Percobaan video 7](https://drive.google.com/file/d/186kIyGP8oFNnb6EM6r1Eic_Xh1Xd85KK/view?usp=sharing)***

    - ***[Percobaan video 7(1)](https://drive.google.com/file/d/1_qBNzA4FZ7RDUE21LQ7O4msqgqwwXWMm/view?usp=sharing)***

    - ***[Percobaan 2 video 7](https://drive.google.com/file/d/1O9SJt4aVGBjUwJeiQUW7qWLyKgRg3Vyz/view?usp=sharing)***
