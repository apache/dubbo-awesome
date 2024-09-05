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
# Warmup Iteration   1: 1.817 ops/ms
Iteration   1: 6.841 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.841 ops/ms


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
# Warmup Iteration   1: 5.929 ops/ms
Iteration   1: 12.557 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.557 ops/ms


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
# Warmup Iteration   1: 4.390 ops/ms
Iteration   1: 12.473 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.473 ops/ms


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
# Warmup Iteration   1: 5.786 ops/ms
Iteration   1: 8.409 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.409 ops/ms


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
# Warmup Iteration   1: 3.936 ±(99.9%) 0.085 ms/op
Iteration   1: 2.142 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.142 ms/op


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
# Warmup Iteration   1: 3.095 ±(99.9%) 0.045 ms/op
Iteration   1: 2.212 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.212 ms/op


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
# Warmup Iteration   1: 3.373 ±(99.9%) 0.065 ms/op
Iteration   1: 1.696 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.696 ms/op


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
# Warmup Iteration   1: 5.976 ±(99.9%) 0.138 ms/op
Iteration   1: 3.599 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.599 ms/op


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
# Warmup Iteration   1: 3.948 ±(99.9%) 0.159 ms/op
Iteration   1: 2.063 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.809 ms/op
                 createUser·p0.50:   1.855 ms/op
                 createUser·p0.90:   2.367 ms/op
                 createUser·p0.95:   2.662 ms/op
                 createUser·p0.99:   8.324 ms/op
                 createUser·p0.999:  15.974 ms/op
                 createUser·p0.9999: 16.431 ms/op
                 createUser·p1.00:   16.450 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15593
  mean =      2.063 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 39 
    [ 1.250,  2.500) = 14406 
    [ 2.500,  3.750) = 877 
    [ 3.750,  5.000) = 62 
    [ 5.000,  6.250) = 45 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 52 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.809 ms/op
     p(50.0000) =      1.855 ms/op
     p(90.0000) =      2.367 ms/op
     p(95.0000) =      2.662 ms/op
     p(99.0000) =      8.324 ms/op
     p(99.9000) =     15.974 ms/op
     p(99.9900) =     16.431 ms/op
     p(99.9990) =     16.450 ms/op
     p(99.9999) =     16.450 ms/op
    p(100.0000) =     16.450 ms/op


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
# Warmup Iteration   1: 3.153 ±(99.9%) 0.090 ms/op
Iteration   1: 1.918 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.475 ms/op
                 existUser·p0.50:   1.761 ms/op
                 existUser·p0.90:   2.662 ms/op
                 existUser·p0.95:   2.966 ms/op
                 existUser·p0.99:   4.143 ms/op
                 existUser·p0.999:  12.900 ms/op
                 existUser·p0.9999: 13.937 ms/op
                 existUser·p1.00:   13.959 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16664
  mean =      1.918 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2009 
    [ 1.250,  2.500) = 12032 
    [ 2.500,  3.750) = 2417 
    [ 3.750,  5.000) = 129 
    [ 5.000,  6.250) = 36 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.475 ms/op
     p(50.0000) =      1.761 ms/op
     p(90.0000) =      2.662 ms/op
     p(95.0000) =      2.966 ms/op
     p(99.0000) =      4.143 ms/op
     p(99.9000) =     12.900 ms/op
     p(99.9900) =     13.937 ms/op
     p(99.9990) =     13.959 ms/op
     p(99.9999) =     13.959 ms/op
    p(100.0000) =     13.959 ms/op


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
# Warmup Iteration   1: 3.548 ±(99.9%) 0.075 ms/op
Iteration   1: 1.928 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.713 ms/op
                 getUser·p0.50:   1.806 ms/op
                 getUser·p0.90:   2.388 ms/op
                 getUser·p0.95:   2.572 ms/op
                 getUser·p0.99:   3.669 ms/op
                 getUser·p0.999:  12.674 ms/op
                 getUser·p0.9999: 12.899 ms/op
                 getUser·p1.00:   12.976 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16722
  mean =      1.928 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 218 
    [ 1.250,  2.500) = 15422 
    [ 2.500,  3.750) = 920 
    [ 3.750,  5.000) = 74 
    [ 5.000,  6.250) = 24 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.713 ms/op
     p(50.0000) =      1.806 ms/op
     p(90.0000) =      2.388 ms/op
     p(95.0000) =      2.572 ms/op
     p(99.0000) =      3.669 ms/op
     p(99.9000) =     12.674 ms/op
     p(99.9900) =     12.899 ms/op
     p(99.9990) =     12.976 ms/op
     p(99.9999) =     12.976 ms/op
    p(100.0000) =     12.976 ms/op


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
# Warmup Iteration   1: 4.329 ±(99.9%) 0.140 ms/op
Iteration   1: 3.165 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.288 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  9.617 ms/op
                 listUser·p0.9999: 9.699 ms/op
                 listUser·p1.00:   9.699 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10096
  mean =      3.165 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 5 
    [ 1.500,  2.000) = 142 
    [ 2.000,  2.500) = 1342 
    [ 2.500,  3.000) = 3658 
    [ 3.000,  3.500) = 2122 
    [ 3.500,  4.000) = 1947 
    [ 4.000,  4.500) = 511 
    [ 4.500,  5.000) = 84 
    [ 5.000,  5.500) = 86 
    [ 5.500,  6.000) = 23 
    [ 6.000,  6.500) = 15 
    [ 6.500,  7.000) = 77 
    [ 7.000,  7.500) = 33 
    [ 7.500,  8.000) = 18 
    [ 8.000,  8.500) = 1 
    [ 8.500,  9.000) = 1 
    [ 9.000,  9.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.288 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.965 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =      9.617 ms/op
     p(99.9900) =      9.699 ms/op
     p(99.9990) =      9.699 ms/op
     p(99.9999) =      9.699 ms/op
    p(100.0000) =      9.699 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.841          ops/ms
ClientSimple.existUser                       thrpt         12.557          ops/ms
ClientSimple.getUser                         thrpt         12.473          ops/ms
ClientSimple.listUser                        thrpt          8.409          ops/ms
ClientSimple.createUser                       avgt          2.142           ms/op
ClientSimple.existUser                        avgt          2.212           ms/op
ClientSimple.getUser                          avgt          1.696           ms/op
ClientSimple.listUser                         avgt          3.599           ms/op
ClientSimple.createUser                     sample  15593   2.063 ± 0.033   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.809           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.855           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.367           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.662           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.324           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.974           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.431           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.450           ms/op
ClientSimple.existUser                      sample  16664   1.918 ± 0.020   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.475           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.761           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.662           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.966           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.143           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.900           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.937           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.959           ms/op
ClientSimple.getUser                        sample  16722   1.928 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.713           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.806           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.388           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.572           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.669           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.674           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.899           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.976           ms/op
ClientSimple.listUser                       sample  10096   3.165 ± 0.028   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.288           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.978           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.965           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.243           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.865           ms/op
ClientSimple.listUser:listUser·p0.999       sample          9.617           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.699           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.699           ms/op

Benchmark result is saved to 1725495451829.json
