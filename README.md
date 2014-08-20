docker-apache-mysql
===================

docker + apache + mysql + phpadmin for devel


$ sudo docker build -t jdelacasa/apache-mysql-phpmyadmin .

$ sudo docker run -d -p 2223:22 -p 80:80 -p 9001:9001 jdelacasa/apache-mysql-phpmyadmin
