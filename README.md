# Apache Maven: Beginner to Guru

This respository contains code examples for the online course [Apache Maven: Beginner to Guru.](https://www.udemy.com/draft/2043700/?couponCode=GITHUB_REPO)

# Alternate JVM Languages in Maven

This repository has examples of using Maven to compile popular alternate JVM Languages.

# Scala

It was hard to get the compilation to work... First make use of the [scala-maven-plugin](https://davidb.github.io/scala-maven-plugin/example_java.html), but unlike in the example,
where the dependency on *scala-library* is defined, in order to cross-compile using *sbt*, I had to pull another dependency instead: [org.scala-sbt/zinc_2.13](https://mvnrepository.com/artifact/org.scala-sbt/zinc_2.13/1.10.0).