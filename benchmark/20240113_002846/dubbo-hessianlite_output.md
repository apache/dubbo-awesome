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
# Warmup Iteration   1: 2.391 ops/ms
Iteration   1: 6.678 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.678 ops/ms


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
# Warmup Iteration   1: 6.229 ops/ms
Iteration   1: 12.751 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.751 ops/ms


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
# Warmup Iteration   1: 4.290 ops/ms
Iteration   1: 9.634 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.634 ops/ms


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
# Warmup Iteration   1: 2.255 ops/ms
Iteration   1: 4.342 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  4.342 ops/ms


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
# Warmup Iteration   1: 5.285 ±(99.9%) 0.070 ms/op
Iteration   1: 2.886 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.886 ms/op


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
# Warmup Iteration   1: 3.083 ±(99.9%) 0.028 ms/op
Iteration   1: 2.057 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.057 ms/op


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
# Warmup Iteration   1: 4.330 ±(99.9%) 0.048 ms/op
Iteration   1: 3.117 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.117 ms/op


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
# Warmup Iteration   1: 11.981 ±(99.9%) 0.328 ms/op
Iteration   1: 9.037 ±(99.9%) 0.076 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.037 ms/op


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
# Warmup Iteration   1: 5.168 ±(99.9%) 0.137 ms/op
Iteration   1: 3.204 ±(99.9%) 0.067 ms/op
                 createUser·p0.00:   0.906 ms/op
                 createUser·p0.50:   2.806 ms/op
                 createUser·p0.90:   3.813 ms/op
                 createUser·p0.95:   4.719 ms/op
                 createUser·p0.99:   13.251 ms/op
                 createUser·p0.999:  25.461 ms/op
                 createUser·p0.9999: 34.144 ms/op
                 createUser·p1.00:   34.144 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9979
  mean =      3.204 ±(99.9%) 0.067 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3050 
    [ 2.500,  5.000) = 6491 
    [ 5.000,  7.500) = 161 
    [ 7.500, 10.000) = 55 
    [10.000, 12.500) = 122 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 17 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.906 ms/op
     p(50.0000) =      2.806 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =     13.251 ms/op
     p(99.9000) =     25.461 ms/op
     p(99.9900) =     34.144 ms/op
     p(99.9990) =     34.144 ms/op
     p(99.9999) =     34.144 ms/op
    p(100.0000) =     34.144 ms/op


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
# Warmup Iteration   1: 3.337 ±(99.9%) 0.077 ms/op
Iteration   1: 2.057 ±(99.9%) 0.030 ms/op
                 existUser·p0.00:   0.365 ms/op
                 existUser·p0.50:   1.968 ms/op
                 existUser·p0.90:   2.474 ms/op
                 existUser·p0.95:   2.675 ms/op
                 existUser·p0.99:   5.028 ms/op
                 existUser·p0.999:  21.151 ms/op
                 existUser·p0.9999: 21.758 ms/op
                 existUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15519
  mean =      2.057 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14139 
    [ 2.500,  5.000) = 1218 
    [ 5.000,  7.500) = 66 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.365 ms/op
     p(50.0000) =      1.968 ms/op
     p(90.0000) =      2.474 ms/op
     p(95.0000) =      2.675 ms/op
     p(99.0000) =      5.028 ms/op
     p(99.9000) =     21.151 ms/op
     p(99.9900) =     21.758 ms/op
     p(99.9990) =     21.758 ms/op
     p(99.9999) =     21.758 ms/op
    p(100.0000) =     21.758 ms/op


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
# Warmup Iteration   1: 4.176 ±(99.9%) 0.100 ms/op
Iteration   1: 3.263 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.590 ms/op
                 getUser·p0.50:   3.211 ms/op
                 getUser·p0.90:   3.974 ms/op
                 getUser·p0.95:   4.456 ms/op
                 getUser·p0.99:   5.559 ms/op
                 getUser·p0.999:  6.702 ms/op
                 getUser·p0.9999: 8.241 ms/op
                 getUser·p1.00:   8.241 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9948
  mean =      3.263 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 4 
    [1.000, 1.500) = 21 
    [1.500, 2.000) = 124 
    [2.000, 2.500) = 640 
    [2.500, 3.000) = 2789 
    [3.000, 3.500) = 3271 
    [3.500, 4.000) = 2152 
    [4.000, 4.500) = 488 
    [4.500, 5.000) = 246 
    [5.000, 5.500) = 106 
    [5.500, 6.000) = 75 
    [6.000, 6.500) = 14 
    [6.500, 7.000) = 11 
    [7.000, 7.500) = 1 
    [7.500, 8.000) = 5 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.590 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.974 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      5.559 ms/op
     p(99.9000) =      6.702 ms/op
     p(99.9900) =      8.241 ms/op
     p(99.9990) =      8.241 ms/op
     p(99.9999) =      8.241 ms/op
    p(100.0000) =      8.241 ms/op


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
# Warmup Iteration   1: 11.506 ±(99.9%) 0.435 ms/op
Iteration   1: 6.965 ±(99.9%) 0.092 ms/op
                 listUser·p0.00:   2.544 ms/op
                 listUser·p0.50:   6.668 ms/op
                 listUser·p0.90:   9.060 ms/op
                 listUser·p0.95:   10.174 ms/op
                 listUser·p0.99:   13.619 ms/op
                 listUser·p0.999:  19.672 ms/op
                 listUser·p0.9999: 20.152 ms/op
                 listUser·p1.00:   20.152 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4588
  mean =      6.965 ±(99.9%) 0.092 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 450 
    [ 5.000,  7.500) = 2746 
    [ 7.500, 10.000) = 1134 
    [10.000, 12.500) = 192 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.544 ms/op
     p(50.0000) =      6.668 ms/op
     p(90.0000) =      9.060 ms/op
     p(95.0000) =     10.174 ms/op
     p(99.0000) =     13.619 ms/op
     p(99.9000) =     19.672 ms/op
     p(99.9900) =     20.152 ms/op
     p(99.9990) =     20.152 ms/op
     p(99.9999) =     20.152 ms/op
    p(100.0000) =     20.152 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.678          ops/ms
