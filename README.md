**Xampp Set Up**
====================
1 ) Go to this path C:\xampp\apache\conf\extra

2 ) Open file **httpd-xampp**

3 ) Set Virtual Host for project 

Ex  <VirtualHost *:80>
     DocumentRoot "C:/xampp/htdocs/"
     ServerName app.authorevo.com
     ServerAlias *.app.authorevo.com
 </VirtualHost>
 <VirtualHost *:443>
     DocumentRoot "C:/xampp/htdocs/"
     ServerName app.authorevo.com
     ServerAlias *.app.authorevo.com
     SSLEngine on
     SSLCertificateFile "C:\Certbot\live\app.authorevo.com\fullchain.pem"
     SSLCertificateKeyFile "C:\Certbot\live\app.authorevo.com\privkey.pem"
 </VirtualHost>
4 ) Open Apache configuration and apply Virtual host changes 

![image_2024_03_08T09_00_51_383Z](https://github.com/wlollo/docs/assets/76046434/2eefd11a-8529-438a-96b6-1288dcdf0143)

5 ) set project wise htaccess at C:\xampp\htdocs 


Angular project Set Up
=============================
please first of check nodejs version  18.17.1  and npm  version  9.6.7  

please follow this command


node version

node -v


npm version 

npm  -v 

npm install

ng build 

build file move of htdocs new folder create and move here and save it.
then create .htaccess file and configuration file added and folder wise path added.

and save it

this video for frontend 

https://github.com/wlollo/docs/assets/76046434/37413a5c-a1fd-4b60-9a4b-78c8983c6add



all backend project 
============================
please first of check nodejs version  18.17.1  and npm  version  9.6.7  

please follow this command

node version

node -v

npm version 

npm  -v 

npm install

pm2 start index.js

for start project


this video for backend 

https://github.com/wlollo/docs/assets/76046434/8d4c3f55-a20f-4bb2-8202-1323e49b5837
