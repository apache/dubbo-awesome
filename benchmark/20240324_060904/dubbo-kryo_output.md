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
# Warmup Iteration   1: 1.962 ops/ms
Iteration   1: 6.609 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.609 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.244 ops/ms
Iteration   1: 12.841 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.841 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.384 ops/ms
Iteration   1: 11.856 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.856 ops/ms


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
# Warmup Iteration   1: 4.931 ops/ms
Iteration   1: 8.536 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.536 ops/ms


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
# Warmup Iteration   1: 4.368 ±(99.9%) 0.068 ms/op
Iteration   1: 2.109 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.109 ms/op


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
# Warmup Iteration   1: 3.077 ±(99.9%) 0.053 ms/op
Iteration   1: 1.953 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.953 ms/op


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
# Warmup Iteration   1: 3.296 ±(99.9%) 0.055 ms/op
Iteration   1: 2.094 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.094 ms/op


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
# Warmup Iteration   1: 4.658 ±(99.9%) 0.088 ms/op
Iteration   1: 3.615 ±(99.9%) 0.031 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.615 ms/op


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
# Warmup Iteration   1: 3.580 ±(99.9%) 0.102 ms/op
Iteration   1: 1.991 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   0.447 ms/op
                 createUser·p0.50:   1.868 ms/op
                 createUser·p0.90:   2.380 ms/op
                 createUser·p0.95:   2.556 ms/op
                 createUser·p0.99:   5.381 ms/op
                 createUser·p0.999:  29.482 ms/op
                 createUser·p0.9999: 31.601 ms/op
                 createUser·p1.00:   31.621 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16057
  mean =      1.991 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15038 
    [ 2.500,  5.000) = 846 
    [ 5.000,  7.500) = 42 
    [ 7.500, 10.000) = 19 
    [10.000, 12.500) = 8 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.447 ms/op
     p(50.0000) =      1.868 ms/op
     p(90.0000) =      2.380 ms/op
     p(95.0000) =      2.556 ms/op
     p(99.0000) =      5.381 ms/op
     p(99.9000) =     29.482 ms/op
     p(99.9900) =     31.601 ms/op
     p(99.9990) =     31.621 ms/op
     p(99.9999) =     31.621 ms/op
    p(100.0000) =     31.621 ms/op


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
# Warmup Iteration   1: 2.943 ±(99.9%) 0.061 ms/op
Iteration   1: 1.900 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.490 ms/op
                 existUser·p0.50:   1.745 ms/op
                 existUser·p0.90:   2.396 ms/op
                 existUser·p0.95:   2.703 ms/op
                 existUser·p0.99:   4.033 ms/op
                 existUser·p0.999:  13.664 ms/op
                 existUser·p0.9999: 13.998 ms/op
                 existUser·p1.00:   14.189 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16831
  mean =      1.900 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 506 
    [ 1.250,  2.500) = 14935 
    [ 2.500,  3.750) = 1200 
    [ 3.750,  5.000) = 52 
    [ 5.000,  6.250) = 74 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.490 ms/op
     p(50.0000) =      1.745 ms/op
     p(90.0000) =      2.396 ms/op
     p(95.0000) =      2.703 ms/op
     p(99.0000) =      4.033 ms/op
     p(99.9000) =     13.664 ms/op
     p(99.9900) =     13.998 ms/op
     p(99.9990) =     14.189 ms/op
     p(99.9999) =     14.189 ms/op
    p(100.0000) =     14.189 ms/op


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
# Warmup Iteration   1: 3.447 ±(99.9%) 0.151 ms/op
Iteration   1: 2.360 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.708 ms/op
                 getUser·p0.50:   2.367 ms/op
                 getUser·p0.90:   2.929 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.928 ms/op
                 getUser·p0.999:  15.113 ms/op
                 getUser·p0.9999: 15.660 ms/op
                 getUser·p1.00:   15.712 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13552
  mean =      2.360 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 148 
    [ 1.250,  2.500) = 8368 
    [ 2.500,  3.750) = 4851 
    [ 3.750,  5.000) = 150 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.708 ms/op
     p(50.0000) =      2.367 ms/op
     p(90.0000) =      2.929 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.928 ms/op
     p(99.9000) =     15.113 ms/op
     p(99.9900) =     15.660 ms/op
     p(99.9990) =     15.712 ms/op
     p(99.9999) =     15.712 ms/op
    p(100.0000) =     15.712 ms/op


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
# Warmup Iteration   1: 4.345 ±(99.9%) 0.125 ms/op
Iteration   1: 3.514 ±(99.9%) 0.038 ms/op
                 listUser·p0.00:   1.247 ms/op
                 listUser·p0.50:   3.383 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   4.964 ms/op
                 listUser·p0.99:   7.258 ms/op
                 listUser·p0.999:  14.287 ms/op
                 listUser·p0.9999: 15.892 ms/op
                 listUser·p1.00:   15.892 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9101
  mean =      3.514 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 822 
    [ 2.500,  3.750) = 5101 
    [ 3.750,  5.000) = 2758 
    [ 5.000,  6.250) = 298 
    [ 6.250,  7.500) = 42 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.247 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      4.964 ms/op
     p(99.0000) =      7.258 ms/op
     p(99.9000) =     14.287 ms/op
     p(99.9900) =     15.892 ms/op
     p(99.9990) =     15.892 ms/op
     p(99.9999) =     15.892 ms/op
    p(100.0000) =     15.892 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.609          ops/ms
ClientSimple.existUser                       thrpt         12.841          ops/ms
ClientSimple.getUser                         thrpt         11.856          ops/ms
ClientSimple.listUser                        thrpt          8.536          ops/ms
ClientSimple.createUser                       avgt          2.109           ms/op
ClientSimple.existUser                        avgt          1.953           ms/op
ClientSimple.getUser                          avgt          2.094           ms/op
ClientSimple.listUser                         avgt          3.615           ms/op
ClientSimple.createUser                     sample  16057   1.991 ± 0.040   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.447           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.868           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.380           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.556           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.381           ms/op
ClientSimple.createUser:createUser·p0.999   sample         29.482           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         31.601           ms/op
ClientSimple.createUser:createUser·p1.00    sample         31.621           ms/op
ClientSimple.existUser                      sample  16831   1.900 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.490           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.745           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.396           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.703           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.033           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.664           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.998           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.189           ms/op
ClientSimple.getUser                        sample  13552   2.360 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.708           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.367           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.929           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.146           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.928           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.113           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.660           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.712           ms/op
ClientSimple.listUser                       sample   9101   3.514 ± 0.038   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.247           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.383           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.473           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.964           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.258           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.287           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.892           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.892           ms/op

Benchmark result is saved to 1711260285667.json
