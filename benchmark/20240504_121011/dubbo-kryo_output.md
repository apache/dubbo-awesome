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
# Warmup Iteration   1: 1.632 ops/ms
Iteration   1: 7.394 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.394 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.360 ops/ms
Iteration   1: 13.076 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.076 ops/ms


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
# Warmup Iteration   1: 5.060 ops/ms
Iteration   1: 13.280 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.280 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.552 ops/ms
Iteration   1: 8.668 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.668 ops/ms


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
# Warmup Iteration   1: 3.892 ±(99.9%) 0.073 ms/op
Iteration   1: 2.075 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.075 ms/op


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
# Warmup Iteration   1: 4.001 ±(99.9%) 0.072 ms/op
Iteration   1: 2.023 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.023 ms/op


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
# Warmup Iteration   1: 3.517 ±(99.9%) 0.067 ms/op
Iteration   1: 1.990 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.990 ms/op


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
# Warmup Iteration   1: 4.358 ±(99.9%) 0.083 ms/op
Iteration   1: 3.608 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.608 ms/op


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
# Warmup Iteration   1: 3.478 ±(99.9%) 0.089 ms/op
Iteration   1: 2.302 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.525 ms/op
                 createUser·p0.50:   2.150 ms/op
                 createUser·p0.90:   2.798 ms/op
                 createUser·p0.95:   3.006 ms/op
                 createUser·p0.99:   8.880 ms/op
                 createUser·p0.999:  15.402 ms/op
                 createUser·p0.9999: 18.672 ms/op
                 createUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13955
  mean =      2.302 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 282 
    [ 1.250,  2.500) = 10199 
    [ 2.500,  3.750) = 3110 
    [ 3.750,  5.000) = 77 
    [ 5.000,  6.250) = 41 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 75 
    [ 8.750, 10.000) = 50 
    [10.000, 11.250) = 37 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.525 ms/op
     p(50.0000) =      2.150 ms/op
     p(90.0000) =      2.798 ms/op
     p(95.0000) =      3.006 ms/op
     p(99.0000) =      8.880 ms/op
     p(99.9000) =     15.402 ms/op
     p(99.9900) =     18.672 ms/op
     p(99.9990) =     18.711 ms/op
     p(99.9999) =     18.711 ms/op
    p(100.0000) =     18.711 ms/op


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
# Warmup Iteration   1: 2.920 ±(99.9%) 0.071 ms/op
Iteration   1: 1.970 ±(99.9%) 0.035 ms/op
                 existUser·p0.00:   0.279 ms/op
                 existUser·p0.50:   1.833 ms/op
                 existUser·p0.90:   2.388 ms/op
                 existUser·p0.95:   2.892 ms/op
                 existUser·p0.99:   5.523 ms/op
                 existUser·p0.999:  23.495 ms/op
                 existUser·p0.9999: 25.569 ms/op
                 existUser·p1.00:   28.836 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16230
  mean =      1.970 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15082 
    [ 2.500,  5.000) = 907 
    [ 5.000,  7.500) = 148 
    [ 7.500, 10.000) = 22 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.279 ms/op
     p(50.0000) =      1.833 ms/op
     p(90.0000) =      2.388 ms/op
     p(95.0000) =      2.892 ms/op
     p(99.0000) =      5.523 ms/op
     p(99.9000) =     23.495 ms/op
     p(99.9900) =     25.569 ms/op
     p(99.9990) =     28.836 ms/op
     p(99.9999) =     28.836 ms/op
    p(100.0000) =     28.836 ms/op


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
# Warmup Iteration   1: 3.264 ±(99.9%) 0.093 ms/op
Iteration   1: 1.829 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.509 ms/op
                 getUser·p0.50:   1.552 ms/op
                 getUser·p0.90:   2.780 ms/op
                 getUser·p0.95:   2.982 ms/op
                 getUser·p0.99:   4.327 ms/op
                 getUser·p0.999:  12.034 ms/op
                 getUser·p0.9999: 12.276 ms/op
                 getUser·p1.00:   12.288 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17483
  mean =      1.829 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2098 
    [ 1.250,  2.500) = 12727 
    [ 2.500,  3.750) = 2407 
    [ 3.750,  5.000) = 104 
    [ 5.000,  6.250) = 91 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.509 ms/op
     p(50.0000) =      1.552 ms/op
     p(90.0000) =      2.780 ms/op
     p(95.0000) =      2.982 ms/op
     p(99.0000) =      4.327 ms/op
     p(99.9000) =     12.034 ms/op
     p(99.9900) =     12.276 ms/op
     p(99.9990) =     12.288 ms/op
     p(99.9999) =     12.288 ms/op
    p(100.0000) =     12.288 ms/op


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
# Warmup Iteration   1: 4.423 ±(99.9%) 0.146 ms/op
Iteration   1: 3.631 ±(99.9%) 0.039 ms/op
                 listUser·p0.00:   0.876 ms/op
                 listUser·p0.50:   3.617 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   6.447 ms/op
                 listUser·p0.999:  17.993 ms/op
                 listUser·p0.9999: 18.678 ms/op
                 listUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8895
  mean =      3.631 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 22 
    [ 1.250,  2.500) = 437 
    [ 2.500,  3.750) = 4796 
    [ 3.750,  5.000) = 3356 
    [ 5.000,  6.250) = 172 
    [ 6.250,  7.500) = 81 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.876 ms/op
     p(50.0000) =      3.617 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      6.447 ms/op
     p(99.9000) =     17.993 ms/op
     p(99.9900) =     18.678 ms/op
     p(99.9990) =     18.678 ms/op
     p(99.9999) =     18.678 ms/op
    p(100.0000) =     18.678 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.394          ops/ms
ClientSimple.existUser                       thrpt         13.076          ops/ms
ClientSimple.getUser                         thrpt         13.280          ops/ms
ClientSimple.listUser                        thrpt          8.668          ops/ms
ClientSimple.createUser                       avgt          2.075           ms/op
ClientSimple.existUser                        avgt          2.023           ms/op
ClientSimple.getUser                          avgt          1.990           ms/op
ClientSimple.listUser                         avgt          3.608           ms/op
ClientSimple.createUser                     sample  13955   2.302 ± 0.033   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.525           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.150           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.798           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.006           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.880           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.402           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.672           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.711           ms/op
ClientSimple.existUser                      sample  16230   1.970 ± 0.035   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.279           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.833           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.388           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.892           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.523           ms/op
ClientSimple.existUser:existUser·p0.999     sample         23.495           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         25.569           ms/op
ClientSimple.existUser:existUser·p1.00      sample         28.836           ms/op
ClientSimple.getUser                        sample  17483   1.829 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.509           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.552           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.780           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.982           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.327           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.034           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.276           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.288           ms/op
ClientSimple.listUser                       sample   8895   3.631 ± 0.039   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.876           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.617           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.399           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.653           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.447           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.993           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.678           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.678           ms/op

Benchmark result is saved to 1714824336049.json
