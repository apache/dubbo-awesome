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
# Warmup Iteration   1: 1.941 ops/ms
Iteration   1: 6.591 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.591 ops/ms


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
# Warmup Iteration   1: 6.413 ops/ms
Iteration   1: 12.728 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.728 ops/ms


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
# Warmup Iteration   1: 5.855 ops/ms
Iteration   1: 13.663 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.663 ops/ms


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
# Warmup Iteration   1: 4.270 ops/ms
Iteration   1: 8.804 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.804 ops/ms


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
# Warmup Iteration   1: 3.594 ±(99.9%) 0.049 ms/op
Iteration   1: 2.064 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.064 ms/op


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
# Warmup Iteration   1: 3.032 ±(99.9%) 0.044 ms/op
Iteration   1: 1.946 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.946 ms/op


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
# Warmup Iteration   1: 3.121 ±(99.9%) 0.056 ms/op
Iteration   1: 1.995 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.995 ms/op


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
# Warmup Iteration   1: 4.336 ±(99.9%) 0.082 ms/op
Iteration   1: 3.506 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.506 ms/op


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
# Warmup Iteration   1: 3.587 ±(99.9%) 0.087 ms/op
Iteration   1: 1.941 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.749 ms/op
                 createUser·p0.50:   1.667 ms/op
                 createUser·p0.90:   2.519 ms/op
                 createUser·p0.95:   3.005 ms/op
                 createUser·p0.99:   5.833 ms/op
                 createUser·p0.999:  16.843 ms/op
                 createUser·p0.9999: 17.207 ms/op
                 createUser·p1.00:   17.334 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16466
  mean =      1.941 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 245 
    [ 1.250,  2.500) = 14492 
    [ 2.500,  3.750) = 1262 
    [ 3.750,  5.000) = 184 
    [ 5.000,  6.250) = 166 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 22 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.749 ms/op
     p(50.0000) =      1.667 ms/op
     p(90.0000) =      2.519 ms/op
     p(95.0000) =      3.005 ms/op
     p(99.0000) =      5.833 ms/op
     p(99.9000) =     16.843 ms/op
     p(99.9900) =     17.207 ms/op
     p(99.9990) =     17.334 ms/op
     p(99.9999) =     17.334 ms/op
    p(100.0000) =     17.334 ms/op


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
# Warmup Iteration   1: 3.035 ±(99.9%) 0.074 ms/op
Iteration   1: 1.827 ±(99.9%) 0.033 ms/op
                 existUser·p0.00:   0.578 ms/op
                 existUser·p0.50:   1.647 ms/op
                 existUser·p0.90:   2.224 ms/op
                 existUser·p0.95:   2.347 ms/op
                 existUser·p0.99:   3.539 ms/op
                 existUser·p0.999:  23.249 ms/op
                 existUser·p0.9999: 23.715 ms/op
                 existUser·p1.00:   24.379 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17505
  mean =      1.827 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17070 
    [ 2.500,  5.000) = 332 
    [ 5.000,  7.500) = 1 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.578 ms/op
     p(50.0000) =      1.647 ms/op
     p(90.0000) =      2.224 ms/op
     p(95.0000) =      2.347 ms/op
     p(99.0000) =      3.539 ms/op
     p(99.9000) =     23.249 ms/op
     p(99.9900) =     23.715 ms/op
     p(99.9990) =     24.379 ms/op
     p(99.9999) =     24.379 ms/op
    p(100.0000) =     24.379 ms/op


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
# Warmup Iteration   1: 3.319 ±(99.9%) 0.091 ms/op
Iteration   1: 2.106 ±(99.9%) 0.033 ms/op
                 getUser·p0.00:   0.443 ms/op
                 getUser·p0.50:   1.999 ms/op
                 getUser·p0.90:   2.552 ms/op
                 getUser·p0.95:   2.732 ms/op
                 getUser·p0.99:   3.718 ms/op
                 getUser·p0.999:  24.904 ms/op
                 getUser·p0.9999: 25.638 ms/op
                 getUser·p1.00:   25.723 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15167
  mean =      2.106 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13368 
    [ 2.500,  5.000) = 1667 
    [ 5.000,  7.500) = 65 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.443 ms/op
     p(50.0000) =      1.999 ms/op
     p(90.0000) =      2.552 ms/op
     p(95.0000) =      2.732 ms/op
     p(99.0000) =      3.718 ms/op
     p(99.9000) =     24.904 ms/op
     p(99.9900) =     25.638 ms/op
     p(99.9990) =     25.723 ms/op
     p(99.9999) =     25.723 ms/op
    p(100.0000) =     25.723 ms/op


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
# Warmup Iteration   1: 5.134 ±(99.9%) 0.232 ms/op
Iteration   1: 3.518 ±(99.9%) 0.059 ms/op
                 listUser·p0.00:   1.037 ms/op
                 listUser·p0.50:   3.404 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   7.241 ms/op
                 listUser·p0.999:  28.439 ms/op
                 listUser·p0.9999: 29.295 ms/op
                 listUser·p1.00:   29.295 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9113
  mean =      3.518 ±(99.9%) 0.059 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1150 
    [ 2.500,  5.000) = 7598 
    [ 5.000,  7.500) = 291 
    [ 7.500, 10.000) = 42 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.037 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      7.241 ms/op
     p(99.9000) =     28.439 ms/op
     p(99.9900) =     29.295 ms/op
     p(99.9990) =     29.295 ms/op
     p(99.9999) =     29.295 ms/op
    p(100.0000) =     29.295 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.591          ops/ms
ClientSimple.existUser                       thrpt         12.728          ops/ms
ClientSimple.getUser                         thrpt         13.663          ops/ms
ClientSimple.listUser                        thrpt          8.804          ops/ms
ClientSimple.createUser                       avgt          2.064           ms/op
ClientSimple.existUser                        avgt          1.946           ms/op
ClientSimple.getUser                          avgt          1.995           ms/op
ClientSimple.listUser                         avgt          3.506           ms/op
ClientSimple.createUser                     sample  16466   1.941 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.749           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.667           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.519           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.005           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.833           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.843           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.207           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.334           ms/op
ClientSimple.existUser                      sample  17505   1.827 ± 0.033   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.578           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.647           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.224           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.347           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.539           ms/op
ClientSimple.existUser:existUser·p0.999     sample         23.249           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         23.715           ms/op
ClientSimple.existUser:existUser·p1.00      sample         24.379           ms/op
ClientSimple.getUser                        sample  15167   2.106 ± 0.033   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.443           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.999           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.552           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.732           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.718           ms/op
ClientSimple.getUser:getUser·p0.999         sample         24.904           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         25.638           ms/op
ClientSimple.getUser:getUser·p1.00          sample         25.723           ms/op
ClientSimple.listUser                       sample   9113   3.518 ± 0.059   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.037           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.404           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.260           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.760           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.241           ms/op
ClientSimple.listUser:listUser·p0.999       sample         28.439           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         29.295           ms/op
ClientSimple.listUser:listUser·p1.00        sample         29.295           ms/op

Benchmark result is saved to 1719447374717.json
