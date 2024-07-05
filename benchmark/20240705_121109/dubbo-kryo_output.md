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
# Warmup Iteration   1: 1.800 ops/ms
Iteration   1: 7.836 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.836 ops/ms


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
# Warmup Iteration   1: 6.627 ops/ms
Iteration   1: 12.534 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.534 ops/ms


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
# Warmup Iteration   1: 5.579 ops/ms
Iteration   1: 12.480 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.480 ops/ms


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
# Warmup Iteration   1: 4.573 ops/ms
Iteration   1: 9.010 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.010 ops/ms


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
# Warmup Iteration   1: 3.706 ±(99.9%) 0.064 ms/op
Iteration   1: 2.255 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.170 ±(99.9%) 0.045 ms/op
Iteration   1: 1.919 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.919 ms/op


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
# Warmup Iteration   1: 3.145 ±(99.9%) 0.053 ms/op
Iteration   1: 2.107 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.107 ms/op


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
# Warmup Iteration   1: 4.632 ±(99.9%) 0.141 ms/op
Iteration   1: 3.949 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.949 ms/op


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
# Warmup Iteration   1: 3.631 ±(99.9%) 0.089 ms/op
Iteration   1: 2.456 ±(99.9%) 0.066 ms/op
                 createUser·p0.00:   0.400 ms/op
                 createUser·p0.50:   2.187 ms/op
                 createUser·p0.90:   2.671 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   12.993 ms/op
                 createUser·p0.999:  42.533 ms/op
                 createUser·p0.9999: 50.640 ms/op
                 createUser·p1.00:   50.659 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13019
  mean =      2.456 ±(99.9%) 0.066 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 12684 
    [ 5.000, 10.000) = 187 
    [10.000, 15.000) = 41 
    [15.000, 20.000) = 72 
    [20.000, 25.000) = 5 
    [25.000, 30.000) = 6 
    [30.000, 35.000) = 5 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 13 
    [45.000, 50.000) = 2 
    [50.000, 55.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.400 ms/op
     p(50.0000) =      2.187 ms/op
     p(90.0000) =      2.671 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =     12.993 ms/op
     p(99.9000) =     42.533 ms/op
     p(99.9900) =     50.640 ms/op
     p(99.9990) =     50.659 ms/op
     p(99.9999) =     50.659 ms/op
    p(100.0000) =     50.659 ms/op


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
# Warmup Iteration   1: 2.785 ±(99.9%) 0.061 ms/op
Iteration   1: 1.889 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.416 ms/op
                 existUser·p0.50:   1.718 ms/op
                 existUser·p0.90:   2.527 ms/op
                 existUser·p0.95:   2.744 ms/op
                 existUser·p0.99:   3.248 ms/op
                 existUser·p0.999:  13.124 ms/op
                 existUser·p0.9999: 13.194 ms/op
                 existUser·p1.00:   13.206 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17049
  mean =      1.889 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 168 
    [ 1.250,  2.500) = 15065 
    [ 2.500,  3.750) = 1675 
    [ 3.750,  5.000) = 72 
    [ 5.000,  6.250) = 31 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.416 ms/op
     p(50.0000) =      1.718 ms/op
     p(90.0000) =      2.527 ms/op
     p(95.0000) =      2.744 ms/op
     p(99.0000) =      3.248 ms/op
     p(99.9000) =     13.124 ms/op
     p(99.9900) =     13.194 ms/op
     p(99.9990) =     13.206 ms/op
     p(99.9999) =     13.206 ms/op
    p(100.0000) =     13.206 ms/op


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
# Warmup Iteration   1: 3.981 ±(99.9%) 0.326 ms/op
Iteration   1: 2.258 ±(99.9%) 0.034 ms/op
                 getUser·p0.00:   0.453 ms/op
                 getUser·p0.50:   2.150 ms/op
                 getUser·p0.90:   2.892 ms/op
                 getUser·p0.95:   3.097 ms/op
                 getUser·p0.99:   4.048 ms/op
                 getUser·p0.999:  23.888 ms/op
                 getUser·p0.9999: 25.705 ms/op
                 getUser·p1.00:   25.788 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14220
  mean =      2.258 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10616 
    [ 2.500,  5.000) = 3526 
    [ 5.000,  7.500) = 14 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.453 ms/op
     p(50.0000) =      2.150 ms/op
     p(90.0000) =      2.892 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =      4.048 ms/op
     p(99.9000) =     23.888 ms/op
     p(99.9900) =     25.705 ms/op
     p(99.9990) =     25.788 ms/op
     p(99.9999) =     25.788 ms/op
    p(100.0000) =     25.788 ms/op


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
# Warmup Iteration   1: 4.259 ±(99.9%) 0.128 ms/op
Iteration   1: 3.401 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   1.079 ms/op
                 listUser·p0.50:   3.277 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   5.014 ms/op
                 listUser·p0.99:   5.849 ms/op
                 listUser·p0.999:  7.301 ms/op
                 listUser·p0.9999: 11.370 ms/op
                 listUser·p1.00:   11.370 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9407
  mean =      3.401 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 926 
    [ 2.500,  3.750) = 5380 
    [ 3.750,  5.000) = 2616 
    [ 5.000,  6.250) = 415 
    [ 6.250,  7.500) = 65 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.079 ms/op
     p(50.0000) =      3.277 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      5.014 ms/op
     p(99.0000) =      5.849 ms/op
     p(99.9000) =      7.301 ms/op
     p(99.9900) =     11.370 ms/op
     p(99.9990) =     11.370 ms/op
     p(99.9999) =     11.370 ms/op
    p(100.0000) =     11.370 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.836          ops/ms
ClientSimple.existUser                       thrpt         12.534          ops/ms
ClientSimple.getUser                         thrpt         12.480          ops/ms
ClientSimple.listUser                        thrpt          9.010          ops/ms
ClientSimple.createUser                       avgt          2.255           ms/op
ClientSimple.existUser                        avgt          1.919           ms/op
ClientSimple.getUser                          avgt          2.107           ms/op
ClientSimple.listUser                         avgt          3.949           ms/op
ClientSimple.createUser                     sample  13019   2.456 ± 0.066   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.400           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.187           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.671           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.154           ms/op
ClientSimple.createUser:createUser·p0.99    sample         12.993           ms/op
ClientSimple.createUser:createUser·p0.999   sample         42.533           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         50.640           ms/op
ClientSimple.createUser:createUser·p1.00    sample         50.659           ms/op
ClientSimple.existUser                      sample  17049   1.889 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.416           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.718           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.527           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.744           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.248           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.124           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.194           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.206           ms/op
ClientSimple.getUser                        sample  14220   2.258 ± 0.034   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.453           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.150           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.892           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.097           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.048           ms/op
ClientSimple.getUser:getUser·p0.999         sample         23.888           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         25.705           ms/op
ClientSimple.getUser:getUser·p1.00          sample         25.788           ms/op
ClientSimple.listUser                       sample   9407   3.401 ± 0.030   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.079           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.277           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.522           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.014           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.849           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.301           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         11.370           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.370           ms/op

Benchmark result is saved to 1720181203153.json
