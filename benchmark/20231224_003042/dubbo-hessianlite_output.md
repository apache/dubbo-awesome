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
# Warmup Iteration   1: 2.383 ops/ms
Iteration   1: 5.831 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.831 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.267 ops/ms
Iteration   1: 13.177 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.177 ops/ms


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
# Warmup Iteration   1: 2.962 ops/ms
Iteration   1: 8.366 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.366 ops/ms


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
# Warmup Iteration   1: 1.798 ops/ms
Iteration   1: 3.641 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.641 ops/ms


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
# Warmup Iteration   1: 5.303 ±(99.9%) 0.087 ms/op
Iteration   1: 3.374 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.374 ms/op


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
# Warmup Iteration   1: 3.128 ±(99.9%) 0.034 ms/op
Iteration   1: 1.781 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.781 ms/op


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
# Warmup Iteration   1: 4.946 ±(99.9%) 0.061 ms/op
Iteration   1: 3.052 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.052 ms/op


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
# Warmup Iteration   1: 11.316 ±(99.9%) 0.204 ms/op
Iteration   1: 7.481 ±(99.9%) 0.083 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.481 ms/op


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
# Warmup Iteration   1: 5.215 ±(99.9%) 0.113 ms/op
Iteration   1: 3.078 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   1.092 ms/op
                 createUser·p0.50:   2.879 ms/op
                 createUser·p0.90:   3.961 ms/op
                 createUser·p0.95:   4.465 ms/op
                 createUser·p0.99:   6.992 ms/op
                 createUser·p0.999:  19.366 ms/op
                 createUser·p0.9999: 19.464 ms/op
                 createUser·p1.00:   19.464 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10374
  mean =      3.078 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 2392 
    [ 2.500,  3.750) = 6586 
    [ 3.750,  5.000) = 1115 
    [ 5.000,  6.250) = 138 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 43 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.092 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      6.992 ms/op
     p(99.9000) =     19.366 ms/op
     p(99.9900) =     19.464 ms/op
     p(99.9990) =     19.464 ms/op
     p(99.9999) =     19.464 ms/op
    p(100.0000) =     19.464 ms/op


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
# Warmup Iteration   1: 3.596 ±(99.9%) 0.168 ms/op
Iteration   1: 1.984 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.636 ms/op
                 existUser·p0.50:   1.958 ms/op
                 existUser·p0.90:   2.523 ms/op
                 existUser·p0.95:   2.666 ms/op
                 existUser·p0.99:   3.695 ms/op
                 existUser·p0.999:  5.317 ms/op
                 existUser·p0.9999: 8.870 ms/op
                 existUser·p1.00:   8.962 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16263
  mean =      1.984 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 147 
    [1.000, 1.500) = 2315 
    [1.500, 2.000) = 6215 
    [2.000, 2.500) = 5765 
    [2.500, 3.000) = 1442 
    [3.000, 3.500) = 150 
    [3.500, 4.000) = 113 
    [4.000, 4.500) = 51 
    [4.500, 5.000) = 26 
    [5.000, 5.500) = 34 
    [5.500, 6.000) = 0 
    [6.000, 6.500) = 1 
    [6.500, 7.000) = 0 
    [7.000, 7.500) = 0 
    [7.500, 8.000) = 0 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.636 ms/op
     p(50.0000) =      1.958 ms/op
     p(90.0000) =      2.523 ms/op
     p(95.0000) =      2.666 ms/op
     p(99.0000) =      3.695 ms/op
     p(99.9000) =      5.317 ms/op
     p(99.9900) =      8.870 ms/op
     p(99.9990) =      8.962 ms/op
     p(99.9999) =      8.962 ms/op
    p(100.0000) =      8.962 ms/op


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
# Warmup Iteration   1: 4.720 ±(99.9%) 0.105 ms/op
Iteration   1: 3.034 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.933 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   3.973 ms/op
                 getUser·p0.99:   4.851 ms/op
                 getUser·p0.999:  12.033 ms/op
                 getUser·p0.9999: 12.694 ms/op
                 getUser·p1.00:   12.698 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10538
  mean =      3.034 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 1909 
    [ 2.500,  3.750) = 7723 
    [ 3.750,  5.000) = 806 
    [ 5.000,  6.250) = 59 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 16 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.933 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      3.973 ms/op
     p(99.0000) =      4.851 ms/op
     p(99.9000) =     12.033 ms/op
     p(99.9900) =     12.694 ms/op
     p(99.9990) =     12.698 ms/op
     p(99.9999) =     12.698 ms/op
    p(100.0000) =     12.698 ms/op


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
# Warmup Iteration   1: 12.527 ±(99.9%) 0.477 ms/op
Iteration   1: 7.687 ±(99.9%) 0.097 ms/op
                 listUser·p0.00:   3.391 ms/op
                 listUser·p0.50:   7.381 ms/op
                 listUser·p0.90:   9.601 ms/op
                 listUser·p0.95:   10.732 ms/op
                 listUser·p0.99:   14.867 ms/op
                 listUser·p0.999:  20.506 ms/op
                 listUser·p0.9999: 23.069 ms/op
                 listUser·p1.00:   23.069 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4219
  mean =      7.687 ±(99.9%) 0.097 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 88 
    [ 5.000,  7.500) = 2170 
    [ 7.500, 10.000) = 1637 
    [10.000, 12.500) = 224 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.391 ms/op
     p(50.0000) =      7.381 ms/op
     p(90.0000) =      9.601 ms/op
     p(95.0000) =     10.732 ms/op
     p(99.0000) =     14.867 ms/op
     p(99.9000) =     20.506 ms/op
     p(99.9900) =     23.069 ms/op
     p(99.9990) =     23.069 ms/op
     p(99.9999) =     23.069 ms/op
    p(100.0000) =     23.069 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.831          ops/ms
