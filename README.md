##Lab 4 - Create a Spring Cloud Eureka Server and Client (3)

Using one project and Maven to run 5 word servers given theirs profiles:

- 1. Run microspring5-cloud-server-lab4
- 2. Run microspring5-eureka-server-lab4
- 3. Run microspring5-sentence-server-lab4 
- 4. Start 5 separate copies of the microspring5-word-server-lab4, using the profiles "subject", "verb", "article", "adjective", and "noun". Go to the root of each server and run:
  
    ```
    mvn spring-boot:run -Drun.jvmArguments="-Dspring.profiles.active=subject"
    mvn spring-boot:run -Drun.jvmArguments="-Dspring.profiles.active=verb"
    mvn spring-boot:run -Drun.jvmArguments="-Dspring.profiles.active=article"
    mvn spring-boot:run -Drun.jvmArguments="-Dspring.profiles.active=adjective"
    mvn spring-boot:run -Drun.jvmArguments="-Dspring.profiles.active=noun"
    ```
