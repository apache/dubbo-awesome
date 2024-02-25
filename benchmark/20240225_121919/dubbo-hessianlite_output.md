# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.955 ops/ms
Iteration   1: 5.173 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.173 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.555 ops/ms
Iteration   1: 11.583 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.583 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.872 ops/ms
Iteration   1: 8.942 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.942 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.925 ops/ms
Iteration   1: 3.090 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.090 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.535 ±(99.9%) 0.063 ms/op
Iteration   1: 3.116 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.116 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.370 ±(99.9%) 0.037 ms/op
Iteration   1: 1.911 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.911 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.852 ±(99.9%) 0.056 ms/op
Iteration   1: 2.976 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.976 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 11.098 ±(99.9%) 0.220 ms/op
Iteration   1: 8.079 ±(99.9%) 0.072 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.079 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.007 ±(99.9%) 0.130 ms/op
Iteration   1: 3.227 ±(99.9%) 0.069 ms/op
                 createUser·p0.00:   0.623 ms/op
                 createUser·p0.50:   2.822 ms/op
                 createUser·p0.90:   4.100 ms/op
                 createUser·p0.95:   4.571 ms/op
                 createUser·p0.99:   13.566 ms/op
                 createUser·p0.999:  31.057 ms/op
                 createUser·p0.9999: 31.785 ms/op
                 createUser·p1.00:   31.785 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9957
  mean =      3.227 ±(99.9%) 0.069 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2015 
    [ 2.500,  5.000) = 7564 
    [ 5.000,  7.500) = 175 
    [ 7.500, 10.000) = 75 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 91 
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
      p(0.0000) =      0.623 ms/op
     p(50.0000) =      2.822 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      4.571 ms/op
     p(99.0000) =     13.566 ms/op
     p(99.9000) =     31.057 ms/op
     p(99.9900) =     31.785 ms/op
     p(99.9990) =     31.785 ms/op
     p(99.9999) =     31.785 ms/op
    p(100.0000) =     31.785 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.253 ±(99.9%) 0.083 ms/op
