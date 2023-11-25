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
# Warmup Iteration   1: 2.414 ops/ms
Iteration   1: 6.148 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.148 ops/ms


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
# Warmup Iteration   1: 6.126 ops/ms
Iteration   1: 12.783 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.783 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.893 ops/ms
Iteration   1: 7.715 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.715 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.007 ops/ms
Iteration   1: 3.541 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.541 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.799 ±(99.9%) 0.067 ms/op
Iteration   1: 3.128 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.128 ms/op


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
# Warmup Iteration   1: 3.057 ±(99.9%) 0.025 ms/op
Iteration   1: 1.993 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.993 ms/op


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
# Warmup Iteration   1: 5.547 ±(99.9%) 0.083 ms/op
Iteration   1: 3.285 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.285 ms/op


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
# Warmup Iteration   1: 10.589 ±(99.9%) 0.154 ms/op
Iteration   1: 7.463 ±(99.9%) 0.062 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.463 ms/op


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
# Warmup Iteration   1: 4.696 ±(99.9%) 0.101 ms/op
Iteration   1: 2.776 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.951 ms/op
                 createUser·p0.50:   2.666 ms/op
                 createUser·p0.90:   3.375 ms/op
                 createUser·p0.95:   3.949 ms/op
                 createUser·p0.99:   6.799 ms/op
                 createUser·p0.999:  14.786 ms/op
                 createUser·p0.9999: 15.511 ms/op
                 createUser·p1.00:   15.630 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11516
  mean =      2.776 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 13 
    [ 1.250,  2.500) = 4454 
    [ 2.500,  3.750) = 6352 
    [ 3.750,  5.000) = 479 
    [ 5.000,  6.250) = 55 
    [ 6.250,  7.500) = 71 
    [ 7.500,  8.750) = 58 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.951 ms/op
     p(50.0000) =      2.666 ms/op
     p(90.0000) =      3.375 ms/op
     p(95.0000) =      3.949 ms/op
     p(99.0000) =      6.799 ms/op
     p(99.9000) =     14.786 ms/op
     p(99.9900) =     15.511 ms/op
     p(99.9990) =     15.630 ms/op
     p(99.9999) =     15.630 ms/op
    p(100.0000) =     15.630 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.960 ±(99.9%) 0.051 ms/op
Iteration   1: 1.833 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.750 ms/op
                 existUser·p0.50:   1.638 ms/op
                 existUser·p0.90:   2.331 ms/op
                 existUser·p0.95:   2.458 ms/op
                 existUser·p0.99:   4.387 ms/op
                 existUser·p0.999:  20.054 ms/op
                 existUser·p0.9999: 20.193 ms/op
                 existUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17460
  mean =      1.833 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16807 
    [ 2.500,  5.000) = 518 
    [ 5.000,  7.500) = 10 
    [ 7.500, 10.000) = 29 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.750 ms/op
     p(50.0000) =      1.638 ms/op
     p(90.0000) =      2.331 ms/op
     p(95.0000) =      2.458 ms/op
     p(99.0000) =      4.387 ms/op
     p(99.9000) =     20.054 ms/op
     p(99.9900) =     20.193 ms/op
     p(99.9990) =     20.218 ms/op
     p(99.9999) =     20.218 ms/op
    p(100.0000) =     20.218 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.240 ±(99.9%) 0.082 ms/op
Iteration   1: 2.869 ±(99.9%) 0.112 ms/op
                 getUser·p0.00:   0.807 ms/op
                 getUser·p0.50:   2.400 ms/op
                 getUser·p0.90:   3.437 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   10.256 ms/op
                 getUser·p0.999:  63.692 ms/op
                 getUser·p0.9999: 64.982 ms/op
                 getUser·p1.00:   65.012 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11138
  mean =      2.869 ±(99.9%) 0.112 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 10872 
    [ 5.000, 10.000) = 144 
    [10.000, 15.000) = 51 
    [15.000, 20.000) = 6 
    [20.000, 25.000) = 2 
    [25.000, 30.000) = 12 
    [30.000, 35.000) = 14 
    [35.000, 40.000) = 5 
    [40.000, 45.000) = 1 
    [45.000, 50.000) = 2 
    [50.000, 55.000) = 3 
    [55.000, 60.000) = 6 
    [60.000, 65.000) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.807 ms/op
     p(50.0000) =      2.400 ms/op
     p(90.0000) =      3.437 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =     10.256 ms/op
     p(99.9000) =     63.692 ms/op
     p(99.9900) =     64.982 ms/op
     p(99.9990) =     65.012 ms/op
     p(99.9999) =     65.012 ms/op
    p(100.0000) =     65.012 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 11.908 ±(99.9%) 0.416 ms/op
