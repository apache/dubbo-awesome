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
# Warmup Iteration   1: 1.642 ops/ms
Iteration   1: 6.923 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.923 ops/ms


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
# Warmup Iteration   1: 5.833 ops/ms
Iteration   1: 11.681 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.681 ops/ms


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
# Warmup Iteration   1: 6.458 ops/ms
Iteration   1: 13.207 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.207 ops/ms


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
# Warmup Iteration   1: 5.262 ops/ms
Iteration   1: 8.775 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.775 ops/ms


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
# Warmup Iteration   1: 3.748 ±(99.9%) 0.069 ms/op
Iteration   1: 2.276 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.276 ms/op


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
# Warmup Iteration   1: 3.510 ±(99.9%) 0.051 ms/op
Iteration   1: 1.913 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.913 ms/op


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
# Warmup Iteration   1: 3.228 ±(99.9%) 0.052 ms/op
Iteration   1: 2.063 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.063 ms/op


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
# Warmup Iteration   1: 4.392 ±(99.9%) 0.092 ms/op
Iteration   1: 3.426 ±(99.9%) 0.032 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.426 ms/op


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
# Warmup Iteration   1: 3.541 ±(99.9%) 0.091 ms/op
Iteration   1: 2.280 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.569 ms/op
                 createUser·p0.50:   2.150 ms/op
                 createUser·p0.90:   2.720 ms/op
                 createUser·p0.95:   2.916 ms/op
                 createUser·p0.99:   8.335 ms/op
                 createUser·p0.999:  14.056 ms/op
                 createUser·p0.9999: 17.744 ms/op
                 createUser·p1.00:   18.088 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14040
  mean =      2.280 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 124 
    [ 1.250,  2.500) = 10916 
    [ 2.500,  3.750) = 2717 
    [ 3.750,  5.000) = 69 
    [ 5.000,  6.250) = 26 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 50 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 73 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.569 ms/op
     p(50.0000) =      2.150 ms/op
     p(90.0000) =      2.720 ms/op
     p(95.0000) =      2.916 ms/op
     p(99.0000) =      8.335 ms/op
     p(99.9000) =     14.056 ms/op
     p(99.9900) =     17.744 ms/op
     p(99.9990) =     18.088 ms/op
     p(99.9999) =     18.088 ms/op
    p(100.0000) =     18.088 ms/op


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
# Warmup Iteration   1: 2.879 ±(99.9%) 0.061 ms/op
Iteration   1: 2.001 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   0.426 ms/op
                 existUser·p0.50:   1.923 ms/op
                 existUser·p0.90:   2.445 ms/op
                 existUser·p0.95:   2.605 ms/op
                 existUser·p0.99:   5.078 ms/op
                 existUser·p0.999:  15.335 ms/op
                 existUser·p0.9999: 15.712 ms/op
                 existUser·p1.00:   15.761 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15989
  mean =      2.001 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 584 
    [ 1.250,  2.500) = 14196 
    [ 2.500,  3.750) = 1000 
    [ 3.750,  5.000) = 49 
    [ 5.000,  6.250) = 55 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 37 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.426 ms/op
     p(50.0000) =      1.923 ms/op
     p(90.0000) =      2.445 ms/op
     p(95.0000) =      2.605 ms/op
     p(99.0000) =      5.078 ms/op
     p(99.9000) =     15.335 ms/op
     p(99.9900) =     15.712 ms/op
     p(99.9990) =     15.761 ms/op
     p(99.9999) =     15.761 ms/op
    p(100.0000) =     15.761 ms/op


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
# Warmup Iteration   1: 3.531 ±(99.9%) 0.090 ms/op
Iteration   1: 1.984 ±(99.9%) 0.099 ms/op
                 getUser·p0.00:   0.814 ms/op
                 getUser·p0.50:   1.599 ms/op
                 getUser·p0.90:   2.372 ms/op
                 getUser·p0.95:   2.589 ms/op
                 getUser·p0.99:   3.809 ms/op
                 getUser·p0.999:  79.390 ms/op
                 getUser·p0.9999: 103.122 ms/op
                 getUser·p1.00:   103.285 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16216
  mean =      1.984 ±(99.9%) 0.099 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 16156 
    [ 12.500,  25.000) = 11 
    [ 25.000,  37.500) = 4 
    [ 37.500,  50.000) = 10 
    [ 50.000,  62.500) = 9 
    [ 62.500,  75.000) = 8 
    [ 75.000,  87.500) = 4 
    [ 87.500, 100.000) = 6 
    [100.000, 112.500) = 8 
    [112.500, 125.000) = 0 
    [125.000, 137.500) = 0 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.814 ms/op
     p(50.0000) =      1.599 ms/op
     p(90.0000) =      2.372 ms/op
     p(95.0000) =      2.589 ms/op
     p(99.0000) =      3.809 ms/op
     p(99.9000) =     79.390 ms/op
     p(99.9900) =    103.122 ms/op
     p(99.9990) =    103.285 ms/op
     p(99.9999) =    103.285 ms/op
    p(100.0000) =    103.285 ms/op


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
# Warmup Iteration   1: 4.564 ±(99.9%) 0.120 ms/op
Iteration   1: 3.351 ±(99.9%) 0.054 ms/op
                 listUser·p0.00:   1.124 ms/op
                 listUser·p0.50:   3.133 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   7.022 ms/op
                 listUser·p0.999:  25.246 ms/op
                 listUser·p0.9999: 30.966 ms/op
                 listUser·p1.00:   30.966 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9540
  mean =      3.351 ±(99.9%) 0.054 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1988 
    [ 2.500,  5.000) = 7233 
    [ 5.000,  7.500) = 238 
    [ 7.500, 10.000) = 13 
    [10.000, 12.500) = 21 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.124 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      7.022 ms/op
     p(99.9000) =     25.246 ms/op
     p(99.9900) =     30.966 ms/op
     p(99.9990) =     30.966 ms/op
     p(99.9999) =     30.966 ms/op
    p(100.0000) =     30.966 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt    Score   Error   Units
