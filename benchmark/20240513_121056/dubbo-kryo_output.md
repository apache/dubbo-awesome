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
# Warmup Iteration   1: 1.882 ops/ms
Iteration   1: 6.855 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.855 ops/ms


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
# Warmup Iteration   1: 5.500 ops/ms
Iteration   1: 13.419 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.419 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 5.174 ops/ms
Iteration   1: 12.136 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.136 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 4.210 ops/ms
Iteration   1: 8.159 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.159 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 4.062 ±(99.9%) 0.091 ms/op
Iteration   1: 2.258 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.258 ms/op


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
# Warmup Iteration   1: 2.961 ±(99.9%) 0.044 ms/op
Iteration   1: 1.959 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.959 ms/op


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
# Warmup Iteration   1: 3.187 ±(99.9%) 0.050 ms/op
Iteration   1: 1.836 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.836 ms/op


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
# Warmup Iteration   1: 4.255 ±(99.9%) 0.093 ms/op
Iteration   1: 3.452 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.452 ms/op


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
# Warmup Iteration   1: 3.731 ±(99.9%) 0.089 ms/op
Iteration   1: 1.994 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   0.868 ms/op
                 createUser·p0.50:   1.808 ms/op
                 createUser·p0.90:   2.486 ms/op
                 createUser·p0.95:   2.720 ms/op
                 createUser·p0.99:   3.289 ms/op
                 createUser·p0.999:  16.073 ms/op
                 createUser·p0.9999: 17.316 ms/op
                 createUser·p1.00:   18.055 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16092
  mean =      1.994 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 14508 
    [ 2.500,  3.750) = 1417 
    [ 3.750,  5.000) = 28 
    [ 5.000,  6.250) = 37 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.868 ms/op
     p(50.0000) =      1.808 ms/op
     p(90.0000) =      2.486 ms/op
     p(95.0000) =      2.720 ms/op
     p(99.0000) =      3.289 ms/op
     p(99.9000) =     16.073 ms/op
     p(99.9900) =     17.316 ms/op
     p(99.9990) =     18.055 ms/op
     p(99.9999) =     18.055 ms/op
    p(100.0000) =     18.055 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.018 ±(99.9%) 0.084 ms/op
Iteration   1: 1.994 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   0.381 ms/op
                 existUser·p0.50:   1.878 ms/op
                 existUser·p0.90:   2.515 ms/op
                 existUser·p0.95:   2.671 ms/op
                 existUser·p0.99:   5.033 ms/op
                 existUser·p0.999:  19.591 ms/op
                 existUser·p0.9999: 19.797 ms/op
                 existUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16118
  mean =      1.994 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 606 
    [ 1.250,  2.500) = 13762 
    [ 2.500,  3.750) = 1511 
    [ 3.750,  5.000) = 76 
    [ 5.000,  6.250) = 66 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.381 ms/op
     p(50.0000) =      1.878 ms/op
     p(90.0000) =      2.515 ms/op
     p(95.0000) =      2.671 ms/op
     p(99.0000) =      5.033 ms/op
     p(99.9000) =     19.591 ms/op
     p(99.9900) =     19.797 ms/op
     p(99.9990) =     19.857 ms/op
     p(99.9999) =     19.857 ms/op
    p(100.0000) =     19.857 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 3.370 ±(99.9%) 0.080 ms/op
Iteration   1: 1.930 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.448 ms/op
                 getUser·p0.50:   1.835 ms/op
                 getUser·p0.90:   2.376 ms/op
                 getUser·p0.95:   2.605 ms/op
                 getUser·p0.99:   3.456 ms/op
                 getUser·p0.999:  11.452 ms/op
                 getUser·p0.9999: 11.816 ms/op
                 getUser·p1.00:   12.190 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16711
  mean =      1.930 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 179 
    [ 1.250,  2.500) = 15274 
    [ 2.500,  3.750) = 1116 
    [ 3.750,  5.000) = 90 
    [ 5.000,  6.250) = 14 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.448 ms/op
     p(50.0000) =      1.835 ms/op
     p(90.0000) =      2.376 ms/op
     p(95.0000) =      2.605 ms/op
     p(99.0000) =      3.456 ms/op
     p(99.9000) =     11.452 ms/op
     p(99.9900) =     11.816 ms/op
     p(99.9990) =     12.190 ms/op
     p(99.9999) =     12.190 ms/op
    p(100.0000) =     12.190 ms/op


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
# Warmup Iteration   1: 4.197 ±(99.9%) 0.148 ms/op
Iteration   1: 3.636 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.401 ms/op
                 listUser·p0.50:   3.572 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   4.803 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  7.115 ms/op
                 listUser·p0.9999: 8.552 ms/op
                 listUser·p1.00:   8.552 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8792
  mean =      3.636 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 3 
    [1.500, 2.000) = 40 
    [2.000, 2.500) = 158 
    [2.500, 3.000) = 1788 
    [3.000, 3.500) = 2120 
    [3.500, 4.000) = 1898 
    [4.000, 4.500) = 1758 
    [4.500, 5.000) = 718 
    [5.000, 5.500) = 210 
    [5.500, 6.000) = 50 
    [6.000, 6.500) = 24 
    [6.500, 7.000) = 13 
    [7.000, 7.500) = 9 
    [7.500, 8.000) = 2 
    [8.000, 8.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.401 ms/op
     p(50.0000) =      3.572 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      4.803 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =      7.115 ms/op
     p(99.9900) =      8.552 ms/op
     p(99.9990) =      8.552 ms/op
     p(99.9999) =      8.552 ms/op
    p(100.0000) =      8.552 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.855          ops/ms
ClientSimple.existUser                       thrpt         13.419          ops/ms
ClientSimple.getUser                         thrpt         12.136          ops/ms
ClientSimple.listUser                        thrpt          8.159          ops/ms
ClientSimple.createUser                       avgt          2.258           ms/op
ClientSimple.existUser                        avgt          1.959           ms/op
ClientSimple.getUser                          avgt          1.836           ms/op
ClientSimple.listUser                         avgt          3.452           ms/op
ClientSimple.createUser                     sample  16092   1.994 ± 0.022   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.868           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.808           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.486           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.720           ms/op
ClientSimple.createUser:createUser·p0.99    sample          3.289           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.073           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.316           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.055           ms/op
ClientSimple.existUser                      sample  16118   1.994 ± 0.028   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.381           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.878           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.515           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.671           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.033           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.591           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.797           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.857           ms/op
ClientSimple.getUser                        sample  16711   1.930 ± 0.015   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.448           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.835           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.376           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.605           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.456           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.452           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.816           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.190           ms/op
ClientSimple.listUser                       sample   8792   3.636 ± 0.026   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.401           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.572           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.588           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.803           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.595           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.115           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.552           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.552           ms/op

Benchmark result is saved to 1715601985188.json
