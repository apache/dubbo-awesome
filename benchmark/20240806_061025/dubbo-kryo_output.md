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
# Warmup Iteration   1: 0.944 ops/ms
Iteration   1: 5.962 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.962 ops/ms


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
# Warmup Iteration   1: 5.654 ops/ms
Iteration   1: 12.364 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.364 ops/ms


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
# Warmup Iteration   1: 5.476 ops/ms
Iteration   1: 12.504 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.504 ops/ms


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
# Warmup Iteration   1: 5.194 ops/ms
Iteration   1: 9.174 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.174 ops/ms


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
# Warmup Iteration   1: 3.878 ±(99.9%) 0.074 ms/op
Iteration   1: 2.185 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.185 ms/op


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
# Warmup Iteration   1: 3.168 ±(99.9%) 0.051 ms/op
Iteration   1: 1.779 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.779 ms/op


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
# Warmup Iteration   1: 3.529 ±(99.9%) 0.153 ms/op
Iteration   1: 1.841 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.841 ms/op


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
# Warmup Iteration   1: 4.345 ±(99.9%) 0.141 ms/op
Iteration   1: 3.430 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.430 ms/op


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
# Warmup Iteration   1: 3.405 ±(99.9%) 0.087 ms/op
Iteration   1: 2.114 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.622 ms/op
                 createUser·p0.50:   1.933 ms/op
                 createUser·p0.90:   2.552 ms/op
                 createUser·p0.95:   2.863 ms/op
                 createUser·p0.99:   5.546 ms/op
                 createUser·p0.999:  20.443 ms/op
                 createUser·p0.9999: 21.445 ms/op
                 createUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15137
  mean =      2.114 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13416 
    [ 2.500,  5.000) = 1504 
    [ 5.000,  7.500) = 121 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.622 ms/op
     p(50.0000) =      1.933 ms/op
     p(90.0000) =      2.552 ms/op
     p(95.0000) =      2.863 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =     20.443 ms/op
     p(99.9900) =     21.445 ms/op
     p(99.9990) =     21.496 ms/op
     p(99.9999) =     21.496 ms/op
    p(100.0000) =     21.496 ms/op


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
# Warmup Iteration   1: 3.211 ±(99.9%) 0.083 ms/op
Iteration   1: 1.870 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.494 ms/op
                 existUser·p0.50:   1.729 ms/op
                 existUser·p0.90:   2.367 ms/op
                 existUser·p0.95:   2.626 ms/op
                 existUser·p0.99:   3.275 ms/op
                 existUser·p0.999:  14.270 ms/op
                 existUser·p0.9999: 14.448 ms/op
                 existUser·p1.00:   14.483 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17140
  mean =      1.870 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 222 
    [ 1.250,  2.500) = 15707 
    [ 2.500,  3.750) = 1119 
    [ 3.750,  5.000) = 22 
    [ 5.000,  6.250) = 6 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.494 ms/op
     p(50.0000) =      1.729 ms/op
     p(90.0000) =      2.367 ms/op
     p(95.0000) =      2.626 ms/op
     p(99.0000) =      3.275 ms/op
     p(99.9000) =     14.270 ms/op
     p(99.9900) =     14.448 ms/op
     p(99.9990) =     14.483 ms/op
     p(99.9999) =     14.483 ms/op
    p(100.0000) =     14.483 ms/op


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
# Warmup Iteration   1: 3.345 ±(99.9%) 0.086 ms/op
Iteration   1: 2.064 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.835 ms/op
                 getUser·p0.50:   1.985 ms/op
                 getUser·p0.90:   2.589 ms/op
                 getUser·p0.95:   2.900 ms/op
                 getUser·p0.99:   3.728 ms/op
                 getUser·p0.999:  10.905 ms/op
                 getUser·p0.9999: 11.924 ms/op
                 getUser·p1.00:   12.059 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15491
  mean =      2.064 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 438 
    [ 1.250,  2.500) = 13129 
    [ 2.500,  3.750) = 1780 
    [ 3.750,  5.000) = 85 
    [ 5.000,  6.250) = 17 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.835 ms/op
     p(50.0000) =      1.985 ms/op
     p(90.0000) =      2.589 ms/op
     p(95.0000) =      2.900 ms/op
     p(99.0000) =      3.728 ms/op
     p(99.9000) =     10.905 ms/op
     p(99.9900) =     11.924 ms/op
     p(99.9990) =     12.059 ms/op
     p(99.9999) =     12.059 ms/op
    p(100.0000) =     12.059 ms/op


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
# Warmup Iteration   1: 4.519 ±(99.9%) 0.151 ms/op
Iteration   1: 3.143 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.017 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.127 ms/op
                 listUser·p0.99:   4.874 ms/op
                 listUser·p0.999:  10.240 ms/op
                 listUser·p0.9999: 10.322 ms/op
                 listUser·p1.00:   10.322 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10170
  mean =      3.143 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 38 
    [ 2.000,  3.000) = 5426 
    [ 3.000,  4.000) = 3983 
    [ 4.000,  5.000) = 630 
    [ 5.000,  6.000) = 17 
    [ 6.000,  7.000) = 43 
    [ 7.000,  8.000) = 1 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.017 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.127 ms/op
     p(99.0000) =      4.874 ms/op
     p(99.9000) =     10.240 ms/op
     p(99.9900) =     10.322 ms/op
     p(99.9990) =     10.322 ms/op
     p(99.9999) =     10.322 ms/op
    p(100.0000) =     10.322 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.962          ops/ms
ClientSimple.existUser                       thrpt         12.364          ops/ms
ClientSimple.getUser                         thrpt         12.504          ops/ms
ClientSimple.listUser                        thrpt          9.174          ops/ms
ClientSimple.createUser                       avgt          2.185           ms/op
ClientSimple.existUser                        avgt          1.779           ms/op
ClientSimple.getUser                          avgt          1.841           ms/op
ClientSimple.listUser                         avgt          3.430           ms/op
ClientSimple.createUser                     sample  15137   2.114 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.622           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.933           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.552           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.863           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.546           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.443           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.445           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.496           ms/op
ClientSimple.existUser                      sample  17140   1.870 ± 0.020   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.494           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.729           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.367           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.626           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.275           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.270           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.448           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.483           ms/op
ClientSimple.getUser                        sample  15491   2.064 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.835           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.985           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.589           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.900           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.728           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.905           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.924           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.059           ms/op
ClientSimple.listUser                       sample  10170   3.143 ± 0.021   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.017           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.974           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.850           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.127           ms/op
ClientSimple.listUser:listUser·p0.99        sample          4.874           ms/op
ClientSimple.listUser:listUser·p0.999       sample         10.240           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.322           ms/op
ClientSimple.listUser:listUser·p1.00        sample         10.322           ms/op

Benchmark result is saved to 1722924370946.json
