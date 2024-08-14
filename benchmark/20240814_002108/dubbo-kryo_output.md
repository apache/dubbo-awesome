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
# Warmup Iteration   1: 1.786 ops/ms
Iteration   1: 7.240 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.240 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.146 ops/ms
Iteration   1: 13.294 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.294 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.875 ops/ms
Iteration   1: 13.702 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.702 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 4.728 ops/ms
Iteration   1: 8.525 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.525 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.782 ±(99.9%) 0.086 ms/op
Iteration   1: 2.109 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.109 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.295 ±(99.9%) 0.055 ms/op
Iteration   1: 1.722 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.722 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.213 ±(99.9%) 0.057 ms/op
Iteration   1: 2.011 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.011 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.611 ±(99.9%) 0.083 ms/op
Iteration   1: 3.846 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.846 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.484 ±(99.9%) 0.089 ms/op
Iteration   1: 2.222 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.570 ms/op
                 createUser·p0.50:   2.011 ms/op
                 createUser·p0.90:   2.687 ms/op
                 createUser·p0.95:   3.035 ms/op
                 createUser·p0.99:   7.972 ms/op
                 createUser·p0.999:  20.631 ms/op
                 createUser·p0.9999: 21.045 ms/op
                 createUser·p1.00:   21.103 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14387
  mean =      2.222 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12212 
    [ 2.500,  5.000) = 1884 
    [ 5.000,  7.500) = 135 
    [ 7.500, 10.000) = 60 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.570 ms/op
     p(50.0000) =      2.011 ms/op
     p(90.0000) =      2.687 ms/op
     p(95.0000) =      3.035 ms/op
     p(99.0000) =      7.972 ms/op
     p(99.9000) =     20.631 ms/op
     p(99.9900) =     21.045 ms/op
     p(99.9990) =     21.103 ms/op
     p(99.9999) =     21.103 ms/op
    p(100.0000) =     21.103 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.765 ±(99.9%) 0.056 ms/op
Iteration   1: 1.976 ±(99.9%) 0.030 ms/op
                 existUser·p0.00:   0.555 ms/op
                 existUser·p0.50:   1.901 ms/op
                 existUser·p0.90:   2.511 ms/op
                 existUser·p0.95:   2.654 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  18.661 ms/op
                 existUser·p0.9999: 19.479 ms/op
                 existUser·p1.00:   19.628 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16497
  mean =      1.976 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2000 
    [ 1.250,  2.500) = 12773 
    [ 2.500,  3.750) = 1512 
    [ 3.750,  5.000) = 98 
    [ 5.000,  6.250) = 48 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 33 

  Percentiles, ms/op:
      p(0.0000) =      0.555 ms/op
     p(50.0000) =      1.901 ms/op
     p(90.0000) =      2.511 ms/op
     p(95.0000) =      2.654 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =     18.661 ms/op
     p(99.9900) =     19.479 ms/op
     p(99.9990) =     19.628 ms/op
     p(99.9999) =     19.628 ms/op
    p(100.0000) =     19.628 ms/op


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
# Warmup Iteration   1: 3.343 ±(99.9%) 0.086 ms/op
Iteration   1: 1.908 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.733 ms/op
                 getUser·p0.50:   1.755 ms/op
                 getUser·p0.90:   2.433 ms/op
                 getUser·p0.95:   2.691 ms/op
                 getUser·p0.99:   3.754 ms/op
                 getUser·p0.999:  13.058 ms/op
                 getUser·p0.9999: 13.189 ms/op
                 getUser·p1.00:   13.189 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16743
  mean =      1.908 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 224 
    [ 1.250,  2.500) = 15108 
    [ 2.500,  3.750) = 1242 
    [ 3.750,  5.000) = 54 
    [ 5.000,  6.250) = 34 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.733 ms/op
     p(50.0000) =      1.755 ms/op
     p(90.0000) =      2.433 ms/op
     p(95.0000) =      2.691 ms/op
     p(99.0000) =      3.754 ms/op
     p(99.9000) =     13.058 ms/op
     p(99.9900) =     13.189 ms/op
     p(99.9990) =     13.189 ms/op
     p(99.9999) =     13.189 ms/op
    p(100.0000) =     13.189 ms/op


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
# Warmup Iteration   1: 4.281 ±(99.9%) 0.119 ms/op
Iteration   1: 3.543 ±(99.9%) 0.047 ms/op
                 listUser·p0.00:   0.983 ms/op
                 listUser·p0.50:   3.502 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   4.882 ms/op
                 listUser·p0.99:   6.318 ms/op
                 listUser·p0.999:  20.742 ms/op
                 listUser·p0.9999: 20.840 ms/op
                 listUser·p1.00:   20.840 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9025
  mean =      3.543 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 954 
    [ 2.500,  5.000) = 7711 
    [ 5.000,  7.500) = 279 
    [ 7.500, 10.000) = 49 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.983 ms/op
     p(50.0000) =      3.502 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      4.882 ms/op
     p(99.0000) =      6.318 ms/op
     p(99.9000) =     20.742 ms/op
     p(99.9900) =     20.840 ms/op
     p(99.9990) =     20.840 ms/op
     p(99.9999) =     20.840 ms/op
    p(100.0000) =     20.840 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.240          ops/ms
ClientSimple.existUser                       thrpt         13.294          ops/ms
ClientSimple.getUser                         thrpt         13.702          ops/ms
ClientSimple.listUser                        thrpt          8.525          ops/ms
ClientSimple.createUser                       avgt          2.109           ms/op
ClientSimple.existUser                        avgt          1.722           ms/op
ClientSimple.getUser                          avgt          2.011           ms/op
ClientSimple.listUser                         avgt          3.846           ms/op
ClientSimple.createUser                     sample  14387   2.222 ± 0.036   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.570           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.011           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.687           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.035           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.972           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.631           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.045           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.103           ms/op
ClientSimple.existUser                      sample  16497   1.976 ± 0.030   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.555           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.901           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.511           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.654           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.358           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.661           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.479           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.628           ms/op
ClientSimple.getUser                        sample  16743   1.908 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.733           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.755           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.433           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.691           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.754           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.058           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.189           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.189           ms/op
ClientSimple.listUser                       sample   9025   3.543 ± 0.047   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.983           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.502           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.588           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.882           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.318           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.742           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.840           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.840           ms/op

Benchmark result is saved to 1723594616798.json
