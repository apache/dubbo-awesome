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
# Warmup Iteration   1: 1.975 ops/ms
Iteration   1: 7.065 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.065 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.271 ops/ms
Iteration   1: 15.567 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  15.567 ops/ms


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
# Warmup Iteration   1: 5.880 ops/ms
Iteration   1: 13.392 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.392 ops/ms


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
# Warmup Iteration   1: 6.020 ops/ms
Iteration   1: 9.277 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.277 ops/ms


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
# Warmup Iteration   1: 3.593 ±(99.9%) 0.064 ms/op
Iteration   1: 2.384 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.384 ms/op


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
# Warmup Iteration   1: 3.670 ±(99.9%) 0.060 ms/op
Iteration   1: 1.803 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.803 ms/op


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
# Warmup Iteration   1: 3.329 ±(99.9%) 0.074 ms/op
Iteration   1: 2.243 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.243 ms/op


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
# Warmup Iteration   1: 4.182 ±(99.9%) 0.101 ms/op
Iteration   1: 3.455 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.455 ms/op


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
# Warmup Iteration   1: 3.442 ±(99.9%) 0.080 ms/op
Iteration   1: 2.111 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.627 ms/op
                 createUser·p0.50:   2.007 ms/op
                 createUser·p0.90:   2.523 ms/op
                 createUser·p0.95:   2.712 ms/op
                 createUser·p0.99:   7.513 ms/op
                 createUser·p0.999:  15.512 ms/op
                 createUser·p0.9999: 19.032 ms/op
                 createUser·p1.00:   19.628 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15192
  mean =      2.111 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 230 
    [ 1.250,  2.500) = 13294 
    [ 2.500,  3.750) = 1387 
    [ 3.750,  5.000) = 54 
    [ 5.000,  6.250) = 65 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.627 ms/op
     p(50.0000) =      2.007 ms/op
     p(90.0000) =      2.523 ms/op
     p(95.0000) =      2.712 ms/op
     p(99.0000) =      7.513 ms/op
     p(99.9000) =     15.512 ms/op
     p(99.9900) =     19.032 ms/op
     p(99.9990) =     19.628 ms/op
     p(99.9999) =     19.628 ms/op
    p(100.0000) =     19.628 ms/op


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
# Warmup Iteration   1: 3.346 ±(99.9%) 0.143 ms/op
Iteration   1: 1.906 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   0.520 ms/op
                 existUser·p0.50:   1.751 ms/op
                 existUser·p0.90:   2.232 ms/op
                 existUser·p0.95:   2.474 ms/op
                 existUser·p0.99:   4.133 ms/op
                 existUser·p0.999:  22.086 ms/op
                 existUser·p0.9999: 22.708 ms/op
                 existUser·p1.00:   22.708 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16918
  mean =      1.906 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16131 
    [ 2.500,  5.000) = 643 
    [ 5.000,  7.500) = 48 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.520 ms/op
     p(50.0000) =      1.751 ms/op
     p(90.0000) =      2.232 ms/op
     p(95.0000) =      2.474 ms/op
     p(99.0000) =      4.133 ms/op
     p(99.9000) =     22.086 ms/op
     p(99.9900) =     22.708 ms/op
     p(99.9990) =     22.708 ms/op
     p(99.9999) =     22.708 ms/op
    p(100.0000) =     22.708 ms/op


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
# Warmup Iteration   1: 3.164 ±(99.9%) 0.086 ms/op
Iteration   1: 1.925 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.412 ms/op
                 getUser·p0.50:   1.835 ms/op
                 getUser·p0.90:   2.470 ms/op
                 getUser·p0.95:   2.628 ms/op
                 getUser·p0.99:   3.093 ms/op
                 getUser·p0.999:  11.012 ms/op
                 getUser·p0.9999: 11.342 ms/op
                 getUser·p1.00:   11.387 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16886
  mean =      1.925 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 577 
    [ 1.250,  2.500) = 14790 
    [ 2.500,  3.750) = 1388 
    [ 3.750,  5.000) = 30 
    [ 5.000,  6.250) = 67 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.412 ms/op
     p(50.0000) =      1.835 ms/op
     p(90.0000) =      2.470 ms/op
     p(95.0000) =      2.628 ms/op
     p(99.0000) =      3.093 ms/op
     p(99.9000) =     11.012 ms/op
     p(99.9900) =     11.342 ms/op
     p(99.9990) =     11.387 ms/op
     p(99.9999) =     11.387 ms/op
    p(100.0000) =     11.387 ms/op


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
# Warmup Iteration   1: 4.197 ±(99.9%) 0.131 ms/op
Iteration   1: 3.344 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   0.762 ms/op
                 listUser·p0.50:   3.379 ms/op
                 listUser·p0.90:   4.133 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.734 ms/op
                 listUser·p0.999:  9.353 ms/op
                 listUser·p0.9999: 10.748 ms/op
                 listUser·p1.00:   10.748 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9577
  mean =      3.344 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 2 
    [ 1.000,  2.000) = 231 
    [ 2.000,  3.000) = 3079 
    [ 3.000,  4.000) = 4661 
    [ 4.000,  5.000) = 1403 
    [ 5.000,  6.000) = 138 
    [ 6.000,  7.000) = 20 
    [ 7.000,  8.000) = 7 
    [ 8.000,  9.000) = 18 
    [ 9.000, 10.000) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.762 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      4.133 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.734 ms/op
     p(99.9000) =      9.353 ms/op
     p(99.9900) =     10.748 ms/op
     p(99.9990) =     10.748 ms/op
     p(99.9999) =     10.748 ms/op
    p(100.0000) =     10.748 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.065          ops/ms
ClientSimple.existUser                       thrpt         15.567          ops/ms
ClientSimple.getUser                         thrpt         13.392          ops/ms
ClientSimple.listUser                        thrpt          9.277          ops/ms
ClientSimple.createUser                       avgt          2.384           ms/op
ClientSimple.existUser                        avgt          1.803           ms/op
ClientSimple.getUser                          avgt          2.243           ms/op
ClientSimple.listUser                         avgt          3.455           ms/op
ClientSimple.createUser                     sample  15192   2.111 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.627           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.007           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.523           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.712           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.513           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.512           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.032           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.628           ms/op
ClientSimple.existUser                      sample  16918   1.906 ± 0.028   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.520           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.751           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.232           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.474           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.133           ms/op
ClientSimple.existUser:existUser·p0.999     sample         22.086           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         22.708           ms/op
ClientSimple.existUser:existUser·p1.00      sample         22.708           ms/op
ClientSimple.getUser                        sample  16886   1.925 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.412           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.835           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.470           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.628           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.093           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.012           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.342           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.387           ms/op
ClientSimple.listUser                       sample   9577   3.344 ± 0.028   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.762           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.379           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.133           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.383           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.734           ms/op
ClientSimple.listUser:listUser·p0.999       sample          9.353           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.748           ms/op
ClientSimple.listUser:listUser·p1.00        sample         10.748           ms/op

Benchmark result is saved to 1711281934675.json
