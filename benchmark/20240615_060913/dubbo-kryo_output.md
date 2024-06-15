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
# Warmup Iteration   1: 1.904 ops/ms
Iteration   1: 7.628 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.628 ops/ms


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
# Warmup Iteration   1: 6.987 ops/ms
Iteration   1: 12.668 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.668 ops/ms


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
# Warmup Iteration   1: 6.388 ops/ms
Iteration   1: 14.353 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.353 ops/ms


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
# Warmup Iteration   1: 5.864 ops/ms
Iteration   1: 8.260 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.260 ops/ms


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
# Warmup Iteration   1: 3.459 ±(99.9%) 0.056 ms/op
Iteration   1: 2.445 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.445 ms/op


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
# Warmup Iteration   1: 3.510 ±(99.9%) 0.051 ms/op
Iteration   1: 2.068 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.068 ms/op


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
# Warmup Iteration   1: 3.301 ±(99.9%) 0.065 ms/op
Iteration   1: 2.361 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.361 ms/op


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
# Warmup Iteration   1: 4.060 ±(99.9%) 0.095 ms/op
Iteration   1: 3.451 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.451 ms/op


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
# Warmup Iteration   1: 3.836 ±(99.9%) 0.113 ms/op
Iteration   1: 2.444 ±(99.9%) 0.051 ms/op
                 createUser·p0.00:   0.743 ms/op
                 createUser·p0.50:   2.286 ms/op
                 createUser·p0.90:   2.937 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   6.949 ms/op
                 createUser·p0.999:  27.344 ms/op
                 createUser·p0.9999: 27.985 ms/op
                 createUser·p1.00:   28.017 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13268
  mean =      2.444 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8332 
    [ 2.500,  5.000) = 4772 
    [ 5.000,  7.500) = 33 
    [ 7.500, 10.000) = 35 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.743 ms/op
     p(50.0000) =      2.286 ms/op
     p(90.0000) =      2.937 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      6.949 ms/op
     p(99.9000) =     27.344 ms/op
     p(99.9900) =     27.985 ms/op
     p(99.9990) =     28.017 ms/op
     p(99.9999) =     28.017 ms/op
    p(100.0000) =     28.017 ms/op


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
# Warmup Iteration   1: 2.927 ±(99.9%) 0.064 ms/op
Iteration   1: 1.929 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.388 ms/op
                 existUser·p0.50:   1.905 ms/op
                 existUser·p0.90:   2.339 ms/op
                 existUser·p0.95:   2.482 ms/op
                 existUser·p0.99:   3.469 ms/op
                 existUser·p0.999:  20.493 ms/op
                 existUser·p0.9999: 22.961 ms/op
                 existUser·p1.00:   23.134 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16602
  mean =      1.929 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15822 
    [ 2.500,  5.000) = 717 
    [ 5.000,  7.500) = 31 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.388 ms/op
     p(50.0000) =      1.905 ms/op
     p(90.0000) =      2.339 ms/op
     p(95.0000) =      2.482 ms/op
     p(99.0000) =      3.469 ms/op
     p(99.9000) =     20.493 ms/op
     p(99.9900) =     22.961 ms/op
     p(99.9990) =     23.134 ms/op
     p(99.9999) =     23.134 ms/op
    p(100.0000) =     23.134 ms/op


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
# Warmup Iteration   1: 3.486 ±(99.9%) 0.090 ms/op
Iteration   1: 2.137 ±(99.9%) 0.036 ms/op
                 getUser·p0.00:   0.637 ms/op
                 getUser·p0.50:   1.901 ms/op
                 getUser·p0.90:   2.630 ms/op
                 getUser·p0.95:   3.027 ms/op
                 getUser·p0.99:   5.762 ms/op
                 getUser·p0.999:  25.563 ms/op
                 getUser·p0.9999: 26.264 ms/op
                 getUser·p1.00:   26.313 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14959
  mean =      2.137 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12812 
    [ 2.500,  5.000) = 1954 
    [ 5.000,  7.500) = 100 
    [ 7.500, 10.000) = 29 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.637 ms/op
     p(50.0000) =      1.901 ms/op
     p(90.0000) =      2.630 ms/op
     p(95.0000) =      3.027 ms/op
     p(99.0000) =      5.762 ms/op
     p(99.9000) =     25.563 ms/op
     p(99.9900) =     26.264 ms/op
     p(99.9990) =     26.313 ms/op
     p(99.9999) =     26.313 ms/op
    p(100.0000) =     26.313 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.265 ±(99.9%) 0.113 ms/op
Iteration   1: 3.581 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.065 ms/op
                 listUser·p0.50:   3.547 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.727 ms/op
                 listUser·p0.99:   6.234 ms/op
                 listUser·p0.999:  7.735 ms/op
                 listUser·p0.9999: 9.126 ms/op
                 listUser·p1.00:   9.126 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8922
  mean =      3.581 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 15 
    [ 1.500,  2.000) = 80 
    [ 2.000,  2.500) = 262 
    [ 2.500,  3.000) = 1823 
    [ 3.000,  3.500) = 2100 
    [ 3.500,  4.000) = 2232 
    [ 4.000,  4.500) = 1746 
    [ 4.500,  5.000) = 336 
    [ 5.000,  5.500) = 151 
    [ 5.500,  6.000) = 53 
    [ 6.000,  6.500) = 51 
    [ 6.500,  7.000) = 19 
    [ 7.000,  7.500) = 33 
    [ 7.500,  8.000) = 19 
    [ 8.000,  8.500) = 1 
    [ 8.500,  9.000) = 0 
    [ 9.000,  9.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.065 ms/op
     p(50.0000) =      3.547 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      6.234 ms/op
     p(99.9000) =      7.735 ms/op
     p(99.9900) =      9.126 ms/op
     p(99.9990) =      9.126 ms/op
     p(99.9999) =      9.126 ms/op
    p(100.0000) =      9.126 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.628          ops/ms
ClientSimple.existUser                       thrpt         12.668          ops/ms
ClientSimple.getUser                         thrpt         14.353          ops/ms
ClientSimple.listUser                        thrpt          8.260          ops/ms
ClientSimple.createUser                       avgt          2.445           ms/op
ClientSimple.existUser                        avgt          2.068           ms/op
ClientSimple.getUser                          avgt          2.361           ms/op
ClientSimple.listUser                         avgt          3.451           ms/op
ClientSimple.createUser                     sample  13268   2.444 ± 0.051   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.743           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.286           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.937           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.121           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.949           ms/op
ClientSimple.createUser:createUser·p0.999   sample         27.344           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         27.985           ms/op
ClientSimple.createUser:createUser·p1.00    sample         28.017           ms/op
ClientSimple.existUser                      sample  16602   1.929 ± 0.024   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.388           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.905           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.339           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.482           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.469           ms/op
ClientSimple.existUser:existUser·p0.999     sample         20.493           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         22.961           ms/op
ClientSimple.existUser:existUser·p1.00      sample         23.134           ms/op
ClientSimple.getUser                        sample  14959   2.137 ± 0.036   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.637           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.901           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.630           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.027           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.762           ms/op
ClientSimple.getUser:getUser·p0.999         sample         25.563           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         26.264           ms/op
ClientSimple.getUser:getUser·p1.00          sample         26.313           ms/op
ClientSimple.listUser                       sample   8922   3.581 ± 0.027   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.065           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.547           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.375           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.727           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.234           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.735           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.126           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.126           ms/op

Benchmark result is saved to 1718431510286.json
