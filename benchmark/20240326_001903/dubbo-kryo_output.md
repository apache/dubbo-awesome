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
# Warmup Iteration   1: 0.641 ops/ms
Iteration   1: 5.884 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.884 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.234 ops/ms
Iteration   1: 13.247 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.247 ops/ms


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
# Warmup Iteration   1: 5.649 ops/ms
Iteration   1: 12.550 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.550 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.960 ops/ms
Iteration   1: 8.753 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.753 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.852 ±(99.9%) 0.108 ms/op
Iteration   1: 2.172 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.172 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.600 ±(99.9%) 0.075 ms/op
Iteration   1: 1.792 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.792 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.180 ±(99.9%) 0.053 ms/op
Iteration   1: 1.919 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.919 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.986 ±(99.9%) 0.129 ms/op
Iteration   1: 3.420 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.420 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.740 ±(99.9%) 0.101 ms/op
Iteration   1: 1.942 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   0.472 ms/op
                 createUser·p0.50:   1.835 ms/op
                 createUser·p0.90:   2.335 ms/op
                 createUser·p0.95:   2.560 ms/op
                 createUser·p0.99:   6.636 ms/op
                 createUser·p0.999:  13.976 ms/op
                 createUser·p0.9999: 15.226 ms/op
                 createUser·p1.00:   15.237 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16498
  mean =      1.942 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 685 
    [ 1.250,  2.500) = 14802 
    [ 2.500,  3.750) = 786 
    [ 3.750,  5.000) = 51 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 58 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.472 ms/op
     p(50.0000) =      1.835 ms/op
     p(90.0000) =      2.335 ms/op
     p(95.0000) =      2.560 ms/op
     p(99.0000) =      6.636 ms/op
     p(99.9000) =     13.976 ms/op
     p(99.9900) =     15.226 ms/op
     p(99.9990) =     15.237 ms/op
     p(99.9999) =     15.237 ms/op
    p(100.0000) =     15.237 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.021 ±(99.9%) 0.071 ms/op
Iteration   1: 2.020 ±(99.9%) 0.032 ms/op
                 existUser·p0.00:   0.651 ms/op
                 existUser·p0.50:   1.915 ms/op
                 existUser·p0.90:   2.458 ms/op
                 existUser·p0.95:   2.638 ms/op
                 existUser·p0.99:   5.358 ms/op
                 existUser·p0.999:  22.086 ms/op
                 existUser·p0.9999: 22.886 ms/op
                 existUser·p1.00:   22.905 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15770
  mean =      2.020 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14426 
    [ 2.500,  5.000) = 1156 
    [ 5.000,  7.500) = 124 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.651 ms/op
     p(50.0000) =      1.915 ms/op
     p(90.0000) =      2.458 ms/op
     p(95.0000) =      2.638 ms/op
     p(99.0000) =      5.358 ms/op
     p(99.9000) =     22.086 ms/op
     p(99.9900) =     22.886 ms/op
     p(99.9990) =     22.905 ms/op
     p(99.9999) =     22.905 ms/op
    p(100.0000) =     22.905 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.053 ±(99.9%) 0.070 ms/op
Iteration   1: 1.888 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.597 ms/op
                 getUser·p0.50:   1.835 ms/op
                 getUser·p0.90:   2.531 ms/op
                 getUser·p0.95:   2.707 ms/op
                 getUser·p0.99:   3.150 ms/op
                 getUser·p0.999:  11.335 ms/op
                 getUser·p0.9999: 11.917 ms/op
                 getUser·p1.00:   12.009 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17053
  mean =      1.888 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1214 
    [ 1.250,  2.500) = 13970 
    [ 2.500,  3.750) = 1821 
    [ 3.750,  5.000) = 12 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.597 ms/op
     p(50.0000) =      1.835 ms/op
     p(90.0000) =      2.531 ms/op
     p(95.0000) =      2.707 ms/op
     p(99.0000) =      3.150 ms/op
     p(99.9000) =     11.335 ms/op
     p(99.9900) =     11.917 ms/op
     p(99.9990) =     12.009 ms/op
     p(99.9999) =     12.009 ms/op
    p(100.0000) =     12.009 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.441 ±(99.9%) 0.132 ms/op
Iteration   1: 2.956 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   0.670 ms/op
                 listUser·p0.50:   2.789 ms/op
                 listUser·p0.90:   3.764 ms/op
                 listUser·p0.95:   3.985 ms/op
                 listUser·p0.99:   5.087 ms/op
                 listUser·p0.999:  6.244 ms/op
                 listUser·p0.9999: 6.791 ms/op
                 listUser·p1.00:   6.791 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10799
  mean =      2.956 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 1 
    [1.000, 1.500) = 25 
    [1.500, 2.000) = 134 
    [2.000, 2.500) = 1864 
    [2.500, 3.000) = 4996 
    [3.000, 3.500) = 1777 
    [3.500, 4.000) = 1479 
    [4.000, 4.500) = 324 
    [4.500, 5.000) = 78 
    [5.000, 5.500) = 59 
    [5.500, 6.000) = 19 
    [6.000, 6.500) = 39 

  Percentiles, ms/op:
      p(0.0000) =      0.670 ms/op
     p(50.0000) =      2.789 ms/op
     p(90.0000) =      3.764 ms/op
     p(95.0000) =      3.985 ms/op
     p(99.0000) =      5.087 ms/op
     p(99.9000) =      6.244 ms/op
     p(99.9900) =      6.791 ms/op
     p(99.9990) =      6.791 ms/op
     p(99.9999) =      6.791 ms/op
    p(100.0000) =      6.791 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.884          ops/ms
ClientSimple.existUser                       thrpt         13.247          ops/ms
ClientSimple.getUser                         thrpt         12.550          ops/ms
ClientSimple.listUser                        thrpt          8.753          ops/ms
ClientSimple.createUser                       avgt          2.172           ms/op
ClientSimple.existUser                        avgt          1.792           ms/op
ClientSimple.getUser                          avgt          1.919           ms/op
ClientSimple.listUser                         avgt          3.420           ms/op
ClientSimple.createUser                     sample  16498   1.942 ± 0.024   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.472           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.835           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.335           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.560           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.636           ms/op
ClientSimple.createUser:createUser·p0.999   sample         13.976           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.226           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.237           ms/op
ClientSimple.existUser                      sample  15770   2.020 ± 0.032   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.651           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.915           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.458           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.638           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.358           ms/op
ClientSimple.existUser:existUser·p0.999     sample         22.086           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         22.886           ms/op
ClientSimple.existUser:existUser·p1.00      sample         22.905           ms/op
ClientSimple.getUser                        sample  17053   1.888 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.597           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.835           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.531           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.707           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.150           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.335           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.917           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.009           ms/op
ClientSimple.listUser                       sample  10799   2.956 ± 0.019   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.670           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.789           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.764           ms/op
ClientSimple.listUser:listUser·p0.95        sample          3.985           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.087           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.244           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          6.791           ms/op
ClientSimple.listUser:listUser·p1.00        sample          6.791           ms/op

Benchmark result is saved to 1711412063343.json
