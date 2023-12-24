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
# Warmup Iteration   1: 2.351 ops/ms
Iteration   1: 5.289 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.289 ops/ms


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
# Warmup Iteration   1: 5.760 ops/ms
Iteration   1: 12.766 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.766 ops/ms


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
# Warmup Iteration   1: 4.505 ops/ms
Iteration   1: 9.806 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.806 ops/ms


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
# Warmup Iteration   1: 2.106 ops/ms
Iteration   1: 3.730 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.730 ops/ms


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
# Warmup Iteration   1: 5.339 ±(99.9%) 0.090 ms/op
Iteration   1: 3.050 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.050 ms/op


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
# Warmup Iteration   1: 3.420 ±(99.9%) 0.043 ms/op
Iteration   1: 1.880 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.880 ms/op


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
# Warmup Iteration   1: 5.116 ±(99.9%) 0.070 ms/op
Iteration   1: 3.159 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.159 ms/op


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
# Warmup Iteration   1: 11.563 ±(99.9%) 0.237 ms/op
Iteration   1: 8.504 ±(99.9%) 0.103 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.504 ms/op


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
# Warmup Iteration   1: 4.857 ±(99.9%) 0.103 ms/op
Iteration   1: 2.915 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   1.335 ms/op
                 createUser·p0.50:   2.683 ms/op
                 createUser·p0.90:   3.729 ms/op
                 createUser·p0.95:   4.141 ms/op
                 createUser·p0.99:   7.104 ms/op
                 createUser·p0.999:  17.468 ms/op
                 createUser·p0.9999: 17.727 ms/op
                 createUser·p1.00:   17.727 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11075
  mean =      2.915 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 3872 
    [ 2.500,  3.750) = 6133 
    [ 3.750,  5.000) = 829 
    [ 5.000,  6.250) = 93 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 9 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.335 ms/op
     p(50.0000) =      2.683 ms/op
     p(90.0000) =      3.729 ms/op
     p(95.0000) =      4.141 ms/op
     p(99.0000) =      7.104 ms/op
     p(99.9000) =     17.468 ms/op
     p(99.9900) =     17.727 ms/op
     p(99.9990) =     17.727 ms/op
     p(99.9999) =     17.727 ms/op
    p(100.0000) =     17.727 ms/op


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
# Warmup Iteration   1: 3.292 ±(99.9%) 0.086 ms/op
Iteration   1: 1.638 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.752 ms/op
                 existUser·p0.50:   1.577 ms/op
                 existUser·p0.90:   1.985 ms/op
                 existUser·p0.95:   2.175 ms/op
                 existUser·p0.99:   2.817 ms/op
                 existUser·p0.999:  4.894 ms/op
                 existUser·p0.9999: 8.640 ms/op
                 existUser·p1.00:   8.765 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 19534
  mean =      1.638 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 12 
    [1.000, 1.500) = 6993 
    [1.500, 2.000) = 10675 
    [2.000, 2.500) = 1515 
    [2.500, 3.000) = 183 
    [3.000, 3.500) = 64 
    [3.500, 4.000) = 30 
    [4.000, 4.500) = 32 
    [4.500, 5.000) = 14 
    [5.000, 5.500) = 5 
    [5.500, 6.000) = 0 
    [6.000, 6.500) = 2 
    [6.500, 7.000) = 0 
    [7.000, 7.500) = 0 
    [7.500, 8.000) = 4 
    [8.000, 8.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.752 ms/op
     p(50.0000) =      1.577 ms/op
     p(90.0000) =      1.985 ms/op
     p(95.0000) =      2.175 ms/op
     p(99.0000) =      2.817 ms/op
     p(99.9000) =      4.894 ms/op
     p(99.9900) =      8.640 ms/op
     p(99.9990) =      8.765 ms/op
     p(99.9999) =      8.765 ms/op
    p(100.0000) =      8.765 ms/op


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
# Warmup Iteration   1: 4.306 ±(99.9%) 0.098 ms/op
Iteration   1: 3.503 ±(99.9%) 0.083 ms/op
                 getUser·p0.00:   1.073 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   4.166 ms/op
                 getUser·p0.95:   4.564 ms/op
                 getUser·p0.99:   7.994 ms/op
                 getUser·p0.999:  40.239 ms/op
                 getUser·p0.9999: 42.533 ms/op
                 getUser·p1.00:   42.533 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9136
  mean =      3.503 ±(99.9%) 0.083 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 8830 
    [ 5.000, 10.000) = 236 
    [10.000, 15.000) = 4 
    [15.000, 20.000) = 14 
    [20.000, 25.000) = 20 
    [25.000, 30.000) = 3 
    [30.000, 35.000) = 3 
    [35.000, 40.000) = 13 
    [40.000, 45.000) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.073 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      4.166 ms/op
     p(95.0000) =      4.564 ms/op
     p(99.0000) =      7.994 ms/op
     p(99.9000) =     40.239 ms/op
     p(99.9900) =     42.533 ms/op
     p(99.9990) =     42.533 ms/op
     p(99.9999) =     42.533 ms/op
    p(100.0000) =     42.533 ms/op


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
# Warmup Iteration   1: 11.764 ±(99.9%) 0.346 ms/op
Iteration   1: 7.768 ±(99.9%) 0.125 ms/op
                 listUser·p0.00:   2.482 ms/op
                 listUser·p0.50:   7.389 ms/op
                 listUser·p0.90:   10.207 ms/op
                 listUser·p0.95:   11.616 ms/op
                 listUser·p0.99:   18.149 ms/op
                 listUser·p0.999:  31.846 ms/op
                 listUser·p0.9999: 36.241 ms/op
                 listUser·p1.00:   36.241 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4114
  mean =      7.768 ±(99.9%) 0.125 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 237 
    [ 5.000,  7.500) = 1922 
    [ 7.500, 10.000) = 1483 
    [10.000, 12.500) = 331 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.482 ms/op
     p(50.0000) =      7.389 ms/op
     p(90.0000) =     10.207 ms/op
     p(95.0000) =     11.616 ms/op
     p(99.0000) =     18.149 ms/op
     p(99.9000) =     31.846 ms/op
     p(99.9900) =     36.241 ms/op
     p(99.9990) =     36.241 ms/op
     p(99.9999) =     36.241 ms/op
    p(100.0000) =     36.241 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.289          ops/ms
Client.existUser                       thrpt         12.766          ops/ms
Client.getUser                         thrpt          9.806          ops/ms
Client.listUser                        thrpt          3.730          ops/ms
Client.createUser                       avgt          3.050           ms/op
Client.existUser                        avgt          1.880           ms/op
Client.getUser                          avgt          3.159           ms/op
Client.listUser                         avgt          8.504           ms/op
Client.createUser                     sample  11075   2.915 ± 0.037   ms/op
Client.createUser:createUser·p0.00    sample          1.335           ms/op
Client.createUser:createUser·p0.50    sample          2.683           ms/op
Client.createUser:createUser·p0.90    sample          3.729           ms/op
Client.createUser:createUser·p0.95    sample          4.141           ms/op
Client.createUser:createUser·p0.99    sample          7.104           ms/op
Client.createUser:createUser·p0.999   sample         17.468           ms/op
Client.createUser:createUser·p0.9999  sample         17.727           ms/op
Client.createUser:createUser·p1.00    sample         17.727           ms/op
Client.existUser                      sample  19534   1.638 ± 0.008   ms/op
Client.existUser:existUser·p0.00      sample          0.752           ms/op
Client.existUser:existUser·p0.50      sample          1.577           ms/op
Client.existUser:existUser·p0.90      sample          1.985           ms/op
Client.existUser:existUser·p0.95      sample          2.175           ms/op
Client.existUser:existUser·p0.99      sample          2.817           ms/op
Client.existUser:existUser·p0.999     sample          4.894           ms/op
Client.existUser:existUser·p0.9999    sample          8.640           ms/op
Client.existUser:existUser·p1.00      sample          8.765           ms/op
Client.getUser                        sample   9136   3.503 ± 0.083   ms/op
Client.getUser:getUser·p0.00          sample          1.073           ms/op
Client.getUser:getUser·p0.50          sample          3.248           ms/op
Client.getUser:getUser·p0.90          sample          4.166           ms/op
Client.getUser:getUser·p0.95          sample          4.564           ms/op
Client.getUser:getUser·p0.99          sample          7.994           ms/op
Client.getUser:getUser·p0.999         sample         40.239           ms/op
Client.getUser:getUser·p0.9999        sample         42.533           ms/op
Client.getUser:getUser·p1.00          sample         42.533           ms/op
Client.listUser                       sample   4114   7.768 ± 0.125   ms/op
Client.listUser:listUser·p0.00        sample          2.482           ms/op
Client.listUser:listUser·p0.50        sample          7.389           ms/op
Client.listUser:listUser·p0.90        sample         10.207           ms/op
Client.listUser:listUser·p0.95        sample         11.616           ms/op
Client.listUser:listUser·p0.99        sample         18.149           ms/op
Client.listUser:listUser·p0.999       sample         31.846           ms/op
Client.listUser:listUser·p0.9999      sample         36.241           ms/op
Client.listUser:listUser·p1.00        sample         36.241           ms/op
