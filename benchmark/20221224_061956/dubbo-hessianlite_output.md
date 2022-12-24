# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.108 ops/ms
Iteration   1: 2.665 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.665 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 3.238 ops/ms
Iteration   1: 8.864 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  8.864 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 1.618 ops/ms
Iteration   1: 5.784 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.784 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 0.885 ops/ms
Iteration   1: 1.261 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.261 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 21.697 ±(99.9%) 0.336 ms/op
Iteration   1: 6.263 ±(99.9%) 0.032 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.263 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 5.566 ±(99.9%) 0.059 ms/op
Iteration   1: 3.445 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.445 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.175 ±(99.9%) 0.109 ms/op
Iteration   1: 4.145 ±(99.9%) 0.035 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.145 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 28.601 ±(99.9%) 0.266 ms/op
Iteration   1: 16.866 ±(99.9%) 0.063 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  16.866 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.299 ±(99.9%) 0.379 ms/op
Iteration   1: 5.587 ±(99.9%) 0.119 ms/op
                 createUser·p0.00:   2.286 ms/op
                 createUser·p0.50:   5.022 ms/op
                 createUser·p0.90:   6.169 ms/op
                 createUser·p0.95:   7.725 ms/op
                 createUser·p0.99:   17.849 ms/op
                 createUser·p0.999:  32.294 ms/op
                 createUser·p0.9999: 32.702 ms/op
                 createUser·p1.00:   32.702 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5729
  mean =      5.587 ±(99.9%) 0.119 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 2789 
    [ 5.000,  7.500) = 2645 
    [ 7.500, 10.000) = 68 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.286 ms/op
     p(50.0000) =      5.022 ms/op
     p(90.0000) =      6.169 ms/op
     p(95.0000) =      7.725 ms/op
     p(99.0000) =     17.849 ms/op
     p(99.9000) =     32.294 ms/op
     p(99.9900) =     32.702 ms/op
     p(99.9990) =     32.702 ms/op
     p(99.9999) =     32.702 ms/op
    p(100.0000) =     32.702 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 5.826 ±(99.9%) 0.201 ms/op
Iteration   1: 3.196 ±(99.9%) 0.087 ms/op
                 existUser·p0.00:   0.642 ms/op
                 existUser·p0.50:   2.839 ms/op
                 existUser·p0.90:   4.350 ms/op
                 existUser·p0.95:   5.194 ms/op
                 existUser·p0.99:   14.738 ms/op
                 existUser·p0.999:  30.933 ms/op
                 existUser·p0.9999: 33.881 ms/op
                 existUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 10144
  mean =      3.196 ±(99.9%) 0.087 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4509 
    [ 2.500,  5.000) = 5097 
    [ 5.000,  7.500) = 245 
    [ 7.500, 10.000) = 112 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.642 ms/op
     p(50.0000) =      2.839 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      5.194 ms/op
     p(99.0000) =     14.738 ms/op
     p(99.9000) =     30.933 ms/op
     p(99.9900) =     33.881 ms/op
     p(99.9990) =     33.882 ms/op
     p(99.9999) =     33.882 ms/op
    p(100.0000) =     33.882 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 10.822 ±(99.9%) 0.457 ms/op
Iteration   1: 4.632 ±(99.9%) 0.084 ms/op
                 getUser·p0.00:   1.853 ms/op
                 getUser·p0.50:   4.194 ms/op
                 getUser·p0.90:   6.444 ms/op
                 getUser·p0.95:   8.135 ms/op
                 getUser·p0.99:   17.007 ms/op
                 getUser·p0.999:  19.697 ms/op
                 getUser·p0.9999: 19.923 ms/op
                 getUser·p1.00:   19.923 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6903
  mean =      4.632 ±(99.9%) 0.084 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 88 
    [ 2.500,  3.750) = 1773 
    [ 3.750,  5.000) = 3615 
    [ 5.000,  6.250) = 683 
    [ 6.250,  7.500) = 346 
    [ 7.500,  8.750) = 130 
    [ 8.750, 10.000) = 94 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 44 

  Percentiles, ms/op:
      p(0.0000) =      1.853 ms/op
     p(50.0000) =      4.194 ms/op
     p(90.0000) =      6.444 ms/op
     p(95.0000) =      8.135 ms/op
     p(99.0000) =     17.007 ms/op
     p(99.9000) =     19.697 ms/op
     p(99.9900) =     19.923 ms/op
     p(99.9990) =     19.923 ms/op
     p(99.9999) =     19.923 ms/op
    p(100.0000) =     19.923 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 26.101 ±(99.9%) 0.922 ms/op
