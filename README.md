# pull base image
From tomcat:8-jre8

# manitainer
MAINTAINER "kannika.vps@gmail.com"

#copy war file on to container
COPY '/webapp.war/usr/local/tomcat/webapps