Iteration   1: 8.354 ±(99.9%) 0.102 ms/op
                 listUser·p0.00:   2.896 ms/op
                 listUser·p0.50:   8.208 ms/op
                 listUser·p0.90:   10.797 ms/op
                 listUser·p0.95:   11.567 ms/op
                 listUser·p0.99:   13.730 ms/op
                 listUser·p0.999:  16.286 ms/op
                 listUser·p0.9999: 16.843 ms/op
                 listUser·p1.00:   16.843 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3830
  mean =      8.354 ±(99.9%) 0.102 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 0 
    [ 2.500,  3.750) = 17 
    [ 3.750,  5.000) = 80 
    [ 5.000,  6.250) = 364 
    [ 6.250,  7.500) = 844 
    [ 7.500,  8.750) = 1035 
    [ 8.750, 10.000) = 750 
    [10.000, 11.250) = 491 
    [11.250, 12.500) = 173 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.896 ms/op
     p(50.0000) =      8.208 ms/op
     p(90.0000) =     10.797 ms/op
     p(95.0000) =     11.567 ms/op
     p(99.0000) =     13.730 ms/op
     p(99.9000) =     16.286 ms/op
     p(99.9900) =     16.843 ms/op
     p(99.9990) =     16.843 ms/op
     p(99.9999) =     16.843 ms/op
    p(100.0000) =     16.843 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.148          ops/ms
Client.existUser                       thrpt         12.783          ops/ms
Client.getUser                         thrpt          7.715          ops/ms
Client.listUser                        thrpt          3.541          ops/ms
Client.createUser                       avgt          3.128           ms/op
Client.existUser                        avgt          1.993           ms/op
Client.getUser                          avgt          3.285           ms/op
Client.listUser                         avgt          7.463           ms/op
Client.createUser                     sample  11516   2.776 ± 0.031   ms/op
Client.createUser:createUser·p0.00    sample          0.951           ms/op
Client.createUser:createUser·p0.50    sample          2.666           ms/op
Client.createUser:createUser·p0.90    sample          3.375           ms/op
Client.createUser:createUser·p0.95    sample          3.949           ms/op
Client.createUser:createUser·p0.99    sample          6.799           ms/op
Client.createUser:createUser·p0.999   sample         14.786           ms/op
Client.createUser:createUser·p0.9999  sample         15.511           ms/op
Client.createUser:createUser·p1.00    sample         15.630           ms/op
Client.existUser                      sample  17460   1.833 ± 0.027   ms/op
Client.existUser:existUser·p0.00      sample          0.750           ms/op
Client.existUser:existUser·p0.50      sample          1.638           ms/op
Client.existUser:existUser·p0.90      sample          2.331           ms/op
Client.existUser:existUser·p0.95      sample          2.458           ms/op
Client.existUser:existUser·p0.99      sample          4.387           ms/op
Client.existUser:existUser·p0.999     sample         20.054           ms/op
Client.existUser:existUser·p0.9999    sample         20.193           ms/op
Client.existUser:existUser·p1.00      sample         20.218           ms/op
Client.getUser                        sample  11138   2.869 ± 0.112   ms/op
Client.getUser:getUser·p0.00          sample          0.807           ms/op
Client.getUser:getUser·p0.50          sample          2.400           ms/op
Client.getUser:getUser·p0.90          sample          3.437           ms/op
Client.getUser:getUser·p0.95          sample          3.916           ms/op
Client.getUser:getUser·p0.99          sample         10.256           ms/op
Client.getUser:getUser·p0.999         sample         63.692           ms/op
Client.getUser:getUser·p0.9999        sample         64.982           ms/op
Client.getUser:getUser·p1.00          sample         65.012           ms/op
Client.listUser                       sample   3830   8.354 ± 0.102   ms/op
Client.listUser:listUser·p0.00        sample          2.896           ms/op
Client.listUser:listUser·p0.50        sample          8.208           ms/op
Client.listUser:listUser·p0.90        sample         10.797           ms/op
Client.listUser:listUser·p0.95        sample         11.567           ms/op
Client.listUser:listUser·p0.99        sample         13.730           ms/op
Client.listUser:listUser·p0.999       sample         16.286           ms/op
Client.listUser:listUser·p0.9999      sample         16.843           ms/op
Client.listUser:listUser·p1.00        sample         16.843           ms/op
