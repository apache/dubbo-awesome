# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.387 ops/ms
Iteration   1: 5.931 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.931 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 4.485 ops/ms
Iteration   1: 12.217 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.217 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.942 ops/ms
Iteration   1: 8.258 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.258 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.242 ops/ms
Iteration   1: 4.003 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  4.003 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.984 ±(99.9%) 0.084 ms/op
Iteration   1: 3.097 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.097 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.553 ±(99.9%) 0.057 ms/op
Iteration   1: 1.835 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.835 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.773 ±(99.9%) 0.059 ms/op
Iteration   1: 2.977 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.977 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 11.711 ±(99.9%) 0.164 ms/op
Iteration   1: 8.690 ±(99.9%) 0.101 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.690 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 4.916 ±(99.9%) 0.108 ms/op
Iteration   1: 3.030 ±(99.9%) 0.045 ms/op
                 createUser·p0.00:   1.133 ms/op
                 createUser·p0.50:   2.834 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   4.121 ms/op
                 createUser·p0.99:   6.619 ms/op
                 createUser·p0.999:  12.013 ms/op
                 createUser·p0.9999: 40.611 ms/op
                 createUser·p1.00:   40.632 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10295
  mean =      3.030 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 10092 
    [ 5.000, 10.000) = 164 
    [10.000, 15.000) = 30 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 8 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.133 ms/op
     p(50.0000) =      2.834 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      4.121 ms/op
     p(99.0000) =      6.619 ms/op
     p(99.9000) =     12.013 ms/op
     p(99.9900) =     40.611 ms/op
     p(99.9990) =     40.632 ms/op
     p(99.9999) =     40.632 ms/op
    p(100.0000) =     40.632 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.249 ±(99.9%) 0.071 ms/op
