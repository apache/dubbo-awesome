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
# Warmup Iteration   1: 0.624 ops/ms
Iteration   1: 5.314 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.314 ops/ms


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
# Warmup Iteration   1: 5.307 ops/ms
Iteration   1: 12.194 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.194 ops/ms


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
# Warmup Iteration   1: 7.615 ops/ms
Iteration   1: 12.975 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.975 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.827 ops/ms
Iteration   1: 9.048 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.048 ops/ms


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
# Warmup Iteration   1: 4.137 ±(99.9%) 0.075 ms/op
Iteration   1: 2.047 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.047 ms/op


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
# Warmup Iteration   1: 3.424 ±(99.9%) 0.067 ms/op
Iteration   1: 1.904 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.904 ms/op


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
# Warmup Iteration   1: 3.287 ±(99.9%) 0.069 ms/op
Iteration   1: 1.808 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.808 ms/op


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
# Warmup Iteration   1: 4.603 ±(99.9%) 0.133 ms/op
Iteration   1: 3.484 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.484 ms/op


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
# Warmup Iteration   1: 3.788 ±(99.9%) 0.109 ms/op
Iteration   1: 2.157 ±(99.9%) 0.047 ms/op
                 createUser·p0.00:   0.283 ms/op
                 createUser·p0.50:   1.870 ms/op
                 createUser·p0.90:   2.499 ms/op
                 createUser·p0.95:   2.904 ms/op
                 createUser·p0.99:   11.502 ms/op
                 createUser·p0.999:  23.653 ms/op
                 createUser·p0.9999: 27.070 ms/op
                 createUser·p1.00:   27.165 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14806
  mean =      2.157 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13334 
    [ 2.500,  5.000) = 1152 
    [ 5.000,  7.500) = 154 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.283 ms/op
     p(50.0000) =      1.870 ms/op
     p(90.0000) =      2.499 ms/op
     p(95.0000) =      2.904 ms/op
     p(99.0000) =     11.502 ms/op
     p(99.9000) =     23.653 ms/op
     p(99.9900) =     27.070 ms/op
     p(99.9990) =     27.165 ms/op
     p(99.9999) =     27.165 ms/op
    p(100.0000) =     27.165 ms/op


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
# Warmup Iteration   1: 2.978 ±(99.9%) 0.076 ms/op
Iteration   1: 2.246 ±(99.9%) 0.032 ms/op
                 existUser·p0.00:   0.545 ms/op
                 existUser·p0.50:   2.146 ms/op
                 existUser·p0.90:   2.720 ms/op
                 existUser·p0.95:   2.904 ms/op
                 existUser·p0.99:   4.555 ms/op
                 existUser·p0.999:  21.103 ms/op
                 existUser·p0.9999: 21.384 ms/op
                 existUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14269
  mean =      2.246 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11048 
    [ 2.500,  5.000) = 3090 
    [ 5.000,  7.500) = 66 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 14 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.545 ms/op
     p(50.0000) =      2.146 ms/op
     p(90.0000) =      2.720 ms/op
     p(95.0000) =      2.904 ms/op
     p(99.0000) =      4.555 ms/op
     p(99.9000) =     21.103 ms/op
     p(99.9900) =     21.384 ms/op
     p(99.9990) =     21.398 ms/op
     p(99.9999) =     21.398 ms/op
    p(100.0000) =     21.398 ms/op


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
# Warmup Iteration   1: 3.465 ±(99.9%) 0.093 ms/op
Iteration   1: 1.891 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.523 ms/op
                 getUser·p0.50:   1.739 ms/op
                 getUser·p0.90:   2.363 ms/op
                 getUser·p0.95:   2.601 ms/op
                 getUser·p0.99:   3.926 ms/op
                 getUser·p0.999:  13.482 ms/op
                 getUser·p0.9999: 13.899 ms/op
                 getUser·p1.00:   13.910 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17014
  mean =      1.891 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 125 
    [ 1.250,  2.500) = 15799 
    [ 2.500,  3.750) = 897 
    [ 3.750,  5.000) = 71 
    [ 5.000,  6.250) = 84 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.523 ms/op
     p(50.0000) =      1.739 ms/op
     p(90.0000) =      2.363 ms/op
     p(95.0000) =      2.601 ms/op
     p(99.0000) =      3.926 ms/op
     p(99.9000) =     13.482 ms/op
     p(99.9900) =     13.899 ms/op
     p(99.9990) =     13.910 ms/op
     p(99.9999) =     13.910 ms/op
    p(100.0000) =     13.910 ms/op


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
# Warmup Iteration   1: 5.082 ±(99.9%) 0.147 ms/op
Iteration   1: 3.461 ±(99.9%) 0.054 ms/op
                 listUser·p0.00:   1.067 ms/op
                 listUser·p0.50:   3.105 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   5.153 ms/op
                 listUser·p0.99:   7.860 ms/op
                 listUser·p0.999:  22.118 ms/op
                 listUser·p0.9999: 22.905 ms/op
                 listUser·p1.00:   22.905 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9346
  mean =      3.461 ±(99.9%) 0.054 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 675 
    [ 2.500,  5.000) = 8150 
    [ 5.000,  7.500) = 403 
    [ 7.500, 10.000) = 54 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.067 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      5.153 ms/op
     p(99.0000) =      7.860 ms/op
     p(99.9000) =     22.118 ms/op
     p(99.9900) =     22.905 ms/op
     p(99.9990) =     22.905 ms/op
     p(99.9999) =     22.905 ms/op
    p(100.0000) =     22.905 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.314          ops/ms
ClientSimple.existUser                       thrpt         12.194          ops/ms
ClientSimple.getUser                         thrpt         12.975          ops/ms
ClientSimple.listUser                        thrpt          9.048          ops/ms
ClientSimple.createUser                       avgt          2.047           ms/op
ClientSimple.existUser                        avgt          1.904           ms/op
ClientSimple.getUser                          avgt          1.808           ms/op
ClientSimple.listUser                         avgt          3.484           ms/op
ClientSimple.createUser                     sample  14806   2.157 ± 0.047   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.283           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.870           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.499           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.904           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.502           ms/op
ClientSimple.createUser:createUser·p0.999   sample         23.653           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         27.070           ms/op
ClientSimple.createUser:createUser·p1.00    sample         27.165           ms/op
ClientSimple.existUser                      sample  14269   2.246 ± 0.032   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.545           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.146           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.720           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.904           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.555           ms/op
ClientSimple.existUser:existUser·p0.999     sample         21.103           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         21.384           ms/op
ClientSimple.existUser:existUser·p1.00      sample         21.398           ms/op
ClientSimple.getUser                        sample  17014   1.891 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.523           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.739           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.363           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.601           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.926           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.482           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.899           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.910           ms/op
ClientSimple.listUser                       sample   9346   3.461 ± 0.054   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.067           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.105           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.424           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.153           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.860           ms/op
ClientSimple.listUser:listUser·p0.999       sample         22.118           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         22.905           ms/op
ClientSimple.listUser:listUser·p1.00        sample         22.905           ms/op

Benchmark result is saved to 1717848355070.json
