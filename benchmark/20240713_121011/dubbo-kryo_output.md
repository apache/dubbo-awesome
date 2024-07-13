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
# Warmup Iteration   1: 1.795 ops/ms
Iteration   1: 8.129 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  8.129 ops/ms


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
# Warmup Iteration   1: 5.645 ops/ms
Iteration   1: 12.012 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.012 ops/ms


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
# Warmup Iteration   1: 5.826 ops/ms
Iteration   1: 14.993 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.993 ops/ms


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
# Warmup Iteration   1: 4.834 ops/ms
Iteration   1: 9.070 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.070 ops/ms


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
# Warmup Iteration   1: 4.014 ±(99.9%) 0.073 ms/op
Iteration   1: 2.143 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.143 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.885 ±(99.9%) 0.047 ms/op
Iteration   1: 1.676 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.676 ms/op


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
# Warmup Iteration   1: 3.373 ±(99.9%) 0.066 ms/op
Iteration   1: 2.079 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.079 ms/op


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
# Warmup Iteration   1: 4.712 ±(99.9%) 0.118 ms/op
Iteration   1: 3.425 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.425 ms/op


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
# Warmup Iteration   1: 3.513 ±(99.9%) 0.094 ms/op
Iteration   1: 2.046 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   0.520 ms/op
                 createUser·p0.50:   1.933 ms/op
                 createUser·p0.90:   2.384 ms/op
                 createUser·p0.95:   2.564 ms/op
                 createUser·p0.99:   6.137 ms/op
                 createUser·p0.999:  12.687 ms/op
                 createUser·p0.9999: 13.353 ms/op
                 createUser·p1.00:   13.353 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15619
  mean =      2.046 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 333 
    [ 1.250,  2.500) = 14292 
    [ 2.500,  3.750) = 656 
    [ 3.750,  5.000) = 116 
    [ 5.000,  6.250) = 74 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 41 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.520 ms/op
     p(50.0000) =      1.933 ms/op
     p(90.0000) =      2.384 ms/op
     p(95.0000) =      2.564 ms/op
     p(99.0000) =      6.137 ms/op
     p(99.9000) =     12.687 ms/op
     p(99.9900) =     13.353 ms/op
     p(99.9990) =     13.353 ms/op
     p(99.9999) =     13.353 ms/op
    p(100.0000) =     13.353 ms/op


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
# Warmup Iteration   1: 2.703 ±(99.9%) 0.061 ms/op
Iteration   1: 1.925 ±(99.9%) 0.033 ms/op
                 existUser·p0.00:   0.613 ms/op
                 existUser·p0.50:   1.800 ms/op
                 existUser·p0.90:   2.396 ms/op
                 existUser·p0.95:   2.585 ms/op
                 existUser·p0.99:   3.559 ms/op
                 existUser·p0.999:  27.013 ms/op
                 existUser·p0.9999: 27.591 ms/op
                 existUser·p1.00:   27.591 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16613
  mean =      1.925 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15450 
    [ 2.500,  5.000) = 1087 
    [ 5.000,  7.500) = 12 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 6 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.613 ms/op
     p(50.0000) =      1.800 ms/op
     p(90.0000) =      2.396 ms/op
     p(95.0000) =      2.585 ms/op
     p(99.0000) =      3.559 ms/op
     p(99.9000) =     27.013 ms/op
     p(99.9900) =     27.591 ms/op
     p(99.9990) =     27.591 ms/op
     p(99.9999) =     27.591 ms/op
    p(100.0000) =     27.591 ms/op


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
# Warmup Iteration   1: 3.213 ±(99.9%) 0.081 ms/op
Iteration   1: 2.128 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.641 ms/op
                 getUser·p0.50:   2.062 ms/op
                 getUser·p0.90:   2.716 ms/op
                 getUser·p0.95:   2.925 ms/op
                 getUser·p0.99:   3.383 ms/op
                 getUser·p0.999:  12.141 ms/op
                 getUser·p0.9999: 12.575 ms/op
                 getUser·p1.00:   12.599 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15042
  mean =      2.128 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 206 
    [ 1.250,  2.500) = 11825 
    [ 2.500,  3.750) = 2938 
    [ 3.750,  5.000) = 9 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.641 ms/op
     p(50.0000) =      2.062 ms/op
     p(90.0000) =      2.716 ms/op
     p(95.0000) =      2.925 ms/op
     p(99.0000) =      3.383 ms/op
     p(99.9000) =     12.141 ms/op
     p(99.9900) =     12.575 ms/op
     p(99.9990) =     12.599 ms/op
     p(99.9999) =     12.599 ms/op
    p(100.0000) =     12.599 ms/op


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
# Warmup Iteration   1: 4.656 ±(99.9%) 0.140 ms/op
Iteration   1: 3.283 ±(99.9%) 0.036 ms/op
                 listUser·p0.00:   0.970 ms/op
                 listUser·p0.50:   3.129 ms/op
                 listUser·p0.90:   4.162 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.510 ms/op
                 listUser·p0.999:  16.876 ms/op
                 listUser·p0.9999: 18.743 ms/op
                 listUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9738
  mean =      3.283 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 967 
    [ 2.500,  3.750) = 6559 
    [ 3.750,  5.000) = 2054 
    [ 5.000,  6.250) = 85 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.970 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      4.162 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      5.510 ms/op
     p(99.9000) =     16.876 ms/op
     p(99.9900) =     18.743 ms/op
     p(99.9990) =     18.743 ms/op
     p(99.9999) =     18.743 ms/op
    p(100.0000) =     18.743 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          8.129          ops/ms
ClientSimple.existUser                       thrpt         12.012          ops/ms
ClientSimple.getUser                         thrpt         14.993          ops/ms
ClientSimple.listUser                        thrpt          9.070          ops/ms
ClientSimple.createUser                       avgt          2.143           ms/op
ClientSimple.existUser                        avgt          1.676           ms/op
ClientSimple.getUser                          avgt          2.079           ms/op
ClientSimple.listUser                         avgt          3.425           ms/op
ClientSimple.createUser                     sample  15619   2.046 ± 0.023   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.520           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.933           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.384           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.564           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.137           ms/op
ClientSimple.createUser:createUser·p0.999   sample         12.687           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         13.353           ms/op
ClientSimple.createUser:createUser·p1.00    sample         13.353           ms/op
ClientSimple.existUser                      sample  16613   1.925 ± 0.033   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.613           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.800           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.396           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.585           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.559           ms/op
ClientSimple.existUser:existUser·p0.999     sample         27.013           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         27.591           ms/op
ClientSimple.existUser:existUser·p1.00      sample         27.591           ms/op
ClientSimple.getUser                        sample  15042   2.128 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.641           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.062           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.716           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.925           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.383           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.141           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.575           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.599           ms/op
ClientSimple.listUser                       sample   9738   3.283 ± 0.036   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.970           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.129           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.162           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.456           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.510           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.876           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.743           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.743           ms/op

Benchmark result is saved to 1720872359769.json
