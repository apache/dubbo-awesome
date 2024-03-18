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
# Warmup Iteration   1: 1.621 ops/ms
Iteration   1: 6.534 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.534 ops/ms


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
# Warmup Iteration   1: 6.738 ops/ms
Iteration   1: 15.392 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  15.392 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.511 ops/ms
Iteration   1: 10.809 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.809 ops/ms


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
# Warmup Iteration   1: 4.158 ops/ms
Iteration   1: 8.351 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.351 ops/ms


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
# Warmup Iteration   1: 4.066 ±(99.9%) 0.070 ms/op
Iteration   1: 2.344 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.344 ms/op


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
# Warmup Iteration   1: 3.712 ±(99.9%) 0.062 ms/op
Iteration   1: 1.989 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.989 ms/op


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
# Warmup Iteration   1: 3.366 ±(99.9%) 0.067 ms/op
Iteration   1: 2.156 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.156 ms/op


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
# Warmup Iteration   1: 4.761 ±(99.9%) 0.110 ms/op
Iteration   1: 3.545 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.545 ms/op


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
# Warmup Iteration   1: 3.600 ±(99.9%) 0.097 ms/op
Iteration   1: 2.206 ±(99.9%) 0.045 ms/op
                 createUser·p0.00:   0.725 ms/op
                 createUser·p0.50:   1.890 ms/op
                 createUser·p0.90:   2.806 ms/op
                 createUser·p0.95:   3.015 ms/op
                 createUser·p0.99:   6.411 ms/op
                 createUser·p0.999:  29.065 ms/op
                 createUser·p0.9999: 29.527 ms/op
                 createUser·p1.00:   29.557 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14493
  mean =      2.206 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11736 
    [ 2.500,  5.000) = 2528 
    [ 5.000,  7.500) = 133 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 20 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.725 ms/op
     p(50.0000) =      1.890 ms/op
     p(90.0000) =      2.806 ms/op
     p(95.0000) =      3.015 ms/op
     p(99.0000) =      6.411 ms/op
     p(99.9000) =     29.065 ms/op
     p(99.9900) =     29.527 ms/op
     p(99.9990) =     29.557 ms/op
     p(99.9999) =     29.557 ms/op
    p(100.0000) =     29.557 ms/op


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
# Warmup Iteration   1: 3.281 ±(99.9%) 0.069 ms/op
Iteration   1: 2.007 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.670 ms/op
                 existUser·p0.50:   1.842 ms/op
                 existUser·p0.90:   2.703 ms/op
                 existUser·p0.95:   2.884 ms/op
                 existUser·p0.99:   3.848 ms/op
                 existUser·p0.999:  11.256 ms/op
                 existUser·p0.9999: 11.321 ms/op
                 existUser·p1.00:   11.321 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15942
  mean =      2.007 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 208 
    [ 1.250,  2.500) = 12823 
    [ 2.500,  3.750) = 2729 
    [ 3.750,  5.000) = 119 
    [ 5.000,  6.250) = 29 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.670 ms/op
     p(50.0000) =      1.842 ms/op
     p(90.0000) =      2.703 ms/op
     p(95.0000) =      2.884 ms/op
     p(99.0000) =      3.848 ms/op
     p(99.9000) =     11.256 ms/op
     p(99.9900) =     11.321 ms/op
     p(99.9990) =     11.321 ms/op
     p(99.9999) =     11.321 ms/op
    p(100.0000) =     11.321 ms/op


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
# Warmup Iteration   1: 3.444 ±(99.9%) 0.103 ms/op
Iteration   1: 1.930 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.712 ms/op
                 getUser·p0.50:   1.804 ms/op
                 getUser·p0.90:   2.355 ms/op
                 getUser·p0.95:   2.658 ms/op
                 getUser·p0.99:   4.612 ms/op
                 getUser·p0.999:  11.436 ms/op
                 getUser·p0.9999: 11.567 ms/op
                 getUser·p1.00:   11.567 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16623
  mean =      1.930 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 91 
    [ 1.250,  2.500) = 15299 
    [ 2.500,  3.750) = 942 
    [ 3.750,  5.000) = 172 
    [ 5.000,  6.250) = 54 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.712 ms/op
     p(50.0000) =      1.804 ms/op
     p(90.0000) =      2.355 ms/op
     p(95.0000) =      2.658 ms/op
     p(99.0000) =      4.612 ms/op
     p(99.9000) =     11.436 ms/op
     p(99.9900) =     11.567 ms/op
     p(99.9990) =     11.567 ms/op
     p(99.9999) =     11.567 ms/op
    p(100.0000) =     11.567 ms/op


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
# Warmup Iteration   1: 4.981 ±(99.9%) 0.170 ms/op
Iteration   1: 3.359 ±(99.9%) 0.072 ms/op
                 listUser·p0.00:   1.141 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   4.006 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   13.397 ms/op
                 listUser·p0.999:  28.410 ms/op
                 listUser·p0.9999: 32.375 ms/op
                 listUser·p1.00:   32.375 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9528
  mean =      3.359 ±(99.9%) 0.072 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1042 
    [ 2.500,  5.000) = 8095 
    [ 5.000,  7.500) = 205 
    [ 7.500, 10.000) = 77 
    [10.000, 12.500) = 12 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.141 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      4.006 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =     13.397 ms/op
     p(99.9000) =     28.410 ms/op
     p(99.9900) =     32.375 ms/op
     p(99.9990) =     32.375 ms/op
     p(99.9999) =     32.375 ms/op
    p(100.0000) =     32.375 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.534          ops/ms
ClientSimple.existUser                       thrpt         15.392          ops/ms
ClientSimple.getUser                         thrpt         10.809          ops/ms
ClientSimple.listUser                        thrpt          8.351          ops/ms
ClientSimple.createUser                       avgt          2.344           ms/op
ClientSimple.existUser                        avgt          1.989           ms/op
ClientSimple.getUser                          avgt          2.156           ms/op
ClientSimple.listUser                         avgt          3.545           ms/op
ClientSimple.createUser                     sample  14493   2.206 ± 0.045   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.725           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.890           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.806           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.015           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.411           ms/op
ClientSimple.createUser:createUser·p0.999   sample         29.065           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         29.527           ms/op
ClientSimple.createUser:createUser·p1.00    sample         29.557           ms/op
ClientSimple.existUser                      sample  15942   2.007 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.670           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.842           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.703           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.884           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.848           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.256           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.321           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.321           ms/op
ClientSimple.getUser                        sample  16623   1.930 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.712           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.804           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.355           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.658           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.612           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.436           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.567           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.567           ms/op
ClientSimple.listUser                       sample   9528   3.359 ± 0.072   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.141           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.998           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.006           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.719           ms/op
ClientSimple.listUser:listUser·p0.99        sample         13.397           ms/op
ClientSimple.listUser:listUser·p0.999       sample         28.410           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         32.375           ms/op
ClientSimple.listUser:listUser·p1.00        sample         32.375           ms/op

Benchmark result is saved to 1710742001274.json
