# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.665 ops/ms
Iteration   1: 6.926 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.926 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.030 ops/ms
Iteration   1: 12.230 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.230 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.921 ops/ms
Iteration   1: 13.880 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.880 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 6.157 ops/ms
Iteration   1: 9.400 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.400 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.173 ±(99.9%) 0.088 ms/op
Iteration   1: 2.121 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.121 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.358 ±(99.9%) 0.061 ms/op
Iteration   1: 1.860 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.860 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.276 ±(99.9%) 0.055 ms/op
Iteration   1: 1.969 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.969 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.310 ±(99.9%) 0.105 ms/op
Iteration   1: 3.369 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.369 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.678 ±(99.9%) 0.115 ms/op
Iteration   1: 2.193 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.553 ms/op
                 createUser·p0.50:   2.071 ms/op
                 createUser·p0.90:   2.544 ms/op
                 createUser·p0.95:   2.777 ms/op
                 createUser·p0.99:   7.258 ms/op
                 createUser·p0.999:  22.086 ms/op
                 createUser·p0.9999: 22.333 ms/op
                 createUser·p1.00:   22.348 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14576
  mean =      2.193 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12765 
    [ 2.500,  5.000) = 1565 
    [ 5.000,  7.500) = 115 
    [ 7.500, 10.000) = 35 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.553 ms/op
     p(50.0000) =      2.071 ms/op
     p(90.0000) =      2.544 ms/op
     p(95.0000) =      2.777 ms/op
     p(99.0000) =      7.258 ms/op
     p(99.9000) =     22.086 ms/op
     p(99.9900) =     22.333 ms/op
     p(99.9990) =     22.348 ms/op
     p(99.9999) =     22.348 ms/op
    p(100.0000) =     22.348 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.219 ±(99.9%) 0.069 ms/op
Iteration   1: 1.805 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.538 ms/op
                 existUser·p0.50:   1.702 ms/op
                 existUser·p0.90:   2.257 ms/op
                 existUser·p0.95:   2.366 ms/op
                 existUser·p0.99:   3.195 ms/op
                 existUser·p0.999:  17.990 ms/op
                 existUser·p0.9999: 18.610 ms/op
                 existUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17704
  mean =      1.805 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 589 
    [ 1.250,  2.500) = 16611 
    [ 2.500,  3.750) = 397 
    [ 3.750,  5.000) = 36 
    [ 5.000,  6.250) = 4 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.538 ms/op
     p(50.0000) =      1.702 ms/op
     p(90.0000) =      2.257 ms/op
     p(95.0000) =      2.366 ms/op
     p(99.0000) =      3.195 ms/op
     p(99.9000) =     17.990 ms/op
     p(99.9900) =     18.610 ms/op
     p(99.9990) =     18.711 ms/op
     p(99.9999) =     18.711 ms/op
    p(100.0000) =     18.711 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.316 ±(99.9%) 0.088 ms/op
Iteration   1: 2.001 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   0.606 ms/op
                 getUser·p0.50:   1.874 ms/op
                 getUser·p0.90:   2.482 ms/op
                 getUser·p0.95:   2.687 ms/op
                 getUser·p0.99:   3.338 ms/op
                 getUser·p0.999:  24.604 ms/op
                 getUser·p0.9999: 25.736 ms/op
                 getUser·p1.00:   25.854 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16007
  mean =      2.001 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14471 
    [ 2.500,  5.000) = 1485 
    [ 5.000,  7.500) = 19 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.606 ms/op
     p(50.0000) =      1.874 ms/op
     p(90.0000) =      2.482 ms/op
     p(95.0000) =      2.687 ms/op
     p(99.0000) =      3.338 ms/op
     p(99.9000) =     24.604 ms/op
     p(99.9900) =     25.736 ms/op
     p(99.9990) =     25.854 ms/op
     p(99.9999) =     25.854 ms/op
    p(100.0000) =     25.854 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.434 ±(99.9%) 0.127 ms/op
Iteration   1: 3.334 ±(99.9%) 0.045 ms/op
                 listUser·p0.00:   0.650 ms/op
                 listUser·p0.50:   3.219 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  21.378 ms/op
                 listUser·p0.9999: 22.381 ms/op
                 listUser·p1.00:   22.381 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9584
  mean =      3.334 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1633 
    [ 2.500,  5.000) = 7612 
    [ 5.000,  7.500) = 292 
    [ 7.500, 10.000) = 15 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.650 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      6.742 ms/op
     p(99.9000) =     21.378 ms/op
     p(99.9900) =     22.381 ms/op
     p(99.9990) =     22.381 ms/op
     p(99.9999) =     22.381 ms/op
    p(100.0000) =     22.381 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.926          ops/ms
ClientSimple.existUser                       thrpt         12.230          ops/ms
ClientSimple.getUser                         thrpt         13.880          ops/ms
ClientSimple.listUser                        thrpt          9.400          ops/ms
ClientSimple.createUser                       avgt          2.121           ms/op
ClientSimple.existUser                        avgt          1.860           ms/op
ClientSimple.getUser                          avgt          1.969           ms/op
ClientSimple.listUser                         avgt          3.369           ms/op
ClientSimple.createUser                     sample  14576   2.193 ± 0.036   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.553           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.071           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.544           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.777           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.258           ms/op
ClientSimple.createUser:createUser·p0.999   sample         22.086           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.333           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.348           ms/op
ClientSimple.existUser                      sample  17704   1.805 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.538           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.702           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.257           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.366           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.195           ms/op
ClientSimple.existUser:existUser·p0.999     sample         17.990           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.610           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.711           ms/op
ClientSimple.getUser                        sample  16007   2.001 ± 0.028   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.606           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.874           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.482           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.687           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.338           ms/op
ClientSimple.getUser:getUser·p0.999         sample         24.604           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         25.736           ms/op
ClientSimple.getUser:getUser·p1.00          sample         25.854           ms/op
ClientSimple.listUser                       sample   9584   3.334 ± 0.045   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.650           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.219           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.293           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.604           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.742           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.378           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         22.381           ms/op
ClientSimple.listUser:listUser·p1.00        sample         22.381           ms/op

Benchmark result is saved to 1713917709055.json
