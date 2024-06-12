# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.558 ops/ms
Iteration   1: 6.540 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.540 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 6.025 ops/ms
Iteration   1: 13.681 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.681 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.736 ops/ms
Iteration   1: 11.761 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.761 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.499 ops/ms
Iteration   1: 7.508 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.508 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.435 ±(99.9%) 0.074 ms/op
Iteration   1: 2.217 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.217 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.539 ±(99.9%) 0.050 ms/op
Iteration   1: 2.009 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.009 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.968 ±(99.9%) 0.081 ms/op
Iteration   1: 2.454 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.454 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.054 ±(99.9%) 0.143 ms/op
Iteration   1: 3.703 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.703 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.489 ±(99.9%) 0.103 ms/op
Iteration   1: 2.407 ±(99.9%) 0.041 ms/op
                 createUser·p0.00:   0.865 ms/op
                 createUser·p0.50:   2.204 ms/op
                 createUser·p0.90:   2.765 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   9.420 ms/op
                 createUser·p0.999:  19.749 ms/op
                 createUser·p0.9999: 21.585 ms/op
                 createUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13300
  mean =      2.407 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10448 
    [ 2.500,  5.000) = 2508 
    [ 5.000,  7.500) = 160 
    [ 7.500, 10.000) = 78 
    [10.000, 12.500) = 9 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.865 ms/op
     p(50.0000) =      2.204 ms/op
     p(90.0000) =      2.765 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      9.420 ms/op
     p(99.9000) =     19.749 ms/op
     p(99.9900) =     21.585 ms/op
     p(99.9990) =     21.791 ms/op
     p(99.9999) =     21.791 ms/op
    p(100.0000) =     21.791 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.989 ±(99.9%) 0.079 ms/op
Iteration   1: 1.871 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.703 ms/op
                 existUser·p0.50:   1.769 ms/op
                 existUser·p0.90:   2.408 ms/op
                 existUser·p0.95:   2.601 ms/op
                 existUser·p0.99:   3.594 ms/op
                 existUser·p0.999:  16.938 ms/op
                 existUser·p0.9999: 17.228 ms/op
                 existUser·p1.00:   17.367 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17088
  mean =      1.871 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 884 
    [ 1.250,  2.500) = 14982 
    [ 2.500,  3.750) = 1082 
    [ 3.750,  5.000) = 65 
    [ 5.000,  6.250) = 5 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 35 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.703 ms/op
     p(50.0000) =      1.769 ms/op
     p(90.0000) =      2.408 ms/op
     p(95.0000) =      2.601 ms/op
     p(99.0000) =      3.594 ms/op
     p(99.9000) =     16.938 ms/op
     p(99.9900) =     17.228 ms/op
     p(99.9990) =     17.367 ms/op
     p(99.9999) =     17.367 ms/op
    p(100.0000) =     17.367 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.116 ±(99.9%) 0.085 ms/op
Iteration   1: 2.238 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.874 ms/op
                 getUser·p0.50:   2.122 ms/op
                 getUser·p0.90:   2.867 ms/op
                 getUser·p0.95:   3.281 ms/op
                 getUser·p0.99:   4.527 ms/op
                 getUser·p0.999:  12.724 ms/op
                 getUser·p0.9999: 13.166 ms/op
                 getUser·p1.00:   13.173 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14367
  mean =      2.238 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 85 
    [ 1.250,  2.500) = 10722 
    [ 2.500,  3.750) = 3139 
    [ 3.750,  5.000) = 333 
    [ 5.000,  6.250) = 56 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.874 ms/op
     p(50.0000) =      2.122 ms/op
     p(90.0000) =      2.867 ms/op
     p(95.0000) =      3.281 ms/op
     p(99.0000) =      4.527 ms/op
     p(99.9000) =     12.724 ms/op
     p(99.9900) =     13.166 ms/op
     p(99.9990) =     13.173 ms/op
     p(99.9999) =     13.173 ms/op
    p(100.0000) =     13.173 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 5.447 ±(99.9%) 0.153 ms/op
Iteration   1: 3.604 ±(99.9%) 0.046 ms/op
                 listUser·p0.00:   1.329 ms/op
                 listUser·p0.50:   3.564 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.923 ms/op
                 listUser·p0.99:   7.610 ms/op
                 listUser·p0.999:  19.530 ms/op
                 listUser·p0.9999: 20.414 ms/op
                 listUser·p1.00:   20.414 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8870
  mean =      3.604 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1051 
    [ 2.500,  5.000) = 7396 
    [ 5.000,  7.500) = 333 
    [ 7.500, 10.000) = 56 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.329 ms/op
     p(50.0000) =      3.564 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.923 ms/op
     p(99.0000) =      7.610 ms/op
     p(99.9000) =     19.530 ms/op
     p(99.9900) =     20.414 ms/op
     p(99.9990) =     20.414 ms/op
     p(99.9999) =     20.414 ms/op
    p(100.0000) =     20.414 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.540          ops/ms
ClientSimple.existUser                       thrpt         13.681          ops/ms
ClientSimple.getUser                         thrpt         11.761          ops/ms
ClientSimple.listUser                        thrpt          7.508          ops/ms
ClientSimple.createUser                       avgt          2.217           ms/op
ClientSimple.existUser                        avgt          2.009           ms/op
ClientSimple.getUser                          avgt          2.454           ms/op
ClientSimple.listUser                         avgt          3.703           ms/op
ClientSimple.createUser                     sample  13300   2.407 ± 0.041   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.865           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.204           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.765           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.203           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.420           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.749           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.585           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.791           ms/op
ClientSimple.existUser                      sample  17088   1.871 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.703           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.769           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.408           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.601           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.594           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.938           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.228           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.367           ms/op
ClientSimple.getUser                        sample  14367   2.238 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.874           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.122           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.867           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.281           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.527           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.724           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.166           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.173           ms/op
ClientSimple.listUser                       sample   8870   3.604 ± 0.046   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.329           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.564           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.432           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.923           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.610           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.530           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.414           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.414           ms/op

Benchmark result is saved to 1718193994528.json
