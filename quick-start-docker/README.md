# Quick start docker example
This example shows the easy and less code usage of [camunda-bpm-spring-boot-starter](https://github.com/camunda/camunda-bpm-spring-boot-starter).

Build an run:
```
mvn package docker:build
docker run info.quarrymen.camunda-spring-boot-starter-examples/quick-start-docker
```

**Note:** There is no code for camunda configuration. Just concentrate on your processes!

Simply starts a process every 10 seconds. The delegate is _async before_ so the job executor is invoked.

![example.bpmn](src/main/resources/example.png)
