# Summary (6) Version Control (Git)
## Tuliskan 3 poin yang dipelajari dari materi Version Control (Git)

- Definisi dari sofware testing
Versioning merupakan perlakuan sebuah pengaturan versi atau pelacakan perubahan dari setiap code program kita
    contoh : dokumen dokumen revisi skripsi yang selalu mengalami perubahan baik dari namanya ataupun isinya, seperti skripsi, skripsi revisi, skripsi revisi fix, skripsi revisi final
    mengetahui perubahan-perubahan tersebut tujuannya untuk mengetahui kesalahan-kesalahannya apa saja, yang mengubah code ini siapa
    Salah satu VCS yang populer adalah git.
- Git ini berguna bagi para developer untuk mengembangkan software secara bersama-sama, salah satu yang paling populer adalah github (git hosting service)
- git init : untuk membuat repositori baru
   git clone : untuk checkout repositori
   git add . : untuk menambah file secara menyeluruh
   git add <nama file> : untuk menambah 1 file saja
   git branch : untuk membuat branch
   git checkout : untuk memindahkan branch
   git branch -m main : berarti branch master kita di main, berarti nanti git checkout main
   branch master : yang rilis 
   develop : masih didevelop dan masih dilingkungan masyarakat 
   feature : masih di lokal dan lingkungan developer 
  conflict pertama : confignya kalau kolaborator yang punya repo ada 10/20 orang, kita harus bisa memastikan misal
  conflict itu disebabkan karena belum update branch yang bakal disepakati branch master itu branch paling update, seblum kalian ke branch feature, harus update branch master dulu
  kedua, ada teman yang ngerjain dan sudah push ke master dan ternyata menggeserkan file yang sudah dibuat 