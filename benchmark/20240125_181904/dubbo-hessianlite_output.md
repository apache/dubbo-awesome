# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.573 ops/ms
Iteration   1: 5.897 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.897 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.108 ops/ms
Iteration   1: 12.147 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.147 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.610 ops/ms
Iteration   1: 9.576 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.576 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.922 ops/ms
Iteration   1: 3.712 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.712 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.440 ±(99.9%) 0.102 ms/op
Iteration   1: 3.047 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.047 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.125 ±(99.9%) 0.029 ms/op
Iteration   1: 1.953 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.953 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.963 ±(99.9%) 0.062 ms/op
Iteration   1: 3.174 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.174 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 12.480 ±(99.9%) 0.163 ms/op
Iteration   1: 8.314 ±(99.9%) 0.094 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.314 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.423 ±(99.9%) 0.114 ms/op
Iteration   1: 3.264 ±(99.9%) 0.043 ms/op
                 createUser·p0.00:   1.227 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   4.100 ms/op
                 createUser·p0.95:   4.530 ms/op
                 createUser·p0.99:   10.475 ms/op
                 createUser·p0.999:  18.717 ms/op
                 createUser·p0.9999: 19.235 ms/op
                 createUser·p1.00:   19.235 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9787
  mean =      3.264 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 1336 
    [ 2.500,  3.750) = 6912 
    [ 3.750,  5.000) = 1273 
    [ 5.000,  6.250) = 49 
    [ 6.250,  7.500) = 68 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.227 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =     10.475 ms/op
     p(99.9000) =     18.717 ms/op
     p(99.9900) =     19.235 ms/op
     p(99.9990) =     19.235 ms/op
     p(99.9999) =     19.235 ms/op
    p(100.0000) =     19.235 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.125 ±(99.9%) 0.064 ms/op
Iteration   1: 1.839 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.423 ms/op
                 existUser·p0.50:   1.735 ms/op
                 existUser·p0.90:   2.347 ms/op
                 existUser·p0.95:   2.580 ms/op
                 existUser·p0.99:   3.535 ms/op
                 existUser·p0.999:  18.383 ms/op
                 existUser·p0.9999: 18.827 ms/op
                 existUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17386
  mean =      1.839 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1076 
    [ 1.250,  2.500) = 15208 
    [ 2.500,  3.750) = 973 
    [ 3.750,  5.000) = 46 
    [ 5.000,  6.250) = 5 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.423 ms/op
     p(50.0000) =      1.735 ms/op
     p(90.0000) =      2.347 ms/op
     p(95.0000) =      2.580 ms/op
     p(99.0000) =      3.535 ms/op
     p(99.9000) =     18.383 ms/op
     p(99.9900) =     18.827 ms/op
     p(99.9990) =     18.973 ms/op
     p(99.9999) =     18.973 ms/op
    p(100.0000) =     18.973 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.482 ±(99.9%) 0.093 ms/op
Iteration   1: 3.163 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.955 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   5.716 ms/op
                 getUser·p0.999:  11.041 ms/op
                 getUser·p0.9999: 11.174 ms/op
                 getUser·p1.00:   11.174 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10106
  mean =      3.163 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 19 
    [ 1.250,  2.500) = 1609 
    [ 2.500,  3.750) = 7109 
    [ 3.750,  5.000) = 1208 
    [ 5.000,  6.250) = 72 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 21 
    [10.000, 11.250) = 43 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.955 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      5.716 ms/op
     p(99.9000) =     11.041 ms/op
     p(99.9900) =     11.174 ms/op
     p(99.9990) =     11.174 ms/op
     p(99.9999) =     11.174 ms/op
    p(100.0000) =     11.174 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.441 ±(99.9%) 0.526 ms/op
