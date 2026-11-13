# Hello REST API

A minimal Spring Boot REST API that returns a greeting.

## Run

```bash
mvn spring-boot:run
```

Request `GET http://localhost:8080/api/hello` to receive:

```json
{"message":"Hello"}
```

Run the tests with `mvn test`.