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
# Warmup Iteration   1: 1.877 ops/ms
Iteration   1: 7.453 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.453 ops/ms


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
# Warmup Iteration   1: 5.777 ops/ms
Iteration   1: 11.954 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.954 ops/ms


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
# Warmup Iteration   1: 5.228 ops/ms
Iteration   1: 11.889 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.889 ops/ms


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
# Warmup Iteration   1: 5.205 ops/ms
Iteration   1: 9.095 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.095 ops/ms


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
# Warmup Iteration   1: 4.026 ±(99.9%) 0.074 ms/op
Iteration   1: 2.156 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.156 ms/op


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
# Warmup Iteration   1: 3.114 ±(99.9%) 0.053 ms/op
Iteration   1: 1.916 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.916 ms/op


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
# Warmup Iteration   1: 3.286 ±(99.9%) 0.060 ms/op
Iteration   1: 1.985 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.985 ms/op


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
# Warmup Iteration   1: 4.591 ±(99.9%) 0.103 ms/op
Iteration   1: 3.712 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.712 ms/op


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
# Warmup Iteration   1: 3.611 ±(99.9%) 0.089 ms/op
Iteration   1: 2.302 ±(99.9%) 0.045 ms/op
                 createUser·p0.00:   0.605 ms/op
                 createUser·p0.50:   2.089 ms/op
                 createUser·p0.90:   2.666 ms/op
                 createUser·p0.95:   2.860 ms/op
                 createUser·p0.99:   13.009 ms/op
                 createUser·p0.999:  19.104 ms/op
                 createUser·p0.9999: 20.362 ms/op
                 createUser·p1.00:   20.414 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13994
  mean =      2.302 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11528 
    [ 2.500,  5.000) = 2223 
    [ 5.000,  7.500) = 24 
    [ 7.500, 10.000) = 27 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.605 ms/op
     p(50.0000) =      2.089 ms/op
     p(90.0000) =      2.666 ms/op
     p(95.0000) =      2.860 ms/op
     p(99.0000) =     13.009 ms/op
     p(99.9000) =     19.104 ms/op
     p(99.9900) =     20.362 ms/op
     p(99.9990) =     20.414 ms/op
     p(99.9999) =     20.414 ms/op
    p(100.0000) =     20.414 ms/op


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
# Warmup Iteration   1: 2.783 ±(99.9%) 0.061 ms/op
Iteration   1: 1.993 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.799 ms/op
                 existUser·p0.50:   1.915 ms/op
                 existUser·p0.90:   2.433 ms/op
                 existUser·p0.95:   2.601 ms/op
                 existUser·p0.99:   3.109 ms/op
                 existUser·p0.999:  11.289 ms/op
                 existUser·p0.9999: 11.816 ms/op
                 existUser·p1.00:   11.846 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16095
  mean =      1.993 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 305 
    [ 1.250,  2.500) = 14540 
    [ 2.500,  3.750) = 1158 
    [ 3.750,  5.000) = 22 
    [ 5.000,  6.250) = 6 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.799 ms/op
     p(50.0000) =      1.915 ms/op
     p(90.0000) =      2.433 ms/op
     p(95.0000) =      2.601 ms/op
     p(99.0000) =      3.109 ms/op
     p(99.9000) =     11.289 ms/op
     p(99.9900) =     11.816 ms/op
     p(99.9990) =     11.846 ms/op
     p(99.9999) =     11.846 ms/op
    p(100.0000) =     11.846 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 3.359 ±(99.9%) 0.093 ms/op
Iteration   1: 2.202 ±(99.9%) 0.035 ms/op
                 getUser·p0.00:   0.443 ms/op
                 getUser·p0.50:   1.913 ms/op
                 getUser·p0.90:   3.396 ms/op
                 getUser·p0.95:   3.637 ms/op
                 getUser·p0.99:   4.248 ms/op
                 getUser·p0.999:  20.251 ms/op
                 getUser·p0.9999: 20.382 ms/op
                 getUser·p1.00:   20.382 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14549
  mean =      2.202 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11551 
    [ 2.500,  5.000) = 2887 
    [ 5.000,  7.500) = 46 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.443 ms/op
     p(50.0000) =      1.913 ms/op
     p(90.0000) =      3.396 ms/op
     p(95.0000) =      3.637 ms/op
     p(99.0000) =      4.248 ms/op
     p(99.9000) =     20.251 ms/op
     p(99.9900) =     20.382 ms/op
     p(99.9990) =     20.382 ms/op
     p(99.9999) =     20.382 ms/op
    p(100.0000) =     20.382 ms/op


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
# Warmup Iteration   1: 4.239 ±(99.9%) 0.107 ms/op
Iteration   1: 3.087 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   0.738 ms/op
                 listUser·p0.50:   2.814 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   6.951 ms/op
                 listUser·p0.999:  7.672 ms/op
                 listUser·p0.9999: 7.774 ms/op
                 listUser·p1.00:   7.774 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10424
  mean =      3.087 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 1 
    [1.000, 1.500) = 8 
    [1.500, 2.000) = 39 
    [2.000, 2.500) = 725 
    [2.500, 3.000) = 5780 
    [3.000, 3.500) = 1784 
    [3.500, 4.000) = 1197 
    [4.000, 4.500) = 556 
    [4.500, 5.000) = 48 
    [5.000, 5.500) = 88 
    [5.500, 6.000) = 31 
    [6.000, 6.500) = 24 
    [6.500, 7.000) = 42 
    [7.000, 7.500) = 63 

  Percentiles, ms/op:
      p(0.0000) =      0.738 ms/op
     p(50.0000) =      2.814 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      6.951 ms/op
     p(99.9000) =      7.672 ms/op
     p(99.9900) =      7.774 ms/op
     p(99.9990) =      7.774 ms/op
     p(99.9999) =      7.774 ms/op
    p(100.0000) =      7.774 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.453          ops/ms
ClientSimple.existUser                       thrpt         11.954          ops/ms
ClientSimple.getUser                         thrpt         11.889          ops/ms
ClientSimple.listUser                        thrpt          9.095          ops/ms
ClientSimple.createUser                       avgt          2.156           ms/op
ClientSimple.existUser                        avgt          1.916           ms/op
ClientSimple.getUser                          avgt          1.985           ms/op
ClientSimple.listUser                         avgt          3.712           ms/op
ClientSimple.createUser                     sample  13994   2.302 ± 0.045   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.605           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.089           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.666           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.860           ms/op
ClientSimple.createUser:createUser·p0.99    sample         13.009           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.104           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.362           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.414           ms/op
ClientSimple.existUser                      sample  16095   1.993 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.799           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.915           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.433           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.601           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.109           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.289           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.816           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.846           ms/op
ClientSimple.getUser                        sample  14549   2.202 ± 0.035   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.443           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.913           ms/op
ClientSimple.getUser:getUser·p0.90          sample          3.396           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.637           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.248           ms/op
ClientSimple.getUser:getUser·p0.999         sample         20.251           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         20.382           ms/op
ClientSimple.getUser:getUser·p1.00          sample         20.382           ms/op
ClientSimple.listUser                       sample  10424   3.087 ± 0.025   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.738           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.814           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.928           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.235           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.951           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.672           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.774           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.774           ms/op

Benchmark result is saved to 1725322645074.json
