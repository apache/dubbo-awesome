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
# Warmup Iteration   1: 1.665 ops/ms
Iteration   1: 6.311 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.311 ops/ms


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
# Warmup Iteration   1: 5.755 ops/ms
Iteration   1: 12.324 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.324 ops/ms


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
# Warmup Iteration   1: 5.125 ops/ms
Iteration   1: 13.236 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.236 ops/ms


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
# Warmup Iteration   1: 4.091 ops/ms
Iteration   1: 8.308 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.308 ops/ms


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
# Warmup Iteration   1: 4.363 ±(99.9%) 0.078 ms/op
Iteration   1: 2.154 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.154 ms/op


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
# Warmup Iteration   1: 3.461 ±(99.9%) 0.054 ms/op
Iteration   1: 2.006 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.006 ms/op


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
# Warmup Iteration   1: 3.418 ±(99.9%) 0.067 ms/op
Iteration   1: 1.931 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.931 ms/op


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
# Warmup Iteration   1: 4.843 ±(99.9%) 0.093 ms/op
Iteration   1: 3.487 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.487 ms/op


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
# Warmup Iteration   1: 3.670 ±(99.9%) 0.103 ms/op
Iteration   1: 2.378 ±(99.9%) 0.046 ms/op
                 createUser·p0.00:   0.658 ms/op
                 createUser·p0.50:   2.058 ms/op
                 createUser·p0.90:   2.851 ms/op
                 createUser·p0.95:   3.305 ms/op
                 createUser·p0.99:   10.600 ms/op
                 createUser·p0.999:  19.014 ms/op
                 createUser·p0.9999: 20.349 ms/op
                 createUser·p1.00:   20.349 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13441
  mean =      2.378 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10532 
    [ 2.500,  5.000) = 2469 
    [ 5.000,  7.500) = 100 
    [ 7.500, 10.000) = 158 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.658 ms/op
     p(50.0000) =      2.058 ms/op
     p(90.0000) =      2.851 ms/op
     p(95.0000) =      3.305 ms/op
     p(99.0000) =     10.600 ms/op
     p(99.9000) =     19.014 ms/op
     p(99.9900) =     20.349 ms/op
     p(99.9990) =     20.349 ms/op
     p(99.9999) =     20.349 ms/op
    p(100.0000) =     20.349 ms/op


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
# Warmup Iteration   1: 2.964 ±(99.9%) 0.069 ms/op
Iteration   1: 1.885 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.452 ms/op
                 existUser·p0.50:   1.710 ms/op
                 existUser·p0.90:   2.261 ms/op
                 existUser·p0.95:   2.452 ms/op
                 existUser·p0.99:   4.938 ms/op
                 existUser·p0.999:  18.057 ms/op
                 existUser·p0.9999: 18.262 ms/op
                 existUser·p1.00:   18.285 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16945
  mean =      1.885 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 192 
    [ 1.250,  2.500) = 16012 
    [ 2.500,  3.750) = 526 
    [ 3.750,  5.000) = 46 
    [ 5.000,  6.250) = 72 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 18 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.452 ms/op
     p(50.0000) =      1.710 ms/op
     p(90.0000) =      2.261 ms/op
     p(95.0000) =      2.452 ms/op
     p(99.0000) =      4.938 ms/op
     p(99.9000) =     18.057 ms/op
     p(99.9900) =     18.262 ms/op
     p(99.9990) =     18.285 ms/op
     p(99.9999) =     18.285 ms/op
    p(100.0000) =     18.285 ms/op


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
# Warmup Iteration   1: 3.312 ±(99.9%) 0.080 ms/op
Iteration   1: 2.084 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.449 ms/op
                 getUser·p0.50:   1.997 ms/op
                 getUser·p0.90:   2.617 ms/op
                 getUser·p0.95:   2.769 ms/op
                 getUser·p0.99:   3.761 ms/op
                 getUser·p0.999:  5.683 ms/op
                 getUser·p0.9999: 9.093 ms/op
                 getUser·p1.00:   9.093 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15577
  mean =      2.084 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 49 
    [ 1.000,  2.000) = 7787 
    [ 2.000,  3.000) = 7385 
    [ 3.000,  4.000) = 208 
    [ 4.000,  5.000) = 80 
    [ 5.000,  6.000) = 65 
    [ 6.000,  7.000) = 0 
    [ 7.000,  8.000) = 0 
    [ 8.000,  9.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.449 ms/op
     p(50.0000) =      1.997 ms/op
     p(90.0000) =      2.617 ms/op
     p(95.0000) =      2.769 ms/op
     p(99.0000) =      3.761 ms/op
     p(99.9000) =      5.683 ms/op
     p(99.9900) =      9.093 ms/op
     p(99.9990) =      9.093 ms/op
     p(99.9999) =      9.093 ms/op
    p(100.0000) =      9.093 ms/op


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
# Warmup Iteration   1: 5.271 ±(99.9%) 0.152 ms/op
Iteration   1: 2.886 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.370 ms/op
                 listUser·p0.50:   2.691 ms/op
                 listUser·p0.90:   3.797 ms/op
                 listUser·p0.95:   4.035 ms/op
                 listUser·p0.99:   5.145 ms/op
                 listUser·p0.999:  15.286 ms/op
                 listUser·p0.9999: 15.335 ms/op
                 listUser·p1.00:   15.335 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 11072
  mean =      2.886 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 3018 
    [ 2.500,  3.750) = 6852 
    [ 3.750,  5.000) = 1079 
    [ 5.000,  6.250) = 83 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.370 ms/op
     p(50.0000) =      2.691 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      4.035 ms/op
     p(99.0000) =      5.145 ms/op
     p(99.9000) =     15.286 ms/op
     p(99.9900) =     15.335 ms/op
     p(99.9990) =     15.335 ms/op
     p(99.9999) =     15.335 ms/op
    p(100.0000) =     15.335 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.311          ops/ms
ClientSimple.existUser                       thrpt         12.324          ops/ms
ClientSimple.getUser                         thrpt         13.236          ops/ms
ClientSimple.listUser                        thrpt          8.308          ops/ms
ClientSimple.createUser                       avgt          2.154           ms/op
ClientSimple.existUser                        avgt          2.006           ms/op
ClientSimple.getUser                          avgt          1.931           ms/op
ClientSimple.listUser                         avgt          3.487           ms/op
ClientSimple.createUser                     sample  13441   2.378 ± 0.046   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.658           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.058           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.851           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.305           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.600           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.014           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.349           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.349           ms/op
ClientSimple.existUser                      sample  16945   1.885 ± 0.024   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.452           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.710           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.261           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.452           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.938           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.057           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.262           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.285           ms/op
ClientSimple.getUser                        sample  15577   2.084 ± 0.013   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.449           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.997           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.617           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.769           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.761           ms/op
ClientSimple.getUser:getUser·p0.999         sample          5.683           ms/op
ClientSimple.getUser:getUser·p0.9999        sample          9.093           ms/op
ClientSimple.getUser:getUser·p1.00          sample          9.093           ms/op
ClientSimple.listUser                       sample  11072   2.886 ± 0.028   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.370           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.691           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.797           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.035           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.145           ms/op
ClientSimple.listUser:listUser·p0.999       sample         15.286           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.335           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.335           ms/op

Benchmark result is saved to 1715148289515.json
