FROM tomcat:11.0
ADD **/*.war /opt/tomcat/webapps
ADD ./server.xml /opt/tomcat/conf
EXPOSE 8081
CMD ["catalina.sh", "run"]
