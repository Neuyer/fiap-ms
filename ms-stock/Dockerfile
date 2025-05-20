FROM amazoncorretto:21

WORKDIR /usr/local/app

COPY *.jar ./

EXPOSE 8080

RUN chmod 777 *.jar

CMD ["java", "-jar", "-Dspring.profiles.active=prd", "/usr/local/app/stock-0.0.1.jar"]

