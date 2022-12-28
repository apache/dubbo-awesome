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
# Warmup Iteration   1: 1.013 ops/ms
Iteration   1: 2.273 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.273 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 2.841 ops/ms
Iteration   1: 5.907 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  5.907 ops/ms


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
# Warmup Iteration   1: 2.253 ops/ms
Iteration   1: 4.509 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.509 ops/ms


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
# Warmup Iteration   1: 0.824 ops/ms
Iteration   1: 1.389 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.389 ops/ms


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
# Warmup Iteration   1: 19.102 ±(99.9%) 0.384 ms/op
Iteration   1: 8.490 ±(99.9%) 0.063 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  8.490 ms/op


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
# Warmup Iteration   1: 6.116 ±(99.9%) 0.072 ms/op
Iteration   1: 4.719 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.719 ms/op


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
# Warmup Iteration   1: 10.736 ±(99.9%) 0.121 ms/op
Iteration   1: 4.685 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.685 ms/op


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
# Warmup Iteration   1: 28.986 ±(99.9%) 0.454 ms/op
Iteration   1: 17.573 ±(99.9%) 0.203 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  17.573 ms/op


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
# Warmup Iteration   1: 13.528 ±(99.9%) 0.362 ms/op
Iteration   1: 7.388 ±(99.9%) 0.149 ms/op
                 createUser·p0.00:   2.990 ms/op
                 createUser·p0.50:   7.397 ms/op
                 createUser·p0.90:   8.471 ms/op
                 createUser·p0.95:   10.365 ms/op
                 createUser·p0.99:   21.311 ms/op
                 createUser·p0.999:  34.800 ms/op
                 createUser·p0.9999: 34.931 ms/op
                 createUser·p1.00:   34.931 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4363
  mean =      7.388 ±(99.9%) 0.149 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 85 
    [ 5.000,  7.500) = 2229 
    [ 7.500, 10.000) = 1796 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.990 ms/op
     p(50.0000) =      7.397 ms/op
     p(90.0000) =      8.471 ms/op
     p(95.0000) =     10.365 ms/op
     p(99.0000) =     21.311 ms/op
     p(99.9000) =     34.800 ms/op
     p(99.9900) =     34.931 ms/op
     p(99.9990) =     34.931 ms/op
     p(99.9999) =     34.931 ms/op
    p(100.0000) =     34.931 ms/op


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
# Warmup Iteration   1: 7.009 ±(99.9%) 0.203 ms/op
Iteration   1: 4.131 ±(99.9%) 0.084 ms/op
                 existUser·p0.00:   0.974 ms/op
                 existUser·p0.50:   3.842 ms/op
                 existUser·p0.90:   4.465 ms/op
                 existUser·p0.95:   4.733 ms/op
                 existUser·p0.99:   11.905 ms/op
                 existUser·p0.999:  34.800 ms/op
                 existUser·p0.9999: 34.865 ms/op
                 existUser·p1.00:   34.865 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 7745
  mean =      4.131 ±(99.9%) 0.084 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 138 
    [ 2.500,  5.000) = 7239 
    [ 5.000,  7.500) = 145 
    [ 7.500, 10.000) = 111 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 44 
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
      p(0.0000) =      0.974 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.733 ms/op
     p(99.0000) =     11.905 ms/op
     p(99.9000) =     34.800 ms/op
     p(99.9900) =     34.865 ms/op
     p(99.9990) =     34.865 ms/op
     p(99.9999) =     34.865 ms/op
    p(100.0000) =     34.865 ms/op


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
# Warmup Iteration   1: 10.249 ±(99.9%) 0.346 ms/op
Iteration   1: 4.942 ±(99.9%) 0.042 ms/op
                 getUser·p0.00:   1.196 ms/op
                 getUser·p0.50:   4.891 ms/op
                 getUser·p0.90:   5.558 ms/op
                 getUser·p0.95:   6.040 ms/op
                 getUser·p0.99:   9.282 ms/op
                 getUser·p0.999:  14.612 ms/op
                 getUser·p0.9999: 14.959 ms/op
                 getUser·p1.00:   14.959 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6574
  mean =      4.942 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 13 
    [ 2.500,  3.750) = 269 
    [ 3.750,  5.000) = 3535 
    [ 5.000,  6.250) = 2474 
    [ 6.250,  7.500) = 195 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.196 ms/op
     p(50.0000) =      4.891 ms/op
     p(90.0000) =      5.558 ms/op
     p(95.0000) =      6.040 ms/op
     p(99.0000) =      9.282 ms/op
     p(99.9000) =     14.612 ms/op
     p(99.9900) =     14.959 ms/op
     p(99.9990) =     14.959 ms/op
     p(99.9999) =     14.959 ms/op
    p(100.0000) =     14.959 ms/op


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
# Warmup Iteration   1: 24.846 ±(99.9%) 0.947 ms/op
Iteration   1: 17.554 ±(99.9%) 0.258 ms/op
                 listUser·p0.00:   9.748 ms/op
                 listUser·p0.50:   16.744 ms/op
                 listUser·p0.90:   20.611 ms/op
                 listUser·p0.95:   22.531 ms/op
                 listUser·p0.99:   34.472 ms/op
                 listUser·p0.999:  35.012 ms/op
                 listUser·p0.9999: 35.717 ms/op
                 listUser·p1.00:   35.717 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1827
  mean =     17.554 ±(99.9%) 0.258 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 18 
    [12.500, 15.000) = 177 
    [15.000, 17.500) = 1115 
    [17.500, 20.000) = 266 
    [20.000, 22.500) = 157 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      9.748 ms/op
     p(50.0000) =     16.744 ms/op
     p(90.0000) =     20.611 ms/op
     p(95.0000) =     22.531 ms/op
     p(99.0000) =     34.472 ms/op
     p(99.9000) =     35.012 ms/op
     p(99.9900) =     35.717 ms/op
     p(99.9990) =     35.717 ms/op
     p(99.9999) =     35.717 ms/op
    p(100.0000) =     35.717 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.273          ops/ms
