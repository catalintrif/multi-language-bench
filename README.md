# Benchmark results

This is the 2011 language benchmark of Robert Hundt, updated and rerun with the current versions of compilers.
Optimized versions of JVM languages (Java and Scala) take the lead in runtime speed while C++ (not optimized) still has the lowest memory consumption.
With the latest compiler, Go speed has greatly improved, while keeping memory usage to a modest level.

### Configuration: 
MacBook Pro 2.7 GHz Intel Core i5
Java(TM) SE Runtime Environment (build 1.8.0_202-b08)
Java HotSpot(TM) 64-Bit Server VM (build 25.202-b08, mixed mode)
Scala sbt 1.3.8
go version go1.13.1 darwin/amd64

## Run time (s) / memory (MB)
C++: 20 / 140
Java: 16 / 921
Java_pro: 11 / 523
Scala: 24 / 690
Scala_pro: 10 / 1070
Go: 29 / 483
Go_pro: 22 / 332

### OpenJDK 13
OpenJDK Runtime Environment (build 13.0.2+8)
OpenJDK 64-Bit Server VM (build 13.0.2+8, mixed mode, sharing)

Java: 28 / 1310
Java_pro: 12 / 1310
Scala: 33 / 1200
Scala_pro: 12 / 692

### JDK 13
Java(TM) SE Runtime Environment (build 13.0.2+8)
Java HotSpot(TM) 64-Bit Server VM (build 13.0.2+8, mixed mode, sharing)

Java: 28 / 1500
Java_pro: 12 / 1200
Scala: 30 / 1180
Scala_pro: 12 / 1130

