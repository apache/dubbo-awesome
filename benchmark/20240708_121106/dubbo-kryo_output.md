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
# Warmup Iteration   1: 1.760 ops/ms
Iteration   1: 7.267 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.267 ops/ms


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
# Warmup Iteration   1: 5.356 ops/ms
Iteration   1: 12.785 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.785 ops/ms


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
# Warmup Iteration   1: 5.474 ops/ms
Iteration   1: 11.332 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.332 ops/ms


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
# Warmup Iteration   1: 5.654 ops/ms
Iteration   1: 8.695 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.695 ops/ms


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
# Warmup Iteration   1: 3.744 ±(99.9%) 0.091 ms/op
Iteration   1: 2.023 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.023 ms/op


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
# Warmup Iteration   1: 3.385 ±(99.9%) 0.052 ms/op
Iteration   1: 1.842 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.842 ms/op


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
# Warmup Iteration   1: 3.421 ±(99.9%) 0.051 ms/op
Iteration   1: 2.429 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.429 ms/op


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
# Warmup Iteration   1: 4.321 ±(99.9%) 0.087 ms/op
Iteration   1: 3.135 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.135 ms/op


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
# Warmup Iteration   1: 3.707 ±(99.9%) 0.086 ms/op
Iteration   1: 2.100 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.890 ms/op
                 createUser·p0.50:   1.913 ms/op
                 createUser·p0.90:   2.593 ms/op
                 createUser·p0.95:   2.843 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  24.674 ms/op
                 createUser·p0.9999: 26.284 ms/op
                 createUser·p1.00:   26.575 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15225
  mean =      2.100 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13188 
    [ 2.500,  5.000) = 1933 
    [ 5.000,  7.500) = 40 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 21 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.890 ms/op
     p(50.0000) =      1.913 ms/op
     p(90.0000) =      2.593 ms/op
     p(95.0000) =      2.843 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =     24.674 ms/op
     p(99.9900) =     26.284 ms/op
     p(99.9990) =     26.575 ms/op
     p(99.9999) =     26.575 ms/op
    p(100.0000) =     26.575 ms/op


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
# Warmup Iteration   1: 3.192 ±(99.9%) 0.090 ms/op
Iteration   1: 1.879 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.632 ms/op
                 existUser·p0.50:   1.821 ms/op
                 existUser·p0.90:   2.164 ms/op
                 existUser·p0.95:   2.302 ms/op
                 existUser·p0.99:   2.998 ms/op
                 existUser·p0.999:  11.469 ms/op
                 existUser·p0.9999: 11.736 ms/op
                 existUser·p1.00:   11.747 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17017
  mean =      1.879 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 139 
    [ 1.250,  2.500) = 16496 
    [ 2.500,  3.750) = 299 
    [ 3.750,  5.000) = 27 
    [ 5.000,  6.250) = 24 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.632 ms/op
     p(50.0000) =      1.821 ms/op
     p(90.0000) =      2.164 ms/op
     p(95.0000) =      2.302 ms/op
     p(99.0000) =      2.998 ms/op
     p(99.9000) =     11.469 ms/op
     p(99.9900) =     11.736 ms/op
     p(99.9990) =     11.747 ms/op
     p(99.9999) =     11.747 ms/op
    p(100.0000) =     11.747 ms/op


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
# Warmup Iteration   1: 3.257 ±(99.9%) 0.071 ms/op
Iteration   1: 2.098 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.658 ms/op
                 getUser·p0.50:   1.985 ms/op
                 getUser·p0.90:   2.658 ms/op
                 getUser·p0.95:   2.822 ms/op
                 getUser·p0.99:   3.131 ms/op
                 getUser·p0.999:  16.728 ms/op
                 getUser·p0.9999: 18.481 ms/op
                 getUser·p1.00:   18.809 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15268
  mean =      2.098 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 116 
    [ 1.250,  2.500) = 12838 
    [ 2.500,  3.750) = 2254 
    [ 3.750,  5.000) = 28 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.658 ms/op
     p(50.0000) =      1.985 ms/op
     p(90.0000) =      2.658 ms/op
     p(95.0000) =      2.822 ms/op
     p(99.0000) =      3.131 ms/op
     p(99.9000) =     16.728 ms/op
     p(99.9900) =     18.481 ms/op
     p(99.9990) =     18.809 ms/op
     p(99.9999) =     18.809 ms/op
    p(100.0000) =     18.809 ms/op


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
# Warmup Iteration   1: 4.312 ±(99.9%) 0.140 ms/op
Iteration   1: 3.155 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   0.584 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   5.366 ms/op
                 listUser·p0.999:  6.210 ms/op
                 listUser·p0.9999: 6.691 ms/op
                 listUser·p1.00:   6.693 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10122
  mean =      3.155 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 3 
    [1.000, 1.500) = 15 
    [1.500, 2.000) = 25 
    [2.000, 2.500) = 232 
    [2.500, 3.000) = 5579 
    [3.000, 3.500) = 1670 
    [3.500, 4.000) = 1721 
    [4.000, 4.500) = 574 
    [4.500, 5.000) = 117 
    [5.000, 5.500) = 102 
    [5.500, 6.000) = 39 
    [6.000, 6.500) = 42 

  Percentiles, ms/op:
      p(0.0000) =      0.584 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      5.366 ms/op
     p(99.9000) =      6.210 ms/op
     p(99.9900) =      6.691 ms/op
     p(99.9990) =      6.693 ms/op
     p(99.9999) =      6.693 ms/op
    p(100.0000) =      6.693 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.267          ops/ms
ClientSimple.existUser                       thrpt         12.785          ops/ms
ClientSimple.getUser                         thrpt         11.332          ops/ms
ClientSimple.listUser                        thrpt          8.695          ops/ms
ClientSimple.createUser                       avgt          2.023           ms/op
ClientSimple.existUser                        avgt          1.842           ms/op
ClientSimple.getUser                          avgt          2.429           ms/op
ClientSimple.listUser                         avgt          3.135           ms/op
ClientSimple.createUser                     sample  15225   2.100 ± 0.033   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.890           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.913           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.593           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.843           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.260           ms/op
ClientSimple.createUser:createUser·p0.999   sample         24.674           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         26.284           ms/op
ClientSimple.createUser:createUser·p1.00    sample         26.575           ms/op
ClientSimple.existUser                      sample  17017   1.879 ± 0.013   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.632           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.821           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.164           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.302           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.998           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.469           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.736           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.747           ms/op
ClientSimple.getUser                        sample  15268   2.098 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.658           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.985           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.658           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.822           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.131           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.728           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.481           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.809           ms/op
ClientSimple.listUser                       sample  10122   3.155 ± 0.020   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.584           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.904           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.928           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.268           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.366           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.210           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          6.691           ms/op
ClientSimple.listUser:listUser·p1.00        sample          6.693           ms/op

Benchmark result is saved to 1720440417094.json
