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
# Warmup Iteration   1: 1.874 ops/ms
Iteration   1: 7.174 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.174 ops/ms


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
# Warmup Iteration   1: 5.127 ops/ms
Iteration   1: 11.607 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.607 ops/ms


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
# Warmup Iteration   1: 5.761 ops/ms
Iteration   1: 12.130 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.130 ops/ms


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
# Warmup Iteration   1: 4.878 ops/ms
Iteration   1: 8.689 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.689 ops/ms


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
# Warmup Iteration   1: 3.750 ±(99.9%) 0.067 ms/op
Iteration   1: 2.424 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.424 ms/op


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
# Warmup Iteration   1: 3.327 ±(99.9%) 0.052 ms/op
Iteration   1: 2.012 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.012 ms/op


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
# Warmup Iteration   1: 3.553 ±(99.9%) 0.069 ms/op
Iteration   1: 2.209 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.209 ms/op


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
# Warmup Iteration   1: 4.930 ±(99.9%) 0.087 ms/op
Iteration   1: 3.773 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.773 ms/op


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
# Warmup Iteration   1: 3.630 ±(99.9%) 0.087 ms/op
Iteration   1: 2.451 ±(99.9%) 0.057 ms/op
                 createUser·p0.00:   0.782 ms/op
                 createUser·p0.50:   2.146 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.463 ms/op
                 createUser·p0.99:   8.169 ms/op
                 createUser·p0.999:  32.008 ms/op
                 createUser·p0.9999: 32.823 ms/op
                 createUser·p1.00:   32.834 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13189
  mean =      2.451 ±(99.9%) 0.057 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9806 
    [ 2.500,  5.000) = 3066 
    [ 5.000,  7.500) = 117 
    [ 7.500, 10.000) = 88 
    [10.000, 12.500) = 15 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.782 ms/op
     p(50.0000) =      2.146 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.463 ms/op
     p(99.0000) =      8.169 ms/op
     p(99.9000) =     32.008 ms/op
     p(99.9900) =     32.823 ms/op
     p(99.9990) =     32.834 ms/op
     p(99.9999) =     32.834 ms/op
    p(100.0000) =     32.834 ms/op


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
# Warmup Iteration   1: 2.912 ±(99.9%) 0.064 ms/op
Iteration   1: 1.779 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.484 ms/op
                 existUser·p0.50:   1.702 ms/op
                 existUser·p0.90:   2.318 ms/op
                 existUser·p0.95:   2.753 ms/op
                 existUser·p0.99:   3.306 ms/op
                 existUser·p0.999:  10.655 ms/op
                 existUser·p0.9999: 11.524 ms/op
                 existUser·p1.00:   11.551 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18085
  mean =      1.779 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1195 
    [ 1.250,  2.500) = 15622 
    [ 2.500,  3.750) = 1163 
    [ 3.750,  5.000) = 57 
    [ 5.000,  6.250) = 13 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.484 ms/op
     p(50.0000) =      1.702 ms/op
     p(90.0000) =      2.318 ms/op
     p(95.0000) =      2.753 ms/op
     p(99.0000) =      3.306 ms/op
     p(99.9000) =     10.655 ms/op
     p(99.9900) =     11.524 ms/op
     p(99.9990) =     11.551 ms/op
     p(99.9999) =     11.551 ms/op
    p(100.0000) =     11.551 ms/op


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
# Warmup Iteration   1: 3.465 ±(99.9%) 0.113 ms/op
Iteration   1: 2.161 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.417 ms/op
                 getUser·p0.50:   2.022 ms/op
                 getUser·p0.90:   2.732 ms/op
                 getUser·p0.95:   2.896 ms/op
                 getUser·p0.99:   4.135 ms/op
                 getUser·p0.999:  12.403 ms/op
                 getUser·p0.9999: 12.706 ms/op
                 getUser·p1.00:   12.714 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14824
  mean =      2.161 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 172 
    [ 1.250,  2.500) = 10562 
    [ 2.500,  3.750) = 3937 
    [ 3.750,  5.000) = 15 
    [ 5.000,  6.250) = 25 
    [ 6.250,  7.500) = 48 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.417 ms/op
     p(50.0000) =      2.022 ms/op
     p(90.0000) =      2.732 ms/op
     p(95.0000) =      2.896 ms/op
     p(99.0000) =      4.135 ms/op
     p(99.9000) =     12.403 ms/op
     p(99.9900) =     12.706 ms/op
     p(99.9990) =     12.714 ms/op
     p(99.9999) =     12.714 ms/op
    p(100.0000) =     12.714 ms/op


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
# Warmup Iteration   1: 4.411 ±(99.9%) 0.122 ms/op
Iteration   1: 3.598 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.102 ms/op
                 listUser·p0.50:   3.613 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.510 ms/op
                 listUser·p0.99:   6.070 ms/op
                 listUser·p0.999:  7.435 ms/op
                 listUser·p0.9999: 8.225 ms/op
                 listUser·p1.00:   8.225 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8888
  mean =      3.598 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 8 
    [1.500, 2.000) = 52 
    [2.000, 2.500) = 330 
    [2.500, 3.000) = 1137 
    [3.000, 3.500) = 2311 
    [3.500, 4.000) = 2897 
    [4.000, 4.500) = 1693 
    [4.500, 5.000) = 285 
    [5.000, 5.500) = 51 
    [5.500, 6.000) = 31 
    [6.000, 6.500) = 17 
    [6.500, 7.000) = 10 
    [7.000, 7.500) = 59 
    [7.500, 8.000) = 3 
    [8.000, 8.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.102 ms/op
     p(50.0000) =      3.613 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.510 ms/op
     p(99.0000) =      6.070 ms/op
     p(99.9000) =      7.435 ms/op
     p(99.9900) =      8.225 ms/op
     p(99.9990) =      8.225 ms/op
     p(99.9999) =      8.225 ms/op
    p(100.0000) =      8.225 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.174          ops/ms
ClientSimple.existUser                       thrpt         11.607          ops/ms
ClientSimple.getUser                         thrpt         12.130          ops/ms
ClientSimple.listUser                        thrpt          8.689          ops/ms
ClientSimple.createUser                       avgt          2.424           ms/op
ClientSimple.existUser                        avgt          2.012           ms/op
ClientSimple.getUser                          avgt          2.209           ms/op
ClientSimple.listUser                         avgt          3.773           ms/op
ClientSimple.createUser                     sample  13189   2.451 ± 0.057   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.782           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.146           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.015           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.463           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.169           ms/op
ClientSimple.createUser:createUser·p0.999   sample         32.008           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         32.823           ms/op
ClientSimple.createUser:createUser·p1.00    sample         32.834           ms/op
ClientSimple.existUser                      sample  18085   1.779 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.484           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.702           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.318           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.753           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.306           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.655           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.524           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.551           ms/op
ClientSimple.getUser                        sample  14824   2.161 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.417           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.022           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.732           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.896           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.135           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.403           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.706           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.714           ms/op
ClientSimple.listUser                       sample   8888   3.598 ± 0.024   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.102           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.613           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.309           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.510           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.070           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.435           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.225           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.225           ms/op

Benchmark result is saved to 1711433162828.json
