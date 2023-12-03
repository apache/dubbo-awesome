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
# Warmup Iteration   1: 2.435 ops/ms
Iteration   1: 6.641 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.641 ops/ms


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
# Warmup Iteration   1: 6.941 ops/ms
Iteration   1: 12.942 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.942 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.403 ops/ms
Iteration   1: 8.759 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.759 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.268 ops/ms
Iteration   1: 3.660 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.660 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:54
# Fork: 1 of 1
# Warmup Iteration   1: 5.239 ±(99.9%) 0.061 ms/op
Iteration   1: 3.034 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.034 ms/op


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
# Warmup Iteration   1: 3.032 ±(99.9%) 0.031 ms/op
Iteration   1: 1.785 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.785 ms/op


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
# Warmup Iteration   1: 4.470 ±(99.9%) 0.045 ms/op
Iteration   1: 2.769 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.769 ms/op


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
# Warmup Iteration   1: 14.122 ±(99.9%) 0.273 ms/op
Iteration   1: 8.430 ±(99.9%) 0.091 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.430 ms/op


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
# Warmup Iteration   1: 4.738 ±(99.9%) 0.093 ms/op
Iteration   1: 2.925 ±(99.9%) 0.057 ms/op
                 createUser·p0.00:   0.508 ms/op
                 createUser·p0.50:   2.671 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   4.148 ms/op
                 createUser·p0.99:   8.952 ms/op
                 createUser·p0.999:  30.574 ms/op
                 createUser·p0.9999: 30.832 ms/op
                 createUser·p1.00:   30.835 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10963
  mean =      2.925 ±(99.9%) 0.057 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4107 
    [ 2.500,  5.000) = 6540 
    [ 5.000,  7.500) = 134 
    [ 7.500, 10.000) = 114 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.508 ms/op
     p(50.0000) =      2.671 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      4.148 ms/op
     p(99.0000) =      8.952 ms/op
     p(99.9000) =     30.574 ms/op
     p(99.9900) =     30.832 ms/op
     p(99.9990) =     30.835 ms/op
     p(99.9999) =     30.835 ms/op
    p(100.0000) =     30.835 ms/op


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
# Warmup Iteration   1: 2.846 ±(99.9%) 0.065 ms/op
Iteration   1: 1.685 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.555 ms/op
                 existUser·p0.50:   1.571 ms/op
                 existUser·p0.90:   2.286 ms/op
                 existUser·p0.95:   2.445 ms/op
                 existUser·p0.99:   2.953 ms/op
                 existUser·p0.999:  6.947 ms/op
                 existUser·p0.9999: 8.052 ms/op
                 existUser·p1.00:   8.118 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18960
  mean =      1.685 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 142 
    [1.000, 1.500) = 8354 
    [1.500, 2.000) = 6187 
    [2.000, 2.500) = 3548 
    [2.500, 3.000) = 563 
    [3.000, 3.500) = 68 
    [3.500, 4.000) = 18 
    [4.000, 4.500) = 4 
    [4.500, 5.000) = 15 
    [5.000, 5.500) = 6 
    [5.500, 6.000) = 3 
    [6.000, 6.500) = 9 
    [6.500, 7.000) = 31 
    [7.000, 7.500) = 10 
    [7.500, 8.000) = 0 
    [8.000, 8.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.555 ms/op
     p(50.0000) =      1.571 ms/op
     p(90.0000) =      2.286 ms/op
     p(95.0000) =      2.445 ms/op
     p(99.0000) =      2.953 ms/op
     p(99.9000) =      6.947 ms/op
     p(99.9900) =      8.052 ms/op
     p(99.9990) =      8.118 ms/op
     p(99.9999) =      8.118 ms/op
    p(100.0000) =      8.118 ms/op


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
# Warmup Iteration   1: 4.445 ±(99.9%) 0.112 ms/op
Iteration   1: 3.024 ±(99.9%) 0.034 ms/op
                 getUser·p0.00:   0.766 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.126 ms/op
                 getUser·p0.99:   5.982 ms/op
                 getUser·p0.999:  17.181 ms/op
                 getUser·p0.9999: 17.496 ms/op
                 getUser·p1.00:   17.498 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10672
  mean =      3.024 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 16 
    [ 1.250,  2.500) = 2922 
    [ 2.500,  3.750) = 6496 
    [ 3.750,  5.000) = 1061 
    [ 5.000,  6.250) = 79 
    [ 6.250,  7.500) = 60 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.766 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      4.126 ms/op
     p(99.0000) =      5.982 ms/op
     p(99.9000) =     17.181 ms/op
     p(99.9900) =     17.496 ms/op
     p(99.9990) =     17.498 ms/op
     p(99.9999) =     17.498 ms/op
    p(100.0000) =     17.498 ms/op


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
# Warmup Iteration   1: 12.062 ±(99.9%) 0.332 ms/op
Iteration   1: 7.951 ±(99.9%) 0.142 ms/op
                 listUser·p0.00:   2.712 ms/op
                 listUser·p0.50:   7.418 ms/op
                 listUser·p0.90:   10.764 ms/op
                 listUser·p0.95:   11.813 ms/op
                 listUser·p0.99:   19.330 ms/op
                 listUser·p0.999:  25.486 ms/op
                 listUser·p0.9999: 29.884 ms/op
                 listUser·p1.00:   29.884 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4108
  mean =      7.951 ±(99.9%) 0.142 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 221 
    [ 5.000,  7.500) = 1908 
    [ 7.500, 10.000) = 1321 
    [10.000, 12.500) = 489 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      2.712 ms/op
     p(50.0000) =      7.418 ms/op
     p(90.0000) =     10.764 ms/op
     p(95.0000) =     11.813 ms/op
     p(99.0000) =     19.330 ms/op
     p(99.9000) =     25.486 ms/op
     p(99.9900) =     29.884 ms/op
     p(99.9990) =     29.884 ms/op
     p(99.9999) =     29.884 ms/op
    p(100.0000) =     29.884 ms/op


# Run complete. Total time: 00:01:22

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.641          ops/ms
Client.existUser                       thrpt         12.942          ops/ms
Client.getUser                         thrpt          8.759          ops/ms
Client.listUser                        thrpt          3.660          ops/ms
Client.createUser                       avgt          3.034           ms/op
Client.existUser                        avgt          1.785           ms/op
Client.getUser                          avgt          2.769           ms/op
Client.listUser                         avgt          8.430           ms/op
Client.createUser                     sample  10963   2.925 ± 0.057   ms/op
Client.createUser:createUser·p0.00    sample          0.508           ms/op
Client.createUser:createUser·p0.50    sample          2.671           ms/op
Client.createUser:createUser·p0.90    sample          3.666           ms/op
Client.createUser:createUser·p0.95    sample          4.148           ms/op
Client.createUser:createUser·p0.99    sample          8.952           ms/op
Client.createUser:createUser·p0.999   sample         30.574           ms/op
Client.createUser:createUser·p0.9999  sample         30.832           ms/op
Client.createUser:createUser·p1.00    sample         30.835           ms/op
Client.existUser                      sample  18960   1.685 ± 0.012   ms/op
Client.existUser:existUser·p0.00      sample          0.555           ms/op
Client.existUser:existUser·p0.50      sample          1.571           ms/op
Client.existUser:existUser·p0.90      sample          2.286           ms/op
Client.existUser:existUser·p0.95      sample          2.445           ms/op
Client.existUser:existUser·p0.99      sample          2.953           ms/op
Client.existUser:existUser·p0.999     sample          6.947           ms/op
Client.existUser:existUser·p0.9999    sample          8.052           ms/op
Client.existUser:existUser·p1.00      sample          8.118           ms/op
Client.getUser                        sample  10672   3.024 ± 0.034   ms/op
Client.getUser:getUser·p0.00          sample          0.766           ms/op
Client.getUser:getUser·p0.50          sample          2.978           ms/op
Client.getUser:getUser·p0.90          sample          3.813           ms/op
Client.getUser:getUser·p0.95          sample          4.126           ms/op
Client.getUser:getUser·p0.99          sample          5.982           ms/op
Client.getUser:getUser·p0.999         sample         17.181           ms/op
Client.getUser:getUser·p0.9999        sample         17.496           ms/op
Client.getUser:getUser·p1.00          sample         17.498           ms/op
Client.listUser                       sample   4108   7.951 ± 0.142   ms/op
Client.listUser:listUser·p0.00        sample          2.712           ms/op
Client.listUser:listUser·p0.50        sample          7.418           ms/op
Client.listUser:listUser·p0.90        sample         10.764           ms/op
Client.listUser:listUser·p0.95        sample         11.813           ms/op
Client.listUser:listUser·p0.99        sample         19.330           ms/op
Client.listUser:listUser·p0.999       sample         25.486           ms/op
Client.listUser:listUser·p0.9999      sample         29.884           ms/op
Client.listUser:listUser·p1.00        sample         29.884           ms/op
