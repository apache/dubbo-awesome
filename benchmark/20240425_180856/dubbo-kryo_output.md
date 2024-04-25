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
# Warmup Iteration   1: 1.429 ops/ms
Iteration   1: 7.068 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.068 ops/ms


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
# Warmup Iteration   1: 5.281 ops/ms
Iteration   1: 13.264 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.264 ops/ms


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
# Warmup Iteration   1: 6.587 ops/ms
Iteration   1: 15.127 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  15.127 ops/ms


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
# Warmup Iteration   1: 5.464 ops/ms
Iteration   1: 8.791 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.791 ops/ms


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
# Warmup Iteration   1: 4.080 ±(99.9%) 0.091 ms/op
Iteration   1: 2.328 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.328 ms/op


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
# Warmup Iteration   1: 3.049 ±(99.9%) 0.059 ms/op
Iteration   1: 1.977 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.977 ms/op


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
# Warmup Iteration   1: 3.283 ±(99.9%) 0.065 ms/op
Iteration   1: 2.091 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.091 ms/op


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
# Warmup Iteration   1: 4.546 ±(99.9%) 0.096 ms/op
Iteration   1: 3.333 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.333 ms/op


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
# Warmup Iteration   1: 3.544 ±(99.9%) 0.085 ms/op
Iteration   1: 2.109 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   0.509 ms/op
                 createUser·p0.50:   1.972 ms/op
                 createUser·p0.90:   2.634 ms/op
                 createUser·p0.95:   2.953 ms/op
                 createUser·p0.99:   5.574 ms/op
                 createUser·p0.999:  13.779 ms/op
                 createUser·p0.9999: 16.153 ms/op
                 createUser·p1.00:   16.204 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15151
  mean =      2.109 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 231 
    [ 1.250,  2.500) = 12748 
    [ 2.500,  3.750) = 1826 
    [ 3.750,  5.000) = 122 
    [ 5.000,  6.250) = 107 
    [ 6.250,  7.500) = 53 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.509 ms/op
     p(50.0000) =      1.972 ms/op
     p(90.0000) =      2.634 ms/op
     p(95.0000) =      2.953 ms/op
     p(99.0000) =      5.574 ms/op
     p(99.9000) =     13.779 ms/op
     p(99.9900) =     16.153 ms/op
     p(99.9990) =     16.204 ms/op
     p(99.9999) =     16.204 ms/op
    p(100.0000) =     16.204 ms/op


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
# Warmup Iteration   1: 2.984 ±(99.9%) 0.068 ms/op
Iteration   1: 1.837 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.618 ms/op
                 existUser·p0.50:   1.786 ms/op
                 existUser·p0.90:   2.212 ms/op
                 existUser·p0.95:   2.343 ms/op
                 existUser·p0.99:   3.358 ms/op
                 existUser·p0.999:  14.352 ms/op
                 existUser·p0.9999: 16.342 ms/op
                 existUser·p1.00:   16.417 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17642
  mean =      1.837 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 882 
    [ 1.250,  2.500) = 16283 
    [ 2.500,  3.750) = 312 
    [ 3.750,  5.000) = 62 
    [ 5.000,  6.250) = 7 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.618 ms/op
     p(50.0000) =      1.786 ms/op
     p(90.0000) =      2.212 ms/op
     p(95.0000) =      2.343 ms/op
     p(99.0000) =      3.358 ms/op
     p(99.9000) =     14.352 ms/op
     p(99.9900) =     16.342 ms/op
     p(99.9990) =     16.417 ms/op
     p(99.9999) =     16.417 ms/op
    p(100.0000) =     16.417 ms/op


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
# Warmup Iteration   1: 3.255 ±(99.9%) 0.090 ms/op
Iteration   1: 1.904 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.596 ms/op
                 getUser·p0.50:   1.794 ms/op
                 getUser·p0.90:   2.216 ms/op
                 getUser·p0.95:   2.417 ms/op
                 getUser·p0.99:   3.154 ms/op
                 getUser·p0.999:  25.788 ms/op
                 getUser·p0.9999: 26.601 ms/op
                 getUser·p1.00:   27.492 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16798
  mean =      1.904 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16231 
    [ 2.500,  5.000) = 466 
    [ 5.000,  7.500) = 34 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.596 ms/op
     p(50.0000) =      1.794 ms/op
     p(90.0000) =      2.216 ms/op
     p(95.0000) =      2.417 ms/op
     p(99.0000) =      3.154 ms/op
     p(99.9000) =     25.788 ms/op
     p(99.9900) =     26.601 ms/op
     p(99.9990) =     27.492 ms/op
     p(99.9999) =     27.492 ms/op
    p(100.0000) =     27.492 ms/op


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
# Warmup Iteration   1: 4.539 ±(99.9%) 0.160 ms/op
Iteration   1: 3.329 ±(99.9%) 0.038 ms/op
                 listUser·p0.00:   1.005 ms/op
                 listUser·p0.50:   3.170 ms/op
                 listUser·p0.90:   4.100 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   7.266 ms/op
                 listUser·p0.999:  17.274 ms/op
                 listUser·p0.9999: 18.678 ms/op
                 listUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9617
  mean =      3.329 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 9 
    [ 1.250,  2.500) = 623 
    [ 2.500,  3.750) = 6762 
    [ 3.750,  5.000) = 1967 
    [ 5.000,  6.250) = 96 
    [ 6.250,  7.500) = 83 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 22 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.005 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      7.266 ms/op
     p(99.9000) =     17.274 ms/op
     p(99.9900) =     18.678 ms/op
     p(99.9990) =     18.678 ms/op
     p(99.9999) =     18.678 ms/op
    p(100.0000) =     18.678 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.068          ops/ms
ClientSimple.existUser                       thrpt         13.264          ops/ms
ClientSimple.getUser                         thrpt         15.127          ops/ms
ClientSimple.listUser                        thrpt          8.791          ops/ms
ClientSimple.createUser                       avgt          2.328           ms/op
ClientSimple.existUser                        avgt          1.977           ms/op
ClientSimple.getUser                          avgt          2.091           ms/op
ClientSimple.listUser                         avgt          3.333           ms/op
ClientSimple.createUser                     sample  15151   2.109 ± 0.024   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.509           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.972           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.634           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.953           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.574           ms/op
ClientSimple.createUser:createUser·p0.999   sample         13.779           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.153           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.204           ms/op
ClientSimple.existUser                      sample  17642   1.837 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.618           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.786           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.212           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.343           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.358           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.352           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.342           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.417           ms/op
ClientSimple.getUser                        sample  16798   1.904 ± 0.029   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.596           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.794           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.216           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.417           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.154           ms/op
ClientSimple.getUser:getUser·p0.999         sample         25.788           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         26.601           ms/op
ClientSimple.getUser:getUser·p1.00          sample         27.492           ms/op
ClientSimple.listUser                       sample   9617   3.329 ± 0.038   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.005           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.170           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.100           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.334           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.266           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.274           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.678           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.678           ms/op

Benchmark result is saved to 1714068294951.json
