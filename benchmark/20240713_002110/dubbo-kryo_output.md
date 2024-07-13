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
# Warmup Iteration   1: 1.818 ops/ms
Iteration   1: 6.880 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.880 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.289 ops/ms
Iteration   1: 12.289 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.289 ops/ms


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
# Warmup Iteration   1: 6.027 ops/ms
Iteration   1: 13.501 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.501 ops/ms


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
# Warmup Iteration   1: 5.287 ops/ms
Iteration   1: 8.885 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.885 ops/ms


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
# Warmup Iteration   1: 3.845 ±(99.9%) 0.073 ms/op
Iteration   1: 2.087 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.087 ms/op


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
# Warmup Iteration   1: 3.140 ±(99.9%) 0.054 ms/op
Iteration   1: 1.598 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.598 ms/op


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
# Warmup Iteration   1: 3.573 ±(99.9%) 0.055 ms/op
Iteration   1: 2.064 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.064 ms/op


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
# Warmup Iteration   1: 4.426 ±(99.9%) 0.082 ms/op
Iteration   1: 3.346 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.346 ms/op


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
# Warmup Iteration   1: 3.571 ±(99.9%) 0.082 ms/op
Iteration   1: 2.195 ±(99.9%) 0.043 ms/op
                 createUser·p0.00:   0.372 ms/op
                 createUser·p0.50:   2.005 ms/op
                 createUser·p0.90:   2.642 ms/op
                 createUser·p0.95:   2.912 ms/op
                 createUser·p0.99:   10.502 ms/op
                 createUser·p0.999:  23.626 ms/op
                 createUser·p0.9999: 29.035 ms/op
                 createUser·p1.00:   29.065 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14569
  mean =      2.195 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12348 
    [ 2.500,  5.000) = 1959 
    [ 5.000,  7.500) = 69 
    [ 7.500, 10.000) = 38 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.372 ms/op
     p(50.0000) =      2.005 ms/op
     p(90.0000) =      2.642 ms/op
     p(95.0000) =      2.912 ms/op
     p(99.0000) =     10.502 ms/op
     p(99.9000) =     23.626 ms/op
     p(99.9900) =     29.035 ms/op
     p(99.9990) =     29.065 ms/op
     p(99.9999) =     29.065 ms/op
    p(100.0000) =     29.065 ms/op


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
# Warmup Iteration   1: 2.956 ±(99.9%) 0.070 ms/op
Iteration   1: 1.968 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.225 ms/op
                 existUser·p0.50:   1.829 ms/op
                 existUser·p0.90:   2.396 ms/op
                 existUser·p0.95:   2.638 ms/op
                 existUser·p0.99:   5.198 ms/op
                 existUser·p0.999:  18.481 ms/op
                 existUser·p0.9999: 19.522 ms/op
                 existUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16236
  mean =      1.968 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 375 
    [ 1.250,  2.500) = 14821 
    [ 2.500,  3.750) = 837 
    [ 3.750,  5.000) = 36 
    [ 5.000,  6.250) = 31 
    [ 6.250,  7.500) = 60 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.225 ms/op
     p(50.0000) =      1.829 ms/op
     p(90.0000) =      2.396 ms/op
     p(95.0000) =      2.638 ms/op
     p(99.0000) =      5.198 ms/op
     p(99.9000) =     18.481 ms/op
     p(99.9900) =     19.522 ms/op
     p(99.9990) =     19.562 ms/op
     p(99.9999) =     19.562 ms/op
    p(100.0000) =     19.562 ms/op


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
# Warmup Iteration   1: 3.146 ±(99.9%) 0.079 ms/op
Iteration   1: 2.148 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.769 ms/op
                 getUser·p0.50:   2.071 ms/op
                 getUser·p0.90:   2.757 ms/op
                 getUser·p0.95:   2.937 ms/op
                 getUser·p0.99:   3.572 ms/op
                 getUser·p0.999:  10.469 ms/op
                 getUser·p0.9999: 10.894 ms/op
                 getUser·p1.00:   11.239 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14903
  mean =      2.148 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 138 
    [ 1.250,  2.500) = 11810 
    [ 2.500,  3.750) = 2826 
    [ 3.750,  5.000) = 88 
    [ 5.000,  6.250) = 9 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.769 ms/op
     p(50.0000) =      2.071 ms/op
     p(90.0000) =      2.757 ms/op
     p(95.0000) =      2.937 ms/op
     p(99.0000) =      3.572 ms/op
     p(99.9000) =     10.469 ms/op
     p(99.9900) =     10.894 ms/op
     p(99.9990) =     11.239 ms/op
     p(99.9999) =     11.239 ms/op
    p(100.0000) =     11.239 ms/op


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
# Warmup Iteration   1: 4.661 ±(99.9%) 0.161 ms/op
Iteration   1: 3.392 ±(99.9%) 0.057 ms/op
                 listUser·p0.00:   1.033 ms/op
                 listUser·p0.50:   3.383 ms/op
                 listUser·p0.90:   4.255 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  29.018 ms/op
                 listUser·p0.9999: 29.327 ms/op
                 listUser·p1.00:   29.327 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9425
  mean =      3.392 ±(99.9%) 0.057 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2337 
    [ 2.500,  5.000) = 6813 
    [ 5.000,  7.500) = 208 
    [ 7.500, 10.000) = 35 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.033 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      4.255 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      6.783 ms/op
     p(99.9000) =     29.018 ms/op
     p(99.9900) =     29.327 ms/op
     p(99.9990) =     29.327 ms/op
     p(99.9999) =     29.327 ms/op
    p(100.0000) =     29.327 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.880          ops/ms
ClientSimple.existUser                       thrpt         12.289          ops/ms
ClientSimple.getUser                         thrpt         13.501          ops/ms
ClientSimple.listUser                        thrpt          8.885          ops/ms
ClientSimple.createUser                       avgt          2.087           ms/op
ClientSimple.existUser                        avgt          1.598           ms/op
ClientSimple.getUser                          avgt          2.064           ms/op
ClientSimple.listUser                         avgt          3.346           ms/op
ClientSimple.createUser                     sample  14569   2.195 ± 0.043   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.372           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.005           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.642           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.912           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.502           ms/op
ClientSimple.createUser:createUser·p0.999   sample         23.626           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         29.035           ms/op
ClientSimple.createUser:createUser·p1.00    sample         29.065           ms/op
ClientSimple.existUser                      sample  16236   1.968 ± 0.026   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.225           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.829           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.396           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.638           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.198           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.481           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.522           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.562           ms/op
ClientSimple.getUser                        sample  14903   2.148 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.769           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.071           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.757           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.937           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.572           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.469           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         10.894           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.239           ms/op
ClientSimple.listUser                       sample   9425   3.392 ± 0.057   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.033           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.383           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.255           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.579           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.783           ms/op
ClientSimple.listUser:listUser·p0.999       sample         29.018           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         29.327           ms/op
ClientSimple.listUser:listUser·p1.00        sample         29.327           ms/op

Benchmark result is saved to 1720829813882.json
