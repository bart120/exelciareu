FROM maven:3-jdk-8-alpine

WORKDIR /usr/src/app

COPY . .
RUN mvn package

ENV PORT 5000
EXPOSE ${PORT}

CMD ["sh", "-c", "mvn -Dserver.port=${PORT} spring-boot:run"]
