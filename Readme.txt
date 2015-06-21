https://spark.apache.org/docs/latest/quick-start.html#self-contained-applications
compile:
mvn compile
package:
mvn package

run 
spark-submit --class "SimpleApp" --master local[4]  target/simple-project-1.0.jar
