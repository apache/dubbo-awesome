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
# Warmup Iteration   1: 1.859 ops/ms
Iteration   1: 7.908 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.908 ops/ms


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
# Warmup Iteration   1: 6.391 ops/ms
Iteration   1: 13.193 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.193 ops/ms


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
# Warmup Iteration   1: 5.607 ops/ms
Iteration   1: 12.979 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.979 ops/ms


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
# Warmup Iteration   1: 5.521 ops/ms
Iteration   1: 8.488 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.488 ops/ms


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
# Warmup Iteration   1: 4.054 ±(99.9%) 0.072 ms/op
Iteration   1: 2.108 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.108 ms/op


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
# Warmup Iteration   1: 2.900 ±(99.9%) 0.052 ms/op
Iteration   1: 1.850 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.850 ms/op


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
# Warmup Iteration   1: 3.208 ±(99.9%) 0.051 ms/op
Iteration   1: 1.868 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.868 ms/op


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
# Warmup Iteration   1: 4.493 ±(99.9%) 0.088 ms/op
Iteration   1: 3.216 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.216 ms/op


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
# Warmup Iteration   1: 3.518 ±(99.9%) 0.088 ms/op
Iteration   1: 2.139 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.566 ms/op
                 createUser·p0.50:   2.050 ms/op
                 createUser·p0.90:   2.494 ms/op
                 createUser·p0.95:   2.744 ms/op
                 createUser·p0.99:   6.153 ms/op
                 createUser·p0.999:  14.533 ms/op
                 createUser·p0.9999: 18.105 ms/op
                 createUser·p1.00:   18.153 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14932
  mean =      2.139 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 175 
    [ 1.250,  2.500) = 13311 
    [ 2.500,  3.750) = 1140 
    [ 3.750,  5.000) = 145 
    [ 5.000,  6.250) = 14 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.566 ms/op
     p(50.0000) =      2.050 ms/op
     p(90.0000) =      2.494 ms/op
     p(95.0000) =      2.744 ms/op
     p(99.0000) =      6.153 ms/op
     p(99.9000) =     14.533 ms/op
     p(99.9900) =     18.105 ms/op
     p(99.9990) =     18.153 ms/op
     p(99.9999) =     18.153 ms/op
    p(100.0000) =     18.153 ms/op


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
# Warmup Iteration   1: 2.877 ±(99.9%) 0.065 ms/op
Iteration   1: 2.074 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.485 ms/op
                 existUser·p0.50:   1.985 ms/op
                 existUser·p0.90:   2.470 ms/op
                 existUser·p0.95:   2.699 ms/op
                 existUser·p0.99:   4.741 ms/op
                 existUser·p0.999:  15.804 ms/op
                 existUser·p0.9999: 15.968 ms/op
                 existUser·p1.00:   16.056 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15411
  mean =      2.074 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 315 
    [ 1.250,  2.500) = 13700 
    [ 2.500,  3.750) = 1173 
    [ 3.750,  5.000) = 93 
    [ 5.000,  6.250) = 59 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.485 ms/op
     p(50.0000) =      1.985 ms/op
     p(90.0000) =      2.470 ms/op
     p(95.0000) =      2.699 ms/op
     p(99.0000) =      4.741 ms/op
     p(99.9000) =     15.804 ms/op
     p(99.9900) =     15.968 ms/op
     p(99.9990) =     16.056 ms/op
     p(99.9999) =     16.056 ms/op
    p(100.0000) =     16.056 ms/op


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
# Warmup Iteration   1: 3.366 ±(99.9%) 0.079 ms/op
Iteration   1: 2.021 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.545 ms/op
                 getUser·p0.50:   1.909 ms/op
                 getUser·p0.90:   2.470 ms/op
                 getUser·p0.95:   2.679 ms/op
                 getUser·p0.99:   3.294 ms/op
                 getUser·p0.999:  10.371 ms/op
                 getUser·p0.9999: 10.652 ms/op
                 getUser·p1.00:   10.748 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15828
  mean =      2.021 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 117 
    [ 1.250,  2.500) = 14269 
    [ 2.500,  3.750) = 1344 
    [ 3.750,  5.000) = 34 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.545 ms/op
     p(50.0000) =      1.909 ms/op
     p(90.0000) =      2.470 ms/op
     p(95.0000) =      2.679 ms/op
     p(99.0000) =      3.294 ms/op
     p(99.9000) =     10.371 ms/op
     p(99.9900) =     10.652 ms/op
     p(99.9990) =     10.748 ms/op
     p(99.9999) =     10.748 ms/op
    p(100.0000) =     10.748 ms/op


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
# Warmup Iteration   1: 4.719 ±(99.9%) 0.129 ms/op
Iteration   1: 3.436 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.143 ms/op
                 listUser·p0.50:   3.404 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  7.378 ms/op
                 listUser·p0.9999: 7.848 ms/op
                 listUser·p1.00:   7.848 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9315
  mean =      3.436 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 10 
    [1.500, 2.000) = 114 
    [2.000, 2.500) = 581 
    [2.500, 3.000) = 2470 
    [3.000, 3.500) = 1875 
    [3.500, 4.000) = 2009 
    [4.000, 4.500) = 1558 
    [4.500, 5.000) = 514 
    [5.000, 5.500) = 82 
    [5.500, 6.000) = 38 
    [6.000, 6.500) = 14 
    [6.500, 7.000) = 9 
    [7.000, 7.500) = 39 

  Percentiles, ms/op:
      p(0.0000) =      1.143 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =      7.378 ms/op
     p(99.9900) =      7.848 ms/op
     p(99.9990) =      7.848 ms/op
     p(99.9999) =      7.848 ms/op
    p(100.0000) =      7.848 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.908          ops/ms
ClientSimple.existUser                       thrpt         13.193          ops/ms
ClientSimple.getUser                         thrpt         12.979          ops/ms
ClientSimple.listUser                        thrpt          8.488          ops/ms
ClientSimple.createUser                       avgt          2.108           ms/op
ClientSimple.existUser                        avgt          1.850           ms/op
ClientSimple.getUser                          avgt          1.868           ms/op
ClientSimple.listUser                         avgt          3.216           ms/op
ClientSimple.createUser                     sample  14932   2.139 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.566           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.050           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.494           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.744           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.153           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.533           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.105           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.153           ms/op
ClientSimple.existUser                      sample  15411   2.074 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.485           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.985           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.470           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.699           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.741           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.804           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.968           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.056           ms/op
ClientSimple.getUser                        sample  15828   2.021 ± 0.015   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.545           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.909           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.470           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.679           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.294           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.371           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         10.652           ms/op
ClientSimple.getUser:getUser·p1.00          sample         10.748           ms/op
ClientSimple.listUser                       sample   9315   3.436 ± 0.026   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.143           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.404           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.375           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.596           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.554           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.378           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.848           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.848           ms/op

Benchmark result is saved to 1723788356020.json
