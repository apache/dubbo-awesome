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
# Warmup Iteration   1: 2.469 ops/ms
Iteration   1: 5.536 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.536 ops/ms


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
# Warmup Iteration   1: 6.218 ops/ms
Iteration   1: 12.372 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.372 ops/ms


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
# Warmup Iteration   1: 4.044 ops/ms
Iteration   1: 8.411 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.411 ops/ms


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
# Warmup Iteration   1: 2.092 ops/ms
Iteration   1: 3.393 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.393 ops/ms


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
# Warmup Iteration   1: 5.721 ±(99.9%) 0.084 ms/op
Iteration   1: 3.161 ±(99.9%) 0.034 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.161 ms/op


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
# Warmup Iteration   1: 3.278 ±(99.9%) 0.050 ms/op
Iteration   1: 1.804 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.804 ms/op


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
# Warmup Iteration   1: 4.325 ±(99.9%) 0.052 ms/op
Iteration   1: 3.109 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.109 ms/op


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
# Warmup Iteration   1: 12.236 ±(99.9%) 0.181 ms/op
Iteration   1: 8.708 ±(99.9%) 0.109 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.708 ms/op


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
# Warmup Iteration   1: 4.943 ±(99.9%) 0.107 ms/op
Iteration   1: 3.093 ±(99.9%) 0.041 ms/op
                 createUser·p0.00:   0.815 ms/op
                 createUser·p0.50:   2.789 ms/op
                 createUser·p0.90:   3.891 ms/op
                 createUser·p0.95:   4.424 ms/op
                 createUser·p0.99:   9.322 ms/op
                 createUser·p0.999:  16.302 ms/op
                 createUser·p0.9999: 16.777 ms/op
                 createUser·p1.00:   16.777 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10338
  mean =      3.093 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 8 
    [ 1.250,  2.500) = 2546 
    [ 2.500,  3.750) = 6465 
    [ 3.750,  5.000) = 965 
    [ 5.000,  6.250) = 107 
    [ 6.250,  7.500) = 83 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 83 
    [10.000, 11.250) = 34 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.815 ms/op
     p(50.0000) =      2.789 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      9.322 ms/op
     p(99.9000) =     16.302 ms/op
     p(99.9900) =     16.777 ms/op
     p(99.9990) =     16.777 ms/op
     p(99.9999) =     16.777 ms/op
    p(100.0000) =     16.777 ms/op


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
# Warmup Iteration   1: 3.045 ±(99.9%) 0.072 ms/op
Iteration   1: 2.019 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.569 ms/op
                 existUser·p0.50:   1.993 ms/op
                 existUser·p0.90:   2.540 ms/op
                 existUser·p0.95:   2.732 ms/op
                 existUser·p0.99:   3.764 ms/op
                 existUser·p0.999:  16.040 ms/op
                 existUser·p0.9999: 17.172 ms/op
                 existUser·p1.00:   17.498 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15858
  mean =      2.019 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 358 
    [ 1.250,  2.500) = 13709 
    [ 2.500,  3.750) = 1631 
    [ 3.750,  5.000) = 94 
    [ 5.000,  6.250) = 31 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.569 ms/op
     p(50.0000) =      1.993 ms/op
     p(90.0000) =      2.540 ms/op
     p(95.0000) =      2.732 ms/op
     p(99.0000) =      3.764 ms/op
     p(99.9000) =     16.040 ms/op
     p(99.9900) =     17.172 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.770 ±(99.9%) 0.110 ms/op
