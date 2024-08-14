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
# Warmup Iteration   1: 1.820 ops/ms
Iteration   1: 7.874 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.874 ops/ms


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
# Warmup Iteration   1: 6.301 ops/ms
Iteration   1: 13.992 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.992 ops/ms


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
# Warmup Iteration   1: 4.919 ops/ms
Iteration   1: 13.636 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.636 ops/ms


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
# Warmup Iteration   1: 4.334 ops/ms
Iteration   1: 8.258 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.258 ops/ms


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
# Warmup Iteration   1: 4.025 ±(99.9%) 0.065 ms/op
Iteration   1: 2.127 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.127 ms/op


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
# Warmup Iteration   1: 3.302 ±(99.9%) 0.064 ms/op
Iteration   1: 1.811 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.811 ms/op


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
# Warmup Iteration   1: 3.172 ±(99.9%) 0.051 ms/op
Iteration   1: 1.894 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.894 ms/op


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
# Warmup Iteration   1: 4.746 ±(99.9%) 0.126 ms/op
Iteration   1: 3.293 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.293 ms/op


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
# Warmup Iteration   1: 3.524 ±(99.9%) 0.080 ms/op
Iteration   1: 2.070 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.792 ms/op
                 createUser·p0.50:   1.982 ms/op
                 createUser·p0.90:   2.380 ms/op
                 createUser·p0.95:   2.535 ms/op
                 createUser·p0.99:   4.936 ms/op
                 createUser·p0.999:  16.067 ms/op
                 createUser·p0.9999: 17.859 ms/op
                 createUser·p1.00:   17.859 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15443
  mean =      2.070 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 193 
    [ 1.250,  2.500) = 14344 
    [ 2.500,  3.750) = 706 
    [ 3.750,  5.000) = 55 
    [ 5.000,  6.250) = 17 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 42 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.792 ms/op
     p(50.0000) =      1.982 ms/op
     p(90.0000) =      2.380 ms/op
     p(95.0000) =      2.535 ms/op
     p(99.0000) =      4.936 ms/op
     p(99.9000) =     16.067 ms/op
     p(99.9900) =     17.859 ms/op
     p(99.9990) =     17.859 ms/op
     p(99.9999) =     17.859 ms/op
    p(100.0000) =     17.859 ms/op


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
# Warmup Iteration   1: 3.024 ±(99.9%) 0.071 ms/op
Iteration   1: 1.796 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.745 ms/op
                 existUser·p0.50:   1.618 ms/op
                 existUser·p0.90:   2.433 ms/op
                 existUser·p0.95:   2.572 ms/op
                 existUser·p0.99:   3.304 ms/op
                 existUser·p0.999:  11.798 ms/op
                 existUser·p0.9999: 12.124 ms/op
                 existUser·p1.00:   12.124 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17921
  mean =      1.796 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 732 
    [ 1.250,  2.500) = 15892 
    [ 2.500,  3.750) = 1181 
    [ 3.750,  5.000) = 51 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.745 ms/op
     p(50.0000) =      1.618 ms/op
     p(90.0000) =      2.433 ms/op
     p(95.0000) =      2.572 ms/op
     p(99.0000) =      3.304 ms/op
     p(99.9000) =     11.798 ms/op
     p(99.9900) =     12.124 ms/op
     p(99.9990) =     12.124 ms/op
     p(99.9999) =     12.124 ms/op
    p(100.0000) =     12.124 ms/op


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
# Warmup Iteration   1: 3.084 ±(99.9%) 0.074 ms/op
Iteration   1: 2.008 ±(99.9%) 0.035 ms/op
                 getUser·p0.00:   0.530 ms/op
                 getUser·p0.50:   1.882 ms/op
                 getUser·p0.90:   2.470 ms/op
                 getUser·p0.95:   2.720 ms/op
                 getUser·p0.99:   4.030 ms/op
                 getUser·p0.999:  27.165 ms/op
                 getUser·p0.9999: 27.997 ms/op
                 getUser·p1.00:   28.017 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15937
  mean =      2.008 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14474 
    [ 2.500,  5.000) = 1328 
    [ 5.000,  7.500) = 63 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 8 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.530 ms/op
     p(50.0000) =      1.882 ms/op
     p(90.0000) =      2.470 ms/op
     p(95.0000) =      2.720 ms/op
     p(99.0000) =      4.030 ms/op
     p(99.9000) =     27.165 ms/op
     p(99.9900) =     27.997 ms/op
     p(99.9990) =     28.017 ms/op
     p(99.9999) =     28.017 ms/op
    p(100.0000) =     28.017 ms/op


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
# Warmup Iteration   1: 4.445 ±(99.9%) 0.128 ms/op
Iteration   1: 3.099 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   0.902 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   4.002 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.705 ms/op
                 listUser·p0.999:  7.447 ms/op
                 listUser·p0.9999: 7.544 ms/op
                 listUser·p1.00:   7.545 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10357
  mean =      3.099 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 3 
    [1.000, 1.500) = 27 
    [1.500, 2.000) = 157 
    [2.000, 2.500) = 1905 
    [2.500, 3.000) = 3493 
    [3.000, 3.500) = 2011 
    [3.500, 4.000) = 1721 
    [4.000, 4.500) = 684 
    [4.500, 5.000) = 161 
    [5.000, 5.500) = 70 
    [5.500, 6.000) = 72 
    [6.000, 6.500) = 20 
    [6.500, 7.000) = 1 
    [7.000, 7.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.902 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      4.002 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.705 ms/op
     p(99.9000) =      7.447 ms/op
     p(99.9900) =      7.544 ms/op
     p(99.9990) =      7.545 ms/op
     p(99.9999) =      7.545 ms/op
    p(100.0000) =      7.545 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.874          ops/ms
ClientSimple.existUser                       thrpt         13.992          ops/ms
ClientSimple.getUser                         thrpt         13.636          ops/ms
ClientSimple.listUser                        thrpt          8.258          ops/ms
ClientSimple.createUser                       avgt          2.127           ms/op
ClientSimple.existUser                        avgt          1.811           ms/op
ClientSimple.getUser                          avgt          1.894           ms/op
ClientSimple.listUser                         avgt          3.293           ms/op
ClientSimple.createUser                     sample  15443   2.070 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.792           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.982           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.380           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.535           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.936           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.067           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.859           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.859           ms/op
ClientSimple.existUser                      sample  17921   1.796 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.745           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.618           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.433           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.572           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.304           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.798           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.124           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.124           ms/op
ClientSimple.getUser                        sample  15937   2.008 ± 0.035   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.530           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.882           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.470           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.720           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.030           ms/op
ClientSimple.getUser:getUser·p0.999         sample         27.165           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         27.997           ms/op
ClientSimple.getUser:getUser·p1.00          sample         28.017           ms/op
ClientSimple.listUser                       sample  10357   3.099 ± 0.024   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.902           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.920           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.002           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.325           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.705           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.447           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.544           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.545           ms/op

Benchmark result is saved to 1723615559018.json
