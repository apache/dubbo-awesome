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
# Warmup Iteration   1: 1.617 ops/ms
Iteration   1: 6.284 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.284 ops/ms


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
# Warmup Iteration   1: 4.936 ops/ms
Iteration   1: 11.626 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.626 ops/ms


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
# Warmup Iteration   1: 4.544 ops/ms
Iteration   1: 11.406 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.406 ops/ms


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
# Warmup Iteration   1: 4.423 ops/ms
Iteration   1: 10.190 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  10.190 ops/ms


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
# Warmup Iteration   1: 4.107 ±(99.9%) 0.069 ms/op
Iteration   1: 2.313 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.313 ms/op


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
# Warmup Iteration   1: 3.902 ±(99.9%) 0.076 ms/op
Iteration   1: 2.143 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.143 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:43
# Fork: 1 of 1
# Warmup Iteration   1: 3.134 ±(99.9%) 0.067 ms/op
Iteration   1: 2.062 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.062 ms/op


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
# Warmup Iteration   1: 4.690 ±(99.9%) 0.091 ms/op
Iteration   1: 3.256 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.256 ms/op


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
# Warmup Iteration   1: 3.824 ±(99.9%) 0.120 ms/op
Iteration   1: 2.199 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.773 ms/op
                 createUser·p0.50:   1.944 ms/op
                 createUser·p0.90:   2.712 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   6.231 ms/op
                 createUser·p0.999:  19.628 ms/op
                 createUser·p0.9999: 21.291 ms/op
                 createUser·p1.00:   21.529 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14525
  mean =      2.199 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11937 
    [ 2.500,  5.000) = 2225 
    [ 5.000,  7.500) = 234 
    [ 7.500, 10.000) = 65 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.773 ms/op
     p(50.0000) =      1.944 ms/op
     p(90.0000) =      2.712 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      6.231 ms/op
     p(99.9000) =     19.628 ms/op
     p(99.9900) =     21.291 ms/op
     p(99.9990) =     21.529 ms/op
     p(99.9999) =     21.529 ms/op
    p(100.0000) =     21.529 ms/op


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
# Warmup Iteration   1: 3.152 ±(99.9%) 0.079 ms/op
Iteration   1: 1.754 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.361 ms/op
                 existUser·p0.50:   1.626 ms/op
                 existUser·p0.90:   2.273 ms/op
                 existUser·p0.95:   2.474 ms/op
                 existUser·p0.99:   4.547 ms/op
                 existUser·p0.999:  16.515 ms/op
                 existUser·p0.9999: 17.930 ms/op
                 existUser·p1.00:   17.957 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18323
  mean =      1.754 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2008 
    [ 1.250,  2.500) = 15504 
    [ 2.500,  3.750) = 580 
    [ 3.750,  5.000) = 119 
    [ 5.000,  6.250) = 27 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.361 ms/op
     p(50.0000) =      1.626 ms/op
     p(90.0000) =      2.273 ms/op
     p(95.0000) =      2.474 ms/op
     p(99.0000) =      4.547 ms/op
     p(99.9000) =     16.515 ms/op
     p(99.9900) =     17.930 ms/op
     p(99.9990) =     17.957 ms/op
     p(99.9999) =     17.957 ms/op
    p(100.0000) =     17.957 ms/op


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
# Warmup Iteration   1: 3.440 ±(99.9%) 0.098 ms/op
Iteration   1: 1.994 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.432 ms/op
                 getUser·p0.50:   1.815 ms/op
                 getUser·p0.90:   2.503 ms/op
                 getUser·p0.95:   2.740 ms/op
                 getUser·p0.99:   5.424 ms/op
                 getUser·p0.999:  14.826 ms/op
                 getUser·p0.9999: 18.940 ms/op
                 getUser·p1.00:   18.940 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16094
  mean =      1.994 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 432 
    [ 1.250,  2.500) = 14038 
    [ 2.500,  3.750) = 1285 
    [ 3.750,  5.000) = 153 
    [ 5.000,  6.250) = 62 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 50 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.432 ms/op
     p(50.0000) =      1.815 ms/op
     p(90.0000) =      2.503 ms/op
     p(95.0000) =      2.740 ms/op
     p(99.0000) =      5.424 ms/op
     p(99.9000) =     14.826 ms/op
     p(99.9900) =     18.940 ms/op
     p(99.9990) =     18.940 ms/op
     p(99.9999) =     18.940 ms/op
    p(100.0000) =     18.940 ms/op


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
# Warmup Iteration   1: 4.759 ±(99.9%) 0.143 ms/op
Iteration   1: 3.836 ±(99.9%) 0.064 ms/op
                 listUser·p0.00:   1.159 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   4.866 ms/op
                 listUser·p0.99:   6.197 ms/op
                 listUser·p0.999:  30.869 ms/op
                 listUser·p0.9999: 32.145 ms/op
                 listUser·p1.00:   32.145 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8325
  mean =      3.836 ±(99.9%) 0.064 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 283 
    [ 2.500,  5.000) = 7737 
    [ 5.000,  7.500) = 236 
    [ 7.500, 10.000) = 34 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.159 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      4.866 ms/op
     p(99.0000) =      6.197 ms/op
     p(99.9000) =     30.869 ms/op
     p(99.9900) =     32.145 ms/op
     p(99.9990) =     32.145 ms/op
     p(99.9999) =     32.145 ms/op
    p(100.0000) =     32.145 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.284          ops/ms
ClientSimple.existUser                       thrpt         11.626          ops/ms
ClientSimple.getUser                         thrpt         11.406          ops/ms
ClientSimple.listUser                        thrpt         10.190          ops/ms
ClientSimple.createUser                       avgt          2.313           ms/op
ClientSimple.existUser                        avgt          2.143           ms/op
ClientSimple.getUser                          avgt          2.062           ms/op
ClientSimple.listUser                         avgt          3.256           ms/op
ClientSimple.createUser                     sample  14525   2.199 ± 0.037   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.773           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.944           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.712           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.121           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.231           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.628           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.291           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.529           ms/op
ClientSimple.existUser                      sample  18323   1.754 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.361           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.626           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.273           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.474           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.547           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.515           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.930           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.957           ms/op
ClientSimple.getUser                        sample  16094   1.994 ± 0.025   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.432           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.815           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.503           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.740           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.424           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.826           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.940           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.940           ms/op
ClientSimple.listUser                       sample   8325   3.836 ± 0.064   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.159           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.731           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.637           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.866           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.197           ms/op
ClientSimple.listUser:listUser·p0.999       sample         30.869           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         32.145           ms/op
ClientSimple.listUser:listUser·p1.00        sample         32.145           ms/op

Benchmark result is saved to 1723140397859.json
