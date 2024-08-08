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
# Warmup Iteration   1: 1.777 ops/ms
Iteration   1: 6.880 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.880 ops/ms


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
# Warmup Iteration   1: 6.401 ops/ms
Iteration   1: 13.059 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.059 ops/ms


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
# Warmup Iteration   1: 6.232 ops/ms
Iteration   1: 13.906 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.906 ops/ms


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
# Warmup Iteration   1: 5.506 ops/ms
Iteration   1: 8.861 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.861 ops/ms


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
# Warmup Iteration   1: 3.670 ±(99.9%) 0.056 ms/op
Iteration   1: 2.139 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.139 ms/op


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
# Warmup Iteration   1: 3.270 ±(99.9%) 0.050 ms/op
Iteration   1: 1.837 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.837 ms/op


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
# Warmup Iteration   1: 3.605 ±(99.9%) 0.059 ms/op
Iteration   1: 2.097 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.097 ms/op


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
# Warmup Iteration   1: 4.383 ±(99.9%) 0.100 ms/op
Iteration   1: 3.151 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.151 ms/op


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
# Warmup Iteration   1: 3.467 ±(99.9%) 0.079 ms/op
Iteration   1: 2.056 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   0.448 ms/op
                 createUser·p0.50:   1.960 ms/op
                 createUser·p0.90:   2.568 ms/op
                 createUser·p0.95:   2.830 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  15.930 ms/op
                 createUser·p0.9999: 16.246 ms/op
                 createUser·p1.00:   16.417 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15786
  mean =      2.056 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 189 
    [ 1.250,  2.500) = 13722 
    [ 2.500,  3.750) = 1648 
    [ 3.750,  5.000) = 129 
    [ 5.000,  6.250) = 31 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.448 ms/op
     p(50.0000) =      1.960 ms/op
     p(90.0000) =      2.568 ms/op
     p(95.0000) =      2.830 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =     15.930 ms/op
     p(99.9900) =     16.246 ms/op
     p(99.9990) =     16.417 ms/op
     p(99.9999) =     16.417 ms/op
    p(100.0000) =     16.417 ms/op


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
# Warmup Iteration   1: 3.100 ±(99.9%) 0.091 ms/op
Iteration   1: 1.661 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.511 ms/op
                 existUser·p0.50:   1.540 ms/op
                 existUser·p0.90:   2.052 ms/op
                 existUser·p0.95:   2.310 ms/op
                 existUser·p0.99:   3.150 ms/op
                 existUser·p0.999:  15.378 ms/op
                 existUser·p0.9999: 15.532 ms/op
                 existUser·p1.00:   15.532 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 19414
  mean =      1.661 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 858 
    [ 1.250,  2.500) = 18032 
    [ 2.500,  3.750) = 424 
    [ 3.750,  5.000) = 17 
    [ 5.000,  6.250) = 16 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.511 ms/op
     p(50.0000) =      1.540 ms/op
     p(90.0000) =      2.052 ms/op
     p(95.0000) =      2.310 ms/op
     p(99.0000) =      3.150 ms/op
     p(99.9000) =     15.378 ms/op
     p(99.9900) =     15.532 ms/op
     p(99.9990) =     15.532 ms/op
     p(99.9999) =     15.532 ms/op
    p(100.0000) =     15.532 ms/op


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
# Warmup Iteration   1: 3.138 ±(99.9%) 0.080 ms/op
Iteration   1: 2.114 ±(99.9%) 0.035 ms/op
                 getUser·p0.00:   0.716 ms/op
                 getUser·p0.50:   1.952 ms/op
                 getUser·p0.90:   2.486 ms/op
                 getUser·p0.95:   2.634 ms/op
                 getUser·p0.99:   5.255 ms/op
                 getUser·p0.999:  25.756 ms/op
                 getUser·p0.9999: 28.172 ms/op
                 getUser·p1.00:   28.312 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15322
  mean =      2.114 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13884 
    [ 2.500,  5.000) = 1252 
    [ 5.000,  7.500) = 108 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 11 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.716 ms/op
     p(50.0000) =      1.952 ms/op
     p(90.0000) =      2.486 ms/op
     p(95.0000) =      2.634 ms/op
     p(99.0000) =      5.255 ms/op
     p(99.9000) =     25.756 ms/op
     p(99.9900) =     28.172 ms/op
     p(99.9990) =     28.312 ms/op
     p(99.9999) =     28.312 ms/op
    p(100.0000) =     28.312 ms/op


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
# Warmup Iteration   1: 4.679 ±(99.9%) 0.138 ms/op
Iteration   1: 3.376 ±(99.9%) 0.038 ms/op
                 listUser·p0.00:   0.961 ms/op
                 listUser·p0.50:   3.031 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.825 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  13.870 ms/op
                 listUser·p0.9999: 16.941 ms/op
                 listUser·p1.00:   16.941 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9471
  mean =      3.376 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 929 
    [ 2.500,  3.750) = 5716 
    [ 3.750,  5.000) = 2427 
    [ 5.000,  6.250) = 208 
    [ 6.250,  7.500) = 109 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.961 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.825 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     13.870 ms/op
     p(99.9900) =     16.941 ms/op
     p(99.9990) =     16.941 ms/op
     p(99.9999) =     16.941 ms/op
    p(100.0000) =     16.941 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.880          ops/ms
ClientSimple.existUser                       thrpt         13.059          ops/ms
ClientSimple.getUser                         thrpt         13.906          ops/ms
ClientSimple.listUser                        thrpt          8.861          ops/ms
ClientSimple.createUser                       avgt          2.139           ms/op
ClientSimple.existUser                        avgt          1.837           ms/op
ClientSimple.getUser                          avgt          2.097           ms/op
ClientSimple.listUser                         avgt          3.151           ms/op
ClientSimple.createUser                     sample  15786   2.056 ± 0.022   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.448           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.960           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.568           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.830           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.456           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.930           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.246           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.417           ms/op
ClientSimple.existUser                      sample  19414   1.661 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.511           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.540           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.052           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.310           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.150           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.378           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.532           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.532           ms/op
ClientSimple.getUser                        sample  15322   2.114 ± 0.035   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.716           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.952           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.486           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.634           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.255           ms/op
ClientSimple.getUser:getUser·p0.999         sample         25.756           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         28.172           ms/op
ClientSimple.getUser:getUser·p1.00          sample         28.312           ms/op
ClientSimple.listUser                       sample   9471   3.376 ± 0.038   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.961           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.031           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.350           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.825           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.053           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.870           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.941           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.941           ms/op

Benchmark result is saved to 1723097169155.json
