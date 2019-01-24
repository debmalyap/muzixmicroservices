FROM openjdk:11.0-jdk

ADD ./target/configserver-0.0.1-SNAPSHOT.jar /muzix/app/configserver-0.0.1-SNAPSHOT.jar

EXPOSE 8183

ENTRYPOINT ["java", "-jar", "configserver-0.0.1-SNAPSHOT.jar"]