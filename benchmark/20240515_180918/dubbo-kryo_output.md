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
# Warmup Iteration   1: 0.666 ops/ms
Iteration   1: 5.584 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.584 ops/ms


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
# Warmup Iteration   1: 5.356 ops/ms
Iteration   1: 11.730 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.730 ops/ms


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
# Warmup Iteration   1: 6.378 ops/ms
Iteration   1: 14.030 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.030 ops/ms


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
# Warmup Iteration   1: 4.787 ops/ms
Iteration   1: 8.062 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.062 ops/ms


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
# Warmup Iteration   1: 3.851 ±(99.9%) 0.069 ms/op
Iteration   1: 1.958 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.958 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.175 ±(99.9%) 0.045 ms/op
Iteration   1: 1.619 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.619 ms/op


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
# Warmup Iteration   1: 3.303 ±(99.9%) 0.056 ms/op
Iteration   1: 2.022 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.022 ms/op


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
# Warmup Iteration   1: 4.408 ±(99.9%) 0.085 ms/op
Iteration   1: 3.131 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.131 ms/op


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
# Warmup Iteration   1: 3.388 ±(99.9%) 0.079 ms/op
Iteration   1: 2.083 ±(99.9%) 0.049 ms/op
                 createUser·p0.00:   0.628 ms/op
                 createUser·p0.50:   1.810 ms/op
                 createUser·p0.90:   2.691 ms/op
                 createUser·p0.95:   2.988 ms/op
                 createUser·p0.99:   6.271 ms/op
                 createUser·p0.999:  38.479 ms/op
                 createUser·p0.9999: 39.584 ms/op
                 createUser·p1.00:   39.584 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15427
  mean =      2.083 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12929 
    [ 2.500,  5.000) = 2267 
    [ 5.000,  7.500) = 135 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.628 ms/op
     p(50.0000) =      1.810 ms/op
     p(90.0000) =      2.691 ms/op
     p(95.0000) =      2.988 ms/op
     p(99.0000) =      6.271 ms/op
     p(99.9000) =     38.479 ms/op
     p(99.9900) =     39.584 ms/op
     p(99.9990) =     39.584 ms/op
     p(99.9999) =     39.584 ms/op
    p(100.0000) =     39.584 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.714 ±(99.9%) 0.060 ms/op
Iteration   1: 1.901 ±(99.9%) 0.032 ms/op
                 existUser·p0.00:   0.573 ms/op
                 existUser·p0.50:   1.794 ms/op
                 existUser·p0.90:   2.220 ms/op
                 existUser·p0.95:   2.370 ms/op
                 existUser·p0.99:   3.551 ms/op
                 existUser·p0.999:  21.185 ms/op
                 existUser·p0.9999: 21.648 ms/op
                 existUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16829
  mean =      1.901 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16257 
    [ 2.500,  5.000) = 413 
    [ 5.000,  7.500) = 63 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.573 ms/op
     p(50.0000) =      1.794 ms/op
     p(90.0000) =      2.220 ms/op
     p(95.0000) =      2.370 ms/op
     p(99.0000) =      3.551 ms/op
     p(99.9000) =     21.185 ms/op
     p(99.9900) =     21.648 ms/op
     p(99.9990) =     21.692 ms/op
     p(99.9999) =     21.692 ms/op
    p(100.0000) =     21.692 ms/op


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
# Warmup Iteration   1: 3.049 ±(99.9%) 0.077 ms/op
Iteration   1: 2.016 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.719 ms/op
                 getUser·p0.50:   1.907 ms/op
                 getUser·p0.90:   2.343 ms/op
                 getUser·p0.95:   2.617 ms/op
                 getUser·p0.99:   5.161 ms/op
                 getUser·p0.999:  10.690 ms/op
                 getUser·p0.9999: 11.662 ms/op
                 getUser·p1.00:   11.682 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15902
  mean =      2.016 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 149 
    [ 1.250,  2.500) = 14771 
    [ 2.500,  3.750) = 673 
    [ 3.750,  5.000) = 112 
    [ 5.000,  6.250) = 128 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.719 ms/op
     p(50.0000) =      1.907 ms/op
     p(90.0000) =      2.343 ms/op
     p(95.0000) =      2.617 ms/op
     p(99.0000) =      5.161 ms/op
     p(99.9000) =     10.690 ms/op
     p(99.9900) =     11.662 ms/op
     p(99.9990) =     11.682 ms/op
     p(99.9999) =     11.682 ms/op
    p(100.0000) =     11.682 ms/op


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
# Warmup Iteration   1: 4.283 ±(99.9%) 0.125 ms/op
Iteration   1: 3.110 ±(99.9%) 0.036 ms/op
                 listUser·p0.00:   0.637 ms/op
                 listUser·p0.50:   2.879 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.162 ms/op
                 listUser·p0.99:   5.103 ms/op
                 listUser·p0.999:  20.021 ms/op
                 listUser·p0.9999: 21.558 ms/op
                 listUser·p1.00:   21.561 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10307
  mean =      3.110 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1348 
    [ 2.500,  5.000) = 8849 
    [ 5.000,  7.500) = 53 
    [ 7.500, 10.000) = 26 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.637 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.162 ms/op
     p(99.0000) =      5.103 ms/op
     p(99.9000) =     20.021 ms/op
     p(99.9900) =     21.558 ms/op
     p(99.9990) =     21.561 ms/op
     p(99.9999) =     21.561 ms/op
    p(100.0000) =     21.561 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.584          ops/ms
ClientSimple.existUser                       thrpt         11.730          ops/ms
ClientSimple.getUser                         thrpt         14.030          ops/ms
ClientSimple.listUser                        thrpt          8.062          ops/ms
ClientSimple.createUser                       avgt          1.958           ms/op
ClientSimple.existUser                        avgt          1.619           ms/op
ClientSimple.getUser                          avgt          2.022           ms/op
ClientSimple.listUser                         avgt          3.131           ms/op
ClientSimple.createUser                     sample  15427   2.083 ± 0.049   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.628           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.810           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.691           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.988           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.271           ms/op
ClientSimple.createUser:createUser·p0.999   sample         38.479           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         39.584           ms/op
ClientSimple.createUser:createUser·p1.00    sample         39.584           ms/op
ClientSimple.existUser                      sample  16829   1.901 ± 0.032   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.573           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.794           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.220           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.370           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.551           ms/op
ClientSimple.existUser:existUser·p0.999     sample         21.185           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         21.648           ms/op
ClientSimple.existUser:existUser·p1.00      sample         21.692           ms/op
ClientSimple.getUser                        sample  15902   2.016 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.719           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.907           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.343           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.617           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.161           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.690           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.662           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.682           ms/op
ClientSimple.listUser                       sample  10307   3.110 ± 0.036   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.637           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.879           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.871           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.162           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.103           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.021           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.558           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.561           ms/op

Benchmark result is saved to 1715796299999.json
