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
# Warmup Iteration   1: 2.073 ops/ms
Iteration   1: 7.859 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.859 ops/ms


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
# Warmup Iteration   1: 6.216 ops/ms
Iteration   1: 14.629 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.629 ops/ms


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
# Warmup Iteration   1: 6.390 ops/ms
Iteration   1: 13.349 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.349 ops/ms


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
# Warmup Iteration   1: 4.738 ops/ms
Iteration   1: 9.403 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.403 ops/ms


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
# Warmup Iteration   1: 3.778 ±(99.9%) 0.070 ms/op
Iteration   1: 2.160 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.160 ms/op


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
# Warmup Iteration   1: 2.736 ±(99.9%) 0.047 ms/op
Iteration   1: 1.803 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.803 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.131 ±(99.9%) 0.055 ms/op
Iteration   1: 1.928 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.928 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.848 ±(99.9%) 0.114 ms/op
Iteration   1: 3.343 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.343 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 4.046 ±(99.9%) 0.108 ms/op
Iteration   1: 2.168 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.403 ms/op
                 createUser·p0.50:   1.884 ms/op
                 createUser·p0.90:   2.825 ms/op
                 createUser·p0.95:   3.331 ms/op
                 createUser·p0.99:   7.940 ms/op
                 createUser·p0.999:  13.614 ms/op
                 createUser·p0.9999: 14.716 ms/op
                 createUser·p1.00:   15.090 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15073
  mean =      2.168 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 202 
    [ 1.250,  2.500) = 12368 
    [ 2.500,  3.750) = 1920 
    [ 3.750,  5.000) = 235 
    [ 5.000,  6.250) = 79 
    [ 6.250,  7.500) = 96 
    [ 7.500,  8.750) = 81 
    [ 8.750, 10.000) = 17 
    [10.000, 11.250) = 39 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.403 ms/op
     p(50.0000) =      1.884 ms/op
     p(90.0000) =      2.825 ms/op
     p(95.0000) =      3.331 ms/op
     p(99.0000) =      7.940 ms/op
     p(99.9000) =     13.614 ms/op
     p(99.9900) =     14.716 ms/op
     p(99.9990) =     15.090 ms/op
     p(99.9999) =     15.090 ms/op
    p(100.0000) =     15.090 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.959 ±(99.9%) 0.080 ms/op
Iteration   1: 1.998 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   0.510 ms/op
                 existUser·p0.50:   1.796 ms/op
                 existUser·p0.90:   2.519 ms/op
                 existUser·p0.95:   2.679 ms/op
                 existUser·p0.99:   3.916 ms/op
                 existUser·p0.999:  20.808 ms/op
                 existUser·p0.9999: 21.129 ms/op
                 existUser·p1.00:   21.168 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15979
  mean =      1.998 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14244 
    [ 2.500,  5.000) = 1607 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 64 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.510 ms/op
     p(50.0000) =      1.796 ms/op
     p(90.0000) =      2.519 ms/op
     p(95.0000) =      2.679 ms/op
     p(99.0000) =      3.916 ms/op
     p(99.9000) =     20.808 ms/op
     p(99.9900) =     21.129 ms/op
     p(99.9990) =     21.168 ms/op
     p(99.9999) =     21.168 ms/op
    p(100.0000) =     21.168 ms/op


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
# Warmup Iteration   1: 3.209 ±(99.9%) 0.077 ms/op
Iteration   1: 1.849 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.896 ms/op
                 getUser·p0.50:   1.696 ms/op
                 getUser·p0.90:   2.200 ms/op
                 getUser·p0.95:   2.646 ms/op
                 getUser·p0.99:   3.490 ms/op
                 getUser·p0.999:  15.347 ms/op
                 getUser·p0.9999: 15.492 ms/op
                 getUser·p1.00:   15.516 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17291
  mean =      1.849 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 95 
    [ 1.250,  2.500) = 16138 
    [ 2.500,  3.750) = 916 
    [ 3.750,  5.000) = 8 
    [ 5.000,  6.250) = 17 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.896 ms/op
     p(50.0000) =      1.696 ms/op
     p(90.0000) =      2.200 ms/op
     p(95.0000) =      2.646 ms/op
     p(99.0000) =      3.490 ms/op
     p(99.9000) =     15.347 ms/op
     p(99.9900) =     15.492 ms/op
     p(99.9990) =     15.516 ms/op
     p(99.9999) =     15.516 ms/op
    p(100.0000) =     15.516 ms/op


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
# Warmup Iteration   1: 4.553 ±(99.9%) 0.113 ms/op
Iteration   1: 3.006 ±(99.9%) 0.038 ms/op
                 listUser·p0.00:   1.112 ms/op
                 listUser·p0.50:   2.826 ms/op
                 listUser·p0.90:   3.781 ms/op
                 listUser·p0.95:   4.059 ms/op
                 listUser·p0.99:   5.891 ms/op
                 listUser·p0.999:  18.514 ms/op
                 listUser·p0.9999: 18.645 ms/op
                 listUser·p1.00:   18.645 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10684
  mean =      3.006 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 2739 
    [ 2.500,  3.750) = 6789 
    [ 3.750,  5.000) = 1003 
    [ 5.000,  6.250) = 49 
    [ 6.250,  7.500) = 35 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.112 ms/op
     p(50.0000) =      2.826 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      4.059 ms/op
     p(99.0000) =      5.891 ms/op
     p(99.9000) =     18.514 ms/op
     p(99.9900) =     18.645 ms/op
     p(99.9990) =     18.645 ms/op
     p(99.9999) =     18.645 ms/op
    p(100.0000) =     18.645 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.859          ops/ms
ClientSimple.existUser                       thrpt         14.629          ops/ms
ClientSimple.getUser                         thrpt         13.349          ops/ms
ClientSimple.listUser                        thrpt          9.403          ops/ms
ClientSimple.createUser                       avgt          2.160           ms/op
ClientSimple.existUser                        avgt          1.803           ms/op
ClientSimple.getUser                          avgt          1.928           ms/op
ClientSimple.listUser                         avgt          3.343           ms/op
ClientSimple.createUser                     sample  15073   2.168 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.403           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.884           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.825           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.331           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.940           ms/op
ClientSimple.createUser:createUser·p0.999   sample         13.614           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.716           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.090           ms/op
ClientSimple.existUser                      sample  15979   1.998 ± 0.031   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.510           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.796           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.519           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.679           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.916           ms/op
ClientSimple.existUser:existUser·p0.999     sample         20.808           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         21.129           ms/op
ClientSimple.existUser:existUser·p1.00      sample         21.168           ms/op
ClientSimple.getUser                        sample  17291   1.849 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.896           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.696           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.200           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.646           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.490           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.347           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.492           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.516           ms/op
ClientSimple.listUser                       sample  10684   3.006 ± 0.038   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.112           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.826           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.781           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.059           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.891           ms/op
ClientSimple.listUser:listUser·p0.999       sample         18.514           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.645           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.645           ms/op

Benchmark result is saved to 1717762090259.json
