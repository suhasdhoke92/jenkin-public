FROM tomcat:latest

ARG artifact=final.war

WORKDIR /usr/local/tomcat/webapps/

COPY ${artifact} final.war

#COPY final.war /usr/local/tomcat/webapps/

EXPOSE 8080
