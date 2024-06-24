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
# Warmup Iteration   1: 1.586 ops/ms
Iteration   1: 7.450 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.450 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.159 ops/ms
Iteration   1: 11.904 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.904 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.189 ops/ms
Iteration   1: 10.591 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.591 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.891 ops/ms
Iteration   1: 8.380 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.380 ops/ms


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
# Warmup Iteration   1: 4.221 ±(99.9%) 0.083 ms/op
Iteration   1: 2.351 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.351 ms/op


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
# Warmup Iteration   1: 3.422 ±(99.9%) 0.050 ms/op
Iteration   1: 1.878 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.878 ms/op


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
# Warmup Iteration   1: 3.650 ±(99.9%) 0.068 ms/op
Iteration   1: 2.057 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.057 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.340 ±(99.9%) 0.099 ms/op
Iteration   1: 3.885 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.885 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.464 ±(99.9%) 0.097 ms/op
Iteration   1: 1.992 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   0.523 ms/op
                 createUser·p0.50:   1.864 ms/op
                 createUser·p0.90:   2.433 ms/op
                 createUser·p0.95:   2.634 ms/op
                 createUser·p0.99:   4.981 ms/op
                 createUser·p0.999:  14.533 ms/op
                 createUser·p0.9999: 17.143 ms/op
                 createUser·p1.00:   19.202 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16042
  mean =      1.992 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 505 
    [ 1.250,  2.500) = 14294 
    [ 2.500,  3.750) = 1017 
    [ 3.750,  5.000) = 70 
    [ 5.000,  6.250) = 47 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 37 
    [13.750, 15.000) = 53 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.523 ms/op
     p(50.0000) =      1.864 ms/op
     p(90.0000) =      2.433 ms/op
     p(95.0000) =      2.634 ms/op
     p(99.0000) =      4.981 ms/op
     p(99.9000) =     14.533 ms/op
     p(99.9900) =     17.143 ms/op
     p(99.9990) =     19.202 ms/op
     p(99.9999) =     19.202 ms/op
    p(100.0000) =     19.202 ms/op


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
# Warmup Iteration   1: 3.349 ±(99.9%) 0.121 ms/op
Iteration   1: 2.040 ±(99.9%) 0.058 ms/op
                 existUser·p0.00:   0.509 ms/op
                 existUser·p0.50:   1.884 ms/op
                 existUser·p0.90:   2.388 ms/op
                 existUser·p0.95:   2.572 ms/op
                 existUser·p0.99:   5.451 ms/op
                 existUser·p0.999:  47.600 ms/op
                 existUser·p0.9999: 47.907 ms/op
                 existUser·p1.00:   47.907 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15678
  mean =      2.040 ±(99.9%) 0.058 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 15502 
    [ 5.000, 10.000) = 109 
    [10.000, 15.000) = 35 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.509 ms/op
     p(50.0000) =      1.884 ms/op
     p(90.0000) =      2.388 ms/op
     p(95.0000) =      2.572 ms/op
     p(99.0000) =      5.451 ms/op
     p(99.9000) =     47.600 ms/op
     p(99.9900) =     47.907 ms/op
     p(99.9990) =     47.907 ms/op
     p(99.9999) =     47.907 ms/op
    p(100.0000) =     47.907 ms/op


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
# Warmup Iteration   1: 3.265 ±(99.9%) 0.080 ms/op
Iteration   1: 2.264 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.633 ms/op
                 getUser·p0.50:   2.220 ms/op
                 getUser·p0.90:   2.744 ms/op
                 getUser·p0.95:   2.937 ms/op
                 getUser·p0.99:   3.424 ms/op
                 getUser·p0.999:  12.056 ms/op
                 getUser·p0.9999: 12.569 ms/op
                 getUser·p1.00:   12.698 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14133
  mean =      2.264 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 132 
    [ 1.250,  2.500) = 10408 
    [ 2.500,  3.750) = 3463 
    [ 3.750,  5.000) = 80 
    [ 5.000,  6.250) = 15 
    [ 6.250,  7.500) = 3 
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
      p(0.0000) =      0.633 ms/op
     p(50.0000) =      2.220 ms/op
     p(90.0000) =      2.744 ms/op
     p(95.0000) =      2.937 ms/op
     p(99.0000) =      3.424 ms/op
     p(99.9000) =     12.056 ms/op
     p(99.9900) =     12.569 ms/op
     p(99.9990) =     12.698 ms/op
     p(99.9999) =     12.698 ms/op
    p(100.0000) =     12.698 ms/op


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
# Warmup Iteration   1: 4.423 ±(99.9%) 0.123 ms/op
Iteration   1: 3.324 ±(99.9%) 0.043 ms/op
                 listUser·p0.00:   1.017 ms/op
                 listUser·p0.50:   3.256 ms/op
                 listUser·p0.90:   4.186 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   6.773 ms/op
                 listUser·p0.999:  20.034 ms/op
                 listUser·p0.9999: 20.185 ms/op
                 listUser·p1.00:   20.185 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9624
  mean =      3.324 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1461 
    [ 2.500,  5.000) = 7906 
    [ 5.000,  7.500) = 184 
    [ 7.500, 10.000) = 40 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.017 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      4.186 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      6.773 ms/op
     p(99.9000) =     20.034 ms/op
     p(99.9900) =     20.185 ms/op
     p(99.9990) =     20.185 ms/op
     p(99.9999) =     20.185 ms/op
    p(100.0000) =     20.185 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.450          ops/ms
ClientSimple.existUser                       thrpt         11.904          ops/ms
ClientSimple.getUser                         thrpt         10.591          ops/ms
ClientSimple.listUser                        thrpt          8.380          ops/ms
ClientSimple.createUser                       avgt          2.351           ms/op
ClientSimple.existUser                        avgt          1.878           ms/op
ClientSimple.getUser                          avgt          2.057           ms/op
ClientSimple.listUser                         avgt          3.885           ms/op
ClientSimple.createUser                     sample  16042   1.992 ± 0.028   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.523           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.864           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.433           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.634           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.981           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.533           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.143           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.202           ms/op
ClientSimple.existUser                      sample  15678   2.040 ± 0.058   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.509           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.884           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.388           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.572           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.451           ms/op
ClientSimple.existUser:existUser·p0.999     sample         47.600           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         47.907           ms/op
ClientSimple.existUser:existUser·p1.00      sample         47.907           ms/op
ClientSimple.getUser                        sample  14133   2.264 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.633           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.220           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.744           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.937           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.424           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.056           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.569           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.698           ms/op
ClientSimple.listUser                       sample   9624   3.324 ± 0.043   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.017           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.256           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.186           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.481           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.773           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.034           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.185           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.185           ms/op

Benchmark result is saved to 1719209157207.json
