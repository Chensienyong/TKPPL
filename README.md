Presentasi
==========
SCRUM Master 1 = Jeffry Tandiono
=> 26 May 2014 - 28 May 2014

SCRUM Master 2 = Soewandi Koerniawan Syahputra
=> 29 May 2014 - 31 May 2014

SCRUM Master 3 = Alwin Mario
=> 2 June 2014 - 4 June 2014

SCRUM Master 4 = Kelvin
=> 5 June 2014 - 7 June 2014

Commit
----------
Saat Commit diharapkan menggunakan
-m '{apa yang dikerjakan}'
ganti {apa yang dikerjakan} dengan apa yang berubah atau tambah dalam proses tersebut.
agar mempermudah Scrum Master memantau perubahan dan anggota lain lebih gampang dalam memahami.

Merge
----------
Setiap ada commit terbaru,
git pull origin master.
**********
Bila dia merge automatic, maka anda hanya perlu men cek dengan men grunt server apakah file sudah ter merge atau belum.
**********
Bila dia tidak bisa merge automatic karena ada faktor ambigu, maka anda perlu membuka file tersebut yang error lalu melihat perubahan.
**********
Akan muncul
<<<<<< HEAD
isi dari perubahan mu
lalu batas dengan '='
isi dari commit anggota yang lain sebelumnya yang mengalami bentrok dan menyebabkan ambigu
baris dengan '>' {id commit}
**********
disaat itulah anda perlu melihat apa yang berbeda antara perubahan anda dengan teman anda dan pilihlah perubahan yang benar. Dan diharapkan menghubungi anggota yang melakukan commit tersebut agar dapat berdiskusi mana yang benar dan mana yang digunakan.
**********
Lalu hapus
<<<<<<<<<< HEAD
batas '='
dan baris dengan '>' {id commit}
serta code yang mempunyai kesalahan..
**********
Note : Sebelum anda me-pull dari git bash, bila ada yang belum di commit, diharapkan commit terlebih dahulu.
**********
Bila mengalami masalah atau butuh bantuan:
FB : www.facebook.com/ashxcellent.k.archivist
LINE : jeffrytandiono
