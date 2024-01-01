# Anthopqua-Ubicom

## Intro 
- Artikel ini membahas mengenai pembangunan teknologi UbiCom yaitu “Penerapan Teknologi IoT (Internet of Things) dalam  Mendukung Ubiquitous Computing pada Peningkatan Bercocok Tanam di Urban Areas dan Efisiensi Sumber Daya”.

## Latar Belakang
Keterbatasan Ruang Fisik Urban areas seringkali memiliki keterbatasan lahan yang dapat digunakan untuk bercocok tanam. Oleh karena itu, solusi IoT harus dirancang untuk dapat beroperasi dalam ruang terbatas, misalnya di balkon, atap, atau ruang indoor. Efisiensi penggunaan air juga dalam lingkungan urban, penggunaan air untuk penyiraman tanaman harus diatur dengan efisien untuk menghindari pemborosan sumber daya. Diharapkan perangkat IoT semacam ini dapat membantu orang-orang di lingkungan urban yang memiliki sedikit lahan untuk tetap dapat menanam tanaman dengan efisien, meminimalkan kerugian akibat hama, dan mengurangi konsumsi air yang tidak perlu.
## Branding 
- Merk: **Anthopqua** 
- Inspirasi merk: Gabungan dari nama ilmiah hewan lebah dan juga air karena lebah itu hewan yang selalu dekat dengan tanaman dengan tidak merusaknya bahkan memberikan manfaat.
- Tagline: Sistem kualitas tanaman
- Campaign: Membuat sumber daya air tidak digunakan secara berlebih sehingga membuat tanaman menjadi lebih berkualitas.
- Target user:
  - petani 
  - yang mempunyai tananman  
- User experience theme:
  - mudah digunakan
  - automatis
  - terkoneksi dengan perangkat mobile

