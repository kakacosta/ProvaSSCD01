#!/bin/bash

apt-get -y update

apt-get install -y apache2

apt-get install -y wget

wget https://gist.github.com/nunomazer/873219/archive/690e1f604dc8ead2583589e1aee6f8a42040a035.zip

apt-get install -y zip
apt-get install -y unzip

unzip 690e1f604dc8ead2583589e1aee6f8a42040a035.zip
cd 873219-690e1f604dc8ead2583589e1aee6f8a42040a035
cp cv-resumido.html /var/www/html/
cp style.css /var/www/html/

cd /var/www/html
rm index.html

cd /var/www/html/
mv cv-resumido.html index.html

/etc/init.d/apache2 start
