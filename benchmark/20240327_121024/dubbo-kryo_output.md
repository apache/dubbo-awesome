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
# Warmup Iteration   1: 1.887 ops/ms
Iteration   1: 7.888 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.888 ops/ms


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
# Warmup Iteration   1: 5.796 ops/ms
Iteration   1: 11.521 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.521 ops/ms


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
# Warmup Iteration   1: 5.900 ops/ms
Iteration   1: 12.243 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.243 ops/ms


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
# Warmup Iteration   1: 4.355 ops/ms
Iteration   1: 7.916 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.916 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.726 ±(99.9%) 0.071 ms/op
Iteration   1: 2.045 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.045 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.685 ±(99.9%) 0.062 ms/op
Iteration   1: 1.894 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.894 ms/op


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
# Warmup Iteration   1: 3.342 ±(99.9%) 0.056 ms/op
Iteration   1: 2.145 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.145 ms/op


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
# Warmup Iteration   1: 4.820 ±(99.9%) 0.095 ms/op
Iteration   1: 3.472 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.472 ms/op


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
# Warmup Iteration   1: 3.398 ±(99.9%) 0.078 ms/op
Iteration   1: 1.910 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.835 ms/op
                 createUser·p0.50:   1.669 ms/op
                 createUser·p0.90:   2.396 ms/op
                 createUser·p0.95:   2.576 ms/op
                 createUser·p0.99:   5.112 ms/op
                 createUser·p0.999:  20.786 ms/op
                 createUser·p0.9999: 25.097 ms/op
                 createUser·p1.00:   25.494 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16722
  mean =      1.910 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15578 
    [ 2.500,  5.000) = 959 
    [ 5.000,  7.500) = 89 
    [ 7.500, 10.000) = 31 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.835 ms/op
     p(50.0000) =      1.669 ms/op
     p(90.0000) =      2.396 ms/op
     p(95.0000) =      2.576 ms/op
     p(99.0000) =      5.112 ms/op
     p(99.9000) =     20.786 ms/op
     p(99.9900) =     25.097 ms/op
     p(99.9990) =     25.494 ms/op
     p(99.9999) =     25.494 ms/op
    p(100.0000) =     25.494 ms/op


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
# Warmup Iteration   1: 2.962 ±(99.9%) 0.078 ms/op
Iteration   1: 1.806 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.694 ms/op
                 existUser·p0.50:   1.708 ms/op
                 existUser·p0.90:   2.257 ms/op
                 existUser·p0.95:   2.531 ms/op
                 existUser·p0.99:   3.637 ms/op
                 existUser·p0.999:  17.531 ms/op
                 existUser·p0.9999: 17.669 ms/op
                 existUser·p1.00:   17.695 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17702
  mean =      1.806 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1200 
    [ 1.250,  2.500) = 15517 
    [ 2.500,  3.750) = 816 
    [ 3.750,  5.000) = 105 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.694 ms/op
     p(50.0000) =      1.708 ms/op
     p(90.0000) =      2.257 ms/op
     p(95.0000) =      2.531 ms/op
     p(99.0000) =      3.637 ms/op
     p(99.9000) =     17.531 ms/op
     p(99.9900) =     17.669 ms/op
     p(99.9990) =     17.695 ms/op
     p(99.9999) =     17.695 ms/op
    p(100.0000) =     17.695 ms/op


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
# Warmup Iteration   1: 3.905 ±(99.9%) 0.202 ms/op
Iteration   1: 2.169 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.843 ms/op
                 getUser·p0.50:   2.081 ms/op
                 getUser·p0.90:   2.859 ms/op
                 getUser·p0.95:   3.113 ms/op
                 getUser·p0.99:   3.666 ms/op
                 getUser·p0.999:  14.778 ms/op
                 getUser·p0.9999: 14.860 ms/op
                 getUser·p1.00:   14.860 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14914
  mean =      2.169 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 341 
    [ 1.250,  2.500) = 10380 
    [ 2.500,  3.750) = 4078 
    [ 3.750,  5.000) = 66 
    [ 5.000,  6.250) = 13 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.843 ms/op
     p(50.0000) =      2.081 ms/op
     p(90.0000) =      2.859 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.666 ms/op
     p(99.9000) =     14.778 ms/op
     p(99.9900) =     14.860 ms/op
     p(99.9990) =     14.860 ms/op
     p(99.9999) =     14.860 ms/op
    p(100.0000) =     14.860 ms/op


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
# Warmup Iteration   1: 4.428 ±(99.9%) 0.116 ms/op
Iteration   1: 3.592 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   1.035 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.472 ms/op
                 listUser·p0.999:  14.221 ms/op
                 listUser·p0.9999: 14.369 ms/op
                 listUser·p1.00:   14.369 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8899
  mean =      3.592 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 776 
    [ 2.500,  3.750) = 4270 
    [ 3.750,  5.000) = 3689 
    [ 5.000,  6.250) = 122 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.035 ms/op
     p(50.0000) =      3.650 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =     14.221 ms/op
     p(99.9900) =     14.369 ms/op
     p(99.9990) =     14.369 ms/op
     p(99.9999) =     14.369 ms/op
    p(100.0000) =     14.369 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.888          ops/ms
ClientSimple.existUser                       thrpt         11.521          ops/ms
ClientSimple.getUser                         thrpt         12.243          ops/ms
ClientSimple.listUser                        thrpt          7.916          ops/ms
ClientSimple.createUser                       avgt          2.045           ms/op
ClientSimple.existUser                        avgt          1.894           ms/op
ClientSimple.getUser                          avgt          2.145           ms/op
ClientSimple.listUser                         avgt          3.472           ms/op
ClientSimple.createUser                     sample  16722   1.910 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.835           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.669           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.396           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.576           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.112           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.786           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         25.097           ms/op
ClientSimple.createUser:createUser·p1.00    sample         25.494           ms/op
ClientSimple.existUser                      sample  17702   1.806 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.694           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.708           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.257           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.531           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.637           ms/op
ClientSimple.existUser:existUser·p0.999     sample         17.531           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.669           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.695           ms/op
ClientSimple.getUser                        sample  14914   2.169 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.843           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.081           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.859           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.113           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.666           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.778           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.860           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.860           ms/op
ClientSimple.listUser                       sample   8899   3.592 ± 0.032   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.035           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.650           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.194           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.424           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.472           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.221           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.369           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.369           ms/op

Benchmark result is saved to 1711541182937.json
