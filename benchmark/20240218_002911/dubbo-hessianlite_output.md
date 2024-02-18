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
# Warmup Iteration   1: 2.446 ops/ms
Iteration   1: 6.184 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.184 ops/ms


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
# Warmup Iteration   1: 7.008 ops/ms
Iteration   1: 12.277 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.277 ops/ms


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
# Warmup Iteration   1: 4.316 ops/ms
Iteration   1: 8.614 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.614 ops/ms


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
# Warmup Iteration   1: 2.320 ops/ms
Iteration   1: 3.740 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.740 ops/ms


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
# Warmup Iteration   1: 5.216 ±(99.9%) 0.055 ms/op
Iteration   1: 3.038 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.038 ms/op


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
# Warmup Iteration   1: 3.324 ±(99.9%) 0.038 ms/op
Iteration   1: 1.854 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.854 ms/op


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
# Warmup Iteration   1: 4.810 ±(99.9%) 0.044 ms/op
Iteration   1: 3.014 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.014 ms/op


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
# Warmup Iteration   1: 11.752 ±(99.9%) 0.148 ms/op
Iteration   1: 8.591 ±(99.9%) 0.110 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.591 ms/op


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
# Warmup Iteration   1: 4.915 ±(99.9%) 0.111 ms/op
Iteration   1: 2.896 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   1.198 ms/op
                 createUser·p0.50:   2.748 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.145 ms/op
                 createUser·p0.99:   4.880 ms/op
                 createUser·p0.999:  6.324 ms/op
                 createUser·p0.9999: 8.180 ms/op
                 createUser·p1.00:   8.208 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11030
  mean =      2.896 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 37 
    [1.500, 2.000) = 717 
    [2.000, 2.500) = 2860 
    [2.500, 3.000) = 3166 
    [3.000, 3.500) = 2006 
    [3.500, 4.000) = 1453 
    [4.000, 4.500) = 556 
    [4.500, 5.000) = 130 
    [5.000, 5.500) = 31 
    [5.500, 6.000) = 52 
    [6.000, 6.500) = 15 
    [6.500, 7.000) = 2 
    [7.000, 7.500) = 2 
    [7.500, 8.000) = 2 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.198 ms/op
     p(50.0000) =      2.748 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.145 ms/op
     p(99.0000) =      4.880 ms/op
     p(99.9000) =      6.324 ms/op
     p(99.9900) =      8.180 ms/op
     p(99.9990) =      8.208 ms/op
     p(99.9999) =      8.208 ms/op
    p(100.0000) =      8.208 ms/op


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
# Warmup Iteration   1: 3.115 ±(99.9%) 0.076 ms/op
Iteration   1: 1.850 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.630 ms/op
                 existUser·p0.50:   1.681 ms/op
                 existUser·p0.90:   2.470 ms/op
                 existUser·p0.95:   2.672 ms/op
                 existUser·p0.99:   4.077 ms/op
                 existUser·p0.999:  7.545 ms/op
                 existUser·p0.9999: 7.715 ms/op
                 existUser·p1.00:   7.995 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17274
  mean =      1.850 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 39 
    [1.000, 1.500) = 2646 
    [1.500, 2.000) = 10133 
    [2.000, 2.500) = 2931 
    [2.500, 3.000) = 1140 
    [3.000, 3.500) = 151 
    [3.500, 4.000) = 45 
    [4.000, 4.500) = 71 
    [4.500, 5.000) = 43 
    [5.000, 5.500) = 36 
    [5.500, 6.000) = 4 
    [6.000, 6.500) = 0 
    [6.500, 7.000) = 2 
    [7.000, 7.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.630 ms/op
     p(50.0000) =      1.681 ms/op
     p(90.0000) =      2.470 ms/op
     p(95.0000) =      2.672 ms/op
     p(99.0000) =      4.077 ms/op
     p(99.9000) =      7.545 ms/op
     p(99.9900) =      7.715 ms/op
     p(99.9990) =      7.995 ms/op
     p(99.9999) =      7.995 ms/op
    p(100.0000) =      7.995 ms/op


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
# Warmup Iteration   1: 4.300 ±(99.9%) 0.088 ms/op
Iteration   1: 3.029 ±(99.9%) 0.040 ms/op
                 getUser·p0.00:   0.670 ms/op
                 getUser·p0.50:   2.789 ms/op
                 getUser·p0.90:   3.879 ms/op
                 getUser·p0.95:   4.424 ms/op
                 getUser·p0.99:   8.640 ms/op
                 getUser·p0.999:  16.195 ms/op
                 getUser·p0.9999: 17.201 ms/op
                 getUser·p1.00:   17.203 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10563
  mean =      3.029 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 14 
    [ 1.250,  2.500) = 3815 
    [ 2.500,  3.750) = 5403 
    [ 3.750,  5.000) = 1015 
    [ 5.000,  6.250) = 147 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 45 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 34 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.670 ms/op
     p(50.0000) =      2.789 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      8.640 ms/op
     p(99.9000) =     16.195 ms/op
     p(99.9900) =     17.201 ms/op
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
# Warmup Iteration   1: 11.914 ±(99.9%) 0.386 ms/op
Iteration   1: 8.073 ±(99.9%) 0.115 ms/op
                 listUser·p0.00:   2.310 ms/op
                 listUser·p0.50:   7.852 ms/op
                 listUser·p0.90:   10.895 ms/op
                 listUser·p0.95:   11.698 ms/op
                 listUser·p0.99:   15.586 ms/op
                 listUser·p0.999:  19.394 ms/op
                 listUser·p0.9999: 21.561 ms/op
                 listUser·p1.00:   21.561 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4034
  mean =      8.073 ±(99.9%) 0.115 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 180 
    [ 5.000,  7.500) = 1575 
    [ 7.500, 10.000) = 1576 
    [10.000, 12.500) = 581 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.310 ms/op
     p(50.0000) =      7.852 ms/op
     p(90.0000) =     10.895 ms/op
     p(95.0000) =     11.698 ms/op
     p(99.0000) =     15.586 ms/op
     p(99.9000) =     19.394 ms/op
     p(99.9900) =     21.561 ms/op
     p(99.9990) =     21.561 ms/op
     p(99.9999) =     21.561 ms/op
    p(100.0000) =     21.561 ms/op


# Run complete. Total time: 00:01:22

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.184          ops/ms
Client.existUser                       thrpt         12.277          ops/ms
Client.getUser                         thrpt          8.614          ops/ms
Client.listUser                        thrpt          3.740          ops/ms
Client.createUser                       avgt          3.038           ms/op
Client.existUser                        avgt          1.854           ms/op
Client.getUser                          avgt          3.014           ms/op
Client.listUser                         avgt          8.591           ms/op
Client.createUser                     sample  11030   2.896 ± 0.023   ms/op
Client.createUser:createUser·p0.00    sample          1.198           ms/op
Client.createUser:createUser·p0.50    sample          2.748           ms/op
Client.createUser:createUser·p0.90    sample          3.846           ms/op
Client.createUser:createUser·p0.95    sample          4.145           ms/op
Client.createUser:createUser·p0.99    sample          4.880           ms/op
Client.createUser:createUser·p0.999   sample          6.324           ms/op
Client.createUser:createUser·p0.9999  sample          8.180           ms/op
Client.createUser:createUser·p1.00    sample          8.208           ms/op
Client.existUser                      sample  17274   1.850 ± 0.014   ms/op
Client.existUser:existUser·p0.00      sample          0.630           ms/op
Client.existUser:existUser·p0.50      sample          1.681           ms/op
Client.existUser:existUser·p0.90      sample          2.470           ms/op
Client.existUser:existUser·p0.95      sample          2.672           ms/op
Client.existUser:existUser·p0.99      sample          4.077           ms/op
Client.existUser:existUser·p0.999     sample          7.545           ms/op
Client.existUser:existUser·p0.9999    sample          7.715           ms/op
Client.existUser:existUser·p1.00      sample          7.995           ms/op
Client.getUser                        sample  10563   3.029 ± 0.040   ms/op
Client.getUser:getUser·p0.00          sample          0.670           ms/op
Client.getUser:getUser·p0.50          sample          2.789           ms/op
Client.getUser:getUser·p0.90          sample          3.879           ms/op
Client.getUser:getUser·p0.95          sample          4.424           ms/op
Client.getUser:getUser·p0.99          sample          8.640           ms/op
Client.getUser:getUser·p0.999         sample         16.195           ms/op
Client.getUser:getUser·p0.9999        sample         17.201           ms/op
Client.getUser:getUser·p1.00          sample         17.203           ms/op
Client.listUser                       sample   4034   8.073 ± 0.115   ms/op
Client.listUser:listUser·p0.00        sample          2.310           ms/op
Client.listUser:listUser·p0.50        sample          7.852           ms/op
Client.listUser:listUser·p0.90        sample         10.895           ms/op
Client.listUser:listUser·p0.95        sample         11.698           ms/op
Client.listUser:listUser·p0.99        sample         15.586           ms/op
Client.listUser:listUser·p0.999       sample         19.394           ms/op
Client.listUser:listUser·p0.9999      sample         21.561           ms/op
Client.listUser:listUser·p1.00        sample         21.561           ms/op
