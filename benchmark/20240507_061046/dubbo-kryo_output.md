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
# Warmup Iteration   1: 1.578 ops/ms
Iteration   1: 6.672 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.672 ops/ms


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
# Warmup Iteration   1: 6.659 ops/ms
Iteration   1: 14.069 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.069 ops/ms


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
# Warmup Iteration   1: 5.181 ops/ms
Iteration   1: 13.628 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.628 ops/ms


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
# Warmup Iteration   1: 5.065 ops/ms
Iteration   1: 9.806 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.806 ops/ms


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
# Warmup Iteration   1: 3.922 ±(99.9%) 0.075 ms/op
Iteration   1: 2.179 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.179 ms/op


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
# Warmup Iteration   1: 3.001 ±(99.9%) 0.043 ms/op
Iteration   1: 1.641 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.641 ms/op


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
# Warmup Iteration   1: 3.597 ±(99.9%) 0.072 ms/op
Iteration   1: 1.910 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.910 ms/op


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
# Warmup Iteration   1: 4.791 ±(99.9%) 0.092 ms/op
Iteration   1: 3.166 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.166 ms/op


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
# Warmup Iteration   1: 3.374 ±(99.9%) 0.085 ms/op
Iteration   1: 2.165 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   0.821 ms/op
                 createUser·p0.50:   2.009 ms/op
                 createUser·p0.90:   2.556 ms/op
                 createUser·p0.95:   2.818 ms/op
                 createUser·p0.99:   7.349 ms/op
                 createUser·p0.999:  14.713 ms/op
                 createUser·p0.9999: 14.821 ms/op
                 createUser·p1.00:   14.860 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14762
  mean =      2.165 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 12863 
    [ 2.500,  3.750) = 1418 
    [ 3.750,  5.000) = 173 
    [ 5.000,  6.250) = 47 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 66 
    [ 8.750, 10.000) = 9 
    [10.000, 11.250) = 35 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.821 ms/op
     p(50.0000) =      2.009 ms/op
     p(90.0000) =      2.556 ms/op
     p(95.0000) =      2.818 ms/op
     p(99.0000) =      7.349 ms/op
     p(99.9000) =     14.713 ms/op
     p(99.9900) =     14.821 ms/op
     p(99.9990) =     14.860 ms/op
     p(99.9999) =     14.860 ms/op
    p(100.0000) =     14.860 ms/op


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
# Warmup Iteration   1: 2.937 ±(99.9%) 0.075 ms/op
Iteration   1: 1.936 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.607 ms/op
                 existUser·p0.50:   1.851 ms/op
                 existUser·p0.90:   2.503 ms/op
                 existUser·p0.95:   2.777 ms/op
                 existUser·p0.99:   3.699 ms/op
                 existUser·p0.999:  15.925 ms/op
                 existUser·p0.9999: 16.089 ms/op
                 existUser·p1.00:   16.089 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16505
  mean =      1.936 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1078 
    [ 1.250,  2.500) = 13767 
    [ 2.500,  3.750) = 1497 
    [ 3.750,  5.000) = 82 
    [ 5.000,  6.250) = 16 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.607 ms/op
     p(50.0000) =      1.851 ms/op
     p(90.0000) =      2.503 ms/op
     p(95.0000) =      2.777 ms/op
     p(99.0000) =      3.699 ms/op
     p(99.9000) =     15.925 ms/op
     p(99.9900) =     16.089 ms/op
     p(99.9990) =     16.089 ms/op
     p(99.9999) =     16.089 ms/op
    p(100.0000) =     16.089 ms/op


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
# Warmup Iteration   1: 3.209 ±(99.9%) 0.084 ms/op
Iteration   1: 1.939 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.349 ms/op
                 getUser·p0.50:   1.886 ms/op
                 getUser·p0.90:   2.408 ms/op
                 getUser·p0.95:   2.572 ms/op
                 getUser·p0.99:   3.305 ms/op
                 getUser·p0.999:  14.557 ms/op
                 getUser·p0.9999: 14.691 ms/op
                 getUser·p1.00:   14.713 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16514
  mean =      1.939 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 617 
    [ 1.250,  2.500) = 14693 
    [ 2.500,  3.750) = 1099 
    [ 3.750,  5.000) = 9 
    [ 5.000,  6.250) = 64 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.349 ms/op
     p(50.0000) =      1.886 ms/op
     p(90.0000) =      2.408 ms/op
     p(95.0000) =      2.572 ms/op
     p(99.0000) =      3.305 ms/op
     p(99.9000) =     14.557 ms/op
     p(99.9900) =     14.691 ms/op
     p(99.9990) =     14.713 ms/op
     p(99.9999) =     14.713 ms/op
    p(100.0000) =     14.713 ms/op


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
# Warmup Iteration   1: 4.532 ±(99.9%) 0.129 ms/op
Iteration   1: 3.262 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   0.969 ms/op
                 listUser·p0.50:   3.203 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.316 ms/op
                 listUser·p0.99:   6.756 ms/op
                 listUser·p0.999:  8.654 ms/op
                 listUser·p0.9999: 10.076 ms/op
                 listUser·p1.00:   10.076 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9823
  mean =      3.262 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 2 
    [ 1.000,  2.000) = 77 
    [ 2.000,  3.000) = 3910 
    [ 3.000,  4.000) = 4917 
    [ 4.000,  5.000) = 675 
    [ 5.000,  6.000) = 111 
    [ 6.000,  7.000) = 55 
    [ 7.000,  8.000) = 56 
    [ 8.000,  9.000) = 15 
    [ 9.000, 10.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.969 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      3.969 ms/op
     p(95.0000) =      4.316 ms/op
     p(99.0000) =      6.756 ms/op
     p(99.9000) =      8.654 ms/op
     p(99.9900) =     10.076 ms/op
     p(99.9990) =     10.076 ms/op
     p(99.9999) =     10.076 ms/op
    p(100.0000) =     10.076 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.672          ops/ms
ClientSimple.existUser                       thrpt         14.069          ops/ms
ClientSimple.getUser                         thrpt         13.628          ops/ms
ClientSimple.listUser                        thrpt          9.806          ops/ms
ClientSimple.createUser                       avgt          2.179           ms/op
ClientSimple.existUser                        avgt          1.641           ms/op
ClientSimple.getUser                          avgt          1.910           ms/op
ClientSimple.listUser                         avgt          3.166           ms/op
ClientSimple.createUser                     sample  14762   2.165 ± 0.028   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.821           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.009           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.556           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.818           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.349           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.713           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.821           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.860           ms/op
ClientSimple.existUser                      sample  16505   1.936 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.607           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.851           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.503           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.777           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.699           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.925           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.089           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.089           ms/op
ClientSimple.getUser                        sample  16514   1.939 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.349           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.886           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.408           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.572           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.305           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.557           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.691           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.713           ms/op
ClientSimple.listUser                       sample   9823   3.262 ± 0.026   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.969           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.203           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.969           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.316           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.756           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.654           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.076           ms/op
ClientSimple.listUser:listUser·p1.00        sample         10.076           ms/op

Benchmark result is saved to 1715061924372.json
