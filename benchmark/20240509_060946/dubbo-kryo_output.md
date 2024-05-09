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
# Warmup Iteration   1: 2.106 ops/ms
Iteration   1: 8.156 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  8.156 ops/ms


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
# Warmup Iteration   1: 6.057 ops/ms
Iteration   1: 12.413 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.413 ops/ms


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
# Warmup Iteration   1: 6.373 ops/ms
Iteration   1: 13.313 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.313 ops/ms


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
# Warmup Iteration   1: 4.424 ops/ms
Iteration   1: 7.810 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.810 ops/ms


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
# Warmup Iteration   1: 3.761 ±(99.9%) 0.066 ms/op
Iteration   1: 2.092 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.092 ms/op


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
# Warmup Iteration   1: 3.608 ±(99.9%) 0.050 ms/op
Iteration   1: 1.867 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.867 ms/op


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
# Warmup Iteration   1: 3.494 ±(99.9%) 0.058 ms/op
Iteration   1: 2.226 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.226 ms/op


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
# Warmup Iteration   1: 4.262 ±(99.9%) 0.081 ms/op
Iteration   1: 3.301 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.301 ms/op


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
# Warmup Iteration   1: 3.457 ±(99.9%) 0.090 ms/op
Iteration   1: 2.295 ±(99.9%) 0.042 ms/op
                 createUser·p0.00:   0.720 ms/op
                 createUser·p0.50:   2.060 ms/op
                 createUser·p0.90:   2.650 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   11.475 ms/op
                 createUser·p0.999:  18.809 ms/op
                 createUser·p0.9999: 18.940 ms/op
                 createUser·p1.00:   18.940 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13980
  mean =      2.295 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 194 
    [ 1.250,  2.500) = 11581 
    [ 2.500,  3.750) = 1711 
    [ 3.750,  5.000) = 137 
    [ 5.000,  6.250) = 96 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 47 
    [ 8.750, 10.000) = 22 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.720 ms/op
     p(50.0000) =      2.060 ms/op
     p(90.0000) =      2.650 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =     11.475 ms/op
     p(99.9000) =     18.809 ms/op
     p(99.9900) =     18.940 ms/op
     p(99.9990) =     18.940 ms/op
     p(99.9999) =     18.940 ms/op
    p(100.0000) =     18.940 ms/op


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
# Warmup Iteration   1: 2.975 ±(99.9%) 0.071 ms/op
Iteration   1: 1.841 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.426 ms/op
                 existUser·p0.50:   1.774 ms/op
                 existUser·p0.90:   2.257 ms/op
                 existUser·p0.95:   2.454 ms/op
                 existUser·p0.99:   4.107 ms/op
                 existUser·p0.999:  6.252 ms/op
                 existUser·p0.9999: 7.425 ms/op
                 existUser·p1.00:   7.463 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17714
  mean =      1.841 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 1 
    [0.500, 1.000) = 63 
    [1.000, 1.500) = 2723 
    [1.500, 2.000) = 10828 
    [2.000, 2.500) = 3360 
    [2.500, 3.000) = 507 
    [3.000, 3.500) = 32 
    [3.500, 4.000) = 8 
    [4.000, 4.500) = 22 
    [4.500, 5.000) = 19 
    [5.000, 5.500) = 87 
    [5.500, 6.000) = 38 
    [6.000, 6.500) = 9 
    [6.500, 7.000) = 1 
    [7.000, 7.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.426 ms/op
     p(50.0000) =      1.774 ms/op
     p(90.0000) =      2.257 ms/op
     p(95.0000) =      2.454 ms/op
     p(99.0000) =      4.107 ms/op
     p(99.9000) =      6.252 ms/op
     p(99.9900) =      7.425 ms/op
     p(99.9990) =      7.463 ms/op
     p(99.9999) =      7.463 ms/op
    p(100.0000) =      7.463 ms/op


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
# Warmup Iteration   1: 4.152 ±(99.9%) 0.138 ms/op
Iteration   1: 2.470 ±(99.9%) 0.032 ms/op
                 getUser·p0.00:   0.750 ms/op
                 getUser·p0.50:   2.380 ms/op
                 getUser·p0.90:   2.949 ms/op
                 getUser·p0.95:   3.240 ms/op
                 getUser·p0.99:   4.961 ms/op
                 getUser·p0.999:  18.285 ms/op
                 getUser·p0.9999: 18.560 ms/op
                 getUser·p1.00:   18.579 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 12970
  mean =      2.470 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 116 
    [ 1.250,  2.500) = 7877 
    [ 2.500,  3.750) = 4726 
    [ 3.750,  5.000) = 128 
    [ 5.000,  6.250) = 15 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 21 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.750 ms/op
     p(50.0000) =      2.380 ms/op
     p(90.0000) =      2.949 ms/op
     p(95.0000) =      3.240 ms/op
     p(99.0000) =      4.961 ms/op
     p(99.9000) =     18.285 ms/op
     p(99.9900) =     18.560 ms/op
     p(99.9990) =     18.579 ms/op
     p(99.9999) =     18.579 ms/op
    p(100.0000) =     18.579 ms/op


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
# Warmup Iteration   1: 5.017 ±(99.9%) 0.149 ms/op
Iteration   1: 3.355 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.061 ms/op
                 listUser·p0.50:   3.256 ms/op
                 listUser·p0.90:   4.182 ms/op
                 listUser·p0.95:   4.501 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  11.108 ms/op
                 listUser·p0.9999: 11.141 ms/op
                 listUser·p1.00:   11.141 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9531
  mean =      3.355 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 680 
    [ 2.500,  3.750) = 6259 
    [ 3.750,  5.000) = 2377 
    [ 5.000,  6.250) = 168 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.061 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      4.182 ms/op
     p(95.0000) =      4.501 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =     11.108 ms/op
     p(99.9900) =     11.141 ms/op
     p(99.9990) =     11.141 ms/op
     p(99.9999) =     11.141 ms/op
    p(100.0000) =     11.141 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          8.156          ops/ms
ClientSimple.existUser                       thrpt         12.413          ops/ms
ClientSimple.getUser                         thrpt         13.313          ops/ms
ClientSimple.listUser                        thrpt          7.810          ops/ms
ClientSimple.createUser                       avgt          2.092           ms/op
ClientSimple.existUser                        avgt          1.867           ms/op
ClientSimple.getUser                          avgt          2.226           ms/op
ClientSimple.listUser                         avgt          3.301           ms/op
ClientSimple.createUser                     sample  13980   2.295 ± 0.042   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.720           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.060           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.650           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.150           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.475           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.809           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.940           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.940           ms/op
ClientSimple.existUser                      sample  17714   1.841 ± 0.012   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.426           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.774           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.257           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.454           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.107           ms/op
ClientSimple.existUser:existUser·p0.999     sample          6.252           ms/op
ClientSimple.existUser:existUser·p0.9999    sample          7.425           ms/op
ClientSimple.existUser:existUser·p1.00      sample          7.463           ms/op
ClientSimple.getUser                        sample  12970   2.470 ± 0.032   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.750           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.380           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.949           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.240           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.961           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.285           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.560           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.579           ms/op
ClientSimple.listUser                       sample   9531   3.355 ± 0.027   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.061           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.256           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.182           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.501           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.571           ms/op
ClientSimple.listUser:listUser·p0.999       sample         11.108           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         11.141           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.141           ms/op

Benchmark result is saved to 1715234737285.json
