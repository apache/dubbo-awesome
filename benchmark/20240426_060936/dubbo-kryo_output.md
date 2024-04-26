# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.476 ops/ms
Iteration   1: 6.545 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.545 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.702 ops/ms
Iteration   1: 11.306 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.306 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.803 ops/ms
Iteration   1: 13.195 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.195 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.203 ops/ms
Iteration   1: 9.344 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.344 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.764 ±(99.9%) 0.074 ms/op
Iteration   1: 2.259 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.259 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.432 ±(99.9%) 0.062 ms/op
Iteration   1: 1.721 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.721 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.107 ±(99.9%) 0.050 ms/op
Iteration   1: 1.801 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.801 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.567 ±(99.9%) 0.082 ms/op
Iteration   1: 3.495 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.495 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.905 ±(99.9%) 0.115 ms/op
Iteration   1: 2.270 ±(99.9%) 0.061 ms/op
                 createUser·p0.00:   0.641 ms/op
                 createUser·p0.50:   2.050 ms/op
                 createUser·p0.90:   2.564 ms/op
                 createUser·p0.95:   2.916 ms/op
                 createUser·p0.99:   8.749 ms/op
                 createUser·p0.999:  43.755 ms/op
                 createUser·p0.9999: 47.487 ms/op
                 createUser·p1.00:   47.514 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14088
  mean =      2.270 ±(99.9%) 0.061 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 13890 
    [ 5.000, 10.000) = 101 
    [10.000, 15.000) = 57 
    [15.000, 20.000) = 8 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.641 ms/op
     p(50.0000) =      2.050 ms/op
     p(90.0000) =      2.564 ms/op
     p(95.0000) =      2.916 ms/op
     p(99.0000) =      8.749 ms/op
     p(99.9000) =     43.755 ms/op
     p(99.9900) =     47.487 ms/op
     p(99.9990) =     47.514 ms/op
     p(99.9999) =     47.514 ms/op
    p(100.0000) =     47.514 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.014 ±(99.9%) 0.074 ms/op
Iteration   1: 1.743 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.653 ms/op
                 existUser·p0.50:   1.632 ms/op
                 existUser·p0.90:   2.273 ms/op
                 existUser·p0.95:   2.429 ms/op
                 existUser·p0.99:   2.809 ms/op
                 existUser·p0.999:  11.687 ms/op
                 existUser·p0.9999: 12.659 ms/op
                 existUser·p1.00:   12.878 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18331
  mean =      1.743 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 824 
    [ 1.250,  2.500) = 16853 
    [ 2.500,  3.750) = 614 
    [ 3.750,  5.000) = 0 
    [ 5.000,  6.250) = 6 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.653 ms/op
     p(50.0000) =      1.632 ms/op
     p(90.0000) =      2.273 ms/op
     p(95.0000) =      2.429 ms/op
     p(99.0000) =      2.809 ms/op
     p(99.9000) =     11.687 ms/op
     p(99.9900) =     12.659 ms/op
     p(99.9990) =     12.878 ms/op
     p(99.9999) =     12.878 ms/op
    p(100.0000) =     12.878 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.295 ±(99.9%) 0.099 ms/op
Iteration   1: 1.782 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.675 ms/op
                 getUser·p0.50:   1.681 ms/op
                 getUser·p0.90:   2.277 ms/op
                 getUser·p0.95:   2.499 ms/op
                 getUser·p0.99:   3.056 ms/op
                 getUser·p0.999:  12.322 ms/op
                 getUser·p0.9999: 12.475 ms/op
                 getUser·p1.00:   12.501 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17964
  mean =      1.782 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1115 
    [ 1.250,  2.500) = 15959 
    [ 2.500,  3.750) = 777 
    [ 3.750,  5.000) = 43 
    [ 5.000,  6.250) = 22 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.675 ms/op
     p(50.0000) =      1.681 ms/op
     p(90.0000) =      2.277 ms/op
     p(95.0000) =      2.499 ms/op
     p(99.0000) =      3.056 ms/op
     p(99.9000) =     12.322 ms/op
     p(99.9900) =     12.475 ms/op
     p(99.9990) =     12.501 ms/op
     p(99.9999) =     12.501 ms/op
    p(100.0000) =     12.501 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.473 ±(99.9%) 0.145 ms/op
Iteration   1: 3.309 ±(99.9%) 0.041 ms/op
                 listUser·p0.00:   0.819 ms/op
                 listUser·p0.50:   3.129 ms/op
                 listUser·p0.90:   4.084 ms/op
                 listUser·p0.95:   4.302 ms/op
                 listUser·p0.99:   5.849 ms/op
                 listUser·p0.999:  21.549 ms/op
                 listUser·p0.9999: 22.741 ms/op
                 listUser·p1.00:   22.741 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9675
  mean =      3.309 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 733 
    [ 2.500,  5.000) = 8753 
    [ 5.000,  7.500) = 157 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.819 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      4.084 ms/op
     p(95.0000) =      4.302 ms/op
     p(99.0000) =      5.849 ms/op
     p(99.9000) =     21.549 ms/op
     p(99.9900) =     22.741 ms/op
     p(99.9990) =     22.741 ms/op
     p(99.9999) =     22.741 ms/op
    p(100.0000) =     22.741 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.545          ops/ms
ClientSimple.existUser                       thrpt         11.306          ops/ms
ClientSimple.getUser                         thrpt         13.195          ops/ms
ClientSimple.listUser                        thrpt          9.344          ops/ms
ClientSimple.createUser                       avgt          2.259           ms/op
ClientSimple.existUser                        avgt          1.721           ms/op
ClientSimple.getUser                          avgt          1.801           ms/op
ClientSimple.listUser                         avgt          3.495           ms/op
ClientSimple.createUser                     sample  14088   2.270 ± 0.061   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.641           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.050           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.564           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.916           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.749           ms/op
ClientSimple.createUser:createUser·p0.999   sample         43.755           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         47.487           ms/op
ClientSimple.createUser:createUser·p1.00    sample         47.514           ms/op
ClientSimple.existUser                      sample  18331   1.743 ± 0.014   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.653           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.632           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.273           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.429           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.809           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.687           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.659           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.878           ms/op
ClientSimple.getUser                        sample  17964   1.782 ± 0.015   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.675           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.681           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.277           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.499           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.056           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.322           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.475           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.501           ms/op
ClientSimple.listUser                       sample   9675   3.309 ± 0.041   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.819           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.129           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.084           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.302           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.849           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.549           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         22.741           ms/op
ClientSimple.listUser:listUser·p1.00        sample         22.741           ms/op

Benchmark result is saved to 1714111523510.json
