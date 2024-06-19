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
# Warmup Iteration   1: 1.827 ops/ms
Iteration   1: 6.290 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.290 ops/ms


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
# Warmup Iteration   1: 6.869 ops/ms
Iteration   1: 12.772 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.772 ops/ms


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
# Warmup Iteration   1: 4.965 ops/ms
Iteration   1: 11.618 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.618 ops/ms


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
# Warmup Iteration   1: 4.351 ops/ms
Iteration   1: 8.138 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.138 ops/ms


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
# Warmup Iteration   1: 4.002 ±(99.9%) 0.075 ms/op
Iteration   1: 2.478 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.478 ms/op


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
# Warmup Iteration   1: 3.626 ±(99.9%) 0.068 ms/op
Iteration   1: 1.889 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.889 ms/op


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
# Warmup Iteration   1: 3.262 ±(99.9%) 0.063 ms/op
Iteration   1: 2.275 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.275 ms/op


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
# Warmup Iteration   1: 4.703 ±(99.9%) 0.105 ms/op
Iteration   1: 3.218 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.218 ms/op


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
# Warmup Iteration   1: 3.443 ±(99.9%) 0.085 ms/op
Iteration   1: 2.396 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   0.643 ms/op
                 createUser·p0.50:   2.249 ms/op
                 createUser·p0.90:   2.895 ms/op
                 createUser·p0.95:   3.184 ms/op
                 createUser·p0.99:   8.618 ms/op
                 createUser·p0.999:  18.317 ms/op
                 createUser·p0.9999: 18.798 ms/op
                 createUser·p1.00:   18.809 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13332
  mean =      2.396 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 352 
    [ 1.250,  2.500) = 8720 
    [ 2.500,  3.750) = 3836 
    [ 3.750,  5.000) = 146 
    [ 5.000,  6.250) = 77 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 39 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.643 ms/op
     p(50.0000) =      2.249 ms/op
     p(90.0000) =      2.895 ms/op
     p(95.0000) =      3.184 ms/op
     p(99.0000) =      8.618 ms/op
     p(99.9000) =     18.317 ms/op
     p(99.9900) =     18.798 ms/op
     p(99.9990) =     18.809 ms/op
     p(99.9999) =     18.809 ms/op
    p(100.0000) =     18.809 ms/op


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
# Warmup Iteration   1: 2.847 ±(99.9%) 0.058 ms/op
Iteration   1: 1.932 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.508 ms/op
                 existUser·p0.50:   1.839 ms/op
                 existUser·p0.90:   2.318 ms/op
                 existUser·p0.95:   2.519 ms/op
                 existUser·p0.99:   3.375 ms/op
                 existUser·p0.999:  23.312 ms/op
                 existUser·p0.9999: 24.456 ms/op
                 existUser·p1.00:   24.478 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16570
  mean =      1.932 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15698 
    [ 2.500,  5.000) = 776 
    [ 5.000,  7.500) = 32 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.508 ms/op
     p(50.0000) =      1.839 ms/op
     p(90.0000) =      2.318 ms/op
     p(95.0000) =      2.519 ms/op
     p(99.0000) =      3.375 ms/op
     p(99.9000) =     23.312 ms/op
     p(99.9900) =     24.456 ms/op
     p(99.9990) =     24.478 ms/op
     p(99.9999) =     24.478 ms/op
    p(100.0000) =     24.478 ms/op


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
# Warmup Iteration   1: 3.515 ±(99.9%) 0.095 ms/op
Iteration   1: 2.356 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.652 ms/op
                 getUser·p0.50:   2.269 ms/op
                 getUser·p0.90:   2.826 ms/op
                 getUser·p0.95:   3.072 ms/op
                 getUser·p0.99:   4.551 ms/op
                 getUser·p0.999:  17.760 ms/op
                 getUser·p0.9999: 17.943 ms/op
                 getUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13570
  mean =      2.356 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 76 
    [ 1.250,  2.500) = 9392 
    [ 2.500,  3.750) = 3908 
    [ 3.750,  5.000) = 115 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.652 ms/op
     p(50.0000) =      2.269 ms/op
     p(90.0000) =      2.826 ms/op
     p(95.0000) =      3.072 ms/op
     p(99.0000) =      4.551 ms/op
     p(99.9000) =     17.760 ms/op
     p(99.9900) =     17.943 ms/op
     p(99.9990) =     17.990 ms/op
     p(99.9999) =     17.990 ms/op
    p(100.0000) =     17.990 ms/op


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
# Warmup Iteration   1: 4.653 ±(99.9%) 0.121 ms/op
Iteration   1: 3.341 ±(99.9%) 0.050 ms/op
                 listUser·p0.00:   1.366 ms/op
                 listUser·p0.50:   3.101 ms/op
                 listUser·p0.90:   4.030 ms/op
                 listUser·p0.95:   4.252 ms/op
                 listUser·p0.99:   6.021 ms/op
                 listUser·p0.999:  26.771 ms/op
                 listUser·p0.9999: 27.197 ms/op
                 listUser·p1.00:   27.197 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9510
  mean =      3.341 ±(99.9%) 0.050 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 446 
    [ 2.500,  5.000) = 8930 
    [ 5.000,  7.500) = 62 
    [ 7.500, 10.000) = 15 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.366 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      6.021 ms/op
     p(99.9000) =     26.771 ms/op
     p(99.9900) =     27.197 ms/op
     p(99.9990) =     27.197 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.290          ops/ms
ClientSimple.existUser                       thrpt         12.772          ops/ms
ClientSimple.getUser                         thrpt         11.618          ops/ms
ClientSimple.listUser                        thrpt          8.138          ops/ms
ClientSimple.createUser                       avgt          2.478           ms/op
ClientSimple.existUser                        avgt          1.889           ms/op
ClientSimple.getUser                          avgt          2.275           ms/op
ClientSimple.listUser                         avgt          3.218           ms/op
ClientSimple.createUser                     sample  13332   2.396 ± 0.038   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.643           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.249           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.895           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.184           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.618           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.317           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.798           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.809           ms/op
ClientSimple.existUser                      sample  16570   1.932 ± 0.029   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.508           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.839           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.318           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.519           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.375           ms/op
ClientSimple.existUser:existUser·p0.999     sample         23.312           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         24.456           ms/op
ClientSimple.existUser:existUser·p1.00      sample         24.478           ms/op
ClientSimple.getUser                        sample  13570   2.356 ± 0.026   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.652           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.269           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.826           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.072           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.551           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.760           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.943           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.990           ms/op
ClientSimple.listUser                       sample   9510   3.341 ± 0.050   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.366           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.101           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.030           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.252           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.021           ms/op
ClientSimple.listUser:listUser·p0.999       sample         26.771           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         27.197           ms/op
ClientSimple.listUser:listUser·p1.00        sample         27.197           ms/op

Benchmark result is saved to 1718756163053.json
