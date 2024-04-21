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
# Warmup Iteration   1: 1.615 ops/ms
Iteration   1: 6.835 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.835 ops/ms


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
# Warmup Iteration   1: 6.539 ops/ms
Iteration   1: 11.710 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.710 ops/ms


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
# Warmup Iteration   1: 6.428 ops/ms
Iteration   1: 16.048 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  16.048 ops/ms


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
# Warmup Iteration   1: 5.124 ops/ms
Iteration   1: 8.547 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.547 ops/ms


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
# Warmup Iteration   1: 3.857 ±(99.9%) 0.071 ms/op
Iteration   1: 2.194 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.194 ms/op


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
# Warmup Iteration   1: 2.948 ±(99.9%) 0.045 ms/op
Iteration   1: 1.949 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.949 ms/op


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
# Warmup Iteration   1: 3.007 ±(99.9%) 0.049 ms/op
Iteration   1: 2.016 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.016 ms/op


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
# Warmup Iteration   1: 4.821 ±(99.9%) 0.093 ms/op
Iteration   1: 3.778 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.778 ms/op


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
# Warmup Iteration   1: 3.436 ±(99.9%) 0.086 ms/op
Iteration   1: 2.524 ±(99.9%) 0.044 ms/op
                 createUser·p0.00:   0.556 ms/op
                 createUser·p0.50:   2.257 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   12.063 ms/op
                 createUser·p0.999:  16.537 ms/op
                 createUser·p0.9999: 17.766 ms/op
                 createUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12672
  mean =      2.524 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 109 
    [ 1.250,  2.500) = 8542 
    [ 2.500,  3.750) = 3371 
    [ 3.750,  5.000) = 300 
    [ 5.000,  6.250) = 80 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 51 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.556 ms/op
     p(50.0000) =      2.257 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =     12.063 ms/op
     p(99.9000) =     16.537 ms/op
     p(99.9900) =     17.766 ms/op
     p(99.9990) =     17.924 ms/op
     p(99.9999) =     17.924 ms/op
    p(100.0000) =     17.924 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.051 ±(99.9%) 0.076 ms/op
Iteration   1: 1.966 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.440 ms/op
                 existUser·p0.50:   1.890 ms/op
                 existUser·p0.90:   2.388 ms/op
                 existUser·p0.95:   2.621 ms/op
                 existUser·p0.99:   4.098 ms/op
                 existUser·p0.999:  10.202 ms/op
                 existUser·p0.9999: 10.760 ms/op
                 existUser·p1.00:   10.781 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16344
  mean =      1.966 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 389 
    [ 1.250,  2.500) = 14848 
    [ 2.500,  3.750) = 896 
    [ 3.750,  5.000) = 135 
    [ 5.000,  6.250) = 37 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.440 ms/op
     p(50.0000) =      1.890 ms/op
     p(90.0000) =      2.388 ms/op
     p(95.0000) =      2.621 ms/op
     p(99.0000) =      4.098 ms/op
     p(99.9000) =     10.202 ms/op
     p(99.9900) =     10.760 ms/op
     p(99.9990) =     10.781 ms/op
     p(99.9999) =     10.781 ms/op
    p(100.0000) =     10.781 ms/op


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
# Warmup Iteration   1: 3.353 ±(99.9%) 0.075 ms/op
Iteration   1: 2.194 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.702 ms/op
                 getUser·p0.50:   2.150 ms/op
                 getUser·p0.90:   2.826 ms/op
                 getUser·p0.95:   3.051 ms/op
                 getUser·p0.99:   5.265 ms/op
                 getUser·p0.999:  12.435 ms/op
                 getUser·p0.9999: 13.683 ms/op
                 getUser·p1.00:   13.713 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14563
  mean =      2.194 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 457 
    [ 1.250,  2.500) = 9928 
    [ 2.500,  3.750) = 3960 
    [ 3.750,  5.000) = 46 
    [ 5.000,  6.250) = 117 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.702 ms/op
     p(50.0000) =      2.150 ms/op
     p(90.0000) =      2.826 ms/op
     p(95.0000) =      3.051 ms/op
     p(99.0000) =      5.265 ms/op
     p(99.9000) =     12.435 ms/op
     p(99.9900) =     13.683 ms/op
     p(99.9990) =     13.713 ms/op
     p(99.9999) =     13.713 ms/op
    p(100.0000) =     13.713 ms/op


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
# Warmup Iteration   1: 4.175 ±(99.9%) 0.129 ms/op
Iteration   1: 3.253 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   0.840 ms/op
                 listUser·p0.50:   3.254 ms/op
                 listUser·p0.90:   4.030 ms/op
                 listUser·p0.95:   4.406 ms/op
                 listUser·p0.99:   6.170 ms/op
                 listUser·p0.999:  9.880 ms/op
                 listUser·p0.9999: 9.961 ms/op
                 listUser·p1.00:   9.961 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9882
  mean =      3.253 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 2 
    [ 1.000,  2.000) = 368 
    [ 2.000,  3.000) = 3351 
    [ 3.000,  4.000) = 5086 
    [ 4.000,  5.000) = 895 
    [ 5.000,  6.000) = 76 
    [ 6.000,  7.000) = 37 
    [ 7.000,  8.000) = 35 
    [ 8.000,  9.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.840 ms/op
     p(50.0000) =      3.254 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.406 ms/op
     p(99.0000) =      6.170 ms/op
     p(99.9000) =      9.880 ms/op
     p(99.9900) =      9.961 ms/op
     p(99.9990) =      9.961 ms/op
     p(99.9999) =      9.961 ms/op
    p(100.0000) =      9.961 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.835          ops/ms
ClientSimple.existUser                       thrpt         11.710          ops/ms
ClientSimple.getUser                         thrpt         16.048          ops/ms
ClientSimple.listUser                        thrpt          8.547          ops/ms
ClientSimple.createUser                       avgt          2.194           ms/op
ClientSimple.existUser                        avgt          1.949           ms/op
ClientSimple.getUser                          avgt          2.016           ms/op
ClientSimple.listUser                         avgt          3.778           ms/op
ClientSimple.createUser                     sample  12672   2.524 ± 0.044   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.556           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.257           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.023           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.789           ms/op
ClientSimple.createUser:createUser·p0.99    sample         12.063           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.537           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.766           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.924           ms/op
ClientSimple.existUser                      sample  16344   1.966 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.440           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.890           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.388           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.621           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.098           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.202           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         10.760           ms/op
ClientSimple.existUser:existUser·p1.00      sample         10.781           ms/op
ClientSimple.getUser                        sample  14563   2.194 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.702           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.150           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.826           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.051           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.265           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.435           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.683           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.713           ms/op
ClientSimple.listUser                       sample   9882   3.253 ± 0.028   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.840           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.254           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.030           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.406           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.170           ms/op
ClientSimple.listUser:listUser·p0.999       sample          9.880           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.961           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.961           ms/op

Benchmark result is saved to 1713701199883.json
