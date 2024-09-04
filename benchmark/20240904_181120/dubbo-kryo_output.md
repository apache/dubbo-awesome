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
# Warmup Iteration   1: 1.054 ops/ms
Iteration   1: 6.665 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.665 ops/ms


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
# Warmup Iteration   1: 6.851 ops/ms
Iteration   1: 13.846 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.846 ops/ms


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
# Warmup Iteration   1: 6.280 ops/ms
Iteration   1: 13.885 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.885 ops/ms


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
# Warmup Iteration   1: 5.064 ops/ms
Iteration   1: 8.677 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.677 ops/ms


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
# Warmup Iteration   1: 3.819 ±(99.9%) 0.068 ms/op
Iteration   1: 2.150 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.150 ms/op


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
# Warmup Iteration   1: 3.295 ±(99.9%) 0.056 ms/op
Iteration   1: 1.750 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.750 ms/op


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
# Warmup Iteration   1: 3.223 ±(99.9%) 0.045 ms/op
Iteration   1: 1.796 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.796 ms/op


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
# Warmup Iteration   1: 4.585 ±(99.9%) 0.074 ms/op
Iteration   1: 3.165 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.165 ms/op


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
# Warmup Iteration   1: 3.341 ±(99.9%) 0.074 ms/op
Iteration   1: 2.196 ±(99.9%) 0.074 ms/op
                 createUser·p0.00:   0.601 ms/op
                 createUser·p0.50:   1.989 ms/op
                 createUser·p0.90:   2.519 ms/op
                 createUser·p0.95:   2.699 ms/op
                 createUser·p0.99:   6.012 ms/op
                 createUser·p0.999:  56.033 ms/op
                 createUser·p0.9999: 56.469 ms/op
                 createUser·p1.00:   56.623 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14708
  mean =      2.196 ±(99.9%) 0.074 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 14535 
    [ 5.000, 10.000) = 64 
    [10.000, 15.000) = 41 
    [15.000, 20.000) = 4 
    [20.000, 25.000) = 11 
    [25.000, 30.000) = 21 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 2 
    [45.000, 50.000) = 4 
    [50.000, 55.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.601 ms/op
     p(50.0000) =      1.989 ms/op
     p(90.0000) =      2.519 ms/op
     p(95.0000) =      2.699 ms/op
     p(99.0000) =      6.012 ms/op
     p(99.9000) =     56.033 ms/op
     p(99.9900) =     56.469 ms/op
     p(99.9990) =     56.623 ms/op
     p(99.9999) =     56.623 ms/op
    p(100.0000) =     56.623 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.924 ±(99.9%) 0.062 ms/op
Iteration   1: 1.719 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.586 ms/op
                 existUser·p0.50:   1.632 ms/op
                 existUser·p0.90:   1.898 ms/op
                 existUser·p0.95:   2.073 ms/op
                 existUser·p0.99:   2.576 ms/op
                 existUser·p0.999:  25.625 ms/op
                 existUser·p0.9999: 25.854 ms/op
                 existUser·p1.00:   25.854 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18624
  mean =      1.719 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18420 
    [ 2.500,  5.000) = 140 
    [ 5.000,  7.500) = 1 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.586 ms/op
     p(50.0000) =      1.632 ms/op
     p(90.0000) =      1.898 ms/op
     p(95.0000) =      2.073 ms/op
     p(99.0000) =      2.576 ms/op
     p(99.9000) =     25.625 ms/op
     p(99.9900) =     25.854 ms/op
     p(99.9990) =     25.854 ms/op
     p(99.9999) =     25.854 ms/op
    p(100.0000) =     25.854 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 3.270 ±(99.9%) 0.070 ms/op
Iteration   1: 1.937 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.338 ms/op
                 getUser·p0.50:   1.888 ms/op
                 getUser·p0.90:   2.351 ms/op
                 getUser·p0.95:   2.548 ms/op
                 getUser·p0.99:   3.043 ms/op
                 getUser·p0.999:  15.006 ms/op
                 getUser·p0.9999: 15.943 ms/op
                 getUser·p1.00:   16.040 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16542
  mean =      1.937 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 245 
    [ 1.250,  2.500) = 15306 
    [ 2.500,  3.750) = 904 
    [ 3.750,  5.000) = 55 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.338 ms/op
     p(50.0000) =      1.888 ms/op
     p(90.0000) =      2.351 ms/op
     p(95.0000) =      2.548 ms/op
     p(99.0000) =      3.043 ms/op
     p(99.9000) =     15.006 ms/op
     p(99.9900) =     15.943 ms/op
     p(99.9990) =     16.040 ms/op
     p(99.9999) =     16.040 ms/op
    p(100.0000) =     16.040 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.621 ±(99.9%) 0.134 ms/op
Iteration   1: 2.919 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   0.820 ms/op
                 listUser·p0.50:   2.814 ms/op
                 listUser·p0.90:   3.318 ms/op
                 listUser·p0.95:   3.924 ms/op
                 listUser·p0.99:   5.125 ms/op
                 listUser·p0.999:  12.191 ms/op
                 listUser·p0.9999: 14.252 ms/op
                 listUser·p1.00:   14.287 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10921
  mean =      2.919 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 874 
    [ 2.500,  3.750) = 9381 
    [ 3.750,  5.000) = 533 
    [ 5.000,  6.250) = 99 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.820 ms/op
     p(50.0000) =      2.814 ms/op
     p(90.0000) =      3.318 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      5.125 ms/op
     p(99.9000) =     12.191 ms/op
     p(99.9900) =     14.252 ms/op
     p(99.9990) =     14.287 ms/op
     p(99.9999) =     14.287 ms/op
    p(100.0000) =     14.287 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.665          ops/ms
ClientSimple.existUser                       thrpt         13.846          ops/ms
ClientSimple.getUser                         thrpt         13.885          ops/ms
ClientSimple.listUser                        thrpt          8.677          ops/ms
ClientSimple.createUser                       avgt          2.150           ms/op
ClientSimple.existUser                        avgt          1.750           ms/op
ClientSimple.getUser                          avgt          1.796           ms/op
ClientSimple.listUser                         avgt          3.165           ms/op
ClientSimple.createUser                     sample  14708   2.196 ± 0.074   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.601           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.989           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.519           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.699           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.012           ms/op
ClientSimple.createUser:createUser·p0.999   sample         56.033           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         56.469           ms/op
ClientSimple.createUser:createUser·p1.00    sample         56.623           ms/op
ClientSimple.existUser                      sample  18624   1.719 ± 0.027   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.586           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.632           ms/op
ClientSimple.existUser:existUser·p0.90      sample          1.898           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.073           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.576           ms/op
ClientSimple.existUser:existUser·p0.999     sample         25.625           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         25.854           ms/op
ClientSimple.existUser:existUser·p1.00      sample         25.854           ms/op
ClientSimple.getUser                        sample  16542   1.937 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.338           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.888           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.351           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.548           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.043           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.006           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.943           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.040           ms/op
ClientSimple.listUser                       sample  10921   2.919 ± 0.021   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.820           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.814           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.318           ms/op
ClientSimple.listUser:listUser·p0.95        sample          3.924           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.125           ms/op
ClientSimple.listUser:listUser·p0.999       sample         12.191           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.252           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.287           ms/op

Benchmark result is saved to 1725473133789.json
