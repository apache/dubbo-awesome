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
# Warmup Iteration   1: 1.951 ops/ms
Iteration   1: 6.952 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.952 ops/ms


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
# Warmup Iteration   1: 5.675 ops/ms
Iteration   1: 13.166 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.166 ops/ms


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
# Warmup Iteration   1: 6.178 ops/ms
Iteration   1: 14.287 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.287 ops/ms


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
# Warmup Iteration   1: 5.889 ops/ms
Iteration   1: 8.956 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.956 ops/ms


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
# Warmup Iteration   1: 3.609 ±(99.9%) 0.076 ms/op
Iteration   1: 2.377 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.377 ms/op


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
# Warmup Iteration   1: 3.191 ±(99.9%) 0.055 ms/op
Iteration   1: 2.138 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.138 ms/op


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
# Warmup Iteration   1: 3.423 ±(99.9%) 0.059 ms/op
Iteration   1: 1.889 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.889 ms/op


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
# Warmup Iteration   1: 4.612 ±(99.9%) 0.085 ms/op
Iteration   1: 3.209 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.209 ms/op


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
# Warmup Iteration   1: 3.566 ±(99.9%) 0.093 ms/op
Iteration   1: 2.273 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.478 ms/op
                 createUser·p0.50:   2.093 ms/op
                 createUser·p0.90:   2.712 ms/op
                 createUser·p0.95:   3.091 ms/op
                 createUser·p0.99:   8.258 ms/op
                 createUser·p0.999:  22.933 ms/op
                 createUser·p0.9999: 23.127 ms/op
                 createUser·p1.00:   23.167 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14065
  mean =      2.273 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11207 
    [ 2.500,  5.000) = 2523 
    [ 5.000,  7.500) = 157 
    [ 7.500, 10.000) = 98 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.478 ms/op
     p(50.0000) =      2.093 ms/op
     p(90.0000) =      2.712 ms/op
     p(95.0000) =      3.091 ms/op
     p(99.0000) =      8.258 ms/op
     p(99.9000) =     22.933 ms/op
     p(99.9900) =     23.127 ms/op
     p(99.9990) =     23.167 ms/op
     p(99.9999) =     23.167 ms/op
    p(100.0000) =     23.167 ms/op


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
# Warmup Iteration   1: 2.901 ±(99.9%) 0.066 ms/op
Iteration   1: 1.895 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.651 ms/op
                 existUser·p0.50:   1.759 ms/op
                 existUser·p0.90:   2.494 ms/op
                 existUser·p0.95:   2.679 ms/op
                 existUser·p0.99:   3.244 ms/op
                 existUser·p0.999:  15.928 ms/op
                 existUser·p0.9999: 16.247 ms/op
                 existUser·p1.00:   16.269 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16855
  mean =      1.895 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 998 
    [ 1.250,  2.500) = 14196 
    [ 2.500,  3.750) = 1551 
    [ 3.750,  5.000) = 45 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.651 ms/op
     p(50.0000) =      1.759 ms/op
     p(90.0000) =      2.494 ms/op
     p(95.0000) =      2.679 ms/op
     p(99.0000) =      3.244 ms/op
     p(99.9000) =     15.928 ms/op
     p(99.9900) =     16.247 ms/op
     p(99.9990) =     16.269 ms/op
     p(99.9999) =     16.269 ms/op
    p(100.0000) =     16.269 ms/op


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
# Warmup Iteration   1: 3.169 ±(99.9%) 0.080 ms/op
Iteration   1: 1.975 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.569 ms/op
                 getUser·p0.50:   1.923 ms/op
                 getUser·p0.90:   2.408 ms/op
                 getUser·p0.95:   2.535 ms/op
                 getUser·p0.99:   2.961 ms/op
                 getUser·p0.999:  17.746 ms/op
                 getUser·p0.9999: 18.689 ms/op
                 getUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16610
  mean =      1.975 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 463 
    [ 1.250,  2.500) = 15145 
    [ 2.500,  3.750) = 951 
    [ 3.750,  5.000) = 8 
    [ 5.000,  6.250) = 10 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.569 ms/op
     p(50.0000) =      1.923 ms/op
     p(90.0000) =      2.408 ms/op
     p(95.0000) =      2.535 ms/op
     p(99.0000) =      2.961 ms/op
     p(99.9000) =     17.746 ms/op
     p(99.9900) =     18.689 ms/op
     p(99.9990) =     18.711 ms/op
     p(99.9999) =     18.711 ms/op
    p(100.0000) =     18.711 ms/op


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
# Warmup Iteration   1: 4.441 ±(99.9%) 0.141 ms/op
Iteration   1: 3.278 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   0.813 ms/op
                 listUser·p0.50:   3.146 ms/op
                 listUser·p0.90:   4.284 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   4.966 ms/op
                 listUser·p0.999:  6.181 ms/op
                 listUser·p0.9999: 6.791 ms/op
                 listUser·p1.00:   6.791 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9784
  mean =      3.278 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 4 
    [1.000, 1.500) = 34 
    [1.500, 2.000) = 56 
    [2.000, 2.500) = 729 
    [2.500, 3.000) = 3367 
    [3.000, 3.500) = 2345 
    [3.500, 4.000) = 1433 
    [4.000, 4.500) = 1241 
    [4.500, 5.000) = 479 
    [5.000, 5.500) = 75 
    [5.500, 6.000) = 9 
    [6.000, 6.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.813 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      4.966 ms/op
     p(99.9000) =      6.181 ms/op
     p(99.9900) =      6.791 ms/op
     p(99.9990) =      6.791 ms/op
     p(99.9999) =      6.791 ms/op
    p(100.0000) =      6.791 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.952          ops/ms
ClientSimple.existUser                       thrpt         13.166          ops/ms
ClientSimple.getUser                         thrpt         14.287          ops/ms
ClientSimple.listUser                        thrpt          8.956          ops/ms
ClientSimple.createUser                       avgt          2.377           ms/op
ClientSimple.existUser                        avgt          2.138           ms/op
ClientSimple.getUser                          avgt          1.889           ms/op
ClientSimple.listUser                         avgt          3.209           ms/op
ClientSimple.createUser                     sample  14065   2.273 ± 0.037   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.478           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.093           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.712           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.091           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.258           ms/op
ClientSimple.createUser:createUser·p0.999   sample         22.933           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.127           ms/op
ClientSimple.createUser:createUser·p1.00    sample         23.167           ms/op
ClientSimple.existUser                      sample  16855   1.895 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.651           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.759           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.494           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.679           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.244           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.928           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.247           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.269           ms/op
ClientSimple.getUser                        sample  16610   1.975 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.569           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.923           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.408           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.535           ms/op
ClientSimple.getUser:getUser·p0.99          sample          2.961           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.746           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.689           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.711           ms/op
ClientSimple.listUser                       sample   9784   3.278 ± 0.023   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.813           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.146           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.284           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.555           ms/op
ClientSimple.listUser:listUser·p0.99        sample          4.966           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.181           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          6.791           ms/op
ClientSimple.listUser:listUser·p1.00        sample          6.791           ms/op

Benchmark result is saved to 1724220359469.json
