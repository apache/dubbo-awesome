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
# Warmup Iteration   1: 2.158 ops/ms
Iteration   1: 6.565 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.565 ops/ms


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
# Warmup Iteration   1: 5.841 ops/ms
Iteration   1: 11.664 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.664 ops/ms


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
# Warmup Iteration   1: 3.542 ops/ms
Iteration   1: 8.160 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.160 ops/ms


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
# Warmup Iteration   1: 2.195 ops/ms
Iteration   1: 3.270 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.270 ops/ms


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
# Warmup Iteration   1: 5.521 ±(99.9%) 0.082 ms/op
Iteration   1: 3.278 ±(99.9%) 0.032 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.278 ms/op


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
# Warmup Iteration   1: 3.826 ±(99.9%) 0.050 ms/op
Iteration   1: 1.881 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.881 ms/op


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
# Warmup Iteration   1: 5.464 ±(99.9%) 0.100 ms/op
Iteration   1: 3.083 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.083 ms/op


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
# Warmup Iteration   1: 13.027 ±(99.9%) 0.256 ms/op
Iteration   1: 8.224 ±(99.9%) 0.069 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.224 ms/op


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
# Warmup Iteration   1: 5.817 ±(99.9%) 0.130 ms/op
Iteration   1: 3.385 ±(99.9%) 0.044 ms/op
                 createUser·p0.00:   1.503 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   4.047 ms/op
                 createUser·p0.95:   4.547 ms/op
                 createUser·p0.99:   11.199 ms/op
                 createUser·p0.999:  14.365 ms/op
                 createUser·p0.9999: 15.663 ms/op
                 createUser·p1.00:   15.663 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9446
  mean =      3.385 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1092 
    [ 2.500,  3.750) = 6652 
    [ 3.750,  5.000) = 1353 
    [ 5.000,  6.250) = 134 
    [ 6.250,  7.500) = 53 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 41 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.503 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      4.047 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =     11.199 ms/op
     p(99.9000) =     14.365 ms/op
     p(99.9900) =     15.663 ms/op
     p(99.9990) =     15.663 ms/op
     p(99.9999) =     15.663 ms/op
    p(100.0000) =     15.663 ms/op


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
# Warmup Iteration   1: 3.070 ±(99.9%) 0.068 ms/op
Iteration   1: 1.803 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.498 ms/op
                 existUser·p0.50:   1.749 ms/op
                 existUser·p0.90:   2.212 ms/op
                 existUser·p0.95:   2.413 ms/op
                 existUser·p0.99:   3.240 ms/op
                 existUser·p0.999:  5.286 ms/op
                 existUser·p0.9999: 5.427 ms/op
                 existUser·p1.00:   5.497 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17733
  mean =      1.803 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 1 
    [0.500, 1.000) = 174 
    [1.000, 1.500) = 3169 
    [1.500, 2.000) = 10087 
    [2.000, 2.500) = 3612 
    [2.500, 3.000) = 438 
    [3.000, 3.500) = 135 
    [3.500, 4.000) = 57 
    [4.000, 4.500) = 25 
    [4.500, 5.000) = 3 
    [5.000, 5.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.498 ms/op
     p(50.0000) =      1.749 ms/op
     p(90.0000) =      2.212 ms/op
     p(95.0000) =      2.413 ms/op
     p(99.0000) =      3.240 ms/op
     p(99.9000) =      5.286 ms/op
     p(99.9900) =      5.427 ms/op
     p(99.9990) =      5.497 ms/op
     p(99.9999) =      5.497 ms/op
    p(100.0000) =      5.497 ms/op


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
# Warmup Iteration   1: 5.116 ±(99.9%) 0.132 ms/op
Iteration   1: 3.261 ±(99.9%) 0.065 ms/op
                 getUser·p0.00:   0.966 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   4.175 ms/op
                 getUser·p0.95:   4.522 ms/op
                 getUser·p0.99:   6.046 ms/op
                 getUser·p0.999:  34.669 ms/op
                 getUser·p0.9999: 35.127 ms/op
                 getUser·p1.00:   35.127 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9797
  mean =      3.261 ±(99.9%) 0.065 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2022 
    [ 2.500,  5.000) = 7531 
    [ 5.000,  7.500) = 169 
    [ 7.500, 10.000) = 40 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.966 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      4.175 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      6.046 ms/op
     p(99.9000) =     34.669 ms/op
     p(99.9900) =     35.127 ms/op
     p(99.9990) =     35.127 ms/op
     p(99.9999) =     35.127 ms/op
    p(100.0000) =     35.127 ms/op


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
# Warmup Iteration   1: 12.102 ±(99.9%) 0.406 ms/op
Iteration   1: 9.278 ±(99.9%) 0.172 ms/op
                 listUser·p0.00:   2.847 ms/op
                 listUser·p0.50:   8.831 ms/op
                 listUser·p0.90:   11.944 ms/op
                 listUser·p0.95:   13.353 ms/op
                 listUser·p0.99:   24.288 ms/op
                 listUser·p0.999:  25.539 ms/op
                 listUser·p0.9999: 25.887 ms/op
                 listUser·p1.00:   25.887 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3459
  mean =      9.278 ±(99.9%) 0.172 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 66 
    [ 5.000,  7.500) = 836 
    [ 7.500, 10.000) = 1449 
    [10.000, 12.500) = 862 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      2.847 ms/op
     p(50.0000) =      8.831 ms/op
     p(90.0000) =     11.944 ms/op
     p(95.0000) =     13.353 ms/op
     p(99.0000) =     24.288 ms/op
     p(99.9000) =     25.539 ms/op
     p(99.9900) =     25.887 ms/op
     p(99.9990) =     25.887 ms/op
     p(99.9999) =     25.887 ms/op
    p(100.0000) =     25.887 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.565          ops/ms
Client.existUser                       thrpt         11.664          ops/ms
Client.getUser                         thrpt          8.160          ops/ms
Client.listUser                        thrpt          3.270          ops/ms
Client.createUser                       avgt          3.278           ms/op
Client.existUser                        avgt          1.881           ms/op
Client.getUser                          avgt          3.083           ms/op
Client.listUser                         avgt          8.224           ms/op
Client.createUser                     sample   9446   3.385 ± 0.044   ms/op
Client.createUser:createUser·p0.00    sample          1.503           ms/op
Client.createUser:createUser·p0.50    sample          3.203           ms/op
Client.createUser:createUser·p0.90    sample          4.047           ms/op
Client.createUser:createUser·p0.95    sample          4.547           ms/op
Client.createUser:createUser·p0.99    sample         11.199           ms/op
Client.createUser:createUser·p0.999   sample         14.365           ms/op
Client.createUser:createUser·p0.9999  sample         15.663           ms/op
Client.createUser:createUser·p1.00    sample         15.663           ms/op
Client.existUser                      sample  17733   1.803 ± 0.010   ms/op
Client.existUser:existUser·p0.00      sample          0.498           ms/op
Client.existUser:existUser·p0.50      sample          1.749           ms/op
Client.existUser:existUser·p0.90      sample          2.212           ms/op
Client.existUser:existUser·p0.95      sample          2.413           ms/op
Client.existUser:existUser·p0.99      sample          3.240           ms/op
Client.existUser:existUser·p0.999     sample          5.286           ms/op
Client.existUser:existUser·p0.9999    sample          5.427           ms/op
Client.existUser:existUser·p1.00      sample          5.497           ms/op
Client.getUser                        sample   9797   3.261 ± 0.065   ms/op
Client.getUser:getUser·p0.00          sample          0.966           ms/op
Client.getUser:getUser·p0.50          sample          3.031           ms/op
Client.getUser:getUser·p0.90          sample          4.175           ms/op
Client.getUser:getUser·p0.95          sample          4.522           ms/op
Client.getUser:getUser·p0.99          sample          6.046           ms/op
Client.getUser:getUser·p0.999         sample         34.669           ms/op
Client.getUser:getUser·p0.9999        sample         35.127           ms/op
Client.getUser:getUser·p1.00          sample         35.127           ms/op
Client.listUser                       sample   3459   9.278 ± 0.172   ms/op
Client.listUser:listUser·p0.00        sample          2.847           ms/op
Client.listUser:listUser·p0.50        sample          8.831           ms/op
Client.listUser:listUser·p0.90        sample         11.944           ms/op
Client.listUser:listUser·p0.95        sample         13.353           ms/op
Client.listUser:listUser·p0.99        sample         24.288           ms/op
Client.listUser:listUser·p0.999       sample         25.539           ms/op
Client.listUser:listUser·p0.9999      sample         25.887           ms/op
Client.listUser:listUser·p1.00        sample         25.887           ms/op
