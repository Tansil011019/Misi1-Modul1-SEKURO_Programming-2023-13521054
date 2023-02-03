# First Video : What is Git and GitHub?
Github dan git yang mungkin dipakai secara terpisah dan juga dapat dipakai secara bersamaan.

## Table of Contents
1. [Version Control System](#version-control-system)
2. [Git](#git)
3. [GitHub](#github)
4. [Git and GitHub Command](#git-and-github-command)
5. [Documentation](#documentation)

## Version Control System
### What is Version Control System?
Version Control System, disebut juga <em> revision control system </em> atau <em> sourse code management </em> adalah sistem yang mengelola perubahan dari sebuah dokumen, program komputer, website dan kumpulan informasi lain.

### Why Should We Have Version Control System?
1. Dapat menyimpan "rekaman / <em>snapshot</em>" perubahan pada source code
2. Memungkinkan bekerja berkolaborasi dengan lebih baik
3. Mengetahui siapa uang melakukan dan kapan sebuah perubahan terjadi
4. Memungkinkan kita untuk kembali ke keadaan sebelum perubahan (<em>checkout</em>)

### Version Control System's Product
1. Git (yang akan dijelaskan pada rangkuman ini).
2. Subversion.
3. Mercurial.
4. CVS.

## Git
### What is Git?
Git adalah sebuah <em>Version Control System</em> terdistribusi untuk mengelola perubahan file di dalam folder (<em>repository / repo</em>). Riwayat perubahan file disimpan menggunakan serangkaian <em><strong>commit</strong></em>.

### How Git Works?
1. Inisialisasi Project.
2. Menambahkan view untuk login dan registrasi.
3. Melakukan penyimpanan riwayat dengan commit.
4. Apabila masih belum selesai, maka tahap ketiga akan dilakukan terus menerus.
5. Project selesai, <em><strong>release version</strong></em>.

### Commit Mechanism
![Commit View](../assets/commit_properties.png)
1. Baris pertama merupakan kode hash untuk menyimpan version.
2. Baris kedua adalah nama dan account orang yang melakukan perubahan.
3. Baris ketiga adalah waktu kapan terjadinya perubahan.
4. Baris keempat adalah pesan commit.

### Branch and Merge
<em><strong>Branch</strong></em> diperlukan agar semua pekerjaan yang dilakukan tidak langsung merubah main program, serta lebih mudah untuk dilakukan kontrol terhadap error pada fitur tertentu.
<br>
Setelah merasa bahwa sudah tidak terdapat error pada program di branch tersebut, maka bisa dilakukan <em><strong>merging</strong></em> ke main program.

## GitHub
### What is GitHub?
GitHub adalah layanan cloud untuk menyimpan dan mengelola project / repo git. Pada GitHub merupakan layanan git secara online dan memiliki seluruh fitur Git.

### Push and Pull
Push dan pull merupakan layanan GitHub untuk melakukan commit secara online. Push merupakan perubahan yang kita buat dan pull merupakan pengambilan perubahan yang telah dibuat. 

### Services that similar to GitHub
1. Bitbucket
2. GitLab

## Git and GitHub Command
1. repo -> folder project
2. commit -> rekaman / snapshot dari repo
3. hash -> penanda unik pada sebuah commit
4. checkout -> berpindah ke sebuah commit
5. branch -> cabang bebas dari sebuah commit
6. merge -> menggabungkan branch 
7. remote -> sumber yang memiliki repo
8. clone -> mengambil repo dari remote
9. push -> mengirimkan commit ke repo
10. pull -> mengambil commit dari repo

## Documentation
![GitHub View](../assets/my_GitHub.png)
GitHub link : [https://github.com/Tansil011019](https://github.com/Tansil011019)