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
# Warmup Iteration   1: 1.658 ops/ms
Iteration   1: 6.233 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.233 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.912 ops/ms
Iteration   1: 10.830 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.830 ops/ms


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
# Warmup Iteration   1: 5.511 ops/ms
Iteration   1: 11.599 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.599 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.468 ops/ms
Iteration   1: 7.908 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.908 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.704 ±(99.9%) 0.091 ms/op
Iteration   1: 2.153 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.153 ms/op


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
# Warmup Iteration   1: 3.205 ±(99.9%) 0.054 ms/op
Iteration   1: 1.992 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.992 ms/op


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
# Warmup Iteration   1: 3.508 ±(99.9%) 0.080 ms/op
Iteration   1: 1.942 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.942 ms/op


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
# Warmup Iteration   1: 6.442 ±(99.9%) 0.130 ms/op
Iteration   1: 3.871 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.871 ms/op


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
# Warmup Iteration   1: 4.111 ±(99.9%) 0.122 ms/op
Iteration   1: 2.326 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.925 ms/op
                 createUser·p0.50:   2.118 ms/op
                 createUser·p0.90:   2.716 ms/op
                 createUser·p0.95:   2.941 ms/op
                 createUser·p0.99:   6.306 ms/op
                 createUser·p0.999:  19.997 ms/op
                 createUser·p0.9999: 22.544 ms/op
                 createUser·p1.00:   22.544 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13738
  mean =      2.326 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11301 
    [ 2.500,  5.000) = 2240 
    [ 5.000,  7.500) = 69 
    [ 7.500, 10.000) = 36 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.925 ms/op
     p(50.0000) =      2.118 ms/op
     p(90.0000) =      2.716 ms/op
     p(95.0000) =      2.941 ms/op
     p(99.0000) =      6.306 ms/op
     p(99.9000) =     19.997 ms/op
     p(99.9900) =     22.544 ms/op
     p(99.9990) =     22.544 ms/op
     p(99.9999) =     22.544 ms/op
    p(100.0000) =     22.544 ms/op


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
# Warmup Iteration   1: 3.793 ±(99.9%) 0.110 ms/op
Iteration   1: 2.069 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.616 ms/op
                 existUser·p0.50:   1.815 ms/op
                 existUser·p0.90:   2.838 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   3.962 ms/op
                 existUser·p0.999:  12.927 ms/op
                 existUser·p0.9999: 14.056 ms/op
                 existUser·p1.00:   14.074 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15481
  mean =      2.069 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 144 
    [ 1.250,  2.500) = 12172 
    [ 2.500,  3.750) = 2893 
    [ 3.750,  5.000) = 165 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 42 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.616 ms/op
     p(50.0000) =      1.815 ms/op
     p(90.0000) =      2.838 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.962 ms/op
     p(99.9000) =     12.927 ms/op
     p(99.9900) =     14.056 ms/op
     p(99.9990) =     14.074 ms/op
     p(99.9999) =     14.074 ms/op
    p(100.0000) =     14.074 ms/op


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
# Warmup Iteration   1: 3.876 ±(99.9%) 0.113 ms/op
Iteration   1: 2.107 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.705 ms/op
                 getUser·p0.50:   1.917 ms/op
                 getUser·p0.90:   2.630 ms/op
                 getUser·p0.95:   2.941 ms/op
                 getUser·p0.99:   4.389 ms/op
                 getUser·p0.999:  19.518 ms/op
                 getUser·p0.9999: 20.430 ms/op
                 getUser·p1.00:   20.447 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15173
  mean =      2.107 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13125 
    [ 2.500,  5.000) = 1902 
    [ 5.000,  7.500) = 114 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.705 ms/op
     p(50.0000) =      1.917 ms/op
     p(90.0000) =      2.630 ms/op
     p(95.0000) =      2.941 ms/op
     p(99.0000) =      4.389 ms/op
     p(99.9000) =     19.518 ms/op
     p(99.9900) =     20.430 ms/op
     p(99.9990) =     20.447 ms/op
     p(99.9999) =     20.447 ms/op
    p(100.0000) =     20.447 ms/op


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
# Warmup Iteration   1: 6.747 ±(99.9%) 0.247 ms/op
Iteration   1: 4.119 ±(99.9%) 0.038 ms/op
                 listUser·p0.00:   1.548 ms/op
                 listUser·p0.50:   4.055 ms/op
                 listUser·p0.90:   4.916 ms/op
                 listUser·p0.95:   5.501 ms/op
                 listUser·p0.99:   7.160 ms/op
                 listUser·p0.999:  12.734 ms/op
                 listUser·p0.9999: 14.713 ms/op
                 listUser·p1.00:   14.713 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 7768
  mean =      4.119 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 87 
    [ 2.500,  3.750) = 2418 
    [ 3.750,  5.000) = 4582 
    [ 5.000,  6.250) = 428 
    [ 6.250,  7.500) = 205 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.548 ms/op
     p(50.0000) =      4.055 ms/op
     p(90.0000) =      4.916 ms/op
     p(95.0000) =      5.501 ms/op
     p(99.0000) =      7.160 ms/op
     p(99.9000) =     12.734 ms/op
     p(99.9900) =     14.713 ms/op
     p(99.9990) =     14.713 ms/op
     p(99.9999) =     14.713 ms/op
    p(100.0000) =     14.713 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.233          ops/ms
ClientSimple.existUser                       thrpt         10.830          ops/ms
ClientSimple.getUser                         thrpt         11.599          ops/ms
ClientSimple.listUser                        thrpt          7.908          ops/ms
ClientSimple.createUser                       avgt          2.153           ms/op
ClientSimple.existUser                        avgt          1.992           ms/op
ClientSimple.getUser                          avgt          1.942           ms/op
ClientSimple.listUser                         avgt          3.871           ms/op
ClientSimple.createUser                     sample  13738   2.326 ± 0.036   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.925           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.118           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.716           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.941           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.306           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.997           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.544           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.544           ms/op
ClientSimple.existUser                      sample  15481   2.069 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.616           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.815           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.838           ms/op
ClientSimple.existUser:existUser·p0.95      sample          3.146           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.962           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.927           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.056           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.074           ms/op
ClientSimple.getUser                        sample  15173   2.107 ± 0.026   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.705           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.917           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.630           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.941           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.389           ms/op
ClientSimple.getUser:getUser·p0.999         sample         19.518           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         20.430           ms/op
ClientSimple.getUser:getUser·p1.00          sample         20.447           ms/op
ClientSimple.listUser                       sample   7768   4.119 ± 0.038   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.548           ms/op
ClientSimple.listUser:listUser·p0.50        sample          4.055           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.916           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.501           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.160           ms/op
ClientSimple.listUser:listUser·p0.999       sample         12.734           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.713           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.713           ms/op

Benchmark result is saved to 1718021212271.json