Iteration   1: 1.829 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.979 ms/op
                 existUser·p0.50:   1.749 ms/op
                 existUser·p0.90:   2.310 ms/op
                 existUser·p0.95:   2.458 ms/op
                 existUser·p0.99:   3.173 ms/op
                 existUser·p0.999:  4.366 ms/op
                 existUser·p0.9999: 5.183 ms/op
                 existUser·p1.00:   5.521 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17507
  mean =      1.829 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 2 
    [1.000, 1.500) = 2587 
    [1.500, 2.000) = 10367 
    [2.000, 2.500) = 3813 
    [2.500, 3.000) = 506 
    [3.000, 3.500) = 147 
    [3.500, 4.000) = 32 
    [4.000, 4.500) = 43 
    [4.500, 5.000) = 8 
    [5.000, 5.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.979 ms/op
     p(50.0000) =      1.749 ms/op
     p(90.0000) =      2.310 ms/op
     p(95.0000) =      2.458 ms/op
     p(99.0000) =      3.173 ms/op
     p(99.9000) =      4.366 ms/op
     p(99.9900) =      5.183 ms/op
     p(99.9990) =      5.521 ms/op
     p(99.9999) =      5.521 ms/op
    p(100.0000) =      5.521 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.627 ±(99.9%) 0.110 ms/op
Iteration   1: 3.186 ±(99.9%) 0.037 ms/op
                 getUser·p0.00:   0.924 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.940 ms/op
                 getUser·p0.95:   4.250 ms/op
                 getUser·p0.99:   5.259 ms/op
                 getUser·p0.999:  19.562 ms/op
                 getUser·p0.9999: 20.119 ms/op
                 getUser·p1.00:   20.120 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10263
  mean =      3.186 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1663 
    [ 2.500,  5.000) = 8444 
    [ 5.000,  7.500) = 116 
    [ 7.500, 10.000) = 8 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.924 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.250 ms/op
     p(99.0000) =      5.259 ms/op
     p(99.9000) =     19.562 ms/op
     p(99.9900) =     20.119 ms/op
     p(99.9990) =     20.120 ms/op
     p(99.9999) =     20.120 ms/op
    p(100.0000) =     20.120 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.289 ±(99.9%) 0.466 ms/op
Iteration   1: 8.064 ±(99.9%) 0.118 ms/op
                 listUser·p0.00:   2.863 ms/op
                 listUser·p0.50:   7.741 ms/op
                 listUser·p0.90:   10.772 ms/op
                 listUser·p0.95:   11.993 ms/op
                 listUser·p0.99:   15.639 ms/op
                 listUser·p0.999:  20.331 ms/op
                 listUser·p0.9999: 21.627 ms/op
                 listUser·p1.00:   21.627 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3964
  mean =      8.064 ±(99.9%) 0.118 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 175 
    [ 5.000,  7.500) = 1609 
    [ 7.500, 10.000) = 1562 
    [10.000, 12.500) = 451 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.863 ms/op
     p(50.0000) =      7.741 ms/op
     p(90.0000) =     10.772 ms/op
     p(95.0000) =     11.993 ms/op
     p(99.0000) =     15.639 ms/op
     p(99.9000) =     20.331 ms/op
     p(99.9900) =     21.627 ms/op
     p(99.9990) =     21.627 ms/op
     p(99.9999) =     21.627 ms/op
    p(100.0000) =     21.627 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.173          ops/ms
Client.existUser                       thrpt         11.583          ops/ms
Client.getUser                         thrpt          8.942          ops/ms
Client.listUser                        thrpt          3.090          ops/ms
Client.createUser                       avgt          3.116           ms/op
Client.existUser                        avgt          1.911           ms/op
Client.getUser                          avgt          2.976           ms/op
Client.listUser                         avgt          8.079           ms/op
Client.createUser                     sample   9957   3.227 ± 0.069   ms/op
Client.createUser:createUser·p0.00    sample          0.623           ms/op
Client.createUser:createUser·p0.50    sample          2.822           ms/op
Client.createUser:createUser·p0.90    sample          4.100           ms/op
Client.createUser:createUser·p0.95    sample          4.571           ms/op
Client.createUser:createUser·p0.99    sample         13.566           ms/op
Client.createUser:createUser·p0.999   sample         31.057           ms/op
Client.createUser:createUser·p0.9999  sample         31.785           ms/op
Client.createUser:createUser·p1.00    sample         31.785           ms/op
Client.existUser                      sample  17507   1.829 ± 0.009   ms/op
Client.existUser:existUser·p0.00      sample          0.979           ms/op
Client.existUser:existUser·p0.50      sample          1.749           ms/op
Client.existUser:existUser·p0.90      sample          2.310           ms/op
Client.existUser:existUser·p0.95      sample          2.458           ms/op
Client.existUser:existUser·p0.99      sample          3.173           ms/op
Client.existUser:existUser·p0.999     sample          4.366           ms/op
Client.existUser:existUser·p0.9999    sample          5.183           ms/op
Client.existUser:existUser·p1.00      sample          5.521           ms/op
Client.getUser                        sample  10263   3.186 ± 0.037   ms/op
Client.getUser:getUser·p0.00          sample          0.924           ms/op
Client.getUser:getUser·p0.50          sample          3.129           ms/op
Client.getUser:getUser·p0.90          sample          3.940           ms/op
Client.getUser:getUser·p0.95          sample          4.250           ms/op
Client.getUser:getUser·p0.99          sample          5.259           ms/op
Client.getUser:getUser·p0.999         sample         19.562           ms/op
Client.getUser:getUser·p0.9999        sample         20.119           ms/op
Client.getUser:getUser·p1.00          sample         20.120           ms/op
Client.listUser                       sample   3964   8.064 ± 0.118   ms/op
Client.listUser:listUser·p0.00        sample          2.863           ms/op
Client.listUser:listUser·p0.50        sample          7.741           ms/op
Client.listUser:listUser·p0.90        sample         10.772           ms/op
Client.listUser:listUser·p0.95        sample         11.993           ms/op
Client.listUser:listUser·p0.99        sample         15.639           ms/op
Client.listUser:listUser·p0.999       sample         20.331           ms/op
Client.listUser:listUser·p0.9999      sample         21.627           ms/op
Client.listUser:listUser·p1.00        sample         21.627           ms/op
