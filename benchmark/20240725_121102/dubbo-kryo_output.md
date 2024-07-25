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
# Warmup Iteration   1: 2.090 ops/ms
Iteration   1: 6.668 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.668 ops/ms


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
# Warmup Iteration   1: 5.695 ops/ms
Iteration   1: 12.242 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.242 ops/ms


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
# Warmup Iteration   1: 6.167 ops/ms
Iteration   1: 12.826 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.826 ops/ms


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
# Warmup Iteration   1: 5.133 ops/ms
Iteration   1: 7.883 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.883 ops/ms


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
# Warmup Iteration   1: 3.900 ±(99.9%) 0.078 ms/op
Iteration   1: 1.974 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.974 ms/op


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
# Warmup Iteration   1: 3.425 ±(99.9%) 0.053 ms/op
Iteration   1: 1.907 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.907 ms/op


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
# Warmup Iteration   1: 3.532 ±(99.9%) 0.057 ms/op
Iteration   1: 1.959 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.959 ms/op


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
# Warmup Iteration   1: 4.718 ±(99.9%) 0.079 ms/op
Iteration   1: 3.500 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.500 ms/op


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
# Warmup Iteration   1: 3.121 ±(99.9%) 0.081 ms/op
Iteration   1: 2.185 ±(99.9%) 0.052 ms/op
                 createUser·p0.00:   0.599 ms/op
                 createUser·p0.50:   1.923 ms/op
                 createUser·p0.90:   2.380 ms/op
                 createUser·p0.95:   2.662 ms/op
                 createUser·p0.99:   11.076 ms/op
                 createUser·p0.999:  33.042 ms/op
                 createUser·p0.9999: 33.549 ms/op
                 createUser·p1.00:   33.686 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14641
  mean =      2.185 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13720 
    [ 2.500,  5.000) = 623 
    [ 5.000,  7.500) = 89 
    [ 7.500, 10.000) = 12 
    [10.000, 12.500) = 125 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.599 ms/op
     p(50.0000) =      1.923 ms/op
     p(90.0000) =      2.380 ms/op
     p(95.0000) =      2.662 ms/op
     p(99.0000) =     11.076 ms/op
     p(99.9000) =     33.042 ms/op
     p(99.9900) =     33.549 ms/op
     p(99.9990) =     33.686 ms/op
     p(99.9999) =     33.686 ms/op
    p(100.0000) =     33.686 ms/op


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
# Warmup Iteration   1: 2.822 ±(99.9%) 0.063 ms/op
Iteration   1: 1.949 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.558 ms/op
                 existUser·p0.50:   1.833 ms/op
                 existUser·p0.90:   2.478 ms/op
                 existUser·p0.95:   2.646 ms/op
                 existUser·p0.99:   3.162 ms/op
                 existUser·p0.999:  21.234 ms/op
                 existUser·p0.9999: 22.146 ms/op
                 existUser·p1.00:   22.381 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16500
  mean =      1.949 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14993 
    [ 2.500,  5.000) = 1443 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.558 ms/op
     p(50.0000) =      1.833 ms/op
     p(90.0000) =      2.478 ms/op
     p(95.0000) =      2.646 ms/op
     p(99.0000) =      3.162 ms/op
     p(99.9000) =     21.234 ms/op
     p(99.9900) =     22.146 ms/op
     p(99.9990) =     22.381 ms/op
     p(99.9999) =     22.381 ms/op
    p(100.0000) =     22.381 ms/op


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
# Warmup Iteration   1: 3.072 ±(99.9%) 0.074 ms/op
Iteration   1: 2.148 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.395 ms/op
                 getUser·p0.50:   2.097 ms/op
                 getUser·p0.90:   2.580 ms/op
                 getUser·p0.95:   2.732 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  14.221 ms/op
                 getUser·p0.9999: 14.418 ms/op
                 getUser·p1.00:   14.418 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14840
  mean =      2.148 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 218 
    [ 1.250,  2.500) = 12368 
    [ 2.500,  3.750) = 2055 
    [ 3.750,  5.000) = 101 
    [ 5.000,  6.250) = 34 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.395 ms/op
     p(50.0000) =      2.097 ms/op
     p(90.0000) =      2.580 ms/op
     p(95.0000) =      2.732 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =     14.221 ms/op
     p(99.9900) =     14.418 ms/op
     p(99.9990) =     14.418 ms/op
     p(99.9999) =     14.418 ms/op
    p(100.0000) =     14.418 ms/op


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
# Warmup Iteration   1: 4.436 ±(99.9%) 0.135 ms/op
Iteration   1: 3.548 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   0.714 ms/op
                 listUser·p0.50:   3.604 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.784 ms/op
                 listUser·p0.99:   5.947 ms/op
                 listUser·p0.999:  7.527 ms/op
                 listUser·p0.9999: 7.741 ms/op
                 listUser·p1.00:   7.741 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9019
  mean =      3.548 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 2 
    [1.000, 1.500) = 3 
    [1.500, 2.000) = 87 
    [2.000, 2.500) = 987 
    [2.500, 3.000) = 1150 
    [3.000, 3.500) = 1738 
    [3.500, 4.000) = 2795 
    [4.000, 4.500) = 1409 
    [4.500, 5.000) = 531 
    [5.000, 5.500) = 167 
    [5.500, 6.000) = 67 
    [6.000, 6.500) = 40 
    [6.500, 7.000) = 27 
    [7.000, 7.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.714 ms/op
     p(50.0000) =      3.604 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.784 ms/op
     p(99.0000) =      5.947 ms/op
     p(99.9000) =      7.527 ms/op
     p(99.9900) =      7.741 ms/op
     p(99.9990) =      7.741 ms/op
     p(99.9999) =      7.741 ms/op
    p(100.0000) =      7.741 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.668          ops/ms
ClientSimple.existUser                       thrpt         12.242          ops/ms
ClientSimple.getUser                         thrpt         12.826          ops/ms
ClientSimple.listUser                        thrpt          7.883          ops/ms
ClientSimple.createUser                       avgt          1.974           ms/op
ClientSimple.existUser                        avgt          1.907           ms/op
ClientSimple.getUser                          avgt          1.959           ms/op
ClientSimple.listUser                         avgt          3.500           ms/op
ClientSimple.createUser                     sample  14641   2.185 ± 0.052   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.599           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.923           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.380           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.662           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.076           ms/op
ClientSimple.createUser:createUser·p0.999   sample         33.042           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         33.549           ms/op
ClientSimple.createUser:createUser·p1.00    sample         33.686           ms/op
ClientSimple.existUser                      sample  16500   1.949 ± 0.027   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.558           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.833           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.478           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.646           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.162           ms/op
ClientSimple.existUser:existUser·p0.999     sample         21.234           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         22.146           ms/op
ClientSimple.existUser:existUser·p1.00      sample         22.381           ms/op
ClientSimple.getUser                        sample  14840   2.148 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.395           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.097           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.580           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.732           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.243           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.221           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.418           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.418           ms/op
ClientSimple.listUser                       sample   9019   3.548 ± 0.028   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.714           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.604           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.456           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.784           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.947           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.527           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.741           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.741           ms/op

Benchmark result is saved to 1721909224951.json
