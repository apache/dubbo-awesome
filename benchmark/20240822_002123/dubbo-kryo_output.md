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
# Warmup Iteration   1: 1.814 ops/ms
Iteration   1: 7.764 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.764 ops/ms


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
# Warmup Iteration   1: 5.891 ops/ms
Iteration   1: 11.828 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.828 ops/ms


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
# Warmup Iteration   1: 6.216 ops/ms
Iteration   1: 11.710 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.710 ops/ms


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
# Warmup Iteration   1: 4.544 ops/ms
Iteration   1: 8.889 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.889 ops/ms


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
# Warmup Iteration   1: 3.569 ±(99.9%) 0.059 ms/op
Iteration   1: 2.583 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.583 ms/op


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
# Warmup Iteration   1: 3.136 ±(99.9%) 0.051 ms/op
Iteration   1: 1.996 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.996 ms/op


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
# Warmup Iteration   1: 3.241 ±(99.9%) 0.084 ms/op
Iteration   1: 2.099 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.099 ms/op


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
# Warmup Iteration   1: 4.750 ±(99.9%) 0.130 ms/op
Iteration   1: 3.198 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.198 ms/op


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
# Warmup Iteration   1: 3.606 ±(99.9%) 0.084 ms/op
Iteration   1: 2.173 ±(99.9%) 0.044 ms/op
                 createUser·p0.00:   0.491 ms/op
                 createUser·p0.50:   2.021 ms/op
                 createUser·p0.90:   2.486 ms/op
                 createUser·p0.95:   2.691 ms/op
                 createUser·p0.99:   5.800 ms/op
                 createUser·p0.999:  34.472 ms/op
                 createUser·p0.9999: 34.669 ms/op
                 createUser·p1.00:   34.669 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14897
  mean =      2.173 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13518 
    [ 2.500,  5.000) = 1165 
    [ 5.000,  7.500) = 146 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.491 ms/op
     p(50.0000) =      2.021 ms/op
     p(90.0000) =      2.486 ms/op
     p(95.0000) =      2.691 ms/op
     p(99.0000) =      5.800 ms/op
     p(99.9000) =     34.472 ms/op
     p(99.9900) =     34.669 ms/op
     p(99.9990) =     34.669 ms/op
     p(99.9999) =     34.669 ms/op
    p(100.0000) =     34.669 ms/op


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
# Warmup Iteration   1: 2.902 ±(99.9%) 0.068 ms/op
Iteration   1: 1.681 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.199 ms/op
                 existUser·p0.50:   1.579 ms/op
                 existUser·p0.90:   2.097 ms/op
                 existUser·p0.95:   2.302 ms/op
                 existUser·p0.99:   3.487 ms/op
                 existUser·p0.999:  13.517 ms/op
                 existUser·p0.9999: 14.221 ms/op
                 existUser·p1.00:   14.221 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 19194
  mean =      1.681 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2569 
    [ 1.250,  2.500) = 16107 
    [ 2.500,  3.750) = 335 
    [ 3.750,  5.000) = 90 
    [ 5.000,  6.250) = 15 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.199 ms/op
     p(50.0000) =      1.579 ms/op
     p(90.0000) =      2.097 ms/op
     p(95.0000) =      2.302 ms/op
     p(99.0000) =      3.487 ms/op
     p(99.9000) =     13.517 ms/op
     p(99.9900) =     14.221 ms/op
     p(99.9990) =     14.221 ms/op
     p(99.9999) =     14.221 ms/op
    p(100.0000) =     14.221 ms/op


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
# Warmup Iteration   1: 3.230 ±(99.9%) 0.088 ms/op
Iteration   1: 2.082 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.310 ms/op
                 getUser·p0.50:   1.993 ms/op
                 getUser·p0.90:   2.900 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.725 ms/op
                 getUser·p0.999:  10.387 ms/op
                 getUser·p0.9999: 10.755 ms/op
                 getUser·p1.00:   10.764 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15759
  mean =      2.082 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 506 
    [ 1.250,  2.500) = 11703 
    [ 2.500,  3.750) = 3394 
    [ 3.750,  5.000) = 113 
    [ 5.000,  6.250) = 11 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.310 ms/op
     p(50.0000) =      1.993 ms/op
     p(90.0000) =      2.900 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.725 ms/op
     p(99.9000) =     10.387 ms/op
     p(99.9900) =     10.755 ms/op
     p(99.9990) =     10.764 ms/op
     p(99.9999) =     10.764 ms/op
    p(100.0000) =     10.764 ms/op


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
# Warmup Iteration   1: 4.636 ±(99.9%) 0.175 ms/op
Iteration   1: 3.599 ±(99.9%) 0.046 ms/op
                 listUser·p0.00:   0.772 ms/op
                 listUser·p0.50:   3.416 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   5.087 ms/op
                 listUser·p0.99:   5.848 ms/op
                 listUser·p0.999:  22.085 ms/op
                 listUser·p0.9999: 23.396 ms/op
                 listUser·p1.00:   23.396 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9010
  mean =      3.599 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 321 
    [ 2.500,  5.000) = 8051 
    [ 5.000,  7.500) = 604 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.772 ms/op
     p(50.0000) =      3.416 ms/op
     p(90.0000) =      4.571 ms/op
     p(95.0000) =      5.087 ms/op
     p(99.0000) =      5.848 ms/op
     p(99.9000) =     22.085 ms/op
     p(99.9900) =     23.396 ms/op
     p(99.9990) =     23.396 ms/op
     p(99.9999) =     23.396 ms/op
    p(100.0000) =     23.396 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.764          ops/ms
ClientSimple.existUser                       thrpt         11.828          ops/ms
ClientSimple.getUser                         thrpt         11.710          ops/ms
ClientSimple.listUser                        thrpt          8.889          ops/ms
ClientSimple.createUser                       avgt          2.583           ms/op
ClientSimple.existUser                        avgt          1.996           ms/op
ClientSimple.getUser                          avgt          2.099           ms/op
ClientSimple.listUser                         avgt          3.198           ms/op
ClientSimple.createUser                     sample  14897   2.173 ± 0.044   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.491           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.021           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.486           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.691           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.800           ms/op
ClientSimple.createUser:createUser·p0.999   sample         34.472           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         34.669           ms/op
ClientSimple.createUser:createUser·p1.00    sample         34.669           ms/op
ClientSimple.existUser                      sample  19194   1.681 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.199           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.579           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.097           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.302           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.487           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.517           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.221           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.221           ms/op
ClientSimple.getUser                        sample  15759   2.082 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.310           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.993           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.900           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.146           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.725           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.387           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         10.755           ms/op
ClientSimple.getUser:getUser·p1.00          sample         10.764           ms/op
ClientSimple.listUser                       sample   9010   3.599 ± 0.046   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.772           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.416           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.571           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.087           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.848           ms/op
ClientSimple.listUser:listUser·p0.999       sample         22.085           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         23.396           ms/op
ClientSimple.listUser:listUser·p1.00        sample         23.396           ms/op

Benchmark result is saved to 1724285816650.json
