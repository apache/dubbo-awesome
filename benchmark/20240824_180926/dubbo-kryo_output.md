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
# Warmup Iteration   1: 1.327 ops/ms
Iteration   1: 6.196 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.196 ops/ms


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
# Warmup Iteration   1: 4.644 ops/ms
Iteration   1: 10.473 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.473 ops/ms


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
# Warmup Iteration   1: 5.189 ops/ms
Iteration   1: 12.350 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.350 ops/ms


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
# Warmup Iteration   1: 5.188 ops/ms
Iteration   1: 8.509 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.509 ops/ms


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
# Warmup Iteration   1: 4.086 ±(99.9%) 0.078 ms/op
Iteration   1: 2.191 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.191 ms/op


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
# Warmup Iteration   1: 3.130 ±(99.9%) 0.049 ms/op
Iteration   1: 2.133 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.133 ms/op


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
# Warmup Iteration   1: 3.512 ±(99.9%) 0.066 ms/op
Iteration   1: 1.958 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.958 ms/op


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
# Warmup Iteration   1: 4.591 ±(99.9%) 0.095 ms/op
Iteration   1: 3.502 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.502 ms/op


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
# Warmup Iteration   1: 3.537 ±(99.9%) 0.088 ms/op
Iteration   1: 2.266 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.466 ms/op
                 createUser·p0.50:   2.134 ms/op
                 createUser·p0.90:   2.888 ms/op
                 createUser·p0.95:   3.109 ms/op
                 createUser·p0.99:   7.070 ms/op
                 createUser·p0.999:  11.835 ms/op
                 createUser·p0.9999: 12.784 ms/op
                 createUser·p1.00:   12.845 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14166
  mean =      2.266 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 547 
    [ 1.250,  2.500) = 9909 
    [ 2.500,  3.750) = 3239 
    [ 3.750,  5.000) = 202 
    [ 5.000,  6.250) = 68 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 47 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.466 ms/op
     p(50.0000) =      2.134 ms/op
     p(90.0000) =      2.888 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      7.070 ms/op
     p(99.9000) =     11.835 ms/op
     p(99.9900) =     12.784 ms/op
     p(99.9990) =     12.845 ms/op
     p(99.9999) =     12.845 ms/op
    p(100.0000) =     12.845 ms/op


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
# Warmup Iteration   1: 2.977 ±(99.9%) 0.072 ms/op
Iteration   1: 1.888 ±(99.9%) 0.030 ms/op
                 existUser·p0.00:   0.739 ms/op
                 existUser·p0.50:   1.712 ms/op
                 existUser·p0.90:   2.294 ms/op
                 existUser·p0.95:   2.421 ms/op
                 existUser·p0.99:   4.915 ms/op
                 existUser·p0.999:  19.956 ms/op
                 existUser·p0.9999: 20.152 ms/op
                 existUser·p1.00:   20.152 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16946
  mean =      1.888 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16432 
    [ 2.500,  5.000) = 365 
    [ 5.000,  7.500) = 52 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.739 ms/op
     p(50.0000) =      1.712 ms/op
     p(90.0000) =      2.294 ms/op
     p(95.0000) =      2.421 ms/op
     p(99.0000) =      4.915 ms/op
     p(99.9000) =     19.956 ms/op
     p(99.9900) =     20.152 ms/op
     p(99.9990) =     20.152 ms/op
     p(99.9999) =     20.152 ms/op
    p(100.0000) =     20.152 ms/op


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
# Warmup Iteration   1: 3.165 ±(99.9%) 0.079 ms/op
Iteration   1: 2.210 ±(99.9%) 0.053 ms/op
                 getUser·p0.00:   0.529 ms/op
                 getUser·p0.50:   2.126 ms/op
                 getUser·p0.90:   2.736 ms/op
                 getUser·p0.95:   2.949 ms/op
                 getUser·p0.99:   3.896 ms/op
                 getUser·p0.999:  46.124 ms/op
                 getUser·p0.9999: 56.812 ms/op
                 getUser·p1.00:   56.951 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14220
  mean =      2.210 ±(99.9%) 0.053 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 14113 
    [ 5.000, 10.000) = 35 
    [10.000, 15.000) = 37 
    [15.000, 20.000) = 17 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 3 
    [45.000, 50.000) = 8 
    [50.000, 55.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.529 ms/op
     p(50.0000) =      2.126 ms/op
     p(90.0000) =      2.736 ms/op
     p(95.0000) =      2.949 ms/op
     p(99.0000) =      3.896 ms/op
     p(99.9000) =     46.124 ms/op
     p(99.9900) =     56.812 ms/op
     p(99.9990) =     56.951 ms/op
     p(99.9999) =     56.951 ms/op
    p(100.0000) =     56.951 ms/op


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
# Warmup Iteration   1: 5.097 ±(99.9%) 0.144 ms/op
Iteration   1: 3.305 ±(99.9%) 0.048 ms/op
                 listUser·p0.00:   0.925 ms/op
                 listUser·p0.50:   3.138 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   10.042 ms/op
                 listUser·p0.999:  16.285 ms/op
                 listUser·p0.9999: 18.612 ms/op
                 listUser·p1.00:   18.612 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9673
  mean =      3.305 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 12 
    [ 1.250,  2.500) = 2232 
    [ 2.500,  3.750) = 4743 
    [ 3.750,  5.000) = 2406 
    [ 5.000,  6.250) = 106 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 53 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.925 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =     10.042 ms/op
     p(99.9000) =     16.285 ms/op
     p(99.9900) =     18.612 ms/op
     p(99.9990) =     18.612 ms/op
     p(99.9999) =     18.612 ms/op
    p(100.0000) =     18.612 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.196          ops/ms
ClientSimple.existUser                       thrpt         10.473          ops/ms
ClientSimple.getUser                         thrpt         12.350          ops/ms
ClientSimple.listUser                        thrpt          8.509          ops/ms
ClientSimple.createUser                       avgt          2.191           ms/op
ClientSimple.existUser                        avgt          2.133           ms/op
ClientSimple.getUser                          avgt          1.958           ms/op
ClientSimple.listUser                         avgt          3.502           ms/op
ClientSimple.createUser                     sample  14166   2.266 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.466           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.134           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.888           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.109           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.070           ms/op
ClientSimple.createUser:createUser·p0.999   sample         11.835           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         12.784           ms/op
ClientSimple.createUser:createUser·p1.00    sample         12.845           ms/op
ClientSimple.existUser                      sample  16946   1.888 ± 0.030   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.739           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.712           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.294           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.421           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.915           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.956           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         20.152           ms/op
ClientSimple.existUser:existUser·p1.00      sample         20.152           ms/op
ClientSimple.getUser                        sample  14220   2.210 ± 0.053   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.529           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.126           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.736           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.949           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.896           ms/op
ClientSimple.getUser:getUser·p0.999         sample         46.124           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         56.812           ms/op
ClientSimple.getUser:getUser·p1.00          sample         56.951           ms/op
ClientSimple.listUser                       sample   9673   3.305 ± 0.048   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.925           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.138           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.235           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.538           ms/op
ClientSimple.listUser:listUser·p0.99        sample         10.042           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.285           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.612           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.612           ms/op

Benchmark result is saved to 1724522697813.json
