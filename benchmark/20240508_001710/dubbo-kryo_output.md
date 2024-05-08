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
# Warmup Iteration   1: 1.807 ops/ms
Iteration   1: 7.476 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.476 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.506 ops/ms
Iteration   1: 13.137 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.137 ops/ms


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
# Warmup Iteration   1: 5.768 ops/ms
Iteration   1: 12.211 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.211 ops/ms


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
# Warmup Iteration   1: 5.323 ops/ms
Iteration   1: 8.607 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.607 ops/ms


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
# Warmup Iteration   1: 3.884 ±(99.9%) 0.074 ms/op
Iteration   1: 2.215 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.215 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.406 ±(99.9%) 0.054 ms/op
Iteration   1: 1.816 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.816 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.370 ±(99.9%) 0.056 ms/op
Iteration   1: 2.151 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.151 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.571 ±(99.9%) 0.079 ms/op
Iteration   1: 3.217 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.217 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.457 ±(99.9%) 0.100 ms/op
Iteration   1: 2.075 ±(99.9%) 0.052 ms/op
                 createUser·p0.00:   0.752 ms/op
                 createUser·p0.50:   1.855 ms/op
                 createUser·p0.90:   2.458 ms/op
                 createUser·p0.95:   2.733 ms/op
                 createUser·p0.99:   4.850 ms/op
                 createUser·p0.999:  47.891 ms/op
                 createUser·p0.9999: 50.135 ms/op
                 createUser·p1.00:   50.856 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15236
  mean =      2.075 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 15106 
    [ 5.000, 10.000) = 65 
    [10.000, 15.000) = 32 
    [15.000, 20.000) = 1 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 16 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 15 
    [50.000, 55.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.752 ms/op
     p(50.0000) =      1.855 ms/op
     p(90.0000) =      2.458 ms/op
     p(95.0000) =      2.733 ms/op
     p(99.0000) =      4.850 ms/op
     p(99.9000) =     47.891 ms/op
     p(99.9900) =     50.135 ms/op
     p(99.9990) =     50.856 ms/op
     p(99.9999) =     50.856 ms/op
    p(100.0000) =     50.856 ms/op


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
# Warmup Iteration   1: 3.295 ±(99.9%) 0.074 ms/op
Iteration   1: 1.791 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.361 ms/op
                 existUser·p0.50:   1.655 ms/op
                 existUser·p0.90:   2.339 ms/op
                 existUser·p0.95:   2.638 ms/op
                 existUser·p0.99:   4.895 ms/op
                 existUser·p0.999:  19.494 ms/op
                 existUser·p0.9999: 20.057 ms/op
                 existUser·p1.00:   20.185 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17845
  mean =      1.791 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16590 
    [ 2.500,  5.000) = 1100 
    [ 5.000,  7.500) = 59 
    [ 7.500, 10.000) = 31 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.361 ms/op
     p(50.0000) =      1.655 ms/op
     p(90.0000) =      2.339 ms/op
     p(95.0000) =      2.638 ms/op
     p(99.0000) =      4.895 ms/op
     p(99.9000) =     19.494 ms/op
     p(99.9900) =     20.057 ms/op
     p(99.9990) =     20.185 ms/op
     p(99.9999) =     20.185 ms/op
    p(100.0000) =     20.185 ms/op


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
# Warmup Iteration   1: 3.293 ±(99.9%) 0.086 ms/op
Iteration   1: 2.060 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.303 ms/op
                 getUser·p0.50:   1.919 ms/op
                 getUser·p0.90:   2.568 ms/op
                 getUser·p0.95:   2.769 ms/op
                 getUser·p0.99:   5.841 ms/op
                 getUser·p0.999:  12.443 ms/op
                 getUser·p0.9999: 12.800 ms/op
                 getUser·p1.00:   12.927 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15535
  mean =      2.060 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 447 
    [ 1.250,  2.500) = 13035 
    [ 2.500,  3.750) = 1774 
    [ 3.750,  5.000) = 63 
    [ 5.000,  6.250) = 140 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.303 ms/op
     p(50.0000) =      1.919 ms/op
     p(90.0000) =      2.568 ms/op
     p(95.0000) =      2.769 ms/op
     p(99.0000) =      5.841 ms/op
     p(99.9000) =     12.443 ms/op
     p(99.9900) =     12.800 ms/op
     p(99.9990) =     12.927 ms/op
     p(99.9999) =     12.927 ms/op
    p(100.0000) =     12.927 ms/op


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
# Warmup Iteration   1: 4.817 ±(99.9%) 0.141 ms/op
Iteration   1: 3.105 ±(99.9%) 0.070 ms/op
                 listUser·p0.00:   1.027 ms/op
                 listUser·p0.50:   2.744 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   7.840 ms/op
                 listUser·p0.999:  37.618 ms/op
                 listUser·p0.9999: 37.938 ms/op
                 listUser·p1.00:   37.945 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10296
  mean =      3.105 ±(99.9%) 0.070 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2578 
    [ 2.500,  5.000) = 7497 
    [ 5.000,  7.500) = 115 
    [ 7.500, 10.000) = 31 
    [10.000, 12.500) = 9 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.027 ms/op
     p(50.0000) =      2.744 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      7.840 ms/op
     p(99.9000) =     37.618 ms/op
     p(99.9900) =     37.938 ms/op
     p(99.9990) =     37.945 ms/op
     p(99.9999) =     37.945 ms/op
    p(100.0000) =     37.945 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.476          ops/ms
ClientSimple.existUser                       thrpt         13.137          ops/ms
ClientSimple.getUser                         thrpt         12.211          ops/ms
ClientSimple.listUser                        thrpt          8.607          ops/ms
ClientSimple.createUser                       avgt          2.215           ms/op
ClientSimple.existUser                        avgt          1.816           ms/op
ClientSimple.getUser                          avgt          2.151           ms/op
ClientSimple.listUser                         avgt          3.217           ms/op
ClientSimple.createUser                     sample  15236   2.075 ± 0.052   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.752           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.855           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.458           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.733           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.850           ms/op
ClientSimple.createUser:createUser·p0.999   sample         47.891           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         50.135           ms/op
ClientSimple.createUser:createUser·p1.00    sample         50.856           ms/op
ClientSimple.existUser                      sample  17845   1.791 ± 0.027   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.361           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.655           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.339           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.638           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.895           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.494           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         20.057           ms/op
ClientSimple.existUser:existUser·p1.00      sample         20.185           ms/op
ClientSimple.getUser                        sample  15535   2.060 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.303           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.919           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.568           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.769           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.841           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.443           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.800           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.927           ms/op
ClientSimple.listUser                       sample  10296   3.105 ± 0.070   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.027           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.744           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.867           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.284           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.840           ms/op
ClientSimple.listUser:listUser·p0.999       sample         37.618           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         37.938           ms/op
ClientSimple.listUser:listUser·p1.00        sample         37.945           ms/op

Benchmark result is saved to 1715127187545.json
