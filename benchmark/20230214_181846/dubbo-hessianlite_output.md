# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.131 ops/ms
Iteration   1: 2.323 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.323 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 2.632 ops/ms
Iteration   1: 6.164 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.164 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.113 ops/ms
Iteration   1: 4.420 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.420 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 0.803 ops/ms
Iteration   1: 1.274 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.274 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 15.569 ±(99.9%) 0.284 ms/op
Iteration   1: 9.346 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  9.346 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 6.880 ±(99.9%) 0.083 ms/op
Iteration   1: 3.913 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.913 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 10.063 ±(99.9%) 0.134 ms/op
Iteration   1: 4.732 ±(99.9%) 0.034 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.732 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 28.319 ±(99.9%) 0.531 ms/op
Iteration   1: 17.196 ±(99.9%) 0.075 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  17.196 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 12.394 ±(99.9%) 0.356 ms/op
Iteration   1: 5.839 ±(99.9%) 0.098 ms/op
                 createUser·p0.00:   2.245 ms/op
                 createUser·p0.50:   5.931 ms/op
                 createUser·p0.90:   6.922 ms/op
                 createUser·p0.95:   8.249 ms/op
                 createUser·p0.99:   15.172 ms/op
                 createUser·p0.999:  23.726 ms/op
                 createUser·p0.9999: 24.084 ms/op
                 createUser·p1.00:   24.084 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5467
  mean =      5.839 ±(99.9%) 0.098 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 1316 
    [ 5.000,  7.500) = 3739 
    [ 7.500, 10.000) = 199 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.245 ms/op
     p(50.0000) =      5.931 ms/op
     p(90.0000) =      6.922 ms/op
     p(95.0000) =      8.249 ms/op
     p(99.0000) =     15.172 ms/op
     p(99.9000) =     23.726 ms/op
     p(99.9900) =     24.084 ms/op
     p(99.9990) =     24.084 ms/op
     p(99.9999) =     24.084 ms/op
    p(100.0000) =     24.084 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 6.067 ±(99.9%) 0.216 ms/op
Iteration   1: 4.485 ±(99.9%) 0.050 ms/op
                 existUser·p0.00:   1.274 ms/op
                 existUser·p0.50:   4.194 ms/op
                 existUser·p0.90:   4.915 ms/op
                 existUser·p0.95:   6.414 ms/op
                 existUser·p0.99:   12.141 ms/op
                 existUser·p0.999:  12.796 ms/op
                 existUser·p0.9999: 13.173 ms/op
                 existUser·p1.00:   13.173 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 7097
  mean =      4.485 ±(99.9%) 0.050 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 53 
    [ 2.500,  3.750) = 316 
    [ 3.750,  5.000) = 6106 
    [ 5.000,  6.250) = 227 
    [ 6.250,  7.500) = 157 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 49 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.274 ms/op
     p(50.0000) =      4.194 ms/op
     p(90.0000) =      4.915 ms/op
     p(95.0000) =      6.414 ms/op
     p(99.0000) =     12.141 ms/op
     p(99.9000) =     12.796 ms/op
     p(99.9900) =     13.173 ms/op
     p(99.9990) =     13.173 ms/op
     p(99.9999) =     13.173 ms/op
    p(100.0000) =     13.173 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 9.907 ±(99.9%) 0.336 ms/op
Iteration   1: 4.770 ±(99.9%) 0.051 ms/op
                 getUser·p0.00:   1.917 ms/op
                 getUser·p0.50:   4.596 ms/op
                 getUser·p0.90:   5.267 ms/op
                 getUser·p0.95:   5.739 ms/op
                 getUser·p0.99:   10.157 ms/op
                 getUser·p0.999:  18.917 ms/op
                 getUser·p0.9999: 19.497 ms/op
                 getUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6707
  mean =      4.770 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 8 
    [ 2.500,  3.750) = 339 
    [ 3.750,  5.000) = 5256 
    [ 5.000,  6.250) = 868 
    [ 6.250,  7.500) = 113 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 34 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.917 ms/op
     p(50.0000) =      4.596 ms/op
     p(90.0000) =      5.267 ms/op
     p(95.0000) =      5.739 ms/op
     p(99.0000) =     10.157 ms/op
     p(99.9000) =     18.917 ms/op
     p(99.9900) =     19.497 ms/op
     p(99.9990) =     19.497 ms/op
     p(99.9999) =     19.497 ms/op
    p(100.0000) =     19.497 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 30.720 ±(99.9%) 0.923 ms/op
