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
# Warmup Iteration   1: 1.757 ops/ms
Iteration   1: 6.734 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.734 ops/ms


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
# Warmup Iteration   1: 6.081 ops/ms
Iteration   1: 14.975 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.975 ops/ms


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
# Warmup Iteration   1: 5.827 ops/ms
Iteration   1: 13.914 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.914 ops/ms


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
# Warmup Iteration   1: 4.359 ops/ms
Iteration   1: 8.969 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.969 ops/ms


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
# Warmup Iteration   1: 3.678 ±(99.9%) 0.064 ms/op
Iteration   1: 2.068 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.068 ms/op


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
# Warmup Iteration   1: 3.234 ±(99.9%) 0.049 ms/op
Iteration   1: 1.849 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.849 ms/op


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
# Warmup Iteration   1: 3.022 ±(99.9%) 0.050 ms/op
Iteration   1: 1.818 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.818 ms/op


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
# Warmup Iteration   1: 4.493 ±(99.9%) 0.099 ms/op
Iteration   1: 3.367 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.367 ms/op


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
# Warmup Iteration   1: 3.669 ±(99.9%) 0.105 ms/op
Iteration   1: 1.975 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   0.537 ms/op
                 createUser·p0.50:   1.849 ms/op
                 createUser·p0.90:   2.380 ms/op
                 createUser·p0.95:   2.597 ms/op
                 createUser·p0.99:   6.295 ms/op
                 createUser·p0.999:  14.251 ms/op
                 createUser·p0.9999: 14.572 ms/op
                 createUser·p1.00:   14.582 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16183
  mean =      1.975 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 354 
    [ 1.250,  2.500) = 14729 
    [ 2.500,  3.750) = 830 
    [ 3.750,  5.000) = 98 
    [ 5.000,  6.250) = 10 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 64 
    [ 8.750, 10.000) = 39 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.537 ms/op
     p(50.0000) =      1.849 ms/op
     p(90.0000) =      2.380 ms/op
     p(95.0000) =      2.597 ms/op
     p(99.0000) =      6.295 ms/op
     p(99.9000) =     14.251 ms/op
     p(99.9900) =     14.572 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.048 ±(99.9%) 0.078 ms/op
Iteration   1: 1.763 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.585 ms/op
                 existUser·p0.50:   1.616 ms/op
                 existUser·p0.90:   2.071 ms/op
                 existUser·p0.95:   2.490 ms/op
                 existUser·p0.99:   4.081 ms/op
                 existUser·p0.999:  15.942 ms/op
                 existUser·p0.9999: 16.030 ms/op
                 existUser·p1.00:   16.056 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18177
  mean =      1.763 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 272 
    [ 1.250,  2.500) = 17019 
    [ 2.500,  3.750) = 665 
    [ 3.750,  5.000) = 66 
    [ 5.000,  6.250) = 33 
    [ 6.250,  7.500) = 55 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.585 ms/op
     p(50.0000) =      1.616 ms/op
     p(90.0000) =      2.071 ms/op
     p(95.0000) =      2.490 ms/op
     p(99.0000) =      4.081 ms/op
     p(99.9000) =     15.942 ms/op
     p(99.9900) =     16.030 ms/op
     p(99.9990) =     16.056 ms/op
     p(99.9999) =     16.056 ms/op
    p(100.0000) =     16.056 ms/op


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
# Warmup Iteration   1: 3.253 ±(99.9%) 0.082 ms/op
Iteration   1: 1.973 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.562 ms/op
                 getUser·p0.50:   1.821 ms/op
                 getUser·p0.90:   2.597 ms/op
                 getUser·p0.95:   2.748 ms/op
                 getUser·p0.99:   3.252 ms/op
                 getUser·p0.999:  11.201 ms/op
                 getUser·p0.9999: 11.527 ms/op
                 getUser·p1.00:   11.567 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16194
  mean =      1.973 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 501 
    [ 1.250,  2.500) = 13400 
    [ 2.500,  3.750) = 2195 
    [ 3.750,  5.000) = 54 
    [ 5.000,  6.250) = 10 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.562 ms/op
     p(50.0000) =      1.821 ms/op
     p(90.0000) =      2.597 ms/op
     p(95.0000) =      2.748 ms/op
     p(99.0000) =      3.252 ms/op
     p(99.9000) =     11.201 ms/op
     p(99.9900) =     11.527 ms/op
     p(99.9990) =     11.567 ms/op
     p(99.9999) =     11.567 ms/op
    p(100.0000) =     11.567 ms/op


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
# Warmup Iteration   1: 4.272 ±(99.9%) 0.113 ms/op
Iteration   1: 3.679 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.161 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  8.326 ms/op
                 listUser·p0.9999: 8.929 ms/op
                 listUser·p1.00:   8.929 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8686
  mean =      3.679 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 14 
    [1.500, 2.000) = 88 
    [2.000, 2.500) = 429 
    [2.500, 3.000) = 975 
    [3.000, 3.500) = 1627 
    [3.500, 4.000) = 3024 
    [4.000, 4.500) = 1785 
    [4.500, 5.000) = 461 
    [5.000, 5.500) = 115 
    [5.500, 6.000) = 41 
    [6.000, 6.500) = 29 
    [6.500, 7.000) = 29 
    [7.000, 7.500) = 31 
    [7.500, 8.000) = 3 
    [8.000, 8.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      1.161 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      6.816 ms/op
     p(99.9000) =      8.326 ms/op
     p(99.9900) =      8.929 ms/op
     p(99.9990) =      8.929 ms/op
     p(99.9999) =      8.929 ms/op
    p(100.0000) =      8.929 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.734          ops/ms
ClientSimple.existUser                       thrpt         14.975          ops/ms
ClientSimple.getUser                         thrpt         13.914          ops/ms
ClientSimple.listUser                        thrpt          8.969          ops/ms
ClientSimple.createUser                       avgt          2.068           ms/op
ClientSimple.existUser                        avgt          1.849           ms/op
ClientSimple.getUser                          avgt          1.818           ms/op
ClientSimple.listUser                         avgt          3.367           ms/op
ClientSimple.createUser                     sample  16183   1.975 ± 0.023   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.537           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.849           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.380           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.597           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.295           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.251           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.572           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.582           ms/op
ClientSimple.existUser                      sample  18177   1.763 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.585           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.616           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.071           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.490           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.081           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.942           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.030           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.056           ms/op
ClientSimple.getUser                        sample  16194   1.973 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.562           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.821           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.597           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.748           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.252           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.201           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.527           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.567           ms/op
ClientSimple.listUser                       sample   8686   3.679 ± 0.028   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.161           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.699           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.415           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.850           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.816           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.326           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.929           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.929           ms/op

Benchmark result is saved to 1721736438189.json
