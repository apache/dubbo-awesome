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
# Warmup Iteration   1: 1.688 ops/ms
Iteration   1: 7.032 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.032 ops/ms


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
# Warmup Iteration   1: 6.489 ops/ms
Iteration   1: 12.565 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.565 ops/ms


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
# Warmup Iteration   1: 4.846 ops/ms
Iteration   1: 12.012 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.483 ops/ms
Iteration   1: 8.469 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.469 ops/ms


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
# Warmup Iteration   1: 4.260 ±(99.9%) 0.092 ms/op
Iteration   1: 2.191 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.191 ms/op


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
# Warmup Iteration   1: 3.215 ±(99.9%) 0.054 ms/op
Iteration   1: 1.755 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.755 ms/op


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
# Warmup Iteration   1: 3.557 ±(99.9%) 0.062 ms/op
Iteration   1: 2.112 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.112 ms/op


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
# Warmup Iteration   1: 5.320 ±(99.9%) 0.116 ms/op
Iteration   1: 3.444 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.444 ms/op


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
# Warmup Iteration   1: 3.673 ±(99.9%) 0.092 ms/op
Iteration   1: 2.391 ±(99.9%) 0.042 ms/op
                 createUser·p0.00:   0.751 ms/op
                 createUser·p0.50:   2.118 ms/op
                 createUser·p0.90:   2.912 ms/op
                 createUser·p0.95:   3.269 ms/op
                 createUser·p0.99:   12.026 ms/op
                 createUser·p0.999:  16.052 ms/op
                 createUser·p0.9999: 18.031 ms/op
                 createUser·p1.00:   18.350 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13360
  mean =      2.391 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 17 
    [ 1.250,  2.500) = 10053 
    [ 2.500,  3.750) = 2836 
    [ 3.750,  5.000) = 155 
    [ 5.000,  6.250) = 63 
    [ 6.250,  7.500) = 12 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 50 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.751 ms/op
     p(50.0000) =      2.118 ms/op
     p(90.0000) =      2.912 ms/op
     p(95.0000) =      3.269 ms/op
     p(99.0000) =     12.026 ms/op
     p(99.9000) =     16.052 ms/op
     p(99.9900) =     18.031 ms/op
     p(99.9990) =     18.350 ms/op
     p(99.9999) =     18.350 ms/op
    p(100.0000) =     18.350 ms/op


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
# Warmup Iteration   1: 3.169 ±(99.9%) 0.078 ms/op
Iteration   1: 2.123 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.685 ms/op
                 existUser·p0.50:   1.944 ms/op
                 existUser·p0.90:   2.757 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   4.047 ms/op
                 existUser·p0.999:  13.532 ms/op
                 existUser·p0.9999: 13.721 ms/op
                 existUser·p1.00:   13.730 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15075
  mean =      2.123 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 255 
    [ 1.250,  2.500) = 11934 
    [ 2.500,  3.750) = 2677 
    [ 3.750,  5.000) = 111 
    [ 5.000,  6.250) = 34 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.685 ms/op
     p(50.0000) =      1.944 ms/op
     p(90.0000) =      2.757 ms/op
     p(95.0000) =      3.072 ms/op
     p(99.0000) =      4.047 ms/op
     p(99.9000) =     13.532 ms/op
     p(99.9900) =     13.721 ms/op
     p(99.9990) =     13.730 ms/op
     p(99.9999) =     13.730 ms/op
    p(100.0000) =     13.730 ms/op


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
# Warmup Iteration   1: 3.574 ±(99.9%) 0.117 ms/op
Iteration   1: 1.851 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.861 ms/op
                 getUser·p0.50:   1.694 ms/op
                 getUser·p0.90:   2.429 ms/op
                 getUser·p0.95:   2.654 ms/op
                 getUser·p0.99:   3.949 ms/op
                 getUser·p0.999:  12.728 ms/op
                 getUser·p0.9999: 13.324 ms/op
                 getUser·p1.00:   13.337 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17547
  mean =      1.851 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 69 
    [ 1.250,  2.500) = 16046 
    [ 2.500,  3.750) = 1231 
    [ 3.750,  5.000) = 131 
    [ 5.000,  6.250) = 37 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.861 ms/op
     p(50.0000) =      1.694 ms/op
     p(90.0000) =      2.429 ms/op
     p(95.0000) =      2.654 ms/op
     p(99.0000) =      3.949 ms/op
     p(99.9000) =     12.728 ms/op
     p(99.9900) =     13.324 ms/op
     p(99.9990) =     13.337 ms/op
     p(99.9999) =     13.337 ms/op
    p(100.0000) =     13.337 ms/op


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
# Warmup Iteration   1: 4.668 ±(99.9%) 0.144 ms/op
Iteration   1: 3.178 ±(99.9%) 0.038 ms/op
                 listUser·p0.00:   0.860 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.977 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   6.148 ms/op
                 listUser·p0.999:  19.464 ms/op
                 listUser·p0.9999: 20.280 ms/op
                 listUser·p1.00:   20.283 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10055
  mean =      3.178 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1053 
    [ 2.500,  5.000) = 8837 
    [ 5.000,  7.500) = 100 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.860 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.148 ms/op
     p(99.9000) =     19.464 ms/op
     p(99.9900) =     20.280 ms/op
     p(99.9990) =     20.283 ms/op
     p(99.9999) =     20.283 ms/op
    p(100.0000) =     20.283 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.032          ops/ms
ClientSimple.existUser                       thrpt         12.565          ops/ms
ClientSimple.getUser                         thrpt         12.012          ops/ms
ClientSimple.listUser                        thrpt          8.469          ops/ms
ClientSimple.createUser                       avgt          2.191           ms/op
ClientSimple.existUser                        avgt          1.755           ms/op
ClientSimple.getUser                          avgt          2.112           ms/op
ClientSimple.listUser                         avgt          3.444           ms/op
ClientSimple.createUser                     sample  13360   2.391 ± 0.042   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.751           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.118           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.912           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.269           ms/op
ClientSimple.createUser:createUser·p0.99    sample         12.026           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.052           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.031           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.350           ms/op
ClientSimple.existUser                      sample  15075   2.123 ± 0.024   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.685           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.944           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.757           ms/op
ClientSimple.existUser:existUser·p0.95      sample          3.072           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.047           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.532           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.721           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.730           ms/op
ClientSimple.getUser                        sample  17547   1.851 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.861           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.694           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.429           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.654           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.949           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.728           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.324           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.337           ms/op
ClientSimple.listUser                       sample  10055   3.178 ± 0.038   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.860           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.966           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.977           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.293           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.148           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.464           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.280           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.283           ms/op

Benchmark result is saved to 1718733950149.json
