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
# Warmup Iteration   1: 2.355 ops/ms
Iteration   1: 6.830 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.830 ops/ms


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
# Warmup Iteration   1: 6.197 ops/ms
Iteration   1: 12.746 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.746 ops/ms


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
# Warmup Iteration   1: 5.774 ops/ms
Iteration   1: 14.079 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.079 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.780 ops/ms
Iteration   1: 8.570 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.570 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 4.099 ±(99.9%) 0.067 ms/op
Iteration   1: 2.144 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.349 ±(99.9%) 0.045 ms/op
Iteration   1: 1.875 ±(99.9%) 0.008 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.276 ±(99.9%) 0.055 ms/op
Iteration   1: 2.014 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.014 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.344 ±(99.9%) 0.092 ms/op
Iteration   1: 3.713 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.713 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.528 ±(99.9%) 0.087 ms/op
Iteration   1: 2.215 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.572 ms/op
                 createUser·p0.50:   2.017 ms/op
                 createUser·p0.90:   2.630 ms/op
                 createUser·p0.95:   2.912 ms/op
                 createUser·p0.99:   7.127 ms/op
                 createUser·p0.999:  20.218 ms/op
                 createUser·p0.9999: 20.699 ms/op
                 createUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14429
  mean =      2.215 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12430 
    [ 2.500,  5.000) = 1774 
    [ 5.000,  7.500) = 94 
    [ 7.500, 10.000) = 49 
    [10.000, 12.500) = 25 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.572 ms/op
     p(50.0000) =      2.017 ms/op
     p(90.0000) =      2.630 ms/op
     p(95.0000) =      2.912 ms/op
     p(99.0000) =      7.127 ms/op
     p(99.9000) =     20.218 ms/op
     p(99.9900) =     20.699 ms/op
     p(99.9990) =     20.742 ms/op
     p(99.9999) =     20.742 ms/op
    p(100.0000) =     20.742 ms/op


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
# Warmup Iteration   1: 3.063 ±(99.9%) 0.092 ms/op
Iteration   1: 1.926 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.506 ms/op
                 existUser·p0.50:   1.870 ms/op
                 existUser·p0.90:   2.503 ms/op
                 existUser·p0.95:   2.617 ms/op
                 existUser·p0.99:   3.559 ms/op
                 existUser·p0.999:  11.082 ms/op
                 existUser·p0.9999: 11.372 ms/op
                 existUser·p1.00:   11.567 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16601
  mean =      1.926 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 986 
    [ 1.250,  2.500) = 13954 
    [ 2.500,  3.750) = 1515 
    [ 3.750,  5.000) = 113 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.506 ms/op
     p(50.0000) =      1.870 ms/op
     p(90.0000) =      2.503 ms/op
     p(95.0000) =      2.617 ms/op
     p(99.0000) =      3.559 ms/op
     p(99.9000) =     11.082 ms/op
     p(99.9900) =     11.372 ms/op
     p(99.9990) =     11.567 ms/op
     p(99.9999) =     11.567 ms/op
    p(100.0000) =     11.567 ms/op


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
# Warmup Iteration   1: 3.212 ±(99.9%) 0.076 ms/op
Iteration   1: 2.115 ±(99.9%) 0.041 ms/op
                 getUser·p0.00:   0.436 ms/op
                 getUser·p0.50:   1.987 ms/op
                 getUser·p0.90:   2.576 ms/op
                 getUser·p0.95:   2.806 ms/op
                 getUser·p0.99:   5.988 ms/op
                 getUser·p0.999:  26.116 ms/op
                 getUser·p0.9999: 29.553 ms/op
                 getUser·p1.00:   32.768 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15109
  mean =      2.115 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13326 
    [ 2.500,  5.000) = 1609 
    [ 5.000,  7.500) = 76 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.436 ms/op
     p(50.0000) =      1.987 ms/op
     p(90.0000) =      2.576 ms/op
     p(95.0000) =      2.806 ms/op
     p(99.0000) =      5.988 ms/op
     p(99.9000) =     26.116 ms/op
     p(99.9900) =     29.553 ms/op
     p(99.9990) =     32.768 ms/op
     p(99.9999) =     32.768 ms/op
    p(100.0000) =     32.768 ms/op


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
# Warmup Iteration   1: 4.772 ±(99.9%) 0.142 ms/op
Iteration   1: 3.266 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   0.805 ms/op
                 listUser·p0.50:   3.297 ms/op
                 listUser·p0.90:   4.149 ms/op
                 listUser·p0.95:   4.411 ms/op
                 listUser·p0.99:   5.850 ms/op
                 listUser·p0.999:  7.620 ms/op
                 listUser·p0.9999: 7.782 ms/op
                 listUser·p1.00:   7.782 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9789
  mean =      3.266 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 1 
    [1.000, 1.500) = 8 
    [1.500, 2.000) = 202 
    [2.000, 2.500) = 1690 
    [2.500, 3.000) = 1852 
    [3.000, 3.500) = 2265 
    [3.500, 4.000) = 2441 
    [4.000, 4.500) = 934 
    [4.500, 5.000) = 196 
    [5.000, 5.500) = 54 
    [5.500, 6.000) = 70 
    [6.000, 6.500) = 9 
    [6.500, 7.000) = 7 
    [7.000, 7.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.805 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      4.149 ms/op
     p(95.0000) =      4.411 ms/op
     p(99.0000) =      5.850 ms/op
     p(99.9000) =      7.620 ms/op
     p(99.9900) =      7.782 ms/op
     p(99.9990) =      7.782 ms/op
     p(99.9999) =      7.782 ms/op
    p(100.0000) =      7.782 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.830          ops/ms
ClientSimple.existUser                       thrpt         12.746          ops/ms
ClientSimple.getUser                         thrpt         14.079          ops/ms
ClientSimple.listUser                        thrpt          8.570          ops/ms
ClientSimple.createUser                       avgt          2.144           ms/op
ClientSimple.existUser                        avgt          1.875           ms/op
ClientSimple.getUser                          avgt          2.014           ms/op
ClientSimple.listUser                         avgt          3.713           ms/op
ClientSimple.createUser                     sample  14429   2.215 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.572           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.017           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.630           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.912           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.127           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.218           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.699           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.742           ms/op
ClientSimple.existUser                      sample  16601   1.926 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.506           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.870           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.503           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.617           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.559           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.082           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.372           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.567           ms/op
ClientSimple.getUser                        sample  15109   2.115 ± 0.041   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.436           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.987           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.576           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.806           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.988           ms/op
ClientSimple.getUser:getUser·p0.999         sample         26.116           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         29.553           ms/op
ClientSimple.getUser:getUser·p1.00          sample         32.768           ms/op
ClientSimple.listUser                       sample   9789   3.266 ± 0.027   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.805           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.297           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.149           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.411           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.850           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.620           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.782           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.782           ms/op

Benchmark result is saved to 1722427623353.json