Client.existUser                       thrpt         13.177          ops/ms
Client.getUser                         thrpt          8.366          ops/ms
Client.listUser                        thrpt          3.641          ops/ms
Client.createUser                       avgt          3.374           ms/op
Client.existUser                        avgt          1.781           ms/op
Client.getUser                          avgt          3.052           ms/op
Client.listUser                         avgt          7.481           ms/op
Client.createUser                     sample  10374   3.078 ± 0.039   ms/op
Client.createUser:createUser·p0.00    sample          1.092           ms/op
Client.createUser:createUser·p0.50    sample          2.879           ms/op
Client.createUser:createUser·p0.90    sample          3.961           ms/op
Client.createUser:createUser·p0.95    sample          4.465           ms/op
Client.createUser:createUser·p0.99    sample          6.992           ms/op
Client.createUser:createUser·p0.999   sample         19.366           ms/op
Client.createUser:createUser·p0.9999  sample         19.464           ms/op
Client.createUser:createUser·p1.00    sample         19.464           ms/op
Client.existUser                      sample  16263   1.984 ± 0.013   ms/op
Client.existUser:existUser·p0.00      sample          0.636           ms/op
Client.existUser:existUser·p0.50      sample          1.958           ms/op
Client.existUser:existUser·p0.90      sample          2.523           ms/op
Client.existUser:existUser·p0.95      sample          2.666           ms/op
Client.existUser:existUser·p0.99      sample          3.695           ms/op
Client.existUser:existUser·p0.999     sample          5.317           ms/op
Client.existUser:existUser·p0.9999    sample          8.870           ms/op
Client.existUser:existUser·p1.00      sample          8.962           ms/op
Client.getUser                        sample  10538   3.034 ± 0.023   ms/op
Client.getUser:getUser·p0.00          sample          0.933           ms/op
Client.getUser:getUser·p0.50          sample          3.011           ms/op
Client.getUser:getUser·p0.90          sample          3.682           ms/op
Client.getUser:getUser·p0.95          sample          3.973           ms/op
Client.getUser:getUser·p0.99          sample          4.851           ms/op
Client.getUser:getUser·p0.999         sample         12.033           ms/op
Client.getUser:getUser·p0.9999        sample         12.694           ms/op
Client.getUser:getUser·p1.00          sample         12.698           ms/op
Client.listUser                       sample   4219   7.687 ± 0.097   ms/op
Client.listUser:listUser·p0.00        sample          3.391           ms/op
Client.listUser:listUser·p0.50        sample          7.381           ms/op
Client.listUser:listUser·p0.90        sample          9.601           ms/op
Client.listUser:listUser·p0.95        sample         10.732           ms/op
Client.listUser:listUser·p0.99        sample         14.867           ms/op
Client.listUser:listUser·p0.999       sample         20.506           ms/op
Client.listUser:listUser·p0.9999      sample         23.069           ms/op
Client.listUser:listUser·p1.00        sample         23.069           ms/op
