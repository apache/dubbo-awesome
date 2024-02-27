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
# Warmup Iteration   1: 2.655 ops/ms
Iteration   1: 6.646 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.646 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.627 ops/ms
Iteration   1: 11.484 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.484 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.560 ops/ms
Iteration   1: 8.810 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.810 ops/ms


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
# Warmup Iteration   1: 1.898 ops/ms
Iteration   1: 3.622 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.622 ops/ms


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
# Warmup Iteration   1: 5.270 ±(99.9%) 0.062 ms/op
Iteration   1: 3.087 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.087 ms/op


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
# Warmup Iteration   1: 3.317 ±(99.9%) 0.035 ms/op
Iteration   1: 1.874 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.874 ms/op


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
# Warmup Iteration   1: 4.947 ±(99.9%) 0.043 ms/op
Iteration   1: 2.704 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.704 ms/op


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
# Warmup Iteration   1: 12.367 ±(99.9%) 0.245 ms/op
Iteration   1: 8.601 ±(99.9%) 0.127 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.601 ms/op


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
# Warmup Iteration   1: 5.249 ±(99.9%) 0.109 ms/op
Iteration   1: 3.124 ±(99.9%) 0.042 ms/op
                 createUser·p0.00:   1.186 ms/op
                 createUser·p0.50:   2.933 ms/op
                 createUser·p0.90:   3.920 ms/op
                 createUser·p0.95:   4.563 ms/op
                 createUser·p0.99:   9.664 ms/op
                 createUser·p0.999:  19.530 ms/op
                 createUser·p0.9999: 20.734 ms/op
                 createUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10271
  mean =      3.124 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2090 
    [ 2.500,  5.000) = 7889 
    [ 5.000,  7.500) = 140 
    [ 7.500, 10.000) = 66 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.186 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      9.664 ms/op
     p(99.9000) =     19.530 ms/op
     p(99.9900) =     20.734 ms/op
     p(99.9990) =     20.742 ms/op
     p(99.9999) =     20.742 ms/op
    p(100.0000) =     20.742 ms/op


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
# Warmup Iteration   1: 3.283 ±(99.9%) 0.072 ms/op
Iteration   1: 1.993 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.813 ms/op
                 existUser·p0.50:   1.841 ms/op
                 existUser·p0.90:   2.490 ms/op
                 existUser·p0.95:   2.761 ms/op
                 existUser·p0.99:   3.936 ms/op
                 existUser·p0.999:  23.331 ms/op
                 existUser·p0.9999: 23.696 ms/op
                 existUser·p1.00:   23.855 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16060
  mean =      1.993 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14492 
    [ 2.500,  5.000) = 1495 
    [ 5.000,  7.500) = 41 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.813 ms/op
     p(50.0000) =      1.841 ms/op
     p(90.0000) =      2.490 ms/op
     p(95.0000) =      2.761 ms/op
     p(99.0000) =      3.936 ms/op
     p(99.9000) =     23.331 ms/op
     p(99.9900) =     23.696 ms/op
     p(99.9990) =     23.855 ms/op
     p(99.9999) =     23.855 ms/op
    p(100.0000) =     23.855 ms/op


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
# Warmup Iteration   1: 4.505 ±(99.9%) 0.112 ms/op
Iteration   1: 3.135 ±(99.9%) 0.090 ms/op
                 getUser·p0.00:   0.829 ms/op
                 getUser·p0.50:   2.724 ms/op
                 getUser·p0.90:   3.752 ms/op
                 getUser·p0.95:   4.067 ms/op
                 getUser·p0.99:   5.877 ms/op
                 getUser·p0.999:  43.516 ms/op
                 getUser·p0.9999: 46.608 ms/op
                 getUser·p1.00:   46.662 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10270
  mean =      3.135 ±(99.9%) 0.090 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 10106 
    [ 5.000, 10.000) = 96 
    [10.000, 15.000) = 2 
    [15.000, 20.000) = 4 
    [20.000, 25.000) = 1 
    [25.000, 30.000) = 23 
    [30.000, 35.000) = 6 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.829 ms/op
     p(50.0000) =      2.724 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      4.067 ms/op
     p(99.0000) =      5.877 ms/op
     p(99.9000) =     43.516 ms/op
     p(99.9900) =     46.608 ms/op
     p(99.9990) =     46.662 ms/op
     p(99.9999) =     46.662 ms/op
    p(100.0000) =     46.662 ms/op


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
# Warmup Iteration   1: 13.056 ±(99.9%) 0.398 ms/op
Iteration   1: 8.230 ±(99.9%) 0.112 ms/op
                 listUser·p0.00:   1.626 ms/op
                 listUser·p0.50:   7.873 ms/op
                 listUser·p0.90:   10.738 ms/op
                 listUser·p0.95:   12.026 ms/op
                 listUser·p0.99:   16.792 ms/op
                 listUser·p0.999:  21.722 ms/op
                 listUser·p0.9999: 22.839 ms/op
                 listUser·p1.00:   22.839 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4055
  mean =      8.230 ±(99.9%) 0.112 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 105 
    [ 5.000,  7.500) = 1462 
    [ 7.500, 10.000) = 1889 
    [10.000, 12.500) = 434 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.626 ms/op
     p(50.0000) =      7.873 ms/op
     p(90.0000) =     10.738 ms/op
     p(95.0000) =     12.026 ms/op
     p(99.0000) =     16.792 ms/op
     p(99.9000) =     21.722 ms/op
     p(99.9900) =     22.839 ms/op
     p(99.9990) =     22.839 ms/op
     p(99.9999) =     22.839 ms/op
    p(100.0000) =     22.839 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.646          ops/ms
