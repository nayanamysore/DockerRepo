FROM java:8-jre
WORKDIR /usr/src
ENV MYSQL_URL=jdbc:mysql://localhost:3306/UserDB
ENV MY_SQL_USER=root
ENV MY_SQL_PASSWORD=Welcome123
ADD ./target/shoppingcart-0.0.1-SNAPSHOT.jar /usr/src/shoppingcart-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java","-jar","shoppingcart-0.0.1-SNAPSHOT.war"]
