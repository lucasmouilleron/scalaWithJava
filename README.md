scalaWithJava
=============

Compile
-------
- `mkdir classes`
- `scalac -d classes *.scala *.java`
- `javac -d classes -classpath $SCALA_HOME/lib/scala-library.jar:target/classes *.java`

Run
---
- `scala -cp classes test.HelloWorld`

Doc
---
- http://www.codecommit.com/blog/scala/joint-compilation-of-scala-and-java-sources
- http://stackoverflow.com/questions/28158173/building-a-project-with-mixed-scala-and-java-source-files-using-ant-illegal-cy