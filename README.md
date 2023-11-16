# Spring Data Rest

## Overview
Spring Data REST is part of the umbrella Spring Data project and makes it easy to build hypermedia-driven REST web services on top of Spring Data repositories.

Spring Data REST builds on top of Spring Data repositories, analyzes your application’s domain model, and exposes hypermedia-driven HTTP resources for aggregates contained in the model.

## Adding Spring Data REST to a Spring Boot Project
### For Gradle build
```
dependencies {
  ...
  compile("org.springframework.boot:spring-boot-starter-data-rest")
  ...
}
```

### For Maven build
```
<dependencies>
  ...
  <dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-data-rest</artifactId>
  </dependency>
  ...
</dependencies>
```
