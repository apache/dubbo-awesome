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
# Warmup Iteration   1: 2.192 ops/ms
Iteration   1: 5.732 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.732 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.660 ops/ms
Iteration   1: 11.556 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.556 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.803 ops/ms
Iteration   1: 8.669 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.669 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.028 ops/ms
Iteration   1: 3.774 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.774 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.435 ±(99.9%) 0.070 ms/op
Iteration   1: 3.436 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.436 ms/op


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
# Warmup Iteration   1: 3.166 ±(99.9%) 0.044 ms/op
Iteration   1: 1.898 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.898 ms/op


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
# Warmup Iteration   1: 4.700 ±(99.9%) 0.059 ms/op
Iteration   1: 3.186 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.186 ms/op


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
# Warmup Iteration   1: 12.096 ±(99.9%) 0.217 ms/op
Iteration   1: 8.008 ±(99.9%) 0.102 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.008 ms/op


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
# Warmup Iteration   1: 5.371 ±(99.9%) 0.127 ms/op
Iteration   1: 3.145 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   0.892 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.969 ms/op
                 createUser·p0.95:   4.357 ms/op
                 createUser·p0.99:   8.196 ms/op
                 createUser·p0.999:  18.252 ms/op
                 createUser·p0.9999: 20.377 ms/op
                 createUser·p1.00:   20.382 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10162
  mean =      3.145 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2140 
    [ 2.500,  5.000) = 7774 
    [ 5.000,  7.500) = 145 
    [ 7.500, 10.000) = 38 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.892 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.969 ms/op
     p(95.0000) =      4.357 ms/op
     p(99.0000) =      8.196 ms/op
     p(99.9000) =     18.252 ms/op
     p(99.9900) =     20.377 ms/op
     p(99.9990) =     20.382 ms/op
     p(99.9999) =     20.382 ms/op
    p(100.0000) =     20.382 ms/op


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
# Warmup Iteration   1: 3.185 ±(99.9%) 0.078 ms/op
Iteration   1: 1.915 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.217 ms/op
                 existUser·p0.50:   1.823 ms/op
                 existUser·p0.90:   2.535 ms/op
                 existUser·p0.95:   2.773 ms/op
                 existUser·p0.99:   3.318 ms/op
                 existUser·p0.999:  16.851 ms/op
                 existUser·p0.9999: 17.334 ms/op
                 existUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16733
  mean =      1.915 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 819 
    [ 1.250,  2.500) = 14104 
    [ 2.500,  3.750) = 1711 
    [ 3.750,  5.000) = 44 
    [ 5.000,  6.250) = 23 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.217 ms/op
     p(50.0000) =      1.823 ms/op
     p(90.0000) =      2.535 ms/op
     p(95.0000) =      2.773 ms/op
     p(99.0000) =      3.318 ms/op
     p(99.9000) =     16.851 ms/op
     p(99.9900) =     17.334 ms/op
     p(99.9990) =     17.400 ms/op
     p(99.9999) =     17.400 ms/op
    p(100.0000) =     17.400 ms/op


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
# Warmup Iteration   1: 4.689 ±(99.9%) 0.126 ms/op
Iteration   1: 2.857 ±(99.9%) 0.036 ms/op
                 getUser·p0.00:   0.520 ms/op
                 getUser·p0.50:   2.650 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.309 ms/op
                 getUser·p0.99:   5.521 ms/op
                 getUser·p0.999:  19.876 ms/op
                 getUser·p0.9999: 23.786 ms/op
                 getUser·p1.00:   23.953 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11219
  mean =      2.857 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4088 
    [ 2.500,  5.000) = 6967 
    [ 5.000,  7.500) = 111 
    [ 7.500, 10.000) = 21 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.520 ms/op
     p(50.0000) =      2.650 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =     19.876 ms/op
     p(99.9900) =     23.786 ms/op
     p(99.9990) =     23.953 ms/op
     p(99.9999) =     23.953 ms/op
    p(100.0000) =     23.953 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 12.499 ±(99.9%) 0.454 ms/op
