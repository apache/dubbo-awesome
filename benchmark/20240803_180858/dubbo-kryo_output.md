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
# Warmup Iteration   1: 2.111 ops/ms
Iteration   1: 6.843 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.843 ops/ms


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
# Warmup Iteration   1: 6.531 ops/ms
Iteration   1: 12.429 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.429 ops/ms


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
# Warmup Iteration   1: 5.467 ops/ms
Iteration   1: 13.137 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.137 ops/ms


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
# Warmup Iteration   1: 5.123 ops/ms
Iteration   1: 8.382 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.382 ops/ms


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
# Warmup Iteration   1: 4.068 ±(99.9%) 0.080 ms/op
Iteration   1: 2.148 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.148 ms/op


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
# Warmup Iteration   1: 3.285 ±(99.9%) 0.050 ms/op
Iteration   1: 1.925 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.925 ms/op


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
# Warmup Iteration   1: 3.431 ±(99.9%) 0.059 ms/op
Iteration   1: 1.918 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.918 ms/op


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
# Warmup Iteration   1: 4.704 ±(99.9%) 0.099 ms/op
Iteration   1: 3.437 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.437 ms/op


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
# Warmup Iteration   1: 3.740 ±(99.9%) 0.096 ms/op
Iteration   1: 1.915 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.852 ms/op
                 createUser·p0.50:   1.669 ms/op
                 createUser·p0.90:   2.556 ms/op
                 createUser·p0.95:   2.810 ms/op
                 createUser·p0.99:   6.078 ms/op
                 createUser·p0.999:  13.505 ms/op
                 createUser·p0.9999: 14.400 ms/op
                 createUser·p1.00:   14.631 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16700
  mean =      1.915 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1260 
    [ 1.250,  2.500) = 13426 
    [ 2.500,  3.750) = 1645 
    [ 3.750,  5.000) = 160 
    [ 5.000,  6.250) = 46 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 36 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 46 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.852 ms/op
     p(50.0000) =      1.669 ms/op
     p(90.0000) =      2.556 ms/op
     p(95.0000) =      2.810 ms/op
     p(99.0000) =      6.078 ms/op
     p(99.9000) =     13.505 ms/op
     p(99.9900) =     14.400 ms/op
     p(99.9990) =     14.631 ms/op
     p(99.9999) =     14.631 ms/op
    p(100.0000) =     14.631 ms/op


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
# Warmup Iteration   1: 3.000 ±(99.9%) 0.074 ms/op
Iteration   1: 2.159 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.360 ms/op
                 existUser·p0.50:   2.019 ms/op
                 existUser·p0.90:   2.810 ms/op
                 existUser·p0.95:   3.035 ms/op
                 existUser·p0.99:   4.792 ms/op
                 existUser·p0.999:  13.028 ms/op
                 existUser·p0.9999: 13.698 ms/op
                 existUser·p1.00:   13.713 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14820
  mean =      2.159 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 548 
    [ 1.250,  2.500) = 11055 
    [ 2.500,  3.750) = 3023 
    [ 3.750,  5.000) = 68 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 34 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.360 ms/op
     p(50.0000) =      2.019 ms/op
     p(90.0000) =      2.810 ms/op
     p(95.0000) =      3.035 ms/op
     p(99.0000) =      4.792 ms/op
     p(99.9000) =     13.028 ms/op
     p(99.9900) =     13.698 ms/op
     p(99.9990) =     13.713 ms/op
     p(99.9999) =     13.713 ms/op
    p(100.0000) =     13.713 ms/op


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
# Warmup Iteration   1: 3.211 ±(99.9%) 0.080 ms/op
Iteration   1: 1.823 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.799 ms/op
                 getUser·p0.50:   1.741 ms/op
                 getUser·p0.90:   2.154 ms/op
                 getUser·p0.95:   2.437 ms/op
                 getUser·p0.99:   3.070 ms/op
                 getUser·p0.999:  16.260 ms/op
                 getUser·p0.9999: 16.339 ms/op
                 getUser·p1.00:   16.351 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17554
  mean =      1.823 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 461 
    [ 1.250,  2.500) = 16380 
    [ 2.500,  3.750) = 642 
    [ 3.750,  5.000) = 25 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.799 ms/op
     p(50.0000) =      1.741 ms/op
     p(90.0000) =      2.154 ms/op
     p(95.0000) =      2.437 ms/op
     p(99.0000) =      3.070 ms/op
     p(99.9000) =     16.260 ms/op
     p(99.9900) =     16.339 ms/op
     p(99.9990) =     16.351 ms/op
     p(99.9999) =     16.351 ms/op
    p(100.0000) =     16.351 ms/op


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
# Warmup Iteration   1: 4.564 ±(99.9%) 0.166 ms/op
Iteration   1: 3.285 ±(99.9%) 0.036 ms/op
                 listUser·p0.00:   1.268 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   4.051 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   6.333 ms/op
                 listUser·p0.999:  16.470 ms/op
                 listUser·p0.9999: 17.269 ms/op
                 listUser·p1.00:   17.269 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9731
  mean =      3.285 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 565 
    [ 2.500,  3.750) = 7082 
    [ 3.750,  5.000) = 1909 
    [ 5.000,  6.250) = 73 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.268 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      4.051 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      6.333 ms/op
     p(99.9000) =     16.470 ms/op
     p(99.9900) =     17.269 ms/op
     p(99.9990) =     17.269 ms/op
     p(99.9999) =     17.269 ms/op
    p(100.0000) =     17.269 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.843          ops/ms
ClientSimple.existUser                       thrpt         12.429          ops/ms
ClientSimple.getUser                         thrpt         13.137          ops/ms
ClientSimple.listUser                        thrpt          8.382          ops/ms
ClientSimple.createUser                       avgt          2.148           ms/op
ClientSimple.existUser                        avgt          1.925           ms/op
ClientSimple.getUser                          avgt          1.918           ms/op
ClientSimple.listUser                         avgt          3.437           ms/op
ClientSimple.createUser                     sample  16700   1.915 ± 0.027   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.852           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.669           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.556           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.810           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.078           ms/op
ClientSimple.createUser:createUser·p0.999   sample         13.505           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.400           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.631           ms/op
ClientSimple.existUser                      sample  14820   2.159 ± 0.023   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.360           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.019           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.810           ms/op
ClientSimple.existUser:existUser·p0.95      sample          3.035           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.792           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.028           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.698           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.713           ms/op
ClientSimple.getUser                        sample  17554   1.823 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.799           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.741           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.154           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.437           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.070           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.260           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.339           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.351           ms/op
ClientSimple.listUser                       sample   9731   3.285 ± 0.036   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.268           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.986           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.051           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.284           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.333           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.470           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.269           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.269           ms/op

Benchmark result is saved to 1722708302834.json
