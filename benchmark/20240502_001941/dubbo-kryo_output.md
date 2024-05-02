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
# Warmup Iteration   1: 1.655 ops/ms
Iteration   1: 6.658 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.658 ops/ms


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
# Warmup Iteration   1: 5.165 ops/ms
Iteration   1: 12.269 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.269 ops/ms


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
# Warmup Iteration   1: 4.748 ops/ms
Iteration   1: 12.844 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.844 ops/ms


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
# Warmup Iteration   1: 5.357 ops/ms
Iteration   1: 8.637 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.637 ops/ms


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
# Warmup Iteration   1: 3.491 ±(99.9%) 0.071 ms/op
Iteration   1: 2.251 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.251 ms/op


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
# Warmup Iteration   1: 3.359 ±(99.9%) 0.061 ms/op
Iteration   1: 1.740 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.740 ms/op


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
# Warmup Iteration   1: 3.362 ±(99.9%) 0.061 ms/op
Iteration   1: 2.077 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.077 ms/op


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
# Warmup Iteration   1: 4.153 ±(99.9%) 0.083 ms/op
Iteration   1: 3.666 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.666 ms/op


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
# Warmup Iteration   1: 3.561 ±(99.9%) 0.089 ms/op
Iteration   1: 2.375 ±(99.9%) 0.041 ms/op
                 createUser·p0.00:   0.229 ms/op
                 createUser·p0.50:   2.216 ms/op
                 createUser·p0.90:   2.953 ms/op
                 createUser·p0.95:   3.080 ms/op
                 createUser·p0.99:   5.882 ms/op
                 createUser·p0.999:  26.083 ms/op
                 createUser·p0.9999: 26.870 ms/op
                 createUser·p1.00:   26.870 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13491
  mean =      2.375 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8776 
    [ 2.500,  5.000) = 4517 
    [ 5.000,  7.500) = 133 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.229 ms/op
     p(50.0000) =      2.216 ms/op
     p(90.0000) =      2.953 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =      5.882 ms/op
     p(99.9000) =     26.083 ms/op
     p(99.9900) =     26.870 ms/op
     p(99.9990) =     26.870 ms/op
     p(99.9999) =     26.870 ms/op
    p(100.0000) =     26.870 ms/op


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
# Warmup Iteration   1: 2.812 ±(99.9%) 0.068 ms/op
Iteration   1: 1.838 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.536 ms/op
                 existUser·p0.50:   1.698 ms/op
                 existUser·p0.90:   2.359 ms/op
                 existUser·p0.95:   2.920 ms/op
                 existUser·p0.99:   3.830 ms/op
                 existUser·p0.999:  12.118 ms/op
                 existUser·p0.9999: 12.827 ms/op
                 existUser·p1.00:   13.009 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17386
  mean =      1.838 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 477 
    [ 1.250,  2.500) = 15458 
    [ 2.500,  3.750) = 1253 
    [ 3.750,  5.000) = 149 
    [ 5.000,  6.250) = 4 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.536 ms/op
     p(50.0000) =      1.698 ms/op
     p(90.0000) =      2.359 ms/op
     p(95.0000) =      2.920 ms/op
     p(99.0000) =      3.830 ms/op
     p(99.9000) =     12.118 ms/op
     p(99.9900) =     12.827 ms/op
     p(99.9990) =     13.009 ms/op
     p(99.9999) =     13.009 ms/op
    p(100.0000) =     13.009 ms/op


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
# Warmup Iteration   1: 3.326 ±(99.9%) 0.099 ms/op
Iteration   1: 2.327 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.314 ms/op
                 getUser·p0.50:   2.220 ms/op
                 getUser·p0.90:   2.949 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   5.068 ms/op
                 getUser·p0.999:  12.239 ms/op
                 getUser·p0.9999: 12.478 ms/op
                 getUser·p1.00:   12.485 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13779
  mean =      2.327 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 159 
    [ 1.250,  2.500) = 9083 
    [ 2.500,  3.750) = 4315 
    [ 3.750,  5.000) = 73 
    [ 5.000,  6.250) = 57 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.314 ms/op
     p(50.0000) =      2.220 ms/op
     p(90.0000) =      2.949 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      5.068 ms/op
     p(99.9000) =     12.239 ms/op
     p(99.9900) =     12.478 ms/op
     p(99.9990) =     12.485 ms/op
     p(99.9999) =     12.485 ms/op
    p(100.0000) =     12.485 ms/op


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
# Warmup Iteration   1: 4.650 ±(99.9%) 0.135 ms/op
Iteration   1: 3.433 ±(99.9%) 0.038 ms/op
                 listUser·p0.00:   1.090 ms/op
                 listUser·p0.50:   3.195 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.784 ms/op
                 listUser·p0.99:   6.546 ms/op
                 listUser·p0.999:  16.728 ms/op
                 listUser·p0.9999: 16.876 ms/op
                 listUser·p1.00:   16.876 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9348
  mean =      3.433 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 603 
    [ 2.500,  3.750) = 5574 
    [ 3.750,  5.000) = 2925 
    [ 5.000,  6.250) = 121 
    [ 6.250,  7.500) = 89 
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
      p(0.0000) =      1.090 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.784 ms/op
     p(99.0000) =      6.546 ms/op
     p(99.9000) =     16.728 ms/op
     p(99.9900) =     16.876 ms/op
     p(99.9990) =     16.876 ms/op
     p(99.9999) =     16.876 ms/op
    p(100.0000) =     16.876 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.658          ops/ms
ClientSimple.existUser                       thrpt         12.269          ops/ms
ClientSimple.getUser                         thrpt         12.844          ops/ms
ClientSimple.listUser                        thrpt          8.637          ops/ms
ClientSimple.createUser                       avgt          2.251           ms/op
ClientSimple.existUser                        avgt          1.740           ms/op
ClientSimple.getUser                          avgt          2.077           ms/op
ClientSimple.listUser                         avgt          3.666           ms/op
ClientSimple.createUser                     sample  13491   2.375 ± 0.041   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.229           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.216           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.953           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.080           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.882           ms/op
ClientSimple.createUser:createUser·p0.999   sample         26.083           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         26.870           ms/op
ClientSimple.createUser:createUser·p1.00    sample         26.870           ms/op
ClientSimple.existUser                      sample  17386   1.838 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.536           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.698           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.359           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.920           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.830           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.118           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.827           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.009           ms/op
ClientSimple.getUser                        sample  13779   2.327 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.314           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.220           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.949           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.133           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.068           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.239           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.478           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.485           ms/op
ClientSimple.listUser                       sample   9348   3.433 ± 0.038   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.090           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.195           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.391           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.784           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.546           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.728           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.876           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.876           ms/op

Benchmark result is saved to 1714608915049.json
