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
# Warmup Iteration   1: 1.934 ops/ms
Iteration   1: 6.790 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.790 ops/ms


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
# Warmup Iteration   1: 6.538 ops/ms
Iteration   1: 15.289 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  15.289 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.286 ops/ms
Iteration   1: 12.291 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.291 ops/ms


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
# Warmup Iteration   1: 5.833 ops/ms
Iteration   1: 9.637 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.637 ops/ms


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
# Warmup Iteration   1: 3.879 ±(99.9%) 0.059 ms/op
Iteration   1: 2.334 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.334 ms/op


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
# Warmup Iteration   1: 2.984 ±(99.9%) 0.053 ms/op
Iteration   1: 1.780 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.780 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.096 ±(99.9%) 0.059 ms/op
Iteration   1: 1.945 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.945 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.394 ±(99.9%) 0.122 ms/op
Iteration   1: 3.260 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.260 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.201 ±(99.9%) 0.078 ms/op
Iteration   1: 2.184 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.517 ms/op
                 createUser·p0.50:   2.097 ms/op
                 createUser·p0.90:   2.560 ms/op
                 createUser·p0.95:   2.781 ms/op
                 createUser·p0.99:   6.046 ms/op
                 createUser·p0.999:  15.548 ms/op
                 createUser·p0.9999: 21.415 ms/op
                 createUser·p1.00:   21.430 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14700
  mean =      2.184 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12711 
    [ 2.500,  5.000) = 1799 
    [ 5.000,  7.500) = 67 
    [ 7.500, 10.000) = 27 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.517 ms/op
     p(50.0000) =      2.097 ms/op
     p(90.0000) =      2.560 ms/op
     p(95.0000) =      2.781 ms/op
     p(99.0000) =      6.046 ms/op
     p(99.9000) =     15.548 ms/op
     p(99.9900) =     21.415 ms/op
     p(99.9990) =     21.430 ms/op
     p(99.9999) =     21.430 ms/op
    p(100.0000) =     21.430 ms/op


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
# Warmup Iteration   1: 2.955 ±(99.9%) 0.074 ms/op
Iteration   1: 1.845 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   0.511 ms/op
                 existUser·p0.50:   1.698 ms/op
                 existUser·p0.90:   2.187 ms/op
                 existUser·p0.95:   2.335 ms/op
                 existUser·p0.99:   2.884 ms/op
                 existUser·p0.999:  25.559 ms/op
                 existUser·p0.9999: 25.972 ms/op
                 existUser·p1.00:   26.116 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17327
  mean =      1.845 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16903 
    [ 2.500,  5.000) = 301 
    [ 5.000,  7.500) = 26 
    [ 7.500, 10.000) = 15 
    [10.000, 12.500) = 18 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.511 ms/op
     p(50.0000) =      1.698 ms/op
     p(90.0000) =      2.187 ms/op
     p(95.0000) =      2.335 ms/op
     p(99.0000) =      2.884 ms/op
     p(99.9000) =     25.559 ms/op
     p(99.9900) =     25.972 ms/op
     p(99.9990) =     26.116 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


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
# Warmup Iteration   1: 3.359 ±(99.9%) 0.098 ms/op
Iteration   1: 2.014 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.555 ms/op
                 getUser·p0.50:   1.915 ms/op
                 getUser·p0.90:   2.621 ms/op
                 getUser·p0.95:   2.896 ms/op
                 getUser·p0.99:   3.555 ms/op
                 getUser·p0.999:  11.484 ms/op
                 getUser·p0.9999: 11.920 ms/op
                 getUser·p1.00:   12.059 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16057
  mean =      2.014 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 251 
    [ 1.250,  2.500) = 13620 
    [ 2.500,  3.750) = 2064 
    [ 3.750,  5.000) = 89 
    [ 5.000,  6.250) = 1 
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
      p(0.0000) =      0.555 ms/op
     p(50.0000) =      1.915 ms/op
     p(90.0000) =      2.621 ms/op
     p(95.0000) =      2.896 ms/op
     p(99.0000) =      3.555 ms/op
     p(99.9000) =     11.484 ms/op
     p(99.9900) =     11.920 ms/op
     p(99.9990) =     12.059 ms/op
     p(99.9999) =     12.059 ms/op
    p(100.0000) =     12.059 ms/op


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
# Warmup Iteration   1: 4.522 ±(99.9%) 0.123 ms/op
Iteration   1: 3.007 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   0.911 ms/op
                 listUser·p0.50:   2.798 ms/op
                 listUser·p0.90:   3.813 ms/op
                 listUser·p0.95:   4.166 ms/op
                 listUser·p0.99:   4.979 ms/op
                 listUser·p0.999:  18.473 ms/op
                 listUser·p0.9999: 19.364 ms/op
                 listUser·p1.00:   19.366 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10617
  mean =      3.007 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 636 
    [ 2.500,  3.750) = 8841 
    [ 3.750,  5.000) = 1036 
    [ 5.000,  6.250) = 52 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.911 ms/op
     p(50.0000) =      2.798 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      4.166 ms/op
     p(99.0000) =      4.979 ms/op
     p(99.9000) =     18.473 ms/op
     p(99.9900) =     19.364 ms/op
     p(99.9990) =     19.366 ms/op
     p(99.9999) =     19.366 ms/op
    p(100.0000) =     19.366 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.790          ops/ms
ClientSimple.existUser                       thrpt         15.289          ops/ms
ClientSimple.getUser                         thrpt         12.291          ops/ms
ClientSimple.listUser                        thrpt          9.637          ops/ms
ClientSimple.createUser                       avgt          2.334           ms/op
ClientSimple.existUser                        avgt          1.780           ms/op
ClientSimple.getUser                          avgt          1.945           ms/op
ClientSimple.listUser                         avgt          3.260           ms/op
ClientSimple.createUser                     sample  14700   2.184 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.517           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.097           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.560           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.781           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.046           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.548           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.415           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.430           ms/op
ClientSimple.existUser                      sample  17327   1.845 ± 0.031   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.511           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.698           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.187           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.335           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.884           ms/op
ClientSimple.existUser:existUser·p0.999     sample         25.559           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         25.972           ms/op
ClientSimple.existUser:existUser·p1.00      sample         26.116           ms/op
ClientSimple.getUser                        sample  16057   2.014 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.555           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.915           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.621           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.896           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.555           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.484           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.920           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.059           ms/op
ClientSimple.listUser                       sample  10617   3.007 ± 0.032   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.911           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.798           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.813           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.166           ms/op
ClientSimple.listUser:listUser·p0.99        sample          4.979           ms/op
ClientSimple.listUser:listUser·p0.999       sample         18.473           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.364           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.366           ms/op

Benchmark result is saved to 1722773166342.json
