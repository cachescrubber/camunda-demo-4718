# Reproducer for Camunda 7 Issue #4718

This project is a demo project to reproduce [Camunda 7 Issue #4718](https://github.com/camunda/camunda-bpm-platform/issues/4718).

The Dockerfile is from the official Spring Boot Documentation.

## Usage

```
# mvn verify docker:build
# docker run --rm -ti -p 8080:8080 camunda-demo:0.1.0-SNAPSHOT
```

Point your Browser to http://localhost:8080/ 