Client.existUser                       thrpt         5.907          ops/ms
Client.getUser                         thrpt         4.509          ops/ms
Client.listUser                        thrpt         1.389          ops/ms
Client.createUser                       avgt         8.490           ms/op
Client.existUser                        avgt         4.719           ms/op
Client.getUser                          avgt         4.685           ms/op
Client.listUser                         avgt        17.573           ms/op
Client.createUser                     sample  4363   7.388 ± 0.149   ms/op
Client.createUser:createUser·p0.00    sample         2.990           ms/op
Client.createUser:createUser·p0.50    sample         7.397           ms/op
Client.createUser:createUser·p0.90    sample         8.471           ms/op
Client.createUser:createUser·p0.95    sample        10.365           ms/op
Client.createUser:createUser·p0.99    sample        21.311           ms/op
Client.createUser:createUser·p0.999   sample        34.800           ms/op
Client.createUser:createUser·p0.9999  sample        34.931           ms/op
Client.createUser:createUser·p1.00    sample        34.931           ms/op
Client.existUser                      sample  7745   4.131 ± 0.084   ms/op
Client.existUser:existUser·p0.00      sample         0.974           ms/op
Client.existUser:existUser·p0.50      sample         3.842           ms/op
Client.existUser:existUser·p0.90      sample         4.465           ms/op
Client.existUser:existUser·p0.95      sample         4.733           ms/op
Client.existUser:existUser·p0.99      sample        11.905           ms/op
Client.existUser:existUser·p0.999     sample        34.800           ms/op
Client.existUser:existUser·p0.9999    sample        34.865           ms/op
Client.existUser:existUser·p1.00      sample        34.865           ms/op
Client.getUser                        sample  6574   4.942 ± 0.042   ms/op
Client.getUser:getUser·p0.00          sample         1.196           ms/op
Client.getUser:getUser·p0.50          sample         4.891           ms/op
Client.getUser:getUser·p0.90          sample         5.558           ms/op
Client.getUser:getUser·p0.95          sample         6.040           ms/op
Client.getUser:getUser·p0.99          sample         9.282           ms/op
Client.getUser:getUser·p0.999         sample        14.612           ms/op
Client.getUser:getUser·p0.9999        sample        14.959           ms/op
Client.getUser:getUser·p1.00          sample        14.959           ms/op
Client.listUser                       sample  1827  17.554 ± 0.258   ms/op
Client.listUser:listUser·p0.00        sample         9.748           ms/op
Client.listUser:listUser·p0.50        sample        16.744           ms/op
Client.listUser:listUser·p0.90        sample        20.611           ms/op
Client.listUser:listUser·p0.95        sample        22.531           ms/op
Client.listUser:listUser·p0.99        sample        34.472           ms/op
Client.listUser:listUser·p0.999       sample        35.012           ms/op
Client.listUser:listUser·p0.9999      sample        35.717           ms/op
Client.listUser:listUser·p1.00        sample        35.717           ms/op
