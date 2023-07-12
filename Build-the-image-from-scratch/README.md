To get started with building the web server container image, you will need to have Docker installed on your machine.
Once Docker is installed, you can follow these steps :

•	Create an new directory for the project :mkdir project-name

•	get into the directory : cd project-name

•	Add the file Dockerfile

•	Run docker build -t image-name to build the server image

•	you need to map the host port with docker port : docker run -p 80:80 image-name

•	To list all Docker containers regardless of their status : docker ps --all