Iteration   1: 8.129 ±(99.9%) 0.109 ms/op
                 listUser·p0.00:   1.952 ms/op
                 listUser·p0.50:   7.889 ms/op
                 listUser·p0.90:   10.437 ms/op
                 listUser·p0.95:   11.600 ms/op
                 listUser·p0.99:   15.854 ms/op
                 listUser·p0.999:  21.681 ms/op
                 listUser·p0.9999: 31.359 ms/op
                 listUser·p1.00:   31.359 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3933
  mean =      8.129 ±(99.9%) 0.109 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 115 
    [ 5.000,  7.500) = 1421 
    [ 7.500, 10.000) = 1882 
    [10.000, 12.500) = 416 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.952 ms/op
     p(50.0000) =      7.889 ms/op
     p(90.0000) =     10.437 ms/op
     p(95.0000) =     11.600 ms/op
     p(99.0000) =     15.854 ms/op
     p(99.9000) =     21.681 ms/op
     p(99.9900) =     31.359 ms/op
     p(99.9990) =     31.359 ms/op
     p(99.9999) =     31.359 ms/op
    p(100.0000) =     31.359 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.897          ops/ms
Client.existUser                       thrpt         12.147          ops/ms
Client.getUser                         thrpt          9.576          ops/ms
Client.listUser                        thrpt          3.712          ops/ms
Client.createUser                       avgt          3.047           ms/op
Client.existUser                        avgt          1.953           ms/op
Client.getUser                          avgt          3.174           ms/op
Client.listUser                         avgt          8.314           ms/op
Client.createUser                     sample   9787   3.264 ± 0.043   ms/op
Client.createUser:createUser·p0.00    sample          1.227           ms/op
Client.createUser:createUser·p0.50    sample          3.043           ms/op
Client.createUser:createUser·p0.90    sample          4.100           ms/op
Client.createUser:createUser·p0.95    sample          4.530           ms/op
Client.createUser:createUser·p0.99    sample         10.475           ms/op
Client.createUser:createUser·p0.999   sample         18.717           ms/op
Client.createUser:createUser·p0.9999  sample         19.235           ms/op
Client.createUser:createUser·p1.00    sample         19.235           ms/op
Client.existUser                      sample  17386   1.839 ± 0.022   ms/op
Client.existUser:existUser·p0.00      sample          0.423           ms/op
Client.existUser:existUser·p0.50      sample          1.735           ms/op
Client.existUser:existUser·p0.90      sample          2.347           ms/op
Client.existUser:existUser·p0.95      sample          2.580           ms/op
Client.existUser:existUser·p0.99      sample          3.535           ms/op
Client.existUser:existUser·p0.999     sample         18.383           ms/op
Client.existUser:existUser·p0.9999    sample         18.827           ms/op
Client.existUser:existUser·p1.00      sample         18.973           ms/op
Client.getUser                        sample  10106   3.163 ± 0.029   ms/op
Client.getUser:getUser·p0.00          sample          0.955           ms/op
Client.getUser:getUser·p0.50          sample          3.129           ms/op
Client.getUser:getUser·p0.90          sample          3.871           ms/op
Client.getUser:getUser·p0.95          sample          4.235           ms/op
Client.getUser:getUser·p0.99          sample          5.716           ms/op
Client.getUser:getUser·p0.999         sample         11.041           ms/op
Client.getUser:getUser·p0.9999        sample         11.174           ms/op
Client.getUser:getUser·p1.00          sample         11.174           ms/op
Client.listUser                       sample   3933   8.129 ± 0.109   ms/op
Client.listUser:listUser·p0.00        sample          1.952           ms/op
Client.listUser:listUser·p0.50        sample          7.889           ms/op
Client.listUser:listUser·p0.90        sample         10.437           ms/op
Client.listUser:listUser·p0.95        sample         11.600           ms/op
Client.listUser:listUser·p0.99        sample         15.854           ms/op
Client.listUser:listUser·p0.999       sample         21.681           ms/op
Client.listUser:listUser·p0.9999      sample         31.359           ms/op
Client.listUser:listUser·p1.00        sample         31.359           ms/op
