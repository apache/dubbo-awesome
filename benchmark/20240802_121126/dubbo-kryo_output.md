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
# Warmup Iteration   1: 1.843 ops/ms
Iteration   1: 6.928 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.928 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.364 ops/ms
Iteration   1: 11.567 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.567 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.429 ops/ms
Iteration   1: 10.909 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.909 ops/ms


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
# Warmup Iteration   1: 5.167 ops/ms
Iteration   1: 9.009 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.009 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.608 ±(99.9%) 0.103 ms/op
Iteration   1: 2.035 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.035 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.343 ±(99.9%) 0.046 ms/op
Iteration   1: 2.080 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.080 ms/op


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
# Warmup Iteration   1: 3.693 ±(99.9%) 0.074 ms/op
Iteration   1: 2.029 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.029 ms/op


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
# Warmup Iteration   1: 4.587 ±(99.9%) 0.105 ms/op
Iteration   1: 3.938 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.938 ms/op


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
# Warmup Iteration   1: 3.635 ±(99.9%) 0.087 ms/op
Iteration   1: 2.373 ±(99.9%) 0.050 ms/op
                 createUser·p0.00:   0.647 ms/op
                 createUser·p0.50:   2.109 ms/op
                 createUser·p0.90:   2.990 ms/op
                 createUser·p0.95:   3.285 ms/op
                 createUser·p0.99:   8.349 ms/op
                 createUser·p0.999:  28.934 ms/op
                 createUser·p0.9999: 29.939 ms/op
                 createUser·p1.00:   29.950 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13461
  mean =      2.373 ±(99.9%) 0.050 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9980 
    [ 2.500,  5.000) = 3176 
    [ 5.000,  7.500) = 161 
    [ 7.500, 10.000) = 39 
    [10.000, 12.500) = 9 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.647 ms/op
     p(50.0000) =      2.109 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.285 ms/op
     p(99.0000) =      8.349 ms/op
     p(99.9000) =     28.934 ms/op
     p(99.9900) =     29.939 ms/op
     p(99.9990) =     29.950 ms/op
     p(99.9999) =     29.950 ms/op
    p(100.0000) =     29.950 ms/op


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
# Warmup Iteration   1: 2.967 ±(99.9%) 0.065 ms/op
Iteration   1: 2.013 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.561 ms/op
                 existUser·p0.50:   1.923 ms/op
                 existUser·p0.90:   2.478 ms/op
                 existUser·p0.95:   2.740 ms/op
                 existUser·p0.99:   3.579 ms/op
                 existUser·p0.999:  20.916 ms/op
                 existUser·p0.9999: 21.130 ms/op
                 existUser·p1.00:   21.168 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15840
  mean =      2.013 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14373 
    [ 2.500,  5.000) = 1394 
    [ 5.000,  7.500) = 6 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.561 ms/op
     p(50.0000) =      1.923 ms/op
     p(90.0000) =      2.478 ms/op
     p(95.0000) =      2.740 ms/op
     p(99.0000) =      3.579 ms/op
     p(99.9000) =     20.916 ms/op
     p(99.9900) =     21.130 ms/op
     p(99.9990) =     21.168 ms/op
     p(99.9999) =     21.168 ms/op
    p(100.0000) =     21.168 ms/op


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
# Warmup Iteration   1: 3.206 ±(99.9%) 0.086 ms/op
Iteration   1: 2.042 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.541 ms/op
                 getUser·p0.50:   1.931 ms/op
                 getUser·p0.90:   2.445 ms/op
                 getUser·p0.95:   2.646 ms/op
                 getUser·p0.99:   3.928 ms/op
                 getUser·p0.999:  11.518 ms/op
                 getUser·p0.9999: 11.583 ms/op
                 getUser·p1.00:   11.583 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15675
  mean =      2.042 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 14320 
    [ 2.500,  3.750) = 1133 
    [ 3.750,  5.000) = 84 
    [ 5.000,  6.250) = 61 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.541 ms/op
     p(50.0000) =      1.931 ms/op
     p(90.0000) =      2.445 ms/op
     p(95.0000) =      2.646 ms/op
     p(99.0000) =      3.928 ms/op
     p(99.9000) =     11.518 ms/op
     p(99.9900) =     11.583 ms/op
     p(99.9990) =     11.583 ms/op
     p(99.9999) =     11.583 ms/op
    p(100.0000) =     11.583 ms/op


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
# Warmup Iteration   1: 4.281 ±(99.9%) 0.130 ms/op
Iteration   1: 3.632 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   1.581 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   4.817 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  7.948 ms/op
                 listUser·p0.9999: 8.020 ms/op
                 listUser·p1.00:   8.020 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8809
  mean =      3.632 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 0 
    [1.500, 2.000) = 36 
    [2.000, 2.500) = 406 
    [2.500, 3.000) = 2135 
    [3.000, 3.500) = 1451 
    [3.500, 4.000) = 1756 
    [4.000, 4.500) = 1832 
    [4.500, 5.000) = 880 
    [5.000, 5.500) = 105 
    [5.500, 6.000) = 62 
    [6.000, 6.500) = 51 
    [6.500, 7.000) = 11 
    [7.000, 7.500) = 45 
    [7.500, 8.000) = 35 
    [8.000, 8.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.581 ms/op
     p(50.0000) =      3.629 ms/op
     p(90.0000) =      4.604 ms/op
     p(95.0000) =      4.817 ms/op
     p(99.0000) =      6.930 ms/op
     p(99.9000) =      7.948 ms/op
     p(99.9900) =      8.020 ms/op
     p(99.9990) =      8.020 ms/op
     p(99.9999) =      8.020 ms/op
    p(100.0000) =      8.020 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.928          ops/ms
ClientSimple.existUser                       thrpt         11.567          ops/ms
ClientSimple.getUser                         thrpt         10.909          ops/ms
ClientSimple.listUser                        thrpt          9.009          ops/ms
ClientSimple.createUser                       avgt          2.035           ms/op
ClientSimple.existUser                        avgt          2.080           ms/op
ClientSimple.getUser                          avgt          2.029           ms/op
ClientSimple.listUser                         avgt          3.938           ms/op
ClientSimple.createUser                     sample  13461   2.373 ± 0.050   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.647           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.109           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.990           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.285           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.349           ms/op
ClientSimple.createUser:createUser·p0.999   sample         28.934           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         29.939           ms/op
ClientSimple.createUser:createUser·p1.00    sample         29.950           ms/op
ClientSimple.existUser                      sample  15840   2.013 ± 0.027   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.561           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.923           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.478           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.740           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.579           ms/op
ClientSimple.existUser:existUser·p0.999     sample         20.916           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         21.130           ms/op
ClientSimple.existUser:existUser·p1.00      sample         21.168           ms/op
ClientSimple.getUser                        sample  15675   2.042 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.541           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.931           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.445           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.646           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.928           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.518           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.583           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.583           ms/op
ClientSimple.listUser                       sample   8809   3.632 ± 0.030   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.581           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.629           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.604           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.817           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.930           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.948           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.020           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.020           ms/op

Benchmark result is saved to 1722600408310.json
