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
# Warmup Iteration   1: 1.959 ops/ms
Iteration   1: 7.318 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.318 ops/ms


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
# Warmup Iteration   1: 5.823 ops/ms
Iteration   1: 13.936 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.936 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.563 ops/ms
Iteration   1: 12.707 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.707 ops/ms


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
# Warmup Iteration   1: 5.957 ops/ms
Iteration   1: 8.358 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.358 ops/ms


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
# Warmup Iteration   1: 3.811 ±(99.9%) 0.083 ms/op
Iteration   1: 2.347 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.347 ms/op


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
# Warmup Iteration   1: 3.259 ±(99.9%) 0.058 ms/op
Iteration   1: 1.870 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.870 ms/op


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
# Warmup Iteration   1: 3.245 ±(99.9%) 0.062 ms/op
Iteration   1: 1.952 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.952 ms/op


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
# Warmup Iteration   1: 4.380 ±(99.9%) 0.090 ms/op
Iteration   1: 3.257 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.257 ms/op


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
# Warmup Iteration   1: 3.813 ±(99.9%) 0.107 ms/op
Iteration   1: 2.260 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.356 ms/op
                 createUser·p0.50:   2.150 ms/op
                 createUser·p0.90:   2.728 ms/op
                 createUser·p0.95:   2.982 ms/op
                 createUser·p0.99:   10.355 ms/op
                 createUser·p0.999:  13.910 ms/op
                 createUser·p0.9999: 13.959 ms/op
                 createUser·p1.00:   13.959 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14170
  mean =      2.260 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 675 
    [ 1.250,  2.500) = 10578 
    [ 2.500,  3.750) = 2559 
    [ 3.750,  5.000) = 72 
    [ 5.000,  6.250) = 46 
    [ 6.250,  7.500) = 41 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 11 
    [10.000, 11.250) = 51 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.356 ms/op
     p(50.0000) =      2.150 ms/op
     p(90.0000) =      2.728 ms/op
     p(95.0000) =      2.982 ms/op
     p(99.0000) =     10.355 ms/op
     p(99.9000) =     13.910 ms/op
     p(99.9900) =     13.959 ms/op
     p(99.9990) =     13.959 ms/op
     p(99.9999) =     13.959 ms/op
    p(100.0000) =     13.959 ms/op


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
# Warmup Iteration   1: 2.743 ±(99.9%) 0.063 ms/op
Iteration   1: 1.902 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   0.555 ms/op
                 existUser·p0.50:   1.769 ms/op
                 existUser·p0.90:   2.388 ms/op
                 existUser·p0.95:   2.564 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  22.540 ms/op
                 existUser·p0.9999: 23.144 ms/op
                 existUser·p1.00:   23.167 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17039
  mean =      1.902 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15989 
    [ 2.500,  5.000) = 951 
    [ 5.000,  7.500) = 29 
    [ 7.500, 10.000) = 6 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.555 ms/op
     p(50.0000) =      1.769 ms/op
     p(90.0000) =      2.388 ms/op
     p(95.0000) =      2.564 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =     22.540 ms/op
     p(99.9900) =     23.144 ms/op
     p(99.9990) =     23.167 ms/op
     p(99.9999) =     23.167 ms/op
    p(100.0000) =     23.167 ms/op


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
# Warmup Iteration   1: 3.234 ±(99.9%) 0.082 ms/op
Iteration   1: 1.831 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.776 ms/op
                 getUser·p0.50:   1.753 ms/op
                 getUser·p0.90:   2.286 ms/op
                 getUser·p0.95:   2.466 ms/op
                 getUser·p0.99:   3.040 ms/op
                 getUser·p0.999:  17.760 ms/op
                 getUser·p0.9999: 17.924 ms/op
                 getUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17471
  mean =      1.831 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 697 
    [ 1.250,  2.500) = 16023 
    [ 2.500,  3.750) = 633 
    [ 3.750,  5.000) = 39 
    [ 5.000,  6.250) = 15 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.776 ms/op
     p(50.0000) =      1.753 ms/op
     p(90.0000) =      2.286 ms/op
     p(95.0000) =      2.466 ms/op
     p(99.0000) =      3.040 ms/op
     p(99.9000) =     17.760 ms/op
     p(99.9900) =     17.924 ms/op
     p(99.9990) =     17.924 ms/op
     p(99.9999) =     17.924 ms/op
    p(100.0000) =     17.924 ms/op


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
# Warmup Iteration   1: 4.169 ±(99.9%) 0.126 ms/op
Iteration   1: 3.804 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   1.307 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   4.686 ms/op
                 listUser·p0.99:   5.438 ms/op
                 listUser·p0.999:  13.831 ms/op
                 listUser·p0.9999: 13.992 ms/op
                 listUser·p1.00:   13.992 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8416
  mean =      3.804 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 418 
    [ 2.500,  3.750) = 3277 
    [ 3.750,  5.000) = 4568 
    [ 5.000,  6.250) = 115 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.307 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      5.438 ms/op
     p(99.9000) =     13.831 ms/op
     p(99.9900) =     13.992 ms/op
     p(99.9990) =     13.992 ms/op
     p(99.9999) =     13.992 ms/op
    p(100.0000) =     13.992 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.318          ops/ms
ClientSimple.existUser                       thrpt         13.936          ops/ms
ClientSimple.getUser                         thrpt         12.707          ops/ms
ClientSimple.listUser                        thrpt          8.358          ops/ms
ClientSimple.createUser                       avgt          2.347           ms/op
ClientSimple.existUser                        avgt          1.870           ms/op
ClientSimple.getUser                          avgt          1.952           ms/op
ClientSimple.listUser                         avgt          3.257           ms/op
ClientSimple.createUser                     sample  14170   2.260 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.356           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.150           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.728           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.982           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.355           ms/op
ClientSimple.createUser:createUser·p0.999   sample         13.910           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         13.959           ms/op
ClientSimple.createUser:createUser·p1.00    sample         13.959           ms/op
ClientSimple.existUser                      sample  17039   1.902 ± 0.028   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.555           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.769           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.388           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.564           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.252           ms/op
ClientSimple.existUser:existUser·p0.999     sample         22.540           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         23.144           ms/op
ClientSimple.existUser:existUser·p1.00      sample         23.167           ms/op
ClientSimple.getUser                        sample  17471   1.831 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.776           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.753           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.286           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.466           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.040           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.760           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.924           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.924           ms/op
ClientSimple.listUser                       sample   8416   3.804 ± 0.032   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.307           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.834           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.530           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.686           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.438           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.831           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         13.992           ms/op
ClientSimple.listUser:listUser·p1.00        sample         13.992           ms/op

Benchmark result is saved to 1715083570634.json
