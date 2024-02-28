FROM tomcat:latest

ARG artifact=target/spring-boot-web.jar

WORKDIR /usr/local/tomcat/webapps/

COPY ${artifact} app.jar

#COPY final.war /usr/local/tomcat/webapps/

EXPOSE 8080
