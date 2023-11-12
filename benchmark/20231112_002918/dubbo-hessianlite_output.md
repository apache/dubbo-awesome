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
Iteration   1: 5.630 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.630 ops/ms


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
# Warmup Iteration   1: 6.954 ops/ms
Iteration   1: 12.797 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.797 ops/ms


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
# Warmup Iteration   1: 5.089 ops/ms
Iteration   1: 9.387 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.387 ops/ms


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
# Warmup Iteration   1: 2.529 ops/ms
Iteration   1: 3.975 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.975 ops/ms


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
# Warmup Iteration   1: 5.243 ±(99.9%) 0.083 ms/op
Iteration   1: 2.855 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.855 ms/op


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
# Warmup Iteration   1: 3.116 ±(99.9%) 0.039 ms/op
Iteration   1: 1.858 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.858 ms/op


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
# Warmup Iteration   1: 4.695 ±(99.9%) 0.058 ms/op
Iteration   1: 3.372 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.372 ms/op


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
# Warmup Iteration   1: 11.195 ±(99.9%) 0.223 ms/op
Iteration   1: 8.710 ±(99.9%) 0.109 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.710 ms/op


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
# Warmup Iteration   1: 4.569 ±(99.9%) 0.084 ms/op
Iteration   1: 2.819 ±(99.9%) 0.047 ms/op
                 createUser·p0.00:   0.758 ms/op
                 createUser·p0.50:   2.519 ms/op
                 createUser·p0.90:   3.305 ms/op
                 createUser·p0.95:   3.654 ms/op
                 createUser·p0.99:   12.837 ms/op
                 createUser·p0.999:  16.896 ms/op
                 createUser·p0.9999: 17.302 ms/op
                 createUser·p1.00:   17.302 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11349
  mean =      2.819 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 17 
    [ 1.250,  2.500) = 5464 
    [ 2.500,  3.750) = 5347 
    [ 3.750,  5.000) = 173 
    [ 5.000,  6.250) = 112 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.758 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      3.305 ms/op
     p(95.0000) =      3.654 ms/op
     p(99.0000) =     12.837 ms/op
     p(99.9000) =     16.896 ms/op
     p(99.9900) =     17.302 ms/op
     p(99.9990) =     17.302 ms/op
     p(99.9999) =     17.302 ms/op
    p(100.0000) =     17.302 ms/op


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
# Warmup Iteration   1: 2.830 ±(99.9%) 0.056 ms/op
Iteration   1: 1.690 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.558 ms/op
                 existUser·p0.50:   1.657 ms/op
                 existUser·p0.90:   2.187 ms/op
                 existUser·p0.95:   2.398 ms/op
                 existUser·p0.99:   3.258 ms/op
                 existUser·p0.999:  11.454 ms/op
                 existUser·p0.9999: 12.508 ms/op
                 existUser·p1.00:   12.567 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18909
  mean =      1.690 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3873 
    [ 1.250,  2.500) = 14321 
    [ 2.500,  3.750) = 624 
    [ 3.750,  5.000) = 51 
    [ 5.000,  6.250) = 8 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.558 ms/op
     p(50.0000) =      1.657 ms/op
     p(90.0000) =      2.187 ms/op
     p(95.0000) =      2.398 ms/op
     p(99.0000) =      3.258 ms/op
     p(99.9000) =     11.454 ms/op
     p(99.9900) =     12.508 ms/op
     p(99.9990) =     12.567 ms/op
     p(99.9999) =     12.567 ms/op
    p(100.0000) =     12.567 ms/op


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
# Warmup Iteration   1: 4.686 ±(99.9%) 0.096 ms/op
Iteration   1: 3.118 ±(99.9%) 0.060 ms/op
                 getUser·p0.00:   0.709 ms/op
                 getUser·p0.50:   2.925 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   3.998 ms/op
                 getUser·p0.99:   8.471 ms/op
                 getUser·p0.999:  30.990 ms/op
                 getUser·p0.9999: 31.553 ms/op
                 getUser·p1.00:   31.556 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10250
  mean =      3.118 ±(99.9%) 0.060 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2868 
    [ 2.500,  5.000) = 7133 
    [ 5.000,  7.500) = 124 
    [ 7.500, 10.000) = 30 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.709 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      8.471 ms/op
     p(99.9000) =     30.990 ms/op
     p(99.9900) =     31.553 ms/op
     p(99.9990) =     31.556 ms/op
     p(99.9999) =     31.556 ms/op
    p(100.0000) =     31.556 ms/op


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
# Warmup Iteration   1: 12.180 ±(99.9%) 0.400 ms/op
Iteration   1: 7.701 ±(99.9%) 0.128 ms/op
                 listUser·p0.00:   2.085 ms/op
                 listUser·p0.50:   7.250 ms/op
                 listUser·p0.90:   10.320 ms/op
                 listUser·p0.95:   12.312 ms/op
                 listUser·p0.99:   17.416 ms/op
                 listUser·p0.999:  21.761 ms/op
                 listUser·p0.9999: 47.710 ms/op
                 listUser·p1.00:   47.710 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4150
  mean =      7.701 ±(99.9%) 0.128 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 250 
    [ 5.000, 10.000) = 3425 
    [10.000, 15.000) = 391 
    [15.000, 20.000) = 72 
    [20.000, 25.000) = 11 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.085 ms/op
     p(50.0000) =      7.250 ms/op
     p(90.0000) =     10.320 ms/op
     p(95.0000) =     12.312 ms/op
     p(99.0000) =     17.416 ms/op
     p(99.9000) =     21.761 ms/op
     p(99.9900) =     47.710 ms/op
     p(99.9990) =     47.710 ms/op
     p(99.9999) =     47.710 ms/op
    p(100.0000) =     47.710 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.630          ops/ms