Iteration   1: 8.718 ±(99.9%) 0.216 ms/op
                 listUser·p0.00:   1.540 ms/op
                 listUser·p0.50:   8.184 ms/op
                 listUser·p0.90:   10.781 ms/op
                 listUser·p0.95:   11.780 ms/op
                 listUser·p0.99:   16.384 ms/op
                 listUser·p0.999:  49.634 ms/op
                 listUser·p0.9999: 51.446 ms/op
                 listUser·p1.00:   51.446 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3649
  mean =      8.718 ±(99.9%) 0.216 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 76 
    [ 5.000, 10.000) = 2968 
    [10.000, 15.000) = 561 
    [15.000, 20.000) = 10 
    [20.000, 25.000) = 2 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 14 
    [45.000, 50.000) = 17 
    [50.000, 55.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.540 ms/op
     p(50.0000) =      8.184 ms/op
     p(90.0000) =     10.781 ms/op
     p(95.0000) =     11.780 ms/op
     p(99.0000) =     16.384 ms/op
     p(99.9000) =     49.634 ms/op
     p(99.9900) =     51.446 ms/op
     p(99.9990) =     51.446 ms/op
     p(99.9999) =     51.446 ms/op
    p(100.0000) =     51.446 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.732          ops/ms
Client.existUser                       thrpt         11.556          ops/ms
Client.getUser                         thrpt          8.669          ops/ms
Client.listUser                        thrpt          3.774          ops/ms
Client.createUser                       avgt          3.436           ms/op
Client.existUser                        avgt          1.898           ms/op
Client.getUser                          avgt          3.186           ms/op
Client.listUser                         avgt          8.008           ms/op
Client.createUser                     sample  10162   3.145 ± 0.040   ms/op
Client.createUser:createUser·p0.00    sample          0.892           ms/op
Client.createUser:createUser·p0.50    sample          2.974           ms/op
Client.createUser:createUser·p0.90    sample          3.969           ms/op
Client.createUser:createUser·p0.95    sample          4.357           ms/op
Client.createUser:createUser·p0.99    sample          8.196           ms/op
Client.createUser:createUser·p0.999   sample         18.252           ms/op
Client.createUser:createUser·p0.9999  sample         20.377           ms/op
Client.createUser:createUser·p1.00    sample         20.382           ms/op
Client.existUser                      sample  16733   1.915 ± 0.021   ms/op
Client.existUser:existUser·p0.00      sample          0.217           ms/op
Client.existUser:existUser·p0.50      sample          1.823           ms/op
Client.existUser:existUser·p0.90      sample          2.535           ms/op
Client.existUser:existUser·p0.95      sample          2.773           ms/op
Client.existUser:existUser·p0.99      sample          3.318           ms/op
Client.existUser:existUser·p0.999     sample         16.851           ms/op
Client.existUser:existUser·p0.9999    sample         17.334           ms/op
Client.existUser:existUser·p1.00      sample         17.400           ms/op
Client.getUser                        sample  11219   2.857 ± 0.036   ms/op
Client.getUser:getUser·p0.00          sample          0.520           ms/op
Client.getUser:getUser·p0.50          sample          2.650           ms/op
Client.getUser:getUser·p0.90          sample          3.842           ms/op
Client.getUser:getUser·p0.95          sample          4.309           ms/op
Client.getUser:getUser·p0.99          sample          5.521           ms/op
Client.getUser:getUser·p0.999         sample         19.876           ms/op
Client.getUser:getUser·p0.9999        sample         23.786           ms/op
Client.getUser:getUser·p1.00          sample         23.953           ms/op
Client.listUser                       sample   3649   8.718 ± 0.216   ms/op
Client.listUser:listUser·p0.00        sample          1.540           ms/op
Client.listUser:listUser·p0.50        sample          8.184           ms/op
Client.listUser:listUser·p0.90        sample         10.781           ms/op
Client.listUser:listUser·p0.95        sample         11.780           ms/op
Client.listUser:listUser·p0.99        sample         16.384           ms/op
Client.listUser:listUser·p0.999       sample         49.634           ms/op
Client.listUser:listUser·p0.9999      sample         51.446           ms/op
Client.listUser:listUser·p1.00        sample         51.446           ms/op