ClientSimple.createUser                      thrpt           6.923          ops/ms
ClientSimple.existUser                       thrpt          11.681          ops/ms
ClientSimple.getUser                         thrpt          13.207          ops/ms
ClientSimple.listUser                        thrpt           8.775          ops/ms
ClientSimple.createUser                       avgt           2.276           ms/op
ClientSimple.existUser                        avgt           1.913           ms/op
ClientSimple.getUser                          avgt           2.063           ms/op
ClientSimple.listUser                         avgt           3.426           ms/op
ClientSimple.createUser                     sample  14040    2.280 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample           0.569           ms/op
ClientSimple.createUser:createUser·p0.50    sample           2.150           ms/op
ClientSimple.createUser:createUser·p0.90    sample           2.720           ms/op
ClientSimple.createUser:createUser·p0.95    sample           2.916           ms/op
ClientSimple.createUser:createUser·p0.99    sample           8.335           ms/op
ClientSimple.createUser:createUser·p0.999   sample          14.056           ms/op
ClientSimple.createUser:createUser·p0.9999  sample          17.744           ms/op
ClientSimple.createUser:createUser·p1.00    sample          18.088           ms/op
ClientSimple.existUser                      sample  15989    2.001 ± 0.028   ms/op
ClientSimple.existUser:existUser·p0.00      sample           0.426           ms/op
ClientSimple.existUser:existUser·p0.50      sample           1.923           ms/op
ClientSimple.existUser:existUser·p0.90      sample           2.445           ms/op
ClientSimple.existUser:existUser·p0.95      sample           2.605           ms/op
ClientSimple.existUser:existUser·p0.99      sample           5.078           ms/op
ClientSimple.existUser:existUser·p0.999     sample          15.335           ms/op
ClientSimple.existUser:existUser·p0.9999    sample          15.712           ms/op
ClientSimple.existUser:existUser·p1.00      sample          15.761           ms/op
ClientSimple.getUser                        sample  16216    1.984 ± 0.099   ms/op
ClientSimple.getUser:getUser·p0.00          sample           0.814           ms/op
ClientSimple.getUser:getUser·p0.50          sample           1.599           ms/op
ClientSimple.getUser:getUser·p0.90          sample           2.372           ms/op
ClientSimple.getUser:getUser·p0.95          sample           2.589           ms/op
ClientSimple.getUser:getUser·p0.99          sample           3.809           ms/op
ClientSimple.getUser:getUser·p0.999         sample          79.390           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         103.122           ms/op
ClientSimple.getUser:getUser·p1.00          sample         103.285           ms/op
ClientSimple.listUser                       sample   9540    3.351 ± 0.054   ms/op
ClientSimple.listUser:listUser·p0.00        sample           1.124           ms/op
ClientSimple.listUser:listUser·p0.50        sample           3.133           ms/op
ClientSimple.listUser:listUser·p0.90        sample           4.301           ms/op
ClientSimple.listUser:listUser·p0.95        sample           4.604           ms/op
ClientSimple.listUser:listUser·p0.99        sample           7.022           ms/op
ClientSimple.listUser:listUser·p0.999       sample          25.246           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          30.966           ms/op
ClientSimple.listUser:listUser·p1.00        sample          30.966           ms/op

Benchmark result is saved to 1718453199944.json
