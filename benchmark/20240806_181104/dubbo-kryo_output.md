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
# Warmup Iteration   1: 1.253 ops/ms
Iteration   1: 6.326 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.326 ops/ms


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
# Warmup Iteration   1: 5.641 ops/ms
Iteration   1: 13.480 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.480 ops/ms


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
# Warmup Iteration   1: 5.638 ops/ms
Iteration   1: 10.895 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.895 ops/ms


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
# Warmup Iteration   1: 5.186 ops/ms
Iteration   1: 9.027 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.027 ops/ms


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
# Warmup Iteration   1: 4.015 ±(99.9%) 0.072 ms/op
Iteration   1: 2.457 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.457 ms/op


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
# Warmup Iteration   1: 3.604 ±(99.9%) 0.067 ms/op
Iteration   1: 1.848 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.848 ms/op


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
# Warmup Iteration   1: 3.498 ±(99.9%) 0.069 ms/op
Iteration   1: 1.933 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.933 ms/op


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
# Warmup Iteration   1: 4.805 ±(99.9%) 0.110 ms/op
Iteration   1: 3.337 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.337 ms/op


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
# Warmup Iteration   1: 3.765 ±(99.9%) 0.121 ms/op
Iteration   1: 2.385 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.655 ms/op
                 createUser·p0.50:   2.150 ms/op
                 createUser·p0.90:   3.154 ms/op
                 createUser·p0.95:   3.334 ms/op
                 createUser·p0.99:   5.722 ms/op
                 createUser·p0.999:  13.386 ms/op
                 createUser·p0.9999: 13.533 ms/op
                 createUser·p1.00:   13.533 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13413
  mean =      2.385 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 105 
    [ 1.250,  2.500) = 9265 
    [ 2.500,  3.750) = 3722 
    [ 3.750,  5.000) = 121 
    [ 5.000,  6.250) = 68 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.655 ms/op
     p(50.0000) =      2.150 ms/op
     p(90.0000) =      3.154 ms/op
     p(95.0000) =      3.334 ms/op
     p(99.0000) =      5.722 ms/op
     p(99.9000) =     13.386 ms/op
     p(99.9900) =     13.533 ms/op
     p(99.9990) =     13.533 ms/op
     p(99.9999) =     13.533 ms/op
    p(100.0000) =     13.533 ms/op


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
# Warmup Iteration   1: 3.128 ±(99.9%) 0.082 ms/op
Iteration   1: 2.070 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.638 ms/op
                 existUser·p0.50:   1.964 ms/op
                 existUser·p0.90:   2.564 ms/op
                 existUser·p0.95:   2.769 ms/op
                 existUser·p0.99:   5.763 ms/op
                 existUser·p0.999:  13.566 ms/op
                 existUser·p0.9999: 13.664 ms/op
                 existUser·p1.00:   13.664 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15605
  mean =      2.070 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 258 
    [ 1.250,  2.500) = 13346 
    [ 2.500,  3.750) = 1651 
    [ 3.750,  5.000) = 162 
    [ 5.000,  6.250) = 75 
    [ 6.250,  7.500) = 56 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.638 ms/op
     p(50.0000) =      1.964 ms/op
     p(90.0000) =      2.564 ms/op
     p(95.0000) =      2.769 ms/op
     p(99.0000) =      5.763 ms/op
     p(99.9000) =     13.566 ms/op
     p(99.9900) =     13.664 ms/op
     p(99.9990) =     13.664 ms/op
     p(99.9999) =     13.664 ms/op
    p(100.0000) =     13.664 ms/op


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
# Warmup Iteration   1: 3.208 ±(99.9%) 0.085 ms/op
Iteration   1: 2.083 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.614 ms/op
                 getUser·p0.50:   1.929 ms/op
                 getUser·p0.90:   2.601 ms/op
                 getUser·p0.95:   2.957 ms/op
                 getUser·p0.99:   4.861 ms/op
                 getUser·p0.999:  10.306 ms/op
                 getUser·p0.9999: 10.985 ms/op
                 getUser·p1.00:   11.174 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15755
  mean =      2.083 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 224 
    [ 1.250,  2.500) = 13464 
    [ 2.500,  3.750) = 1749 
    [ 3.750,  5.000) = 164 
    [ 5.000,  6.250) = 56 
    [ 6.250,  7.500) = 53 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.614 ms/op
     p(50.0000) =      1.929 ms/op
     p(90.0000) =      2.601 ms/op
     p(95.0000) =      2.957 ms/op
     p(99.0000) =      4.861 ms/op
     p(99.9000) =     10.306 ms/op
     p(99.9900) =     10.985 ms/op
     p(99.9990) =     11.174 ms/op
     p(99.9999) =     11.174 ms/op
    p(100.0000) =     11.174 ms/op


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
# Warmup Iteration   1: 5.022 ±(99.9%) 0.181 ms/op
Iteration   1: 3.391 ±(99.9%) 0.057 ms/op
                 listUser·p0.00:   1.223 ms/op
                 listUser·p0.50:   3.084 ms/op
                 listUser·p0.90:   4.088 ms/op
                 listUser·p0.95:   4.550 ms/op
                 listUser·p0.99:   11.494 ms/op
                 listUser·p0.999:  26.106 ms/op
                 listUser·p0.9999: 27.165 ms/op
                 listUser·p1.00:   27.165 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9431
  mean =      3.391 ±(99.9%) 0.057 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 616 
    [ 2.500,  5.000) = 8458 
    [ 5.000,  7.500) = 261 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.223 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      4.088 ms/op
     p(95.0000) =      4.550 ms/op
     p(99.0000) =     11.494 ms/op
     p(99.9000) =     26.106 ms/op
     p(99.9900) =     27.165 ms/op
     p(99.9990) =     27.165 ms/op
     p(99.9999) =     27.165 ms/op
    p(100.0000) =     27.165 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.326          ops/ms
ClientSimple.existUser                       thrpt         13.480          ops/ms
ClientSimple.getUser                         thrpt         10.895          ops/ms
ClientSimple.listUser                        thrpt          9.027          ops/ms
ClientSimple.createUser                       avgt          2.457           ms/op
ClientSimple.existUser                        avgt          1.848           ms/op
ClientSimple.getUser                          avgt          1.933           ms/op
ClientSimple.listUser                         avgt          3.337           ms/op
ClientSimple.createUser                     sample  13413   2.385 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.655           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.150           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.154           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.334           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.722           ms/op
ClientSimple.createUser:createUser·p0.999   sample         13.386           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         13.533           ms/op
ClientSimple.createUser:createUser·p1.00    sample         13.533           ms/op
ClientSimple.existUser                      sample  15605   2.070 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.638           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.964           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.564           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.769           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.763           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.566           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.664           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.664           ms/op
ClientSimple.getUser                        sample  15755   2.083 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.614           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.929           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.601           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.957           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.861           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.306           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         10.985           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.174           ms/op
ClientSimple.listUser                       sample   9431   3.391 ± 0.057   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.223           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.084           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.088           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.550           ms/op
ClientSimple.listUser:listUser·p0.99        sample         11.494           ms/op
ClientSimple.listUser:listUser·p0.999       sample         26.106           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         27.165           ms/op
ClientSimple.listUser:listUser·p1.00        sample         27.165           ms/op

Benchmark result is saved to 1722967592344.json
