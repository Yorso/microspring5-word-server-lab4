##Lab 4 - Create a Spring Cloud Eureka Server and Client (2)

Using one project and Maven to run 5 word servers given theis profiles:

Start 5 separate copies of the microspring5-word-server-lab4, using the profiles "subject", "verb", "article", "adjective", and "noun":
  
```
    mvn spring-boot:run -Drun.jvmArguments="-Dspring.profiles.active=subject" &
    mvn spring-boot:run -Drun.jvmArguments="-Dspring.profiles.active=verb" &
    mvn spring-boot:run -Drun.jvmArguments="-Dspring.profiles.active=article" &
    mvn spring-boot:run -Drun.jvmArguments="-Dspring.profiles.active=adjective" &
    mvn spring-boot:run -Drun.jvmArguments="-Dspring.profiles.active=noun"
```
