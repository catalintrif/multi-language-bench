# Benchmark results

This is the 2011 C++/Java/Scala/Go language benchmark of Robert Hundt, updated and rerun with the current versions of compilers. \
Optimized versions of JVM languages (Java and Scala) take the lead in runtime speed while C++ (not optimized) still has the lowest memory consumption. \
With the latest compiler, Go speed has greatly improved, while keeping memory usage to a modest level.

### Configuration: 
- MacBook Pro 2.7 GHz Intel Core i5
- Apple LLVM version 9.0.0 (clang-900.0.38)
- Target: x86_64-apple-darwin16.7.0
- Java(TM) SE Runtime Environment (build 1.8.0_202-b08)
- Java HotSpot(TM) 64-Bit Server VM (build 25.202-b08, mixed mode)
- Scala sbt 1.3.8
- go version go1.13.1 darwin/amd64

## Results

| Language | Run time | Memory |
|----------|----------|--------|
| C++      | 20 s     | 140 MB |
| Java     | 16 s     | 921 MB |
| Java_pro | 11 s     | 523 MB |
| Scala    | 24 s     | 690 MB |
|Scala_pro | 10 s     | 1070 MB|
| Go       | 29 s     | 483 MB |
| Go_pro   | 22 s     | 332 MB |

## Other configurations
### OpenJDK 13
OpenJDK Runtime Environment (build 13.0.2+8) \
OpenJDK 64-Bit Server VM (build 13.0.2+8, mixed mode, sharing)

| Language | Run time | Memory |
|----------|----------|--------|
| Java     | 28 s     | 1310 MB |
| Java_pro | 12 s     | 1310 MB |
| Scala    | 33 s     | 1200 MB |
|Scala_pro | 12 s     | 692 MB|

### Oracle JDK 13
Java(TM) SE Runtime Environment (build 13.0.2+8)
Java HotSpot(TM) 64-Bit Server VM (build 13.0.2+8, mixed mode, sharing)

| Language | Run time | Memory |
|----------|----------|--------|
| Java     | 28 s     | 1500 MB |
| Java_pro | 12 s     | 1200 MB |
| Scala    | 30 s     | 1180 MB |
|Scala_pro | 12 s     | 1130 MB|
