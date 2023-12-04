# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.379 ops/ms
Iteration   1: 5.653 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.653 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.529 ops/ms
Iteration   1: 10.913 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  10.913 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.574 ops/ms
Iteration   1: 8.320 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.320 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.437 ops/ms
Iteration   1: 3.710 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.710 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 4.933 ±(99.9%) 0.061 ms/op
Iteration   1: 2.898 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.898 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.333 ±(99.9%) 0.047 ms/op
Iteration   1: 2.038 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.038 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.673 ±(99.9%) 0.060 ms/op
Iteration   1: 3.418 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.418 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 13.178 ±(99.9%) 0.374 ms/op
Iteration   1: 8.726 ±(99.9%) 0.074 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.726 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.622 ±(99.9%) 0.180 ms/op
Iteration   1: 3.018 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   0.809 ms/op
                 createUser·p0.50:   2.855 ms/op
                 createUser·p0.90:   3.853 ms/op
                 createUser·p0.95:   4.316 ms/op
                 createUser·p0.99:   8.749 ms/op
                 createUser·p0.999:  19.476 ms/op
                 createUser·p0.9999: 19.562 ms/op
                 createUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10643
  mean =      3.018 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 3397 
    [ 2.500,  3.750) = 5939 
    [ 3.750,  5.000) = 1051 
    [ 5.000,  6.250) = 75 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 56 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.809 ms/op
     p(50.0000) =      2.855 ms/op
     p(90.0000) =      3.853 ms/op
     p(95.0000) =      4.316 ms/op
     p(99.0000) =      8.749 ms/op
     p(99.9000) =     19.476 ms/op
     p(99.9900) =     19.562 ms/op
     p(99.9990) =     19.562 ms/op
     p(99.9999) =     19.562 ms/op
    p(100.0000) =     19.562 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.160 ±(99.9%) 0.095 ms/op
