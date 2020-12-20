# git-info
docker made git information 

This app was made from all open source tools.
\
 Even Atom was used to create it from the scratch. \

Docker Side
-----------

### To build the image

You need to build the Image upon some pre existing image. \
 Here I have used Nginx Server to host this. \
 Hence image is nginx:latest can be found upon
[DockerHub](https://hub.docker.com/_/nginx) or
[GitHub](https://github.com/nginxinc/docker-nginx/) \
 \
 Command to buld \
 `docker build -t git_app:oss .` \
 git\_app is the name \
 oss is the tag \
 where as . reffers to current directory where the source resides \
 \
 Run via \
 `docker run -d --name git_app -p 8080:80 git_app:oss` \
 \
 You are good to go Just open browser and type `127.0.0.1:8080` \
 \

About the web page
------------------

You can find out basic template [here](template). \
 Dashboard is the main page and decent to understand and is
[here](index.html). \

Contribution
------------

If you wish to contribute you happily can and is reccomended to.

* * * * *

Worked under OSS Lab,\
 WCE Sangli.\
 By : 2017BTEIT00062 \
 [Aniket Vaishnav](https://github.com/obrutus)

* * * * *