Iteration   1: 15.956 ±(99.9%) 0.305 ms/op
                 listUser·p0.00:   3.199 ms/op
                 listUser·p0.50:   15.270 ms/op
                 listUser·p0.90:   20.644 ms/op
                 listUser·p0.95:   22.661 ms/op
                 listUser·p0.99:   30.667 ms/op
                 listUser·p0.999:  32.863 ms/op
                 listUser·p0.9999: 33.260 ms/op
                 listUser·p1.00:   33.260 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2002
  mean =     15.956 ±(99.9%) 0.305 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 6 
    [ 5.000,  7.500) = 9 
    [ 7.500, 10.000) = 81 
    [10.000, 12.500) = 240 
    [12.500, 15.000) = 590 
    [15.000, 17.500) = 559 
    [17.500, 20.000) = 256 
    [20.000, 22.500) = 156 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 17 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.199 ms/op
     p(50.0000) =     15.270 ms/op
     p(90.0000) =     20.644 ms/op
     p(95.0000) =     22.661 ms/op
     p(99.0000) =     30.667 ms/op
     p(99.9000) =     32.863 ms/op
     p(99.9900) =     33.260 ms/op
     p(99.9990) =     33.260 ms/op
     p(99.9999) =     33.260 ms/op
    p(100.0000) =     33.260 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          2.665          ops/ms
Client.existUser                       thrpt          8.864          ops/ms
Client.getUser                         thrpt          5.784          ops/ms
Client.listUser                        thrpt          1.261          ops/ms
Client.createUser                       avgt          6.263           ms/op
Client.existUser                        avgt          3.445           ms/op
Client.getUser                          avgt          4.145           ms/op
Client.listUser                         avgt         16.866           ms/op
Client.createUser                     sample   5729   5.587 ± 0.119   ms/op
Client.createUser:createUser·p0.00    sample          2.286           ms/op
Client.createUser:createUser·p0.50    sample          5.022           ms/op
Client.createUser:createUser·p0.90    sample          6.169           ms/op
Client.createUser:createUser·p0.95    sample          7.725           ms/op
Client.createUser:createUser·p0.99    sample         17.849           ms/op
Client.createUser:createUser·p0.999   sample         32.294           ms/op
Client.createUser:createUser·p0.9999  sample         32.702           ms/op
Client.createUser:createUser·p1.00    sample         32.702           ms/op
Client.existUser                      sample  10144   3.196 ± 0.087   ms/op
Client.existUser:existUser·p0.00      sample          0.642           ms/op
Client.existUser:existUser·p0.50      sample          2.839           ms/op
Client.existUser:existUser·p0.90      sample          4.350           ms/op
Client.existUser:existUser·p0.95      sample          5.194           ms/op
Client.existUser:existUser·p0.99      sample         14.738           ms/op
Client.existUser:existUser·p0.999     sample         30.933           ms/op
Client.existUser:existUser·p0.9999    sample         33.881           ms/op
Client.existUser:existUser·p1.00      sample         33.882           ms/op
Client.getUser                        sample   6903   4.632 ± 0.084   ms/op
Client.getUser:getUser·p0.00          sample          1.853           ms/op
Client.getUser:getUser·p0.50          sample          4.194           ms/op
Client.getUser:getUser·p0.90          sample          6.444           ms/op
Client.getUser:getUser·p0.95          sample          8.135           ms/op
Client.getUser:getUser·p0.99          sample         17.007           ms/op
Client.getUser:getUser·p0.999         sample         19.697           ms/op
Client.getUser:getUser·p0.9999        sample         19.923           ms/op
Client.getUser:getUser·p1.00          sample         19.923           ms/op
Client.listUser                       sample   2002  15.956 ± 0.305   ms/op
Client.listUser:listUser·p0.00        sample          3.199           ms/op
Client.listUser:listUser·p0.50        sample         15.270           ms/op
Client.listUser:listUser·p0.90        sample         20.644           ms/op
Client.listUser:listUser·p0.95        sample         22.661           ms/op
Client.listUser:listUser·p0.99        sample         30.667           ms/op
Client.listUser:listUser·p0.999       sample         32.863           ms/op
Client.listUser:listUser·p0.9999      sample         33.260           ms/op
Client.listUser:listUser·p1.00        sample         33.260           ms/op
