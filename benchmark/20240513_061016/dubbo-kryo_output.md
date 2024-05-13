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
# Warmup Iteration   1: 1.244 ops/ms
Iteration   1: 6.806 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.806 ops/ms


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
# Warmup Iteration   1: 6.202 ops/ms
Iteration   1: 13.011 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.011 ops/ms


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
# Warmup Iteration   1: 6.229 ops/ms
Iteration   1: 14.228 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.228 ops/ms


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
# Warmup Iteration   1: 4.544 ops/ms
Iteration   1: 7.043 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.043 ops/ms


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
# Warmup Iteration   1: 3.996 ±(99.9%) 0.089 ms/op
Iteration   1: 2.238 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.238 ms/op


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
# Warmup Iteration   1: 3.171 ±(99.9%) 0.071 ms/op
Iteration   1: 2.066 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.066 ms/op


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
# Warmup Iteration   1: 3.260 ±(99.9%) 0.064 ms/op
Iteration   1: 2.178 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.178 ms/op


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
# Warmup Iteration   1: 4.519 ±(99.9%) 0.134 ms/op
Iteration   1: 3.807 ±(99.9%) 0.037 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.807 ms/op


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
# Warmup Iteration   1: 3.474 ±(99.9%) 0.094 ms/op
Iteration   1: 2.083 ±(99.9%) 0.049 ms/op
                 createUser·p0.00:   0.799 ms/op
                 createUser·p0.50:   1.690 ms/op
                 createUser·p0.90:   2.879 ms/op
                 createUser·p0.95:   3.068 ms/op
                 createUser·p0.99:   5.315 ms/op
                 createUser·p0.999:  32.002 ms/op
                 createUser·p0.9999: 37.115 ms/op
                 createUser·p1.00:   37.290 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15343
  mean =      2.083 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12213 
    [ 2.500,  5.000) = 2969 
    [ 5.000,  7.500) = 33 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.799 ms/op
     p(50.0000) =      1.690 ms/op
     p(90.0000) =      2.879 ms/op
     p(95.0000) =      3.068 ms/op
     p(99.0000) =      5.315 ms/op
     p(99.9000) =     32.002 ms/op
     p(99.9900) =     37.115 ms/op
     p(99.9990) =     37.290 ms/op
     p(99.9999) =     37.290 ms/op
    p(100.0000) =     37.290 ms/op


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
# Warmup Iteration   1: 2.858 ±(99.9%) 0.064 ms/op
Iteration   1: 1.680 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.560 ms/op
                 existUser·p0.50:   1.556 ms/op
                 existUser·p0.90:   2.130 ms/op
                 existUser·p0.95:   2.343 ms/op
                 existUser·p0.99:   3.432 ms/op
                 existUser·p0.999:  14.919 ms/op
                 existUser·p0.9999: 16.566 ms/op
                 existUser·p1.00:   16.597 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 19409
  mean =      1.680 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1646 
    [ 1.250,  2.500) = 17162 
    [ 2.500,  3.750) = 434 
    [ 3.750,  5.000) = 86 
    [ 5.000,  6.250) = 49 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.560 ms/op
     p(50.0000) =      1.556 ms/op
     p(90.0000) =      2.130 ms/op
     p(95.0000) =      2.343 ms/op
     p(99.0000) =      3.432 ms/op
     p(99.9000) =     14.919 ms/op
     p(99.9900) =     16.566 ms/op
     p(99.9990) =     16.597 ms/op
     p(99.9999) =     16.597 ms/op
    p(100.0000) =     16.597 ms/op


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
# Warmup Iteration   1: 3.581 ±(99.9%) 0.084 ms/op
Iteration   1: 2.126 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   1.112 ms/op
                 getUser·p0.50:   1.948 ms/op
                 getUser·p0.90:   2.580 ms/op
                 getUser·p0.95:   2.839 ms/op
                 getUser·p0.99:   4.766 ms/op
                 getUser·p0.999:  15.925 ms/op
                 getUser·p0.9999: 15.958 ms/op
                 getUser·p1.00:   15.958 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15040
  mean =      2.126 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 13142 
    [ 2.500,  3.750) = 1667 
    [ 3.750,  5.000) = 77 
    [ 5.000,  6.250) = 39 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.112 ms/op
     p(50.0000) =      1.948 ms/op
     p(90.0000) =      2.580 ms/op
     p(95.0000) =      2.839 ms/op
     p(99.0000) =      4.766 ms/op
     p(99.9000) =     15.925 ms/op
     p(99.9900) =     15.958 ms/op
     p(99.9990) =     15.958 ms/op
     p(99.9999) =     15.958 ms/op
    p(100.0000) =     15.958 ms/op


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
# Warmup Iteration   1: 4.761 ±(99.9%) 0.131 ms/op
Iteration   1: 3.351 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   0.810 ms/op
                 listUser·p0.50:   3.195 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   5.674 ms/op
                 listUser·p0.999:  8.363 ms/op
                 listUser·p0.9999: 8.471 ms/op
                 listUser·p1.00:   8.471 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9538
  mean =      3.351 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 2 
    [1.000, 1.500) = 10 
    [1.500, 2.000) = 77 
    [2.000, 2.500) = 1190 
    [2.500, 3.000) = 2783 
    [3.000, 3.500) = 1521 
    [3.500, 4.000) = 1893 
    [4.000, 4.500) = 1196 
    [4.500, 5.000) = 573 
    [5.000, 5.500) = 168 
    [5.500, 6.000) = 66 
    [6.000, 6.500) = 14 
    [6.500, 7.000) = 2 
    [7.000, 7.500) = 9 
    [7.500, 8.000) = 4 
    [8.000, 8.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.810 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      5.674 ms/op
     p(99.9000) =      8.363 ms/op
     p(99.9900) =      8.471 ms/op
     p(99.9990) =      8.471 ms/op
     p(99.9999) =      8.471 ms/op
    p(100.0000) =      8.471 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.806          ops/ms
ClientSimple.existUser                       thrpt         13.011          ops/ms
ClientSimple.getUser                         thrpt         14.228          ops/ms
ClientSimple.listUser                        thrpt          7.043          ops/ms
ClientSimple.createUser                       avgt          2.238           ms/op
ClientSimple.existUser                        avgt          2.066           ms/op
ClientSimple.getUser                          avgt          2.178           ms/op
ClientSimple.listUser                         avgt          3.807           ms/op
ClientSimple.createUser                     sample  15343   2.083 ± 0.049   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.799           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.690           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.879           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.068           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.315           ms/op
ClientSimple.createUser:createUser·p0.999   sample         32.002           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         37.115           ms/op
ClientSimple.createUser:createUser·p1.00    sample         37.290           ms/op
ClientSimple.existUser                      sample  19409   1.680 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.560           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.556           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.130           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.343           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.432           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.919           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.566           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.597           ms/op
ClientSimple.getUser                        sample  15040   2.126 ± 0.026   ms/op
ClientSimple.getUser:getUser·p0.00          sample          1.112           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.948           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.580           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.839           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.766           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.925           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.958           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.958           ms/op
ClientSimple.listUser                       sample   9538   3.351 ± 0.029   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.810           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.195           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.456           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.776           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.674           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.363           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.471           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.471           ms/op

Benchmark result is saved to 1715580351140.json
