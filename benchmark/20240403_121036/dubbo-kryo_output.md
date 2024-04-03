# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.438 ops/ms
Iteration   1: 6.705 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.705 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.384 ops/ms
Iteration   1: 11.683 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.683 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.995 ops/ms
Iteration   1: 12.350 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.350 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 6.113 ops/ms
Iteration   1: 8.391 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.391 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.326 ±(99.9%) 0.083 ms/op
Iteration   1: 2.059 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.059 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.284 ±(99.9%) 0.076 ms/op
Iteration   1: 2.037 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.037 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.255 ±(99.9%) 0.065 ms/op
Iteration   1: 2.246 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.246 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 5.587 ±(99.9%) 0.127 ms/op
Iteration   1: 3.264 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.264 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.767 ±(99.9%) 0.103 ms/op
Iteration   1: 2.372 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.702 ms/op
                 createUser·p0.50:   2.191 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   7.563 ms/op
                 createUser·p0.999:  13.091 ms/op
                 createUser·p0.9999: 14.197 ms/op
                 createUser·p1.00:   14.369 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13494
  mean =      2.372 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 150 
    [ 1.250,  2.500) = 9319 
    [ 2.500,  3.750) = 3698 
    [ 3.750,  5.000) = 97 
    [ 5.000,  6.250) = 79 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 45 
    [ 8.750, 10.000) = 22 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.702 ms/op
     p(50.0000) =      2.191 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.240 ms/op
     p(99.0000) =      7.563 ms/op
     p(99.9000) =     13.091 ms/op
     p(99.9900) =     14.197 ms/op
     p(99.9990) =     14.369 ms/op
     p(99.9999) =     14.369 ms/op
    p(100.0000) =     14.369 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.986 ±(99.9%) 0.069 ms/op
Iteration   1: 2.003 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   0.490 ms/op
                 existUser·p0.50:   1.847 ms/op
                 existUser·p0.90:   2.511 ms/op
                 existUser·p0.95:   2.785 ms/op
                 existUser·p0.99:   4.751 ms/op
                 existUser·p0.999:  22.480 ms/op
                 existUser·p0.9999: 23.213 ms/op
                 existUser·p1.00:   23.233 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15975
  mean =      2.003 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14317 
    [ 2.500,  5.000) = 1515 
    [ 5.000,  7.500) = 65 
    [ 7.500, 10.000) = 13 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.490 ms/op
     p(50.0000) =      1.847 ms/op
     p(90.0000) =      2.511 ms/op
     p(95.0000) =      2.785 ms/op
     p(99.0000) =      4.751 ms/op
     p(99.9000) =     22.480 ms/op
     p(99.9900) =     23.213 ms/op
     p(99.9990) =     23.233 ms/op
     p(99.9999) =     23.233 ms/op
    p(100.0000) =     23.233 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.142 ±(99.9%) 0.088 ms/op
Iteration   1: 2.109 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   0.338 ms/op
                 getUser·p0.50:   1.829 ms/op
                 getUser·p0.90:   2.859 ms/op
                 getUser·p0.95:   3.047 ms/op
                 getUser·p0.99:   3.625 ms/op
                 getUser·p0.999:  17.302 ms/op
                 getUser·p0.9999: 17.676 ms/op
                 getUser·p1.00:   17.760 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15166
  mean =      2.109 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 166 
    [ 1.250,  2.500) = 11522 
    [ 2.500,  3.750) = 3340 
    [ 3.750,  5.000) = 21 
    [ 5.000,  6.250) = 39 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.338 ms/op
     p(50.0000) =      1.829 ms/op
     p(90.0000) =      2.859 ms/op
     p(95.0000) =      3.047 ms/op
     p(99.0000) =      3.625 ms/op
     p(99.9000) =     17.302 ms/op
     p(99.9900) =     17.676 ms/op
     p(99.9990) =     17.760 ms/op
     p(99.9999) =     17.760 ms/op
    p(100.0000) =     17.760 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.711 ±(99.9%) 0.142 ms/op
Iteration   1: 3.536 ±(99.9%) 0.039 ms/op
                 listUser·p0.00:   0.949 ms/op
                 listUser·p0.50:   3.539 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.964 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  15.532 ms/op
                 listUser·p0.9999: 15.811 ms/op
                 listUser·p1.00:   15.811 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9033
  mean =      3.536 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 1166 
    [ 2.500,  3.750) = 4598 
    [ 3.750,  5.000) = 2832 
    [ 5.000,  6.250) = 288 
    [ 6.250,  7.500) = 95 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.949 ms/op
     p(50.0000) =      3.539 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.964 ms/op
     p(99.0000) =      6.668 ms/op
     p(99.9000) =     15.532 ms/op
     p(99.9900) =     15.811 ms/op
     p(99.9990) =     15.811 ms/op
     p(99.9999) =     15.811 ms/op
    p(100.0000) =     15.811 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.705          ops/ms
ClientSimple.existUser                       thrpt         11.683          ops/ms
ClientSimple.getUser                         thrpt         12.350          ops/ms
ClientSimple.listUser                        thrpt          8.391          ops/ms
ClientSimple.createUser                       avgt          2.059           ms/op
ClientSimple.existUser                        avgt          2.037           ms/op
ClientSimple.getUser                          avgt          2.246           ms/op
ClientSimple.listUser                         avgt          3.264           ms/op
ClientSimple.createUser                     sample  13494   2.372 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.702           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.191           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.047           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.240           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.563           ms/op
ClientSimple.createUser:createUser·p0.999   sample         13.091           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.197           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.369           ms/op
ClientSimple.existUser                      sample  15975   2.003 ± 0.028   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.490           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.847           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.511           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.785           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.751           ms/op
ClientSimple.existUser:existUser·p0.999     sample         22.480           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         23.213           ms/op
ClientSimple.existUser:existUser·p1.00      sample         23.233           ms/op
ClientSimple.getUser                        sample  15166   2.109 ± 0.028   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.338           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.829           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.859           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.047           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.625           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.302           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.676           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.760           ms/op
ClientSimple.listUser                       sample   9033   3.536 ± 0.039   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.949           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.539           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.465           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.964           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.668           ms/op
ClientSimple.listUser:listUser·p0.999       sample         15.532           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.811           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.811           ms/op

Benchmark result is saved to 1712145977906.json
