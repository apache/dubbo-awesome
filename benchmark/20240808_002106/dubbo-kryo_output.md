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
# Warmup Iteration   1: 1.600 ops/ms
Iteration   1: 6.827 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.827 ops/ms


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
# Warmup Iteration   1: 4.977 ops/ms
Iteration   1: 12.117 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.117 ops/ms


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
# Warmup Iteration   1: 4.999 ops/ms
Iteration   1: 11.561 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.561 ops/ms


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
# Warmup Iteration   1: 4.053 ops/ms
Iteration   1: 8.195 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.195 ops/ms


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
# Warmup Iteration   1: 4.093 ±(99.9%) 0.080 ms/op
Iteration   1: 2.288 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.288 ms/op


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
# Warmup Iteration   1: 3.112 ±(99.9%) 0.045 ms/op
Iteration   1: 2.085 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.085 ms/op


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
# Warmup Iteration   1: 3.448 ±(99.9%) 0.057 ms/op
Iteration   1: 2.006 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.006 ms/op


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
# Warmup Iteration   1: 4.416 ±(99.9%) 0.104 ms/op
Iteration   1: 3.703 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.703 ms/op


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
# Warmup Iteration   1: 3.421 ±(99.9%) 0.086 ms/op
Iteration   1: 2.500 ±(99.9%) 0.048 ms/op
                 createUser·p0.00:   0.457 ms/op
                 createUser·p0.50:   2.363 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.338 ms/op
                 createUser·p0.99:   11.878 ms/op
                 createUser·p0.999:  19.270 ms/op
                 createUser·p0.9999: 20.054 ms/op
                 createUser·p1.00:   20.054 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12956
  mean =      2.500 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7983 
    [ 2.500,  5.000) = 4679 
    [ 5.000,  7.500) = 109 
    [ 7.500, 10.000) = 25 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.457 ms/op
     p(50.0000) =      2.363 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.338 ms/op
     p(99.0000) =     11.878 ms/op
     p(99.9000) =     19.270 ms/op
     p(99.9900) =     20.054 ms/op
     p(99.9990) =     20.054 ms/op
     p(99.9999) =     20.054 ms/op
    p(100.0000) =     20.054 ms/op


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
# Warmup Iteration   1: 3.096 ±(99.9%) 0.097 ms/op
Iteration   1: 1.882 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.658 ms/op
                 existUser·p0.50:   1.817 ms/op
                 existUser·p0.90:   2.331 ms/op
                 existUser·p0.95:   2.503 ms/op
                 existUser·p0.99:   2.843 ms/op
                 existUser·p0.999:  10.453 ms/op
                 existUser·p0.9999: 10.596 ms/op
                 existUser·p1.00:   10.699 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16998
  mean =      1.882 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 245 
    [ 1.250,  2.500) = 15890 
    [ 2.500,  3.750) = 788 
    [ 3.750,  5.000) = 33 
    [ 5.000,  6.250) = 10 
    [ 6.250,  7.500) = 0 
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
      p(0.0000) =      0.658 ms/op
     p(50.0000) =      1.817 ms/op
     p(90.0000) =      2.331 ms/op
     p(95.0000) =      2.503 ms/op
     p(99.0000) =      2.843 ms/op
     p(99.9000) =     10.453 ms/op
     p(99.9900) =     10.596 ms/op
     p(99.9990) =     10.699 ms/op
     p(99.9999) =     10.699 ms/op
    p(100.0000) =     10.699 ms/op


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
# Warmup Iteration   1: 3.845 ±(99.9%) 0.128 ms/op
Iteration   1: 2.545 ±(99.9%) 0.034 ms/op
                 getUser·p0.00:   0.565 ms/op
                 getUser·p0.50:   2.343 ms/op
                 getUser·p0.90:   3.285 ms/op
                 getUser·p0.95:   3.630 ms/op
                 getUser·p0.99:   5.950 ms/op
                 getUser·p0.999:  17.302 ms/op
                 getUser·p0.9999: 17.891 ms/op
                 getUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 12555
  mean =      2.545 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 68 
    [ 1.250,  2.500) = 7598 
    [ 2.500,  3.750) = 4390 
    [ 3.750,  5.000) = 268 
    [ 5.000,  6.250) = 112 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.565 ms/op
     p(50.0000) =      2.343 ms/op
     p(90.0000) =      3.285 ms/op
     p(95.0000) =      3.630 ms/op
     p(99.0000) =      5.950 ms/op
     p(99.9000) =     17.302 ms/op
     p(99.9900) =     17.891 ms/op
     p(99.9990) =     17.924 ms/op
     p(99.9999) =     17.924 ms/op
    p(100.0000) =     17.924 ms/op


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
# Warmup Iteration   1: 4.484 ±(99.9%) 0.131 ms/op
Iteration   1: 3.655 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   0.820 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.791 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  11.764 ms/op
                 listUser·p0.9999: 12.435 ms/op
                 listUser·p1.00:   12.435 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8762
  mean =      3.655 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 509 
    [ 2.500,  3.750) = 4432 
    [ 3.750,  5.000) = 3468 
    [ 5.000,  6.250) = 203 
    [ 6.250,  7.500) = 80 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.820 ms/op
     p(50.0000) =      3.650 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.791 ms/op
     p(99.0000) =      6.816 ms/op
     p(99.9000) =     11.764 ms/op
     p(99.9900) =     12.435 ms/op
     p(99.9990) =     12.435 ms/op
     p(99.9999) =     12.435 ms/op
    p(100.0000) =     12.435 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.827          ops/ms
ClientSimple.existUser                       thrpt         12.117          ops/ms
ClientSimple.getUser                         thrpt         11.561          ops/ms
ClientSimple.listUser                        thrpt          8.195          ops/ms
ClientSimple.createUser                       avgt          2.288           ms/op
ClientSimple.existUser                        avgt          2.085           ms/op
ClientSimple.getUser                          avgt          2.006           ms/op
ClientSimple.listUser                         avgt          3.703           ms/op
ClientSimple.createUser                     sample  12956   2.500 ± 0.048   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.457           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.363           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.015           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.338           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.878           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.270           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.054           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.054           ms/op
ClientSimple.existUser                      sample  16998   1.882 ± 0.013   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.658           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.817           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.331           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.503           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.843           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.453           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         10.596           ms/op
ClientSimple.existUser:existUser·p1.00      sample         10.699           ms/op
ClientSimple.getUser                        sample  12555   2.545 ± 0.034   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.565           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.343           ms/op
ClientSimple.getUser:getUser·p0.90          sample          3.285           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.630           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.950           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.302           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.891           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.924           ms/op
ClientSimple.listUser                       sample   8762   3.655 ± 0.032   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.820           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.650           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.383           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.791           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.816           ms/op
ClientSimple.listUser:listUser·p0.999       sample         11.764           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         12.435           ms/op
ClientSimple.listUser:listUser·p1.00        sample         12.435           ms/op

Benchmark result is saved to 1723076203248.json
