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
# Warmup Iteration   1: 1.344 ops/ms
Iteration   1: 6.628 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.628 ops/ms


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
# Warmup Iteration   1: 5.882 ops/ms
Iteration   1: 11.619 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.619 ops/ms


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
# Warmup Iteration   1: 5.606 ops/ms
Iteration   1: 13.378 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.378 ops/ms


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
# Warmup Iteration   1: 4.503 ops/ms
Iteration   1: 8.808 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.808 ops/ms


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
# Warmup Iteration   1: 3.986 ±(99.9%) 0.071 ms/op
Iteration   1: 1.944 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.944 ms/op


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
# Warmup Iteration   1: 3.161 ±(99.9%) 0.058 ms/op
Iteration   1: 1.814 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.814 ms/op


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
# Warmup Iteration   1: 3.361 ±(99.9%) 0.058 ms/op
Iteration   1: 1.798 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.798 ms/op


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
# Warmup Iteration   1: 4.186 ±(99.9%) 0.084 ms/op
Iteration   1: 3.926 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.926 ms/op


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
# Warmup Iteration   1: 3.395 ±(99.9%) 0.093 ms/op
Iteration   1: 2.152 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.523 ms/op
                 createUser·p0.50:   2.034 ms/op
                 createUser·p0.90:   2.765 ms/op
                 createUser·p0.95:   2.933 ms/op
                 createUser·p0.99:   4.313 ms/op
                 createUser·p0.999:  19.005 ms/op
                 createUser·p0.9999: 23.123 ms/op
                 createUser·p1.00:   23.298 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14856
  mean =      2.152 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11849 
    [ 2.500,  5.000) = 2869 
    [ 5.000,  7.500) = 69 
    [ 7.500, 10.000) = 35 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.523 ms/op
     p(50.0000) =      2.034 ms/op
     p(90.0000) =      2.765 ms/op
     p(95.0000) =      2.933 ms/op
     p(99.0000) =      4.313 ms/op
     p(99.9000) =     19.005 ms/op
     p(99.9900) =     23.123 ms/op
     p(99.9990) =     23.298 ms/op
     p(99.9999) =     23.298 ms/op
    p(100.0000) =     23.298 ms/op


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
# Warmup Iteration   1: 2.969 ±(99.9%) 0.079 ms/op
Iteration   1: 2.089 ±(99.9%) 0.095 ms/op
                 existUser·p0.00:   0.673 ms/op
                 existUser·p0.50:   1.774 ms/op
                 existUser·p0.90:   2.232 ms/op
                 existUser·p0.95:   2.527 ms/op
                 existUser·p0.99:   5.956 ms/op
                 existUser·p0.999:  82.051 ms/op
                 existUser·p0.9999: 86.760 ms/op
                 existUser·p1.00:   87.949 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15337
  mean =      2.089 ±(99.9%) 0.095 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 15137 
    [ 5.000, 10.000) = 89 
    [10.000, 15.000) = 69 
    [15.000, 20.000) = 3 
    [20.000, 25.000) = 2 
    [25.000, 30.000) = 2 
    [30.000, 35.000) = 3 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 1 
    [50.000, 55.000) = 1 
    [55.000, 60.000) = 3 
    [60.000, 65.000) = 2 
    [65.000, 70.000) = 3 
    [70.000, 75.000) = 0 
    [75.000, 80.000) = 2 
    [80.000, 85.000) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.673 ms/op
     p(50.0000) =      1.774 ms/op
     p(90.0000) =      2.232 ms/op
     p(95.0000) =      2.527 ms/op
     p(99.0000) =      5.956 ms/op
     p(99.9000) =     82.051 ms/op
     p(99.9900) =     86.760 ms/op
     p(99.9990) =     87.949 ms/op
     p(99.9999) =     87.949 ms/op
    p(100.0000) =     87.949 ms/op


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
# Warmup Iteration   1: 3.221 ±(99.9%) 0.084 ms/op
Iteration   1: 2.312 ±(99.9%) 0.031 ms/op
                 getUser·p0.00:   0.467 ms/op
                 getUser·p0.50:   2.261 ms/op
                 getUser·p0.90:   2.900 ms/op
                 getUser·p0.95:   3.056 ms/op
                 getUser·p0.99:   3.839 ms/op
                 getUser·p0.999:  22.750 ms/op
                 getUser·p0.9999: 23.613 ms/op
                 getUser·p1.00:   23.626 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13866
  mean =      2.312 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9441 
    [ 2.500,  5.000) = 4352 
    [ 5.000,  7.500) = 39 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.467 ms/op
     p(50.0000) =      2.261 ms/op
     p(90.0000) =      2.900 ms/op
     p(95.0000) =      3.056 ms/op
     p(99.0000) =      3.839 ms/op
     p(99.9000) =     22.750 ms/op
     p(99.9900) =     23.613 ms/op
     p(99.9990) =     23.626 ms/op
     p(99.9999) =     23.626 ms/op
    p(100.0000) =     23.626 ms/op


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
# Warmup Iteration   1: 4.228 ±(99.9%) 0.140 ms/op
Iteration   1: 3.186 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   0.914 ms/op
                 listUser·p0.50:   3.232 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.162 ms/op
                 listUser·p0.99:   5.022 ms/op
                 listUser·p0.999:  9.502 ms/op
                 listUser·p0.9999: 9.568 ms/op
                 listUser·p1.00:   9.568 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10057
  mean =      3.186 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 2 
    [ 1.000,  2.000) = 159 
    [ 2.000,  3.000) = 3764 
    [ 3.000,  4.000) = 5343 
    [ 4.000,  5.000) = 681 
    [ 5.000,  6.000) = 71 
    [ 6.000,  7.000) = 5 
    [ 7.000,  8.000) = 0 
    [ 8.000,  9.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.914 ms/op
     p(50.0000) =      3.232 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.162 ms/op
     p(99.0000) =      5.022 ms/op
     p(99.9000) =      9.502 ms/op
     p(99.9900) =      9.568 ms/op
     p(99.9990) =      9.568 ms/op
     p(99.9999) =      9.568 ms/op
    p(100.0000) =      9.568 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.628          ops/ms
ClientSimple.existUser                       thrpt         11.619          ops/ms
ClientSimple.getUser                         thrpt         13.378          ops/ms
ClientSimple.listUser                        thrpt          8.808          ops/ms
ClientSimple.createUser                       avgt          1.944           ms/op
ClientSimple.existUser                        avgt          1.814           ms/op
ClientSimple.getUser                          avgt          1.798           ms/op
ClientSimple.listUser                         avgt          3.926           ms/op
ClientSimple.createUser                     sample  14856   2.152 ± 0.027   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.523           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.034           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.765           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.933           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.313           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.005           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.123           ms/op
ClientSimple.createUser:createUser·p1.00    sample         23.298           ms/op
ClientSimple.existUser                      sample  15337   2.089 ± 0.095   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.673           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.774           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.232           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.527           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.956           ms/op
ClientSimple.existUser:existUser·p0.999     sample         82.051           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         86.760           ms/op
ClientSimple.existUser:existUser·p1.00      sample         87.949           ms/op
ClientSimple.getUser                        sample  13866   2.312 ± 0.031   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.467           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.261           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.900           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.056           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.839           ms/op
ClientSimple.getUser:getUser·p0.999         sample         22.750           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         23.613           ms/op
ClientSimple.getUser:getUser·p1.00          sample         23.626           ms/op
ClientSimple.listUser                       sample  10057   3.186 ± 0.024   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.914           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.232           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.908           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.162           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.022           ms/op
ClientSimple.listUser:listUser·p0.999       sample          9.502           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.568           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.568           ms/op

Benchmark result is saved to 1714133211800.json
