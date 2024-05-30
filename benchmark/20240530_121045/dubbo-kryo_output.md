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
# Warmup Iteration   1: 1.724 ops/ms
Iteration   1: 7.063 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.063 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 4.918 ops/ms
Iteration   1: 12.791 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.791 ops/ms


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
# Warmup Iteration   1: 5.933 ops/ms
Iteration   1: 12.371 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.371 ops/ms


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
# Warmup Iteration   1: 4.034 ops/ms
Iteration   1: 8.169 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.169 ops/ms


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
# Warmup Iteration   1: 3.929 ±(99.9%) 0.070 ms/op
Iteration   1: 2.100 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.100 ms/op


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
# Warmup Iteration   1: 3.635 ±(99.9%) 0.058 ms/op
Iteration   1: 1.836 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.836 ms/op


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
# Warmup Iteration   1: 3.528 ±(99.9%) 0.064 ms/op
Iteration   1: 2.265 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.265 ms/op


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
# Warmup Iteration   1: 5.380 ±(99.9%) 0.123 ms/op
Iteration   1: 3.323 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.323 ms/op


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
# Warmup Iteration   1: 3.785 ±(99.9%) 0.108 ms/op
Iteration   1: 2.153 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.818 ms/op
                 createUser·p0.50:   1.972 ms/op
                 createUser·p0.90:   2.621 ms/op
                 createUser·p0.95:   2.830 ms/op
                 createUser·p0.99:   3.937 ms/op
                 createUser·p0.999:  14.057 ms/op
                 createUser·p0.9999: 15.213 ms/op
                 createUser·p1.00:   15.221 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14841
  mean =      2.153 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 12165 
    [ 2.500,  3.750) = 2474 
    [ 3.750,  5.000) = 40 
    [ 5.000,  6.250) = 23 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 37 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.818 ms/op
     p(50.0000) =      1.972 ms/op
     p(90.0000) =      2.621 ms/op
     p(95.0000) =      2.830 ms/op
     p(99.0000) =      3.937 ms/op
     p(99.9000) =     14.057 ms/op
     p(99.9900) =     15.213 ms/op
     p(99.9990) =     15.221 ms/op
     p(99.9999) =     15.221 ms/op
    p(100.0000) =     15.221 ms/op


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
# Warmup Iteration   1: 2.812 ±(99.9%) 0.067 ms/op
Iteration   1: 1.759 ±(99.9%) 0.033 ms/op
                 existUser·p0.00:   0.696 ms/op
                 existUser·p0.50:   1.638 ms/op
                 existUser·p0.90:   2.050 ms/op
                 existUser·p0.95:   2.228 ms/op
                 existUser·p0.99:   2.908 ms/op
                 existUser·p0.999:  30.769 ms/op
                 existUser·p0.9999: 31.004 ms/op
                 existUser·p1.00:   31.031 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18400
  mean =      1.759 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18013 
    [ 2.500,  5.000) = 323 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.696 ms/op
     p(50.0000) =      1.638 ms/op
     p(90.0000) =      2.050 ms/op
     p(95.0000) =      2.228 ms/op
     p(99.0000) =      2.908 ms/op
     p(99.9000) =     30.769 ms/op
     p(99.9900) =     31.004 ms/op
     p(99.9990) =     31.031 ms/op
     p(99.9999) =     31.031 ms/op
    p(100.0000) =     31.031 ms/op


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
# Warmup Iteration   1: 3.339 ±(99.9%) 0.108 ms/op
Iteration   1: 1.990 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.766 ms/op
                 getUser·p0.50:   1.835 ms/op
                 getUser·p0.90:   2.544 ms/op
                 getUser·p0.95:   2.757 ms/op
                 getUser·p0.99:   3.448 ms/op
                 getUser·p0.999:  10.839 ms/op
                 getUser·p0.9999: 11.125 ms/op
                 getUser·p1.00:   11.125 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16230
  mean =      1.990 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 107 
    [ 1.250,  2.500) = 14298 
    [ 2.500,  3.750) = 1703 
    [ 3.750,  5.000) = 39 
    [ 5.000,  6.250) = 40 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.766 ms/op
     p(50.0000) =      1.835 ms/op
     p(90.0000) =      2.544 ms/op
     p(95.0000) =      2.757 ms/op
     p(99.0000) =      3.448 ms/op
     p(99.9000) =     10.839 ms/op
     p(99.9900) =     11.125 ms/op
     p(99.9990) =     11.125 ms/op
     p(99.9999) =     11.125 ms/op
    p(100.0000) =     11.125 ms/op


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
# Warmup Iteration   1: 4.582 ±(99.9%) 0.139 ms/op
Iteration   1: 3.636 ±(99.9%) 0.043 ms/op
                 listUser·p0.00:   0.974 ms/op
                 listUser·p0.50:   3.482 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.169 ms/op
                 listUser·p0.99:   6.347 ms/op
                 listUser·p0.999:  17.826 ms/op
                 listUser·p0.9999: 17.859 ms/op
                 listUser·p1.00:   17.859 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8925
  mean =      3.636 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 492 
    [ 2.500,  3.750) = 5101 
    [ 3.750,  5.000) = 2681 
    [ 5.000,  6.250) = 537 
    [ 6.250,  7.500) = 64 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.974 ms/op
     p(50.0000) =      3.482 ms/op
     p(90.0000) =      4.809 ms/op
     p(95.0000) =      5.169 ms/op
     p(99.0000) =      6.347 ms/op
     p(99.9000) =     17.826 ms/op
     p(99.9900) =     17.859 ms/op
     p(99.9990) =     17.859 ms/op
     p(99.9999) =     17.859 ms/op
    p(100.0000) =     17.859 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.063          ops/ms
ClientSimple.existUser                       thrpt         12.791          ops/ms
ClientSimple.getUser                         thrpt         12.371          ops/ms
ClientSimple.listUser                        thrpt          8.169          ops/ms
ClientSimple.createUser                       avgt          2.100           ms/op
ClientSimple.existUser                        avgt          1.836           ms/op
ClientSimple.getUser                          avgt          2.265           ms/op
ClientSimple.listUser                         avgt          3.323           ms/op
ClientSimple.createUser                     sample  14841   2.153 ± 0.027   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.818           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.972           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.621           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.830           ms/op
ClientSimple.createUser:createUser·p0.99    sample          3.937           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.057           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.213           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.221           ms/op
ClientSimple.existUser                      sample  18400   1.759 ± 0.033   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.696           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.638           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.050           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.228           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.908           ms/op
ClientSimple.existUser:existUser·p0.999     sample         30.769           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         31.004           ms/op
ClientSimple.existUser:existUser·p1.00      sample         31.031           ms/op
ClientSimple.getUser                        sample  16230   1.990 ± 0.015   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.766           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.835           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.544           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.757           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.448           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.839           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.125           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.125           ms/op
ClientSimple.listUser                       sample   8925   3.636 ± 0.043   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.974           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.482           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.809           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.169           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.347           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.826           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.859           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.859           ms/op

Benchmark result is saved to 1717070780440.json
