Configurer un serveur apache2 linux 

Mettre une ip statique : 172.16.10.34
apt-get install apache2 


Analyse des logs

Requête réussie : 
172.16.10.34 - - [09/Apr/2025:11:44:20 +0200] "GET /next.html HTTP/1.1" 200 933 "http://172.16.10.34/" "Mozilla/5.0 (X11; Linux x86_64; rv:128.0) Gecko/20100101 Firefox/128.0"

Erreur 404 :
172.16.10.34 - - [09/Apr/2025:11:34:32 +0200] "GET /test HTTP/1.0" 404 454 "-" "Lynx/2.9.0dev.12 libwww-FM/2.14 SSL-MM/1.4.1 GNUTLS/3.7.8"


192.168.1.14 - - [03/Apr/2025:10:20:25 +0200] "GET /next.html HTTP/1.1" 404 490 "http://192.168.1.14/" "Mozilla/5.0 (X11; Linux x86_64; rv:128.0) Gecko/20100101 Firefox/128.0"
