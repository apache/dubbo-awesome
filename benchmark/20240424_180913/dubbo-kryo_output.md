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
# Warmup Iteration   1: 0.722 ops/ms
Iteration   1: 5.898 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.898 ops/ms


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
# Warmup Iteration   1: 5.083 ops/ms
Iteration   1: 12.696 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.696 ops/ms


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
# Warmup Iteration   1: 5.732 ops/ms
Iteration   1: 12.034 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.034 ops/ms


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
# Warmup Iteration   1: 4.063 ops/ms
Iteration   1: 8.530 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.530 ops/ms


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
# Warmup Iteration   1: 4.630 ±(99.9%) 0.110 ms/op
Iteration   1: 2.150 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.150 ms/op


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
# Warmup Iteration   1: 3.072 ±(99.9%) 0.061 ms/op
Iteration   1: 1.884 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.884 ms/op


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
# Warmup Iteration   1: 3.194 ±(99.9%) 0.067 ms/op
Iteration   1: 1.842 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.842 ms/op


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
# Warmup Iteration   1: 4.714 ±(99.9%) 0.103 ms/op
Iteration   1: 3.572 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.572 ms/op


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
# Warmup Iteration   1: 3.672 ±(99.9%) 0.095 ms/op
Iteration   1: 2.067 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.663 ms/op
                 createUser·p0.50:   1.929 ms/op
                 createUser·p0.90:   2.367 ms/op
                 createUser·p0.95:   2.531 ms/op
                 createUser·p0.99:   6.145 ms/op
                 createUser·p0.999:  18.420 ms/op
                 createUser·p0.9999: 19.509 ms/op
                 createUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15466
  mean =      2.067 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 296 
    [ 1.250,  2.500) = 14317 
    [ 2.500,  3.750) = 673 
    [ 3.750,  5.000) = 16 
    [ 5.000,  6.250) = 10 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.663 ms/op
     p(50.0000) =      1.929 ms/op
     p(90.0000) =      2.367 ms/op
     p(95.0000) =      2.531 ms/op
     p(99.0000) =      6.145 ms/op
     p(99.9000) =     18.420 ms/op
     p(99.9900) =     19.509 ms/op
     p(99.9990) =     19.562 ms/op
     p(99.9999) =     19.562 ms/op
    p(100.0000) =     19.562 ms/op


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
# Warmup Iteration   1: 2.959 ±(99.9%) 0.071 ms/op
Iteration   1: 1.822 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.572 ms/op
                 existUser·p0.50:   1.681 ms/op
                 existUser·p0.90:   2.400 ms/op
                 existUser·p0.95:   2.556 ms/op
                 existUser·p0.99:   3.266 ms/op
                 existUser·p0.999:  16.335 ms/op
                 existUser·p0.9999: 16.974 ms/op
                 existUser·p1.00:   16.974 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17573
  mean =      1.822 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1122 
    [ 1.250,  2.500) = 15354 
    [ 2.500,  3.750) = 969 
    [ 3.750,  5.000) = 57 
    [ 5.000,  6.250) = 7 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.572 ms/op
     p(50.0000) =      1.681 ms/op
     p(90.0000) =      2.400 ms/op
     p(95.0000) =      2.556 ms/op
     p(99.0000) =      3.266 ms/op
     p(99.9000) =     16.335 ms/op
     p(99.9900) =     16.974 ms/op
     p(99.9990) =     16.974 ms/op
     p(99.9999) =     16.974 ms/op
    p(100.0000) =     16.974 ms/op


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
# Warmup Iteration   1: 3.197 ±(99.9%) 0.076 ms/op
Iteration   1: 1.989 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.706 ms/op
                 getUser·p0.50:   1.858 ms/op
                 getUser·p0.90:   2.511 ms/op
                 getUser·p0.95:   2.675 ms/op
                 getUser·p0.99:   3.480 ms/op
                 getUser·p0.999:  11.368 ms/op
                 getUser·p0.9999: 11.814 ms/op
                 getUser·p1.00:   11.895 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16176
  mean =      1.989 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 115 
    [ 1.250,  2.500) = 14375 
    [ 2.500,  3.750) = 1551 
    [ 3.750,  5.000) = 36 
    [ 5.000,  6.250) = 54 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.706 ms/op
     p(50.0000) =      1.858 ms/op
     p(90.0000) =      2.511 ms/op
     p(95.0000) =      2.675 ms/op
     p(99.0000) =      3.480 ms/op
     p(99.9000) =     11.368 ms/op
     p(99.9900) =     11.814 ms/op
     p(99.9990) =     11.895 ms/op
     p(99.9999) =     11.895 ms/op
    p(100.0000) =     11.895 ms/op


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
# Warmup Iteration   1: 4.846 ±(99.9%) 0.151 ms/op
Iteration   1: 3.401 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   0.976 ms/op
                 listUser·p0.50:   3.387 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   6.275 ms/op
                 listUser·p0.999:  9.218 ms/op
                 listUser·p0.9999: 9.568 ms/op
                 listUser·p1.00:   9.568 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9399
  mean =      3.401 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 1 
    [ 1.000,  2.000) = 190 
    [ 2.000,  3.000) = 3085 
    [ 3.000,  4.000) = 4203 
    [ 4.000,  5.000) = 1627 
    [ 5.000,  6.000) = 158 
    [ 6.000,  7.000) = 90 
    [ 7.000,  8.000) = 21 
    [ 8.000,  9.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.976 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      6.275 ms/op
     p(99.9000) =      9.218 ms/op
     p(99.9900) =      9.568 ms/op
     p(99.9990) =      9.568 ms/op
     p(99.9999) =      9.568 ms/op
    p(100.0000) =      9.568 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.898          ops/ms
ClientSimple.existUser                       thrpt         12.696          ops/ms
ClientSimple.getUser                         thrpt         12.034          ops/ms
ClientSimple.listUser                        thrpt          8.530          ops/ms
ClientSimple.createUser                       avgt          2.150           ms/op
ClientSimple.existUser                        avgt          1.884           ms/op
ClientSimple.getUser                          avgt          1.842           ms/op
ClientSimple.listUser                         avgt          3.572           ms/op
ClientSimple.createUser                     sample  15466   2.067 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.663           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.929           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.367           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.531           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.145           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.420           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.509           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.562           ms/op
ClientSimple.existUser                      sample  17573   1.822 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.572           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.681           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.400           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.556           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.266           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.335           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.974           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.974           ms/op
ClientSimple.getUser                        sample  16176   1.989 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.706           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.858           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.511           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.675           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.480           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.368           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.814           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.895           ms/op
ClientSimple.listUser                       sample   9399   3.401 ± 0.029   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.976           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.387           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.276           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.604           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.275           ms/op
ClientSimple.listUser:listUser·p0.999       sample          9.218           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.568           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.568           ms/op

Benchmark result is saved to 1713981896789.json
