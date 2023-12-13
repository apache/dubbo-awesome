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
# Warmup Iteration   1: 2.275 ops/ms
Iteration   1: 5.940 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.940 ops/ms


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
# Warmup Iteration   1: 6.299 ops/ms
Iteration   1: 13.425 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.425 ops/ms


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
# Warmup Iteration   1: 4.496 ops/ms
Iteration   1: 9.613 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.613 ops/ms


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
# Warmup Iteration   1: 1.936 ops/ms
Iteration   1: 3.432 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.432 ops/ms


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
# Warmup Iteration   1: 5.420 ±(99.9%) 0.082 ms/op
Iteration   1: 3.251 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.251 ms/op


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
# Warmup Iteration   1: 3.281 ±(99.9%) 0.043 ms/op
Iteration   1: 1.942 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.942 ms/op


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
# Warmup Iteration   1: 4.577 ±(99.9%) 0.050 ms/op
Iteration   1: 3.036 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.036 ms/op


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
# Warmup Iteration   1: 13.367 ±(99.9%) 0.220 ms/op
Iteration   1: 8.538 ±(99.9%) 0.107 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.538 ms/op


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
# Warmup Iteration   1: 5.214 ±(99.9%) 0.132 ms/op
Iteration   1: 3.117 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   1.009 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   4.186 ms/op
                 createUser·p0.99:   7.430 ms/op
                 createUser·p0.999:  14.722 ms/op
                 createUser·p0.9999: 24.054 ms/op
                 createUser·p1.00:   24.150 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10242
  mean =      3.117 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1734 
    [ 2.500,  5.000) = 8249 
    [ 5.000,  7.500) = 166 
    [ 7.500, 10.000) = 29 
    [10.000, 12.500) = 13 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.009 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      4.186 ms/op
     p(99.0000) =      7.430 ms/op
     p(99.9000) =     14.722 ms/op
     p(99.9900) =     24.054 ms/op
     p(99.9990) =     24.150 ms/op
     p(99.9999) =     24.150 ms/op
    p(100.0000) =     24.150 ms/op


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
# Warmup Iteration   1: 2.989 ±(99.9%) 0.074 ms/op
Iteration   1: 1.879 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.689 ms/op
                 existUser·p0.50:   1.774 ms/op
                 existUser·p0.90:   2.404 ms/op
                 existUser·p0.95:   2.580 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  13.812 ms/op
                 existUser·p0.9999: 13.980 ms/op
                 existUser·p1.00:   13.992 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17004
  mean =      1.879 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 612 
    [ 1.250,  2.500) = 15284 
    [ 2.500,  3.750) = 925 
    [ 3.750,  5.000) = 108 
    [ 5.000,  6.250) = 11 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.689 ms/op
     p(50.0000) =      1.774 ms/op
     p(90.0000) =      2.404 ms/op
     p(95.0000) =      2.580 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =     13.812 ms/op
     p(99.9900) =     13.980 ms/op
     p(99.9990) =     13.992 ms/op
     p(99.9999) =     13.992 ms/op
    p(100.0000) =     13.992 ms/op


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
# Warmup Iteration   1: 4.389 ±(99.9%) 0.101 ms/op
Iteration   1: 3.053 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.033 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   4.092 ms/op
                 getUser·p0.99:   4.910 ms/op
                 getUser·p0.999:  5.894 ms/op
                 getUser·p0.9999: 6.185 ms/op
                 getUser·p1.00:   6.185 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10465
  mean =      3.053 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 20 
    [1.500, 2.000) = 380 
    [2.000, 2.500) = 1670 
    [2.500, 3.000) = 3149 
    [3.000, 3.500) = 2665 
    [3.500, 4.000) = 1914 
    [4.000, 4.500) = 475 
    [4.500, 5.000) = 107 
    [5.000, 5.500) = 48 
    [5.500, 6.000) = 32 
    [6.000, 6.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.033 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.092 ms/op
     p(99.0000) =      4.910 ms/op
     p(99.9000) =      5.894 ms/op
     p(99.9900) =      6.185 ms/op
     p(99.9990) =      6.185 ms/op
     p(99.9999) =      6.185 ms/op
    p(100.0000) =      6.185 ms/op


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
# Warmup Iteration   1: 12.432 ±(99.9%) 0.425 ms/op
Iteration   1: 8.742 ±(99.9%) 0.136 ms/op
                 listUser·p0.00:   1.671 ms/op
                 listUser·p0.50:   8.454 ms/op
                 listUser·p0.90:   12.000 ms/op
                 listUser·p0.95:   13.369 ms/op
                 listUser·p0.99:   15.694 ms/op
                 listUser·p0.999:  19.874 ms/op
                 listUser·p0.9999: 24.314 ms/op
                 listUser·p1.00:   24.314 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3655
  mean =      8.742 ±(99.9%) 0.136 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 145 
    [ 5.000,  7.500) = 1080 
    [ 7.500, 10.000) = 1459 
    [10.000, 12.500) = 680 
    [12.500, 15.000) = 235 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.671 ms/op
     p(50.0000) =      8.454 ms/op
     p(90.0000) =     12.000 ms/op
     p(95.0000) =     13.369 ms/op
     p(99.0000) =     15.694 ms/op
     p(99.9000) =     19.874 ms/op
     p(99.9900) =     24.314 ms/op
     p(99.9990) =     24.314 ms/op
     p(99.9999) =     24.314 ms/op
    p(100.0000) =     24.314 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.940          ops/ms
Client.existUser                       thrpt         13.425          ops/ms
Client.getUser                         thrpt          9.613          ops/ms
Client.listUser                        thrpt          3.432          ops/ms
Client.createUser                       avgt          3.251           ms/op
Client.existUser                        avgt          1.942           ms/op
Client.getUser                          avgt          3.036           ms/op
Client.listUser                         avgt          8.538           ms/op
Client.createUser                     sample  10242   3.117 ± 0.037   ms/op
Client.createUser:createUser·p0.00    sample          1.009           ms/op
Client.createUser:createUser·p0.50    sample          2.970           ms/op
Client.createUser:createUser·p0.90    sample          3.678           ms/op
Client.createUser:createUser·p0.95    sample          4.186           ms/op
Client.createUser:createUser·p0.99    sample          7.430           ms/op
Client.createUser:createUser·p0.999   sample         14.722           ms/op
Client.createUser:createUser·p0.9999  sample         24.054           ms/op
Client.createUser:createUser·p1.00    sample         24.150           ms/op
Client.existUser                      sample  17004   1.879 ± 0.019   ms/op
Client.existUser:existUser·p0.00      sample          0.689           ms/op
Client.existUser:existUser·p0.50      sample          1.774           ms/op
Client.existUser:existUser·p0.90      sample          2.404           ms/op
Client.existUser:existUser·p0.95      sample          2.580           ms/op
Client.existUser:existUser·p0.99      sample          4.366           ms/op
Client.existUser:existUser·p0.999     sample         13.812           ms/op
Client.existUser:existUser·p0.9999    sample         13.980           ms/op
Client.existUser:existUser·p1.00      sample         13.992           ms/op
Client.getUser                        sample  10465   3.053 ± 0.021   ms/op
Client.getUser:getUser·p0.00          sample          1.033           ms/op
Client.getUser:getUser·p0.50          sample          3.002           ms/op
Client.getUser:getUser·p0.90          sample          3.871           ms/op
Client.getUser:getUser·p0.95          sample          4.092           ms/op
Client.getUser:getUser·p0.99          sample          4.910           ms/op
Client.getUser:getUser·p0.999         sample          5.894           ms/op
Client.getUser:getUser·p0.9999        sample          6.185           ms/op
Client.getUser:getUser·p1.00          sample          6.185           ms/op
Client.listUser                       sample   3655   8.742 ± 0.136   ms/op
Client.listUser:listUser·p0.00        sample          1.671           ms/op
Client.listUser:listUser·p0.50        sample          8.454           ms/op
Client.listUser:listUser·p0.90        sample         12.000           ms/op
Client.listUser:listUser·p0.95        sample         13.369           ms/op
Client.listUser:listUser·p0.99        sample         15.694           ms/op
Client.listUser:listUser·p0.999       sample         19.874           ms/op
Client.listUser:listUser·p0.9999      sample         24.314           ms/op
Client.listUser:listUser·p1.00        sample         24.314           ms/op
