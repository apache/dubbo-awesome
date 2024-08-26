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
# Warmup Iteration   1: 1.757 ops/ms
Iteration   1: 7.226 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.226 ops/ms


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
# Warmup Iteration   1: 5.140 ops/ms
Iteration   1: 12.082 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.082 ops/ms


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
# Warmup Iteration   1: 5.259 ops/ms
Iteration   1: 13.872 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.872 ops/ms


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
# Warmup Iteration   1: 4.639 ops/ms
Iteration   1: 8.594 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.594 ops/ms


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
# Warmup Iteration   1: 4.019 ±(99.9%) 0.068 ms/op
Iteration   1: 2.051 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.051 ms/op


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
# Warmup Iteration   1: 3.079 ±(99.9%) 0.052 ms/op
Iteration   1: 1.910 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.910 ms/op


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
# Warmup Iteration   1: 3.136 ±(99.9%) 0.056 ms/op
Iteration   1: 2.157 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.157 ms/op


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
# Warmup Iteration   1: 4.860 ±(99.9%) 0.091 ms/op
Iteration   1: 3.352 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.352 ms/op


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
# Warmup Iteration   1: 3.577 ±(99.9%) 0.113 ms/op
Iteration   1: 2.104 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.868 ms/op
                 createUser·p0.50:   1.855 ms/op
                 createUser·p0.90:   2.585 ms/op
                 createUser·p0.95:   2.855 ms/op
                 createUser·p0.99:   5.770 ms/op
                 createUser·p0.999:  15.233 ms/op
                 createUser·p0.9999: 16.539 ms/op
                 createUser·p1.00:   16.876 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15269
  mean =      2.104 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 13315 
    [ 2.500,  3.750) = 1602 
    [ 3.750,  5.000) = 80 
    [ 5.000,  6.250) = 77 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 34 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.868 ms/op
     p(50.0000) =      1.855 ms/op
     p(90.0000) =      2.585 ms/op
     p(95.0000) =      2.855 ms/op
     p(99.0000) =      5.770 ms/op
     p(99.9000) =     15.233 ms/op
     p(99.9900) =     16.539 ms/op
     p(99.9990) =     16.876 ms/op
     p(99.9999) =     16.876 ms/op
    p(100.0000) =     16.876 ms/op


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
# Warmup Iteration   1: 2.758 ±(99.9%) 0.069 ms/op
Iteration   1: 1.721 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.553 ms/op
                 existUser·p0.50:   1.606 ms/op
                 existUser·p0.90:   2.114 ms/op
                 existUser·p0.95:   2.257 ms/op
                 existUser·p0.99:   2.971 ms/op
                 existUser·p0.999:  11.747 ms/op
                 existUser·p0.9999: 13.675 ms/op
                 existUser·p1.00:   15.204 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18565
  mean =      1.721 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 681 
    [ 1.250,  2.500) = 17482 
    [ 2.500,  3.750) = 270 
    [ 3.750,  5.000) = 57 
    [ 5.000,  6.250) = 11 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 21 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.553 ms/op
     p(50.0000) =      1.606 ms/op
     p(90.0000) =      2.114 ms/op
     p(95.0000) =      2.257 ms/op
     p(99.0000) =      2.971 ms/op
     p(99.9000) =     11.747 ms/op
     p(99.9900) =     13.675 ms/op
     p(99.9990) =     15.204 ms/op
     p(99.9999) =     15.204 ms/op
    p(100.0000) =     15.204 ms/op


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
# Warmup Iteration   1: 3.290 ±(99.9%) 0.087 ms/op
Iteration   1: 2.002 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.386 ms/op
                 getUser·p0.50:   1.876 ms/op
                 getUser·p0.90:   2.417 ms/op
                 getUser·p0.95:   2.650 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  17.859 ms/op
                 getUser·p0.9999: 18.232 ms/op
                 getUser·p1.00:   18.252 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15941
  mean =      2.002 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 89 
    [ 1.250,  2.500) = 14644 
    [ 2.500,  3.750) = 1041 
    [ 3.750,  5.000) = 100 
    [ 5.000,  6.250) = 30 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.386 ms/op
     p(50.0000) =      1.876 ms/op
     p(90.0000) =      2.417 ms/op
     p(95.0000) =      2.650 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =     17.859 ms/op
     p(99.9900) =     18.232 ms/op
     p(99.9990) =     18.252 ms/op
     p(99.9999) =     18.252 ms/op
    p(100.0000) =     18.252 ms/op


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
# Warmup Iteration   1: 4.689 ±(99.9%) 0.153 ms/op
Iteration   1: 3.621 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.033 ms/op
                 listUser·p0.50:   3.621 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   5.886 ms/op
                 listUser·p0.999:  10.174 ms/op
                 listUser·p0.9999: 10.371 ms/op
                 listUser·p1.00:   10.371 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8844
  mean =      3.621 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 49 
    [ 2.000,  3.000) = 1591 
    [ 3.000,  4.000) = 5033 
    [ 4.000,  5.000) = 1972 
    [ 5.000,  6.000) = 120 
    [ 6.000,  7.000) = 25 
    [ 7.000,  8.000) = 19 
    [ 8.000,  9.000) = 3 
    [ 9.000, 10.000) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.033 ms/op
     p(50.0000) =      3.621 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      5.886 ms/op
     p(99.9000) =     10.174 ms/op
     p(99.9900) =     10.371 ms/op
     p(99.9990) =     10.371 ms/op
     p(99.9999) =     10.371 ms/op
    p(100.0000) =     10.371 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.226          ops/ms
ClientSimple.existUser                       thrpt         12.082          ops/ms
ClientSimple.getUser                         thrpt         13.872          ops/ms
ClientSimple.listUser                        thrpt          8.594          ops/ms
ClientSimple.createUser                       avgt          2.051           ms/op
ClientSimple.existUser                        avgt          1.910           ms/op
ClientSimple.getUser                          avgt          2.157           ms/op
ClientSimple.listUser                         avgt          3.352           ms/op
ClientSimple.createUser                     sample  15269   2.104 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.868           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.855           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.585           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.855           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.770           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.233           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.539           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.876           ms/op
ClientSimple.existUser                      sample  18565   1.721 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.553           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.606           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.114           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.257           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.971           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.747           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.675           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.204           ms/op
ClientSimple.getUser                        sample  15941   2.002 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.386           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.876           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.417           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.650           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.456           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.859           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.232           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.252           ms/op
ClientSimple.listUser                       sample   8844   3.621 ± 0.027   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.033           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.621           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.334           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.653           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.886           ms/op
ClientSimple.listUser:listUser·p0.999       sample         10.174           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.371           ms/op
ClientSimple.listUser:listUser·p1.00        sample         10.371           ms/op

Benchmark result is saved to 1724674036406.json
