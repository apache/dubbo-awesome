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
# Warmup Iteration   1: 1.754 ops/ms
Iteration   1: 7.483 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.483 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 6.783 ops/ms
Iteration   1: 13.429 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.429 ops/ms


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
# Warmup Iteration   1: 5.327 ops/ms
Iteration   1: 13.372 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.372 ops/ms


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
# Warmup Iteration   1: 5.309 ops/ms
Iteration   1: 8.164 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.164 ops/ms


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
# Warmup Iteration   1: 3.826 ±(99.9%) 0.065 ms/op
Iteration   1: 2.452 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.452 ms/op


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
# Warmup Iteration   1: 3.205 ±(99.9%) 0.047 ms/op
Iteration   1: 2.178 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.178 ms/op


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
# Warmup Iteration   1: 3.666 ±(99.9%) 0.069 ms/op
Iteration   1: 2.277 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.277 ms/op


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
# Warmup Iteration   1: 4.410 ±(99.9%) 0.093 ms/op
Iteration   1: 3.340 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.340 ms/op


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
# Warmup Iteration   1: 3.460 ±(99.9%) 0.074 ms/op
Iteration   1: 2.266 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   0.582 ms/op
                 createUser·p0.50:   2.126 ms/op
                 createUser·p0.90:   2.695 ms/op
                 createUser·p0.95:   2.884 ms/op
                 createUser·p0.99:   6.095 ms/op
                 createUser·p0.999:  23.655 ms/op
                 createUser·p0.9999: 24.241 ms/op
                 createUser·p1.00:   24.281 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14112
  mean =      2.266 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11347 
    [ 2.500,  5.000) = 2589 
    [ 5.000,  7.500) = 80 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.582 ms/op
     p(50.0000) =      2.126 ms/op
     p(90.0000) =      2.695 ms/op
     p(95.0000) =      2.884 ms/op
     p(99.0000) =      6.095 ms/op
     p(99.9000) =     23.655 ms/op
     p(99.9900) =     24.241 ms/op
     p(99.9990) =     24.281 ms/op
     p(99.9999) =     24.281 ms/op
    p(100.0000) =     24.281 ms/op


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
# Warmup Iteration   1: 2.931 ±(99.9%) 0.066 ms/op
Iteration   1: 1.793 ±(99.9%) 0.046 ms/op
                 existUser·p0.00:   0.675 ms/op
                 existUser·p0.50:   1.569 ms/op
                 existUser·p0.90:   2.101 ms/op
                 existUser·p0.95:   2.284 ms/op
                 existUser·p0.99:   3.132 ms/op
                 existUser·p0.999:  38.227 ms/op
                 existUser·p0.9999: 45.102 ms/op
                 existUser·p1.00:   45.154 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17985
  mean =      1.793 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 17839 
    [ 5.000, 10.000) = 36 
    [10.000, 15.000) = 24 
    [15.000, 20.000) = 49 
    [20.000, 25.000) = 8 
    [25.000, 30.000) = 5 
    [30.000, 35.000) = 6 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.675 ms/op
     p(50.0000) =      1.569 ms/op
     p(90.0000) =      2.101 ms/op
     p(95.0000) =      2.284 ms/op
     p(99.0000) =      3.132 ms/op
     p(99.9000) =     38.227 ms/op
     p(99.9900) =     45.102 ms/op
     p(99.9990) =     45.154 ms/op
     p(99.9999) =     45.154 ms/op
    p(100.0000) =     45.154 ms/op


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
# Warmup Iteration   1: 3.349 ±(99.9%) 0.092 ms/op
Iteration   1: 1.878 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.674 ms/op
                 getUser·p0.50:   1.796 ms/op
                 getUser·p0.90:   2.392 ms/op
                 getUser·p0.95:   2.560 ms/op
                 getUser·p0.99:   3.154 ms/op
                 getUser·p0.999:  12.057 ms/op
                 getUser·p0.9999: 12.353 ms/op
                 getUser·p1.00:   12.468 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17040
  mean =      1.878 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 655 
    [ 1.250,  2.500) = 15306 
    [ 2.500,  3.750) = 949 
    [ 3.750,  5.000) = 53 
    [ 5.000,  6.250) = 13 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 14 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.674 ms/op
     p(50.0000) =      1.796 ms/op
     p(90.0000) =      2.392 ms/op
     p(95.0000) =      2.560 ms/op
     p(99.0000) =      3.154 ms/op
     p(99.9000) =     12.057 ms/op
     p(99.9900) =     12.353 ms/op
     p(99.9990) =     12.468 ms/op
     p(99.9999) =     12.468 ms/op
    p(100.0000) =     12.468 ms/op


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
# Warmup Iteration   1: 4.658 ±(99.9%) 0.134 ms/op
Iteration   1: 3.569 ±(99.9%) 0.058 ms/op
                 listUser·p0.00:   0.595 ms/op
                 listUser·p0.50:   3.543 ms/op
                 listUser·p0.90:   4.170 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   6.447 ms/op
                 listUser·p0.999:  28.905 ms/op
                 listUser·p0.9999: 30.409 ms/op
                 listUser·p1.00:   30.409 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8971
  mean =      3.569 ±(99.9%) 0.058 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1029 
    [ 2.500,  5.000) = 7585 
    [ 5.000,  7.500) = 292 
    [ 7.500, 10.000) = 31 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.595 ms/op
     p(50.0000) =      3.543 ms/op
     p(90.0000) =      4.170 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      6.447 ms/op
     p(99.9000) =     28.905 ms/op
     p(99.9900) =     30.409 ms/op
     p(99.9990) =     30.409 ms/op
     p(99.9999) =     30.409 ms/op
    p(100.0000) =     30.409 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.483          ops/ms
ClientSimple.existUser                       thrpt         13.429          ops/ms
ClientSimple.getUser                         thrpt         13.372          ops/ms
ClientSimple.listUser                        thrpt          8.164          ops/ms
ClientSimple.createUser                       avgt          2.452           ms/op
ClientSimple.existUser                        avgt          2.178           ms/op
ClientSimple.getUser                          avgt          2.277           ms/op
ClientSimple.listUser                         avgt          3.340           ms/op
ClientSimple.createUser                     sample  14112   2.266 ± 0.040   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.582           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.126           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.695           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.884           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.095           ms/op
ClientSimple.createUser:createUser·p0.999   sample         23.655           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         24.241           ms/op
ClientSimple.createUser:createUser·p1.00    sample         24.281           ms/op
ClientSimple.existUser                      sample  17985   1.793 ± 0.046   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.675           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.569           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.101           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.284           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.132           ms/op
ClientSimple.existUser:existUser·p0.999     sample         38.227           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         45.102           ms/op
ClientSimple.existUser:existUser·p1.00      sample         45.154           ms/op
ClientSimple.getUser                        sample  17040   1.878 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.674           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.796           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.392           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.560           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.154           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.057           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.353           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.468           ms/op
ClientSimple.listUser                       sample   8971   3.569 ± 0.058   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.595           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.543           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.170           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.604           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.447           ms/op
ClientSimple.listUser:listUser·p0.999       sample         28.905           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         30.409           ms/op
ClientSimple.listUser:listUser·p1.00        sample         30.409           ms/op

Benchmark result is saved to 1723810025776.json
