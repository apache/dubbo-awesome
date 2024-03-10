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
# Warmup Iteration   1: 2.322 ops/ms
Iteration   1: 6.182 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.182 ops/ms


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
# Warmup Iteration   1: 5.650 ops/ms
Iteration   1: 13.167 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.167 ops/ms


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
# Warmup Iteration   1: 4.083 ops/ms
Iteration   1: 8.787 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.787 ops/ms


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
# Warmup Iteration   1: 2.211 ops/ms
Iteration   1: 4.017 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  4.017 ops/ms


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
# Warmup Iteration   1: 5.178 ±(99.9%) 0.095 ms/op
Iteration   1: 3.260 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.260 ms/op


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
# Warmup Iteration   1: 3.145 ±(99.9%) 0.030 ms/op
Iteration   1: 1.853 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.853 ms/op


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
# Warmup Iteration   1: 4.312 ±(99.9%) 0.053 ms/op
Iteration   1: 3.092 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.092 ms/op


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
# Warmup Iteration   1: 11.539 ±(99.9%) 0.190 ms/op
Iteration   1: 8.455 ±(99.9%) 0.079 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.455 ms/op


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
# Warmup Iteration   1: 4.766 ±(99.9%) 0.103 ms/op
Iteration   1: 3.040 ±(99.9%) 0.051 ms/op
                 createUser·p0.00:   1.055 ms/op
                 createUser·p0.50:   2.777 ms/op
                 createUser·p0.90:   3.850 ms/op
                 createUser·p0.95:   4.415 ms/op
                 createUser·p0.99:   6.845 ms/op
                 createUser·p0.999:  29.149 ms/op
                 createUser·p0.9999: 29.814 ms/op
                 createUser·p1.00:   29.819 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10719
  mean =      3.040 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2244 
    [ 2.500,  5.000) = 8235 
    [ 5.000,  7.500) = 170 
    [ 7.500, 10.000) = 33 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.055 ms/op
     p(50.0000) =      2.777 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      6.845 ms/op
     p(99.9000) =     29.149 ms/op
     p(99.9900) =     29.814 ms/op
     p(99.9990) =     29.819 ms/op
     p(99.9999) =     29.819 ms/op
    p(100.0000) =     29.819 ms/op


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
# Warmup Iteration   1: 3.173 ±(99.9%) 0.067 ms/op
Iteration   1: 1.897 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.279 ms/op
                 existUser·p0.50:   1.798 ms/op
                 existUser·p0.90:   2.564 ms/op
                 existUser·p0.95:   2.904 ms/op
                 existUser·p0.99:   4.147 ms/op
                 existUser·p0.999:  8.847 ms/op
                 existUser·p0.9999: 9.028 ms/op
                 existUser·p1.00:   9.028 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16861
  mean =      1.897 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 74 
    [ 1.000,  2.000) = 11262 
    [ 2.000,  3.000) = 4811 
    [ 3.000,  4.000) = 535 
    [ 4.000,  5.000) = 146 
    [ 5.000,  6.000) = 1 
    [ 6.000,  7.000) = 0 
    [ 7.000,  8.000) = 0 
    [ 8.000,  9.000) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.279 ms/op
     p(50.0000) =      1.798 ms/op
     p(90.0000) =      2.564 ms/op
     p(95.0000) =      2.904 ms/op
     p(99.0000) =      4.147 ms/op
     p(99.9000) =      8.847 ms/op
     p(99.9900) =      9.028 ms/op
     p(99.9990) =      9.028 ms/op
     p(99.9999) =      9.028 ms/op
    p(100.0000) =      9.028 ms/op


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
# Warmup Iteration   1: 4.522 ±(99.9%) 0.114 ms/op
Iteration   1: 2.870 ±(99.9%) 0.031 ms/op
                 getUser·p0.00:   0.696 ms/op
                 getUser·p0.50:   2.671 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   3.928 ms/op
                 getUser·p0.99:   5.108 ms/op
                 getUser·p0.999:  17.002 ms/op
                 getUser·p0.9999: 17.199 ms/op
                 getUser·p1.00:   17.203 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11143
  mean =      2.870 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 13 
    [ 1.250,  2.500) = 4286 
    [ 2.500,  3.750) = 5913 
    [ 3.750,  5.000) = 801 
    [ 5.000,  6.250) = 78 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.696 ms/op
     p(50.0000) =      2.671 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      5.108 ms/op
     p(99.9000) =     17.002 ms/op
     p(99.9900) =     17.199 ms/op
     p(99.9990) =     17.203 ms/op
     p(99.9999) =     17.203 ms/op
    p(100.0000) =     17.203 ms/op


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
# Warmup Iteration   1: 13.579 ±(99.9%) 0.557 ms/op
Iteration   1: 8.322 ±(99.9%) 0.132 ms/op
                 listUser·p0.00:   1.724 ms/op
                 listUser·p0.50:   7.844 ms/op
                 listUser·p0.90:   10.961 ms/op
                 listUser·p0.95:   11.846 ms/op
                 listUser·p0.99:   15.196 ms/op
                 listUser·p0.999:  26.650 ms/op
                 listUser·p0.9999: 27.001 ms/op
                 listUser·p1.00:   27.001 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3850
  mean =      8.322 ±(99.9%) 0.132 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 108 
    [ 5.000,  7.500) = 1473 
    [ 7.500, 10.000) = 1572 
    [10.000, 12.500) = 542 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.724 ms/op
     p(50.0000) =      7.844 ms/op
     p(90.0000) =     10.961 ms/op
     p(95.0000) =     11.846 ms/op
     p(99.0000) =     15.196 ms/op
     p(99.9000) =     26.650 ms/op
     p(99.9900) =     27.001 ms/op
     p(99.9990) =     27.001 ms/op
     p(99.9999) =     27.001 ms/op
    p(100.0000) =     27.001 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.182          ops/ms
