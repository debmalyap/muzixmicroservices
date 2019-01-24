FROM openjdk:11.0-jdk

ADD ./target/ZuulService-0.0.1-SNAPSHOT.jar /muzix/app/ZuulService-0.0.1-SNAPSHOT.jar

EXPOSE 8185

ENTRYPOINT ["java", "-jar", "ZuulService-0.0.1-SNAPSHOT.jar"]