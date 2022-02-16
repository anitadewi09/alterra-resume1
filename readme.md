# Resume Materi Version Control and Branch Management (Git) #

## Version Control System (VCS) ##

Terdapat 3 jenis Version Control System (VCS) yaitu Singel User, Centralized, dan Distributed. Version Control Sytem digunakan dalam menggunakan Versioning kepada source code program yang telah dibuat. Penggunaan Version Control System sangat mudah dan praktis disimpan ketika ada riwayat perubahan yang dilakukan terhadap source code program yang telah dibuat atau dikerjakan dengan banyak orang. Sehingga setiap orang yang berkontribusi dalam pembuatan suatu program tersebut.

## Version Control System pada Git ##

Git merupakan salah satu version control system populer yang digunakan para developer untuk mengembangkan suatu software secara bersama-sama. Pada tahun 2005 Git diciptakan oleh Linus Torvalds. Git memiliki sifat terdistribusi atau distributed yang artinya program akan di host pada suatu git hosting service yang disebut sebagai sebuah repository. Selanjutnya commit yaitu riwayat perubahan code program pada setiap repository. Jadi Git melacak setiap perubahan pada file yang telah dikerjakan pada masing-masing kolabolator. Selanjutnya setiap kolabolator dapat mengetahui perubahan yang dibuat dan diaplikasikan perubahan tersebut ke local machine dari setiap kolabolator. 

## Cara Menggunakan Git ##

Pertama-tama buka git lalu membuat repository baru. Selanjutnya dengan menggunakan commit, source code pada local machine yang telah dibuat lalu di push ke github. Setiap kolabolator dapat melakukan pull untuk mendapatkan data dari source code  yang telah disimpan pada repositori git hosting service. Branching digunakan untuk membuat suatu perubahan pada source code menjadi lebih efisien. Selanjutnya lakukan branching untuk memisahkan brach master dan develop dan membuat branch baru untuk setiap fitur dalam pengembangannya. Fitur tersebut dilakukan merge ke develop apabila fitur tersebut sudah bekerja secara maksimal. Kemudian branch develop akan di merge ke branch master apabila proses pengembangan telah selesai yang bertujuan untuk meng-deploy fitur baru yang ditambahkan.
