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
# Warmup Iteration   1: 0.995 ops/ms
Iteration   1: 6.314 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.314 ops/ms


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
# Warmup Iteration   1: 6.211 ops/ms
Iteration   1: 13.506 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.506 ops/ms


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
# Warmup Iteration   1: 6.082 ops/ms
Iteration   1: 14.077 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.077 ops/ms


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
# Warmup Iteration   1: 5.017 ops/ms
Iteration   1: 8.704 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.704 ops/ms


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
# Warmup Iteration   1: 4.282 ±(99.9%) 0.070 ms/op
Iteration   1: 2.185 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.185 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.003 ±(99.9%) 0.039 ms/op
Iteration   1: 2.041 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.041 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.729 ±(99.9%) 0.071 ms/op
Iteration   1: 2.077 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.077 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.680 ±(99.9%) 0.091 ms/op
Iteration   1: 3.847 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.847 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.747 ±(99.9%) 0.094 ms/op
Iteration   1: 2.068 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   0.700 ms/op
                 createUser·p0.50:   1.919 ms/op
                 createUser·p0.90:   2.519 ms/op
                 createUser·p0.95:   2.703 ms/op
                 createUser·p0.99:   3.600 ms/op
                 createUser·p0.999:  21.664 ms/op
                 createUser·p0.9999: 22.634 ms/op
                 createUser·p1.00:   22.741 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15463
  mean =      2.068 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13804 
    [ 2.500,  5.000) = 1535 
    [ 5.000,  7.500) = 52 
    [ 7.500, 10.000) = 8 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.700 ms/op
     p(50.0000) =      1.919 ms/op
     p(90.0000) =      2.519 ms/op
     p(95.0000) =      2.703 ms/op
     p(99.0000) =      3.600 ms/op
     p(99.9000) =     21.664 ms/op
     p(99.9900) =     22.634 ms/op
     p(99.9990) =     22.741 ms/op
     p(99.9999) =     22.741 ms/op
    p(100.0000) =     22.741 ms/op


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
# Warmup Iteration   1: 3.111 ±(99.9%) 0.077 ms/op
Iteration   1: 1.814 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.681 ms/op
                 existUser·p0.50:   1.704 ms/op
                 existUser·p0.90:   1.999 ms/op
                 existUser·p0.95:   2.150 ms/op
                 existUser·p0.99:   2.731 ms/op
                 existUser·p0.999:  19.444 ms/op
                 existUser·p0.9999: 19.988 ms/op
                 existUser·p1.00:   19.988 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17607
  mean =      1.814 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 131 
    [ 1.250,  2.500) = 17224 
    [ 2.500,  3.750) = 142 
    [ 3.750,  5.000) = 14 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 21 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.681 ms/op
     p(50.0000) =      1.704 ms/op
     p(90.0000) =      1.999 ms/op
     p(95.0000) =      2.150 ms/op
     p(99.0000) =      2.731 ms/op
     p(99.9000) =     19.444 ms/op
     p(99.9900) =     19.988 ms/op
     p(99.9990) =     19.988 ms/op
     p(99.9999) =     19.988 ms/op
    p(100.0000) =     19.988 ms/op


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
# Warmup Iteration   1: 3.103 ±(99.9%) 0.071 ms/op
Iteration   1: 2.060 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.571 ms/op
                 getUser·p0.50:   1.911 ms/op
                 getUser·p0.90:   2.732 ms/op
                 getUser·p0.95:   2.904 ms/op
                 getUser·p0.99:   3.428 ms/op
                 getUser·p0.999:  11.534 ms/op
                 getUser·p0.9999: 12.567 ms/op
                 getUser·p1.00:   12.567 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15507
  mean =      2.060 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 172 
    [ 1.250,  2.500) = 12343 
    [ 2.500,  3.750) = 2860 
    [ 3.750,  5.000) = 83 
    [ 5.000,  6.250) = 8 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.571 ms/op
     p(50.0000) =      1.911 ms/op
     p(90.0000) =      2.732 ms/op
     p(95.0000) =      2.904 ms/op
     p(99.0000) =      3.428 ms/op
     p(99.9000) =     11.534 ms/op
     p(99.9900) =     12.567 ms/op
     p(99.9990) =     12.567 ms/op
     p(99.9999) =     12.567 ms/op
    p(100.0000) =     12.567 ms/op


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
# Warmup Iteration   1: 4.869 ±(99.9%) 0.167 ms/op
Iteration   1: 3.431 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.247 ms/op
                 listUser·p0.50:   3.310 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  7.280 ms/op
                 listUser·p0.9999: 8.864 ms/op
                 listUser·p1.00:   8.864 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9321
  mean =      3.431 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 6 
    [1.500, 2.000) = 40 
    [2.000, 2.500) = 427 
    [2.500, 3.000) = 3481 
    [3.000, 3.500) = 1146 
    [3.500, 4.000) = 1892 
    [4.000, 4.500) = 1565 
    [4.500, 5.000) = 559 
    [5.000, 5.500) = 101 
    [5.500, 6.000) = 50 
    [6.000, 6.500) = 24 
    [6.500, 7.000) = 15 
    [7.000, 7.500) = 13 
    [7.500, 8.000) = 1 
    [8.000, 8.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.247 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =      7.280 ms/op
     p(99.9900) =      8.864 ms/op
     p(99.9990) =      8.864 ms/op
     p(99.9999) =      8.864 ms/op
    p(100.0000) =      8.864 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.314          ops/ms
ClientSimple.existUser                       thrpt         13.506          ops/ms
ClientSimple.getUser                         thrpt         14.077          ops/ms
ClientSimple.listUser                        thrpt          8.704          ops/ms
ClientSimple.createUser                       avgt          2.185           ms/op
ClientSimple.existUser                        avgt          2.041           ms/op
ClientSimple.getUser                          avgt          2.077           ms/op
ClientSimple.listUser                         avgt          3.847           ms/op
ClientSimple.createUser                     sample  15463   2.068 ± 0.028   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.700           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.919           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.519           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.703           ms/op
ClientSimple.createUser:createUser·p0.99    sample          3.600           ms/op
ClientSimple.createUser:createUser·p0.999   sample         21.664           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.634           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.741           ms/op
ClientSimple.existUser                      sample  17607   1.814 ± 0.027   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.681           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.704           ms/op
ClientSimple.existUser:existUser·p0.90      sample          1.999           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.150           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.731           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.444           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.988           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.988           ms/op
ClientSimple.getUser                        sample  15507   2.060 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.571           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.911           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.732           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.904           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.428           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.534           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.567           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.567           ms/op
ClientSimple.listUser                       sample   9321   3.431 ± 0.026   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.247           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.310           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.415           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.710           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.652           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.280           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.864           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.864           ms/op

Benchmark result is saved to 1714802691375.json
