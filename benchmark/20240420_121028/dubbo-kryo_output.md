# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.923 ops/ms
Iteration   1: 6.756 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.756 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.674 ops/ms
Iteration   1: 14.329 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.329 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.333 ops/ms
Iteration   1: 13.333 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.333 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.810 ops/ms
Iteration   1: 8.558 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.558 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 4.175 ±(99.9%) 0.068 ms/op
Iteration   1: 2.085 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.085 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.176 ±(99.9%) 0.059 ms/op
Iteration   1: 1.743 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.743 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.516 ±(99.9%) 0.070 ms/op
Iteration   1: 2.288 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.288 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.508 ±(99.9%) 0.114 ms/op
Iteration   1: 3.632 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.632 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.637 ±(99.9%) 0.092 ms/op
Iteration   1: 2.331 ±(99.9%) 0.047 ms/op
                 createUser·p0.00:   0.775 ms/op
                 createUser·p0.50:   2.101 ms/op
                 createUser·p0.90:   2.699 ms/op
                 createUser·p0.95:   2.950 ms/op
                 createUser·p0.99:   7.857 ms/op
                 createUser·p0.999:  32.526 ms/op
                 createUser·p0.9999: 34.727 ms/op
                 createUser·p1.00:   35.586 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13693
  mean =      2.331 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11144 
    [ 2.500,  5.000) = 2313 
    [ 5.000,  7.500) = 50 
    [ 7.500, 10.000) = 122 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.775 ms/op
     p(50.0000) =      2.101 ms/op
     p(90.0000) =      2.699 ms/op
     p(95.0000) =      2.950 ms/op
     p(99.0000) =      7.857 ms/op
     p(99.9000) =     32.526 ms/op
     p(99.9900) =     34.727 ms/op
     p(99.9990) =     35.586 ms/op
     p(99.9999) =     35.586 ms/op
    p(100.0000) =     35.586 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.849 ±(99.9%) 0.061 ms/op
Iteration   1: 1.878 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.614 ms/op
                 existUser·p0.50:   1.733 ms/op
                 existUser·p0.90:   2.359 ms/op
                 existUser·p0.95:   2.576 ms/op
                 existUser·p0.99:   4.116 ms/op
                 existUser·p0.999:  12.599 ms/op
                 existUser·p0.9999: 12.707 ms/op
                 existUser·p1.00:   12.730 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17028
  mean =      1.878 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 472 
    [ 1.250,  2.500) = 15469 
    [ 2.500,  3.750) = 898 
    [ 3.750,  5.000) = 92 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.614 ms/op
     p(50.0000) =      1.733 ms/op
     p(90.0000) =      2.359 ms/op
     p(95.0000) =      2.576 ms/op
     p(99.0000) =      4.116 ms/op
     p(99.9000) =     12.599 ms/op
     p(99.9900) =     12.707 ms/op
     p(99.9990) =     12.730 ms/op
     p(99.9999) =     12.730 ms/op
    p(100.0000) =     12.730 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.191 ±(99.9%) 0.083 ms/op
Iteration   1: 2.145 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.712 ms/op
                 getUser·p0.50:   2.114 ms/op
                 getUser·p0.90:   2.658 ms/op
                 getUser·p0.95:   2.814 ms/op
                 getUser·p0.99:   3.411 ms/op
                 getUser·p0.999:  11.567 ms/op
                 getUser·p0.9999: 12.058 ms/op
                 getUser·p1.00:   12.075 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15064
  mean =      2.145 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 158 
    [ 1.250,  2.500) = 11864 
    [ 2.500,  3.750) = 2911 
    [ 3.750,  5.000) = 8 
    [ 5.000,  6.250) = 50 
    [ 6.250,  7.500) = 41 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.712 ms/op
     p(50.0000) =      2.114 ms/op
     p(90.0000) =      2.658 ms/op
     p(95.0000) =      2.814 ms/op
     p(99.0000) =      3.411 ms/op
     p(99.9000) =     11.567 ms/op
     p(99.9900) =     12.058 ms/op
     p(99.9990) =     12.075 ms/op
     p(99.9999) =     12.075 ms/op
    p(100.0000) =     12.075 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.697 ±(99.9%) 0.148 ms/op
Iteration   1: 3.887 ±(99.9%) 0.042 ms/op
                 listUser·p0.00:   1.524 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   4.833 ms/op
                 listUser·p0.99:   7.660 ms/op
                 listUser·p0.999:  19.287 ms/op
                 listUser·p0.9999: 21.004 ms/op
                 listUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8204
  mean =      3.887 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 179 
    [ 2.500,  5.000) = 7704 
    [ 5.000,  7.500) = 224 
    [ 7.500, 10.000) = 42 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.524 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      7.660 ms/op
     p(99.9000) =     19.287 ms/op
     p(99.9900) =     21.004 ms/op
     p(99.9990) =     21.004 ms/op
     p(99.9999) =     21.004 ms/op
    p(100.0000) =     21.004 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.756          ops/ms
ClientSimple.existUser                       thrpt         14.329          ops/ms
ClientSimple.getUser                         thrpt         13.333          ops/ms
ClientSimple.listUser                        thrpt          8.558          ops/ms
ClientSimple.createUser                       avgt          2.085           ms/op
ClientSimple.existUser                        avgt          1.743           ms/op
ClientSimple.getUser                          avgt          2.288           ms/op
ClientSimple.listUser                         avgt          3.632           ms/op
ClientSimple.createUser                     sample  13693   2.331 ± 0.047   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.775           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.101           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.699           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.950           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.857           ms/op
ClientSimple.createUser:createUser·p0.999   sample         32.526           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         34.727           ms/op
ClientSimple.createUser:createUser·p1.00    sample         35.586           ms/op
ClientSimple.existUser                      sample  17028   1.878 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.614           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.733           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.359           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.576           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.116           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.599           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.707           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.730           ms/op
ClientSimple.getUser                        sample  15064   2.145 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.712           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.114           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.658           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.814           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.411           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.567           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.058           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.075           ms/op
ClientSimple.listUser                       sample   8204   3.887 ± 0.042   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.524           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.797           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.497           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.833           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.660           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.287           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.004           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.004           ms/op

Benchmark result is saved to 1713614743075.json
