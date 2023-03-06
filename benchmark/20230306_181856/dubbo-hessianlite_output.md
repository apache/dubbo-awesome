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
# Warmup Iteration   1: 0.566 ops/ms
Iteration   1: 1.077 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  1.077 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:26
# Fork: 1 of 1
# Warmup Iteration   1: 1.588 ops/ms
Iteration   1: 3.478 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.478 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 0.913 ops/ms
Iteration   1: 1.975 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  1.975 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 0.609 ops/ms
Iteration   1: 0.868 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  0.868 ops/ms


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

# Run progress: 33.33% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 25.490 ±(99.9%) 0.889 ms/op
Iteration   1: 18.235 ±(99.9%) 0.080 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  18.235 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:54
# Fork: 1 of 1
# Warmup Iteration   1: 23.175 ±(99.9%) 0.332 ms/op
Iteration   1: 9.261 ±(99.9%) 0.083 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  9.261 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:46
# Fork: 1 of 1
# Warmup Iteration   1: 21.181 ±(99.9%) 0.404 ms/op
Iteration   1: 10.580 ±(99.9%) 0.074 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  10.580 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:38
# Fork: 1 of 1
# Warmup Iteration   1: 39.163 ±(99.9%) 0.687 ms/op
Iteration   1: 29.384 ±(99.9%) 0.306 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  29.384 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:30
# Fork: 1 of 1
# Warmup Iteration   1: 26.142 ±(99.9%) 1.338 ms/op
Iteration   1: 13.283 ±(99.9%) 0.315 ms/op
                 createUser·p0.00:   7.119 ms/op
                 createUser·p0.50:   11.616 ms/op
                 createUser·p0.90:   20.480 ms/op
                 createUser·p0.95:   24.704 ms/op
                 createUser·p0.99:   29.592 ms/op
                 createUser·p0.999:  42.302 ms/op
                 createUser·p0.9999: 47.907 ms/op
                 createUser·p1.00:   47.907 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 2390
  mean =     13.283 ±(99.9%) 0.315 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 0 
    [ 5.000, 10.000) = 265 
    [10.000, 15.000) = 1594 
    [15.000, 20.000) = 273 
    [20.000, 25.000) = 150 
    [25.000, 30.000) = 89 
    [30.000, 35.000) = 16 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      7.119 ms/op
     p(50.0000) =     11.616 ms/op
     p(90.0000) =     20.480 ms/op
     p(95.0000) =     24.704 ms/op
     p(99.0000) =     29.592 ms/op
     p(99.9000) =     42.302 ms/op
     p(99.9900) =     47.907 ms/op
     p(99.9990) =     47.907 ms/op
     p(99.9999) =     47.907 ms/op
    p(100.0000) =     47.907 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:23
# Fork: 1 of 1
# Warmup Iteration   1: 13.968 ±(99.9%) 0.432 ms/op
Iteration   1: 7.157 ±(99.9%) 0.148 ms/op
                 existUser·p0.00:   1.102 ms/op
                 existUser·p0.50:   6.660 ms/op
                 existUser·p0.90:   9.896 ms/op
                 existUser·p0.95:   10.699 ms/op
                 existUser·p0.99:   23.221 ms/op
                 existUser·p0.999:  25.365 ms/op
                 existUser·p0.9999: 25.592 ms/op
                 existUser·p1.00:   25.592 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 4467
  mean =      7.157 ±(99.9%) 0.148 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22 
    [ 2.500,  5.000) = 608 
    [ 5.000,  7.500) = 2525 
    [ 7.500, 10.000) = 915 
    [10.000, 12.500) = 212 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.102 ms/op
     p(50.0000) =      6.660 ms/op
     p(90.0000) =      9.896 ms/op
     p(95.0000) =     10.699 ms/op
     p(99.0000) =     23.221 ms/op
     p(99.9000) =     25.365 ms/op
     p(99.9900) =     25.592 ms/op
     p(99.9990) =     25.592 ms/op
     p(99.9999) =     25.592 ms/op
    p(100.0000) =     25.592 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:15
