FROM tomcat:11.0
ADD **/*.war /usr/local/tomcat/webapps
ADD ./server.xml /usr/local/tomcat/conf
EXPOSE 8081
CMD ["catalina.sh", "run"]
