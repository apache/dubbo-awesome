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
# Warmup Iteration   1: 2.187 ops/ms
Iteration   1: 7.175 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.175 ops/ms


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
# Warmup Iteration   1: 7.103 ops/ms
Iteration   1: 15.706 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  15.706 ops/ms


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
# Warmup Iteration   1: 5.495 ops/ms
Iteration   1: 13.379 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.379 ops/ms


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
# Warmup Iteration   1: 4.294 ops/ms
Iteration   1: 8.634 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.634 ops/ms


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
# Warmup Iteration   1: 3.847 ±(99.9%) 0.074 ms/op
Iteration   1: 2.124 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.124 ms/op


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
# Warmup Iteration   1: 3.091 ±(99.9%) 0.049 ms/op
Iteration   1: 1.936 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.936 ms/op


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
# Warmup Iteration   1: 3.306 ±(99.9%) 0.053 ms/op
Iteration   1: 2.035 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.035 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.520 ±(99.9%) 0.099 ms/op
Iteration   1: 3.320 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.320 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 4.310 ±(99.9%) 0.122 ms/op
Iteration   1: 2.306 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.589 ms/op
                 createUser·p0.50:   2.077 ms/op
                 createUser·p0.90:   2.966 ms/op
                 createUser·p0.95:   3.346 ms/op
                 createUser·p0.99:   7.032 ms/op
                 createUser·p0.999:  14.308 ms/op
                 createUser·p0.9999: 14.929 ms/op
                 createUser·p1.00:   15.024 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13865
  mean =      2.306 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 87 
    [ 1.250,  2.500) = 9477 
    [ 2.500,  3.750) = 3931 
    [ 3.750,  5.000) = 154 
    [ 5.000,  6.250) = 60 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.589 ms/op
     p(50.0000) =      2.077 ms/op
     p(90.0000) =      2.966 ms/op
     p(95.0000) =      3.346 ms/op
     p(99.0000) =      7.032 ms/op
     p(99.9000) =     14.308 ms/op
     p(99.9900) =     14.929 ms/op
     p(99.9990) =     15.024 ms/op
     p(99.9999) =     15.024 ms/op
    p(100.0000) =     15.024 ms/op


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
# Warmup Iteration   1: 3.141 ±(99.9%) 0.099 ms/op
Iteration   1: 1.883 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.695 ms/op
                 existUser·p0.50:   1.774 ms/op
                 existUser·p0.90:   2.400 ms/op
                 existUser·p0.95:   2.605 ms/op
                 existUser·p0.99:   3.166 ms/op
                 existUser·p0.999:  14.550 ms/op
                 existUser·p0.9999: 15.871 ms/op
                 existUser·p1.00:   15.974 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16979
  mean =      1.883 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 193 
    [ 1.250,  2.500) = 15508 
    [ 2.500,  3.750) = 1168 
    [ 3.750,  5.000) = 30 
    [ 5.000,  6.250) = 47 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.695 ms/op
     p(50.0000) =      1.774 ms/op
     p(90.0000) =      2.400 ms/op
     p(95.0000) =      2.605 ms/op
     p(99.0000) =      3.166 ms/op
     p(99.9000) =     14.550 ms/op
     p(99.9900) =     15.871 ms/op
     p(99.9990) =     15.974 ms/op
     p(99.9999) =     15.974 ms/op
    p(100.0000) =     15.974 ms/op


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
# Warmup Iteration   1: 3.567 ±(99.9%) 0.088 ms/op
Iteration   1: 1.910 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.303 ms/op
                 getUser·p0.50:   1.819 ms/op
                 getUser·p0.90:   2.216 ms/op
                 getUser·p0.95:   2.531 ms/op
                 getUser·p0.99:   3.166 ms/op
                 getUser·p0.999:  13.353 ms/op
                 getUser·p0.9999: 13.516 ms/op
                 getUser·p1.00:   13.550 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16769
  mean =      1.910 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 31 
    [ 1.250,  2.500) = 15835 
    [ 2.500,  3.750) = 824 
    [ 3.750,  5.000) = 15 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.303 ms/op
     p(50.0000) =      1.819 ms/op
     p(90.0000) =      2.216 ms/op
     p(95.0000) =      2.531 ms/op
     p(99.0000) =      3.166 ms/op
     p(99.9000) =     13.353 ms/op
     p(99.9900) =     13.516 ms/op
     p(99.9990) =     13.550 ms/op
     p(99.9999) =     13.550 ms/op
    p(100.0000) =     13.550 ms/op


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
# Warmup Iteration   1: 4.936 ±(99.9%) 0.145 ms/op
Iteration   1: 3.263 ±(99.9%) 0.037 ms/op
                 listUser·p0.00:   0.722 ms/op
                 listUser·p0.50:   3.121 ms/op
                 listUser·p0.90:   3.998 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  14.549 ms/op
                 listUser·p0.9999: 16.613 ms/op
                 listUser·p1.00:   16.613 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9795
  mean =      3.263 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 1197 
    [ 2.500,  3.750) = 6779 
    [ 3.750,  5.000) = 1518 
    [ 5.000,  6.250) = 144 
    [ 6.250,  7.500) = 48 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.722 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      6.840 ms/op
     p(99.9000) =     14.549 ms/op
     p(99.9900) =     16.613 ms/op
     p(99.9990) =     16.613 ms/op
     p(99.9999) =     16.613 ms/op
    p(100.0000) =     16.613 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.175          ops/ms
ClientSimple.existUser                       thrpt         15.706          ops/ms
ClientSimple.getUser                         thrpt         13.379          ops/ms
ClientSimple.listUser                        thrpt          8.634          ops/ms
ClientSimple.createUser                       avgt          2.124           ms/op
ClientSimple.existUser                        avgt          1.936           ms/op
ClientSimple.getUser                          avgt          2.035           ms/op
ClientSimple.listUser                         avgt          3.320           ms/op
ClientSimple.createUser                     sample  13865   2.306 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.589           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.077           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.966           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.346           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.032           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.308           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.929           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.024           ms/op
ClientSimple.existUser                      sample  16979   1.883 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.695           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.774           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.400           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.605           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.166           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.550           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.871           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.974           ms/op
ClientSimple.getUser                        sample  16769   1.910 ± 0.015   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.303           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.819           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.216           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.531           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.166           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.353           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.516           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.550           ms/op
ClientSimple.listUser                       sample   9795   3.263 ± 0.037   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.722           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.121           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.998           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.407           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.840           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.549           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.613           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.613           ms/op

Benchmark result is saved to 1716185147591.json
