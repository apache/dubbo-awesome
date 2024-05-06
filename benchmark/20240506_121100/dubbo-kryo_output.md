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
# Warmup Iteration   1: 2.085 ops/ms
Iteration   1: 7.321 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.321 ops/ms


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
# Warmup Iteration   1: 6.000 ops/ms
Iteration   1: 12.805 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.805 ops/ms


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
# Warmup Iteration   1: 5.410 ops/ms
Iteration   1: 11.926 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.926 ops/ms


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
# Warmup Iteration   1: 4.698 ops/ms
Iteration   1: 7.636 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.636 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 4.043 ±(99.9%) 0.083 ms/op
Iteration   1: 2.053 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.053 ms/op


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
# Warmup Iteration   1: 3.251 ±(99.9%) 0.052 ms/op
Iteration   1: 1.840 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.840 ms/op


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
# Warmup Iteration   1: 3.204 ±(99.9%) 0.051 ms/op
Iteration   1: 2.134 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.134 ms/op


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
# Warmup Iteration   1: 4.411 ±(99.9%) 0.074 ms/op
Iteration   1: 3.332 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.332 ms/op


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
# Warmup Iteration   1: 3.602 ±(99.9%) 0.087 ms/op
Iteration   1: 2.358 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.633 ms/op
                 createUser·p0.50:   2.232 ms/op
                 createUser·p0.90:   2.949 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   5.712 ms/op
                 createUser·p0.999:  23.377 ms/op
                 createUser·p0.9999: 26.123 ms/op
                 createUser·p1.00:   26.182 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13576
  mean =      2.358 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9557 
    [ 2.500,  5.000) = 3844 
    [ 5.000,  7.500) = 78 
    [ 7.500, 10.000) = 33 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.633 ms/op
     p(50.0000) =      2.232 ms/op
     p(90.0000) =      2.949 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      5.712 ms/op
     p(99.9000) =     23.377 ms/op
     p(99.9900) =     26.123 ms/op
     p(99.9990) =     26.182 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


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
# Warmup Iteration   1: 3.068 ±(99.9%) 0.072 ms/op
Iteration   1: 1.808 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.530 ms/op
                 existUser·p0.50:   1.696 ms/op
                 existUser·p0.90:   2.269 ms/op
                 existUser·p0.95:   2.478 ms/op
                 existUser·p0.99:   4.900 ms/op
                 existUser·p0.999:  14.898 ms/op
                 existUser·p0.9999: 15.057 ms/op
                 existUser·p1.00:   15.057 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17689
  mean =      1.808 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 575 
    [ 1.250,  2.500) = 16287 
    [ 2.500,  3.750) = 546 
    [ 3.750,  5.000) = 131 
    [ 5.000,  6.250) = 81 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.530 ms/op
     p(50.0000) =      1.696 ms/op
     p(90.0000) =      2.269 ms/op
     p(95.0000) =      2.478 ms/op
     p(99.0000) =      4.900 ms/op
     p(99.9000) =     14.898 ms/op
     p(99.9900) =     15.057 ms/op
     p(99.9990) =     15.057 ms/op
     p(99.9999) =     15.057 ms/op
    p(100.0000) =     15.057 ms/op


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
# Warmup Iteration   1: 3.323 ±(99.9%) 0.090 ms/op
Iteration   1: 1.927 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.318 ms/op
                 getUser·p0.50:   1.833 ms/op
                 getUser·p0.90:   2.408 ms/op
                 getUser·p0.95:   2.712 ms/op
                 getUser·p0.99:   4.161 ms/op
                 getUser·p0.999:  11.359 ms/op
                 getUser·p0.9999: 12.239 ms/op
                 getUser·p1.00:   12.239 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16785
  mean =      1.927 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 484 
    [ 1.250,  2.500) = 14928 
    [ 2.500,  3.750) = 1123 
    [ 3.750,  5.000) = 201 
    [ 5.000,  6.250) = 14 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 15 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.318 ms/op
     p(50.0000) =      1.833 ms/op
     p(90.0000) =      2.408 ms/op
     p(95.0000) =      2.712 ms/op
     p(99.0000) =      4.161 ms/op
     p(99.9000) =     11.359 ms/op
     p(99.9900) =     12.239 ms/op
     p(99.9990) =     12.239 ms/op
     p(99.9999) =     12.239 ms/op
    p(100.0000) =     12.239 ms/op


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
# Warmup Iteration   1: 4.672 ±(99.9%) 0.164 ms/op
Iteration   1: 3.482 ±(99.9%) 0.042 ms/op
                 listUser·p0.00:   0.800 ms/op
                 listUser·p0.50:   3.346 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  20.861 ms/op
                 listUser·p0.9999: 23.757 ms/op
                 listUser·p1.00:   23.757 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9181
  mean =      3.482 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 297 
    [ 2.500,  5.000) = 8726 
    [ 5.000,  7.500) = 121 
    [ 7.500, 10.000) = 5 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.800 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =     20.861 ms/op
     p(99.9900) =     23.757 ms/op
     p(99.9990) =     23.757 ms/op
     p(99.9999) =     23.757 ms/op
    p(100.0000) =     23.757 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.321          ops/ms
ClientSimple.existUser                       thrpt         12.805          ops/ms
ClientSimple.getUser                         thrpt         11.926          ops/ms
ClientSimple.listUser                        thrpt          7.636          ops/ms
ClientSimple.createUser                       avgt          2.053           ms/op
ClientSimple.existUser                        avgt          1.840           ms/op
ClientSimple.getUser                          avgt          2.134           ms/op
ClientSimple.listUser                         avgt          3.332           ms/op
ClientSimple.createUser                     sample  13576   2.358 ± 0.037   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.633           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.232           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.949           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.191           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.712           ms/op
ClientSimple.createUser:createUser·p0.999   sample         23.377           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         26.123           ms/op
ClientSimple.createUser:createUser·p1.00    sample         26.182           ms/op
ClientSimple.existUser                      sample  17689   1.808 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.530           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.696           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.269           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.478           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.900           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.898           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.057           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.057           ms/op
ClientSimple.getUser                        sample  16785   1.927 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.318           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.833           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.408           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.712           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.161           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.359           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.239           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.239           ms/op
ClientSimple.listUser                       sample   9181   3.482 ± 0.042   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.800           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.346           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.317           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.522           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.685           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.861           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         23.757           ms/op
ClientSimple.listUser:listUser·p1.00        sample         23.757           ms/op

Benchmark result is saved to 1714997182812.json
