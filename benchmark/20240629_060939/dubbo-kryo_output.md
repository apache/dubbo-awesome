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
# Warmup Iteration   1: 2.149 ops/ms
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

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.320 ops/ms
Iteration   1: 12.196 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.196 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 6.969 ops/ms
Iteration   1: 15.358 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  15.358 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.959 ops/ms
Iteration   1: 9.522 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.522 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.699 ±(99.9%) 0.064 ms/op
Iteration   1: 1.925 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.925 ms/op


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
# Warmup Iteration   1: 2.750 ±(99.9%) 0.038 ms/op
Iteration   1: 1.752 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.752 ms/op


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
# Warmup Iteration   1: 3.110 ±(99.9%) 0.046 ms/op
Iteration   1: 1.873 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.873 ms/op


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
# Warmup Iteration   1: 4.507 ±(99.9%) 0.108 ms/op
Iteration   1: 3.187 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.187 ms/op


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
# Warmup Iteration   1: 3.140 ±(99.9%) 0.074 ms/op
Iteration   1: 2.123 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   0.358 ms/op
                 createUser·p0.50:   2.036 ms/op
                 createUser·p0.90:   2.576 ms/op
                 createUser·p0.95:   2.757 ms/op
                 createUser·p0.99:   3.699 ms/op
                 createUser·p0.999:  26.080 ms/op
                 createUser·p0.9999: 27.262 ms/op
                 createUser·p1.00:   27.329 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15087
  mean =      2.123 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12900 
    [ 2.500,  5.000) = 2089 
    [ 5.000,  7.500) = 2 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.358 ms/op
     p(50.0000) =      2.036 ms/op
     p(90.0000) =      2.576 ms/op
     p(95.0000) =      2.757 ms/op
     p(99.0000) =      3.699 ms/op
     p(99.9000) =     26.080 ms/op
     p(99.9900) =     27.262 ms/op
     p(99.9990) =     27.329 ms/op
     p(99.9999) =     27.329 ms/op
    p(100.0000) =     27.329 ms/op


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
# Warmup Iteration   1: 3.068 ±(99.9%) 0.071 ms/op
Iteration   1: 1.653 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.657 ms/op
                 existUser·p0.50:   1.518 ms/op
                 existUser·p0.90:   2.118 ms/op
                 existUser·p0.95:   2.245 ms/op
                 existUser·p0.99:   3.236 ms/op
                 existUser·p0.999:  18.186 ms/op
                 existUser·p0.9999: 18.582 ms/op
                 existUser·p1.00:   18.645 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 19593
  mean =      1.653 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1190 
    [ 1.250,  2.500) = 18006 
    [ 2.500,  3.750) = 317 
    [ 3.750,  5.000) = 17 
    [ 5.000,  6.250) = 31 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.657 ms/op
     p(50.0000) =      1.518 ms/op
     p(90.0000) =      2.118 ms/op
     p(95.0000) =      2.245 ms/op
     p(99.0000) =      3.236 ms/op
     p(99.9000) =     18.186 ms/op
     p(99.9900) =     18.582 ms/op
     p(99.9990) =     18.645 ms/op
     p(99.9999) =     18.645 ms/op
    p(100.0000) =     18.645 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 3.207 ±(99.9%) 0.099 ms/op
Iteration   1: 2.147 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.706 ms/op
                 getUser·p0.50:   2.091 ms/op
                 getUser·p0.90:   2.646 ms/op
                 getUser·p0.95:   2.908 ms/op
                 getUser·p0.99:   4.481 ms/op
                 getUser·p0.999:  12.206 ms/op
                 getUser·p0.9999: 12.279 ms/op
                 getUser·p1.00:   12.304 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15097
  mean =      2.147 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 173 
    [ 1.250,  2.500) = 12561 
    [ 2.500,  3.750) = 2138 
    [ 3.750,  5.000) = 150 
    [ 5.000,  6.250) = 36 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.706 ms/op
     p(50.0000) =      2.091 ms/op
     p(90.0000) =      2.646 ms/op
     p(95.0000) =      2.908 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =     12.206 ms/op
     p(99.9900) =     12.279 ms/op
     p(99.9990) =     12.304 ms/op
     p(99.9999) =     12.304 ms/op
    p(100.0000) =     12.304 ms/op


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
# Warmup Iteration   1: 4.028 ±(99.9%) 0.108 ms/op
Iteration   1: 3.336 ±(99.9%) 0.048 ms/op
                 listUser·p0.00:   0.827 ms/op
                 listUser·p0.50:   3.334 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  25.311 ms/op
                 listUser·p0.9999: 25.756 ms/op
                 listUser·p1.00:   25.756 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9576
  mean =      3.336 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1458 
    [ 2.500,  5.000) = 7881 
    [ 5.000,  7.500) = 166 
    [ 7.500, 10.000) = 34 
    [10.000, 12.500) = 4 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.827 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      3.981 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      6.668 ms/op
     p(99.9000) =     25.311 ms/op
     p(99.9900) =     25.756 ms/op
     p(99.9990) =     25.756 ms/op
     p(99.9999) =     25.756 ms/op
    p(100.0000) =     25.756 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.470          ops/ms
ClientSimple.existUser                       thrpt         12.196          ops/ms
ClientSimple.getUser                         thrpt         15.358          ops/ms
ClientSimple.listUser                        thrpt          9.522          ops/ms
ClientSimple.createUser                       avgt          1.925           ms/op
ClientSimple.existUser                        avgt          1.752           ms/op
ClientSimple.getUser                          avgt          1.873           ms/op
ClientSimple.listUser                         avgt          3.187           ms/op
ClientSimple.createUser                     sample  15087   2.123 ± 0.040   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.358           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.036           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.576           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.757           ms/op
ClientSimple.createUser:createUser·p0.99    sample          3.699           ms/op
ClientSimple.createUser:createUser·p0.999   sample         26.080           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         27.262           ms/op
ClientSimple.createUser:createUser·p1.00    sample         27.329           ms/op
ClientSimple.existUser                      sample  19593   1.653 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.657           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.518           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.118           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.245           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.236           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.186           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.582           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.645           ms/op
ClientSimple.getUser                        sample  15097   2.147 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.706           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.091           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.646           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.908           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.481           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.206           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.279           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.304           ms/op
ClientSimple.listUser                       sample   9576   3.336 ± 0.048   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.827           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.334           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.981           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.284           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.668           ms/op
ClientSimple.listUser:listUser·p0.999       sample         25.311           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         25.756           ms/op
ClientSimple.listUser:listUser·p1.00        sample         25.756           ms/op

Benchmark result is saved to 1719641121057.json
