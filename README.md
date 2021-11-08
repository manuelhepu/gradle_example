[![Gradle Build](https://github.com/tkgregory/spring-boot-api-example/actions/workflows/gradle-build.yml/badge.svg)](https://github.com/tkgregory/spring-boot-api-example/actions/workflows/gradle-build.yml)



## Pre-requisites

* JDK 8+
* Docker

## Building

### Testing

`./gradlew test`

### Building (no tests)

`./gradlew assemble`

### Building (with tests)

`./gradlew build`

### Running in Docker

`./gradlew assemble docker dockerRun`

### Stopping Docker container

`./gradlew dockerStop`
