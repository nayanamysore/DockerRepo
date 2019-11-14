FROM java:8-jre
WORKDIR /usr/src
ENV MYSQL_URL=jdbc:mysql://dockermysql/UserDB
ENV MY_SQL_USER=root
ENV MY_SQL_PASSWORD=Welcome123
ADD ./target/shoppingcart-0.0.1-SNAPSHOT.war /usr/src/shoppingcart-0.0.1-SNAPSHOT.war
ENTRYPOINT ["java","-jar","shoppingcart-0.0.1-SNAPSHOT.war"]
