# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.560 ops/ms
Iteration   1: 6.279 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.279 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.879 ops/ms
Iteration   1: 10.643 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.643 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:12
# Fork: 1 of 1
# Warmup Iteration   1: 4.672 ops/ms
Iteration   1: 11.441 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.441 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.153 ops/ms
Iteration   1: 8.364 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.364 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.823 ±(99.9%) 0.067 ms/op
Iteration   1: 2.162 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.162 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.268 ±(99.9%) 0.054 ms/op
Iteration   1: 2.024 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.024 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 2.964 ±(99.9%) 0.052 ms/op
Iteration   1: 2.020 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.020 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.808 ±(99.9%) 0.107 ms/op
Iteration   1: 3.365 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.365 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.606 ±(99.9%) 0.091 ms/op
Iteration   1: 2.039 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.729 ms/op
                 createUser·p0.50:   1.956 ms/op
                 createUser·p0.90:   2.396 ms/op
                 createUser·p0.95:   2.638 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  21.091 ms/op
                 createUser·p0.9999: 27.011 ms/op
                 createUser·p1.00:   27.066 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15676
  mean =      2.039 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14668 
    [ 2.500,  5.000) = 865 
    [ 5.000,  7.500) = 78 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 20 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.729 ms/op
     p(50.0000) =      1.956 ms/op
     p(90.0000) =      2.396 ms/op
     p(95.0000) =      2.638 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =     21.091 ms/op
     p(99.9900) =     27.011 ms/op
     p(99.9990) =     27.066 ms/op
     p(99.9999) =     27.066 ms/op
    p(100.0000) =     27.066 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.119 ±(99.9%) 0.098 ms/op
Iteration   1: 1.916 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   0.540 ms/op
                 existUser·p0.50:   1.749 ms/op
                 existUser·p0.90:   2.335 ms/op
                 existUser·p0.95:   2.642 ms/op
                 existUser·p0.99:   4.727 ms/op
                 existUser·p0.999:  19.497 ms/op
                 existUser·p0.9999: 19.726 ms/op
                 existUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16697
  mean =      1.916 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 566 
    [ 1.250,  2.500) = 14919 
    [ 2.500,  3.750) = 841 
    [ 3.750,  5.000) = 273 
    [ 5.000,  6.250) = 33 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.540 ms/op
     p(50.0000) =      1.749 ms/op
     p(90.0000) =      2.335 ms/op
     p(95.0000) =      2.642 ms/op
     p(99.0000) =      4.727 ms/op
     p(99.9000) =     19.497 ms/op
     p(99.9900) =     19.726 ms/op
     p(99.9990) =     19.792 ms/op
     p(99.9999) =     19.792 ms/op
    p(100.0000) =     19.792 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.010 ±(99.9%) 0.073 ms/op
Iteration   1: 2.173 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.367 ms/op
                 getUser·p0.50:   2.030 ms/op
                 getUser·p0.90:   2.695 ms/op
                 getUser·p0.95:   3.010 ms/op
                 getUser·p0.99:   5.927 ms/op
                 getUser·p0.999:  14.009 ms/op
                 getUser·p0.9999: 14.574 ms/op
                 getUser·p1.00:   14.582 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14642
  mean =      2.173 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 318 
    [ 1.250,  2.500) = 11843 
    [ 2.500,  3.750) = 2071 
    [ 3.750,  5.000) = 200 
    [ 5.000,  6.250) = 86 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.367 ms/op
     p(50.0000) =      2.030 ms/op
     p(90.0000) =      2.695 ms/op
     p(95.0000) =      3.010 ms/op
     p(99.0000) =      5.927 ms/op
     p(99.9000) =     14.009 ms/op
     p(99.9900) =     14.574 ms/op
     p(99.9990) =     14.582 ms/op
     p(99.9999) =     14.582 ms/op
    p(100.0000) =     14.582 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 5.024 ±(99.9%) 0.146 ms/op
Iteration   1: 3.863 ±(99.9%) 0.056 ms/op
                 listUser·p0.00:   1.092 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.376 ms/op
                 listUser·p0.99:   8.737 ms/op
                 listUser·p0.999:  21.159 ms/op
                 listUser·p0.9999: 21.987 ms/op
                 listUser·p1.00:   21.987 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8274
  mean =      3.863 ±(99.9%) 0.056 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 689 
    [ 2.500,  5.000) = 6966 
    [ 5.000,  7.500) = 513 
    [ 7.500, 10.000) = 42 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.092 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.776 ms/op
     p(95.0000) =      5.376 ms/op
     p(99.0000) =      8.737 ms/op
     p(99.9000) =     21.159 ms/op
     p(99.9900) =     21.987 ms/op
     p(99.9990) =     21.987 ms/op
     p(99.9999) =     21.987 ms/op
    p(100.0000) =     21.987 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.279          ops/ms
ClientSimple.existUser                       thrpt         10.643          ops/ms
ClientSimple.getUser                         thrpt         11.441          ops/ms
ClientSimple.listUser                        thrpt          8.364          ops/ms
ClientSimple.createUser                       avgt          2.162           ms/op
ClientSimple.existUser                        avgt          2.024           ms/op
ClientSimple.getUser                          avgt          2.020           ms/op
ClientSimple.listUser                         avgt          3.365           ms/op
ClientSimple.createUser                     sample  15676   2.039 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.729           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.956           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.396           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.638           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.293           ms/op
ClientSimple.createUser:createUser·p0.999   sample         21.091           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         27.011           ms/op
ClientSimple.createUser:createUser·p1.00    sample         27.066           ms/op
ClientSimple.existUser                      sample  16697   1.916 ± 0.028   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.540           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.749           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.335           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.642           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.727           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.497           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.726           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.792           ms/op
ClientSimple.getUser                        sample  14642   2.173 ± 0.027   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.367           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.030           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.695           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.010           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.927           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.009           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.574           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.582           ms/op
ClientSimple.listUser                       sample   8274   3.863 ± 0.056   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.092           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.871           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.776           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.376           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.737           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.159           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.987           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.987           ms/op

Benchmark result is saved to 1724349933304.json
