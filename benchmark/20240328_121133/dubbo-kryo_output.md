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
# Warmup Iteration   1: 1.848 ops/ms
Iteration   1: 7.452 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.452 ops/ms


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
# Warmup Iteration   1: 6.266 ops/ms
Iteration   1: 11.974 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.974 ops/ms


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
# Warmup Iteration   1: 6.678 ops/ms
Iteration   1: 13.491 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.491 ops/ms


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
# Warmup Iteration   1: 4.248 ops/ms
Iteration   1: 8.712 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.712 ops/ms


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
# Warmup Iteration   1: 3.841 ±(99.9%) 0.069 ms/op
Iteration   1: 2.188 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.188 ms/op


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
# Warmup Iteration   1: 3.061 ±(99.9%) 0.044 ms/op
Iteration   1: 2.092 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.092 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.474 ±(99.9%) 0.066 ms/op
Iteration   1: 2.079 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.079 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.069 ±(99.9%) 0.092 ms/op
Iteration   1: 3.578 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.578 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.376 ±(99.9%) 0.077 ms/op
Iteration   1: 2.449 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   0.671 ms/op
                 createUser·p0.50:   2.228 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.379 ms/op
                 createUser·p0.99:   9.241 ms/op
                 createUser·p0.999:  16.906 ms/op
                 createUser·p0.9999: 17.880 ms/op
                 createUser·p1.00:   18.121 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13059
  mean =      2.449 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 128 
    [ 1.250,  2.500) = 8932 
    [ 2.500,  3.750) = 3563 
    [ 3.750,  5.000) = 172 
    [ 5.000,  6.250) = 72 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 51 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 34 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.671 ms/op
     p(50.0000) =      2.228 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.379 ms/op
     p(99.0000) =      9.241 ms/op
     p(99.9000) =     16.906 ms/op
     p(99.9900) =     17.880 ms/op
     p(99.9990) =     18.121 ms/op
     p(99.9999) =     18.121 ms/op
    p(100.0000) =     18.121 ms/op


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
# Warmup Iteration   1: 2.844 ±(99.9%) 0.064 ms/op
Iteration   1: 2.078 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.555 ms/op
                 existUser·p0.50:   2.044 ms/op
                 existUser·p0.90:   2.703 ms/op
                 existUser·p0.95:   2.926 ms/op
                 existUser·p0.99:   3.999 ms/op
                 existUser·p0.999:  15.106 ms/op
                 existUser·p0.9999: 15.285 ms/op
                 existUser·p1.00:   15.303 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15374
  mean =      2.078 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 494 
    [ 1.250,  2.500) = 12008 
    [ 2.500,  3.750) = 2708 
    [ 3.750,  5.000) = 69 
    [ 5.000,  6.250) = 33 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.555 ms/op
     p(50.0000) =      2.044 ms/op
     p(90.0000) =      2.703 ms/op
     p(95.0000) =      2.926 ms/op
     p(99.0000) =      3.999 ms/op
     p(99.9000) =     15.106 ms/op
     p(99.9900) =     15.285 ms/op
     p(99.9990) =     15.303 ms/op
     p(99.9999) =     15.303 ms/op
    p(100.0000) =     15.303 ms/op


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
# Warmup Iteration   1: 3.233 ±(99.9%) 0.082 ms/op
Iteration   1: 2.052 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.748 ms/op
                 getUser·p0.50:   1.810 ms/op
                 getUser·p0.90:   2.720 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.807 ms/op
                 getUser·p0.999:  14.025 ms/op
                 getUser·p0.9999: 14.189 ms/op
                 getUser·p1.00:   14.189 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15577
  mean =      2.052 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 88 
    [ 1.250,  2.500) = 13156 
    [ 2.500,  3.750) = 2175 
    [ 3.750,  5.000) = 51 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.748 ms/op
     p(50.0000) =      1.810 ms/op
     p(90.0000) =      2.720 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.807 ms/op
     p(99.9000) =     14.025 ms/op
     p(99.9900) =     14.189 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.505 ±(99.9%) 0.130 ms/op
Iteration   1: 4.146 ±(99.9%) 0.033 ms/op
                 listUser·p0.00:   1.544 ms/op
                 listUser·p0.50:   4.194 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.218 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  8.260 ms/op
                 listUser·p0.9999: 8.798 ms/op
                 listUser·p1.00:   8.798 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 7698
  mean =      4.146 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 0 
    [1.500, 2.000) = 25 
    [2.000, 2.500) = 93 
    [2.500, 3.000) = 694 
    [3.000, 3.500) = 1094 
    [3.500, 4.000) = 1333 
    [4.000, 4.500) = 1587 
    [4.500, 5.000) = 2111 
    [5.000, 5.500) = 517 
    [5.500, 6.000) = 44 
    [6.000, 6.500) = 28 
    [6.500, 7.000) = 80 
    [7.000, 7.500) = 34 
    [7.500, 8.000) = 41 
    [8.000, 8.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.544 ms/op
     p(50.0000) =      4.194 ms/op
     p(90.0000) =      4.997 ms/op
     p(95.0000) =      5.218 ms/op
     p(99.0000) =      7.193 ms/op
     p(99.9000) =      8.260 ms/op
     p(99.9900) =      8.798 ms/op
     p(99.9990) =      8.798 ms/op
     p(99.9999) =      8.798 ms/op
    p(100.0000) =      8.798 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.452          ops/ms
ClientSimple.existUser                       thrpt         11.974          ops/ms
ClientSimple.getUser                         thrpt         13.491          ops/ms
ClientSimple.listUser                        thrpt          8.712          ops/ms
ClientSimple.createUser                       avgt          2.188           ms/op
ClientSimple.existUser                        avgt          2.092           ms/op
ClientSimple.getUser                          avgt          2.079           ms/op
ClientSimple.listUser                         avgt          3.578           ms/op
ClientSimple.createUser                     sample  13059   2.449 ± 0.038   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.671           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.228           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.023           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.379           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.241           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.906           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.880           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.121           ms/op
ClientSimple.existUser                      sample  15374   2.078 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.555           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.044           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.703           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.926           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.999           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.106           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.285           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.303           ms/op
ClientSimple.getUser                        sample  15577   2.052 ± 0.026   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.748           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.810           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.720           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.150           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.807           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.025           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.189           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.189           ms/op
ClientSimple.listUser                       sample   7698   4.146 ± 0.033   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.544           ms/op
ClientSimple.listUser:listUser·p0.50        sample          4.194           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.997           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.218           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.193           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.260           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.798           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.798           ms/op

Benchmark result is saved to 1711627655037.json