Iteration   1: 2.005 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.615 ms/op
                 existUser·p0.50:   1.993 ms/op
                 existUser·p0.90:   2.429 ms/op
                 existUser·p0.95:   2.585 ms/op
                 existUser·p0.99:   3.589 ms/op
                 existUser·p0.999:  5.039 ms/op
                 existUser·p0.9999: 5.474 ms/op
                 existUser·p1.00:   5.538 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15958
  mean =      2.005 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 93 
    [1.000, 1.500) = 1356 
    [1.500, 2.000) = 6612 
    [2.000, 2.500) = 6771 
    [2.500, 3.000) = 859 
    [3.000, 3.500) = 97 
    [3.500, 4.000) = 46 
    [4.000, 4.500) = 77 
    [4.500, 5.000) = 30 
    [5.000, 5.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.615 ms/op
     p(50.0000) =      1.993 ms/op
     p(90.0000) =      2.429 ms/op
     p(95.0000) =      2.585 ms/op
     p(99.0000) =      3.589 ms/op
     p(99.9000) =      5.039 ms/op
     p(99.9900) =      5.474 ms/op
     p(99.9990) =      5.538 ms/op
     p(99.9999) =      5.538 ms/op
    p(100.0000) =      5.538 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.673 ±(99.9%) 0.111 ms/op
Iteration   1: 3.065 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   1.065 ms/op
                 getUser·p0.50:   2.900 ms/op
                 getUser·p0.90:   3.928 ms/op
                 getUser·p0.95:   4.375 ms/op
                 getUser·p0.99:   5.937 ms/op
                 getUser·p0.999:  7.365 ms/op
                 getUser·p0.9999: 9.288 ms/op
                 getUser·p1.00:   9.290 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10422
  mean =      3.065 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 35 
    [ 1.500,  2.000) = 263 
    [ 2.000,  2.500) = 1815 
    [ 2.500,  3.000) = 3678 
    [ 3.000,  3.500) = 2344 
    [ 3.500,  4.000) = 1354 
    [ 4.000,  4.500) = 466 
    [ 4.500,  5.000) = 175 
    [ 5.000,  5.500) = 113 
    [ 5.500,  6.000) = 80 
    [ 6.000,  6.500) = 24 
    [ 6.500,  7.000) = 39 
    [ 7.000,  7.500) = 31 
    [ 7.500,  8.000) = 0 
    [ 8.000,  8.500) = 0 
    [ 8.500,  9.000) = 0 
    [ 9.000,  9.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.065 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.937 ms/op
     p(99.9000) =      7.365 ms/op
     p(99.9900) =      9.288 ms/op
     p(99.9990) =      9.290 ms/op
     p(99.9999) =      9.290 ms/op
    p(100.0000) =      9.290 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 12.294 ±(99.9%) 0.495 ms/op
Iteration   1: 8.663 ±(99.9%) 0.123 ms/op
                 listUser·p0.00:   3.469 ms/op
                 listUser·p0.50:   8.270 ms/op
                 listUser·p0.90:   11.715 ms/op
                 listUser·p0.95:   12.796 ms/op
                 listUser·p0.99:   15.679 ms/op
                 listUser·p0.999:  20.388 ms/op
                 listUser·p0.9999: 26.706 ms/op
                 listUser·p1.00:   26.706 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3684
  mean =      8.663 ±(99.9%) 0.123 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 63 
    [ 5.000,  7.500) = 1210 
    [ 7.500, 10.000) = 1528 
    [10.000, 12.500) = 646 
    [12.500, 15.000) = 179 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      3.469 ms/op
     p(50.0000) =      8.270 ms/op
     p(90.0000) =     11.715 ms/op
     p(95.0000) =     12.796 ms/op
     p(99.0000) =     15.679 ms/op
     p(99.9000) =     20.388 ms/op
     p(99.9900) =     26.706 ms/op
     p(99.9990) =     26.706 ms/op
     p(99.9999) =     26.706 ms/op
    p(100.0000) =     26.706 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.653          ops/ms
Client.existUser                       thrpt         10.913          ops/ms
Client.getUser                         thrpt          8.320          ops/ms
Client.listUser                        thrpt          3.710          ops/ms
Client.createUser                       avgt          2.898           ms/op
Client.existUser                        avgt          2.038           ms/op
Client.getUser                          avgt          3.418           ms/op
Client.listUser                         avgt          8.726           ms/op
Client.createUser                     sample  10643   3.018 ± 0.040   ms/op
Client.createUser:createUser·p0.00    sample          0.809           ms/op
Client.createUser:createUser·p0.50    sample          2.855           ms/op
Client.createUser:createUser·p0.90    sample          3.853           ms/op
Client.createUser:createUser·p0.95    sample          4.316           ms/op
Client.createUser:createUser·p0.99    sample          8.749           ms/op
Client.createUser:createUser·p0.999   sample         19.476           ms/op
Client.createUser:createUser·p0.9999  sample         19.562           ms/op
Client.createUser:createUser·p1.00    sample         19.562           ms/op
Client.existUser                      sample  15958   2.005 ± 0.011   ms/op
Client.existUser:existUser·p0.00      sample          0.615           ms/op
Client.existUser:existUser·p0.50      sample          1.993           ms/op
Client.existUser:existUser·p0.90      sample          2.429           ms/op
Client.existUser:existUser·p0.95      sample          2.585           ms/op
Client.existUser:existUser·p0.99      sample          3.589           ms/op
Client.existUser:existUser·p0.999     sample          5.039           ms/op
Client.existUser:existUser·p0.9999    sample          5.474           ms/op
Client.existUser:existUser·p1.00      sample          5.538           ms/op
Client.getUser                        sample  10422   3.065 ± 0.025   ms/op
Client.getUser:getUser·p0.00          sample          1.065           ms/op
Client.getUser:getUser·p0.50          sample          2.900           ms/op
Client.getUser:getUser·p0.90          sample          3.928           ms/op
Client.getUser:getUser·p0.95          sample          4.375           ms/op
Client.getUser:getUser·p0.99          sample          5.937           ms/op
Client.getUser:getUser·p0.999         sample          7.365           ms/op
Client.getUser:getUser·p0.9999        sample          9.288           ms/op
Client.getUser:getUser·p1.00          sample          9.290           ms/op
Client.listUser                       sample   3684   8.663 ± 0.123   ms/op
Client.listUser:listUser·p0.00        sample          3.469           ms/op
Client.listUser:listUser·p0.50        sample          8.270           ms/op
Client.listUser:listUser·p0.90        sample         11.715           ms/op
Client.listUser:listUser·p0.95        sample         12.796           ms/op
Client.listUser:listUser·p0.99        sample         15.679           ms/op
Client.listUser:listUser·p0.999       sample         20.388           ms/op
Client.listUser:listUser·p0.9999      sample         26.706           ms/op
Client.listUser:listUser·p1.00        sample         26.706           ms/op
