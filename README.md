#Hello World
https://spring.io/guides/gs/spring-boot-docker/

###Executar a aplicação localmente
```bash
./mvnw package -DskipTests=false && java -jar target/hello-0.0.1-SNAPSHOT.jar
```
###Executar a aplicação em container
```bash
docker build -t springio/gs-spring-boot-docker .
docker run -p 8080:8080 springio/gs-spring-boot-docker
```

