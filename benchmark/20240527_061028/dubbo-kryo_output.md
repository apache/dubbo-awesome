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
# Warmup Iteration   1: 1.708 ops/ms
Iteration   1: 7.102 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.102 ops/ms


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
# Warmup Iteration   1: 6.322 ops/ms
Iteration   1: 11.205 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.205 ops/ms


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
# Warmup Iteration   1: 4.945 ops/ms
Iteration   1: 12.888 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.888 ops/ms


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
# Warmup Iteration   1: 5.398 ops/ms
Iteration   1: 8.608 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.608 ops/ms


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
# Warmup Iteration   1: 3.831 ±(99.9%) 0.070 ms/op
Iteration   1: 2.088 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.088 ms/op


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
# Warmup Iteration   1: 3.257 ±(99.9%) 0.057 ms/op
Iteration   1: 1.972 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.972 ms/op


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
# Warmup Iteration   1: 3.160 ±(99.9%) 0.059 ms/op
Iteration   1: 1.973 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.973 ms/op


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
# Warmup Iteration   1: 4.335 ±(99.9%) 0.088 ms/op
Iteration   1: 3.572 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.572 ms/op


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
# Warmup Iteration   1: 3.420 ±(99.9%) 0.082 ms/op
Iteration   1: 2.024 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.437 ms/op
                 createUser·p0.50:   1.786 ms/op
                 createUser·p0.90:   2.499 ms/op
                 createUser·p0.95:   2.740 ms/op
                 createUser·p0.99:   7.522 ms/op
                 createUser·p0.999:  14.991 ms/op
                 createUser·p0.9999: 15.923 ms/op
                 createUser·p1.00:   15.991 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15875
  mean =      2.024 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 226 
    [ 1.250,  2.500) = 14076 
    [ 2.500,  3.750) = 1292 
    [ 3.750,  5.000) = 60 
    [ 5.000,  6.250) = 28 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.437 ms/op
     p(50.0000) =      1.786 ms/op
     p(90.0000) =      2.499 ms/op
     p(95.0000) =      2.740 ms/op
     p(99.0000) =      7.522 ms/op
     p(99.9000) =     14.991 ms/op
     p(99.9900) =     15.923 ms/op
     p(99.9990) =     15.991 ms/op
     p(99.9999) =     15.991 ms/op
    p(100.0000) =     15.991 ms/op


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
# Warmup Iteration   1: 3.060 ±(99.9%) 0.078 ms/op
Iteration   1: 1.700 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.483 ms/op
                 existUser·p0.50:   1.679 ms/op
                 existUser·p0.90:   2.159 ms/op
                 existUser·p0.95:   2.281 ms/op
                 existUser·p0.99:   2.843 ms/op
                 existUser·p0.999:  19.979 ms/op
                 existUser·p0.9999: 22.821 ms/op
                 existUser·p1.00:   23.560 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 19022
  mean =      1.700 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18652 
    [ 2.500,  5.000) = 330 
    [ 5.000,  7.500) = 7 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.483 ms/op
     p(50.0000) =      1.679 ms/op
     p(90.0000) =      2.159 ms/op
     p(95.0000) =      2.281 ms/op
     p(99.0000) =      2.843 ms/op
     p(99.9000) =     19.979 ms/op
     p(99.9900) =     22.821 ms/op
     p(99.9990) =     23.560 ms/op
     p(99.9999) =     23.560 ms/op
    p(100.0000) =     23.560 ms/op


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
# Warmup Iteration   1: 3.476 ±(99.9%) 0.095 ms/op
Iteration   1: 2.047 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.856 ms/op
                 getUser·p0.50:   1.898 ms/op
                 getUser·p0.90:   2.396 ms/op
                 getUser·p0.95:   2.662 ms/op
                 getUser·p0.99:   5.062 ms/op
                 getUser·p0.999:  18.002 ms/op
                 getUser·p0.9999: 18.703 ms/op
                 getUser·p1.00:   18.776 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15609
  mean =      2.047 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 38 
    [ 1.250,  2.500) = 14334 
    [ 2.500,  3.750) = 1040 
    [ 3.750,  5.000) = 37 
    [ 5.000,  6.250) = 81 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.856 ms/op
     p(50.0000) =      1.898 ms/op
     p(90.0000) =      2.396 ms/op
     p(95.0000) =      2.662 ms/op
     p(99.0000) =      5.062 ms/op
     p(99.9000) =     18.002 ms/op
     p(99.9900) =     18.703 ms/op
     p(99.9990) =     18.776 ms/op
     p(99.9999) =     18.776 ms/op
    p(100.0000) =     18.776 ms/op


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
# Warmup Iteration   1: 4.632 ±(99.9%) 0.132 ms/op
Iteration   1: 3.547 ±(99.9%) 0.053 ms/op
                 listUser·p0.00:   1.380 ms/op
                 listUser·p0.50:   3.371 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   7.137 ms/op
                 listUser·p0.999:  23.101 ms/op
                 listUser·p0.9999: 23.691 ms/op
                 listUser·p1.00:   23.691 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9068
  mean =      3.547 ±(99.9%) 0.053 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 445 
    [ 2.500,  5.000) = 8358 
    [ 5.000,  7.500) = 198 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.380 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      7.137 ms/op
     p(99.9000) =     23.101 ms/op
     p(99.9900) =     23.691 ms/op
     p(99.9990) =     23.691 ms/op
     p(99.9999) =     23.691 ms/op
    p(100.0000) =     23.691 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.102          ops/ms
ClientSimple.existUser                       thrpt         11.205          ops/ms
ClientSimple.getUser                         thrpt         12.888          ops/ms
ClientSimple.listUser                        thrpt          8.608          ops/ms
ClientSimple.createUser                       avgt          2.088           ms/op
ClientSimple.existUser                        avgt          1.972           ms/op
ClientSimple.getUser                          avgt          1.973           ms/op
ClientSimple.listUser                         avgt          3.572           ms/op
ClientSimple.createUser                     sample  15875   2.024 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.437           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.786           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.499           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.740           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.522           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.991           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.923           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.991           ms/op
ClientSimple.existUser                      sample  19022   1.700 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.483           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.679           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.159           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.281           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.843           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.979           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         22.821           ms/op
ClientSimple.existUser:existUser·p1.00      sample         23.560           ms/op
ClientSimple.getUser                        sample  15609   2.047 ± 0.025   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.856           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.898           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.396           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.662           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.062           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.002           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.703           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.776           ms/op
ClientSimple.listUser                       sample   9068   3.547 ± 0.053   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.380           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.371           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.260           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.514           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.137           ms/op
ClientSimple.listUser:listUser·p0.999       sample         23.101           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         23.691           ms/op
ClientSimple.listUser:listUser·p1.00        sample         23.691           ms/op

Benchmark result is saved to 1716789983061.json