Client.existUser                       thrpt         11.484          ops/ms
Client.getUser                         thrpt          8.810          ops/ms
Client.listUser                        thrpt          3.622          ops/ms
Client.createUser                       avgt          3.087           ms/op
Client.existUser                        avgt          1.874           ms/op
Client.getUser                          avgt          2.704           ms/op
Client.listUser                         avgt          8.601           ms/op
Client.createUser                     sample  10271   3.124 ± 0.042   ms/op
Client.createUser:createUser·p0.00    sample          1.186           ms/op
Client.createUser:createUser·p0.50    sample          2.933           ms/op
Client.createUser:createUser·p0.90    sample          3.920           ms/op
Client.createUser:createUser·p0.95    sample          4.563           ms/op
Client.createUser:createUser·p0.99    sample          9.664           ms/op
Client.createUser:createUser·p0.999   sample         19.530           ms/op
Client.createUser:createUser·p0.9999  sample         20.734           ms/op
Client.createUser:createUser·p1.00    sample         20.742           ms/op
Client.existUser                      sample  16060   1.993 ± 0.027   ms/op
Client.existUser:existUser·p0.00      sample          0.813           ms/op
Client.existUser:existUser·p0.50      sample          1.841           ms/op
Client.existUser:existUser·p0.90      sample          2.490           ms/op
Client.existUser:existUser·p0.95      sample          2.761           ms/op
Client.existUser:existUser·p0.99      sample          3.936           ms/op
Client.existUser:existUser·p0.999     sample         23.331           ms/op
Client.existUser:existUser·p0.9999    sample         23.696           ms/op
Client.existUser:existUser·p1.00      sample         23.855           ms/op
Client.getUser                        sample  10270   3.135 ± 0.090   ms/op
Client.getUser:getUser·p0.00          sample          0.829           ms/op
Client.getUser:getUser·p0.50          sample          2.724           ms/op
Client.getUser:getUser·p0.90          sample          3.752           ms/op
Client.getUser:getUser·p0.95          sample          4.067           ms/op
Client.getUser:getUser·p0.99          sample          5.877           ms/op
Client.getUser:getUser·p0.999         sample         43.516           ms/op
Client.getUser:getUser·p0.9999        sample         46.608           ms/op
Client.getUser:getUser·p1.00          sample         46.662           ms/op
Client.listUser                       sample   4055   8.230 ± 0.112   ms/op
Client.listUser:listUser·p0.00        sample          1.626           ms/op
Client.listUser:listUser·p0.50        sample          7.873           ms/op
Client.listUser:listUser·p0.90        sample         10.738           ms/op
Client.listUser:listUser·p0.95        sample         12.026           ms/op
Client.listUser:listUser·p0.99        sample         16.792           ms/op
Client.listUser:listUser·p0.999       sample         21.722           ms/op
Client.listUser:listUser·p0.9999      sample         22.839           ms/op
Client.listUser:listUser·p1.00        sample         22.839           ms/op
