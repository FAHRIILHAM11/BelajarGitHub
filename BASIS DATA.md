# CATATAN GIT
## 1. INSTALASI GIT BASH
1. Buka di leptop kalian google atau chroome dan masuk kewebsiet resmi GIT yaitu "https://git-scm.com/"
2. Setelah kalian masuk kalian tekan DOWNLOAD dibagian gambar yang saya tandaiin.
![](asset/instal1.PNG)

3. Setelah kalian tekan maka ada 3 pilihan merek lepto yaitu macOS, Windows, dan Linus/Unis karna berhubungan leptop saya windows maka saya pilih windows seperti digambar berikut.
![](asset/instal2.PNG)

4. Setelah kalian sudah memilih merek leptop kalian berikutnya kalian disuruh memilih kualitas GIT terserah kalian mau memilih apa, berhubungan leptop saya spek dewa maka saya memilih 64-Bit berikut contohnya.
![](asset/instal3.PNG)

5. Stelah kalian memilih maka aplikasi otomatis terinstal dan tunggu sampai selesai, berikut step berikutnya.
6. Setelah terinstal maka kalian masuk kedalam file kalian dan caridimana kalian simpan, berhubungan saya menyimpannya di Data D: seperti gambar berikut.
![](asset/instal4.PNG)

7. Berikut caranya Klik **Next** untuk melanjutkan installasi.
![](asset/instal5.PNG)

8. Lalu Anda akan diminta untuk memberi lokasi folder GIT. Lokasi tersebut dapat Anda letakkan dimanapun. Jika sudah, maka klik *Next*.
![](asset/instal6.PNG)

9. Pilihlah komponen-komponen yang ingin Anda Install di GIT. Disini saya hanya memerlukan **Windows Explorer Integration, Git Bash Here, Git GUI Here, Git LFS, Associate .git* configuration files with the default text editor, dan Associate .sh* files to be run with Bash.** Jika sudah selesai memilih komponen yang dibutuhkan, maka klik **Next**.
![](asset/instal7.PNG)

10. Klik **Next**.
![](asset/instal8.PNG)

11. Kemudian pilihlah default editor yang akan digunakan oleh GIT, disini pilih saja **Use Vim (the ubiquitous text editor) as Git’s default editor**. Setelah itu klik **Next**.
![](asset/instal9.PNG)

12. Pilih **Use Git from the Windows Command Prompt** dan klik **Next**.
![](asset/instal10.PNG)

13. Selanjutnya Anda akan diminta untuk memilih SSL/TLS library yang akan GIT gunakan koneksi HTTPS. Anda dapat memilih **Use the OpenSSL library**. Lalu klik **Next**.
![](asset/instal11.PNG)

14. Kemudian Anda harus memilih konfigurasi line ending konfersi. Pilih Checkout Windows-style, commit Unix-style line endings. Lalu klik **Next**.
![](asset/instal12.PNG)

15. Setelah itu Anda akan diminta untuk mengkonfigurasi terminal emulator yang akan digunakan Git Bash. Disini Anda dapat memilih **Use Windows’ default console window**. Kemudian klik **Next**.
![](asset/instal13.PNG)

16. Anda juga dapat menambahkan pilihan ekstra fitur yang Anda inginkan. Disini saya memilih **Enable file system caching** dan **Enable Git Credential Manager**. Setelah itu klik tombol **Next**.
![](asset/instal14.PNG)

17. Untuk konfigurasi ini saya tidak memilih satu pun karena itu tidak saya butuhkan. Jika Anda membutuhkan experimental options tersebut, Anda dapat memberikan centang pada kotak tersebut. Kemudian klik tombol **Install**.
![](asset/instal15.PNG)

18. Tunggulah beberapa saat sampai proses instalasi selesai. Proses instalasi tidak berlangsung lama, hanya dalam hitungan menit saja, sehingga Anda dapat menunggunya.
![](asset/instal16.PNG)

