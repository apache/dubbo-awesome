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
# Warmup Iteration   1: 1.604 ops/ms
Iteration   1: 7.470 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.470 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.354 ops/ms
Iteration   1: 11.114 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.114 ops/ms


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
# Warmup Iteration   1: 6.075 ops/ms
Iteration   1: 14.598 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.598 ops/ms


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
# Warmup Iteration   1: 5.288 ops/ms
Iteration   1: 8.858 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.858 ops/ms


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
# Warmup Iteration   1: 3.909 ±(99.9%) 0.077 ms/op
Iteration   1: 2.391 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.391 ms/op


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
# Warmup Iteration   1: 3.818 ±(99.9%) 0.075 ms/op
Iteration   1: 2.095 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.095 ms/op


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
# Warmup Iteration   1: 3.608 ±(99.9%) 0.071 ms/op
Iteration   1: 2.195 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.195 ms/op


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
# Warmup Iteration   1: 4.710 ±(99.9%) 0.107 ms/op
Iteration   1: 3.368 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.368 ms/op


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
# Warmup Iteration   1: 3.401 ±(99.9%) 0.080 ms/op
Iteration   1: 1.958 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.628 ms/op
                 createUser·p0.50:   1.772 ms/op
                 createUser·p0.90:   2.494 ms/op
                 createUser·p0.95:   2.990 ms/op
                 createUser·p0.99:   3.935 ms/op
                 createUser·p0.999:  23.582 ms/op
                 createUser·p0.9999: 25.816 ms/op
                 createUser·p1.00:   26.542 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16329
  mean =      1.958 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14700 
    [ 2.500,  5.000) = 1517 
    [ 5.000,  7.500) = 31 
    [ 7.500, 10.000) = 17 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.628 ms/op
     p(50.0000) =      1.772 ms/op
     p(90.0000) =      2.494 ms/op
     p(95.0000) =      2.990 ms/op
     p(99.0000) =      3.935 ms/op
     p(99.9000) =     23.582 ms/op
     p(99.9900) =     25.816 ms/op
     p(99.9990) =     26.542 ms/op
     p(99.9999) =     26.542 ms/op
    p(100.0000) =     26.542 ms/op


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
# Warmup Iteration   1: 2.922 ±(99.9%) 0.068 ms/op
Iteration   1: 1.828 ±(99.9%) 0.035 ms/op
                 existUser·p0.00:   0.587 ms/op
                 existUser·p0.50:   1.708 ms/op
                 existUser·p0.90:   2.253 ms/op
                 existUser·p0.95:   2.458 ms/op
                 existUser·p0.99:   4.905 ms/op
                 existUser·p0.999:  27.639 ms/op
                 existUser·p0.9999: 28.680 ms/op
                 existUser·p1.00:   28.705 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17523
  mean =      1.828 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16733 
    [ 2.500,  5.000) = 630 
    [ 5.000,  7.500) = 64 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.587 ms/op
     p(50.0000) =      1.708 ms/op
     p(90.0000) =      2.253 ms/op
     p(95.0000) =      2.458 ms/op
     p(99.0000) =      4.905 ms/op
     p(99.9000) =     27.639 ms/op
     p(99.9900) =     28.680 ms/op
     p(99.9990) =     28.705 ms/op
     p(99.9999) =     28.705 ms/op
    p(100.0000) =     28.705 ms/op


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
# Warmup Iteration   1: 3.270 ±(99.9%) 0.095 ms/op
Iteration   1: 2.192 ±(99.9%) 0.034 ms/op
                 getUser·p0.00:   0.440 ms/op
                 getUser·p0.50:   2.130 ms/op
                 getUser·p0.90:   2.613 ms/op
                 getUser·p0.95:   2.867 ms/op
                 getUser·p0.99:   3.850 ms/op
                 getUser·p0.999:  23.265 ms/op
                 getUser·p0.9999: 23.331 ms/op
                 getUser·p1.00:   23.331 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14582
  mean =      2.192 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12366 
    [ 2.500,  5.000) = 2116 
    [ 5.000,  7.500) = 36 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.440 ms/op
     p(50.0000) =      2.130 ms/op
     p(90.0000) =      2.613 ms/op
     p(95.0000) =      2.867 ms/op
     p(99.0000) =      3.850 ms/op
     p(99.9000) =     23.265 ms/op
     p(99.9900) =     23.331 ms/op
     p(99.9990) =     23.331 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


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
# Warmup Iteration   1: 4.628 ±(99.9%) 0.154 ms/op
Iteration   1: 3.152 ±(99.9%) 0.052 ms/op
                 listUser·p0.00:   1.051 ms/op
                 listUser·p0.50:   2.855 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.186 ms/op
                 listUser·p0.99:   5.226 ms/op
                 listUser·p0.999:  28.783 ms/op
                 listUser·p0.9999: 29.914 ms/op
                 listUser·p1.00:   29.917 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10150
  mean =      3.152 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 865 
    [ 2.500,  5.000) = 9159 
    [ 5.000,  7.500) = 61 
    [ 7.500, 10.000) = 29 
    [10.000, 12.500) = 4 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.051 ms/op
     p(50.0000) =      2.855 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.186 ms/op
     p(99.0000) =      5.226 ms/op
     p(99.9000) =     28.783 ms/op
     p(99.9900) =     29.914 ms/op
     p(99.9990) =     29.917 ms/op
     p(99.9999) =     29.917 ms/op
    p(100.0000) =     29.917 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.470          ops/ms
ClientSimple.existUser                       thrpt         11.114          ops/ms
ClientSimple.getUser                         thrpt         14.598          ops/ms
ClientSimple.listUser                        thrpt          8.858          ops/ms
ClientSimple.createUser                       avgt          2.391           ms/op
ClientSimple.existUser                        avgt          2.095           ms/op
ClientSimple.getUser                          avgt          2.195           ms/op
ClientSimple.listUser                         avgt          3.368           ms/op
ClientSimple.createUser                     sample  16329   1.958 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.628           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.772           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.494           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.990           ms/op
ClientSimple.createUser:createUser·p0.99    sample          3.935           ms/op
ClientSimple.createUser:createUser·p0.999   sample         23.582           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         25.816           ms/op
ClientSimple.createUser:createUser·p1.00    sample         26.542           ms/op
ClientSimple.existUser                      sample  17523   1.828 ± 0.035   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.587           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.708           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.253           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.458           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.905           ms/op
ClientSimple.existUser:existUser·p0.999     sample         27.639           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         28.680           ms/op
ClientSimple.existUser:existUser·p1.00      sample         28.705           ms/op
ClientSimple.getUser                        sample  14582   2.192 ± 0.034   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.440           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.130           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.613           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.867           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.850           ms/op
ClientSimple.getUser:getUser·p0.999         sample         23.265           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         23.331           ms/op
ClientSimple.getUser:getUser·p1.00          sample         23.331           ms/op
ClientSimple.listUser                       sample  10150   3.152 ± 0.052   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.051           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.855           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.912           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.186           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.226           ms/op
ClientSimple.listUser:listUser·p0.999       sample         28.783           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         29.914           ms/op
ClientSimple.listUser:listUser·p1.00        sample         29.917           ms/op

Benchmark result is saved to 1716876332380.json
