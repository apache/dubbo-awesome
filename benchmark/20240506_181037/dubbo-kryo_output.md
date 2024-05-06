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
# Warmup Iteration   1: 1.783 ops/ms
Iteration   1: 7.058 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.058 ops/ms


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
# Warmup Iteration   1: 6.281 ops/ms
Iteration   1: 12.033 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.033 ops/ms


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
# Warmup Iteration   1: 5.484 ops/ms
Iteration   1: 12.747 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.747 ops/ms


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
# Warmup Iteration   1: 5.303 ops/ms
Iteration   1: 7.965 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.965 ops/ms


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
# Warmup Iteration   1: 3.722 ±(99.9%) 0.071 ms/op
Iteration   1: 2.059 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.059 ms/op


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
# Warmup Iteration   1: 3.690 ±(99.9%) 0.062 ms/op
Iteration   1: 1.934 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.934 ms/op


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
# Warmup Iteration   1: 3.169 ±(99.9%) 0.050 ms/op
Iteration   1: 2.067 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.067 ms/op


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
# Warmup Iteration   1: 4.493 ±(99.9%) 0.088 ms/op
Iteration   1: 3.504 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.504 ms/op


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
# Warmup Iteration   1: 3.847 ±(99.9%) 0.100 ms/op
Iteration   1: 2.217 ±(99.9%) 0.042 ms/op
                 createUser·p0.00:   1.090 ms/op
                 createUser·p0.50:   1.985 ms/op
                 createUser·p0.90:   2.560 ms/op
                 createUser·p0.95:   2.805 ms/op
                 createUser·p0.99:   5.743 ms/op
                 createUser·p0.999:  25.919 ms/op
                 createUser·p0.9999: 26.885 ms/op
                 createUser·p1.00:   27.001 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14403
  mean =      2.217 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12585 
    [ 2.500,  5.000) = 1648 
    [ 5.000,  7.500) = 33 
    [ 7.500, 10.000) = 38 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.090 ms/op
     p(50.0000) =      1.985 ms/op
     p(90.0000) =      2.560 ms/op
     p(95.0000) =      2.805 ms/op
     p(99.0000) =      5.743 ms/op
     p(99.9000) =     25.919 ms/op
     p(99.9900) =     26.885 ms/op
     p(99.9990) =     27.001 ms/op
     p(99.9999) =     27.001 ms/op
    p(100.0000) =     27.001 ms/op


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
# Warmup Iteration   1: 3.113 ±(99.9%) 0.081 ms/op
Iteration   1: 1.816 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.669 ms/op
                 existUser·p0.50:   1.745 ms/op
                 existUser·p0.90:   2.245 ms/op
                 existUser·p0.95:   2.490 ms/op
                 existUser·p0.99:   3.556 ms/op
                 existUser·p0.999:  11.338 ms/op
                 existUser·p0.9999: 11.492 ms/op
                 existUser·p1.00:   11.567 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17597
  mean =      1.816 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 873 
    [ 1.250,  2.500) = 15871 
    [ 2.500,  3.750) = 690 
    [ 3.750,  5.000) = 69 
    [ 5.000,  6.250) = 39 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.669 ms/op
     p(50.0000) =      1.745 ms/op
     p(90.0000) =      2.245 ms/op
     p(95.0000) =      2.490 ms/op
     p(99.0000) =      3.556 ms/op
     p(99.9000) =     11.338 ms/op
     p(99.9900) =     11.492 ms/op
     p(99.9990) =     11.567 ms/op
     p(99.9999) =     11.567 ms/op
    p(100.0000) =     11.567 ms/op


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
# Warmup Iteration   1: 3.338 ±(99.9%) 0.108 ms/op
Iteration   1: 2.144 ±(99.9%) 0.041 ms/op
                 getUser·p0.00:   0.443 ms/op
                 getUser·p0.50:   2.032 ms/op
                 getUser·p0.90:   2.695 ms/op
                 getUser·p0.95:   2.978 ms/op
                 getUser·p0.99:   4.964 ms/op
                 getUser·p0.999:  28.476 ms/op
                 getUser·p0.9999: 28.688 ms/op
                 getUser·p1.00:   28.738 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14990
  mean =      2.144 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12362 
    [ 2.500,  5.000) = 2485 
    [ 5.000,  7.500) = 47 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.443 ms/op
     p(50.0000) =      2.032 ms/op
     p(90.0000) =      2.695 ms/op
     p(95.0000) =      2.978 ms/op
     p(99.0000) =      4.964 ms/op
     p(99.9000) =     28.476 ms/op
     p(99.9900) =     28.688 ms/op
     p(99.9990) =     28.738 ms/op
     p(99.9999) =     28.738 ms/op
    p(100.0000) =     28.738 ms/op


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
# Warmup Iteration   1: 4.376 ±(99.9%) 0.116 ms/op
Iteration   1: 3.729 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   0.716 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   6.701 ms/op
                 listUser·p0.999:  12.531 ms/op
                 listUser·p0.9999: 12.648 ms/op
                 listUser·p1.00:   12.648 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8595
  mean =      3.729 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 11 
    [ 1.250,  2.500) = 318 
    [ 2.500,  3.750) = 4099 
    [ 3.750,  5.000) = 3947 
    [ 5.000,  6.250) = 109 
    [ 6.250,  7.500) = 69 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.716 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.637 ms/op
     p(99.0000) =      6.701 ms/op
     p(99.9000) =     12.531 ms/op
     p(99.9900) =     12.648 ms/op
     p(99.9990) =     12.648 ms/op
     p(99.9999) =     12.648 ms/op
    p(100.0000) =     12.648 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.058          ops/ms
ClientSimple.existUser                       thrpt         12.033          ops/ms
ClientSimple.getUser                         thrpt         12.747          ops/ms
ClientSimple.listUser                        thrpt          7.965          ops/ms
ClientSimple.createUser                       avgt          2.059           ms/op
ClientSimple.existUser                        avgt          1.934           ms/op
ClientSimple.getUser                          avgt          2.067           ms/op
ClientSimple.listUser                         avgt          3.504           ms/op
ClientSimple.createUser                     sample  14403   2.217 ± 0.042   ms/op
ClientSimple.createUser:createUser·p0.00    sample          1.090           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.985           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.560           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.805           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.743           ms/op
ClientSimple.createUser:createUser·p0.999   sample         25.919           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         26.885           ms/op
ClientSimple.createUser:createUser·p1.00    sample         27.001           ms/op
ClientSimple.existUser                      sample  17597   1.816 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.669           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.745           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.245           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.490           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.556           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.338           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.492           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.567           ms/op
ClientSimple.getUser                        sample  14990   2.144 ± 0.041   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.443           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.032           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.695           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.978           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.964           ms/op
ClientSimple.getUser:getUser·p0.999         sample         28.476           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         28.688           ms/op
ClientSimple.getUser:getUser·p1.00          sample         28.738           ms/op
ClientSimple.listUser                       sample   8595   3.729 ± 0.030   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.716           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.731           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.399           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.637           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.701           ms/op
ClientSimple.listUser:listUser·p0.999       sample         12.531           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         12.648           ms/op
ClientSimple.listUser:listUser·p1.00        sample         12.648           ms/op

Benchmark result is saved to 1715018757210.json
