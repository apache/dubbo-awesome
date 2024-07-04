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
# Warmup Iteration   1: 1.542 ops/ms
Iteration   1: 7.659 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.659 ops/ms


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
# Warmup Iteration   1: 5.872 ops/ms
Iteration   1: 12.617 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.617 ops/ms


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
# Warmup Iteration   1: 6.425 ops/ms
Iteration   1: 13.940 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.940 ops/ms


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
# Warmup Iteration   1: 5.166 ops/ms
Iteration   1: 8.544 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.544 ops/ms


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
# Warmup Iteration   1: 4.061 ±(99.9%) 0.081 ms/op
Iteration   1: 2.426 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.426 ms/op


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
# Warmup Iteration   1: 3.488 ±(99.9%) 0.065 ms/op
Iteration   1: 1.932 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.932 ms/op


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
# Warmup Iteration   1: 3.304 ±(99.9%) 0.056 ms/op
Iteration   1: 2.050 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.050 ms/op


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
# Warmup Iteration   1: 4.659 ±(99.9%) 0.094 ms/op
Iteration   1: 3.231 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.231 ms/op


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
# Warmup Iteration   1: 4.043 ±(99.9%) 0.121 ms/op
Iteration   1: 2.308 ±(99.9%) 0.046 ms/op
                 createUser·p0.00:   0.851 ms/op
                 createUser·p0.50:   2.118 ms/op
                 createUser·p0.90:   2.793 ms/op
                 createUser·p0.95:   3.019 ms/op
                 createUser·p0.99:   6.506 ms/op
                 createUser·p0.999:  34.069 ms/op
                 createUser·p0.9999: 34.824 ms/op
                 createUser·p1.00:   34.931 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14076
  mean =      2.308 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10985 
    [ 2.500,  5.000) = 2916 
    [ 5.000,  7.500) = 66 
    [ 7.500, 10.000) = 45 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.851 ms/op
     p(50.0000) =      2.118 ms/op
     p(90.0000) =      2.793 ms/op
     p(95.0000) =      3.019 ms/op
     p(99.0000) =      6.506 ms/op
     p(99.9000) =     34.069 ms/op
     p(99.9900) =     34.824 ms/op
     p(99.9990) =     34.931 ms/op
     p(99.9999) =     34.931 ms/op
    p(100.0000) =     34.931 ms/op


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
# Warmup Iteration   1: 2.947 ±(99.9%) 0.072 ms/op
Iteration   1: 1.924 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.557 ms/op
                 existUser·p0.50:   1.862 ms/op
                 existUser·p0.90:   2.298 ms/op
                 existUser·p0.95:   2.458 ms/op
                 existUser·p0.99:   3.207 ms/op
                 existUser·p0.999:  15.230 ms/op
                 existUser·p0.9999: 15.882 ms/op
                 existUser·p1.00:   15.892 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16614
  mean =      1.924 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 384 
    [ 1.250,  2.500) = 15533 
    [ 2.500,  3.750) = 571 
    [ 3.750,  5.000) = 62 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.557 ms/op
     p(50.0000) =      1.862 ms/op
     p(90.0000) =      2.298 ms/op
     p(95.0000) =      2.458 ms/op
     p(99.0000) =      3.207 ms/op
     p(99.9000) =     15.230 ms/op
     p(99.9900) =     15.882 ms/op
     p(99.9990) =     15.892 ms/op
     p(99.9999) =     15.892 ms/op
    p(100.0000) =     15.892 ms/op


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
# Warmup Iteration   1: 3.400 ±(99.9%) 0.094 ms/op
Iteration   1: 1.924 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.868 ms/op
                 getUser·p0.50:   1.761 ms/op
                 getUser·p0.90:   2.413 ms/op
                 getUser·p0.95:   2.683 ms/op
                 getUser·p0.99:   4.182 ms/op
                 getUser·p0.999:  12.583 ms/op
                 getUser·p0.9999: 13.140 ms/op
                 getUser·p1.00:   13.173 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16758
  mean =      1.924 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 125 
    [ 1.250,  2.500) = 15330 
    [ 2.500,  3.750) = 1088 
    [ 3.750,  5.000) = 114 
    [ 5.000,  6.250) = 30 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.868 ms/op
     p(50.0000) =      1.761 ms/op
     p(90.0000) =      2.413 ms/op
     p(95.0000) =      2.683 ms/op
     p(99.0000) =      4.182 ms/op
     p(99.9000) =     12.583 ms/op
     p(99.9900) =     13.140 ms/op
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
# Warmup Iteration   1: 4.290 ±(99.9%) 0.107 ms/op
Iteration   1: 3.204 ±(99.9%) 0.041 ms/op
                 listUser·p0.00:   1.278 ms/op
                 listUser·p0.50:   2.871 ms/op
                 listUser·p0.90:   4.088 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   7.440 ms/op
                 listUser·p0.999:  17.236 ms/op
                 listUser·p0.9999: 17.302 ms/op
                 listUser·p1.00:   17.302 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9975
  mean =      3.204 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 321 
    [ 2.500,  3.750) = 7849 
    [ 3.750,  5.000) = 1625 
    [ 5.000,  6.250) = 72 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.278 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      4.088 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      7.440 ms/op
     p(99.9000) =     17.236 ms/op
     p(99.9900) =     17.302 ms/op
     p(99.9990) =     17.302 ms/op
     p(99.9999) =     17.302 ms/op
    p(100.0000) =     17.302 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.659          ops/ms
ClientSimple.existUser                       thrpt         12.617          ops/ms
ClientSimple.getUser                         thrpt         13.940          ops/ms
ClientSimple.listUser                        thrpt          8.544          ops/ms
ClientSimple.createUser                       avgt          2.426           ms/op
ClientSimple.existUser                        avgt          1.932           ms/op
ClientSimple.getUser                          avgt          2.050           ms/op
ClientSimple.listUser                         avgt          3.231           ms/op
ClientSimple.createUser                     sample  14076   2.308 ± 0.046   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.851           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.118           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.793           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.019           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.506           ms/op
ClientSimple.createUser:createUser·p0.999   sample         34.069           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         34.824           ms/op
ClientSimple.createUser:createUser·p1.00    sample         34.931           ms/op
ClientSimple.existUser                      sample  16614   1.924 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.557           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.862           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.298           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.458           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.207           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.230           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.882           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.892           ms/op
ClientSimple.getUser                        sample  16758   1.924 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.868           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.761           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.413           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.683           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.182           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.583           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.140           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.173           ms/op
ClientSimple.listUser                       sample   9975   3.204 ± 0.041   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.278           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.871           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.088           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.293           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.440           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.236           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.302           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.302           ms/op

Benchmark result is saved to 1720052164201.json
