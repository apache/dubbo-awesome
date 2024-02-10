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
# Warmup Iteration   1: 2.416 ops/ms
Iteration   1: 6.014 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.014 ops/ms


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
# Warmup Iteration   1: 6.231 ops/ms
Iteration   1: 13.866 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.866 ops/ms


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
# Warmup Iteration   1: 4.196 ops/ms
Iteration   1: 9.424 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.424 ops/ms


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
# Warmup Iteration   1: 1.881 ops/ms
Iteration   1: 3.903 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.903 ops/ms


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
# Warmup Iteration   1: 5.398 ±(99.9%) 0.072 ms/op
Iteration   1: 2.964 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.964 ms/op


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
# Warmup Iteration   1: 3.955 ±(99.9%) 0.050 ms/op
Iteration   1: 2.126 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.126 ms/op


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
# Warmup Iteration   1: 4.646 ±(99.9%) 0.078 ms/op
Iteration   1: 3.103 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.103 ms/op


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
# Warmup Iteration   1: 11.886 ±(99.9%) 0.190 ms/op
Iteration   1: 8.185 ±(99.9%) 0.091 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.185 ms/op


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
# Warmup Iteration   1: 4.838 ±(99.9%) 0.118 ms/op
Iteration   1: 3.180 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.834 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   4.243 ms/op
                 createUser·p0.95:   4.563 ms/op
                 createUser·p0.99:   5.974 ms/op
                 createUser·p0.999:  10.779 ms/op
                 createUser·p0.9999: 10.895 ms/op
                 createUser·p1.00:   10.895 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10094
  mean =      3.180 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 1369 
    [ 2.500,  3.750) = 6878 
    [ 3.750,  5.000) = 1644 
    [ 5.000,  6.250) = 105 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.834 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      5.974 ms/op
     p(99.9000) =     10.779 ms/op
     p(99.9900) =     10.895 ms/op
     p(99.9990) =     10.895 ms/op
     p(99.9999) =     10.895 ms/op
    p(100.0000) =     10.895 ms/op


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
# Warmup Iteration   1: 3.031 ±(99.9%) 0.076 ms/op
Iteration   1: 1.730 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.584 ms/op
                 existUser·p0.50:   1.634 ms/op
                 existUser·p0.90:   2.052 ms/op
                 existUser·p0.95:   2.286 ms/op
                 existUser·p0.99:   3.036 ms/op
                 existUser·p0.999:  19.678 ms/op
                 existUser·p0.9999: 19.938 ms/op
                 existUser·p1.00:   20.021 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18469
  mean =      1.730 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18022 
    [ 2.500,  5.000) = 411 
    [ 5.000,  7.500) = 4 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.584 ms/op
     p(50.0000) =      1.634 ms/op
     p(90.0000) =      2.052 ms/op
     p(95.0000) =      2.286 ms/op
     p(99.0000) =      3.036 ms/op
     p(99.9000) =     19.678 ms/op
     p(99.9900) =     19.938 ms/op
     p(99.9990) =     20.021 ms/op
     p(99.9999) =     20.021 ms/op
    p(100.0000) =     20.021 ms/op


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
# Warmup Iteration   1: 4.372 ±(99.9%) 0.099 ms/op
Iteration   1: 3.168 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   1.079 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.887 ms/op
                 getUser·p0.95:   4.276 ms/op
                 getUser·p0.99:   5.899 ms/op
                 getUser·p0.999:  7.192 ms/op
                 getUser·p0.9999: 10.424 ms/op
                 getUser·p1.00:   10.437 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10092
  mean =      3.168 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 186 
    [ 2.000,  3.000) = 4129 
    [ 3.000,  4.000) = 5029 
    [ 4.000,  5.000) = 482 
    [ 5.000,  6.000) = 179 
    [ 6.000,  7.000) = 63 
    [ 7.000,  8.000) = 18 
    [ 8.000,  9.000) = 4 
    [ 9.000, 10.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.079 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      5.899 ms/op
     p(99.9000) =      7.192 ms/op
     p(99.9900) =     10.424 ms/op
     p(99.9990) =     10.437 ms/op
     p(99.9999) =     10.437 ms/op
    p(100.0000) =     10.437 ms/op


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
# Warmup Iteration   1: 12.077 ±(99.9%) 0.488 ms/op
Iteration   1: 7.380 ±(99.9%) 0.098 ms/op
                 listUser·p0.00:   2.585 ms/op
                 listUser·p0.50:   7.078 ms/op
                 listUser·p0.90:   9.699 ms/op
                 listUser·p0.95:   10.694 ms/op
                 listUser·p0.99:   14.592 ms/op
                 listUser·p0.999:  18.884 ms/op
                 listUser·p0.9999: 20.808 ms/op
                 listUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4425
  mean =      7.380 ±(99.9%) 0.098 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 252 
    [ 5.000,  7.500) = 2405 
    [ 7.500, 10.000) = 1415 
    [10.000, 12.500) = 273 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.585 ms/op
     p(50.0000) =      7.078 ms/op
     p(90.0000) =      9.699 ms/op
     p(95.0000) =     10.694 ms/op
     p(99.0000) =     14.592 ms/op
     p(99.9000) =     18.884 ms/op
     p(99.9900) =     20.808 ms/op
     p(99.9990) =     20.808 ms/op
     p(99.9999) =     20.808 ms/op
    p(100.0000) =     20.808 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.014          ops/ms
Client.existUser                       thrpt         13.866          ops/ms
Client.getUser                         thrpt          9.424          ops/ms
Client.listUser                        thrpt          3.903          ops/ms
Client.createUser                       avgt          2.964           ms/op
Client.existUser                        avgt          2.126           ms/op
Client.getUser                          avgt          3.103           ms/op
Client.listUser                         avgt          8.185           ms/op
Client.createUser                     sample  10094   3.180 ± 0.029   ms/op
Client.createUser:createUser·p0.00    sample          0.834           ms/op
Client.createUser:createUser·p0.50    sample          2.994           ms/op
Client.createUser:createUser·p0.90    sample          4.243           ms/op
Client.createUser:createUser·p0.95    sample          4.563           ms/op
Client.createUser:createUser·p0.99    sample          5.974           ms/op
Client.createUser:createUser·p0.999   sample         10.779           ms/op
Client.createUser:createUser·p0.9999  sample         10.895           ms/op
Client.createUser:createUser·p1.00    sample         10.895           ms/op
Client.existUser                      sample  18469   1.730 ± 0.020   ms/op
Client.existUser:existUser·p0.00      sample          0.584           ms/op
Client.existUser:existUser·p0.50      sample          1.634           ms/op
Client.existUser:existUser·p0.90      sample          2.052           ms/op
Client.existUser:existUser·p0.95      sample          2.286           ms/op
Client.existUser:existUser·p0.99      sample          3.036           ms/op
Client.existUser:existUser·p0.999     sample         19.678           ms/op
Client.existUser:existUser·p0.9999    sample         19.938           ms/op
Client.existUser:existUser·p1.00      sample         20.021           ms/op
Client.getUser                        sample  10092   3.168 ± 0.023   ms/op
Client.getUser:getUser·p0.00          sample          1.079           ms/op
Client.getUser:getUser·p0.50          sample          3.117           ms/op
Client.getUser:getUser·p0.90          sample          3.887           ms/op
Client.getUser:getUser·p0.95          sample          4.276           ms/op
Client.getUser:getUser·p0.99          sample          5.899           ms/op
Client.getUser:getUser·p0.999         sample          7.192           ms/op
Client.getUser:getUser·p0.9999        sample         10.424           ms/op
Client.getUser:getUser·p1.00          sample         10.437           ms/op
Client.listUser                       sample   4425   7.380 ± 0.098   ms/op
Client.listUser:listUser·p0.00        sample          2.585           ms/op
Client.listUser:listUser·p0.50        sample          7.078           ms/op
Client.listUser:listUser·p0.90        sample          9.699           ms/op
Client.listUser:listUser·p0.95        sample         10.694           ms/op
Client.listUser:listUser·p0.99        sample         14.592           ms/op
Client.listUser:listUser·p0.999       sample         18.884           ms/op
Client.listUser:listUser·p0.9999      sample         20.808           ms/op
Client.listUser:listUser·p1.00        sample         20.808           ms/op
