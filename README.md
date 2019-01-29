#revisi 1
# Pengertian Git
Git adalah salah satu sistem pengontrol versi pada proyek perangkat lunak yang diciptakan oleh Linus Torvalds. 
Pengontrol versi bertugas mencatat setiap perubahan pada file proyek yang dikerjakan oleh banyak orang maupun sendiri. 
Git dikenal juga dengan distributed revision control, artinya penyimpanan database Git tidak hanya berada dalam satu tempat saja

# Perintah Dasar pada Git
* _**git init**_, perintah untuk membuat repository local
* _**git add**_, perintah untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit. 
* _**git commit**_, perintah untuk menyimpan perubahan kedalam database git. 
* _**git push -u origin master**_, perintah untuk mengirim perubahan pada repository local menuju server repository. 
* _**git clone [url]**_, perintah untuk membuat working directory yang diambil dari repositry sever.
* _**git remote add origin [url]**_, perintah untuk menambahkan remote server/reopsitory server pada local repositry (working directory)

# Membuat Reposiory Local
* Pertama buka direktory aktif, misal: d:/bhspemograman1
* Buat direktory project praktikum pertama dengan nama revisi1
* Sehingga terbentuk satu direktori baru dibawahnya, selanjutnya masuk kedalam direktori tersebut dengan perintah cd (change directory)
* direktory aktif menjadi: d:/bhspemograman1/revisi1 kemudian masuk ke direktory tersebut 
# ![GitHub Logo](ss1.PNG)

* Lakukan "git init" untuk menjadikan repository lokal 
# ![GitHub Logo](2.PNG) <h2>
* Buat File Bernama "README.md" (text file), jika file berhasil dibuat, akan tampil seperti dlm gambar
# ![GitHub Logo](3.PNG) <h2>
* kemudian tambahkan file tersebut ke repository dengan " git add 
README.md, file yang berhasil ditambahkan akan terlihat seperti di 
gambar, dengan "git status" 
# ![GitHub Logo](4.PNG) <h2>
* Untuk  Menyimpan perubahan sebuah file ke repository local gunakan 
printah " git commit -m "perubahan yang terjadi"
# ![GitHub Logo](5.PNG)
# Membuat repository server <h2>
* Server reopsitory yang akan kita gunakan adalah http://github.com
* Anda harus membuat akun terlebih dahulu. • Pada laman github, klik tombol start a project, atau
* Dari menu (icon +) klik New Repository
