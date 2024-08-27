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
# Warmup Iteration   1: 1.865 ops/ms
Iteration   1: 7.244 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.244 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.249 ops/ms
Iteration   1: 12.830 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.830 ops/ms


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
# Warmup Iteration   1: 5.965 ops/ms
Iteration   1: 13.959 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.959 ops/ms


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
# Warmup Iteration   1: 6.069 ops/ms
Iteration   1: 9.099 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.099 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.416 ±(99.9%) 0.059 ms/op
Iteration   1: 2.259 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.259 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.896 ±(99.9%) 0.053 ms/op
Iteration   1: 2.058 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.058 ms/op


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
# Warmup Iteration   1: 3.056 ±(99.9%) 0.053 ms/op
Iteration   1: 1.861 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.861 ms/op


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
# Warmup Iteration   1: 4.315 ±(99.9%) 0.085 ms/op
Iteration   1: 3.087 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.087 ms/op


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
# Warmup Iteration   1: 3.978 ±(99.9%) 0.090 ms/op
Iteration   1: 2.197 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   0.441 ms/op
                 createUser·p0.50:   2.114 ms/op
                 createUser·p0.90:   2.687 ms/op
                 createUser·p0.95:   3.068 ms/op
                 createUser·p0.99:   5.825 ms/op
                 createUser·p0.999:  15.171 ms/op
                 createUser·p0.9999: 17.105 ms/op
                 createUser·p1.00:   17.105 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14606
  mean =      2.197 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 84 
    [ 1.250,  2.500) = 12117 
    [ 2.500,  3.750) = 2138 
    [ 3.750,  5.000) = 62 
    [ 5.000,  6.250) = 86 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.441 ms/op
     p(50.0000) =      2.114 ms/op
     p(90.0000) =      2.687 ms/op
     p(95.0000) =      3.068 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =     15.171 ms/op
     p(99.9900) =     17.105 ms/op
     p(99.9990) =     17.105 ms/op
     p(99.9999) =     17.105 ms/op
    p(100.0000) =     17.105 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.902 ±(99.9%) 0.081 ms/op
Iteration   1: 1.804 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.425 ms/op
                 existUser·p0.50:   1.743 ms/op
                 existUser·p0.90:   2.150 ms/op
                 existUser·p0.95:   2.359 ms/op
                 existUser·p0.99:   3.607 ms/op
                 existUser·p0.999:  10.408 ms/op
                 existUser·p0.9999: 10.960 ms/op
                 existUser·p1.00:   11.239 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17741
  mean =      1.804 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 503 
    [ 1.250,  2.500) = 16701 
    [ 2.500,  3.750) = 397 
    [ 3.750,  5.000) = 75 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.425 ms/op
     p(50.0000) =      1.743 ms/op
     p(90.0000) =      2.150 ms/op
     p(95.0000) =      2.359 ms/op
     p(99.0000) =      3.607 ms/op
     p(99.9000) =     10.408 ms/op
     p(99.9900) =     10.960 ms/op
     p(99.9990) =     11.239 ms/op
     p(99.9999) =     11.239 ms/op
    p(100.0000) =     11.239 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 3.161 ±(99.9%) 0.073 ms/op
Iteration   1: 2.225 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.616 ms/op
                 getUser·p0.50:   2.060 ms/op
                 getUser·p0.90:   2.888 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  17.978 ms/op
                 getUser·p0.9999: 18.121 ms/op
                 getUser·p1.00:   18.121 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14355
  mean =      2.225 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 99 
    [ 1.250,  2.500) = 10442 
    [ 2.500,  3.750) = 3542 
    [ 3.750,  5.000) = 140 
    [ 5.000,  6.250) = 61 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.616 ms/op
     p(50.0000) =      2.060 ms/op
     p(90.0000) =      2.888 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =     17.978 ms/op
     p(99.9900) =     18.121 ms/op
     p(99.9990) =     18.121 ms/op
     p(99.9999) =     18.121 ms/op
    p(100.0000) =     18.121 ms/op


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
# Warmup Iteration   1: 4.250 ±(99.9%) 0.119 ms/op
Iteration   1: 3.738 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.231 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   5.063 ms/op
                 listUser·p0.99:   5.710 ms/op
                 listUser·p0.999:  7.821 ms/op
                 listUser·p0.9999: 11.305 ms/op
                 listUser·p1.00:   11.305 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8546
  mean =      3.738 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 520 
    [ 2.500,  3.750) = 3796 
    [ 3.750,  5.000) = 3726 
    [ 5.000,  6.250) = 456 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.231 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      4.628 ms/op
     p(95.0000) =      5.063 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =      7.821 ms/op
     p(99.9900) =     11.305 ms/op
     p(99.9990) =     11.305 ms/op
     p(99.9999) =     11.305 ms/op
    p(100.0000) =     11.305 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.244          ops/ms
ClientSimple.existUser                       thrpt         12.830          ops/ms
ClientSimple.getUser                         thrpt         13.959          ops/ms
ClientSimple.listUser                        thrpt          9.099          ops/ms
ClientSimple.createUser                       avgt          2.259           ms/op
ClientSimple.existUser                        avgt          2.058           ms/op
ClientSimple.getUser                          avgt          1.861           ms/op
ClientSimple.listUser                         avgt          3.087           ms/op
ClientSimple.createUser                     sample  14606   2.197 ± 0.028   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.441           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.114           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.687           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.068           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.825           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.171           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.105           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.105           ms/op
ClientSimple.existUser                      sample  17741   1.804 ± 0.013   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.425           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.743           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.150           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.359           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.607           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.408           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         10.960           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.239           ms/op
ClientSimple.getUser                        sample  14355   2.225 ± 0.027   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.616           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.060           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.888           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.166           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.465           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.978           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.121           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.121           ms/op
ClientSimple.listUser                       sample   8546   3.738 ± 0.028   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.231           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.740           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.628           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.063           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.710           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.821           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         11.305           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.305           ms/op

Benchmark result is saved to 1724717834227.json
