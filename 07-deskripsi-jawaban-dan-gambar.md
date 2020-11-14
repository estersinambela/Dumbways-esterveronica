DNS adalah sistem yang dapat memudahkan pengguna ketika mengakses internet
atau sistem yang menjadi pengubung antara URL dan IP add.
Ketika pengguna ingin mengakses sebuah web maka pengguna tidak perlu mengingat
ip add melainkan hanya domain nya saja untuk diinput pada bar.
Jadi fungsi DNS adalah untuk menerjemahkan ip add ke domain atau pun sebaliknya.

Cara kerja DNS 

- DNS Query
DNS Query merupakan istilah teknis untuk meminta informasi soal IP Address. 
Tahapan ini dimulai ketika Anda mengetikkan URL ke address bar. 
DNS server kemudian mencari informasi di filehosts. Jika informasi yang 
dicari tidak ditemukan, server akan berusaha mencari kepingan informasi atau 
rekam informasi yang pernah tercatat di sistem (cache).
Dalam tahapan awal ini sendiri, terdapat tiga jenis DNS Query. 
Ketiganya adalah recursive query, iterative query, dan non-recursive query.

- DNS Recursor
DNS recursor merupakan tahapan pertama pencarian informasi. 
Ketika user memasukkan URL dan tidak menemukan hasil yang valid di cache, 
sistem akan mencari informasi dalam cache penyedia internet atau internet 
service provider (ISP). 

- Root Name Server
Root name server merupakan semacam database yang menjawab pertanyaan soal 
nama domain dan IP Address. Server ini tidak memiliki jawaban tepat untuk 
informasi yang dicari.
Akan tetapi, server ini bisa meneruskan permintaan informasi ke pihak
yang lebih mengetahui. Di dunia ini, terdapat 13 root server yang bekerja. 
Root server tersebut diurutkan secara alfabetis dari A sampai M.

- TLD Name Server
Dari root name server, sistem akan membaca jenis informasi yang dicari dari 
top-level domain. Setiap TLD seperti .COM, .ORG, .EDU, .ID, .AU, 
dan sebagainya memiliki server yang spesifik.

- Authoritative Name Server
Setelah menemukan klu di mana server yang diinginkan, 
sampailah pada authoritative name server. Jenis server satu ini memiliki 
semua informasi lengkap soal situs web yang dituju.

Ketika informasi yang diminta sesuai dengan hasilnya, maka browser akan 
menampilkan situs web atau halaman yang Anda minta di awal. 
Tentu saja hasil pencarian ini memiliki masa waktu tertentu.



