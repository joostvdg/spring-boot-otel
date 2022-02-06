# spring-boot-otel

Demo application for showcasing Spring Boot with Open Telemetry (OTEL)

## TODO

* Test Open Telemetry as per:
  * [this blog post](https://allopensourcetech.com/integrating-spring-boot-with-opentelemetry/)
  * [and this blog](https://reflectoring.io/spring-boot-tracing/)
  * https://github.com/open-telemetry/opentelemetry-java-instrumentation
  * https://grafana.com/blog/2021/02/03/auto-instrumenting-a-java-spring-boot-application-for-traces-and-logs-using-opentelemetry-and-grafana-tempo/
  * https://github.com/joe-elliott/tempo-springboot-example
* Test building with Bazel, as per [this blog post](https://www.baeldung.com/bazel-build-tool)
* Test Native Image
* Test WaveFront
* Test Spring Cloud Config Server

## How To Generate This Project

```shell
https://start.spring.io/#!type=maven-project&language=java&platformVersion=2.6.3&packaging=jar&jvmVersion=17&groupId=com.github.joostvdg.demo&artifactId=spring-boot-otel&name=spring-boot-otel&description=Demo%20project%20for%20Spring%20Boot%20with%20OTEL&packageName=com.github.joostvdg.demo.spring-boot-otel&dependencies=devtools,native,data-rest,data-mongodb,actuator,prometheus,wavefront,testcontainers,cloud-config-client
```