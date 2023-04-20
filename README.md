1. Add dependency
<dependency>
      <groupId>io.quarkus</groupId>
      <artifactId>quarkus-spring-cloud-config-client</artifactId>
</dependency>

2. Add below properties in application.properties
      quarkus.spring-cloud-config.enabled=true
      quarkus.spring-cloud-config.url=http://localhost:8888
