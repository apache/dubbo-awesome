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
# Warmup Iteration   1: 1.862 ops/ms
Iteration   1: 7.244 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.244 ops/ms


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
# Warmup Iteration   1: 6.075 ops/ms
Iteration   1: 12.533 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.533 ops/ms


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
# Warmup Iteration   1: 5.504 ops/ms
Iteration   1: 12.348 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.348 ops/ms


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
# Warmup Iteration   1: 4.038 ops/ms
Iteration   1: 8.960 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.960 ops/ms


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
# Warmup Iteration   1: 3.699 ±(99.9%) 0.064 ms/op
Iteration   1: 2.024 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.024 ms/op


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
# Warmup Iteration   1: 3.165 ±(99.9%) 0.052 ms/op
Iteration   1: 1.954 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.954 ms/op


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
# Warmup Iteration   1: 3.224 ±(99.9%) 0.056 ms/op
Iteration   1: 1.926 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.926 ms/op


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
# Warmup Iteration   1: 4.374 ±(99.9%) 0.094 ms/op
Iteration   1: 3.715 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.715 ms/op


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
# Warmup Iteration   1: 3.472 ±(99.9%) 0.099 ms/op
Iteration   1: 2.151 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.555 ms/op
                 createUser·p0.50:   1.952 ms/op
                 createUser·p0.90:   2.753 ms/op
                 createUser·p0.95:   2.941 ms/op
                 createUser·p0.99:   3.826 ms/op
                 createUser·p0.999:  22.166 ms/op
                 createUser·p0.9999: 24.548 ms/op
                 createUser·p1.00:   24.740 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14886
  mean =      2.151 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11684 
    [ 2.500,  5.000) = 3096 
    [ 5.000,  7.500) = 74 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.555 ms/op
     p(50.0000) =      1.952 ms/op
     p(90.0000) =      2.753 ms/op
     p(95.0000) =      2.941 ms/op
     p(99.0000) =      3.826 ms/op
     p(99.9000) =     22.166 ms/op
     p(99.9900) =     24.548 ms/op
     p(99.9990) =     24.740 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


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
# Warmup Iteration   1: 2.830 ±(99.9%) 0.060 ms/op
Iteration   1: 1.824 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.654 ms/op
                 existUser·p0.50:   1.706 ms/op
                 existUser·p0.90:   2.232 ms/op
                 existUser·p0.95:   2.421 ms/op
                 existUser·p0.99:   2.974 ms/op
                 existUser·p0.999:  17.349 ms/op
                 existUser·p0.9999: 17.531 ms/op
                 existUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17542
  mean =      1.824 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 506 
    [ 1.250,  2.500) = 16348 
    [ 2.500,  3.750) = 577 
    [ 3.750,  5.000) = 57 
    [ 5.000,  6.250) = 18 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.654 ms/op
     p(50.0000) =      1.706 ms/op
     p(90.0000) =      2.232 ms/op
     p(95.0000) =      2.421 ms/op
     p(99.0000) =      2.974 ms/op
     p(99.9000) =     17.349 ms/op
     p(99.9900) =     17.531 ms/op
     p(99.9990) =     17.531 ms/op
     p(99.9999) =     17.531 ms/op
    p(100.0000) =     17.531 ms/op


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
# Warmup Iteration   1: 3.052 ±(99.9%) 0.074 ms/op
Iteration   1: 2.093 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.625 ms/op
                 getUser·p0.50:   2.095 ms/op
                 getUser·p0.90:   2.552 ms/op
                 getUser·p0.95:   2.687 ms/op
                 getUser·p0.99:   3.344 ms/op
                 getUser·p0.999:  5.361 ms/op
                 getUser·p0.9999: 7.671 ms/op
                 getUser·p1.00:   7.922 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15277
  mean =      2.093 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 140 
    [1.000, 1.500) = 797 
    [1.500, 2.000) = 5062 
    [2.000, 2.500) = 7336 
    [2.500, 3.000) = 1685 
    [3.000, 3.500) = 137 
    [3.500, 4.000) = 72 
    [4.000, 4.500) = 24 
    [4.500, 5.000) = 4 
    [5.000, 5.500) = 6 
    [5.500, 6.000) = 3 
    [6.000, 6.500) = 4 
    [6.500, 7.000) = 0 
    [7.000, 7.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.625 ms/op
     p(50.0000) =      2.095 ms/op
     p(90.0000) =      2.552 ms/op
     p(95.0000) =      2.687 ms/op
     p(99.0000) =      3.344 ms/op
     p(99.9000) =      5.361 ms/op
     p(99.9900) =      7.671 ms/op
     p(99.9990) =      7.922 ms/op
     p(99.9999) =      7.922 ms/op
    p(100.0000) =      7.922 ms/op


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
# Warmup Iteration   1: 4.503 ±(99.9%) 0.114 ms/op
Iteration   1: 3.203 ±(99.9%) 0.051 ms/op
                 listUser·p0.00:   1.055 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   4.056 ms/op
                 listUser·p0.95:   4.351 ms/op
                 listUser·p0.99:   6.500 ms/op
                 listUser·p0.999:  26.051 ms/op
                 listUser·p0.9999: 26.706 ms/op
                 listUser·p1.00:   26.706 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9997
  mean =      3.203 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1202 
    [ 2.500,  5.000) = 8603 
    [ 5.000,  7.500) = 101 
    [ 7.500, 10.000) = 27 
    [10.000, 12.500) = 15 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.055 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      4.056 ms/op
     p(95.0000) =      4.351 ms/op
     p(99.0000) =      6.500 ms/op
     p(99.9000) =     26.051 ms/op
     p(99.9900) =     26.706 ms/op
     p(99.9990) =     26.706 ms/op
     p(99.9999) =     26.706 ms/op
    p(100.0000) =     26.706 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.244          ops/ms
ClientSimple.existUser                       thrpt         12.533          ops/ms
ClientSimple.getUser                         thrpt         12.348          ops/ms
ClientSimple.listUser                        thrpt          8.960          ops/ms
ClientSimple.createUser                       avgt          2.024           ms/op
ClientSimple.existUser                        avgt          1.954           ms/op
ClientSimple.getUser                          avgt          1.926           ms/op
ClientSimple.listUser                         avgt          3.715           ms/op
ClientSimple.createUser                     sample  14886   2.151 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.555           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.952           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.753           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.941           ms/op
ClientSimple.createUser:createUser·p0.99    sample          3.826           ms/op
ClientSimple.createUser:createUser·p0.999   sample         22.166           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         24.548           ms/op
ClientSimple.createUser:createUser·p1.00    sample         24.740           ms/op
ClientSimple.existUser                      sample  17542   1.824 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.654           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.706           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.232           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.421           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.974           ms/op
ClientSimple.existUser:existUser·p0.999     sample         17.349           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.531           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.531           ms/op
ClientSimple.getUser                        sample  15277   2.093 ± 0.012   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.625           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.095           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.552           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.687           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.344           ms/op
ClientSimple.getUser:getUser·p0.999         sample          5.361           ms/op
ClientSimple.getUser:getUser·p0.9999        sample          7.671           ms/op
ClientSimple.getUser:getUser·p1.00          sample          7.922           ms/op
ClientSimple.listUser                       sample   9997   3.203 ± 0.051   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.055           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.929           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.056           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.351           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.500           ms/op
ClientSimple.listUser:listUser·p0.999       sample         26.051           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         26.706           ms/op
ClientSimple.listUser:listUser·p1.00        sample         26.706           ms/op

Benchmark result is saved to 1715256374807.json
