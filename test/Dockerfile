FROM adoptopenjdk/openjdk8:alpine-jre
ADD target/*.jar springboot-docker.jar
ENTRYPOINT ["java","-jar","/springboot-docker.jar"]