Iteration   1: 18.038 ±(99.9%) 0.220 ms/op
                 listUser·p0.00:   6.930 ms/op
                 listUser·p0.50:   17.793 ms/op
                 listUser·p0.90:   20.283 ms/op
                 listUser·p0.95:   20.611 ms/op
                 listUser·p0.99:   30.912 ms/op
                 listUser·p0.999:  37.644 ms/op
                 listUser·p0.9999: 37.945 ms/op
                 listUser·p1.00:   37.945 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1765
  mean =     18.038 ±(99.9%) 0.220 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 1 
    [ 7.500, 10.000) = 15 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 605 
    [17.500, 20.000) = 808 
    [20.000, 22.500) = 193 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 9 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      6.930 ms/op
     p(50.0000) =     17.793 ms/op
     p(90.0000) =     20.283 ms/op
     p(95.0000) =     20.611 ms/op
     p(99.0000) =     30.912 ms/op
     p(99.9000) =     37.644 ms/op
     p(99.9900) =     37.945 ms/op
     p(99.9990) =     37.945 ms/op
     p(99.9999) =     37.945 ms/op
    p(100.0000) =     37.945 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.323          ops/ms
Client.existUser                       thrpt         6.164          ops/ms
Client.getUser                         thrpt         4.420          ops/ms
Client.listUser                        thrpt         1.274          ops/ms
Client.createUser                       avgt         9.346           ms/op
Client.existUser                        avgt         3.913           ms/op
Client.getUser                          avgt         4.732           ms/op
Client.listUser                         avgt        17.196           ms/op
Client.createUser                     sample  5467   5.839 ± 0.098   ms/op
Client.createUser:createUser·p0.00    sample         2.245           ms/op
Client.createUser:createUser·p0.50    sample         5.931           ms/op
Client.createUser:createUser·p0.90    sample         6.922           ms/op
Client.createUser:createUser·p0.95    sample         8.249           ms/op
Client.createUser:createUser·p0.99    sample        15.172           ms/op
Client.createUser:createUser·p0.999   sample        23.726           ms/op
Client.createUser:createUser·p0.9999  sample        24.084           ms/op
Client.createUser:createUser·p1.00    sample        24.084           ms/op
Client.existUser                      sample  7097   4.485 ± 0.050   ms/op
Client.existUser:existUser·p0.00      sample         1.274           ms/op
Client.existUser:existUser·p0.50      sample         4.194           ms/op
Client.existUser:existUser·p0.90      sample         4.915           ms/op
Client.existUser:existUser·p0.95      sample         6.414           ms/op
Client.existUser:existUser·p0.99      sample        12.141           ms/op
Client.existUser:existUser·p0.999     sample        12.796           ms/op
Client.existUser:existUser·p0.9999    sample        13.173           ms/op
Client.existUser:existUser·p1.00      sample        13.173           ms/op
Client.getUser                        sample  6707   4.770 ± 0.051   ms/op
Client.getUser:getUser·p0.00          sample         1.917           ms/op
Client.getUser:getUser·p0.50          sample         4.596           ms/op
Client.getUser:getUser·p0.90          sample         5.267           ms/op
Client.getUser:getUser·p0.95          sample         5.739           ms/op
Client.getUser:getUser·p0.99          sample        10.157           ms/op
Client.getUser:getUser·p0.999         sample        18.917           ms/op
Client.getUser:getUser·p0.9999        sample        19.497           ms/op
Client.getUser:getUser·p1.00          sample        19.497           ms/op
Client.listUser                       sample  1765  18.038 ± 0.220   ms/op
Client.listUser:listUser·p0.00        sample         6.930           ms/op
Client.listUser:listUser·p0.50        sample        17.793           ms/op
Client.listUser:listUser·p0.90        sample        20.283           ms/op
Client.listUser:listUser·p0.95        sample        20.611           ms/op
Client.listUser:listUser·p0.99        sample        30.912           ms/op
Client.listUser:listUser·p0.999       sample        37.644           ms/op
Client.listUser:listUser·p0.9999      sample        37.945           ms/op
Client.listUser:listUser·p1.00        sample        37.945           ms/op
