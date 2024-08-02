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
# Warmup Iteration   1: 1.076 ops/ms
Iteration   1: 6.197 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.197 ops/ms


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
# Warmup Iteration   1: 6.705 ops/ms
Iteration   1: 13.989 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.989 ops/ms


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
# Warmup Iteration   1: 5.760 ops/ms
Iteration   1: 12.243 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.243 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.150 ops/ms
Iteration   1: 8.350 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.350 ops/ms


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
# Warmup Iteration   1: 3.689 ±(99.9%) 0.062 ms/op
Iteration   1: 2.233 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.233 ms/op


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
# Warmup Iteration   1: 3.495 ±(99.9%) 0.057 ms/op
Iteration   1: 1.918 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.918 ms/op


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
# Warmup Iteration   1: 3.505 ±(99.9%) 0.061 ms/op
Iteration   1: 1.905 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.905 ms/op


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
# Warmup Iteration   1: 4.315 ±(99.9%) 0.091 ms/op
Iteration   1: 3.352 ±(99.9%) 0.014 ms/op


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
# Warmup Iteration   1: 3.764 ±(99.9%) 0.093 ms/op
Iteration   1: 2.668 ±(99.9%) 0.041 ms/op
                 createUser·p0.00:   0.826 ms/op
                 createUser·p0.50:   2.507 ms/op
                 createUser·p0.90:   3.181 ms/op
                 createUser·p0.95:   3.596 ms/op
                 createUser·p0.99:   11.518 ms/op
                 createUser·p0.999:  15.992 ms/op
                 createUser·p0.9999: 16.683 ms/op
                 createUser·p1.00:   16.728 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 11983
  mean =      2.668 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 102 
    [ 1.250,  2.500) = 5815 
    [ 2.500,  3.750) = 5582 
    [ 3.750,  5.000) = 195 
    [ 5.000,  6.250) = 58 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 14 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 43 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.826 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.181 ms/op
     p(95.0000) =      3.596 ms/op
     p(99.0000) =     11.518 ms/op
     p(99.9000) =     15.992 ms/op
     p(99.9900) =     16.683 ms/op
     p(99.9990) =     16.728 ms/op
     p(99.9999) =     16.728 ms/op
    p(100.0000) =     16.728 ms/op


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
# Warmup Iteration   1: 3.274 ±(99.9%) 0.087 ms/op
Iteration   1: 2.001 ±(99.9%) 0.032 ms/op
                 existUser·p0.00:   0.733 ms/op
                 existUser·p0.50:   1.827 ms/op
                 existUser·p0.90:   2.298 ms/op
                 existUser·p0.95:   2.535 ms/op
                 existUser·p0.99:   5.572 ms/op
                 existUser·p0.999:  24.019 ms/op
                 existUser·p0.9999: 24.812 ms/op
                 existUser·p1.00:   24.871 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15984
  mean =      2.001 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15134 
    [ 2.500,  5.000) = 659 
    [ 5.000,  7.500) = 119 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 4 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.733 ms/op
     p(50.0000) =      1.827 ms/op
     p(90.0000) =      2.298 ms/op
     p(95.0000) =      2.535 ms/op
     p(99.0000) =      5.572 ms/op
     p(99.9000) =     24.019 ms/op
     p(99.9900) =     24.812 ms/op
     p(99.9990) =     24.871 ms/op
     p(99.9999) =     24.871 ms/op
    p(100.0000) =     24.871 ms/op


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
# Warmup Iteration   1: 3.288 ±(99.9%) 0.078 ms/op
Iteration   1: 1.949 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.757 ms/op
                 getUser·p0.50:   1.837 ms/op
                 getUser·p0.90:   2.351 ms/op
                 getUser·p0.95:   2.527 ms/op
                 getUser·p0.99:   3.256 ms/op
                 getUser·p0.999:  14.741 ms/op
                 getUser·p0.9999: 17.229 ms/op
                 getUser·p1.00:   17.334 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16418
  mean =      1.949 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 92 
    [ 1.250,  2.500) = 15405 
    [ 2.500,  3.750) = 804 
    [ 3.750,  5.000) = 82 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.757 ms/op
     p(50.0000) =      1.837 ms/op
     p(90.0000) =      2.351 ms/op
     p(95.0000) =      2.527 ms/op
     p(99.0000) =      3.256 ms/op
     p(99.9000) =     14.741 ms/op
     p(99.9900) =     17.229 ms/op
     p(99.9990) =     17.334 ms/op
     p(99.9999) =     17.334 ms/op
    p(100.0000) =     17.334 ms/op


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
# Warmup Iteration   1: 4.260 ±(99.9%) 0.142 ms/op
Iteration   1: 3.665 ±(99.9%) 0.051 ms/op
                 listUser·p0.00:   1.073 ms/op
                 listUser·p0.50:   3.600 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.905 ms/op
                 listUser·p0.99:   6.806 ms/op
                 listUser·p0.999:  20.519 ms/op
                 listUser·p0.9999: 20.775 ms/op
                 listUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8803
  mean =      3.665 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 659 
    [ 2.500,  5.000) = 7734 
    [ 5.000,  7.500) = 343 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.073 ms/op
     p(50.0000) =      3.600 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.905 ms/op
     p(99.0000) =      6.806 ms/op
     p(99.9000) =     20.519 ms/op
     p(99.9900) =     20.775 ms/op
     p(99.9990) =     20.775 ms/op
     p(99.9999) =     20.775 ms/op
    p(100.0000) =     20.775 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.197          ops/ms
ClientSimple.existUser                       thrpt         13.989          ops/ms
ClientSimple.getUser                         thrpt         12.243          ops/ms
ClientSimple.listUser                        thrpt          8.350          ops/ms
ClientSimple.createUser                       avgt          2.233           ms/op
ClientSimple.existUser                        avgt          1.918           ms/op
ClientSimple.getUser                          avgt          1.905           ms/op
ClientSimple.listUser                         avgt          3.352           ms/op
ClientSimple.createUser                     sample  11983   2.668 ± 0.041   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.826           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.507           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.181           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.596           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.518           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.992           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.683           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.728           ms/op
ClientSimple.existUser                      sample  15984   2.001 ± 0.032   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.733           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.827           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.298           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.535           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.572           ms/op
ClientSimple.existUser:existUser·p0.999     sample         24.019           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         24.812           ms/op
ClientSimple.existUser:existUser·p1.00      sample         24.871           ms/op
ClientSimple.getUser                        sample  16418   1.949 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.757           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.837           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.351           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.527           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.256           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.741           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.229           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.334           ms/op
ClientSimple.listUser                       sample   8803   3.665 ± 0.051   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.073           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.600           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.276           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.905           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.806           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.519           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.775           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.775           ms/op

Benchmark result is saved to 1722578814007.json
