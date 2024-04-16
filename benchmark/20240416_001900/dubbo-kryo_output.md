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
# Warmup Iteration   1: 1.738 ops/ms
Iteration   1: 7.799 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.799 ops/ms


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
# Warmup Iteration   1: 6.205 ops/ms
Iteration   1: 11.127 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.127 ops/ms


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
# Warmup Iteration   1: 6.373 ops/ms
Iteration   1: 12.190 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.190 ops/ms


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
# Warmup Iteration   1: 5.362 ops/ms
Iteration   1: 7.908 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.908 ops/ms


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
# Warmup Iteration   1: 3.812 ±(99.9%) 0.076 ms/op
Iteration   1: 2.044 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.044 ms/op


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
# Warmup Iteration   1: 3.312 ±(99.9%) 0.056 ms/op
Iteration   1: 1.922 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.922 ms/op


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
# Warmup Iteration   1: 3.055 ±(99.9%) 0.046 ms/op
Iteration   1: 2.242 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.242 ms/op


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
# Warmup Iteration   1: 4.564 ±(99.9%) 0.083 ms/op
Iteration   1: 3.729 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.729 ms/op


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
# Warmup Iteration   1: 3.529 ±(99.9%) 0.095 ms/op
Iteration   1: 2.093 ±(99.9%) 0.044 ms/op
                 createUser·p0.00:   0.759 ms/op
                 createUser·p0.50:   1.806 ms/op
                 createUser·p0.90:   2.404 ms/op
                 createUser·p0.95:   2.845 ms/op
                 createUser·p0.99:   10.584 ms/op
                 createUser·p0.999:  22.432 ms/op
                 createUser·p0.9999: 23.009 ms/op
                 createUser·p1.00:   23.560 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15425
  mean =      2.093 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14115 
    [ 2.500,  5.000) = 1010 
    [ 5.000,  7.500) = 77 
    [ 7.500, 10.000) = 42 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.759 ms/op
     p(50.0000) =      1.806 ms/op
     p(90.0000) =      2.404 ms/op
     p(95.0000) =      2.845 ms/op
     p(99.0000) =     10.584 ms/op
     p(99.9000) =     22.432 ms/op
     p(99.9900) =     23.009 ms/op
     p(99.9990) =     23.560 ms/op
     p(99.9999) =     23.560 ms/op
    p(100.0000) =     23.560 ms/op


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
# Warmup Iteration   1: 2.934 ±(99.9%) 0.067 ms/op
Iteration   1: 1.999 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.836 ms/op
                 existUser·p0.50:   1.896 ms/op
                 existUser·p0.90:   2.437 ms/op
                 existUser·p0.95:   2.703 ms/op
                 existUser·p0.99:   4.013 ms/op
                 existUser·p0.999:  11.059 ms/op
                 existUser·p0.9999: 11.477 ms/op
                 existUser·p1.00:   11.813 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16407
  mean =      1.999 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 128 
    [ 1.250,  2.500) = 14893 
    [ 2.500,  3.750) = 1196 
    [ 3.750,  5.000) = 79 
    [ 5.000,  6.250) = 65 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.836 ms/op
     p(50.0000) =      1.896 ms/op
     p(90.0000) =      2.437 ms/op
     p(95.0000) =      2.703 ms/op
     p(99.0000) =      4.013 ms/op
     p(99.9000) =     11.059 ms/op
     p(99.9900) =     11.477 ms/op
     p(99.9990) =     11.813 ms/op
     p(99.9999) =     11.813 ms/op
    p(100.0000) =     11.813 ms/op


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
# Warmup Iteration   1: 3.434 ±(99.9%) 0.089 ms/op
Iteration   1: 2.105 ±(99.9%) 0.033 ms/op
                 getUser·p0.00:   0.591 ms/op
                 getUser·p0.50:   1.964 ms/op
                 getUser·p0.90:   2.486 ms/op
                 getUser·p0.95:   2.855 ms/op
                 getUser·p0.99:   4.113 ms/op
                 getUser·p0.999:  25.297 ms/op
                 getUser·p0.9999: 25.819 ms/op
                 getUser·p1.00:   25.887 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15186
  mean =      2.105 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13735 
    [ 2.500,  5.000) = 1352 
    [ 5.000,  7.500) = 34 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.591 ms/op
     p(50.0000) =      1.964 ms/op
     p(90.0000) =      2.486 ms/op
     p(95.0000) =      2.855 ms/op
     p(99.0000) =      4.113 ms/op
     p(99.9000) =     25.297 ms/op
     p(99.9900) =     25.819 ms/op
     p(99.9990) =     25.887 ms/op
     p(99.9999) =     25.887 ms/op
    p(100.0000) =     25.887 ms/op


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
# Warmup Iteration   1: 4.555 ±(99.9%) 0.136 ms/op
Iteration   1: 3.447 ±(99.9%) 0.037 ms/op
                 listUser·p0.00:   0.749 ms/op
                 listUser·p0.50:   3.420 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   6.603 ms/op
                 listUser·p0.999:  14.336 ms/op
                 listUser·p0.9999: 15.385 ms/op
                 listUser·p1.00:   15.385 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9297
  mean =      3.447 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 1127 
    [ 2.500,  3.750) = 5547 
    [ 3.750,  5.000) = 2414 
    [ 5.000,  6.250) = 105 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.749 ms/op
     p(50.0000) =      3.420 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      6.603 ms/op
     p(99.9000) =     14.336 ms/op
     p(99.9900) =     15.385 ms/op
     p(99.9990) =     15.385 ms/op
     p(99.9999) =     15.385 ms/op
    p(100.0000) =     15.385 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.799          ops/ms
ClientSimple.existUser                       thrpt         11.127          ops/ms
ClientSimple.getUser                         thrpt         12.190          ops/ms
ClientSimple.listUser                        thrpt          7.908          ops/ms
ClientSimple.createUser                       avgt          2.044           ms/op
ClientSimple.existUser                        avgt          1.922           ms/op
ClientSimple.getUser                          avgt          2.242           ms/op
ClientSimple.listUser                         avgt          3.729           ms/op
ClientSimple.createUser                     sample  15425   2.093 ± 0.044   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.759           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.806           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.404           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.845           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.584           ms/op
ClientSimple.createUser:createUser·p0.999   sample         22.432           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.009           ms/op
ClientSimple.createUser:createUser·p1.00    sample         23.560           ms/op
ClientSimple.existUser                      sample  16407   1.999 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.836           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.896           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.437           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.703           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.013           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.059           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.477           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.813           ms/op
ClientSimple.getUser                        sample  15186   2.105 ± 0.033   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.591           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.964           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.486           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.855           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.113           ms/op
ClientSimple.getUser:getUser·p0.999         sample         25.297           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         25.819           ms/op
ClientSimple.getUser:getUser·p1.00          sample         25.887           ms/op
ClientSimple.listUser                       sample   9297   3.447 ± 0.037   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.749           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.420           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.243           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.465           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.603           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.336           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.385           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.385           ms/op

Benchmark result is saved to 1713226480262.json
