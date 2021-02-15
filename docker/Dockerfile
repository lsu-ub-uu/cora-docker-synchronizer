ARG CORA_DOCKER_VERSION
FROM cora-docker-tomcat:${CORA_DOCKER_VERSION}

COPY /server.xml /usr/local/tomcat/conf/
COPY /synchronizer.war /usr/local/tomcat/webapps/synchronizer.war
COPY /synchronizer.xml /usr/local/tomcat/conf/Catalina/localhost/synchronizer.xml