Client.existUser                       thrpt         12.797          ops/ms
Client.getUser                         thrpt          9.387          ops/ms
Client.listUser                        thrpt          3.975          ops/ms
Client.createUser                       avgt          2.855           ms/op
Client.existUser                        avgt          1.858           ms/op
Client.getUser                          avgt          3.372           ms/op
Client.listUser                         avgt          8.710           ms/op
Client.createUser                     sample  11349   2.819 ± 0.047   ms/op
Client.createUser:createUser·p0.00    sample          0.758           ms/op
Client.createUser:createUser·p0.50    sample          2.519           ms/op
Client.createUser:createUser·p0.90    sample          3.305           ms/op
Client.createUser:createUser·p0.95    sample          3.654           ms/op
Client.createUser:createUser·p0.99    sample         12.837           ms/op
Client.createUser:createUser·p0.999   sample         16.896           ms/op
Client.createUser:createUser·p0.9999  sample         17.302           ms/op
Client.createUser:createUser·p1.00    sample         17.302           ms/op
Client.existUser                      sample  18909   1.690 ± 0.015   ms/op
Client.existUser:existUser·p0.00      sample          0.558           ms/op
Client.existUser:existUser·p0.50      sample          1.657           ms/op
Client.existUser:existUser·p0.90      sample          2.187           ms/op
Client.existUser:existUser·p0.95      sample          2.398           ms/op
Client.existUser:existUser·p0.99      sample          3.258           ms/op
Client.existUser:existUser·p0.999     sample         11.454           ms/op
Client.existUser:existUser·p0.9999    sample         12.508           ms/op
Client.existUser:existUser·p1.00      sample         12.567           ms/op
Client.getUser                        sample  10250   3.118 ± 0.060   ms/op
Client.getUser:getUser·p0.00          sample          0.709           ms/op
Client.getUser:getUser·p0.50          sample          2.925           ms/op
Client.getUser:getUser·p0.90          sample          3.723           ms/op
Client.getUser:getUser·p0.95          sample          3.998           ms/op
Client.getUser:getUser·p0.99          sample          8.471           ms/op
Client.getUser:getUser·p0.999         sample         30.990           ms/op
Client.getUser:getUser·p0.9999        sample         31.553           ms/op
Client.getUser:getUser·p1.00          sample         31.556           ms/op
Client.listUser                       sample   4150   7.701 ± 0.128   ms/op
Client.listUser:listUser·p0.00        sample          2.085           ms/op
Client.listUser:listUser·p0.50        sample          7.250           ms/op
Client.listUser:listUser·p0.90        sample         10.320           ms/op
Client.listUser:listUser·p0.95        sample         12.312           ms/op
Client.listUser:listUser·p0.99        sample         17.416           ms/op
Client.listUser:listUser·p0.999       sample         21.761           ms/op
Client.listUser:listUser·p0.9999      sample         47.710           ms/op
Client.listUser:listUser·p1.00        sample         47.710           ms/op
