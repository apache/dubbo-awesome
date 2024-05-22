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
# Warmup Iteration   1: 1.979 ops/ms
Iteration   1: 7.583 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.583 ops/ms


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
# Warmup Iteration   1: 5.025 ops/ms
Iteration   1: 13.061 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.061 ops/ms


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
# Warmup Iteration   1: 4.808 ops/ms
Iteration   1: 13.379 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.379 ops/ms


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
# Warmup Iteration   1: 4.769 ops/ms
Iteration   1: 8.372 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.372 ops/ms


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
# Warmup Iteration   1: 4.236 ±(99.9%) 0.085 ms/op
Iteration   1: 2.155 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.155 ms/op


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
# Warmup Iteration   1: 3.226 ±(99.9%) 0.054 ms/op
Iteration   1: 2.069 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.069 ms/op


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
# Warmup Iteration   1: 3.525 ±(99.9%) 0.053 ms/op
Iteration   1: 2.219 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.219 ms/op


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
# Warmup Iteration   1: 4.424 ±(99.9%) 0.084 ms/op
Iteration   1: 3.247 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.247 ms/op


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
# Warmup Iteration   1: 3.802 ±(99.9%) 0.088 ms/op
Iteration   1: 2.414 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   0.479 ms/op
                 createUser·p0.50:   2.167 ms/op
                 createUser·p0.90:   2.916 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   11.649 ms/op
                 createUser·p0.999:  15.446 ms/op
                 createUser·p0.9999: 16.618 ms/op
                 createUser·p1.00:   16.630 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13473
  mean =      2.414 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 191 
    [ 1.250,  2.500) = 9777 
    [ 2.500,  3.750) = 2826 
    [ 3.750,  5.000) = 226 
    [ 5.000,  6.250) = 212 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 46 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.479 ms/op
     p(50.0000) =      2.167 ms/op
     p(90.0000) =      2.916 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =     11.649 ms/op
     p(99.9000) =     15.446 ms/op
     p(99.9900) =     16.618 ms/op
     p(99.9990) =     16.630 ms/op
     p(99.9999) =     16.630 ms/op
    p(100.0000) =     16.630 ms/op


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
# Warmup Iteration   1: 2.779 ±(99.9%) 0.067 ms/op
Iteration   1: 2.066 ±(99.9%) 0.041 ms/op
                 existUser·p0.00:   0.582 ms/op
                 existUser·p0.50:   1.950 ms/op
                 existUser·p0.90:   2.380 ms/op
                 existUser·p0.95:   2.597 ms/op
                 existUser·p0.99:   4.522 ms/op
                 existUser·p0.999:  27.132 ms/op
                 existUser·p0.9999: 28.392 ms/op
                 existUser·p1.00:   28.770 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15497
  mean =      2.066 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14385 
    [ 2.500,  5.000) = 1038 
    [ 5.000,  7.500) = 8 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.582 ms/op
     p(50.0000) =      1.950 ms/op
     p(90.0000) =      2.380 ms/op
     p(95.0000) =      2.597 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =     27.132 ms/op
     p(99.9900) =     28.392 ms/op
     p(99.9990) =     28.770 ms/op
     p(99.9999) =     28.770 ms/op
    p(100.0000) =     28.770 ms/op


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
# Warmup Iteration   1: 3.441 ±(99.9%) 0.093 ms/op
Iteration   1: 1.849 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.714 ms/op
                 getUser·p0.50:   1.696 ms/op
                 getUser·p0.90:   2.331 ms/op
                 getUser·p0.95:   2.597 ms/op
                 getUser·p0.99:   3.409 ms/op
                 getUser·p0.999:  12.176 ms/op
                 getUser·p0.9999: 14.166 ms/op
                 getUser·p1.00:   14.238 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17282
  mean =      1.849 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 82 
    [ 1.250,  2.500) = 16065 
    [ 2.500,  3.750) = 1030 
    [ 3.750,  5.000) = 61 
    [ 5.000,  6.250) = 12 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.714 ms/op
     p(50.0000) =      1.696 ms/op
     p(90.0000) =      2.331 ms/op
     p(95.0000) =      2.597 ms/op
     p(99.0000) =      3.409 ms/op
     p(99.9000) =     12.176 ms/op
     p(99.9900) =     14.166 ms/op
     p(99.9990) =     14.238 ms/op
     p(99.9999) =     14.238 ms/op
    p(100.0000) =     14.238 ms/op


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
# Warmup Iteration   1: 5.070 ±(99.9%) 0.157 ms/op
Iteration   1: 3.475 ±(99.9%) 0.140 ms/op
                 listUser·p0.00:   0.750 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.768 ms/op
                 listUser·p0.99:   6.725 ms/op
                 listUser·p0.999:  70.018 ms/op
                 listUser·p0.9999: 72.614 ms/op
                 listUser·p1.00:   72.614 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9201
  mean =      3.475 ±(99.9%) 0.140 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 8845 
    [ 5.000, 10.000) = 291 
    [10.000, 15.000) = 2 
    [15.000, 20.000) = 19 
    [20.000, 25.000) = 12 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 0 
    [60.000, 65.000) = 0 
    [65.000, 70.000) = 23 
    [70.000, 75.000) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.750 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      6.725 ms/op
     p(99.9000) =     70.018 ms/op
     p(99.9900) =     72.614 ms/op
     p(99.9990) =     72.614 ms/op
     p(99.9999) =     72.614 ms/op
    p(100.0000) =     72.614 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.583          ops/ms
ClientSimple.existUser                       thrpt         13.061          ops/ms
ClientSimple.getUser                         thrpt         13.379          ops/ms
ClientSimple.listUser                        thrpt          8.372          ops/ms
ClientSimple.createUser                       avgt          2.155           ms/op
ClientSimple.existUser                        avgt          2.069           ms/op
ClientSimple.getUser                          avgt          2.219           ms/op
ClientSimple.listUser                         avgt          3.247           ms/op
ClientSimple.createUser                     sample  13473   2.414 ± 0.040   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.479           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.167           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.916           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.772           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.649           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.446           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.618           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.630           ms/op
ClientSimple.existUser                      sample  15497   2.066 ± 0.041   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.582           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.950           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.380           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.597           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.522           ms/op
ClientSimple.existUser:existUser·p0.999     sample         27.132           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         28.392           ms/op
ClientSimple.existUser:existUser·p1.00      sample         28.770           ms/op
ClientSimple.getUser                        sample  17282   1.849 ± 0.015   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.714           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.696           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.331           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.597           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.409           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.176           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.166           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.238           ms/op
ClientSimple.listUser                       sample   9201   3.475 ± 0.140   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.750           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.937           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.243           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.768           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.725           ms/op
ClientSimple.listUser:listUser·p0.999       sample         70.018           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         72.614           ms/op
ClientSimple.listUser:listUser·p1.00        sample         72.614           ms/op

Benchmark result is saved to 1716357947060.json
