FROM openjdk:8-jre-alpine
WORKDIR usr/src
ENV MYSQL_DATABASE=pubgdb
ENV MYSQL_USER=app_root
ENV MYSQL_PASSWORD=root123
ENV MYSQL_CI_URL=jdbc:mysql://localhost:3306/pubgdb
ADD ./target/favouriteservice-0.0.1-SNAPSHOT.jar /usr/src/favouriteservice-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java","-jar","favouriteservice-0.0.1-SNAPSHOT.jar"]
