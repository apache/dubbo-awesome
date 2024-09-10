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
# Warmup Iteration   1: 0.974 ops/ms
Iteration   1: 5.943 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.943 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.325 ops/ms
Iteration   1: 12.287 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.287 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.208 ops/ms
Iteration   1: 13.477 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.477 ops/ms


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
# Warmup Iteration   1: 5.150 ops/ms
Iteration   1: 8.722 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.722 ops/ms


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
# Warmup Iteration   1: 3.775 ±(99.9%) 0.061 ms/op
Iteration   1: 2.091 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.091 ms/op


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
# Warmup Iteration   1: 3.379 ±(99.9%) 0.065 ms/op
Iteration   1: 1.962 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.962 ms/op


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
# Warmup Iteration   1: 3.246 ±(99.9%) 0.054 ms/op
Iteration   1: 1.925 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.925 ms/op


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
# Warmup Iteration   1: 4.603 ±(99.9%) 0.108 ms/op
Iteration   1: 3.624 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.624 ms/op


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
# Warmup Iteration   1: 3.666 ±(99.9%) 0.104 ms/op
Iteration   1: 2.071 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.878 ms/op
                 createUser·p0.50:   1.876 ms/op
                 createUser·p0.90:   2.597 ms/op
                 createUser·p0.95:   2.929 ms/op
                 createUser·p0.99:   6.910 ms/op
                 createUser·p0.999:  19.797 ms/op
                 createUser·p0.9999: 21.187 ms/op
                 createUser·p1.00:   21.365 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15423
  mean =      2.071 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13350 
    [ 2.500,  5.000) = 1793 
    [ 5.000,  7.500) = 158 
    [ 7.500, 10.000) = 58 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.878 ms/op
     p(50.0000) =      1.876 ms/op
     p(90.0000) =      2.597 ms/op
     p(95.0000) =      2.929 ms/op
     p(99.0000) =      6.910 ms/op
     p(99.9000) =     19.797 ms/op
     p(99.9900) =     21.187 ms/op
     p(99.9990) =     21.365 ms/op
     p(99.9999) =     21.365 ms/op
    p(100.0000) =     21.365 ms/op


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
# Warmup Iteration   1: 3.128 ±(99.9%) 0.076 ms/op
Iteration   1: 1.806 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.601 ms/op
                 existUser·p0.50:   1.688 ms/op
                 existUser·p0.90:   2.269 ms/op
                 existUser·p0.95:   2.388 ms/op
                 existUser·p0.99:   2.809 ms/op
                 existUser·p0.999:  15.792 ms/op
                 existUser·p0.9999: 15.995 ms/op
                 existUser·p1.00:   16.007 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17717
  mean =      1.806 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 277 
    [ 1.250,  2.500) = 17012 
    [ 2.500,  3.750) = 373 
    [ 3.750,  5.000) = 14 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.601 ms/op
     p(50.0000) =      1.688 ms/op
     p(90.0000) =      2.269 ms/op
     p(95.0000) =      2.388 ms/op
     p(99.0000) =      2.809 ms/op
     p(99.9000) =     15.792 ms/op
     p(99.9900) =     15.995 ms/op
     p(99.9990) =     16.007 ms/op
     p(99.9999) =     16.007 ms/op
    p(100.0000) =     16.007 ms/op


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
# Warmup Iteration   1: 3.304 ±(99.9%) 0.099 ms/op
Iteration   1: 2.434 ±(99.9%) 0.048 ms/op
                 getUser·p0.00:   0.675 ms/op
                 getUser·p0.50:   2.277 ms/op
                 getUser·p0.90:   3.121 ms/op
                 getUser·p0.95:   3.338 ms/op
                 getUser·p0.99:   5.497 ms/op
                 getUser·p0.999:  33.817 ms/op
                 getUser·p0.9999: 34.964 ms/op
                 getUser·p1.00:   35.258 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13452
  mean =      2.434 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8760 
    [ 2.500,  5.000) = 4511 
    [ 5.000,  7.500) = 117 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.675 ms/op
     p(50.0000) =      2.277 ms/op
     p(90.0000) =      3.121 ms/op
     p(95.0000) =      3.338 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =     33.817 ms/op
     p(99.9900) =     34.964 ms/op
     p(99.9990) =     35.258 ms/op
     p(99.9999) =     35.258 ms/op
    p(100.0000) =     35.258 ms/op


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
# Warmup Iteration   1: 4.797 ±(99.9%) 0.146 ms/op
Iteration   1: 3.257 ±(99.9%) 0.033 ms/op
                 listUser·p0.00:   0.647 ms/op
                 listUser·p0.50:   3.019 ms/op
                 listUser·p0.90:   4.112 ms/op
                 listUser·p0.95:   4.491 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  13.815 ms/op
                 listUser·p0.9999: 14.336 ms/op
                 listUser·p1.00:   14.336 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9815
  mean =      3.257 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 11 
    [ 1.250,  2.500) = 907 
    [ 2.500,  3.750) = 6981 
    [ 3.750,  5.000) = 1595 
    [ 5.000,  6.250) = 170 
    [ 6.250,  7.500) = 80 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.647 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      4.112 ms/op
     p(95.0000) =      4.491 ms/op
     p(99.0000) =      6.971 ms/op
     p(99.9000) =     13.815 ms/op
     p(99.9900) =     14.336 ms/op
     p(99.9990) =     14.336 ms/op
     p(99.9999) =     14.336 ms/op
    p(100.0000) =     14.336 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.943          ops/ms
ClientSimple.existUser                       thrpt         12.287          ops/ms
ClientSimple.getUser                         thrpt         13.477          ops/ms
ClientSimple.listUser                        thrpt          8.722          ops/ms
ClientSimple.createUser                       avgt          2.091           ms/op
ClientSimple.existUser                        avgt          1.962           ms/op
ClientSimple.getUser                          avgt          1.925           ms/op
ClientSimple.listUser                         avgt          3.624           ms/op
ClientSimple.createUser                     sample  15423   2.071 ± 0.033   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.878           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.876           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.597           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.929           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.910           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.797           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.187           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.365           ms/op
ClientSimple.existUser                      sample  17717   1.806 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.601           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.688           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.269           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.388           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.809           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.792           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.995           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.007           ms/op
ClientSimple.getUser                        sample  13452   2.434 ± 0.048   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.675           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.277           ms/op
ClientSimple.getUser:getUser·p0.90          sample          3.121           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.338           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.497           ms/op
ClientSimple.getUser:getUser·p0.999         sample         33.817           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         34.964           ms/op
ClientSimple.getUser:getUser·p1.00          sample         35.258           ms/op
ClientSimple.listUser                       sample   9815   3.257 ± 0.033   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.647           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.019           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.112           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.491           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.971           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.815           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.336           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.336           ms/op

Benchmark result is saved to 1725970057044.json
