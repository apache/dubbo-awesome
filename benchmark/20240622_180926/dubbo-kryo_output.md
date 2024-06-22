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
# Warmup Iteration   1: 2.115 ops/ms
Iteration   1: 7.249 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.249 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.863 ops/ms
Iteration   1: 11.582 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.582 ops/ms


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
# Warmup Iteration   1: 5.707 ops/ms
Iteration   1: 14.024 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.024 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 4.862 ops/ms
Iteration   1: 9.144 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.144 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.333 ±(99.9%) 0.055 ms/op
Iteration   1: 2.064 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.899 ±(99.9%) 0.047 ms/op
Iteration   1: 1.507 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.507 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.294 ±(99.9%) 0.074 ms/op
Iteration   1: 1.882 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.882 ms/op


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
# Warmup Iteration   1: 4.279 ±(99.9%) 0.093 ms/op
Iteration   1: 3.397 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.397 ms/op


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
# Warmup Iteration   1: 3.339 ±(99.9%) 0.084 ms/op
Iteration   1: 2.151 ±(99.9%) 0.078 ms/op
                 createUser·p0.00:   0.535 ms/op
                 createUser·p0.50:   1.837 ms/op
                 createUser·p0.90:   2.384 ms/op
                 createUser·p0.95:   2.843 ms/op
                 createUser·p0.99:   6.278 ms/op
                 createUser·p0.999:  58.786 ms/op
                 createUser·p0.9999: 79.825 ms/op
                 createUser·p1.00:   92.668 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15076
  mean =      2.151 ±(99.9%) 0.078 ms/op

  Histogram, ms/op:
    [  0.000,  10.000) = 14979 
    [ 10.000,  20.000) = 64 
    [ 20.000,  30.000) = 0 
    [ 30.000,  40.000) = 1 
    [ 40.000,  50.000) = 0 
    [ 50.000,  60.000) = 25 
    [ 60.000,  70.000) = 6 
    [ 70.000,  80.000) = 0 
    [ 80.000,  90.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.535 ms/op
     p(50.0000) =      1.837 ms/op
     p(90.0000) =      2.384 ms/op
     p(95.0000) =      2.843 ms/op
     p(99.0000) =      6.278 ms/op
     p(99.9000) =     58.786 ms/op
     p(99.9900) =     79.825 ms/op
     p(99.9990) =     92.668 ms/op
     p(99.9999) =     92.668 ms/op
    p(100.0000) =     92.668 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.003 ±(99.9%) 0.064 ms/op
Iteration   1: 1.966 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   0.465 ms/op
                 existUser·p0.50:   1.876 ms/op
                 existUser·p0.90:   2.300 ms/op
                 existUser·p0.95:   2.449 ms/op
                 existUser·p0.99:   4.056 ms/op
                 existUser·p0.999:  25.674 ms/op
                 existUser·p0.9999: 26.041 ms/op
                 existUser·p1.00:   26.083 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16483
  mean =      1.966 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15841 
    [ 2.500,  5.000) = 518 
    [ 5.000,  7.500) = 60 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.465 ms/op
     p(50.0000) =      1.876 ms/op
     p(90.0000) =      2.300 ms/op
     p(95.0000) =      2.449 ms/op
     p(99.0000) =      4.056 ms/op
     p(99.9000) =     25.674 ms/op
     p(99.9900) =     26.041 ms/op
     p(99.9990) =     26.083 ms/op
     p(99.9999) =     26.083 ms/op
    p(100.0000) =     26.083 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 3.878 ±(99.9%) 0.192 ms/op
Iteration   1: 2.152 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.582 ms/op
                 getUser·p0.50:   2.068 ms/op
                 getUser·p0.90:   2.621 ms/op
                 getUser·p0.95:   2.810 ms/op
                 getUser·p0.99:   4.563 ms/op
                 getUser·p0.999:  14.526 ms/op
                 getUser·p0.9999: 15.198 ms/op
                 getUser·p1.00:   15.254 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14882
  mean =      2.152 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 124 
    [ 1.250,  2.500) = 12508 
    [ 2.500,  3.750) = 2005 
    [ 3.750,  5.000) = 122 
    [ 5.000,  6.250) = 76 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.582 ms/op
     p(50.0000) =      2.068 ms/op
     p(90.0000) =      2.621 ms/op
     p(95.0000) =      2.810 ms/op
     p(99.0000) =      4.563 ms/op
     p(99.9000) =     14.526 ms/op
     p(99.9900) =     15.198 ms/op
     p(99.9990) =     15.254 ms/op
     p(99.9999) =     15.254 ms/op
    p(100.0000) =     15.254 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.446 ±(99.9%) 0.107 ms/op
Iteration   1: 3.121 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   0.859 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.990 ms/op
                 listUser·p0.95:   4.202 ms/op
                 listUser·p0.99:   4.838 ms/op
                 listUser·p0.999:  6.165 ms/op
                 listUser·p0.9999: 6.241 ms/op
                 listUser·p1.00:   6.242 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10446
  mean =      3.121 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 4 
    [1.000, 1.500) = 34 
    [1.500, 2.000) = 114 
    [2.000, 2.500) = 1259 
    [2.500, 3.000) = 4040 
    [3.000, 3.500) = 1947 
    [3.500, 4.000) = 2032 
    [4.000, 4.500) = 788 
    [4.500, 5.000) = 136 
    [5.000, 5.500) = 60 
    [5.500, 6.000) = 13 
    [6.000, 6.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.859 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      4.838 ms/op
     p(99.9000) =      6.165 ms/op
     p(99.9900) =      6.241 ms/op
     p(99.9990) =      6.242 ms/op
     p(99.9999) =      6.242 ms/op
    p(100.0000) =      6.242 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.249          ops/ms
ClientSimple.existUser                       thrpt         11.582          ops/ms
ClientSimple.getUser                         thrpt         14.024          ops/ms
ClientSimple.listUser                        thrpt          9.144          ops/ms
ClientSimple.createUser                       avgt          2.064           ms/op
ClientSimple.existUser                        avgt          1.507           ms/op
ClientSimple.getUser                          avgt          1.882           ms/op
ClientSimple.listUser                         avgt          3.397           ms/op
ClientSimple.createUser                     sample  15076   2.151 ± 0.078   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.535           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.837           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.384           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.843           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.278           ms/op
ClientSimple.createUser:createUser·p0.999   sample         58.786           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         79.825           ms/op
ClientSimple.createUser:createUser·p1.00    sample         92.668           ms/op
ClientSimple.existUser                      sample  16483   1.966 ± 0.031   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.465           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.876           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.300           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.449           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.056           ms/op
ClientSimple.existUser:existUser·p0.999     sample         25.674           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         26.041           ms/op
ClientSimple.existUser:existUser·p1.00      sample         26.083           ms/op
ClientSimple.getUser                        sample  14882   2.152 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.582           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.068           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.621           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.810           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.563           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.526           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.198           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.254           ms/op
ClientSimple.listUser                       sample  10446   3.121 ± 0.021   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.859           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.957           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.990           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.202           ms/op
ClientSimple.listUser:listUser·p0.99        sample          4.838           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.165           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          6.241           ms/op
ClientSimple.listUser:listUser·p1.00        sample          6.242           ms/op

Benchmark result is saved to 1719079511536.json
