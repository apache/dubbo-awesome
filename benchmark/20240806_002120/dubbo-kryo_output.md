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
# Warmup Iteration   1: 1.881 ops/ms
Iteration   1: 6.990 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.990 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.164 ops/ms
Iteration   1: 11.092 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.092 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.763 ops/ms
Iteration   1: 13.085 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.085 ops/ms


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
# Warmup Iteration   1: 6.242 ops/ms
Iteration   1: 8.576 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.576 ops/ms


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
# Warmup Iteration   1: 3.691 ±(99.9%) 0.067 ms/op
Iteration   1: 2.076 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.076 ms/op


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
# Warmup Iteration   1: 3.043 ±(99.9%) 0.048 ms/op
Iteration   1: 1.875 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.875 ms/op


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
# Warmup Iteration   1: 3.215 ±(99.9%) 0.054 ms/op
Iteration   1: 1.844 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.844 ms/op


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
# Warmup Iteration   1: 4.516 ±(99.9%) 0.067 ms/op
Iteration   1: 3.325 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.325 ms/op


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
# Warmup Iteration   1: 3.610 ±(99.9%) 0.083 ms/op
Iteration   1: 2.308 ±(99.9%) 0.042 ms/op
                 createUser·p0.00:   0.664 ms/op
                 createUser·p0.50:   2.066 ms/op
                 createUser·p0.90:   2.757 ms/op
                 createUser·p0.95:   3.079 ms/op
                 createUser·p0.99:   11.445 ms/op
                 createUser·p0.999:  19.176 ms/op
                 createUser·p0.9999: 20.069 ms/op
                 createUser·p1.00:   20.120 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13847
  mean =      2.308 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11269 
    [ 2.500,  5.000) = 2279 
    [ 5.000,  7.500) = 85 
    [ 7.500, 10.000) = 62 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.664 ms/op
     p(50.0000) =      2.066 ms/op
     p(90.0000) =      2.757 ms/op
     p(95.0000) =      3.079 ms/op
     p(99.0000) =     11.445 ms/op
     p(99.9000) =     19.176 ms/op
     p(99.9900) =     20.069 ms/op
     p(99.9990) =     20.120 ms/op
     p(99.9999) =     20.120 ms/op
    p(100.0000) =     20.120 ms/op


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
# Warmup Iteration   1: 3.033 ±(99.9%) 0.075 ms/op
Iteration   1: 1.885 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.537 ms/op
                 existUser·p0.50:   1.729 ms/op
                 existUser·p0.90:   2.388 ms/op
                 existUser·p0.95:   2.834 ms/op
                 existUser·p0.99:   3.813 ms/op
                 existUser·p0.999:  12.485 ms/op
                 existUser·p0.9999: 12.621 ms/op
                 existUser·p1.00:   12.632 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16959
  mean =      1.885 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 61 
    [ 1.250,  2.500) = 15478 
    [ 2.500,  3.750) = 1223 
    [ 3.750,  5.000) = 157 
    [ 5.000,  6.250) = 8 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.537 ms/op
     p(50.0000) =      1.729 ms/op
     p(90.0000) =      2.388 ms/op
     p(95.0000) =      2.834 ms/op
     p(99.0000) =      3.813 ms/op
     p(99.9000) =     12.485 ms/op
     p(99.9900) =     12.621 ms/op
     p(99.9990) =     12.632 ms/op
     p(99.9999) =     12.632 ms/op
    p(100.0000) =     12.632 ms/op


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
# Warmup Iteration   1: 3.468 ±(99.9%) 0.079 ms/op
Iteration   1: 2.186 ±(99.9%) 0.041 ms/op
                 getUser·p0.00:   0.566 ms/op
                 getUser·p0.50:   1.946 ms/op
                 getUser·p0.90:   2.822 ms/op
                 getUser·p0.95:   3.088 ms/op
                 getUser·p0.99:   4.153 ms/op
                 getUser·p0.999:  26.411 ms/op
                 getUser·p0.9999: 27.468 ms/op
                 getUser·p1.00:   27.591 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14682
  mean =      2.186 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11518 
    [ 2.500,  5.000) = 3065 
    [ 5.000,  7.500) = 35 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.566 ms/op
     p(50.0000) =      1.946 ms/op
     p(90.0000) =      2.822 ms/op
     p(95.0000) =      3.088 ms/op
     p(99.0000) =      4.153 ms/op
     p(99.9000) =     26.411 ms/op
     p(99.9900) =     27.468 ms/op
     p(99.9990) =     27.591 ms/op
     p(99.9999) =     27.591 ms/op
    p(100.0000) =     27.591 ms/op


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
# Warmup Iteration   1: 4.072 ±(99.9%) 0.115 ms/op
Iteration   1: 3.305 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.370 ms/op
                 listUser·p0.50:   3.039 ms/op
                 listUser·p0.90:   4.409 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  7.015 ms/op
                 listUser·p0.9999: 11.010 ms/op
                 listUser·p1.00:   11.010 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9757
  mean =      3.305 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 79 
    [ 2.000,  3.000) = 4726 
    [ 3.000,  4.000) = 2919 
    [ 4.000,  5.000) = 1752 
    [ 5.000,  6.000) = 229 
    [ 6.000,  7.000) = 43 
    [ 7.000,  8.000) = 3 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 3 
    [10.000, 11.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.370 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      4.409 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =      7.015 ms/op
     p(99.9900) =     11.010 ms/op
     p(99.9990) =     11.010 ms/op
     p(99.9999) =     11.010 ms/op
    p(100.0000) =     11.010 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.990          ops/ms
ClientSimple.existUser                       thrpt         11.092          ops/ms
ClientSimple.getUser                         thrpt         13.085          ops/ms
ClientSimple.listUser                        thrpt          8.576          ops/ms
ClientSimple.createUser                       avgt          2.076           ms/op
ClientSimple.existUser                        avgt          1.875           ms/op
ClientSimple.getUser                          avgt          1.844           ms/op
ClientSimple.listUser                         avgt          3.325           ms/op
ClientSimple.createUser                     sample  13847   2.308 ± 0.042   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.664           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.066           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.757           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.079           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.445           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.176           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.069           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.120           ms/op
ClientSimple.existUser                      sample  16959   1.885 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.537           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.729           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.388           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.834           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.813           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.485           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.621           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.632           ms/op
ClientSimple.getUser                        sample  14682   2.186 ± 0.041   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.566           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.946           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.822           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.088           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.153           ms/op
ClientSimple.getUser:getUser·p0.999         sample         26.411           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         27.468           ms/op
ClientSimple.getUser:getUser·p1.00          sample         27.591           ms/op
ClientSimple.listUser                       sample   9757   3.305 ± 0.027   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.370           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.039           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.409           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.735           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.538           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.015           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         11.010           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.010           ms/op

Benchmark result is saved to 1722903404136.json
