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
# Warmup Iteration   1: 2.145 ops/ms
Iteration   1: 7.610 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.610 ops/ms


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
# Warmup Iteration   1: 6.123 ops/ms
Iteration   1: 12.836 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.836 ops/ms


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
# Warmup Iteration   1: 6.260 ops/ms
Iteration   1: 14.805 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.805 ops/ms


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
# Warmup Iteration   1: 5.892 ops/ms
Iteration   1: 9.420 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.420 ops/ms


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
# Warmup Iteration   1: 3.904 ±(99.9%) 0.096 ms/op
Iteration   1: 2.330 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.330 ms/op


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
# Warmup Iteration   1: 2.769 ±(99.9%) 0.040 ms/op
Iteration   1: 1.951 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.951 ms/op


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
# Warmup Iteration   1: 3.179 ±(99.9%) 0.063 ms/op
Iteration   1: 2.019 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.019 ms/op


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
# Warmup Iteration   1: 4.513 ±(99.9%) 0.089 ms/op
Iteration   1: 3.342 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.342 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.544 ±(99.9%) 0.111 ms/op
Iteration   1: 2.284 ±(99.9%) 0.043 ms/op
                 createUser·p0.00:   0.437 ms/op
                 createUser·p0.50:   2.003 ms/op
                 createUser·p0.90:   3.158 ms/op
                 createUser·p0.95:   3.428 ms/op
                 createUser·p0.99:   5.530 ms/op
                 createUser·p0.999:  29.362 ms/op
                 createUser·p0.9999: 32.919 ms/op
                 createUser·p1.00:   32.997 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13989
  mean =      2.284 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9779 
    [ 2.500,  5.000) = 4058 
    [ 5.000,  7.500) = 82 
    [ 7.500, 10.000) = 26 
    [10.000, 12.500) = 10 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.437 ms/op
     p(50.0000) =      2.003 ms/op
     p(90.0000) =      3.158 ms/op
     p(95.0000) =      3.428 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =     29.362 ms/op
     p(99.9900) =     32.919 ms/op
     p(99.9990) =     32.997 ms/op
     p(99.9999) =     32.997 ms/op
    p(100.0000) =     32.997 ms/op


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
# Warmup Iteration   1: 2.723 ±(99.9%) 0.065 ms/op
Iteration   1: 1.975 ±(99.9%) 0.040 ms/op
                 existUser·p0.00:   0.440 ms/op
                 existUser·p0.50:   1.821 ms/op
                 existUser·p0.90:   2.413 ms/op
                 existUser·p0.95:   2.593 ms/op
                 existUser·p0.99:   3.484 ms/op
                 existUser·p0.999:  32.275 ms/op
                 existUser·p0.9999: 33.639 ms/op
                 existUser·p1.00:   33.686 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17048
  mean =      1.975 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15784 
    [ 2.500,  5.000) = 1166 
    [ 5.000,  7.500) = 2 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.440 ms/op
     p(50.0000) =      1.821 ms/op
     p(90.0000) =      2.413 ms/op
     p(95.0000) =      2.593 ms/op
     p(99.0000) =      3.484 ms/op
     p(99.9000) =     32.275 ms/op
     p(99.9900) =     33.639 ms/op
     p(99.9990) =     33.686 ms/op
     p(99.9999) =     33.686 ms/op
    p(100.0000) =     33.686 ms/op


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
# Warmup Iteration   1: 3.131 ±(99.9%) 0.107 ms/op
Iteration   1: 2.216 ±(99.9%) 0.110 ms/op
                 getUser·p0.00:   0.643 ms/op
                 getUser·p0.50:   1.851 ms/op
                 getUser·p0.90:   2.521 ms/op
                 getUser·p0.95:   2.748 ms/op
                 getUser·p0.99:   5.030 ms/op
                 getUser·p0.999:  85.663 ms/op
                 getUser·p0.9999: 99.615 ms/op
                 getUser·p1.00:   99.615 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14445
  mean =      2.216 ±(99.9%) 0.110 ms/op

  Histogram, ms/op:
    [  0.000,  10.000) = 14358 
    [ 10.000,  20.000) = 24 
    [ 20.000,  30.000) = 19 
    [ 30.000,  40.000) = 10 
    [ 40.000,  50.000) = 2 
    [ 50.000,  60.000) = 2 
    [ 60.000,  70.000) = 10 
    [ 70.000,  80.000) = 2 
    [ 80.000,  90.000) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.643 ms/op
     p(50.0000) =      1.851 ms/op
     p(90.0000) =      2.521 ms/op
     p(95.0000) =      2.748 ms/op
     p(99.0000) =      5.030 ms/op
     p(99.9000) =     85.663 ms/op
     p(99.9900) =     99.615 ms/op
     p(99.9990) =     99.615 ms/op
     p(99.9999) =     99.615 ms/op
    p(100.0000) =     99.615 ms/op


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
# Warmup Iteration   1: 4.720 ±(99.9%) 0.126 ms/op
Iteration   1: 3.278 ±(99.9%) 0.045 ms/op
                 listUser·p0.00:   0.994 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   4.186 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   7.463 ms/op
                 listUser·p0.999:  17.564 ms/op
                 listUser·p0.9999: 17.629 ms/op
                 listUser·p1.00:   17.629 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9757
  mean =      3.278 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 1751 
    [ 2.500,  3.750) = 5574 
    [ 3.750,  5.000) = 2107 
    [ 5.000,  6.250) = 199 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.994 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      4.186 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      7.463 ms/op
     p(99.9000) =     17.564 ms/op
     p(99.9900) =     17.629 ms/op
     p(99.9990) =     17.629 ms/op
     p(99.9999) =     17.629 ms/op
    p(100.0000) =     17.629 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.610          ops/ms
ClientSimple.existUser                       thrpt         12.836          ops/ms
ClientSimple.getUser                         thrpt         14.805          ops/ms
ClientSimple.listUser                        thrpt          9.420          ops/ms
ClientSimple.createUser                       avgt          2.330           ms/op
ClientSimple.existUser                        avgt          1.951           ms/op
ClientSimple.getUser                          avgt          2.019           ms/op
ClientSimple.listUser                         avgt          3.342           ms/op
ClientSimple.createUser                     sample  13989   2.284 ± 0.043   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.437           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.003           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.158           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.428           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.530           ms/op
ClientSimple.createUser:createUser·p0.999   sample         29.362           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         32.919           ms/op
ClientSimple.createUser:createUser·p1.00    sample         32.997           ms/op
ClientSimple.existUser                      sample  17048   1.975 ± 0.040   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.440           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.821           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.413           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.593           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.484           ms/op
ClientSimple.existUser:existUser·p0.999     sample         32.275           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         33.639           ms/op
ClientSimple.existUser:existUser·p1.00      sample         33.686           ms/op
ClientSimple.getUser                        sample  14445   2.216 ± 0.110   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.643           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.851           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.521           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.748           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.030           ms/op
ClientSimple.getUser:getUser·p0.999         sample         85.663           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         99.615           ms/op
ClientSimple.getUser:getUser·p1.00          sample         99.615           ms/op
ClientSimple.listUser                       sample   9757   3.278 ± 0.045   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.994           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.994           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.186           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.620           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.463           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.564           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.629           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.629           ms/op

Benchmark result is saved to 1721239533817.json
