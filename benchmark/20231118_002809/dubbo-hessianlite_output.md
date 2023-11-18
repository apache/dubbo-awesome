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
# Warmup Iteration   1: 2.540 ops/ms
Iteration   1: 5.733 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.733 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 7.072 ops/ms
Iteration   1: 12.266 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.266 ops/ms


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
# Warmup Iteration   1: 4.090 ops/ms
Iteration   1: 9.030 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.030 ops/ms


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
# Warmup Iteration   1: 2.063 ops/ms
Iteration   1: 3.584 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.584 ops/ms


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
# Warmup Iteration   1: 5.170 ±(99.9%) 0.090 ms/op
Iteration   1: 3.296 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.296 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.401 ±(99.9%) 0.038 ms/op
Iteration   1: 1.878 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.878 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.246 ±(99.9%) 0.053 ms/op
Iteration   1: 2.879 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.879 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 13.083 ±(99.9%) 0.313 ms/op
Iteration   1: 8.540 ±(99.9%) 0.129 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.540 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.931 ±(99.9%) 0.091 ms/op
Iteration   1: 2.951 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   0.639 ms/op
                 createUser·p0.50:   2.720 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   4.350 ms/op
                 createUser·p0.99:   5.577 ms/op
                 createUser·p0.999:  17.668 ms/op
                 createUser·p0.9999: 17.886 ms/op
                 createUser·p1.00:   17.891 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10823
  mean =      2.951 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 3783 
    [ 2.500,  3.750) = 6005 
    [ 3.750,  5.000) = 781 
    [ 5.000,  6.250) = 165 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.639 ms/op
     p(50.0000) =      2.720 ms/op
     p(90.0000) =      3.711 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.577 ms/op
     p(99.9000) =     17.668 ms/op
     p(99.9900) =     17.886 ms/op
     p(99.9990) =     17.891 ms/op
     p(99.9999) =     17.891 ms/op
    p(100.0000) =     17.891 ms/op


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
# Warmup Iteration   1: 2.887 ±(99.9%) 0.053 ms/op
Iteration   1: 1.803 ±(99.9%) 0.040 ms/op
                 existUser·p0.00:   0.531 ms/op
                 existUser·p0.50:   1.606 ms/op
                 existUser·p0.90:   2.298 ms/op
                 existUser·p0.95:   2.478 ms/op
                 existUser·p0.99:   4.667 ms/op
                 existUser·p0.999:  33.817 ms/op
                 existUser·p0.9999: 34.079 ms/op
                 existUser·p1.00:   34.079 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17716
  mean =      1.803 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16894 
    [ 2.500,  5.000) = 676 
    [ 5.000,  7.500) = 77 
    [ 7.500, 10.000) = 5 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.531 ms/op
     p(50.0000) =      1.606 ms/op
     p(90.0000) =      2.298 ms/op
     p(95.0000) =      2.478 ms/op
     p(99.0000) =      4.667 ms/op
     p(99.9000) =     33.817 ms/op
     p(99.9900) =     34.079 ms/op
     p(99.9990) =     34.079 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


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
# Warmup Iteration   1: 4.320 ±(99.9%) 0.095 ms/op
Iteration   1: 3.062 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.783 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.817 ms/op
                 getUser·p0.95:   4.133 ms/op
                 getUser·p0.99:   5.786 ms/op
                 getUser·p0.999:  9.280 ms/op
                 getUser·p0.9999: 9.585 ms/op
                 getUser·p1.00:   9.585 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10565
  mean =      3.062 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 2 
    [ 1.000,  2.000) = 256 
    [ 2.000,  3.000) = 5073 
    [ 3.000,  4.000) = 4542 
    [ 4.000,  5.000) = 547 
    [ 5.000,  6.000) = 64 
    [ 6.000,  7.000) = 48 
    [ 7.000,  8.000) = 0 
    [ 8.000,  9.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.783 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.133 ms/op
     p(99.0000) =      5.786 ms/op
     p(99.9000) =      9.280 ms/op
     p(99.9900) =      9.585 ms/op
     p(99.9990) =      9.585 ms/op
     p(99.9999) =      9.585 ms/op
    p(100.0000) =      9.585 ms/op


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
# Warmup Iteration   1: 11.486 ±(99.9%) 0.383 ms/op
Iteration   1: 8.167 ±(99.9%) 0.113 ms/op
                 listUser·p0.00:   1.841 ms/op
                 listUser·p0.50:   7.889 ms/op
                 listUser·p0.90:   11.026 ms/op
                 listUser·p0.95:   11.747 ms/op
                 listUser·p0.99:   14.234 ms/op
                 listUser·p0.999:  17.449 ms/op
                 listUser·p0.9999: 19.923 ms/op
                 listUser·p1.00:   19.923 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3914
  mean =      8.167 ±(99.9%) 0.113 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 8 
    [ 2.500,  3.750) = 50 
    [ 3.750,  5.000) = 150 
    [ 5.000,  6.250) = 418 
    [ 6.250,  7.500) = 979 
    [ 7.500,  8.750) = 928 
    [ 8.750, 10.000) = 667 
    [10.000, 11.250) = 423 
    [11.250, 12.500) = 169 
    [12.500, 13.750) = 72 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.841 ms/op
     p(50.0000) =      7.889 ms/op
     p(90.0000) =     11.026 ms/op
     p(95.0000) =     11.747 ms/op
     p(99.0000) =     14.234 ms/op
     p(99.9000) =     17.449 ms/op
     p(99.9900) =     19.923 ms/op
     p(99.9990) =     19.923 ms/op
     p(99.9999) =     19.923 ms/op
    p(100.0000) =     19.923 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.733          ops/ms
Client.existUser                       thrpt         12.266          ops/ms
Client.getUser                         thrpt          9.030          ops/ms
Client.listUser                        thrpt          3.584          ops/ms
Client.createUser                       avgt          3.296           ms/op
Client.existUser                        avgt          1.878           ms/op
Client.getUser                          avgt          2.879           ms/op
Client.listUser                         avgt          8.540           ms/op
Client.createUser                     sample  10823   2.951 ± 0.040   ms/op
Client.createUser:createUser·p0.00    sample          0.639           ms/op
Client.createUser:createUser·p0.50    sample          2.720           ms/op
Client.createUser:createUser·p0.90    sample          3.711           ms/op
Client.createUser:createUser·p0.95    sample          4.350           ms/op
Client.createUser:createUser·p0.99    sample          5.577           ms/op
Client.createUser:createUser·p0.999   sample         17.668           ms/op
Client.createUser:createUser·p0.9999  sample         17.886           ms/op
Client.createUser:createUser·p1.00    sample         17.891           ms/op
Client.existUser                      sample  17716   1.803 ± 0.040   ms/op
Client.existUser:existUser·p0.00      sample          0.531           ms/op
Client.existUser:existUser·p0.50      sample          1.606           ms/op
Client.existUser:existUser·p0.90      sample          2.298           ms/op
Client.existUser:existUser·p0.95      sample          2.478           ms/op
Client.existUser:existUser·p0.99      sample          4.667           ms/op
Client.existUser:existUser·p0.999     sample         33.817           ms/op
Client.existUser:existUser·p0.9999    sample         34.079           ms/op
Client.existUser:existUser·p1.00      sample         34.079           ms/op
Client.getUser                        sample  10565   3.062 ± 0.023   ms/op
Client.getUser:getUser·p0.00          sample          0.783           ms/op
Client.getUser:getUser·p0.50          sample          2.994           ms/op
Client.getUser:getUser·p0.90          sample          3.817           ms/op
Client.getUser:getUser·p0.95          sample          4.133           ms/op
Client.getUser:getUser·p0.99          sample          5.786           ms/op
Client.getUser:getUser·p0.999         sample          9.280           ms/op
Client.getUser:getUser·p0.9999        sample          9.585           ms/op
Client.getUser:getUser·p1.00          sample          9.585           ms/op
Client.listUser                       sample   3914   8.167 ± 0.113   ms/op
Client.listUser:listUser·p0.00        sample          1.841           ms/op
Client.listUser:listUser·p0.50        sample          7.889           ms/op
Client.listUser:listUser·p0.90        sample         11.026           ms/op
Client.listUser:listUser·p0.95        sample         11.747           ms/op
Client.listUser:listUser·p0.99        sample         14.234           ms/op
Client.listUser:listUser·p0.999       sample         17.449           ms/op
Client.listUser:listUser·p0.9999      sample         19.923           ms/op
Client.listUser:listUser·p1.00        sample         19.923           ms/op
