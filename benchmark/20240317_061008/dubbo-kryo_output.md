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
# Warmup Iteration   1: 1.947 ops/ms
Iteration   1: 7.053 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.053 ops/ms


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
# Warmup Iteration   1: 6.057 ops/ms
Iteration   1: 11.395 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.395 ops/ms


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
# Warmup Iteration   1: 6.043 ops/ms
Iteration   1: 14.688 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.688 ops/ms


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
# Warmup Iteration   1: 4.633 ops/ms
Iteration   1: 8.611 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.611 ops/ms


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
# Warmup Iteration   1: 4.289 ±(99.9%) 0.072 ms/op
Iteration   1: 2.126 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.126 ms/op


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
# Warmup Iteration   1: 3.086 ±(99.9%) 0.043 ms/op
Iteration   1: 1.823 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.823 ms/op


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
# Warmup Iteration   1: 3.142 ±(99.9%) 0.060 ms/op
Iteration   1: 1.907 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.907 ms/op


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
# Warmup Iteration   1: 4.358 ±(99.9%) 0.075 ms/op
Iteration   1: 3.787 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.787 ms/op


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
# Warmup Iteration   1: 3.378 ±(99.9%) 0.079 ms/op
Iteration   1: 2.251 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.469 ms/op
                 createUser·p0.50:   2.036 ms/op
                 createUser·p0.90:   2.540 ms/op
                 createUser·p0.95:   3.316 ms/op
                 createUser·p0.99:   9.683 ms/op
                 createUser·p0.999:  17.957 ms/op
                 createUser·p0.9999: 21.553 ms/op
                 createUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14214
  mean =      2.251 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12674 
    [ 2.500,  5.000) = 1123 
    [ 5.000,  7.500) = 238 
    [ 7.500, 10.000) = 47 
    [10.000, 12.500) = 83 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.469 ms/op
     p(50.0000) =      2.036 ms/op
     p(90.0000) =      2.540 ms/op
     p(95.0000) =      3.316 ms/op
     p(99.0000) =      9.683 ms/op
     p(99.9000) =     17.957 ms/op
     p(99.9900) =     21.553 ms/op
     p(99.9990) =     21.594 ms/op
     p(99.9999) =     21.594 ms/op
    p(100.0000) =     21.594 ms/op


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
# Warmup Iteration   1: 3.006 ±(99.9%) 0.067 ms/op
Iteration   1: 1.993 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   0.441 ms/op
                 existUser·p0.50:   1.890 ms/op
                 existUser·p0.90:   2.470 ms/op
                 existUser·p0.95:   2.593 ms/op
                 existUser·p0.99:   3.219 ms/op
                 existUser·p0.999:  24.347 ms/op
                 existUser·p0.9999: 24.975 ms/op
                 existUser·p1.00:   25.035 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16033
  mean =      1.993 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14766 
    [ 2.500,  5.000) = 1137 
    [ 5.000,  7.500) = 61 
    [ 7.500, 10.000) = 5 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.441 ms/op
     p(50.0000) =      1.890 ms/op
     p(90.0000) =      2.470 ms/op
     p(95.0000) =      2.593 ms/op
     p(99.0000) =      3.219 ms/op
     p(99.9000) =     24.347 ms/op
     p(99.9900) =     24.975 ms/op
     p(99.9990) =     25.035 ms/op
     p(99.9999) =     25.035 ms/op
    p(100.0000) =     25.035 ms/op


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
# Warmup Iteration   1: 3.171 ±(99.9%) 0.078 ms/op
Iteration   1: 1.770 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.743 ms/op
                 getUser·p0.50:   1.683 ms/op
                 getUser·p0.90:   2.077 ms/op
                 getUser·p0.95:   2.310 ms/op
                 getUser·p0.99:   3.093 ms/op
                 getUser·p0.999:  13.546 ms/op
                 getUser·p0.9999: 13.916 ms/op
                 getUser·p1.00:   13.943 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 18076
  mean =      1.770 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 208 
    [ 1.250,  2.500) = 17377 
    [ 2.500,  3.750) = 352 
    [ 3.750,  5.000) = 86 
    [ 5.000,  6.250) = 20 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.743 ms/op
     p(50.0000) =      1.683 ms/op
     p(90.0000) =      2.077 ms/op
     p(95.0000) =      2.310 ms/op
     p(99.0000) =      3.093 ms/op
     p(99.9000) =     13.546 ms/op
     p(99.9900) =     13.916 ms/op
     p(99.9990) =     13.943 ms/op
     p(99.9999) =     13.943 ms/op
    p(100.0000) =     13.943 ms/op


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
# Warmup Iteration   1: 4.391 ±(99.9%) 0.137 ms/op
Iteration   1: 3.289 ±(99.9%) 0.043 ms/op
                 listUser·p0.00:   1.120 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   4.076 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   6.739 ms/op
                 listUser·p0.999:  21.561 ms/op
                 listUser·p0.9999: 21.725 ms/op
                 listUser·p1.00:   21.725 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9738
  mean =      3.289 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 284 
    [ 2.500,  5.000) = 9184 
    [ 5.000,  7.500) = 207 
    [ 7.500, 10.000) = 29 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.120 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      4.076 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      6.739 ms/op
     p(99.9000) =     21.561 ms/op
     p(99.9900) =     21.725 ms/op
     p(99.9990) =     21.725 ms/op
     p(99.9999) =     21.725 ms/op
    p(100.0000) =     21.725 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.053          ops/ms
ClientSimple.existUser                       thrpt         11.395          ops/ms
ClientSimple.getUser                         thrpt         14.688          ops/ms
ClientSimple.listUser                        thrpt          8.611          ops/ms
ClientSimple.createUser                       avgt          2.126           ms/op
ClientSimple.existUser                        avgt          1.823           ms/op
ClientSimple.getUser                          avgt          1.907           ms/op
ClientSimple.listUser                         avgt          3.787           ms/op
ClientSimple.createUser                     sample  14214   2.251 ± 0.037   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.469           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.036           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.540           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.316           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.683           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.957           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.553           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.594           ms/op
ClientSimple.existUser                      sample  16033   1.993 ± 0.031   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.441           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.890           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.470           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.593           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.219           ms/op
ClientSimple.existUser:existUser·p0.999     sample         24.347           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         24.975           ms/op
ClientSimple.existUser:existUser·p1.00      sample         25.035           ms/op
ClientSimple.getUser                        sample  18076   1.770 ± 0.015   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.743           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.683           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.077           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.310           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.093           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.546           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.916           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.943           ms/op
ClientSimple.listUser                       sample   9738   3.289 ± 0.043   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.120           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.945           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.076           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.383           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.739           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.561           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.725           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.725           ms/op

Benchmark result is saved to 1710655510363.json
