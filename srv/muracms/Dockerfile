FROM blueriver/muracms:latest

ENV APP_DIR="/var/www"

COPY ./srv/muracms/conf/catalina.* /usr/local/tomcat/conf/
COPY ./srv/muracms/conf/server.* /usr/local/tomcat/conf/
COPY ./srv/muracms/conf/web.* /usr/local/tomcat/conf/
COPY ./srv/muracms/conf/lucee-server.* /opt/lucee/server/lucee-server/context/
COPY ./srv/muracms/conf/lucee-web.* /opt/lucee/web/

RUN apt-get update && apt-get install -y vim && apt-get clean && rm -rf /var/lib/apt/lists/* 

EXPOSE 8888