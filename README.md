# Tentang repository ini :

## Capstone Project Modul 2 Purwadhika : Data Analyst

Capstone ini akan membahas analisa dari sebuah data yang diambil dari kaggle yang bernama **Trending YouTube Video Statistics** (dataset dapat diakses [di sini](https://drive.google.com/drive/folders/1JFhDSfs4vzWuCdsBFObEp5sVLQMo-dR1)). Summary pembahasannya adalah sebagai berikut:


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Youtube adalah website tempat berbagi video secara gratis. Walaupun pengguna Youtube mengakses secara gratis, Youtube tetap membayar sejumlah uang yang besarnya bervariasi kepada pembuat atau penyedia video (*content creator*) di dalamnya. Bayaran yang menggiurkan dan tidak adanya batasan usia untuk menjadi *content creator*, membuat Youtube dijadikan sebagai pekerjaan tetap bagi para *content creator* . Selama *content creator* dapat menyediakan video yang dapat ditonton oleh banyak orang, Youtube tidak segan-segan akan membayar sejumlah uang tergantung dari banyaknya *view* pada video yang dibuat. Namun akun atau *channel* milik *content creator* harus diverifikasi terlebih dahulu sehingga akan mengikat pada term and agreement. Dilihat dari cara mendapatkan uang pada Youtube yang tergolong mudah, tak heran banyak orang yang berbondong-bondong untuk menjadi *content creator* pada *website* raksasa ini. Namun ada hal yang perlu diperhatikan bagi para *content creator* pemula yaitu bagaimana mereka "menjual" video mereka supaya dapat di-*view* oleh banyak orang sehingga *channel* mereka dapat berkembang dan dikenal. Youtube memiliki fitur berlangganan bernama "*subscribe*", fitur ini menjadi daya tarik sebuah *channel* dengan menampilkan berapa banyak *subscriber* yang ada pada *channel* tersebut sehingga banyak menarik perhatian banyak orang. Bagi pemula, menaikkan jumlah *subscriber* bukan perkara yang mudah. Mereka harus bekerja keras untuk mengiklankan video mereka kepada orang-orang. Namun ada salah satu cara supaya orang-orang dapat melirik *channel* para pemula dengan memanfaatkan fitur "*Youtube Trending Videos*". Fitur ini akan menjajakan video apa saja yang sedang tren di beranda pengguna Youtube. Tren video dikategorikan baik dari tiap negara sampai seluruh dunia tak terkecuali Negara US. Tidak peduli video yang sedang tren berasal dari *channel* yang terkenal ataupun tidak, selama video ditonton oleh banyak orang, dapat dikatakan "pasti" orang-orang yang menonton video tersebut akan mengunjungi *channel* dari pemilik video tren tersebut. Hal ini menjadi kesempatan besar bagi para pemula supaya *channel*-nya dilirik oleh banyak orang yang berpotensi menjadi *subscriber*.<br>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Dengan adanya fitur *Youtube Trending Videos*, pemula *content creator* mendapatkan kesempatan yang besar supaya channelnya dilirik oleh banyak pengguna. Oleh karena itu para content creator ingin mengetahui bagaimana video mereka dapat menjadi video yang tren. Sebagai seorang data analyst, akan dicoba menjawab pertanyaan berikut :

**Bagaimana tipe video yang dipublish masuk menjadi kategori video tren di Negara US?**

Pertanyaan di atas masih tergolong abstrak dan tidak jelas arahnya, maka akan dijadikan beberapa masalah yang jelas diantaranya :

1.	Pengaruh lamanya usia video dari ditayangkan sampai menjadi tren terhadap jumlah video, views, like, dislike, dan jumlah komentar.
2.	Hubungan atau korelasi dari view terhadap berbagai variabel, mengapa view pada video yang tren merupakan faktor yang penting.
3.	Proporsi banyaknya video per jam tayang video.
4.	Proporsi banyaknya video per kategori atau jenis video.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Untuk menjawab pertanyaan di atas, akan dilakukan serangkaian analisa baik secara *descriptive statistic* maupun *inferensial statistic*. Sebelum melakukan analisa terhadap data, terlebih dahulu akan dilakukan *data understanding* dan *data cleaning*. Hal ini dilakukan supaya data benar-benar siap untuk dilakukan Analisa.

Setelah dilakukan serangkaian analisa dari data tersebut, diambil sejumlah insight yang isinya adalah:
 
1. View adalah faktor terkuat utama terhadap video yang tren (penjelasan ada di kesimpulan nomor 6).

2. Tidak peduli berapa lama usia video sejak ditayangkan, seluruh video tetap memiliki kesempatan untuk menjadi trending. 

3. Jika video ingin trending dalam waktu yang cepat, dalam kurun waktu 15 hari `days until trending` memiliki pengaruh yang besar terhadap `view`, `like`, `dislike`, dan `jumlah komentar`. Hal ini tentu akan dirasa sulit bagi para pemula yang mengejar jumlah `view` setidaknya paling sedikit sebanyak 100 ribu.

4. `View` terkecil supaya video menjadi tren dipengaruhi oleh performa penayangan video terhadap performa dari penayangan video-video sebelumnya dengan channel yang sama. Hal ini membuat `view` terkecil nilainya masih bias karena angka 100 ribu-pun masuk ke dalam kategori.

5. Hasil korelasi membuat kejelasan dari pernyataan kesimpulan nomor 2 bahwa ketika `days until trending` dari video yang sudah melebihi 32 hari, maka dipastikan pengaruhnya kecil sekali. Berbeda dengan `view` yang korelasinya benar-benar kuat terhadap variabel lainnya.

6. Korelasi kuat yang ditunjukkan pada `view` memastikan bahwa pengaruh `view` terhadap video yang tren adalah faktor utama. Hal ini juga diperkuat oleh pernyataan resmi dari Youtube (bisa diakses [di sini](https://support.google.com/youtube/answer/7239739?hl=en)), dan tak sengaja kita juga membuktikan kebenaran dari pernyataan tersebut.

7. `Jam tayang` sebuah video tidak bisa menjadi acuan jika kita memasukkan seluruh data. Sebaliknya dalam kurun waktu kurang dari 2 hari, waktu `jam tayang` yang paling berpengaruh adalah dari siang hari menjelang sore hari.

8. Minat tontonan video yang tren pada negara US adalah `Entertaintment` kemudian `Music` dan disusul `How to & Style`. Hal ini bisa dijadikan kategori acuan bagi para pemula yang ingin memulai karir sebagai content creator pada Youtube.
<br>
<br>
<br>
<br>

Muhammad Mukhlis JC Data Science and Machine Learning
-



