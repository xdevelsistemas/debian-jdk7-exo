# Debian + Oracle jdk 7 + eXo Platform Community Docker container

* Debian jessie
* Oracle JDK 7 update 71
* eXo Platform 4.1.0 Community edition

## How to

* run the container


    docker run -d -p 8080:8080 --name=exo exoplatform/ubuntu-jdk7-exo:plf-4.1.0

* watch container logs


    docker logs --follow exo