# Fork: 1 of 1
# Warmup Iteration   1: 22.005 ±(99.9%) 0.676 ms/op
Iteration   1: 8.126 ±(99.9%) 0.180 ms/op
                 getUser·p0.00:   2.556 ms/op
                 getUser·p0.50:   7.086 ms/op
                 getUser·p0.90:   11.125 ms/op
                 getUser·p0.95:   15.860 ms/op
                 getUser·p0.99:   25.606 ms/op
                 getUser·p0.999:  31.297 ms/op
                 getUser·p0.9999: 31.490 ms/op
                 getUser·p1.00:   31.490 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 3938
  mean =      8.126 ±(99.9%) 0.180 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 160 
    [ 5.000,  7.500) = 2139 
    [ 7.500, 10.000) = 1127 
    [10.000, 12.500) = 222 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 122 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 28 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.556 ms/op
     p(50.0000) =      7.086 ms/op
     p(90.0000) =     11.125 ms/op
     p(95.0000) =     15.860 ms/op
     p(99.0000) =     25.606 ms/op
     p(99.9000) =     31.297 ms/op
     p(99.9900) =     31.490 ms/op
     p(99.9990) =     31.490 ms/op
     p(99.9999) =     31.490 ms/op
    p(100.0000) =     31.490 ms/op


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
# Warmup Iteration   1: 46.799 ±(99.9%) 1.885 ms/op
Iteration   1: 29.063 ±(99.9%) 1.006 ms/op
                 listUser·p0.00:   13.025 ms/op
                 listUser·p0.50:   26.640 ms/op
                 listUser·p0.90:   41.189 ms/op
                 listUser·p0.95:   48.759 ms/op
                 listUser·p0.99:   68.518 ms/op
                 listUser·p0.999:  74.465 ms/op
                 listUser·p0.9999: 74.711 ms/op
                 listUser·p1.00:   74.711 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1124
  mean =     29.063 ±(99.9%) 1.006 ms/op

  Histogram, ms/op:
    [10.000, 15.000) = 10 
    [15.000, 20.000) = 131 
    [20.000, 25.000) = 315 
    [25.000, 30.000) = 296 
    [30.000, 35.000) = 142 
    [35.000, 40.000) = 92 
    [40.000, 45.000) = 58 
    [45.000, 50.000) = 33 
    [50.000, 55.000) = 4 
    [55.000, 60.000) = 15 
    [60.000, 65.000) = 14 
    [65.000, 70.000) = 7 
    [70.000, 75.000) = 7 

  Percentiles, ms/op:
      p(0.0000) =     13.025 ms/op
     p(50.0000) =     26.640 ms/op
     p(90.0000) =     41.189 ms/op
     p(95.0000) =     48.759 ms/op
     p(99.0000) =     68.518 ms/op
     p(99.9000) =     74.465 ms/op
     p(99.9900) =     74.711 ms/op
     p(99.9990) =     74.711 ms/op
     p(99.9999) =     74.711 ms/op
    p(100.0000) =     74.711 ms/op


# Run complete. Total time: 00:01:33

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         1.077          ops/ms
Client.existUser                       thrpt         3.478          ops/ms
Client.getUser                         thrpt         1.975          ops/ms
Client.listUser                        thrpt         0.868          ops/ms
Client.createUser                       avgt        18.235           ms/op
Client.existUser                        avgt         9.261           ms/op
Client.getUser                          avgt        10.580           ms/op
Client.listUser                         avgt        29.384           ms/op
Client.createUser                     sample  2390  13.283 ± 0.315   ms/op
Client.createUser:createUser·p0.00    sample         7.119           ms/op
Client.createUser:createUser·p0.50    sample        11.616           ms/op
Client.createUser:createUser·p0.90    sample        20.480           ms/op
Client.createUser:createUser·p0.95    sample        24.704           ms/op
Client.createUser:createUser·p0.99    sample        29.592           ms/op
Client.createUser:createUser·p0.999   sample        42.302           ms/op
Client.createUser:createUser·p0.9999  sample        47.907           ms/op
Client.createUser:createUser·p1.00    sample        47.907           ms/op
Client.existUser                      sample  4467   7.157 ± 0.148   ms/op
Client.existUser:existUser·p0.00      sample         1.102           ms/op
Client.existUser:existUser·p0.50      sample         6.660           ms/op
Client.existUser:existUser·p0.90      sample         9.896           ms/op
Client.existUser:existUser·p0.95      sample        10.699           ms/op
Client.existUser:existUser·p0.99      sample        23.221           ms/op
Client.existUser:existUser·p0.999     sample        25.365           ms/op
Client.existUser:existUser·p0.9999    sample        25.592           ms/op
Client.existUser:existUser·p1.00      sample        25.592           ms/op
Client.getUser                        sample  3938   8.126 ± 0.180   ms/op
Client.getUser:getUser·p0.00          sample         2.556           ms/op
Client.getUser:getUser·p0.50          sample         7.086           ms/op
Client.getUser:getUser·p0.90          sample        11.125           ms/op
Client.getUser:getUser·p0.95          sample        15.860           ms/op
Client.getUser:getUser·p0.99          sample        25.606           ms/op
Client.getUser:getUser·p0.999         sample        31.297           ms/op
Client.getUser:getUser·p0.9999        sample        31.490           ms/op
Client.getUser:getUser·p1.00          sample        31.490           ms/op
Client.listUser                       sample  1124  29.063 ± 1.006   ms/op
Client.listUser:listUser·p0.00        sample        13.025           ms/op
Client.listUser:listUser·p0.50        sample        26.640           ms/op
Client.listUser:listUser·p0.90        sample        41.189           ms/op
Client.listUser:listUser·p0.95        sample        48.759           ms/op
Client.listUser:listUser·p0.99        sample        68.518           ms/op
Client.listUser:listUser·p0.999       sample        74.465           ms/op
Client.listUser:listUser·p0.9999      sample        74.711           ms/op
Client.listUser:listUser·p1.00        sample        74.711           ms/op
