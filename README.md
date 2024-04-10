# Scala with Maven

This project is a template for a Scala project that uses Maven as the build tool. 

To build the project, run:

```shell
mvn clean package
```

To test it against Scala REPL, run:

```shell
scala -cp target/scala-maven-template-1.0-SNAPSHOT.jar
```

To run a simple test, run:

```scala
import io.saawgr.HelloWorld

val helloWorld = new HelloWorld()
helloWorld.sayHello()
```