19. Jika proses instalasi telah selesai, maka kini Anda sudah selesai menginstal aplikasi GIT. Klik tombol **finish** untuk mengakhiri proses instalasi.
![](asset/instal17.PNG)
## 2. BUAT AKUN GIT HUB
1. Buka [https://github.com](https://github.com/) di browser web, lalu pilih **Daftar**.
![](asset/login1.png)

2. **Masukkan alamat email** Anda.
![](asset/login2.png)

3. **Buat kata sandi** untuk akun GitHub baru Anda, dan **Masukkan nama** pengguna juga. Selanjutnya, pilih apakah Anda ingin menerima pembaruan dan pengumuman melalui email, lalu pilih **Lanjutkan**.
![](asset/login3.png)

4. **Verifikasi akun** Anda dengan memecahkan teka-teki. Pilih tombol **Mulai Teka-teki** untuk melakukannya, lalu ikuti perintah.
5. Setelah Anda memverifikasi akun Anda, pilih tombol **Buat akun** .
6. Selanjutnya, GitHub mengirimkan kode peluncuran ke alamat email Anda. Ketik kode peluncuran tersebut **dalam dialog Masukkan kode** , lalu tekan **Enter**.
![](asset/login4.png)\

7. **Di layar Tempat tim berkolaborasi dan mengirim**, Anda dapat memilih apakah Anda ingin menggunakan akun Gratis atau akun Tim. Untuk memilih **akun Gratis** , pilih tombol **Lewati personalisasi** .
8. GitHub membuka halaman yang dipersonalisasi di browser Anda.
![](asset/login6.png)

9. selamat anda sudah login ke GitHub.
## BUAT REPOSITORY DI GIT HUB
1. Buka Google Chrome dan Akses Situs [Github](https://github.com/login)
2. Kemudian login menggunaka
3. Akun Github kamu
4. kemudian pilih pada **Create new repository**
![](asset/repository2.png)

5. masukkan Detail repository seperti : masukkan nama repository nama, terus centangkan Add a READMI file
![](asset/repository5.png)

6. Kemudian Pilih Keterlihatan pilih public atau privat
7. Centang Pada **Add a README file**
8. Setelah selesai Langsung create repository
![](asset/repository4.png)

9. stelah mengikuti tahapnya makan repository selesai dibuat.
## UPLOAD FOLDER OBSIDIAN KE GIT HUB
1. pertama kalian masuk dipencarian dan ketik *CMD* atau kalian bisa juga menggunakan *Windows + R* agar dapat masuk di CMD.
![](asset/up1.png)

2. Lalu kalian klik *OK*, Lalu berikutnya kalian ketikkan lokasi *FOLDER PROJEK* anda tersimpan dimana lalu ENTER.
![](asset/up2.png)

3. Lalu kalian ketikkan **`git init`** Perintah ini digunakan untuk menginisialisasi repository Git baru di direktori proyek yang saat ini sedang digunakan. Ini akan membuat subdirektori baru bernama `.git` yang berisi semua file metadata repository.
![](asset/up3.png)

4. Lalu ketikkan **`git add .`** Perintah ini digunakan untuk menambahkan semua perubahan yang ada di direktori kerja (termasuk file baru, file yang diubah, dan file yang dihapus) ke dalam staging area, sehingga siap untuk di-commit pada tahap selanjutnya.
![](asset/up4.png)

5. **`git commit -m "perubahan-1"`**: Perintah ini digunakan untuk menyimpan snapshot dari semua perubahan yang ada di staging area ke dalam repository lokal. Teks di dalam tanda kutip (`"perubahan-1"`) adalah pesan commit yang menjelaskan perubahan apa saja yang dilakukan dalam commit tersebut.
![](asset/up5.png)

6. **`git remote add origin https://github.com/FAHRIILHAM11/FahriAjaa.git`**: Perintah ini digunakan untuk menambahkan URL repository remote (dalam hal ini, repository GitHub) dengan nama alias `origin`. Setelah menambahkan remote, Anda dapat mengirim (push) perubahan dari repository lokal Anda ke repository remote di GitHub.
![](asset/up6.png)

7. **`git status`**: Perintah ini digunakan untuk menampilkan status dari repository lokal Anda. Ini akan menunjukkan informasi seperti file yang telah dimodifikasi, file yang telah ditambahkan ke staging area, dan branch mana yang sedang aktif.
![](asset/up7.png)

8. **`git branch -M master`**: Perintah ini digunakan untuk mengubah nama branch saat ini menjadi `master`. Pada versi Git terbaru, penggunaan `-M` digunakan untuk memindahkan branch dan mengubah namanya sekaligus. Dalam konteks ini, `master` adalah nama branch yang diubah.
![](asset/up8.png)

9. Perintah `git push -u origin master` digunakan untuk mengirim (push) semua perubahan dari branch lokal `master` ke branch `master` di repository remote (`origin`) di GitHub atau repository Git lainnya.
- `git push`: Mengirim perubahan lokal ke repository remote.
- `-u origin master`: Parameter `-u` atau `--set-upstream` digunakan untuk menetapkan branch lokal (`master` dalam hal ini) sebagai branch default untuk branch remote (`origin/master`). Setelah ini, Anda dapat menggunakan `git push` tanpa argumen untuk branch dan repository yang sama.
![](asset/up9.png)

10. setelah kalian `git push -u origin master` kalian masuk ke GitHub anda dan repres dan seluruh isi folder projek akan tampil di repository github.
![](asset/up10.png)

11. Setelah anda melakukan tahap-tahapnya maka kalian sudah berhasil menguploadnya ke GitHub.