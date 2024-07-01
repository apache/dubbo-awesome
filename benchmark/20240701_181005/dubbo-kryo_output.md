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
# Warmup Iteration   1: 0.797 ops/ms
Iteration   1: 5.515 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.515 ops/ms


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
# Warmup Iteration   1: 5.592 ops/ms
Iteration   1: 10.756 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.756 ops/ms


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
# Warmup Iteration   1: 4.362 ops/ms
Iteration   1: 11.156 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.156 ops/ms


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
# Warmup Iteration   1: 3.861 ops/ms
Iteration   1: 7.367 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.367 ops/ms


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
# Warmup Iteration   1: 4.250 ±(99.9%) 0.076 ms/op
Iteration   1: 2.341 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.341 ms/op


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
# Warmup Iteration   1: 3.226 ±(99.9%) 0.063 ms/op
Iteration   1: 1.823 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.823 ms/op


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
# Warmup Iteration   1: 3.397 ±(99.9%) 0.064 ms/op
Iteration   1: 1.836 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.836 ms/op


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
# Warmup Iteration   1: 5.223 ±(99.9%) 0.106 ms/op
Iteration   1: 3.529 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.529 ms/op


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
# Warmup Iteration   1: 3.755 ±(99.9%) 0.103 ms/op
Iteration   1: 2.230 ±(99.9%) 0.052 ms/op
                 createUser·p0.00:   0.598 ms/op
                 createUser·p0.50:   1.978 ms/op
                 createUser·p0.90:   2.724 ms/op
                 createUser·p0.95:   3.039 ms/op
                 createUser·p0.99:   11.391 ms/op
                 createUser·p0.999:  28.934 ms/op
                 createUser·p0.9999: 29.786 ms/op
                 createUser·p1.00:   29.786 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14374
  mean =      2.230 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12077 
    [ 2.500,  5.000) = 2061 
    [ 5.000,  7.500) = 46 
    [ 7.500, 10.000) = 25 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.598 ms/op
     p(50.0000) =      1.978 ms/op
     p(90.0000) =      2.724 ms/op
     p(95.0000) =      3.039 ms/op
     p(99.0000) =     11.391 ms/op
     p(99.9000) =     28.934 ms/op
     p(99.9900) =     29.786 ms/op
     p(99.9990) =     29.786 ms/op
     p(99.9999) =     29.786 ms/op
    p(100.0000) =     29.786 ms/op


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
# Warmup Iteration   1: 3.354 ±(99.9%) 0.094 ms/op
Iteration   1: 2.074 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.584 ms/op
                 existUser·p0.50:   1.978 ms/op
                 existUser·p0.90:   2.683 ms/op
                 existUser·p0.95:   2.966 ms/op
                 existUser·p0.99:   4.415 ms/op
                 existUser·p0.999:  9.883 ms/op
                 existUser·p0.9999: 10.313 ms/op
                 existUser·p1.00:   10.437 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15402
  mean =      2.074 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 27 
    [ 1.000,  2.000) = 7904 
    [ 2.000,  3.000) = 6743 
    [ 3.000,  4.000) = 547 
    [ 4.000,  5.000) = 57 
    [ 5.000,  6.000) = 60 
    [ 6.000,  7.000) = 0 
    [ 7.000,  8.000) = 0 
    [ 8.000,  9.000) = 14 
    [ 9.000, 10.000) = 38 

  Percentiles, ms/op:
      p(0.0000) =      0.584 ms/op
     p(50.0000) =      1.978 ms/op
     p(90.0000) =      2.683 ms/op
     p(95.0000) =      2.966 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      9.883 ms/op
     p(99.9900) =     10.313 ms/op
     p(99.9990) =     10.437 ms/op
     p(99.9999) =     10.437 ms/op
    p(100.0000) =     10.437 ms/op


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
# Warmup Iteration   1: 3.552 ±(99.9%) 0.107 ms/op
Iteration   1: 2.168 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.678 ms/op
                 getUser·p0.50:   1.876 ms/op
                 getUser·p0.90:   2.974 ms/op
                 getUser·p0.95:   3.264 ms/op
                 getUser·p0.99:   5.315 ms/op
                 getUser·p0.999:  15.995 ms/op
                 getUser·p0.9999: 16.516 ms/op
                 getUser·p1.00:   16.531 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14760
  mean =      2.168 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 297 
    [ 1.250,  2.500) = 10757 
    [ 2.500,  3.750) = 3370 
    [ 3.750,  5.000) = 171 
    [ 5.000,  6.250) = 52 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.678 ms/op
     p(50.0000) =      1.876 ms/op
     p(90.0000) =      2.974 ms/op
     p(95.0000) =      3.264 ms/op
     p(99.0000) =      5.315 ms/op
     p(99.9000) =     15.995 ms/op
     p(99.9900) =     16.516 ms/op
     p(99.9990) =     16.531 ms/op
     p(99.9999) =     16.531 ms/op
    p(100.0000) =     16.531 ms/op


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
# Warmup Iteration   1: 4.851 ±(99.9%) 0.180 ms/op
Iteration   1: 3.193 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   1.180 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.303 ms/op
                 listUser·p0.999:  16.416 ms/op
                 listUser·p0.9999: 17.301 ms/op
                 listUser·p1.00:   17.302 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10041
  mean =      3.193 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 700 
    [ 2.500,  3.750) = 7785 
    [ 3.750,  5.000) = 1399 
    [ 5.000,  6.250) = 120 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.180 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      5.303 ms/op
     p(99.9000) =     16.416 ms/op
     p(99.9900) =     17.301 ms/op
     p(99.9990) =     17.302 ms/op
     p(99.9999) =     17.302 ms/op
    p(100.0000) =     17.302 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.515          ops/ms
ClientSimple.existUser                       thrpt         10.756          ops/ms
ClientSimple.getUser                         thrpt         11.156          ops/ms
ClientSimple.listUser                        thrpt          7.367          ops/ms
ClientSimple.createUser                       avgt          2.341           ms/op
ClientSimple.existUser                        avgt          1.823           ms/op
ClientSimple.getUser                          avgt          1.836           ms/op
ClientSimple.listUser                         avgt          3.529           ms/op
ClientSimple.createUser                     sample  14374   2.230 ± 0.052   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.598           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.978           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.724           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.039           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.391           ms/op
ClientSimple.createUser:createUser·p0.999   sample         28.934           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         29.786           ms/op
ClientSimple.createUser:createUser·p1.00    sample         29.786           ms/op
ClientSimple.existUser                      sample  15402   2.074 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.584           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.978           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.683           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.966           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.415           ms/op
ClientSimple.existUser:existUser·p0.999     sample          9.883           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         10.313           ms/op
ClientSimple.existUser:existUser·p1.00      sample         10.437           ms/op
ClientSimple.getUser                        sample  14760   2.168 ± 0.029   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.678           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.876           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.974           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.264           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.315           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.995           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.516           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.531           ms/op
ClientSimple.listUser                       sample  10041   3.193 ± 0.031   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.180           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.998           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.949           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.293           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.303           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.416           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.301           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.302           ms/op

Benchmark result is saved to 1719857151700.json
