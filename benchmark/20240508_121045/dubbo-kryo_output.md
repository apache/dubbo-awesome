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
# Warmup Iteration   1: 1.756 ops/ms
Iteration   1: 6.629 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.629 ops/ms


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
# Warmup Iteration   1: 5.624 ops/ms
Iteration   1: 12.611 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.611 ops/ms


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
# Warmup Iteration   1: 5.214 ops/ms
Iteration   1: 10.057 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.057 ops/ms


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
# Warmup Iteration   1: 4.250 ops/ms
Iteration   1: 8.288 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.288 ops/ms


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
# Warmup Iteration   1: 4.166 ±(99.9%) 0.073 ms/op
Iteration   1: 2.155 ±(99.9%) 0.015 ms/op


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
# Warmup Iteration   1: 3.058 ±(99.9%) 0.066 ms/op
Iteration   1: 1.809 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.809 ms/op


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
# Warmup Iteration   1: 3.227 ±(99.9%) 0.059 ms/op
Iteration   1: 2.122 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.122 ms/op


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
# Warmup Iteration   1: 4.569 ±(99.9%) 0.107 ms/op
Iteration   1: 3.436 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.436 ms/op


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
# Warmup Iteration   1: 3.482 ±(99.9%) 0.107 ms/op
Iteration   1: 2.118 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.703 ms/op
                 createUser·p0.50:   2.034 ms/op
                 createUser·p0.90:   2.593 ms/op
                 createUser·p0.95:   2.773 ms/op
                 createUser·p0.99:   4.141 ms/op
                 createUser·p0.999:  24.478 ms/op
                 createUser·p0.9999: 25.621 ms/op
                 createUser·p1.00:   25.788 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15103
  mean =      2.118 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12968 
    [ 2.500,  5.000) = 2063 
    [ 5.000,  7.500) = 3 
    [ 7.500, 10.000) = 37 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.703 ms/op
     p(50.0000) =      2.034 ms/op
     p(90.0000) =      2.593 ms/op
     p(95.0000) =      2.773 ms/op
     p(99.0000) =      4.141 ms/op
     p(99.9000) =     24.478 ms/op
     p(99.9900) =     25.621 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.701 ±(99.9%) 0.056 ms/op
Iteration   1: 1.865 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.607 ms/op
                 existUser·p0.50:   1.825 ms/op
                 existUser·p0.90:   2.306 ms/op
                 existUser·p0.95:   2.507 ms/op
                 existUser·p0.99:   3.010 ms/op
                 existUser·p0.999:  10.893 ms/op
                 existUser·p0.9999: 11.523 ms/op
                 existUser·p1.00:   11.534 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17117
  mean =      1.865 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 697 
    [ 1.250,  2.500) = 15548 
    [ 2.500,  3.750) = 749 
    [ 3.750,  5.000) = 76 
    [ 5.000,  6.250) = 14 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.607 ms/op
     p(50.0000) =      1.825 ms/op
     p(90.0000) =      2.306 ms/op
     p(95.0000) =      2.507 ms/op
     p(99.0000) =      3.010 ms/op
     p(99.9000) =     10.893 ms/op
     p(99.9900) =     11.523 ms/op
     p(99.9990) =     11.534 ms/op
     p(99.9999) =     11.534 ms/op
    p(100.0000) =     11.534 ms/op


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
# Warmup Iteration   1: 3.201 ±(99.9%) 0.087 ms/op
Iteration   1: 2.203 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.780 ms/op
                 getUser·p0.50:   2.114 ms/op
                 getUser·p0.90:   2.871 ms/op
                 getUser·p0.95:   3.076 ms/op
                 getUser·p0.99:   4.202 ms/op
                 getUser·p0.999:  10.281 ms/op
                 getUser·p0.9999: 11.223 ms/op
                 getUser·p1.00:   11.223 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14499
  mean =      2.203 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 290 
    [ 1.250,  2.500) = 10425 
    [ 2.500,  3.750) = 3556 
    [ 3.750,  5.000) = 131 
    [ 5.000,  6.250) = 34 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.780 ms/op
     p(50.0000) =      2.114 ms/op
     p(90.0000) =      2.871 ms/op
     p(95.0000) =      3.076 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =     10.281 ms/op
     p(99.9900) =     11.223 ms/op
     p(99.9990) =     11.223 ms/op
     p(99.9999) =     11.223 ms/op
    p(100.0000) =     11.223 ms/op


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
# Warmup Iteration   1: 4.274 ±(99.9%) 0.123 ms/op
Iteration   1: 3.378 ±(99.9%) 0.044 ms/op
                 listUser·p0.00:   0.888 ms/op
                 listUser·p0.50:   3.285 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   6.802 ms/op
                 listUser·p0.999:  21.336 ms/op
                 listUser·p0.9999: 22.610 ms/op
                 listUser·p1.00:   22.610 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9472
  mean =      3.378 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 966 
    [ 2.500,  5.000) = 8126 
    [ 5.000,  7.500) = 348 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.888 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      6.802 ms/op
     p(99.9000) =     21.336 ms/op
     p(99.9900) =     22.610 ms/op
     p(99.9990) =     22.610 ms/op
     p(99.9999) =     22.610 ms/op
    p(100.0000) =     22.610 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.629          ops/ms
ClientSimple.existUser                       thrpt         12.611          ops/ms
ClientSimple.getUser                         thrpt         10.057          ops/ms
ClientSimple.listUser                        thrpt          8.288          ops/ms
ClientSimple.createUser                       avgt          2.155           ms/op
ClientSimple.existUser                        avgt          1.809           ms/op
ClientSimple.getUser                          avgt          2.122           ms/op
ClientSimple.listUser                         avgt          3.436           ms/op
ClientSimple.createUser                     sample  15103   2.118 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.703           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.034           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.593           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.773           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.141           ms/op
ClientSimple.createUser:createUser·p0.999   sample         24.478           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         25.621           ms/op
ClientSimple.createUser:createUser·p1.00    sample         25.788           ms/op
ClientSimple.existUser                      sample  17117   1.865 ± 0.014   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.607           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.825           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.306           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.507           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.010           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.893           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.523           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.534           ms/op
ClientSimple.getUser                        sample  14499   2.203 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.780           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.114           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.871           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.076           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.202           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.281           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.223           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.223           ms/op
ClientSimple.listUser                       sample   9472   3.378 ± 0.044   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.888           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.285           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.202           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.751           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.802           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.336           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         22.610           ms/op
ClientSimple.listUser:listUser·p1.00        sample         22.610           ms/op

Benchmark result is saved to 1715169984184.json
