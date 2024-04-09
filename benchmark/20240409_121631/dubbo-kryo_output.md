# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.884 ops/ms
Iteration   1: 7.165 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.165 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.549 ops/ms
Iteration   1: 12.621 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.621 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 6.312 ops/ms
Iteration   1: 13.784 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.784 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.618 ops/ms
Iteration   1: 7.839 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.839 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.961 ±(99.9%) 0.085 ms/op
Iteration   1: 2.355 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.355 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.250 ±(99.9%) 0.046 ms/op
Iteration   1: 1.912 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.912 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.609 ±(99.9%) 0.071 ms/op
Iteration   1: 1.961 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.961 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.486 ±(99.9%) 0.082 ms/op
Iteration   1: 3.863 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.863 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.766 ±(99.9%) 0.109 ms/op
Iteration   1: 2.294 ±(99.9%) 0.041 ms/op
                 createUser·p0.00:   0.795 ms/op
                 createUser·p0.50:   2.114 ms/op
                 createUser·p0.90:   2.986 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   5.095 ms/op
                 createUser·p0.999:  26.640 ms/op
                 createUser·p0.9999: 27.086 ms/op
                 createUser·p1.00:   27.099 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13920
  mean =      2.294 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11021 
    [ 2.500,  5.000) = 2740 
    [ 5.000,  7.500) = 63 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.795 ms/op
     p(50.0000) =      2.114 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      5.095 ms/op
     p(99.9000) =     26.640 ms/op
     p(99.9900) =     27.086 ms/op
     p(99.9990) =     27.099 ms/op
     p(99.9999) =     27.099 ms/op
    p(100.0000) =     27.099 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.927 ±(99.9%) 0.065 ms/op
Iteration   1: 1.730 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.697 ms/op
                 existUser·p0.50:   1.604 ms/op
                 existUser·p0.90:   2.170 ms/op
                 existUser·p0.95:   2.427 ms/op
                 existUser·p0.99:   3.590 ms/op
                 existUser·p0.999:  11.125 ms/op
                 existUser·p0.9999: 11.345 ms/op
                 existUser·p1.00:   11.387 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18510
  mean =      1.730 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 645 
    [ 1.250,  2.500) = 17133 
    [ 2.500,  3.750) = 583 
    [ 3.750,  5.000) = 80 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.697 ms/op
     p(50.0000) =      1.604 ms/op
     p(90.0000) =      2.170 ms/op
     p(95.0000) =      2.427 ms/op
     p(99.0000) =      3.590 ms/op
     p(99.9000) =     11.125 ms/op
     p(99.9900) =     11.345 ms/op
     p(99.9990) =     11.387 ms/op
     p(99.9999) =     11.387 ms/op
    p(100.0000) =     11.387 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.130 ±(99.9%) 0.082 ms/op
Iteration   1: 1.853 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.555 ms/op
                 getUser·p0.50:   1.737 ms/op
                 getUser·p0.90:   2.265 ms/op
                 getUser·p0.95:   2.445 ms/op
                 getUser·p0.99:   3.772 ms/op
                 getUser·p0.999:  19.127 ms/op
                 getUser·p0.9999: 19.268 ms/op
                 getUser·p1.00:   19.268 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17299
  mean =      1.853 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 590 
    [ 1.250,  2.500) = 15948 
    [ 2.500,  3.750) = 581 
    [ 3.750,  5.000) = 70 
    [ 5.000,  6.250) = 18 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.555 ms/op
     p(50.0000) =      1.737 ms/op
     p(90.0000) =      2.265 ms/op
     p(95.0000) =      2.445 ms/op
     p(99.0000) =      3.772 ms/op
     p(99.9000) =     19.127 ms/op
     p(99.9900) =     19.268 ms/op
     p(99.9990) =     19.268 ms/op
     p(99.9999) =     19.268 ms/op
    p(100.0000) =     19.268 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.421 ±(99.9%) 0.112 ms/op
Iteration   1: 3.682 ±(99.9%) 0.051 ms/op
                 listUser·p0.00:   1.110 ms/op
                 listUser·p0.50:   3.596 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   5.079 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  22.369 ms/op
                 listUser·p0.9999: 25.756 ms/op
                 listUser·p1.00:   25.756 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8671
  mean =      3.682 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 668 
    [ 2.500,  5.000) = 7541 
    [ 5.000,  7.500) = 397 
    [ 7.500, 10.000) = 33 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.110 ms/op
     p(50.0000) =      3.596 ms/op
     p(90.0000) =      4.506 ms/op
     p(95.0000) =      5.079 ms/op
     p(99.0000) =      6.914 ms/op
     p(99.9000) =     22.369 ms/op
     p(99.9900) =     25.756 ms/op
     p(99.9990) =     25.756 ms/op
     p(99.9999) =     25.756 ms/op
    p(100.0000) =     25.756 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.165          ops/ms
ClientSimple.existUser                       thrpt         12.621          ops/ms
ClientSimple.getUser                         thrpt         13.784          ops/ms
ClientSimple.listUser                        thrpt          7.839          ops/ms
ClientSimple.createUser                       avgt          2.355           ms/op
ClientSimple.existUser                        avgt          1.912           ms/op
ClientSimple.getUser                          avgt          1.961           ms/op
ClientSimple.listUser                         avgt          3.863           ms/op
ClientSimple.createUser                     sample  13920   2.294 ± 0.041   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.795           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.114           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.986           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.211           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.095           ms/op
ClientSimple.createUser:createUser·p0.999   sample         26.640           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         27.086           ms/op
ClientSimple.createUser:createUser·p1.00    sample         27.099           ms/op
ClientSimple.existUser                      sample  18510   1.730 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.697           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.604           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.170           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.427           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.590           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.125           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.345           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.387           ms/op
ClientSimple.getUser                        sample  17299   1.853 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.555           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.737           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.265           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.445           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.772           ms/op
ClientSimple.getUser:getUser·p0.999         sample         19.127           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.268           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.268           ms/op
ClientSimple.listUser                       sample   8671   3.682 ± 0.051   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.110           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.596           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.506           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.079           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.914           ms/op
ClientSimple.listUser:listUser·p0.999       sample         22.369           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         25.756           ms/op
ClientSimple.listUser:listUser·p1.00        sample         25.756           ms/op

Benchmark result is saved to 1712664412127.json
