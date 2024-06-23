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
# Warmup Iteration   1: 2.055 ops/ms
Iteration   1: 7.231 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.231 ops/ms


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
# Warmup Iteration   1: 5.741 ops/ms
Iteration   1: 11.710 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.710 ops/ms


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
# Warmup Iteration   1: 5.333 ops/ms
Iteration   1: 12.073 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.073 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.175 ops/ms
Iteration   1: 9.070 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.070 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.667 ±(99.9%) 0.051 ms/op
Iteration   1: 2.079 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.079 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.030 ±(99.9%) 0.042 ms/op
Iteration   1: 1.676 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.676 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.595 ±(99.9%) 0.064 ms/op
Iteration   1: 1.995 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.995 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.655 ±(99.9%) 0.089 ms/op
Iteration   1: 3.287 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.287 ms/op


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
# Warmup Iteration   1: 3.485 ±(99.9%) 0.084 ms/op
Iteration   1: 2.185 ±(99.9%) 0.042 ms/op
                 createUser·p0.00:   0.766 ms/op
                 createUser·p0.50:   1.964 ms/op
                 createUser·p0.90:   2.511 ms/op
                 createUser·p0.95:   2.809 ms/op
                 createUser·p0.99:   8.231 ms/op
                 createUser·p0.999:  25.518 ms/op
                 createUser·p0.9999: 27.464 ms/op
                 createUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14624
  mean =      2.185 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13112 
    [ 2.500,  5.000) = 1311 
    [ 5.000,  7.500) = 39 
    [ 7.500, 10.000) = 66 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.766 ms/op
     p(50.0000) =      1.964 ms/op
     p(90.0000) =      2.511 ms/op
     p(95.0000) =      2.809 ms/op
     p(99.0000) =      8.231 ms/op
     p(99.9000) =     25.518 ms/op
     p(99.9900) =     27.464 ms/op
     p(99.9990) =     27.525 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.098 ±(99.9%) 0.086 ms/op
Iteration   1: 1.954 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.524 ms/op
                 existUser·p0.50:   1.878 ms/op
                 existUser·p0.90:   2.396 ms/op
                 existUser·p0.95:   2.568 ms/op
                 existUser·p0.99:   3.274 ms/op
                 existUser·p0.999:  12.113 ms/op
                 existUser·p0.9999: 13.201 ms/op
                 existUser·p1.00:   13.222 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16465
  mean =      1.954 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 225 
    [ 1.250,  2.500) = 15139 
    [ 2.500,  3.750) = 996 
    [ 3.750,  5.000) = 45 
    [ 5.000,  6.250) = 19 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.524 ms/op
     p(50.0000) =      1.878 ms/op
     p(90.0000) =      2.396 ms/op
     p(95.0000) =      2.568 ms/op
     p(99.0000) =      3.274 ms/op
     p(99.9000) =     12.113 ms/op
     p(99.9900) =     13.201 ms/op
     p(99.9990) =     13.222 ms/op
     p(99.9999) =     13.222 ms/op
    p(100.0000) =     13.222 ms/op


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
# Warmup Iteration   1: 3.142 ±(99.9%) 0.083 ms/op
Iteration   1: 1.846 ±(99.9%) 0.030 ms/op
                 getUser·p0.00:   0.294 ms/op
                 getUser·p0.50:   1.692 ms/op
                 getUser·p0.90:   2.408 ms/op
                 getUser·p0.95:   2.605 ms/op
                 getUser·p0.99:   3.219 ms/op
                 getUser·p0.999:  25.494 ms/op
                 getUser·p0.9999: 26.226 ms/op
                 getUser·p1.00:   26.345 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17306
  mean =      1.846 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16052 
    [ 2.500,  5.000) = 1181 
    [ 5.000,  7.500) = 9 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.294 ms/op
     p(50.0000) =      1.692 ms/op
     p(90.0000) =      2.408 ms/op
     p(95.0000) =      2.605 ms/op
     p(99.0000) =      3.219 ms/op
     p(99.9000) =     25.494 ms/op
     p(99.9900) =     26.226 ms/op
     p(99.9990) =     26.345 ms/op
     p(99.9999) =     26.345 ms/op
    p(100.0000) =     26.345 ms/op


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
# Warmup Iteration   1: 4.223 ±(99.9%) 0.110 ms/op
Iteration   1: 3.123 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   1.037 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   4.047 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   6.249 ms/op
                 listUser·p0.999:  11.174 ms/op
                 listUser·p0.9999: 11.337 ms/op
                 listUser·p1.00:   11.338 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10260
  mean =      3.123 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 2573 
    [ 2.500,  3.750) = 5681 
    [ 3.750,  5.000) = 1875 
    [ 5.000,  6.250) = 27 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.037 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      4.047 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      6.249 ms/op
     p(99.9000) =     11.174 ms/op
     p(99.9900) =     11.337 ms/op
     p(99.9990) =     11.338 ms/op
     p(99.9999) =     11.338 ms/op
    p(100.0000) =     11.338 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.231          ops/ms
ClientSimple.existUser                       thrpt         11.710          ops/ms
ClientSimple.getUser                         thrpt         12.073          ops/ms
ClientSimple.listUser                        thrpt          9.070          ops/ms
ClientSimple.createUser                       avgt          2.079           ms/op
ClientSimple.existUser                        avgt          1.676           ms/op
ClientSimple.getUser                          avgt          1.995           ms/op
ClientSimple.listUser                         avgt          3.287           ms/op
ClientSimple.createUser                     sample  14624   2.185 ± 0.042   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.766           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.964           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.511           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.809           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.231           ms/op
ClientSimple.createUser:createUser·p0.999   sample         25.518           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         27.464           ms/op
ClientSimple.createUser:createUser·p1.00    sample         27.525           ms/op
ClientSimple.existUser                      sample  16465   1.954 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.524           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.878           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.396           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.568           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.274           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.113           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.201           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.222           ms/op
ClientSimple.getUser                        sample  17306   1.846 ± 0.030   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.294           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.692           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.408           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.605           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.219           ms/op
ClientSimple.getUser:getUser·p0.999         sample         25.494           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         26.226           ms/op
ClientSimple.getUser:getUser·p1.00          sample         26.345           ms/op
ClientSimple.listUser                       sample  10260   3.123 ± 0.032   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.037           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.892           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.047           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.276           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.249           ms/op
ClientSimple.listUser:listUser·p0.999       sample         11.174           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         11.337           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.338           ms/op

Benchmark result is saved to 1719101838464.json
