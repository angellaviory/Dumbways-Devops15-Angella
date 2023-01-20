Day-1

1. DevOps merupakan penggabungan dari kata “Development” dan “Operation”, yang bertugas sebagai jembatan penghubung antara development (programmer) dan operation (infrastruktur server) agar produk atau aplikasi yang dibuat dapat bekerja secara cepat, lancar dan tidak mengalami hambatan.

2. Sebutkan lifecycle DevOps (Continuous ...) dan Jelaskan definisi-definisinya!

 - Continuous Development: Tahap dimana proses perencanaan dan programmer membuat kodingan untuk pembuatan suatu aplikasi. 
 - Continuous Integration: Tahap dimana pengumpulan hasil koding programmer di sebuah repository agar hasil koding dapat di cek dan diperbaharui jika --    mengalami bug/error. Dalam pembuatan suatu aplikasi, pasti mengalami penambahan ataupun perubahan sehingga mempengaruhi kodingan. Hal ini dilakukan untuk    mendeteksi masalah lebih awal dan cepat untuk diperbaiki.
 - Continuous Testing: Tahap dimana men-testing aplikasi secara keseluruhan untuk memastikan tidak terjadi bug, error, dll sehingga aplikasi dapat berjalan dengan lancar.
 - Continuous Deployment: Proses dimana aplikasi yang telah di test (kodingan berhasil terintegrasi) untuk dirilis secara otomatis.
 - Continuous Monitoring: Memantau aplikasi sehingga jika terjadi error dapat segera diatasi atau diperbaiki.
 - Continuous Feedback: Mengumpulkan saran-saran mengenai aplikasi sehingga tim dapat meningkatkan kualitas aplikasi.
 - Continuous Operations: Tahap dimana menjaga kestabilan dan kualitas aplikasi.

3. Jalankan Nginx Server (Day1-ss)


Day-2

1.	Jelaskan perbedaan IP Publik dan IP Private
IP Publik merupakan alamat IP yang diberikan oleh penyedia layanan internet (ISP, contoh: indihome, dll) yang dapat digunakan untuk mengakses internet sehingga dapat terhubung dengan jaringan yang lebih luas. 

IP Private merupakan alamat IP yang ada pada perangkat seperti laptop, printer, handphone, dll agar dapat terhubung dengan jaringan lokal. 


2.	Jelaskan perbedaan Client to Server dan Peer to Peer
Client to Server atau disebut juga dedicated server merupakan jaringan dimana satu komputer (server) akan menjadi pusat yang dapat diakses oleh komputer-komputer lain (client). Server yang memegang kendali dalam jaringan dan biasanya untuk client bisa terhubung dengan server, harus membuat permintaan kepada server.  

Peer to Peer atau disebut non dedicated server merupakan jaringan dimana semua komputer dapat menjadi server maupun client. Hal ini komputer satu dengan yang lainnya dapat saling berinteraksi tanpa meminta akses terlebih dahulu. 

3. Jalankan nginx di server kalian (day2-ss)
4. Cari 3 command shell yang belum di present dan berikan definisinya (day2-ss)



Day-3 (day3-ss)
1. Menjalankan aplikasi Webserver (nginx/apache2)
2. Menjalankan 3 aplikasi "hello world" menggunakan nodejs, golang dan python
3. Gunakan localtunnel untuk menjalankan "Hello world!" nodejs

Challenge :
Jalankan "Hello world" di python3 melalui port 5000 (gunakan flask), lalu akses dengan localtunnel
Gunakan PM2

Day-4

1. Jelaskan definisi distributed revision control
Dimana penyimpanan pengerjaan suatu aplikasi dapat diakses oleh developer sehingga memudahkan dalam pengerjaan aplikasi. Developer dapat melakukan perubahan dalam kodingan secara bersamaan. Penyimpanan file pun dapat dilakukan baik secara online maupun offline.

2. Buat repository untuk tugas kalian di github (day4-ss)
Format : dumbways-devops15-<nama kalian>
3. Hubungkan ssh public key ke akun github (day4-ss)
4. Clone repository dumbflix-frontend & buat 3 branch (Development, Staging & Production) (day4-ss)


Day-5
1. Apa itu terminal
Terminal merupakan command line atau shell yang dapat digunakna untuk membuat folder ataupun file dan dapat mengaturnya. Terminal juga dapat digunakan untuk memberikan akses, merubah maupun membaca akses. 

2. BASH script untuk update dan upgrade server, lalu install nginx/apache2 (salah satu). (day5-ss)
3. BASH script untuk memberi akses ke port 22,80,443 (day5-ss)
4. Tugas text manipulation (day5-ss)
    - contoh penggunaan cat, grep, echo & sort
    - mengganti text 'Dumbways' ke 'Bootcamp'
5. Gunakan nmon untuk tampilkan CPU usage, RAM usage, Disk dan Resources OS & Proc (day5-ss)

Challenge. (day5-ss)
- Buat script instalasi node version manager menggunakan BASH. 
- Jalankan aplikasi pilihan kalian (nodejs/python) dengan kondisi ufw enable


Day-6
1. Definisi Web Server
Software yang memberikan layanan dalam bentuk data. Biasanya dalam bentuk HTTP (belum terproteksi) dan HTTPS (sudah terproteksi) yang diterima oleh web browser dan server akan memproses nya menjadi sebuah halaman web.
 
 
2. Jalankan 2 VM (Optional). (day6-ss)
  - VM 1 = appserver
  - VM 2 = nginx
3. VM1 :
  - jalankan aplikasi dumbflix-frontend (day6-ss)
  - gunakan PM2 (Challenge) (day6-ss)
4. VM2 :
  - jalankan nginx (day6-ss)
  - buat konfigurasi reverse proxy dengan domain (gunakan nama kalian) mengarah ke app di VM1 (day6-ss)
  - buat konfigurasi load balance antara VM1 dan VM2 (day6-ss)

5. Domain bisa diakses melalui web browser kalian (edit filenya di /etc/hosts) (day6-ss)

 
Challenge
Load Balancer dapat berjalan dengan baik


