# Hello Logger
## Prerequisites
Install Java and maven.

## Running
After cloning this repo, you can build the project using maven:
```
mvn clean package
```
Then to run it, use:
```
java -jar target/hello-logger-1.0-SNAPSHOT.jar
```

This project is setup to send logs to siglens.
See https://github.com/siglens/siglens for instructions to install and run siglens.

This project assumes siglens is running on the same machine that you run this project on, and with the default siglens ingest port.
If you change the siglens ingest port or are running siglens on a different machine, make sure to update log4j2.xml to specify the correct URL to send the logs to.
