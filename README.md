# Hello Java Maven - Jenkins Build Task
- `src/main/java/HelloWorld.java`: Java code (default package).
- `pom.xml`: Maven config with executable JAR.
- `screenshot.png`: Jenkins build success.
## Steps
1. Created Java app with Maven.
2. Set up Jenkins in Docker.
3. Configured Maven/JDK in Jenkins.
4. Built Freestyle job with `clean package`.
5. Fixed `pom.xml` for `HelloWorld` main class.
6. Ran build, got `BUILD SUCCESS`.
7. Ran `java -jar helloww-1.0.jar` (output: `Hello, Jenkins + Maven!`).
## Tools
- Java JDK 11, Maven 3.8.6, Jenkins (Docker), Git, VS Code
## Output
`Hello, Jenkins + Maven!`