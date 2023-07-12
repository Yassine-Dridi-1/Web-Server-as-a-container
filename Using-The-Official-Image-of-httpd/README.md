Dockerfile :

•	To get the last version of httpd : FROM httpd:latest

•	Every file you create in the current directory will be copied in /usr/local/apache2/htdocs : COPY . /usr/local/apache2/htdocs
