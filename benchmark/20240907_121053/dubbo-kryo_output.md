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
# Warmup Iteration   1: 1.766 ops/ms
Iteration   1: 7.189 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.189 ops/ms


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
# Warmup Iteration   1: 6.229 ops/ms
Iteration   1: 13.763 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.763 ops/ms


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
# Warmup Iteration   1: 6.189 ops/ms
Iteration   1: 14.405 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.405 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.693 ops/ms
Iteration   1: 9.012 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.012 ops/ms


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
# Warmup Iteration   1: 4.205 ±(99.9%) 0.105 ms/op
Iteration   1: 2.338 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.338 ms/op


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
# Warmup Iteration   1: 2.858 ±(99.9%) 0.044 ms/op
Iteration   1: 1.787 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.787 ms/op


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
# Warmup Iteration   1: 3.057 ±(99.9%) 0.055 ms/op
Iteration   1: 2.023 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.023 ms/op


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
# Warmup Iteration   1: 4.581 ±(99.9%) 0.097 ms/op
Iteration   1: 3.349 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.349 ms/op


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
# Warmup Iteration   1: 3.417 ±(99.9%) 0.096 ms/op
Iteration   1: 2.158 ±(99.9%) 0.041 ms/op
                 createUser·p0.00:   0.573 ms/op
                 createUser·p0.50:   2.021 ms/op
                 createUser·p0.90:   2.630 ms/op
                 createUser·p0.95:   2.843 ms/op
                 createUser·p0.99:   5.612 ms/op
                 createUser·p0.999:  30.704 ms/op
                 createUser·p0.9999: 32.969 ms/op
                 createUser·p1.00:   33.456 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14799
  mean =      2.158 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12285 
    [ 2.500,  5.000) = 2347 
    [ 5.000,  7.500) = 61 
    [ 7.500, 10.000) = 43 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.573 ms/op
     p(50.0000) =      2.021 ms/op
     p(90.0000) =      2.630 ms/op
     p(95.0000) =      2.843 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =     30.704 ms/op
     p(99.9900) =     32.969 ms/op
     p(99.9990) =     33.456 ms/op
     p(99.9999) =     33.456 ms/op
    p(100.0000) =     33.456 ms/op


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
# Warmup Iteration   1: 3.067 ±(99.9%) 0.100 ms/op
Iteration   1: 1.866 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.599 ms/op
                 existUser·p0.50:   1.763 ms/op
                 existUser·p0.90:   2.404 ms/op
                 existUser·p0.95:   2.585 ms/op
                 existUser·p0.99:   3.457 ms/op
                 existUser·p0.999:  11.420 ms/op
                 existUser·p0.9999: 11.946 ms/op
                 existUser·p1.00:   11.993 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17149
  mean =      1.866 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 526 
    [ 1.250,  2.500) = 15550 
    [ 2.500,  3.750) = 1015 
    [ 3.750,  5.000) = 26 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.599 ms/op
     p(50.0000) =      1.763 ms/op
     p(90.0000) =      2.404 ms/op
     p(95.0000) =      2.585 ms/op
     p(99.0000) =      3.457 ms/op
     p(99.9000) =     11.420 ms/op
     p(99.9900) =     11.946 ms/op
     p(99.9990) =     11.993 ms/op
     p(99.9999) =     11.993 ms/op
    p(100.0000) =     11.993 ms/op


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
# Warmup Iteration   1: 3.053 ±(99.9%) 0.080 ms/op
Iteration   1: 2.078 ±(99.9%) 0.036 ms/op
                 getUser·p0.00:   0.554 ms/op
                 getUser·p0.50:   1.892 ms/op
                 getUser·p0.90:   2.421 ms/op
                 getUser·p0.95:   2.695 ms/op
                 getUser·p0.99:   4.727 ms/op
                 getUser·p0.999:  25.166 ms/op
                 getUser·p0.9999: 25.572 ms/op
                 getUser·p1.00:   25.625 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15389
  mean =      2.078 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14200 
    [ 2.500,  5.000) = 1046 
    [ 5.000,  7.500) = 9 
    [ 7.500, 10.000) = 7 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.554 ms/op
     p(50.0000) =      1.892 ms/op
     p(90.0000) =      2.421 ms/op
     p(95.0000) =      2.695 ms/op
     p(99.0000) =      4.727 ms/op
     p(99.9000) =     25.166 ms/op
     p(99.9900) =     25.572 ms/op
     p(99.9990) =     25.625 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


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
# Warmup Iteration   1: 4.093 ±(99.9%) 0.113 ms/op
Iteration   1: 3.133 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.038 ms/op
                 listUser·p0.50:   3.039 ms/op
                 listUser·p0.90:   3.662 ms/op
                 listUser·p0.95:   4.137 ms/op
                 listUser·p0.99:   5.038 ms/op
                 listUser·p0.999:  6.134 ms/op
                 listUser·p0.9999: 7.434 ms/op
                 listUser·p1.00:   7.438 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10209
  mean =      3.133 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 24 
    [1.500, 2.000) = 86 
    [2.000, 2.500) = 203 
    [2.500, 3.000) = 4105 
    [3.000, 3.500) = 4474 
    [3.500, 4.000) = 654 
    [4.000, 4.500) = 380 
    [4.500, 5.000) = 175 
    [5.000, 5.500) = 26 
    [5.500, 6.000) = 62 
    [6.000, 6.500) = 18 
    [6.500, 7.000) = 0 
    [7.000, 7.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.038 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      4.137 ms/op
     p(99.0000) =      5.038 ms/op
     p(99.9000) =      6.134 ms/op
     p(99.9900) =      7.434 ms/op
     p(99.9990) =      7.438 ms/op
     p(99.9999) =      7.438 ms/op
    p(100.0000) =      7.438 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.189          ops/ms
ClientSimple.existUser                       thrpt         13.763          ops/ms
ClientSimple.getUser                         thrpt         14.405          ops/ms
ClientSimple.listUser                        thrpt          9.012          ops/ms
ClientSimple.createUser                       avgt          2.338           ms/op
ClientSimple.existUser                        avgt          1.787           ms/op
ClientSimple.getUser                          avgt          2.023           ms/op
ClientSimple.listUser                         avgt          3.349           ms/op
ClientSimple.createUser                     sample  14799   2.158 ± 0.041   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.573           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.021           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.630           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.843           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.612           ms/op
ClientSimple.createUser:createUser·p0.999   sample         30.704           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         32.969           ms/op
ClientSimple.createUser:createUser·p1.00    sample         33.456           ms/op
ClientSimple.existUser                      sample  17149   1.866 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.599           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.763           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.404           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.585           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.457           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.420           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.946           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.993           ms/op
ClientSimple.getUser                        sample  15389   2.078 ± 0.036   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.554           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.892           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.421           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.695           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.727           ms/op
ClientSimple.getUser:getUser·p0.999         sample         25.166           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         25.572           ms/op
ClientSimple.getUser:getUser·p1.00          sample         25.625           ms/op
ClientSimple.listUser                       sample  10209   3.133 ± 0.017   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.038           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.039           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.662           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.137           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.038           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.134           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.434           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.438           ms/op

Benchmark result is saved to 1725710783535.json
