# WebServer
a simple web server using golang and docker


<b>clone repo on your local system</b> </br>
git clone https://github.com/rkravi2015/WebServer.git

<b>navigate to app folder</b> </br>
cd WebServer/HelloWorldInGoLang

<b>build this image</b> </br>
docker build --tag webserver:1.0 .

<b>run this image</b> </br>
docker run --publish 8000:8080 --detach --name wb webserver:1.0
