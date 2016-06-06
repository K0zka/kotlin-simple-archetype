@Deprecated
===========

[Kotlin 1.0.2 was released](https://blog.jetbrains.com/kotlin/2016/05/kotlin-1-0-2-is-here/) with an archetype, this project won't be needed in the future.

kotlin-simple-archetype
=======================

[![Kotlin](https://img.shields.io/badge/kotlin-1.0.0-blue.svg)](http://kotlinlang.org)

Simple kotlin archetype for maven for libraries and stand alone apps

Usage
=====

To kickstart your [kotlin](http://kotlinlang.org/) project with [maven](http://maven.apache.org/), simply copy paste this into the command line:

```
mvn archetype:generate \
    -DarchetypeArtifactId=kotlin-simple-archetype \
    -DarchetypeGroupId=com.github.K0zka \
    -DarchetypeVersion=1.0.0 \
    -DgroupId=com.foo.bar \
    -DartifactId=kickass-app \
    -DinteractiveMode=false
```
Enjoy kotlin!