Iteration   1: 3.176 ±(99.9%) 0.032 ms/op
                 getUser·p0.00:   0.980 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   4.178 ms/op
                 getUser·p0.95:   4.465 ms/op
                 getUser·p0.99:   5.574 ms/op
                 getUser·p0.999:  12.778 ms/op
                 getUser·p0.9999: 14.941 ms/op
                 getUser·p1.00:   14.942 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10077
  mean =      3.176 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 23 
    [ 1.250,  2.500) = 2202 
    [ 2.500,  3.750) = 5887 
    [ 3.750,  5.000) = 1828 
    [ 5.000,  6.250) = 77 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.980 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      4.178 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      5.574 ms/op
     p(99.9000) =     12.778 ms/op
     p(99.9900) =     14.941 ms/op
     p(99.9990) =     14.942 ms/op
     p(99.9999) =     14.942 ms/op
    p(100.0000) =     14.942 ms/op


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
# Warmup Iteration   1: 12.793 ±(99.9%) 0.482 ms/op
Iteration   1: 8.113 ±(99.9%) 0.112 ms/op
                 listUser·p0.00:   2.032 ms/op
                 listUser·p0.50:   7.791 ms/op
                 listUser·p0.90:   10.535 ms/op
                 listUser·p0.95:   11.814 ms/op
                 listUser·p0.99:   16.048 ms/op
                 listUser·p0.999:  19.382 ms/op
                 listUser·p0.9999: 21.234 ms/op
                 listUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3958
  mean =      8.113 ±(99.9%) 0.112 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 111 
    [ 5.000,  7.500) = 1598 
    [ 7.500, 10.000) = 1689 
    [10.000, 12.500) = 410 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.032 ms/op
     p(50.0000) =      7.791 ms/op
     p(90.0000) =     10.535 ms/op
     p(95.0000) =     11.814 ms/op
     p(99.0000) =     16.048 ms/op
     p(99.9000) =     19.382 ms/op
     p(99.9900) =     21.234 ms/op
     p(99.9990) =     21.234 ms/op
     p(99.9999) =     21.234 ms/op
    p(100.0000) =     21.234 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.536          ops/ms
Client.existUser                       thrpt         12.372          ops/ms
Client.getUser                         thrpt          8.411          ops/ms
Client.listUser                        thrpt          3.393          ops/ms
Client.createUser                       avgt          3.161           ms/op
Client.existUser                        avgt          1.804           ms/op
Client.getUser                          avgt          3.109           ms/op
Client.listUser                         avgt          8.708           ms/op
Client.createUser                     sample  10338   3.093 ± 0.041   ms/op
Client.createUser:createUser·p0.00    sample          0.815           ms/op
Client.createUser:createUser·p0.50    sample          2.789           ms/op
Client.createUser:createUser·p0.90    sample          3.891           ms/op
Client.createUser:createUser·p0.95    sample          4.424           ms/op
Client.createUser:createUser·p0.99    sample          9.322           ms/op
Client.createUser:createUser·p0.999   sample         16.302           ms/op
Client.createUser:createUser·p0.9999  sample         16.777           ms/op
Client.createUser:createUser·p1.00    sample         16.777           ms/op
Client.existUser                      sample  15858   2.019 ± 0.021   ms/op
Client.existUser:existUser·p0.00      sample          0.569           ms/op
Client.existUser:existUser·p0.50      sample          1.993           ms/op
Client.existUser:existUser·p0.90      sample          2.540           ms/op
Client.existUser:existUser·p0.95      sample          2.732           ms/op
Client.existUser:existUser·p0.99      sample          3.764           ms/op
Client.existUser:existUser·p0.999     sample         16.040           ms/op
Client.existUser:existUser·p0.9999    sample         17.172           ms/op
Client.existUser:existUser·p1.00      sample         17.498           ms/op
Client.getUser                        sample  10077   3.176 ± 0.032   ms/op
Client.getUser:getUser·p0.00          sample          0.980           ms/op
Client.getUser:getUser·p0.50          sample          3.138           ms/op
Client.getUser:getUser·p0.90          sample          4.178           ms/op
Client.getUser:getUser·p0.95          sample          4.465           ms/op
Client.getUser:getUser·p0.99          sample          5.574           ms/op
Client.getUser:getUser·p0.999         sample         12.778           ms/op
Client.getUser:getUser·p0.9999        sample         14.941           ms/op
Client.getUser:getUser·p1.00          sample         14.942           ms/op
Client.listUser                       sample   3958   8.113 ± 0.112   ms/op
Client.listUser:listUser·p0.00        sample          2.032           ms/op
Client.listUser:listUser·p0.50        sample          7.791           ms/op
Client.listUser:listUser·p0.90        sample         10.535           ms/op
Client.listUser:listUser·p0.95        sample         11.814           ms/op
Client.listUser:listUser·p0.99        sample         16.048           ms/op
Client.listUser:listUser·p0.999       sample         19.382           ms/op
Client.listUser:listUser·p0.9999      sample         21.234           ms/op
Client.listUser:listUser·p1.00        sample         21.234           ms/op
