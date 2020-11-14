1.	Menginstall dns server yaitu bind
Perintah	: yum install –y bind bind-utils
Screenshot	: 08.1
 
2.	Edit file named.conf, pada options masukkan ip addr centos di bagian listen-on port 53 dan allow-query seperti gambari dibawah.
Perintah	: nano /etc/named.conf
Screenshot	: 08.2
 
 
3.	Selanjutnya edit file forward seperti dibawah ini
Perintah	: nano /var/named/forward.zone
Screenshot	: 08.3
 
4.	Edit file reverse seperti dibawah ini
Perintah	: nano /var/named/reverse.zone
Screenshot	: 08.4
 
5.	Atur file resolve
Perintah : nano /etc/resolv.conf
Screenshot	: 08.5
 
6.	Selanjutnya restart named dan aktifkan named
Perintah	: systemctl restart named
		  systemctl enable named
Screenshot	: 08.6
 
7.	Untuk melihat dengan menggunakan web server kita terlebih dahulu install web servernya, disini saya menggunakan apache 
Perintah	: yum install –y httpd
Screenshot	: 08.7
 
8.	Enable dan start httpd
Perintah	: systemctl enable httpd
		  systemctl start httpd
Screenshot	: 08.8
 
9.	Aktifkan firewall dns dan http
Perintah	: firewall-cmd –add-service=dns –permanent
		  firewall-cmd –add-service=http –permanent
		  firewall-cmd –reload
Screenshot	: 08.9
 
10.	Cek nama domain dengan perintah nslookup
Perintah	: nslookup dumbways-esterveronica.xyz
Screenshot	: 08.10
 
11.	Kita juga dapat melakukan pengecekan dengan perintah dig
Perintah	: dig dumbways-esterveronica.xyz
Screenshot	: 08.11
 
12.	Cek melalui browser
Screenshot	: 08.12
	 
Melalui langkah-langkah diatas kita sudah berhasil menginstall dan melakukan konfigurasi dns server serta menghasilkan sebuah domain.
