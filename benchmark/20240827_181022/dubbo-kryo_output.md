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
# Warmup Iteration   1: 1.924 ops/ms
Iteration   1: 6.242 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.242 ops/ms


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
# Warmup Iteration   1: 6.511 ops/ms
Iteration   1: 11.228 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.228 ops/ms


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
# Warmup Iteration   1: 4.320 ops/ms
Iteration   1: 10.247 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.247 ops/ms


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
# Warmup Iteration   1: 4.277 ops/ms
Iteration   1: 8.272 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.272 ops/ms


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
# Warmup Iteration   1: 3.757 ±(99.9%) 0.085 ms/op
Iteration   1: 2.247 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.247 ms/op


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
# Warmup Iteration   1: 3.459 ±(99.9%) 0.067 ms/op
Iteration   1: 1.975 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.975 ms/op


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
# Warmup Iteration   1: 3.498 ±(99.9%) 0.072 ms/op
Iteration   1: 2.110 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.110 ms/op


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
# Warmup Iteration   1: 4.390 ±(99.9%) 0.077 ms/op
Iteration   1: 3.558 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.558 ms/op


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
# Warmup Iteration   1: 3.455 ±(99.9%) 0.089 ms/op
Iteration   1: 2.016 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.473 ms/op
                 createUser·p0.50:   1.737 ms/op
                 createUser·p0.90:   2.507 ms/op
                 createUser·p0.95:   2.765 ms/op
                 createUser·p0.99:   8.333 ms/op
                 createUser·p0.999:  21.304 ms/op
                 createUser·p0.9999: 21.692 ms/op
                 createUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15853
  mean =      2.016 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14242 
    [ 2.500,  5.000) = 1319 
    [ 5.000,  7.500) = 126 
    [ 7.500, 10.000) = 38 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.473 ms/op
     p(50.0000) =      1.737 ms/op
     p(90.0000) =      2.507 ms/op
     p(95.0000) =      2.765 ms/op
     p(99.0000) =      8.333 ms/op
     p(99.9000) =     21.304 ms/op
     p(99.9900) =     21.692 ms/op
     p(99.9990) =     21.692 ms/op
     p(99.9999) =     21.692 ms/op
    p(100.0000) =     21.692 ms/op


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
# Warmup Iteration   1: 3.107 ±(99.9%) 0.077 ms/op
Iteration   1: 1.753 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.301 ms/op
                 existUser·p0.50:   1.651 ms/op
                 existUser·p0.90:   2.171 ms/op
                 existUser·p0.95:   2.327 ms/op
                 existUser·p0.99:   3.150 ms/op
                 existUser·p0.999:  9.961 ms/op
                 existUser·p0.9999: 10.947 ms/op
                 existUser·p1.00:   10.961 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18225
  mean =      1.753 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 709 
    [ 1.250,  2.500) = 16996 
    [ 2.500,  3.750) = 401 
    [ 3.750,  5.000) = 45 
    [ 5.000,  6.250) = 27 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.301 ms/op
     p(50.0000) =      1.651 ms/op
     p(90.0000) =      2.171 ms/op
     p(95.0000) =      2.327 ms/op
     p(99.0000) =      3.150 ms/op
     p(99.9000) =      9.961 ms/op
     p(99.9900) =     10.947 ms/op
     p(99.9990) =     10.961 ms/op
     p(99.9999) =     10.961 ms/op
    p(100.0000) =     10.961 ms/op


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
# Warmup Iteration   1: 3.343 ±(99.9%) 0.091 ms/op
Iteration   1: 2.067 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.515 ms/op
                 getUser·p0.50:   2.077 ms/op
                 getUser·p0.90:   2.695 ms/op
                 getUser·p0.95:   2.925 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  10.232 ms/op
                 getUser·p0.9999: 11.278 ms/op
                 getUser·p1.00:   11.305 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15461
  mean =      2.067 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1294 
    [ 1.250,  2.500) = 11144 
    [ 2.500,  3.750) = 2799 
    [ 3.750,  5.000) = 144 
    [ 5.000,  6.250) = 46 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.515 ms/op
     p(50.0000) =      2.077 ms/op
     p(90.0000) =      2.695 ms/op
     p(95.0000) =      2.925 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =     10.232 ms/op
     p(99.9900) =     11.278 ms/op
     p(99.9990) =     11.305 ms/op
     p(99.9999) =     11.305 ms/op
    p(100.0000) =     11.305 ms/op


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
# Warmup Iteration   1: 4.526 ±(99.9%) 0.142 ms/op
Iteration   1: 3.480 ±(99.9%) 0.050 ms/op
                 listUser·p0.00:   0.969 ms/op
                 listUser·p0.50:   3.363 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   7.094 ms/op
                 listUser·p0.999:  23.220 ms/op
                 listUser·p0.9999: 23.527 ms/op
                 listUser·p1.00:   23.527 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9194
  mean =      3.480 ±(99.9%) 0.050 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1005 
    [ 2.500,  5.000) = 7845 
    [ 5.000,  7.500) = 275 
    [ 7.500, 10.000) = 15 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.969 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      7.094 ms/op
     p(99.9000) =     23.220 ms/op
     p(99.9900) =     23.527 ms/op
     p(99.9990) =     23.527 ms/op
     p(99.9999) =     23.527 ms/op
    p(100.0000) =     23.527 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.242          ops/ms
ClientSimple.existUser                       thrpt         11.228          ops/ms
ClientSimple.getUser                         thrpt         10.247          ops/ms
ClientSimple.listUser                        thrpt          8.272          ops/ms
ClientSimple.createUser                       avgt          2.247           ms/op
ClientSimple.existUser                        avgt          1.975           ms/op
ClientSimple.getUser                          avgt          2.110           ms/op
ClientSimple.listUser                         avgt          3.558           ms/op
ClientSimple.createUser                     sample  15853   2.016 ± 0.037   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.473           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.737           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.507           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.765           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.333           ms/op
ClientSimple.createUser:createUser·p0.999   sample         21.304           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.692           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.692           ms/op
ClientSimple.existUser                      sample  18225   1.753 ± 0.013   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.301           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.651           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.171           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.327           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.150           ms/op
ClientSimple.existUser:existUser·p0.999     sample          9.961           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         10.947           ms/op
ClientSimple.existUser:existUser·p1.00      sample         10.961           ms/op
ClientSimple.getUser                        sample  15461   2.067 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.515           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.077           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.695           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.925           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.456           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.232           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.278           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.305           ms/op
ClientSimple.listUser                       sample   9194   3.480 ± 0.050   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.969           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.363           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.325           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.751           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.094           ms/op
ClientSimple.listUser:listUser·p0.999       sample         23.220           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         23.527           ms/op
ClientSimple.listUser:listUser·p1.00        sample         23.527           ms/op

Benchmark result is saved to 1724781952163.json
