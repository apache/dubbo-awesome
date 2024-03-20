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
# Warmup Iteration   1: 1.753 ops/ms
Iteration   1: 6.437 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.437 ops/ms


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
# Warmup Iteration   1: 5.896 ops/ms
Iteration   1: 11.666 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.666 ops/ms


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
# Warmup Iteration   1: 5.499 ops/ms
Iteration   1: 14.146 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.146 ops/ms


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
# Warmup Iteration   1: 5.634 ops/ms
Iteration   1: 8.872 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.872 ops/ms


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
# Warmup Iteration   1: 3.855 ±(99.9%) 0.067 ms/op
Iteration   1: 2.131 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.131 ms/op


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
# Warmup Iteration   1: 3.315 ±(99.9%) 0.093 ms/op
Iteration   1: 2.191 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.191 ms/op


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
# Warmup Iteration   1: 3.299 ±(99.9%) 0.061 ms/op
Iteration   1: 1.917 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.917 ms/op


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
# Warmup Iteration   1: 5.037 ±(99.9%) 0.118 ms/op
Iteration   1: 3.673 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.673 ms/op


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
# Warmup Iteration   1: 3.324 ±(99.9%) 0.082 ms/op
Iteration   1: 2.325 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.556 ms/op
                 createUser·p0.50:   2.191 ms/op
                 createUser·p0.90:   2.818 ms/op
                 createUser·p0.95:   3.080 ms/op
                 createUser·p0.99:   8.511 ms/op
                 createUser·p0.999:  14.405 ms/op
                 createUser·p0.9999: 16.777 ms/op
                 createUser·p1.00:   16.777 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13793
  mean =      2.325 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 359 
    [ 1.250,  2.500) = 10419 
    [ 2.500,  3.750) = 2639 
    [ 3.750,  5.000) = 89 
    [ 5.000,  6.250) = 95 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.556 ms/op
     p(50.0000) =      2.191 ms/op
     p(90.0000) =      2.818 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =      8.511 ms/op
     p(99.9000) =     14.405 ms/op
     p(99.9900) =     16.777 ms/op
     p(99.9990) =     16.777 ms/op
     p(99.9999) =     16.777 ms/op
    p(100.0000) =     16.777 ms/op


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
# Warmup Iteration   1: 3.127 ±(99.9%) 0.069 ms/op
Iteration   1: 1.923 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.628 ms/op
                 existUser·p0.50:   1.825 ms/op
                 existUser·p0.90:   2.507 ms/op
                 existUser·p0.95:   2.732 ms/op
                 existUser·p0.99:   3.176 ms/op
                 existUser·p0.999:  19.440 ms/op
                 existUser·p0.9999: 19.573 ms/op
                 existUser·p1.00:   19.595 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16749
  mean =      1.923 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 572 
    [ 1.250,  2.500) = 14468 
    [ 2.500,  3.750) = 1635 
    [ 3.750,  5.000) = 7 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.628 ms/op
     p(50.0000) =      1.825 ms/op
     p(90.0000) =      2.507 ms/op
     p(95.0000) =      2.732 ms/op
     p(99.0000) =      3.176 ms/op
     p(99.9000) =     19.440 ms/op
     p(99.9900) =     19.573 ms/op
     p(99.9990) =     19.595 ms/op
     p(99.9999) =     19.595 ms/op
    p(100.0000) =     19.595 ms/op


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
# Warmup Iteration   1: 3.196 ±(99.9%) 0.067 ms/op
Iteration   1: 2.006 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.387 ms/op
                 getUser·p0.50:   1.995 ms/op
                 getUser·p0.90:   2.458 ms/op
                 getUser·p0.95:   2.642 ms/op
                 getUser·p0.99:   3.224 ms/op
                 getUser·p0.999:  12.665 ms/op
                 getUser·p0.9999: 13.435 ms/op
                 getUser·p1.00:   13.435 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15986
  mean =      2.006 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 634 
    [ 1.250,  2.500) = 14035 
    [ 2.500,  3.750) = 1190 
    [ 3.750,  5.000) = 31 
    [ 5.000,  6.250) = 54 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.387 ms/op
     p(50.0000) =      1.995 ms/op
     p(90.0000) =      2.458 ms/op
     p(95.0000) =      2.642 ms/op
     p(99.0000) =      3.224 ms/op
     p(99.9000) =     12.665 ms/op
     p(99.9900) =     13.435 ms/op
     p(99.9990) =     13.435 ms/op
     p(99.9999) =     13.435 ms/op
    p(100.0000) =     13.435 ms/op


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
# Warmup Iteration   1: 4.485 ±(99.9%) 0.138 ms/op
Iteration   1: 3.187 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.163 ms/op
                 listUser·p0.50:   3.064 ms/op
                 listUser·p0.90:   3.777 ms/op
                 listUser·p0.95:   4.190 ms/op
                 listUser·p0.99:   4.735 ms/op
                 listUser·p0.999:  12.698 ms/op
                 listUser·p0.9999: 14.379 ms/op
                 listUser·p1.00:   14.385 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10040
  mean =      3.187 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 690 
    [ 2.500,  3.750) = 8295 
    [ 3.750,  5.000) = 977 
    [ 5.000,  6.250) = 24 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.163 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.190 ms/op
     p(99.0000) =      4.735 ms/op
     p(99.9000) =     12.698 ms/op
     p(99.9900) =     14.379 ms/op
     p(99.9990) =     14.385 ms/op
     p(99.9999) =     14.385 ms/op
    p(100.0000) =     14.385 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.437          ops/ms
ClientSimple.existUser                       thrpt         11.666          ops/ms
ClientSimple.getUser                         thrpt         14.146          ops/ms
ClientSimple.listUser                        thrpt          8.872          ops/ms
ClientSimple.createUser                       avgt          2.131           ms/op
ClientSimple.existUser                        avgt          2.191           ms/op
ClientSimple.getUser                          avgt          1.917           ms/op
ClientSimple.listUser                         avgt          3.673           ms/op
ClientSimple.createUser                     sample  13793   2.325 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.556           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.191           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.818           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.080           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.511           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.405           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.777           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.777           ms/op
ClientSimple.existUser                      sample  16749   1.923 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.628           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.825           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.507           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.732           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.176           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.440           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.573           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.595           ms/op
ClientSimple.getUser                        sample  15986   2.006 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.387           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.995           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.458           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.642           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.224           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.665           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.435           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.435           ms/op
ClientSimple.listUser                       sample  10040   3.187 ± 0.025   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.163           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.064           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.777           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.190           ms/op
ClientSimple.listUser:listUser·p0.99        sample          4.735           ms/op
ClientSimple.listUser:listUser·p0.999       sample         12.698           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.379           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.385           ms/op

Benchmark result is saved to 1710893653236.json
