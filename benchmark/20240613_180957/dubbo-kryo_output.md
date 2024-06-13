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
# Warmup Iteration   1: 1.853 ops/ms
Iteration   1: 7.537 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.537 ops/ms


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
# Warmup Iteration   1: 6.570 ops/ms
Iteration   1: 12.368 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.368 ops/ms


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
# Warmup Iteration   1: 5.126 ops/ms
Iteration   1: 10.811 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.811 ops/ms


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
# Warmup Iteration   1: 5.257 ops/ms
Iteration   1: 9.944 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.944 ops/ms


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
# Warmup Iteration   1: 3.863 ±(99.9%) 0.073 ms/op
Iteration   1: 2.406 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.406 ms/op


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
# Warmup Iteration   1: 3.130 ±(99.9%) 0.041 ms/op
Iteration   1: 1.840 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.840 ms/op


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
# Warmup Iteration   1: 3.323 ±(99.9%) 0.073 ms/op
Iteration   1: 2.020 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.020 ms/op


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
# Warmup Iteration   1: 4.736 ±(99.9%) 0.118 ms/op
Iteration   1: 3.210 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.210 ms/op


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
# Warmup Iteration   1: 3.946 ±(99.9%) 0.115 ms/op
Iteration   1: 2.136 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.690 ms/op
                 createUser·p0.50:   1.966 ms/op
                 createUser·p0.90:   2.703 ms/op
                 createUser·p0.95:   2.855 ms/op
                 createUser·p0.99:   6.861 ms/op
                 createUser·p0.999:  19.859 ms/op
                 createUser·p0.9999: 21.054 ms/op
                 createUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14942
  mean =      2.136 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12528 
    [ 2.500,  5.000) = 2209 
    [ 5.000,  7.500) = 76 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.690 ms/op
     p(50.0000) =      1.966 ms/op
     p(90.0000) =      2.703 ms/op
     p(95.0000) =      2.855 ms/op
     p(99.0000) =      6.861 ms/op
     p(99.9000) =     19.859 ms/op
     p(99.9900) =     21.054 ms/op
     p(99.9990) =     21.135 ms/op
     p(99.9999) =     21.135 ms/op
    p(100.0000) =     21.135 ms/op


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
# Warmup Iteration   1: 3.054 ±(99.9%) 0.072 ms/op
Iteration   1: 1.930 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.732 ms/op
                 existUser·p0.50:   1.837 ms/op
                 existUser·p0.90:   2.257 ms/op
                 existUser·p0.95:   2.463 ms/op
                 existUser·p0.99:   4.014 ms/op
                 existUser·p0.999:  13.754 ms/op
                 existUser·p0.9999: 14.075 ms/op
                 existUser·p1.00:   14.107 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16532
  mean =      1.930 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 197 
    [ 1.250,  2.500) = 15575 
    [ 2.500,  3.750) = 527 
    [ 3.750,  5.000) = 136 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.732 ms/op
     p(50.0000) =      1.837 ms/op
     p(90.0000) =      2.257 ms/op
     p(95.0000) =      2.463 ms/op
     p(99.0000) =      4.014 ms/op
     p(99.9000) =     13.754 ms/op
     p(99.9900) =     14.075 ms/op
     p(99.9990) =     14.107 ms/op
     p(99.9999) =     14.107 ms/op
    p(100.0000) =     14.107 ms/op


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
# Warmup Iteration   1: 3.643 ±(99.9%) 0.100 ms/op
Iteration   1: 1.911 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.863 ms/op
                 getUser·p0.50:   1.794 ms/op
                 getUser·p0.90:   2.318 ms/op
                 getUser·p0.95:   2.564 ms/op
                 getUser·p0.99:   3.334 ms/op
                 getUser·p0.999:  13.730 ms/op
                 getUser·p0.9999: 13.958 ms/op
                 getUser·p1.00:   14.090 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16736
  mean =      1.911 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 15692 
    [ 2.500,  3.750) = 841 
    [ 3.750,  5.000) = 39 
    [ 5.000,  6.250) = 72 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      1.794 ms/op
     p(90.0000) =      2.318 ms/op
     p(95.0000) =      2.564 ms/op
     p(99.0000) =      3.334 ms/op
     p(99.9000) =     13.730 ms/op
     p(99.9900) =     13.958 ms/op
     p(99.9990) =     14.090 ms/op
     p(99.9999) =     14.090 ms/op
    p(100.0000) =     14.090 ms/op


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
# Warmup Iteration   1: 4.068 ±(99.9%) 0.116 ms/op
Iteration   1: 3.619 ±(99.9%) 0.075 ms/op
                 listUser·p0.00:   0.888 ms/op
                 listUser·p0.50:   3.432 ms/op
                 listUser·p0.90:   4.678 ms/op
                 listUser·p0.95:   5.038 ms/op
                 listUser·p0.99:   5.874 ms/op
                 listUser·p0.999:  36.372 ms/op
                 listUser·p0.9999: 36.438 ms/op
                 listUser·p1.00:   36.438 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8825
  mean =      3.619 ±(99.9%) 0.075 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1187 
    [ 2.500,  5.000) = 7181 
    [ 5.000,  7.500) = 425 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.888 ms/op
     p(50.0000) =      3.432 ms/op
     p(90.0000) =      4.678 ms/op
     p(95.0000) =      5.038 ms/op
     p(99.0000) =      5.874 ms/op
     p(99.9000) =     36.372 ms/op
     p(99.9900) =     36.438 ms/op
     p(99.9990) =     36.438 ms/op
     p(99.9999) =     36.438 ms/op
    p(100.0000) =     36.438 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.537          ops/ms
ClientSimple.existUser                       thrpt         12.368          ops/ms
ClientSimple.getUser                         thrpt         10.811          ops/ms
ClientSimple.listUser                        thrpt          9.944          ops/ms
ClientSimple.createUser                       avgt          2.406           ms/op
ClientSimple.existUser                        avgt          1.840           ms/op
ClientSimple.getUser                          avgt          2.020           ms/op
ClientSimple.listUser                         avgt          3.210           ms/op
ClientSimple.createUser                     sample  14942   2.136 ± 0.036   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.690           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.966           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.703           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.855           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.861           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.859           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.054           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.135           ms/op
ClientSimple.existUser                      sample  16532   1.930 ± 0.020   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.732           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.837           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.257           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.463           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.014           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.754           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.075           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.107           ms/op
ClientSimple.getUser                        sample  16736   1.911 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.863           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.794           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.318           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.564           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.334           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.730           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.958           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.090           ms/op
ClientSimple.listUser                       sample   8825   3.619 ± 0.075   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.888           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.432           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.678           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.038           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.874           ms/op
ClientSimple.listUser:listUser·p0.999       sample         36.372           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         36.438           ms/op
ClientSimple.listUser:listUser·p1.00        sample         36.438           ms/op

Benchmark result is saved to 1718301925922.json
