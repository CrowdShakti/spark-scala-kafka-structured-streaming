### Building the project
Let's use maven for building the project.
```
mvn package
```

### Running the project
The command for running the jar file created by build phase is:

```spark-submit --class com.examples.MainExample  --packages org.apache.spark:spark-sql-kafka-0-10_2.11:2.1.0  --master local[2] target/spark-scala-maven-project-0.0.1-SNAPSHOT-jar-with-dependencies.jar```

