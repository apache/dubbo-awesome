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
# Warmup Iteration   1: 2.571 ops/ms
Iteration   1: 5.549 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.549 ops/ms


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
# Warmup Iteration   1: 5.904 ops/ms
Iteration   1: 12.637 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.637 ops/ms


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
# Warmup Iteration   1: 4.718 ops/ms
Iteration   1: 8.185 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.185 ops/ms


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
# Warmup Iteration   1: 2.290 ops/ms
Iteration   1: 3.855 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.855 ops/ms


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
# Warmup Iteration   1: 5.007 ±(99.9%) 0.099 ms/op
Iteration   1: 3.183 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.183 ms/op


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
# Warmup Iteration   1: 3.065 ±(99.9%) 0.030 ms/op
Iteration   1: 1.842 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.842 ms/op


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
# Warmup Iteration   1: 4.349 ±(99.9%) 0.058 ms/op
Iteration   1: 3.089 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.089 ms/op


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
# Warmup Iteration   1: 10.501 ±(99.9%) 0.138 ms/op
Iteration   1: 8.201 ±(99.9%) 0.072 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.201 ms/op


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
# Warmup Iteration   1: 4.805 ±(99.9%) 0.096 ms/op
Iteration   1: 3.161 ±(99.9%) 0.047 ms/op
                 createUser·p0.00:   0.502 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   4.088 ms/op
                 createUser·p0.99:   8.962 ms/op
                 createUser·p0.999:  24.310 ms/op
                 createUser·p0.9999: 24.738 ms/op
                 createUser·p1.00:   24.740 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10114
  mean =      3.161 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1365 
    [ 2.500,  5.000) = 8529 
    [ 5.000,  7.500) = 92 
    [ 7.500, 10.000) = 59 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.502 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      4.088 ms/op
     p(99.0000) =      8.962 ms/op
     p(99.9000) =     24.310 ms/op
     p(99.9900) =     24.738 ms/op
     p(99.9990) =     24.740 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


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
# Warmup Iteration   1: 2.852 ±(99.9%) 0.059 ms/op
Iteration   1: 1.923 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.697 ms/op
                 existUser·p0.50:   1.778 ms/op
                 existUser·p0.90:   2.630 ms/op
                 existUser·p0.95:   2.912 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  8.428 ms/op
                 existUser·p0.9999: 10.871 ms/op
                 existUser·p1.00:   11.305 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16621
  mean =      1.923 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 711 
    [ 1.250,  2.500) = 13769 
    [ 2.500,  3.750) = 1854 
    [ 3.750,  5.000) = 189 
    [ 5.000,  6.250) = 54 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.697 ms/op
     p(50.0000) =      1.778 ms/op
     p(90.0000) =      2.630 ms/op
     p(95.0000) =      2.912 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      8.428 ms/op
     p(99.9900) =     10.871 ms/op
     p(99.9990) =     11.305 ms/op
     p(99.9999) =     11.305 ms/op
    p(100.0000) =     11.305 ms/op


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
# Warmup Iteration   1: 3.981 ±(99.9%) 0.079 ms/op
Iteration   1: 3.714 ±(99.9%) 0.154 ms/op
                 getUser·p0.00:   0.615 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   4.084 ms/op
                 getUser·p0.95:   4.555 ms/op
                 getUser·p0.99:   10.024 ms/op
                 getUser·p0.999:  68.994 ms/op
                 getUser·p0.9999: 87.294 ms/op
                 getUser·p1.00:   87.294 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 8620
  mean =      3.714 ±(99.9%) 0.154 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 8328 
    [ 5.000, 10.000) = 200 
    [10.000, 15.000) = 28 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 1 
    [25.000, 30.000) = 31 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 0 
    [60.000, 65.000) = 0 
    [65.000, 70.000) = 29 
    [70.000, 75.000) = 0 
    [75.000, 80.000) = 2 
    [80.000, 85.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.615 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      4.084 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =     10.024 ms/op
     p(99.9000) =     68.994 ms/op
     p(99.9900) =     87.294 ms/op
     p(99.9990) =     87.294 ms/op
     p(99.9999) =     87.294 ms/op
    p(100.0000) =     87.294 ms/op


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
# Warmup Iteration   1: 11.621 ±(99.9%) 0.375 ms/op
Iteration   1: 7.567 ±(99.9%) 0.101 ms/op
                 listUser·p0.00:   2.707 ms/op
                 listUser·p0.50:   7.250 ms/op
                 listUser·p0.90:   9.748 ms/op
                 listUser·p0.95:   10.738 ms/op
                 listUser·p0.99:   15.011 ms/op
                 listUser·p0.999:  20.436 ms/op
                 listUser·p0.9999: 21.037 ms/op
                 listUser·p1.00:   21.037 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4225
  mean =      7.567 ±(99.9%) 0.101 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 167 
    [ 5.000,  7.500) = 2211 
    [ 7.500, 10.000) = 1509 
    [10.000, 12.500) = 239 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.707 ms/op
     p(50.0000) =      7.250 ms/op
     p(90.0000) =      9.748 ms/op
     p(95.0000) =     10.738 ms/op
     p(99.0000) =     15.011 ms/op
     p(99.9000) =     20.436 ms/op
     p(99.9900) =     21.037 ms/op
     p(99.9990) =     21.037 ms/op
     p(99.9999) =     21.037 ms/op
    p(100.0000) =     21.037 ms/op


# Run complete. Total time: 00:01:22

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.549          ops/ms
Client.existUser                       thrpt         12.637          ops/ms
Client.getUser                         thrpt          8.185          ops/ms
Client.listUser                        thrpt          3.855          ops/ms
Client.createUser                       avgt          3.183           ms/op
Client.existUser                        avgt          1.842           ms/op
Client.getUser                          avgt          3.089           ms/op
Client.listUser                         avgt          8.201           ms/op
Client.createUser                     sample  10114   3.161 ± 0.047   ms/op
Client.createUser:createUser·p0.00    sample          0.502           ms/op
Client.createUser:createUser·p0.50    sample          3.002           ms/op
Client.createUser:createUser·p0.90    sample          3.690           ms/op
Client.createUser:createUser·p0.95    sample          4.088           ms/op
Client.createUser:createUser·p0.99    sample          8.962           ms/op
Client.createUser:createUser·p0.999   sample         24.310           ms/op
Client.createUser:createUser·p0.9999  sample         24.738           ms/op
Client.createUser:createUser·p1.00    sample         24.740           ms/op
Client.existUser                      sample  16621   1.923 ± 0.017   ms/op
Client.existUser:existUser·p0.00      sample          0.697           ms/op
Client.existUser:existUser·p0.50      sample          1.778           ms/op
Client.existUser:existUser·p0.90      sample          2.630           ms/op
Client.existUser:existUser·p0.95      sample          2.912           ms/op
Client.existUser:existUser·p0.99      sample          4.440           ms/op
Client.existUser:existUser·p0.999     sample          8.428           ms/op
Client.existUser:existUser·p0.9999    sample         10.871           ms/op
Client.existUser:existUser·p1.00      sample         11.305           ms/op
Client.getUser                        sample   8620   3.714 ± 0.154   ms/op
Client.getUser:getUser·p0.00          sample          0.615           ms/op
Client.getUser:getUser·p0.50          sample          3.318           ms/op
Client.getUser:getUser·p0.90          sample          4.084           ms/op
Client.getUser:getUser·p0.95          sample          4.555           ms/op
Client.getUser:getUser·p0.99          sample         10.024           ms/op
Client.getUser:getUser·p0.999         sample         68.994           ms/op
Client.getUser:getUser·p0.9999        sample         87.294           ms/op
Client.getUser:getUser·p1.00          sample         87.294           ms/op
Client.listUser                       sample   4225   7.567 ± 0.101   ms/op
Client.listUser:listUser·p0.00        sample          2.707           ms/op
Client.listUser:listUser·p0.50        sample          7.250           ms/op
Client.listUser:listUser·p0.90        sample          9.748           ms/op
Client.listUser:listUser·p0.95        sample         10.738           ms/op
Client.listUser:listUser·p0.99        sample         15.011           ms/op
Client.listUser:listUser·p0.999       sample         20.436           ms/op
Client.listUser:listUser·p0.9999      sample         21.037           ms/op
Client.listUser:listUser·p1.00        sample         21.037           ms/op
