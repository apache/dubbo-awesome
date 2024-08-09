# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.636 ops/ms
Iteration   1: 6.520 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.520 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.833 ops/ms
Iteration   1: 12.546 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.546 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.731 ops/ms
Iteration   1: 13.225 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.225 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.174 ops/ms
Iteration   1: 8.410 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.410 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.734 ±(99.9%) 0.102 ms/op
Iteration   1: 2.170 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.170 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.022 ±(99.9%) 0.049 ms/op
Iteration   1: 1.994 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.994 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.327 ±(99.9%) 0.056 ms/op
Iteration   1: 2.523 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.523 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 5.180 ±(99.9%) 0.118 ms/op
Iteration   1: 3.731 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.731 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.655 ±(99.9%) 0.097 ms/op
Iteration   1: 2.178 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.494 ms/op
                 createUser·p0.50:   2.015 ms/op
                 createUser·p0.90:   2.609 ms/op
                 createUser·p0.95:   2.875 ms/op
                 createUser·p0.99:   5.718 ms/op
                 createUser·p0.999:  21.266 ms/op
                 createUser·p0.9999: 22.708 ms/op
                 createUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14670
  mean =      2.178 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12676 
    [ 2.500,  5.000) = 1832 
    [ 5.000,  7.500) = 66 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.494 ms/op
     p(50.0000) =      2.015 ms/op
     p(90.0000) =      2.609 ms/op
     p(95.0000) =      2.875 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =     21.266 ms/op
     p(99.9900) =     22.708 ms/op
     p(99.9990) =     22.938 ms/op
     p(99.9999) =     22.938 ms/op
    p(100.0000) =     22.938 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.934 ±(99.9%) 0.068 ms/op
Iteration   1: 1.856 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.544 ms/op
                 existUser·p0.50:   1.706 ms/op
                 existUser·p0.90:   2.380 ms/op
                 existUser·p0.95:   2.601 ms/op
                 existUser·p0.99:   3.448 ms/op
                 existUser·p0.999:  11.395 ms/op
                 existUser·p0.9999: 11.986 ms/op
                 existUser·p1.00:   12.141 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17240
  mean =      1.856 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 130 
    [ 1.250,  2.500) = 15891 
    [ 2.500,  3.750) = 1086 
    [ 3.750,  5.000) = 24 
    [ 5.000,  6.250) = 77 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.544 ms/op
     p(50.0000) =      1.706 ms/op
     p(90.0000) =      2.380 ms/op
     p(95.0000) =      2.601 ms/op
     p(99.0000) =      3.448 ms/op
     p(99.9000) =     11.395 ms/op
     p(99.9900) =     11.986 ms/op
     p(99.9990) =     12.141 ms/op
     p(99.9999) =     12.141 ms/op
    p(100.0000) =     12.141 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.290 ±(99.9%) 0.084 ms/op
Iteration   1: 1.968 ±(99.9%) 0.036 ms/op
                 getUser·p0.00:   0.665 ms/op
                 getUser·p0.50:   1.827 ms/op
                 getUser·p0.90:   2.376 ms/op
                 getUser·p0.95:   2.608 ms/op
                 getUser·p0.99:   3.223 ms/op
                 getUser·p0.999:  28.508 ms/op
                 getUser·p0.9999: 29.028 ms/op
                 getUser·p1.00:   29.524 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16305
  mean =      1.968 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15130 
    [ 2.500,  5.000) = 1104 
    [ 5.000,  7.500) = 6 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.665 ms/op
     p(50.0000) =      1.827 ms/op
     p(90.0000) =      2.376 ms/op
     p(95.0000) =      2.608 ms/op
     p(99.0000) =      3.223 ms/op
     p(99.9000) =     28.508 ms/op
     p(99.9900) =     29.028 ms/op
     p(99.9990) =     29.524 ms/op
     p(99.9999) =     29.524 ms/op
    p(100.0000) =     29.524 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.737 ±(99.9%) 0.151 ms/op
Iteration   1: 3.384 ±(99.9%) 0.045 ms/op
                 listUser·p0.00:   0.903 ms/op
                 listUser·p0.50:   3.394 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   7.197 ms/op
                 listUser·p0.999:  19.417 ms/op
                 listUser·p0.9999: 21.594 ms/op
                 listUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9448
  mean =      3.384 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2470 
    [ 2.500,  5.000) = 6716 
    [ 5.000,  7.500) = 180 
    [ 7.500, 10.000) = 50 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.903 ms/op
     p(50.0000) =      3.394 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      7.197 ms/op
     p(99.9000) =     19.417 ms/op
     p(99.9900) =     21.594 ms/op
     p(99.9990) =     21.594 ms/op
     p(99.9999) =     21.594 ms/op
    p(100.0000) =     21.594 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.520          ops/ms
ClientSimple.existUser                       thrpt         12.546          ops/ms
ClientSimple.getUser                         thrpt         13.225          ops/ms
ClientSimple.listUser                        thrpt          8.410          ops/ms
ClientSimple.createUser                       avgt          2.170           ms/op
ClientSimple.existUser                        avgt          1.994           ms/op
ClientSimple.getUser                          avgt          2.523           ms/op
ClientSimple.listUser                         avgt          3.731           ms/op
ClientSimple.createUser                     sample  14670   2.178 ± 0.037   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.494           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.015           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.609           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.875           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.718           ms/op
ClientSimple.createUser:createUser·p0.999   sample         21.266           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.708           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.938           ms/op
ClientSimple.existUser                      sample  17240   1.856 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.544           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.706           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.380           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.601           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.448           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.395           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.986           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.141           ms/op
ClientSimple.getUser                        sample  16305   1.968 ± 0.036   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.665           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.827           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.376           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.608           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.223           ms/op
ClientSimple.getUser:getUser·p0.999         sample         28.508           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         29.028           ms/op
ClientSimple.getUser:getUser·p1.00          sample         29.524           ms/op
ClientSimple.listUser                       sample   9448   3.384 ± 0.045   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.903           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.394           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.260           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.522           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.197           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.417           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.594           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.594           ms/op

Benchmark result is saved to 1723226741035.json
