# learnJava
spring boot first

## samples

### first sprint boot example

look into hello2.groovy
then terminal spring run hello2.groovy
then browser 127.0.0.1:8080

### second spring boot example

1. need to open project kotlin-learning
   1. open KotinLearningApplication.kt 
   2. mouse right click on fun main and run it
    3. browser open 127.0.0.1:8080/rest/users/all, empty initially
    4. then 127.0.0.1:8080/rest/users/insert/peter, show 1 user json
    5. then 127.0.0.1:8080/rest/users/insert/sam, show 2 users json
2. refer to video tutorial
[Spring Boot (Spring MVC and JPA) App using Kotlin in Java 8 runtime | Tech Primers](https://www.youtube.com/watch?v=30wfb-zOSEk&t=99s)
   
3. learn how to use project generator from
[spring io start] (https://start.spring.io/)
   
### first maven example
1. execute
```dtd
mvn archetype:generate -DgroupId=com.mycompany.app -DartifactId=my-app -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false
```
2. then my-app folder generated, move into the folder, then build it
```dtd
mvn package
```
3. build error encountered like 
```dtd
[ERROR] Failed to execute goal org.apache.maven.plugins:maven-compiler-plugin:3.1:compile (default-compile) on project my-app: Compilation failure: Compilation failure:
[ERROR] Source option 5 is no longer supported. Use 7 or later.
[ERROR] Target option 5 is no longer supported. Use 7 or later.
```
   
## log

### 2021/2/23
1. first maven example

### 2021/1/20
initial successful test for spring boot, 1st and 2nd examples
