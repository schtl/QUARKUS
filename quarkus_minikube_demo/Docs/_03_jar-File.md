# Jar File
https://quarkus-seminar.github.io/2024-lab-minikube/#_jar_file_erstellen_uber_jar
https://imagej.net/develop/uber-jars

```bash
quarkus.package.type=uber-jar
```
must in:

```text
application.properties
```

Rebuild the project:
```bash
./mvnw clean package
```

## Test the application
Change into 'target'
```bash
cd target/
java -jar  quarkus_minikube_demo-1.0-SNAPSHOT-runner.jar
```