Client.existUser                       thrpt         12.751          ops/ms
Client.getUser                         thrpt          9.634          ops/ms
Client.listUser                        thrpt          4.342          ops/ms
Client.createUser                       avgt          2.886           ms/op
Client.existUser                        avgt          2.057           ms/op
Client.getUser                          avgt          3.117           ms/op
Client.listUser                         avgt          9.037           ms/op
Client.createUser                     sample   9979   3.204 ± 0.067   ms/op
Client.createUser:createUser·p0.00    sample          0.906           ms/op
Client.createUser:createUser·p0.50    sample          2.806           ms/op
Client.createUser:createUser·p0.90    sample          3.813           ms/op
Client.createUser:createUser·p0.95    sample          4.719           ms/op
Client.createUser:createUser·p0.99    sample         13.251           ms/op
Client.createUser:createUser·p0.999   sample         25.461           ms/op
Client.createUser:createUser·p0.9999  sample         34.144           ms/op
Client.createUser:createUser·p1.00    sample         34.144           ms/op
Client.existUser                      sample  15519   2.057 ± 0.030   ms/op
Client.existUser:existUser·p0.00      sample          0.365           ms/op
Client.existUser:existUser·p0.50      sample          1.968           ms/op
Client.existUser:existUser·p0.90      sample          2.474           ms/op
Client.existUser:existUser·p0.95      sample          2.675           ms/op
Client.existUser:existUser·p0.99      sample          5.028           ms/op
Client.existUser:existUser·p0.999     sample         21.151           ms/op
Client.existUser:existUser·p0.9999    sample         21.758           ms/op
Client.existUser:existUser·p1.00      sample         21.758           ms/op
Client.getUser                        sample   9948   3.263 ± 0.022   ms/op
Client.getUser:getUser·p0.00          sample          0.590           ms/op
Client.getUser:getUser·p0.50          sample          3.211           ms/op
Client.getUser:getUser·p0.90          sample          3.974           ms/op
Client.getUser:getUser·p0.95          sample          4.456           ms/op
Client.getUser:getUser·p0.99          sample          5.559           ms/op
Client.getUser:getUser·p0.999         sample          6.702           ms/op
Client.getUser:getUser·p0.9999        sample          8.241           ms/op
Client.getUser:getUser·p1.00          sample          8.241           ms/op
Client.listUser                       sample   4588   6.965 ± 0.092   ms/op
Client.listUser:listUser·p0.00        sample          2.544           ms/op
Client.listUser:listUser·p0.50        sample          6.668           ms/op
Client.listUser:listUser·p0.90        sample          9.060           ms/op
Client.listUser:listUser·p0.95        sample         10.174           ms/op
Client.listUser:listUser·p0.99        sample         13.619           ms/op
Client.listUser:listUser·p0.999       sample         19.672           ms/op
Client.listUser:listUser·p0.9999      sample         20.152           ms/op
Client.listUser:listUser·p1.00        sample         20.152           ms/op
