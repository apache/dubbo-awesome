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
# Warmup Iteration   1: 1.800 ops/ms
Iteration   1: 7.545 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.545 ops/ms


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
# Warmup Iteration   1: 5.735 ops/ms
Iteration   1: 12.822 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.822 ops/ms


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
# Warmup Iteration   1: 5.506 ops/ms
Iteration   1: 12.978 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.978 ops/ms


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
# Warmup Iteration   1: 4.087 ops/ms
Iteration   1: 9.067 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.067 ops/ms


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
# Warmup Iteration   1: 4.566 ±(99.9%) 0.083 ms/op
Iteration   1: 1.983 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.983 ms/op


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
# Warmup Iteration   1: 3.147 ±(99.9%) 0.045 ms/op
Iteration   1: 1.723 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.723 ms/op


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
# Warmup Iteration   1: 3.487 ±(99.9%) 0.058 ms/op
Iteration   1: 2.282 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.282 ms/op


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
# Warmup Iteration   1: 5.166 ±(99.9%) 0.104 ms/op
Iteration   1: 3.649 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.649 ms/op


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
# Warmup Iteration   1: 3.634 ±(99.9%) 0.102 ms/op
Iteration   1: 2.102 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.830 ms/op
                 createUser·p0.50:   1.989 ms/op
                 createUser·p0.90:   2.601 ms/op
                 createUser·p0.95:   2.961 ms/op
                 createUser·p0.99:   5.448 ms/op
                 createUser·p0.999:  16.679 ms/op
                 createUser·p0.9999: 18.396 ms/op
                 createUser·p1.00:   18.448 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15324
  mean =      2.102 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 268 
    [ 1.250,  2.500) = 13208 
    [ 2.500,  3.750) = 1415 
    [ 3.750,  5.000) = 248 
    [ 5.000,  6.250) = 84 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 18 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.830 ms/op
     p(50.0000) =      1.989 ms/op
     p(90.0000) =      2.601 ms/op
     p(95.0000) =      2.961 ms/op
     p(99.0000) =      5.448 ms/op
     p(99.9000) =     16.679 ms/op
     p(99.9900) =     18.396 ms/op
     p(99.9990) =     18.448 ms/op
     p(99.9999) =     18.448 ms/op
    p(100.0000) =     18.448 ms/op


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
# Warmup Iteration   1: 3.035 ±(99.9%) 0.070 ms/op
Iteration   1: 2.168 ±(99.9%) 0.062 ms/op
                 existUser·p0.00:   0.365 ms/op
                 existUser·p0.50:   2.005 ms/op
                 existUser·p0.90:   2.609 ms/op
                 existUser·p0.95:   2.851 ms/op
                 existUser·p0.99:   5.030 ms/op
                 existUser·p0.999:  48.576 ms/op
                 existUser·p0.9999: 50.009 ms/op
                 existUser·p1.00:   50.135 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14788
  mean =      2.168 ±(99.9%) 0.062 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 14636 
    [ 5.000, 10.000) = 88 
    [10.000, 15.000) = 32 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 31 
    [50.000, 55.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.365 ms/op
     p(50.0000) =      2.005 ms/op
     p(90.0000) =      2.609 ms/op
     p(95.0000) =      2.851 ms/op
     p(99.0000) =      5.030 ms/op
     p(99.9000) =     48.576 ms/op
     p(99.9900) =     50.009 ms/op
     p(99.9990) =     50.135 ms/op
     p(99.9999) =     50.135 ms/op
    p(100.0000) =     50.135 ms/op


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
# Warmup Iteration   1: 3.165 ±(99.9%) 0.093 ms/op
Iteration   1: 2.144 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.466 ms/op
                 getUser·p0.50:   2.048 ms/op
                 getUser·p0.90:   2.687 ms/op
                 getUser·p0.95:   2.933 ms/op
                 getUser·p0.99:   4.743 ms/op
                 getUser·p0.999:  12.123 ms/op
                 getUser·p0.9999: 12.198 ms/op
                 getUser·p1.00:   12.206 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15083
  mean =      2.144 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 373 
    [ 1.250,  2.500) = 11882 
    [ 2.500,  3.750) = 2601 
    [ 3.750,  5.000) = 99 
    [ 5.000,  6.250) = 60 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.466 ms/op
     p(50.0000) =      2.048 ms/op
     p(90.0000) =      2.687 ms/op
     p(95.0000) =      2.933 ms/op
     p(99.0000) =      4.743 ms/op
     p(99.9000) =     12.123 ms/op
     p(99.9900) =     12.198 ms/op
     p(99.9990) =     12.206 ms/op
     p(99.9999) =     12.206 ms/op
    p(100.0000) =     12.206 ms/op


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
# Warmup Iteration   1: 4.621 ±(99.9%) 0.125 ms/op
Iteration   1: 3.273 ±(99.9%) 0.042 ms/op
                 listUser·p0.00:   1.245 ms/op
                 listUser·p0.50:   3.072 ms/op
                 listUser·p0.90:   4.096 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  18.514 ms/op
                 listUser·p0.9999: 19.759 ms/op
                 listUser·p1.00:   19.759 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9801
  mean =      3.273 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 1768 
    [ 2.500,  3.750) = 5797 
    [ 3.750,  5.000) = 1865 
    [ 5.000,  6.250) = 182 
    [ 6.250,  7.500) = 103 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.245 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      4.096 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     18.514 ms/op
     p(99.9900) =     19.759 ms/op
     p(99.9990) =     19.759 ms/op
     p(99.9999) =     19.759 ms/op
    p(100.0000) =     19.759 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.545          ops/ms
ClientSimple.existUser                       thrpt         12.822          ops/ms
ClientSimple.getUser                         thrpt         12.978          ops/ms
ClientSimple.listUser                        thrpt          9.067          ops/ms
ClientSimple.createUser                       avgt          1.983           ms/op
ClientSimple.existUser                        avgt          1.723           ms/op
ClientSimple.getUser                          avgt          2.282           ms/op
ClientSimple.listUser                         avgt          3.649           ms/op
ClientSimple.createUser                     sample  15324   2.102 ± 0.027   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.830           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.989           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.601           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.961           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.448           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.679           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.396           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.448           ms/op
ClientSimple.existUser                      sample  14788   2.168 ± 0.062   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.365           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.005           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.609           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.851           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.030           ms/op
ClientSimple.existUser:existUser·p0.999     sample         48.576           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         50.009           ms/op
ClientSimple.existUser:existUser·p1.00      sample         50.135           ms/op
ClientSimple.getUser                        sample  15083   2.144 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.466           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.048           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.687           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.933           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.743           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.123           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.198           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.206           ms/op
ClientSimple.listUser                       sample   9801   3.273 ± 0.042   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.245           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.072           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.096           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.473           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.053           ms/op
ClientSimple.listUser:listUser·p0.999       sample         18.514           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.759           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.759           ms/op

Benchmark result is saved to 1720570604020.json
