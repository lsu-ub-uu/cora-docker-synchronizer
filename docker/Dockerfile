ARG CORA_DOCKER_JAVA_VERSION
FROM cora-docker-java:${CORA_DOCKER_JAVA_VERSION}

COPY /alvinindexmessenger*.jar /indexing/alvinindexmessenger.jar

COPY /*.properties /indexing/properties/

WORKDIR /indexing

CMD java -classpath /indexing/properties/:/indexing/alvinindexmessenger.jar:/indexing/log4j.jar se.uu.ub.cora.alvin.indexmessenger.AlvinIndexMessengerStarter