## User Story
Pada tahap ini kita mengeksplorasi kebutuhan prioritas dari para pengguna untuk kita wujudkan sebagai fitur pada sistem atau aplikasi yang akan dibuat.
User story [[1]](https://www.mountaingoatsoftware.com/agile/user-stories) memudahkan kita membuat prioritas fitur-fitur untuk dikerjakan untuk jangka waktu tertentu.

|Sebagai|Saya ingin bisa|Sehingga|Prioritas
|---|---|---|---|
|Sistem|Mendeteksi kelembaban tanah|Bisa mengetahui keadaan tanah dari kondisi kelembabannya|⭐⭐⭐⭐⭐|
|Sistem|&raquo; Menyalakan air secara otomatis|Bisa menyiram tanaman |⭐⭐⭐⭐⭐|
|Sistem|&raquo; Memberikan notifikasi pada perangkat mobile tentang aktivitas sistem|Bisa memberi tahu user hal yang sedang dilakukan sistem|⭐⭐|
|Sistem|&raquo; Mendeteksi hasil panen dan waktu panen yang tepat|Bisa memberi tahu user recomendasi waktu panen dan prediksi hasil panen yang didapat|⭐⭐|
|User|Menerima notifikasi|Pengguna bisa melihat apa yang diberikan sistem baik itu notifikasi aktifitas, rocomendasi waktu panen dan prediksi hasil panen|⭐⭐|

## Metode dan Algoritma 
- **Device:**
  - soil moisture sensor: module untuk mendeteksi kelempbaban tanah yang dapat diakses menggunakan mikrocontroller
  - arduino: module mikro kontroler
  - bread board: perangkai komponen
  - lcd: menampilkan nilai dari sensor
  - camera: mendeteksi tanaman
  - kabel jumper: penghubung sensor dengan mikro kontroler
  - resistor 220 ohm
  - module relay
  - pompa mini
        
- **Rule Based Algorithm**
  
- **Metode Perancangan Sistem**
  - Identifikasi Kebutuhan: kebutuhan fungsional dan non-fungsional perangkat IoT
  - Pemilihan Platform: platform yang dipilih pada perancangan sistem ini yaitu Arduino Uno
  - Desain Hardware: pemilihan komponen sensor, akuator, dan koneksi antar komponen
  - Pengembangan Perangkat Lunak: pada sistem kali ini pemrograman firmware perangkat menggunakan bahasa pemrograman C
  - Koneksi Jaringan: penghhubungan perangkat baik itu dengan internet, wifi, atau bluetooth
  - Keamanan Perangkat: ancaman paling serius pada sistem kali ini berasal dari luar seperti bencana, atau gangguan dari hewan terhadap perangkat
  - Uji Coba dan Optimisasi: pengujian perangkat secara menyeluruh untuk memastikan fungsionalitasnya sesuai dengan keinginan
  - Perawatan dan Pemantauan Perangkat: penjagaan terhadap kinerja perangkat
 
## Struktur Data

![](https://github.com/muhamadiqbalsetiawan/Anthopqua-Ubicom/blob/main/struktur_ubicom.png)

## Arsitektur Sistem
![](https://github.com/muhamadiqbalsetiawan/Anthopqua-Ubicom/blob/main/arsitektur_ubicok.png)

## Deskripsi Teknologi
•	Software development 
  - Java lenguage: bahasa pemrograman yang dapat dijalankan diberbagai komputer termasuk telepon genggam. Bahasa ini sudah berjalan pada miliaran perangkat diseluruh dunia, bahasa pemrograman multiplatform dan berorientasi-object
•	Sensor 
  -	soil moisture sensor: merupakan module untuk mendeteksi kelempbaban tanah yang dapat diakses menggunakan mikrocontroller seperti arduino, sensor ini dapat digunakan untuk memantau kelembaban tanah baik secara offline maupun online. Cara kerja dari sensor inii yaitu pada saat diberikan catudayadan disensingkan pada tanah, maka nilai output analog akan berubah sesuai kondisi kadar air pada tanah tersebut. pada saat kondisi tanah:
-	> Basah: tegangan output akan turun 
-	> Kering; tegangan output akan naik
•	Responder 
  - Module Relay: merupakan salah satu piranti yang berproses berdasarkan prinsip elektromagnetik untuk menggerakan kontaktor guna memindahkan posisi ON dan OFF atau sebaliknya dengan memanfaatkan tanaga listrik. Cara kerja dari relay ini adalah dengan memutus dan menyambungkan aliran listrik dalam rangkaian.
  - Pompa air: alat yang digunakan untuk memindahkan fluida(air) dari satu tempat ke tempat lain yang prinsip kerjanya adalah dengan mengubah energi mekanik menjadi energi kinetik. Energi mekanik yang diberikan oleh alat digunakan untuk meningkatkan kecepatan, tekanan atau ketinggian (elevasi). Biasanya, pompa digerakan oleh mesin atau motor.
  - Smartphone: merupakan perangkat elektronik yang di desain untuk memiliki tujuan dan bermacam fungsi praktis dalam mendukung dan memudahkan aktivitas manusia. Dalam kasus ini smartphone berfungsi untuk menangkap input dari mikrocontroller lewat bluetooth dan kemudian memberikan respons dengan notifikasi.

## User Experience (UX) Design
![](https://github.com/muhamadiqbalsetiawan/Anthopqua-Ubicom/blob/main/image.jpg)

![](https://github.com/muhamadiqbalsetiawan/Anthopqua-Ubicom/blob/main/rancangan.png)

## Demo Penjelasan Dari Solusi Ubicom
youtube:
https://youtu.be/MS6pT1NkOW8
https://youtu.be/MS6pT1NkOW8

## Analsis Sistem dari Solusi Ubicom yang Dibuat
perangkat yang dibutuhkan:
  - soil moisture sensor: module untuk mendeteksi kelempbaban tanah yang dapat diakses menggunakan mikrocontroller
  - arduino: module mikro kontroler
  - bread board: perangkai komponen
  - lcd: menampilkan nilai dari sensor
  - camera: mendeteksi tanaman
  - kabel jumper: penghubung sensor dengan mikro kontroler
  - resistor 220 ohm
  - module relay
  - pompa mini

Jadi diharapkan pada project ini perangkat IoT yang dibuat dapat mendeteksi kelembaban tanah sehingga dari hari deteksi tersebut akan menghasilkan respons yanitu penyiraman air otomatis dari pompa air yang telah dihubungkan dengan arduino, selainna itu juga terdapat camera yang dapat mendeteksi hama dan grow up pada tunaman tersebut, dan semua itu dapat di kontrol dengan perangkat mobil.

## Tampilan Project
![](https://github.com/muhamadiqbalsetiawan/Anthopqua-Ubicom/blob/main/foto.jpg)

## Draf Proposal
google doc:
https://docs.google.com/document/d/1XJ5tIxdO3-V65OxFybV-0UgZm25w47eEalMKNG_MdvU/edit?usp=sharing
https://docs.google.com/document/d/1XJ5tIxdO3-V65OxFybV-0UgZm25w47eEalMKNG_MdvU/edit?usp=sharing
