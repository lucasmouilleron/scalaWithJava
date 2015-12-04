scalaWithJava
=============

Compile
-------
- scalac -d classes *.scala *.java
- javac -d classes -classpath $SCALA_HOME/lib/scala-library.jar:target/classes *.java

Run
---
scala -cp classes test.HelloWorld