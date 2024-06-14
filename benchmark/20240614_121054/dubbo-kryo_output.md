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
# Warmup Iteration   1: 0.638 ops/ms
Iteration   1: 5.737 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.737 ops/ms


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
# Warmup Iteration   1: 5.764 ops/ms
Iteration   1: 11.832 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.832 ops/ms


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
# Warmup Iteration   1: 6.216 ops/ms
Iteration   1: 14.714 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.714 ops/ms


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
# Warmup Iteration   1: 4.398 ops/ms
Iteration   1: 8.032 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.032 ops/ms


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
# Warmup Iteration   1: 3.788 ±(99.9%) 0.056 ms/op
Iteration   1: 2.126 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.126 ms/op


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
# Warmup Iteration   1: 3.070 ±(99.9%) 0.052 ms/op
Iteration   1: 2.120 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.120 ms/op


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
# Warmup Iteration   1: 3.497 ±(99.9%) 0.061 ms/op
Iteration   1: 2.192 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.192 ms/op


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
# Warmup Iteration   1: 3.989 ±(99.9%) 0.086 ms/op
Iteration   1: 3.519 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.519 ms/op


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
# Warmup Iteration   1: 3.756 ±(99.9%) 0.106 ms/op
Iteration   1: 2.067 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.643 ms/op
                 createUser·p0.50:   1.964 ms/op
                 createUser·p0.90:   2.400 ms/op
                 createUser·p0.95:   2.674 ms/op
                 createUser·p0.99:   4.156 ms/op
                 createUser·p0.999:  26.723 ms/op
                 createUser·p0.9999: 32.562 ms/op
                 createUser·p1.00:   32.670 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15461
  mean =      2.067 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14259 
    [ 2.500,  5.000) = 1088 
    [ 5.000,  7.500) = 82 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 22 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.643 ms/op
     p(50.0000) =      1.964 ms/op
     p(90.0000) =      2.400 ms/op
     p(95.0000) =      2.674 ms/op
     p(99.0000) =      4.156 ms/op
     p(99.9000) =     26.723 ms/op
     p(99.9900) =     32.562 ms/op
     p(99.9990) =     32.670 ms/op
     p(99.9999) =     32.670 ms/op
    p(100.0000) =     32.670 ms/op


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
# Warmup Iteration   1: 3.121 ±(99.9%) 0.068 ms/op
Iteration   1: 1.755 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.566 ms/op
                 existUser·p0.50:   1.634 ms/op
                 existUser·p0.90:   2.142 ms/op
                 existUser·p0.95:   2.347 ms/op
                 existUser·p0.99:   4.522 ms/op
                 existUser·p0.999:  13.841 ms/op
                 existUser·p0.9999: 13.992 ms/op
                 existUser·p1.00:   13.992 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18241
  mean =      1.755 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1012 
    [ 1.250,  2.500) = 16711 
    [ 2.500,  3.750) = 284 
    [ 3.750,  5.000) = 95 
    [ 5.000,  6.250) = 65 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.566 ms/op
     p(50.0000) =      1.634 ms/op
     p(90.0000) =      2.142 ms/op
     p(95.0000) =      2.347 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =     13.841 ms/op
     p(99.9900) =     13.992 ms/op
     p(99.9990) =     13.992 ms/op
     p(99.9999) =     13.992 ms/op
    p(100.0000) =     13.992 ms/op


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
# Warmup Iteration   1: 3.375 ±(99.9%) 0.089 ms/op
Iteration   1: 2.235 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   1.104 ms/op
                 getUser·p0.50:   2.163 ms/op
                 getUser·p0.90:   2.748 ms/op
                 getUser·p0.95:   2.953 ms/op
                 getUser·p0.99:   3.847 ms/op
                 getUser·p0.999:  16.908 ms/op
                 getUser·p0.9999: 17.806 ms/op
                 getUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14294
  mean =      2.235 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 22 
    [ 1.250,  2.500) = 11124 
    [ 2.500,  3.750) = 2997 
    [ 3.750,  5.000) = 84 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.104 ms/op
     p(50.0000) =      2.163 ms/op
     p(90.0000) =      2.748 ms/op
     p(95.0000) =      2.953 ms/op
     p(99.0000) =      3.847 ms/op
     p(99.9000) =     16.908 ms/op
     p(99.9900) =     17.806 ms/op
     p(99.9990) =     18.186 ms/op
     p(99.9999) =     18.186 ms/op
    p(100.0000) =     18.186 ms/op


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
# Warmup Iteration   1: 4.662 ±(99.9%) 0.150 ms/op
Iteration   1: 3.727 ±(99.9%) 0.046 ms/op
                 listUser·p0.00:   0.945 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.284 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   7.499 ms/op
                 listUser·p0.999:  17.446 ms/op
                 listUser·p0.9999: 17.957 ms/op
                 listUser·p1.00:   17.957 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8581
  mean =      3.727 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 16 
    [ 1.250,  2.500) = 369 
    [ 2.500,  3.750) = 4258 
    [ 3.750,  5.000) = 3740 
    [ 5.000,  6.250) = 68 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 39 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.945 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      7.499 ms/op
     p(99.9000) =     17.446 ms/op
     p(99.9900) =     17.957 ms/op
     p(99.9990) =     17.957 ms/op
     p(99.9999) =     17.957 ms/op
    p(100.0000) =     17.957 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.737          ops/ms
ClientSimple.existUser                       thrpt         11.832          ops/ms
ClientSimple.getUser                         thrpt         14.714          ops/ms
ClientSimple.listUser                        thrpt          8.032          ops/ms
ClientSimple.createUser                       avgt          2.126           ms/op
ClientSimple.existUser                        avgt          2.120           ms/op
ClientSimple.getUser                          avgt          2.192           ms/op
ClientSimple.listUser                         avgt          3.519           ms/op
ClientSimple.createUser                     sample  15461   2.067 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.643           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.964           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.400           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.674           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.156           ms/op
ClientSimple.createUser:createUser·p0.999   sample         26.723           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         32.562           ms/op
ClientSimple.createUser:createUser·p1.00    sample         32.670           ms/op
ClientSimple.existUser                      sample  18241   1.755 ± 0.020   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.566           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.634           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.142           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.347           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.522           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.841           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.992           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.992           ms/op
ClientSimple.getUser                        sample  14294   2.235 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          1.104           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.163           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.748           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.953           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.847           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.908           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.806           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.186           ms/op
ClientSimple.listUser                       sample   8581   3.727 ± 0.046   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.945           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.690           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.284           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.489           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.499           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.446           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.957           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.957           ms/op

Benchmark result is saved to 1718366812230.json