Client.existUser                       thrpt         13.167          ops/ms
Client.getUser                         thrpt          8.787          ops/ms
Client.listUser                        thrpt          4.017          ops/ms
Client.createUser                       avgt          3.260           ms/op
Client.existUser                        avgt          1.853           ms/op
Client.getUser                          avgt          3.092           ms/op
Client.listUser                         avgt          8.455           ms/op
Client.createUser                     sample  10719   3.040 ± 0.051   ms/op
Client.createUser:createUser·p0.00    sample          1.055           ms/op
Client.createUser:createUser·p0.50    sample          2.777           ms/op
Client.createUser:createUser·p0.90    sample          3.850           ms/op
Client.createUser:createUser·p0.95    sample          4.415           ms/op
Client.createUser:createUser·p0.99    sample          6.845           ms/op
Client.createUser:createUser·p0.999   sample         29.149           ms/op
Client.createUser:createUser·p0.9999  sample         29.814           ms/op
Client.createUser:createUser·p1.00    sample         29.819           ms/op
Client.existUser                      sample  16861   1.897 ± 0.016   ms/op
Client.existUser:existUser·p0.00      sample          0.279           ms/op
Client.existUser:existUser·p0.50      sample          1.798           ms/op
Client.existUser:existUser·p0.90      sample          2.564           ms/op
Client.existUser:existUser·p0.95      sample          2.904           ms/op
Client.existUser:existUser·p0.99      sample          4.147           ms/op
Client.existUser:existUser·p0.999     sample          8.847           ms/op
Client.existUser:existUser·p0.9999    sample          9.028           ms/op
Client.existUser:existUser·p1.00      sample          9.028           ms/op
Client.getUser                        sample  11143   2.870 ± 0.031   ms/op
Client.getUser:getUser·p0.00          sample          0.696           ms/op
Client.getUser:getUser·p0.50          sample          2.671           ms/op
Client.getUser:getUser·p0.90          sample          3.678           ms/op
Client.getUser:getUser·p0.95          sample          3.928           ms/op
Client.getUser:getUser·p0.99          sample          5.108           ms/op
Client.getUser:getUser·p0.999         sample         17.002           ms/op
Client.getUser:getUser·p0.9999        sample         17.199           ms/op
Client.getUser:getUser·p1.00          sample         17.203           ms/op
Client.listUser                       sample   3850   8.322 ± 0.132   ms/op
Client.listUser:listUser·p0.00        sample          1.724           ms/op
Client.listUser:listUser·p0.50        sample          7.844           ms/op
Client.listUser:listUser·p0.90        sample         10.961           ms/op
Client.listUser:listUser·p0.95        sample         11.846           ms/op
Client.listUser:listUser·p0.99        sample         15.196           ms/op
Client.listUser:listUser·p0.999       sample         26.650           ms/op
Client.listUser:listUser·p0.9999      sample         27.001           ms/op
Client.listUser:listUser·p1.00        sample         27.001           ms/op
