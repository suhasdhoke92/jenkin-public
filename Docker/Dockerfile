FROM tomcat:latest

ARG artifact=/var/lib/jenkins/workspace/final.war

WORKDIR /usr/local/tomcat/webapps/

COPY ${artifact} final.war

#COPY final.war /usr/local/tomcat/webapps/

EXPOSE 8080
