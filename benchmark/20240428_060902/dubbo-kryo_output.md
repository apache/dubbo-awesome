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
# Warmup Iteration   1: 1.715 ops/ms
Iteration   1: 7.288 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.288 ops/ms


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
# Warmup Iteration   1: 7.123 ops/ms
Iteration   1: 14.612 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.612 ops/ms


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
# Warmup Iteration   1: 6.549 ops/ms
Iteration   1: 14.392 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.392 ops/ms


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
# Warmup Iteration   1: 5.270 ops/ms
Iteration   1: 8.216 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.216 ops/ms


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
# Warmup Iteration   1: 3.829 ±(99.9%) 0.080 ms/op
Iteration   1: 2.154 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.154 ms/op


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
# Warmup Iteration   1: 2.981 ±(99.9%) 0.052 ms/op
Iteration   1: 1.872 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.872 ms/op


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
# Warmup Iteration   1: 3.500 ±(99.9%) 0.061 ms/op
Iteration   1: 1.862 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.862 ms/op


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
# Warmup Iteration   1: 4.358 ±(99.9%) 0.084 ms/op
Iteration   1: 3.791 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.791 ms/op


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
# Warmup Iteration   1: 3.300 ±(99.9%) 0.080 ms/op
Iteration   1: 2.126 ±(99.9%) 0.042 ms/op
                 createUser·p0.00:   0.483 ms/op
                 createUser·p0.50:   1.882 ms/op
                 createUser·p0.90:   2.474 ms/op
                 createUser·p0.95:   2.662 ms/op
                 createUser·p0.99:   9.716 ms/op
                 createUser·p0.999:  28.410 ms/op
                 createUser·p0.9999: 29.119 ms/op
                 createUser·p1.00:   29.327 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15308
  mean =      2.126 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13921 
    [ 2.500,  5.000) = 1118 
    [ 5.000,  7.500) = 105 
    [ 7.500, 10.000) = 42 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.483 ms/op
     p(50.0000) =      1.882 ms/op
     p(90.0000) =      2.474 ms/op
     p(95.0000) =      2.662 ms/op
     p(99.0000) =      9.716 ms/op
     p(99.9000) =     28.410 ms/op
     p(99.9900) =     29.119 ms/op
     p(99.9990) =     29.327 ms/op
     p(99.9999) =     29.327 ms/op
    p(100.0000) =     29.327 ms/op


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
# Warmup Iteration   1: 2.996 ±(99.9%) 0.065 ms/op
Iteration   1: 1.758 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.531 ms/op
                 existUser·p0.50:   1.702 ms/op
                 existUser·p0.90:   2.126 ms/op
                 existUser·p0.95:   2.277 ms/op
                 existUser·p0.99:   2.564 ms/op
                 existUser·p0.999:  3.096 ms/op
                 existUser·p0.9999: 4.502 ms/op
                 existUser·p1.00:   4.522 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18204
  mean =      1.758 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 43 
    [1.000, 1.500) = 2002 
    [1.500, 2.000) = 13118 
    [2.000, 2.500) = 2788 
    [2.500, 3.000) = 213 
    [3.000, 3.500) = 37 
    [3.500, 4.000) = 0 
    [4.000, 4.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.531 ms/op
     p(50.0000) =      1.702 ms/op
     p(90.0000) =      2.126 ms/op
     p(95.0000) =      2.277 ms/op
     p(99.0000) =      2.564 ms/op
     p(99.9000) =      3.096 ms/op
     p(99.9900) =      4.502 ms/op
     p(99.9990) =      4.522 ms/op
     p(99.9999) =      4.522 ms/op
    p(100.0000) =      4.522 ms/op


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
# Warmup Iteration   1: 3.323 ±(99.9%) 0.096 ms/op
Iteration   1: 2.075 ±(99.9%) 0.035 ms/op
                 getUser·p0.00:   0.646 ms/op
                 getUser·p0.50:   1.931 ms/op
                 getUser·p0.90:   2.617 ms/op
                 getUser·p0.95:   2.871 ms/op
                 getUser·p0.99:   3.808 ms/op
                 getUser·p0.999:  21.945 ms/op
                 getUser·p0.9999: 22.649 ms/op
                 getUser·p1.00:   22.774 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15433
  mean =      2.075 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13567 
    [ 2.500,  5.000) = 1766 
    [ 5.000,  7.500) = 36 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.646 ms/op
     p(50.0000) =      1.931 ms/op
     p(90.0000) =      2.617 ms/op
     p(95.0000) =      2.871 ms/op
     p(99.0000) =      3.808 ms/op
     p(99.9000) =     21.945 ms/op
     p(99.9900) =     22.649 ms/op
     p(99.9990) =     22.774 ms/op
     p(99.9999) =     22.774 ms/op
    p(100.0000) =     22.774 ms/op


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
# Warmup Iteration   1: 4.381 ±(99.9%) 0.131 ms/op
Iteration   1: 3.281 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.110 ms/op
                 listUser·p0.50:   3.109 ms/op
                 listUser·p0.90:   4.010 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   7.496 ms/op
                 listUser·p0.999:  11.198 ms/op
                 listUser·p0.9999: 11.796 ms/op
                 listUser·p1.00:   11.796 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9762
  mean =      3.281 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 749 
    [ 2.500,  3.750) = 7039 
    [ 3.750,  5.000) = 1761 
    [ 5.000,  6.250) = 83 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 62 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.110 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      4.010 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      7.496 ms/op
     p(99.9000) =     11.198 ms/op
     p(99.9900) =     11.796 ms/op
     p(99.9990) =     11.796 ms/op
     p(99.9999) =     11.796 ms/op
    p(100.0000) =     11.796 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.288          ops/ms
ClientSimple.existUser                       thrpt         14.612          ops/ms
ClientSimple.getUser                         thrpt         14.392          ops/ms
ClientSimple.listUser                        thrpt          8.216          ops/ms
ClientSimple.createUser                       avgt          2.154           ms/op
ClientSimple.existUser                        avgt          1.872           ms/op
ClientSimple.getUser                          avgt          1.862           ms/op
ClientSimple.listUser                         avgt          3.791           ms/op
ClientSimple.createUser                     sample  15308   2.126 ± 0.042   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.483           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.882           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.474           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.662           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.716           ms/op
ClientSimple.createUser:createUser·p0.999   sample         28.410           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         29.119           ms/op
ClientSimple.createUser:createUser·p1.00    sample         29.327           ms/op
ClientSimple.existUser                      sample  18204   1.758 ± 0.007   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.531           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.702           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.126           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.277           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.564           ms/op
ClientSimple.existUser:existUser·p0.999     sample          3.096           ms/op
ClientSimple.existUser:existUser·p0.9999    sample          4.502           ms/op
ClientSimple.existUser:existUser·p1.00      sample          4.522           ms/op
ClientSimple.getUser                        sample  15433   2.075 ± 0.035   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.646           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.931           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.617           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.871           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.808           ms/op
ClientSimple.getUser:getUser·p0.999         sample         21.945           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         22.649           ms/op
ClientSimple.getUser:getUser·p1.00          sample         22.774           ms/op
ClientSimple.listUser                       sample   9762   3.281 ± 0.028   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.110           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.109           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.010           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.260           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.496           ms/op
ClientSimple.listUser:listUser·p0.999       sample         11.198           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         11.796           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.796           ms/op

Benchmark result is saved to 1714284282008.json
