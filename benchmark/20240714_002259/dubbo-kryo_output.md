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
# Warmup Iteration   1: 1.812 ops/ms
Iteration   1: 6.623 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.623 ops/ms


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
# Warmup Iteration   1: 6.875 ops/ms
Iteration   1: 14.695 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.695 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 6.781 ops/ms
Iteration   1: 13.692 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.692 ops/ms


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
# Warmup Iteration   1: 4.675 ops/ms
Iteration   1: 8.148 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.148 ops/ms


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
# Warmup Iteration   1: 4.058 ±(99.9%) 0.092 ms/op
Iteration   1: 2.153 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.153 ms/op


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
# Warmup Iteration   1: 2.895 ±(99.9%) 0.048 ms/op
Iteration   1: 1.777 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.777 ms/op


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
# Warmup Iteration   1: 3.415 ±(99.9%) 0.080 ms/op
Iteration   1: 1.991 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.991 ms/op


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
# Warmup Iteration   1: 4.578 ±(99.9%) 0.087 ms/op
Iteration   1: 3.938 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.938 ms/op


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
# Warmup Iteration   1: 3.398 ±(99.9%) 0.079 ms/op
Iteration   1: 2.089 ±(99.9%) 0.044 ms/op
                 createUser·p0.00:   0.549 ms/op
                 createUser·p0.50:   1.951 ms/op
                 createUser·p0.90:   2.486 ms/op
                 createUser·p0.95:   2.691 ms/op
                 createUser·p0.99:   3.992 ms/op
                 createUser·p0.999:  32.309 ms/op
                 createUser·p0.9999: 38.103 ms/op
                 createUser·p1.00:   38.207 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15320
  mean =      2.089 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13853 
    [ 2.500,  5.000) = 1335 
    [ 5.000,  7.500) = 3 
    [ 7.500, 10.000) = 49 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.549 ms/op
     p(50.0000) =      1.951 ms/op
     p(90.0000) =      2.486 ms/op
     p(95.0000) =      2.691 ms/op
     p(99.0000) =      3.992 ms/op
     p(99.9000) =     32.309 ms/op
     p(99.9900) =     38.103 ms/op
     p(99.9990) =     38.207 ms/op
     p(99.9999) =     38.207 ms/op
    p(100.0000) =     38.207 ms/op


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
# Warmup Iteration   1: 3.370 ±(99.9%) 0.085 ms/op
Iteration   1: 1.980 ±(99.9%) 0.037 ms/op
                 existUser·p0.00:   0.649 ms/op
                 existUser·p0.50:   1.819 ms/op
                 existUser·p0.90:   2.408 ms/op
                 existUser·p0.95:   2.561 ms/op
                 existUser·p0.99:   3.538 ms/op
                 existUser·p0.999:  30.633 ms/op
                 existUser·p0.9999: 31.634 ms/op
                 existUser·p1.00:   31.654 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16155
  mean =      1.980 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15068 
    [ 2.500,  5.000) = 997 
    [ 5.000,  7.500) = 18 
    [ 7.500, 10.000) = 8 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.649 ms/op
     p(50.0000) =      1.819 ms/op
     p(90.0000) =      2.408 ms/op
     p(95.0000) =      2.561 ms/op
     p(99.0000) =      3.538 ms/op
     p(99.9000) =     30.633 ms/op
     p(99.9900) =     31.634 ms/op
     p(99.9990) =     31.654 ms/op
     p(99.9999) =     31.654 ms/op
    p(100.0000) =     31.654 ms/op


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
# Warmup Iteration   1: 3.622 ±(99.9%) 0.140 ms/op
Iteration   1: 1.999 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.423 ms/op
                 getUser·p0.50:   1.868 ms/op
                 getUser·p0.90:   2.478 ms/op
                 getUser·p0.95:   2.707 ms/op
                 getUser·p0.99:   3.719 ms/op
                 getUser·p0.999:  11.729 ms/op
                 getUser·p0.9999: 11.836 ms/op
                 getUser·p1.00:   11.846 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16031
  mean =      1.999 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 129 
    [ 1.250,  2.500) = 14428 
    [ 2.500,  3.750) = 1326 
    [ 3.750,  5.000) = 73 
    [ 5.000,  6.250) = 42 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.423 ms/op
     p(50.0000) =      1.868 ms/op
     p(90.0000) =      2.478 ms/op
     p(95.0000) =      2.707 ms/op
     p(99.0000) =      3.719 ms/op
     p(99.9000) =     11.729 ms/op
     p(99.9900) =     11.836 ms/op
     p(99.9990) =     11.846 ms/op
     p(99.9999) =     11.846 ms/op
    p(100.0000) =     11.846 ms/op


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
# Warmup Iteration   1: 4.350 ±(99.9%) 0.132 ms/op
Iteration   1: 4.151 ±(99.9%) 0.039 ms/op
                 listUser·p0.00:   1.157 ms/op
                 listUser·p0.50:   4.043 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.408 ms/op
                 listUser·p0.99:   8.061 ms/op
                 listUser·p0.999:  13.866 ms/op
                 listUser·p0.9999: 14.582 ms/op
                 listUser·p1.00:   14.582 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 7696
  mean =      4.151 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 141 
    [ 2.500,  3.750) = 2022 
    [ 3.750,  5.000) = 4838 
    [ 5.000,  6.250) = 525 
    [ 6.250,  7.500) = 74 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 40 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.157 ms/op
     p(50.0000) =      4.043 ms/op
     p(90.0000) =      4.923 ms/op
     p(95.0000) =      5.408 ms/op
     p(99.0000) =      8.061 ms/op
     p(99.9000) =     13.866 ms/op
     p(99.9900) =     14.582 ms/op
     p(99.9990) =     14.582 ms/op
     p(99.9999) =     14.582 ms/op
    p(100.0000) =     14.582 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.623          ops/ms
ClientSimple.existUser                       thrpt         14.695          ops/ms
ClientSimple.getUser                         thrpt         13.692          ops/ms
ClientSimple.listUser                        thrpt          8.148          ops/ms
ClientSimple.createUser                       avgt          2.153           ms/op
ClientSimple.existUser                        avgt          1.777           ms/op
ClientSimple.getUser                          avgt          1.991           ms/op
ClientSimple.listUser                         avgt          3.938           ms/op
ClientSimple.createUser                     sample  15320   2.089 ± 0.044   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.549           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.951           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.486           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.691           ms/op
ClientSimple.createUser:createUser·p0.99    sample          3.992           ms/op
ClientSimple.createUser:createUser·p0.999   sample         32.309           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         38.103           ms/op
ClientSimple.createUser:createUser·p1.00    sample         38.207           ms/op
ClientSimple.existUser                      sample  16155   1.980 ± 0.037   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.649           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.819           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.408           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.561           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.538           ms/op
ClientSimple.existUser:existUser·p0.999     sample         30.633           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         31.634           ms/op
ClientSimple.existUser:existUser·p1.00      sample         31.654           ms/op
ClientSimple.getUser                        sample  16031   1.999 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.423           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.868           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.478           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.707           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.719           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.729           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.836           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.846           ms/op
ClientSimple.listUser                       sample   7696   4.151 ± 0.039   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.157           ms/op
ClientSimple.listUser:listUser·p0.50        sample          4.043           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.923           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.408           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.061           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.866           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.582           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.582           ms/op

Benchmark result is saved to 1720916315028.json
