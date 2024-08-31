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
# Warmup Iteration   1: 1.808 ops/ms
Iteration   1: 7.175 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.175 ops/ms


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
# Warmup Iteration   1: 7.069 ops/ms
Iteration   1: 14.017 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.017 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 6.055 ops/ms
Iteration   1: 14.372 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.372 ops/ms


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
# Warmup Iteration   1: 5.427 ops/ms
Iteration   1: 9.424 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.424 ops/ms


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
# Warmup Iteration   1: 4.018 ±(99.9%) 0.093 ms/op
Iteration   1: 2.189 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.189 ms/op


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
# Warmup Iteration   1: 3.257 ±(99.9%) 0.049 ms/op
Iteration   1: 2.038 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.038 ms/op


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
# Warmup Iteration   1: 3.397 ±(99.9%) 0.067 ms/op
Iteration   1: 2.055 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.055 ms/op


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
# Warmup Iteration   1: 5.151 ±(99.9%) 0.107 ms/op
Iteration   1: 3.427 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.427 ms/op


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
# Warmup Iteration   1: 3.353 ±(99.9%) 0.100 ms/op
Iteration   1: 2.182 ±(99.9%) 0.054 ms/op
                 createUser·p0.00:   0.381 ms/op
                 createUser·p0.50:   1.868 ms/op
                 createUser·p0.90:   2.556 ms/op
                 createUser·p0.95:   3.367 ms/op
                 createUser·p0.99:   11.272 ms/op
                 createUser·p0.999:  32.790 ms/op
                 createUser·p0.9999: 37.312 ms/op
                 createUser·p1.00:   37.618 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14663
  mean =      2.182 ±(99.9%) 0.054 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13040 
    [ 2.500,  5.000) = 1226 
    [ 5.000,  7.500) = 167 
    [ 7.500, 10.000) = 70 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.381 ms/op
     p(50.0000) =      1.868 ms/op
     p(90.0000) =      2.556 ms/op
     p(95.0000) =      3.367 ms/op
     p(99.0000) =     11.272 ms/op
     p(99.9000) =     32.790 ms/op
     p(99.9900) =     37.312 ms/op
     p(99.9990) =     37.618 ms/op
     p(99.9999) =     37.618 ms/op
    p(100.0000) =     37.618 ms/op


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
# Warmup Iteration   1: 2.971 ±(99.9%) 0.066 ms/op
Iteration   1: 1.823 ±(99.9%) 0.039 ms/op
                 existUser·p0.00:   0.341 ms/op
                 existUser·p0.50:   1.640 ms/op
                 existUser·p0.90:   2.327 ms/op
                 existUser·p0.95:   2.617 ms/op
                 existUser·p0.99:   3.707 ms/op
                 existUser·p0.999:  35.389 ms/op
                 existUser·p0.9999: 35.864 ms/op
                 existUser·p1.00:   35.914 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17609
  mean =      1.823 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16429 
    [ 2.500,  5.000) = 1042 
    [ 5.000,  7.500) = 74 
    [ 7.500, 10.000) = 0 
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
    [35.000, 37.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.341 ms/op
     p(50.0000) =      1.640 ms/op
     p(90.0000) =      2.327 ms/op
     p(95.0000) =      2.617 ms/op
     p(99.0000) =      3.707 ms/op
     p(99.9000) =     35.389 ms/op
     p(99.9900) =     35.864 ms/op
     p(99.9990) =     35.914 ms/op
     p(99.9999) =     35.914 ms/op
    p(100.0000) =     35.914 ms/op


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
# Warmup Iteration   1: 3.597 ±(99.9%) 0.104 ms/op
Iteration   1: 2.423 ±(99.9%) 0.072 ms/op
                 getUser·p0.00:   0.696 ms/op
                 getUser·p0.50:   2.159 ms/op
                 getUser·p0.90:   2.806 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   6.922 ms/op
                 getUser·p0.999:  49.152 ms/op
                 getUser·p0.9999: 52.890 ms/op
                 getUser·p1.00:   53.477 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13200
  mean =      2.423 ±(99.9%) 0.072 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 12935 
    [ 5.000, 10.000) = 169 
    [10.000, 15.000) = 62 
    [15.000, 20.000) = 2 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 23 
    [50.000, 55.000) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.696 ms/op
     p(50.0000) =      2.159 ms/op
     p(90.0000) =      2.806 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      6.922 ms/op
     p(99.9000) =     49.152 ms/op
     p(99.9900) =     52.890 ms/op
     p(99.9990) =     53.477 ms/op
     p(99.9999) =     53.477 ms/op
    p(100.0000) =     53.477 ms/op


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
# Warmup Iteration   1: 4.616 ±(99.9%) 0.121 ms/op
Iteration   1: 3.786 ±(99.9%) 0.071 ms/op
                 listUser·p0.00:   0.777 ms/op
                 listUser·p0.50:   3.633 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   4.923 ms/op
                 listUser·p0.99:   9.322 ms/op
                 listUser·p0.999:  31.253 ms/op
                 listUser·p0.9999: 32.113 ms/op
                 listUser·p1.00:   32.113 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8447
  mean =      3.786 ±(99.9%) 0.071 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 522 
    [ 2.500,  5.000) = 7579 
    [ 5.000,  7.500) = 247 
    [ 7.500, 10.000) = 34 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.777 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      4.923 ms/op
     p(99.0000) =      9.322 ms/op
     p(99.9000) =     31.253 ms/op
     p(99.9900) =     32.113 ms/op
     p(99.9990) =     32.113 ms/op
     p(99.9999) =     32.113 ms/op
    p(100.0000) =     32.113 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.175          ops/ms
ClientSimple.existUser                       thrpt         14.017          ops/ms
ClientSimple.getUser                         thrpt         14.372          ops/ms
ClientSimple.listUser                        thrpt          9.424          ops/ms
ClientSimple.createUser                       avgt          2.189           ms/op
ClientSimple.existUser                        avgt          2.038           ms/op
ClientSimple.getUser                          avgt          2.055           ms/op
ClientSimple.listUser                         avgt          3.427           ms/op
ClientSimple.createUser                     sample  14663   2.182 ± 0.054   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.381           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.868           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.556           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.367           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.272           ms/op
ClientSimple.createUser:createUser·p0.999   sample         32.790           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         37.312           ms/op
ClientSimple.createUser:createUser·p1.00    sample         37.618           ms/op
ClientSimple.existUser                      sample  17609   1.823 ± 0.039   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.341           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.640           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.327           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.617           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.707           ms/op
ClientSimple.existUser:existUser·p0.999     sample         35.389           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         35.864           ms/op
ClientSimple.existUser:existUser·p1.00      sample         35.914           ms/op
ClientSimple.getUser                        sample  13200   2.423 ± 0.072   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.696           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.159           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.806           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.183           ms/op
ClientSimple.getUser:getUser·p0.99          sample          6.922           ms/op
ClientSimple.getUser:getUser·p0.999         sample         49.152           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         52.890           ms/op
ClientSimple.getUser:getUser·p1.00          sample         53.477           ms/op
ClientSimple.listUser                       sample   8447   3.786 ± 0.071   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.777           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.633           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.473           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.923           ms/op
ClientSimple.listUser:listUser·p0.99        sample          9.322           ms/op
ClientSimple.listUser:listUser·p0.999       sample         31.253           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         32.113           ms/op
ClientSimple.listUser:listUser·p1.00        sample         32.113           ms/op

Benchmark result is saved to 1725105980632.json