Iteration   1: 1.754 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.539 ms/op
                 existUser·p0.50:   1.665 ms/op
                 existUser·p0.90:   2.200 ms/op
                 existUser·p0.95:   2.351 ms/op
                 existUser·p0.99:   2.712 ms/op
                 existUser·p0.999:  4.812 ms/op
                 existUser·p0.9999: 5.519 ms/op
                 existUser·p1.00:   5.546 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18288
  mean =      1.754 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 51 
    [1.000, 1.500) = 2544 
    [1.500, 2.000) = 12288 
    [2.000, 2.500) = 2996 
    [2.500, 3.000) = 272 
    [3.000, 3.500) = 55 
    [3.500, 4.000) = 21 
    [4.000, 4.500) = 17 
    [4.500, 5.000) = 31 
    [5.000, 5.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.539 ms/op
     p(50.0000) =      1.665 ms/op
     p(90.0000) =      2.200 ms/op
     p(95.0000) =      2.351 ms/op
     p(99.0000) =      2.712 ms/op
     p(99.9000) =      4.812 ms/op
     p(99.9900) =      5.519 ms/op
     p(99.9990) =      5.546 ms/op
     p(99.9999) =      5.546 ms/op
    p(100.0000) =      5.546 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.283 ±(99.9%) 0.097 ms/op
Iteration   1: 3.152 ±(99.9%) 0.115 ms/op
                 getUser·p0.00:   0.590 ms/op
                 getUser·p0.50:   2.830 ms/op
                 getUser·p0.90:   3.749 ms/op
                 getUser·p0.95:   4.080 ms/op
                 getUser·p0.99:   6.395 ms/op
                 getUser·p0.999:  70.643 ms/op
                 getUser·p0.9999: 74.703 ms/op
                 getUser·p1.00:   74.711 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10147
  mean =      3.152 ±(99.9%) 0.115 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 9962 
    [ 5.000, 10.000) = 101 
    [10.000, 15.000) = 38 
    [15.000, 20.000) = 3 
    [20.000, 25.000) = 7 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 4 
    [40.000, 45.000) = 4 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 4 
    [55.000, 60.000) = 6 
    [60.000, 65.000) = 7 
    [65.000, 70.000) = 1 
    [70.000, 75.000) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.590 ms/op
     p(50.0000) =      2.830 ms/op
     p(90.0000) =      3.749 ms/op
     p(95.0000) =      4.080 ms/op
     p(99.0000) =      6.395 ms/op
     p(99.9000) =     70.643 ms/op
     p(99.9900) =     74.703 ms/op
     p(99.9990) =     74.711 ms/op
     p(99.9999) =     74.711 ms/op
    p(100.0000) =     74.711 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 11.945 ±(99.9%) 0.475 ms/op
Iteration   1: 8.941 ±(99.9%) 0.237 ms/op
                 listUser·p0.00:   3.211 ms/op
                 listUser·p0.50:   8.208 ms/op
                 listUser·p0.90:   11.583 ms/op
                 listUser·p0.95:   13.009 ms/op
                 listUser·p0.99:   22.585 ms/op
                 listUser·p0.999:  47.690 ms/op
                 listUser·p0.9999: 49.676 ms/op
                 listUser·p1.00:   49.676 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3576
  mean =      8.941 ±(99.9%) 0.237 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 56 
    [ 5.000, 10.000) = 2701 
    [10.000, 15.000) = 725 
    [15.000, 20.000) = 35 
    [20.000, 25.000) = 27 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      3.211 ms/op
     p(50.0000) =      8.208 ms/op
     p(90.0000) =     11.583 ms/op
     p(95.0000) =     13.009 ms/op
     p(99.0000) =     22.585 ms/op
     p(99.9000) =     47.690 ms/op
     p(99.9900) =     49.676 ms/op
     p(99.9990) =     49.676 ms/op
     p(99.9999) =     49.676 ms/op
    p(100.0000) =     49.676 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.931          ops/ms
Client.existUser                       thrpt         12.217          ops/ms
Client.getUser                         thrpt          8.258          ops/ms
Client.listUser                        thrpt          4.003          ops/ms
Client.createUser                       avgt          3.097           ms/op
Client.existUser                        avgt          1.835           ms/op
Client.getUser                          avgt          2.977           ms/op
Client.listUser                         avgt          8.690           ms/op
Client.createUser                     sample  10295   3.030 ± 0.045   ms/op
Client.createUser:createUser·p0.00    sample          1.133           ms/op
Client.createUser:createUser·p0.50    sample          2.834           ms/op
Client.createUser:createUser·p0.90    sample          3.748           ms/op
Client.createUser:createUser·p0.95    sample          4.121           ms/op
Client.createUser:createUser·p0.99    sample          6.619           ms/op
Client.createUser:createUser·p0.999   sample         12.013           ms/op
Client.createUser:createUser·p0.9999  sample         40.611           ms/op
Client.createUser:createUser·p1.00    sample         40.632           ms/op
Client.existUser                      sample  18288   1.754 ± 0.009   ms/op
Client.existUser:existUser·p0.00      sample          0.539           ms/op
Client.existUser:existUser·p0.50      sample          1.665           ms/op
Client.existUser:existUser·p0.90      sample          2.200           ms/op
Client.existUser:existUser·p0.95      sample          2.351           ms/op
Client.existUser:existUser·p0.99      sample          2.712           ms/op
Client.existUser:existUser·p0.999     sample          4.812           ms/op
Client.existUser:existUser·p0.9999    sample          5.519           ms/op
Client.existUser:existUser·p1.00      sample          5.546           ms/op
Client.getUser                        sample  10147   3.152 ± 0.115   ms/op
Client.getUser:getUser·p0.00          sample          0.590           ms/op
Client.getUser:getUser·p0.50          sample          2.830           ms/op
Client.getUser:getUser·p0.90          sample          3.749           ms/op
Client.getUser:getUser·p0.95          sample          4.080           ms/op
Client.getUser:getUser·p0.99          sample          6.395           ms/op
Client.getUser:getUser·p0.999         sample         70.643           ms/op
Client.getUser:getUser·p0.9999        sample         74.703           ms/op
Client.getUser:getUser·p1.00          sample         74.711           ms/op
Client.listUser                       sample   3576   8.941 ± 0.237   ms/op
Client.listUser:listUser·p0.00        sample          3.211           ms/op
Client.listUser:listUser·p0.50        sample          8.208           ms/op
Client.listUser:listUser·p0.90        sample         11.583           ms/op
Client.listUser:listUser·p0.95        sample         13.009           ms/op
Client.listUser:listUser·p0.99        sample         22.585           ms/op
Client.listUser:listUser·p0.999       sample         47.690           ms/op
Client.listUser:listUser·p0.9999      sample         49.676           ms/op
Client.listUser:listUser·p1.00        sample         49.676           ms/op
