# P1 持续集成和部署

* /web/pom.xml
```xml
<plugins>
  <plugin>
      <groupId>org.springframework.boot</groupId>
      <artifactId>spring-boot-maven-plugin</artifactId>
  </plugin>
  
  <plugin>
    <groupId>com.github.eirslett</groupId>
    <artifactId>frontend-maven-plugin</artifactId>
  </plugin>
</plugins>
```

* CICD (jenkins)
* (前后端打包的配置)[https://confluence.synnex.com/display/~lukexj/P1+Auto+Pack+for+frontend]
