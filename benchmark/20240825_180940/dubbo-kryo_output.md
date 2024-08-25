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
# Warmup Iteration   1: 1.927 ops/ms
Iteration   1: 7.327 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.327 ops/ms


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
# Warmup Iteration   1: 6.464 ops/ms
Iteration   1: 13.172 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.172 ops/ms


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
# Warmup Iteration   1: 5.340 ops/ms
Iteration   1: 12.801 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.801 ops/ms


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
# Warmup Iteration   1: 5.879 ops/ms
Iteration   1: 8.626 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.626 ops/ms


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
# Warmup Iteration   1: 3.840 ±(99.9%) 0.074 ms/op
Iteration   1: 2.040 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.040 ms/op


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
# Warmup Iteration   1: 2.938 ±(99.9%) 0.041 ms/op
Iteration   1: 2.104 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.104 ms/op


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
# Warmup Iteration   1: 3.104 ±(99.9%) 0.065 ms/op
Iteration   1: 1.837 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.837 ms/op


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
# Warmup Iteration   1: 4.391 ±(99.9%) 0.087 ms/op
Iteration   1: 3.160 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.160 ms/op


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
# Warmup Iteration   1: 3.491 ±(99.9%) 0.089 ms/op
Iteration   1: 2.098 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.758 ms/op
                 createUser·p0.50:   1.911 ms/op
                 createUser·p0.90:   2.638 ms/op
                 createUser·p0.95:   2.834 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  27.263 ms/op
                 createUser·p0.9999: 27.439 ms/op
                 createUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15234
  mean =      2.098 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12885 
    [ 2.500,  5.000) = 2228 
    [ 5.000,  7.500) = 24 
    [ 7.500, 10.000) = 33 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.758 ms/op
     p(50.0000) =      1.911 ms/op
     p(90.0000) =      2.638 ms/op
     p(95.0000) =      2.834 ms/op
     p(99.0000) =      4.555 ms/op
     p(99.9000) =     27.263 ms/op
     p(99.9900) =     27.439 ms/op
     p(99.9990) =     27.525 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


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
# Warmup Iteration   1: 3.206 ±(99.9%) 0.080 ms/op
Iteration   1: 1.711 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.524 ms/op
                 existUser·p0.50:   1.597 ms/op
                 existUser·p0.90:   2.077 ms/op
                 existUser·p0.95:   2.224 ms/op
                 existUser·p0.99:   3.376 ms/op
                 existUser·p0.999:  16.127 ms/op
                 existUser·p0.9999: 17.118 ms/op
                 existUser·p1.00:   17.203 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18686
  mean =      1.711 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 498 
    [ 1.250,  2.500) = 17782 
    [ 2.500,  3.750) = 290 
    [ 3.750,  5.000) = 22 
    [ 5.000,  6.250) = 14 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.524 ms/op
     p(50.0000) =      1.597 ms/op
     p(90.0000) =      2.077 ms/op
     p(95.0000) =      2.224 ms/op
     p(99.0000) =      3.376 ms/op
     p(99.9000) =     16.127 ms/op
     p(99.9900) =     17.118 ms/op
     p(99.9990) =     17.203 ms/op
     p(99.9999) =     17.203 ms/op
    p(100.0000) =     17.203 ms/op


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
# Warmup Iteration   1: 3.015 ±(99.9%) 0.079 ms/op
Iteration   1: 1.967 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   0.585 ms/op
                 getUser·p0.50:   1.769 ms/op
                 getUser·p0.90:   2.568 ms/op
                 getUser·p0.95:   2.796 ms/op
                 getUser·p0.99:   3.946 ms/op
                 getUser·p0.999:  19.316 ms/op
                 getUser·p0.9999: 20.193 ms/op
                 getUser·p1.00:   20.316 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16265
  mean =      1.967 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14423 
    [ 2.500,  5.000) = 1756 
    [ 5.000,  7.500) = 22 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.585 ms/op
     p(50.0000) =      1.769 ms/op
     p(90.0000) =      2.568 ms/op
     p(95.0000) =      2.796 ms/op
     p(99.0000) =      3.946 ms/op
     p(99.9000) =     19.316 ms/op
     p(99.9900) =     20.193 ms/op
     p(99.9990) =     20.316 ms/op
     p(99.9999) =     20.316 ms/op
    p(100.0000) =     20.316 ms/op


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
# Warmup Iteration   1: 4.243 ±(99.9%) 0.115 ms/op
Iteration   1: 3.351 ±(99.9%) 0.040 ms/op
                 listUser·p0.00:   0.827 ms/op
                 listUser·p0.50:   3.314 ms/op
                 listUser·p0.90:   4.157 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   6.512 ms/op
                 listUser·p0.999:  18.544 ms/op
                 listUser·p0.9999: 19.268 ms/op
                 listUser·p1.00:   19.268 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9535
  mean =      3.351 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 1821 
    [ 2.500,  3.750) = 4718 
    [ 3.750,  5.000) = 2786 
    [ 5.000,  6.250) = 101 
    [ 6.250,  7.500) = 68 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.827 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      4.157 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      6.512 ms/op
     p(99.9000) =     18.544 ms/op
     p(99.9900) =     19.268 ms/op
     p(99.9990) =     19.268 ms/op
     p(99.9999) =     19.268 ms/op
    p(100.0000) =     19.268 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.327          ops/ms
ClientSimple.existUser                       thrpt         13.172          ops/ms
ClientSimple.getUser                         thrpt         12.801          ops/ms
ClientSimple.listUser                        thrpt          8.626          ops/ms
ClientSimple.createUser                       avgt          2.040           ms/op
ClientSimple.existUser                        avgt          2.104           ms/op
ClientSimple.getUser                          avgt          1.837           ms/op
ClientSimple.listUser                         avgt          3.160           ms/op
ClientSimple.createUser                     sample  15234   2.098 ± 0.037   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.758           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.911           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.638           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.834           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.555           ms/op
ClientSimple.createUser:createUser·p0.999   sample         27.263           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         27.439           ms/op
ClientSimple.createUser:createUser·p1.00    sample         27.525           ms/op
ClientSimple.existUser                      sample  18686   1.711 ± 0.020   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.524           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.597           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.077           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.224           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.376           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.127           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.118           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.203           ms/op
ClientSimple.getUser                        sample  16265   1.967 ± 0.028   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.585           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.769           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.568           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.796           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.946           ms/op
ClientSimple.getUser:getUser·p0.999         sample         19.316           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         20.193           ms/op
ClientSimple.getUser:getUser·p1.00          sample         20.316           ms/op
ClientSimple.listUser                       sample   9535   3.351 ± 0.040   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.827           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.314           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.157           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.506           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.512           ms/op
ClientSimple.listUser:listUser·p0.999       sample         18.544           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.268           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.268           ms/op

Benchmark result is saved to 1724609092924.json
