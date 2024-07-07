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
# Warmup Iteration   1: 0.989 ops/ms
Iteration   1: 5.648 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.648 ops/ms


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
# Warmup Iteration   1: 6.316 ops/ms
Iteration   1: 10.551 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.551 ops/ms


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
# Warmup Iteration   1: 5.122 ops/ms
Iteration   1: 12.637 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.637 ops/ms


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
# Warmup Iteration   1: 4.742 ops/ms
Iteration   1: 8.003 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.003 ops/ms


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
# Warmup Iteration   1: 4.078 ±(99.9%) 0.084 ms/op
Iteration   1: 2.049 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.049 ms/op


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
# Warmup Iteration   1: 3.519 ±(99.9%) 0.074 ms/op
Iteration   1: 2.007 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.007 ms/op


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
# Warmup Iteration   1: 3.110 ±(99.9%) 0.063 ms/op
Iteration   1: 2.255 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.255 ms/op


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
# Warmup Iteration   1: 4.300 ±(99.9%) 0.097 ms/op
Iteration   1: 3.266 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.266 ms/op


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
# Warmup Iteration   1: 3.266 ±(99.9%) 0.084 ms/op
Iteration   1: 2.159 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   0.583 ms/op
                 createUser·p0.50:   1.964 ms/op
                 createUser·p0.90:   2.441 ms/op
                 createUser·p0.95:   2.727 ms/op
                 createUser·p0.99:   5.160 ms/op
                 createUser·p0.999:  20.742 ms/op
                 createUser·p0.9999: 21.578 ms/op
                 createUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14806
  mean =      2.159 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13555 
    [ 2.500,  5.000) = 1084 
    [ 5.000,  7.500) = 36 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.583 ms/op
     p(50.0000) =      1.964 ms/op
     p(90.0000) =      2.441 ms/op
     p(95.0000) =      2.727 ms/op
     p(99.0000) =      5.160 ms/op
     p(99.9000) =     20.742 ms/op
     p(99.9900) =     21.578 ms/op
     p(99.9990) =     21.594 ms/op
     p(99.9999) =     21.594 ms/op
    p(100.0000) =     21.594 ms/op


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
# Warmup Iteration   1: 2.920 ±(99.9%) 0.066 ms/op
Iteration   1: 2.015 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.678 ms/op
                 existUser·p0.50:   1.905 ms/op
                 existUser·p0.90:   2.560 ms/op
                 existUser·p0.95:   2.866 ms/op
                 existUser·p0.99:   4.212 ms/op
                 existUser·p0.999:  12.141 ms/op
                 existUser·p0.9999: 12.393 ms/op
                 existUser·p1.00:   12.403 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15987
  mean =      2.015 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 422 
    [ 1.250,  2.500) = 13564 
    [ 2.500,  3.750) = 1747 
    [ 3.750,  5.000) = 137 
    [ 5.000,  6.250) = 38 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.678 ms/op
     p(50.0000) =      1.905 ms/op
     p(90.0000) =      2.560 ms/op
     p(95.0000) =      2.866 ms/op
     p(99.0000) =      4.212 ms/op
     p(99.9000) =     12.141 ms/op
     p(99.9900) =     12.393 ms/op
     p(99.9990) =     12.403 ms/op
     p(99.9999) =     12.403 ms/op
    p(100.0000) =     12.403 ms/op


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
# Warmup Iteration   1: 3.357 ±(99.9%) 0.090 ms/op
Iteration   1: 2.325 ±(99.9%) 0.042 ms/op
                 getUser·p0.00:   0.674 ms/op
                 getUser·p0.50:   2.122 ms/op
                 getUser·p0.90:   2.847 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   6.328 ms/op
                 getUser·p0.999:  27.722 ms/op
                 getUser·p0.9999: 28.230 ms/op
                 getUser·p1.00:   28.279 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13752
  mean =      2.325 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11197 
    [ 2.500,  5.000) = 2365 
    [ 5.000,  7.500) = 90 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.674 ms/op
     p(50.0000) =      2.122 ms/op
     p(90.0000) =      2.847 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      6.328 ms/op
     p(99.9000) =     27.722 ms/op
     p(99.9900) =     28.230 ms/op
     p(99.9990) =     28.279 ms/op
     p(99.9999) =     28.279 ms/op
    p(100.0000) =     28.279 ms/op


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
# Warmup Iteration   1: 4.603 ±(99.9%) 0.159 ms/op
Iteration   1: 3.278 ±(99.9%) 0.035 ms/op
                 listUser·p0.00:   1.069 ms/op
                 listUser·p0.50:   3.289 ms/op
                 listUser·p0.90:   4.071 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   6.023 ms/op
                 listUser·p0.999:  14.226 ms/op
                 listUser·p0.9999: 28.377 ms/op
                 listUser·p1.00:   28.377 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9773
  mean =      3.278 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1632 
    [ 2.500,  5.000) = 7992 
    [ 5.000,  7.500) = 111 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.069 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      6.023 ms/op
     p(99.9000) =     14.226 ms/op
     p(99.9900) =     28.377 ms/op
     p(99.9990) =     28.377 ms/op
     p(99.9999) =     28.377 ms/op
    p(100.0000) =     28.377 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.648          ops/ms
ClientSimple.existUser                       thrpt         10.551          ops/ms
ClientSimple.getUser                         thrpt         12.637          ops/ms
ClientSimple.listUser                        thrpt          8.003          ops/ms
ClientSimple.createUser                       avgt          2.049           ms/op
ClientSimple.existUser                        avgt          2.007           ms/op
ClientSimple.getUser                          avgt          2.255           ms/op
ClientSimple.listUser                         avgt          3.266           ms/op
ClientSimple.createUser                     sample  14806   2.159 ± 0.039   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.583           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.964           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.441           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.727           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.160           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.742           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.578           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.594           ms/op
ClientSimple.existUser                      sample  15987   2.015 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.678           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.905           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.560           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.866           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.212           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.141           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.393           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.403           ms/op
ClientSimple.getUser                        sample  13752   2.325 ± 0.042   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.674           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.122           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.847           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.150           ms/op
ClientSimple.getUser:getUser·p0.99          sample          6.328           ms/op
ClientSimple.getUser:getUser·p0.999         sample         27.722           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         28.230           ms/op
ClientSimple.getUser:getUser·p1.00          sample         28.279           ms/op
ClientSimple.listUser                       sample   9773   3.278 ± 0.035   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.069           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.289           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.071           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.325           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.023           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.226           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         28.377           ms/op
ClientSimple.listUser:listUser·p1.00        sample         28.377           ms/op

Benchmark result is saved to 1720332369370.json
