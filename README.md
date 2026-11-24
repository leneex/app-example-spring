# Spring

Example [Spring Boot](https://spring.io/projects/spring-boot) app. Spring Boot is a Java framework for building production-ready applications and APIs with minimal configuration.

## Deploy settings

| Field | Value |
| --- | --- |
| Build | Railpack |
| Project directory | `/` |
| Install command | leave empty |
| Build command | leave empty |
| Start command | leave empty |
| Application port | `8080` |
| Health check path | `/` |

## <a name="dev"></a>Run locally

```bash
# run in development mode
./mvnw spring-boot:run

# build for production and run
./mvnw package
java -jar target/hello-0.0.1-SNAPSHOT.jar
```

Requires JDK 21 or later. `./mvnw` will automatically download the required Maven version.
