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
# Warmup Iteration   1: 1.740 ops/ms
Iteration   1: 6.017 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.017 ops/ms


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
# Warmup Iteration   1: 5.378 ops/ms
Iteration   1: 12.249 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.249 ops/ms


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
# Warmup Iteration   1: 5.571 ops/ms
Iteration   1: 11.607 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.607 ops/ms


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
# Warmup Iteration   1: 4.440 ops/ms
Iteration   1: 8.542 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.542 ops/ms


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
# Warmup Iteration   1: 4.259 ±(99.9%) 0.084 ms/op
Iteration   1: 2.187 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.187 ms/op


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
# Warmup Iteration   1: 3.205 ±(99.9%) 0.050 ms/op
Iteration   1: 1.872 ±(99.9%) 0.018 ms/op


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
# Warmup Iteration   1: 3.141 ±(99.9%) 0.063 ms/op
Iteration   1: 1.970 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.970 ms/op


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
# Warmup Iteration   1: 4.656 ±(99.9%) 0.079 ms/op
Iteration   1: 3.706 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.706 ms/op


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
# Warmup Iteration   1: 4.118 ±(99.9%) 0.124 ms/op
Iteration   1: 2.558 ±(99.9%) 0.137 ms/op
                 createUser·p0.00:   0.536 ms/op
                 createUser·p0.50:   2.195 ms/op
                 createUser·p0.90:   2.818 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   6.373 ms/op
                 createUser·p0.999:  92.733 ms/op
                 createUser·p0.9999: 95.257 ms/op
                 createUser·p1.00:   95.289 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12499
  mean =      2.558 ±(99.9%) 0.137 ms/op

  Histogram, ms/op:
    [  0.000,  10.000) = 12434 
    [ 10.000,  20.000) = 33 
    [ 20.000,  30.000) = 0 
    [ 30.000,  40.000) = 0 
    [ 40.000,  50.000) = 0 
    [ 50.000,  60.000) = 0 
    [ 60.000,  70.000) = 0 
    [ 70.000,  80.000) = 0 
    [ 80.000,  90.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.536 ms/op
     p(50.0000) =      2.195 ms/op
     p(90.0000) =      2.818 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      6.373 ms/op
     p(99.9000) =     92.733 ms/op
     p(99.9900) =     95.257 ms/op
     p(99.9990) =     95.289 ms/op
     p(99.9999) =     95.289 ms/op
    p(100.0000) =     95.289 ms/op


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
# Warmup Iteration   1: 3.372 ±(99.9%) 0.080 ms/op
Iteration   1: 1.984 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.438 ms/op
                 existUser·p0.50:   1.896 ms/op
                 existUser·p0.90:   2.388 ms/op
                 existUser·p0.95:   2.548 ms/op
                 existUser·p0.99:   3.878 ms/op
                 existUser·p0.999:  11.331 ms/op
                 existUser·p0.9999: 12.175 ms/op
                 existUser·p1.00:   12.255 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16141
  mean =      1.984 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 179 
    [ 1.250,  2.500) = 14921 
    [ 2.500,  3.750) = 874 
    [ 3.750,  5.000) = 36 
    [ 5.000,  6.250) = 92 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.438 ms/op
     p(50.0000) =      1.896 ms/op
     p(90.0000) =      2.388 ms/op
     p(95.0000) =      2.548 ms/op
     p(99.0000) =      3.878 ms/op
     p(99.9000) =     11.331 ms/op
     p(99.9900) =     12.175 ms/op
     p(99.9990) =     12.255 ms/op
     p(99.9999) =     12.255 ms/op
    p(100.0000) =     12.255 ms/op


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
# Warmup Iteration   1: 3.316 ±(99.9%) 0.105 ms/op
Iteration   1: 1.981 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.660 ms/op
                 getUser·p0.50:   1.800 ms/op
                 getUser·p0.90:   2.576 ms/op
                 getUser·p0.95:   2.830 ms/op
                 getUser·p0.99:   3.617 ms/op
                 getUser·p0.999:  14.860 ms/op
                 getUser·p0.9999: 15.976 ms/op
                 getUser·p1.00:   16.237 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16116
  mean =      1.981 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 74 
    [ 1.250,  2.500) = 14066 
    [ 2.500,  3.750) = 1848 
    [ 3.750,  5.000) = 85 
    [ 5.000,  6.250) = 11 
    [ 6.250,  7.500) = 0 
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
      p(0.0000) =      0.660 ms/op
     p(50.0000) =      1.800 ms/op
     p(90.0000) =      2.576 ms/op
     p(95.0000) =      2.830 ms/op
     p(99.0000) =      3.617 ms/op
     p(99.9000) =     14.860 ms/op
     p(99.9900) =     15.976 ms/op
     p(99.9990) =     16.237 ms/op
     p(99.9999) =     16.237 ms/op
    p(100.0000) =     16.237 ms/op


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
# Warmup Iteration   1: 4.892 ±(99.9%) 0.152 ms/op
Iteration   1: 3.765 ±(99.9%) 0.055 ms/op
                 listUser·p0.00:   1.059 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   4.833 ms/op
                 listUser·p0.99:   8.389 ms/op
                 listUser·p0.999:  21.503 ms/op
                 listUser·p0.9999: 22.675 ms/op
                 listUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8486
  mean =      3.765 ±(99.9%) 0.055 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 207 
    [ 2.500,  5.000) = 7941 
    [ 5.000,  7.500) = 238 
    [ 7.500, 10.000) = 36 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.059 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.506 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      8.389 ms/op
     p(99.9000) =     21.503 ms/op
     p(99.9900) =     22.675 ms/op
     p(99.9990) =     22.675 ms/op
     p(99.9999) =     22.675 ms/op
    p(100.0000) =     22.675 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.017          ops/ms
ClientSimple.existUser                       thrpt         12.249          ops/ms
ClientSimple.getUser                         thrpt         11.607          ops/ms
ClientSimple.listUser                        thrpt          8.542          ops/ms
ClientSimple.createUser                       avgt          2.187           ms/op
ClientSimple.existUser                        avgt          1.872           ms/op
ClientSimple.getUser                          avgt          1.970           ms/op
ClientSimple.listUser                         avgt          3.706           ms/op
ClientSimple.createUser                     sample  12499   2.558 ± 0.137   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.536           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.195           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.818           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.211           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.373           ms/op
ClientSimple.createUser:createUser·p0.999   sample         92.733           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         95.257           ms/op
ClientSimple.createUser:createUser·p1.00    sample         95.289           ms/op
ClientSimple.existUser                      sample  16141   1.984 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.438           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.896           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.388           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.548           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.878           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.331           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.175           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.255           ms/op
ClientSimple.getUser                        sample  16116   1.981 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.660           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.800           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.576           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.830           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.617           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.860           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.976           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.237           ms/op
ClientSimple.listUser                       sample   8486   3.765 ± 0.055   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.059           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.686           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.506           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.833           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.389           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.503           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         22.675           ms/op
ClientSimple.listUser:listUser·p1.00        sample         22.675           ms/op

Benchmark result is saved to 1716033992028.json
