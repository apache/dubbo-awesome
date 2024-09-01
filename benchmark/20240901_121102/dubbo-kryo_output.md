# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.645 ops/ms
Iteration   1: 6.854 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.854 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.698 ops/ms
Iteration   1: 11.147 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.147 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.523 ops/ms
Iteration   1: 12.668 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.668 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.837 ops/ms
Iteration   1: 8.299 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.299 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.759 ±(99.9%) 0.082 ms/op
Iteration   1: 2.032 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.032 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.488 ±(99.9%) 0.064 ms/op
Iteration   1: 2.144 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.144 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.389 ±(99.9%) 0.058 ms/op
Iteration   1: 2.115 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.115 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.023 ±(99.9%) 0.074 ms/op
Iteration   1: 3.162 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.162 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.776 ±(99.9%) 0.097 ms/op
Iteration   1: 2.112 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.935 ms/op
                 createUser·p0.50:   1.907 ms/op
                 createUser·p0.90:   2.535 ms/op
                 createUser·p0.95:   2.830 ms/op
                 createUser·p0.99:   6.308 ms/op
                 createUser·p0.999:  16.171 ms/op
                 createUser·p0.9999: 17.219 ms/op
                 createUser·p1.00:   17.236 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15125
  mean =      2.112 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 69 
    [ 1.250,  2.500) = 13374 
    [ 2.500,  3.750) = 1408 
    [ 3.750,  5.000) = 47 
    [ 5.000,  6.250) = 49 
    [ 6.250,  7.500) = 70 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 60 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.935 ms/op
     p(50.0000) =      1.907 ms/op
     p(90.0000) =      2.535 ms/op
     p(95.0000) =      2.830 ms/op
     p(99.0000) =      6.308 ms/op
     p(99.9000) =     16.171 ms/op
     p(99.9900) =     17.219 ms/op
     p(99.9990) =     17.236 ms/op
     p(99.9999) =     17.236 ms/op
    p(100.0000) =     17.236 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.200 ±(99.9%) 0.092 ms/op
Iteration   1: 1.893 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.516 ms/op
                 existUser·p0.50:   1.845 ms/op
                 existUser·p0.90:   2.294 ms/op
                 existUser·p0.95:   2.458 ms/op
                 existUser·p0.99:   3.350 ms/op
                 existUser·p0.999:  19.202 ms/op
                 existUser·p0.9999: 19.595 ms/op
                 existUser·p1.00:   19.595 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16905
  mean =      1.893 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 825 
    [ 1.250,  2.500) = 15360 
    [ 2.500,  3.750) = 573 
    [ 3.750,  5.000) = 82 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.516 ms/op
     p(50.0000) =      1.845 ms/op
     p(90.0000) =      2.294 ms/op
     p(95.0000) =      2.458 ms/op
     p(99.0000) =      3.350 ms/op
     p(99.9000) =     19.202 ms/op
     p(99.9900) =     19.595 ms/op
     p(99.9990) =     19.595 ms/op
     p(99.9999) =     19.595 ms/op
    p(100.0000) =     19.595 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.137 ±(99.9%) 0.084 ms/op
Iteration   1: 1.980 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.594 ms/op
                 getUser·p0.50:   1.903 ms/op
                 getUser·p0.90:   2.396 ms/op
                 getUser·p0.95:   2.642 ms/op
                 getUser·p0.99:   3.782 ms/op
                 getUser·p0.999:  11.201 ms/op
                 getUser·p0.9999: 11.532 ms/op
                 getUser·p1.00:   11.633 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16161
  mean =      1.980 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 111 
    [ 1.250,  2.500) = 14920 
    [ 2.500,  3.750) = 964 
    [ 3.750,  5.000) = 116 
    [ 5.000,  6.250) = 13 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 18 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.594 ms/op
     p(50.0000) =      1.903 ms/op
     p(90.0000) =      2.396 ms/op
     p(95.0000) =      2.642 ms/op
     p(99.0000) =      3.782 ms/op
     p(99.9000) =     11.201 ms/op
     p(99.9900) =     11.532 ms/op
     p(99.9990) =     11.633 ms/op
     p(99.9999) =     11.633 ms/op
    p(100.0000) =     11.633 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.995 ±(99.9%) 0.151 ms/op
Iteration   1: 3.907 ±(99.9%) 0.121 ms/op
                 listUser·p0.00:   0.446 ms/op
                 listUser·p0.50:   3.617 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   12.324 ms/op
                 listUser·p0.999:  60.948 ms/op
                 listUser·p0.9999: 63.635 ms/op
                 listUser·p1.00:   63.635 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8195
  mean =      3.907 ±(99.9%) 0.121 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 7896 
    [ 5.000, 10.000) = 212 
    [10.000, 15.000) = 9 
    [15.000, 20.000) = 32 
    [20.000, 25.000) = 5 
    [25.000, 30.000) = 8 
    [30.000, 35.000) = 3 
    [35.000, 40.000) = 4 
    [40.000, 45.000) = 4 
    [45.000, 50.000) = 4 
    [50.000, 55.000) = 5 
    [55.000, 60.000) = 1 
    [60.000, 65.000) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.446 ms/op
     p(50.0000) =      3.617 ms/op
     p(90.0000) =      4.506 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =     12.324 ms/op
     p(99.9000) =     60.948 ms/op
     p(99.9900) =     63.635 ms/op
     p(99.9990) =     63.635 ms/op
     p(99.9999) =     63.635 ms/op
    p(100.0000) =     63.635 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.854          ops/ms
ClientSimple.existUser                       thrpt         11.147          ops/ms
ClientSimple.getUser                         thrpt         12.668          ops/ms
ClientSimple.listUser                        thrpt          8.299          ops/ms
ClientSimple.createUser                       avgt          2.032           ms/op
ClientSimple.existUser                        avgt          2.144           ms/op
ClientSimple.getUser                          avgt          2.115           ms/op
ClientSimple.listUser                         avgt          3.162           ms/op
ClientSimple.createUser                     sample  15125   2.112 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.935           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.907           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.535           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.830           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.308           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.171           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.219           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.236           ms/op
ClientSimple.existUser                      sample  16905   1.893 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.516           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.845           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.294           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.458           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.350           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.202           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.595           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.595           ms/op
ClientSimple.getUser                        sample  16161   1.980 ± 0.015   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.594           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.903           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.396           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.642           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.782           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.201           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.532           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.633           ms/op
ClientSimple.listUser                       sample   8195   3.907 ± 0.121   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.446           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.617           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.506           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.776           ms/op
ClientSimple.listUser:listUser·p0.99        sample         12.324           ms/op
ClientSimple.listUser:listUser·p0.999       sample         60.948           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         63.635           ms/op
ClientSimple.listUser:listUser·p1.00        sample         63.635           ms/op

Benchmark result is saved to 1725192400593.json
