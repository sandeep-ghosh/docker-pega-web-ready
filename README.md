Pega Docker Image
===========

Forked from [pegasystems/docker-pega-web-ready](https://github.com/pegasystems/docker-pega-web-ready), used baseimage tomcat:9 with OpenJDK, compiled in Apple Silicon (arm64).

You cannot run the image directly because it does not come with the Pega web application (.war file). Therefore you must use this image as a base to construct an executable Docker image.
