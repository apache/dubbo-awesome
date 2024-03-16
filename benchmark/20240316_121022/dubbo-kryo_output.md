# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.895 ops/ms
Iteration   1: 7.818 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.818 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.152 ops/ms
Iteration   1: 14.429 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.429 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 6.963 ops/ms
Iteration   1: 13.452 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.452 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.538 ops/ms
Iteration   1: 8.608 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.608 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.363 ±(99.9%) 0.055 ms/op
Iteration   1: 2.067 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.067 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.168 ±(99.9%) 0.053 ms/op
Iteration   1: 1.733 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.733 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.227 ±(99.9%) 0.048 ms/op
Iteration   1: 1.914 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.914 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.755 ±(99.9%) 0.069 ms/op
Iteration   1: 3.240 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.240 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.186 ±(99.9%) 0.074 ms/op
Iteration   1: 1.909 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.542 ms/op
                 createUser·p0.50:   1.747 ms/op
                 createUser·p0.90:   2.142 ms/op
                 createUser·p0.95:   2.335 ms/op
                 createUser·p0.99:   7.115 ms/op
                 createUser·p0.999:  17.007 ms/op
                 createUser·p0.9999: 17.610 ms/op
                 createUser·p1.00:   17.727 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 17140
  mean =      1.909 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 363 
    [ 1.250,  2.500) = 16196 
    [ 2.500,  3.750) = 159 
    [ 3.750,  5.000) = 119 
    [ 5.000,  6.250) = 50 
    [ 6.250,  7.500) = 121 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.542 ms/op
     p(50.0000) =      1.747 ms/op
     p(90.0000) =      2.142 ms/op
     p(95.0000) =      2.335 ms/op
     p(99.0000) =      7.115 ms/op
     p(99.9000) =     17.007 ms/op
     p(99.9900) =     17.610 ms/op
     p(99.9990) =     17.727 ms/op
     p(99.9999) =     17.727 ms/op
    p(100.0000) =     17.727 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.833 ±(99.9%) 0.078 ms/op
Iteration   1: 1.710 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.322 ms/op
                 existUser·p0.50:   1.659 ms/op
                 existUser·p0.90:   2.191 ms/op
                 existUser·p0.95:   2.335 ms/op
                 existUser·p0.99:   3.509 ms/op
                 existUser·p0.999:  12.730 ms/op
                 existUser·p0.9999: 12.865 ms/op
                 existUser·p1.00:   12.894 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 19032
  mean =      1.710 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2730 
    [ 1.250,  2.500) = 15774 
    [ 2.500,  3.750) = 368 
    [ 3.750,  5.000) = 93 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.322 ms/op
     p(50.0000) =      1.659 ms/op
     p(90.0000) =      2.191 ms/op
     p(95.0000) =      2.335 ms/op
     p(99.0000) =      3.509 ms/op
     p(99.9000) =     12.730 ms/op
     p(99.9900) =     12.865 ms/op
     p(99.9990) =     12.894 ms/op
     p(99.9999) =     12.894 ms/op
    p(100.0000) =     12.894 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 3.036 ±(99.9%) 0.065 ms/op
Iteration   1: 2.039 ±(99.9%) 0.038 ms/op
                 getUser·p0.00:   0.622 ms/op
                 getUser·p0.50:   1.923 ms/op
                 getUser·p0.90:   2.626 ms/op
                 getUser·p0.95:   2.830 ms/op
                 getUser·p0.99:   3.679 ms/op
                 getUser·p0.999:  29.590 ms/op
                 getUser·p0.9999: 30.350 ms/op
                 getUser·p1.00:   30.704 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15671
  mean =      2.039 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13402 
    [ 2.500,  5.000) = 2172 
    [ 5.000,  7.500) = 29 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.622 ms/op
     p(50.0000) =      1.923 ms/op
     p(90.0000) =      2.626 ms/op
     p(95.0000) =      2.830 ms/op
     p(99.0000) =      3.679 ms/op
     p(99.9000) =     29.590 ms/op
     p(99.9900) =     30.350 ms/op
     p(99.9990) =     30.704 ms/op
     p(99.9999) =     30.704 ms/op
    p(100.0000) =     30.704 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.196 ±(99.9%) 0.125 ms/op
Iteration   1: 3.152 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   0.708 ms/op
                 listUser·p0.50:   2.761 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   5.980 ms/op
                 listUser·p0.999:  7.438 ms/op
                 listUser·p0.9999: 8.287 ms/op
                 listUser·p1.00:   8.298 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10143
  mean =      3.152 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 3 
    [1.000, 1.500) = 22 
    [1.500, 2.000) = 96 
    [2.000, 2.500) = 2325 
    [2.500, 3.000) = 3315 
    [3.000, 3.500) = 849 
    [3.500, 4.000) = 1853 
    [4.000, 4.500) = 1070 
    [4.500, 5.000) = 372 
    [5.000, 5.500) = 118 
    [5.500, 6.000) = 19 
    [6.000, 6.500) = 35 
    [6.500, 7.000) = 16 
    [7.000, 7.500) = 48 
    [7.500, 8.000) = 1 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.708 ms/op
     p(50.0000) =      2.761 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      5.980 ms/op
     p(99.9000) =      7.438 ms/op
     p(99.9900) =      8.287 ms/op
     p(99.9990) =      8.298 ms/op
     p(99.9999) =      8.298 ms/op
    p(100.0000) =      8.298 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.818          ops/ms
ClientSimple.existUser                       thrpt         14.429          ops/ms
ClientSimple.getUser                         thrpt         13.452          ops/ms
ClientSimple.listUser                        thrpt          8.608          ops/ms
ClientSimple.createUser                       avgt          2.067           ms/op
ClientSimple.existUser                        avgt          1.733           ms/op
ClientSimple.getUser                          avgt          1.914           ms/op
ClientSimple.listUser                         avgt          3.240           ms/op
ClientSimple.createUser                     sample  17140   1.909 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.542           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.747           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.142           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.335           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.115           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.007           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.610           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.727           ms/op
ClientSimple.existUser                      sample  19032   1.710 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.322           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.659           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.191           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.335           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.509           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.730           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.865           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.894           ms/op
ClientSimple.getUser                        sample  15671   2.039 ± 0.038   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.622           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.923           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.626           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.830           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.679           ms/op
ClientSimple.getUser:getUser·p0.999         sample         29.590           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         30.350           ms/op
ClientSimple.getUser:getUser·p1.00          sample         30.704           ms/op
ClientSimple.listUser                       sample  10143   3.152 ± 0.028   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.708           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.761           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.235           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.588           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.980           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.438           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.287           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.298           ms/op

Benchmark result is saved to 1710590771177.json
