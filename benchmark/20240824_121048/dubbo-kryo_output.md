# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.784 ops/ms
Iteration   1: 7.145 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.145 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.848 ops/ms
Iteration   1: 13.685 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.685 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.846 ops/ms
Iteration   1: 11.836 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.836 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.474 ops/ms
Iteration   1: 9.182 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.182 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.675 ±(99.9%) 0.062 ms/op
Iteration   1: 2.090 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.090 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.074 ±(99.9%) 0.055 ms/op
Iteration   1: 2.007 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.007 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.217 ±(99.9%) 0.051 ms/op
Iteration   1: 2.044 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.044 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.405 ±(99.9%) 0.097 ms/op
Iteration   1: 3.272 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.272 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.786 ±(99.9%) 0.114 ms/op
Iteration   1: 1.967 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.578 ms/op
                 createUser·p0.50:   1.780 ms/op
                 createUser·p0.90:   2.339 ms/op
                 createUser·p0.95:   2.646 ms/op
                 createUser·p0.99:   6.099 ms/op
                 createUser·p0.999:  16.413 ms/op
                 createUser·p0.9999: 17.474 ms/op
                 createUser·p1.00:   17.596 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16249
  mean =      1.967 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 462 
    [ 1.250,  2.500) = 14696 
    [ 2.500,  3.750) = 726 
    [ 3.750,  5.000) = 167 
    [ 5.000,  6.250) = 41 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 42 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.578 ms/op
     p(50.0000) =      1.780 ms/op
     p(90.0000) =      2.339 ms/op
     p(95.0000) =      2.646 ms/op
     p(99.0000) =      6.099 ms/op
     p(99.9000) =     16.413 ms/op
     p(99.9900) =     17.474 ms/op
     p(99.9990) =     17.596 ms/op
     p(99.9999) =     17.596 ms/op
    p(100.0000) =     17.596 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.952 ±(99.9%) 0.074 ms/op
Iteration   1: 1.881 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.636 ms/op
                 existUser·p0.50:   1.786 ms/op
                 existUser·p0.90:   2.290 ms/op
                 existUser·p0.95:   2.507 ms/op
                 existUser·p0.99:   2.927 ms/op
                 existUser·p0.999:  15.843 ms/op
                 existUser·p0.9999: 15.974 ms/op
                 existUser·p1.00:   16.056 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17136
  mean =      1.881 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 99 
    [ 1.250,  2.500) = 16154 
    [ 2.500,  3.750) = 814 
    [ 3.750,  5.000) = 30 
    [ 5.000,  6.250) = 6 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.636 ms/op
     p(50.0000) =      1.786 ms/op
     p(90.0000) =      2.290 ms/op
     p(95.0000) =      2.507 ms/op
     p(99.0000) =      2.927 ms/op
     p(99.9000) =     15.843 ms/op
     p(99.9900) =     15.974 ms/op
     p(99.9990) =     16.056 ms/op
     p(99.9999) =     16.056 ms/op
    p(100.0000) =     16.056 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.362 ±(99.9%) 0.093 ms/op
Iteration   1: 2.056 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.425 ms/op
                 getUser·p0.50:   1.950 ms/op
                 getUser·p0.90:   2.609 ms/op
                 getUser·p0.95:   2.785 ms/op
                 getUser·p0.99:   3.931 ms/op
                 getUser·p0.999:  18.523 ms/op
                 getUser·p0.9999: 19.606 ms/op
                 getUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15610
  mean =      2.056 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 378 
    [ 1.250,  2.500) = 12963 
    [ 2.500,  3.750) = 2099 
    [ 3.750,  5.000) = 93 
    [ 5.000,  6.250) = 20 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.425 ms/op
     p(50.0000) =      1.950 ms/op
     p(90.0000) =      2.609 ms/op
     p(95.0000) =      2.785 ms/op
     p(99.0000) =      3.931 ms/op
     p(99.9000) =     18.523 ms/op
     p(99.9900) =     19.606 ms/op
     p(99.9990) =     19.661 ms/op
     p(99.9999) =     19.661 ms/op
    p(100.0000) =     19.661 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.421 ±(99.9%) 0.128 ms/op
Iteration   1: 4.140 ±(99.9%) 0.279 ms/op
                 listUser·p0.00:   0.994 ms/op
                 listUser·p0.50:   3.514 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   24.335 ms/op
                 listUser·p0.999:  113.069 ms/op
                 listUser·p0.9999: 118.358 ms/op
                 listUser·p1.00:   118.358 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 7793
  mean =      4.140 ±(99.9%) 0.279 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 7667 
    [ 12.500,  25.000) = 49 
    [ 25.000,  37.500) = 13 
    [ 37.500,  50.000) = 9 
    [ 50.000,  62.500) = 11 
    [ 62.500,  75.000) = 13 
    [ 75.000,  87.500) = 3 
    [ 87.500, 100.000) = 8 
    [100.000, 112.500) = 11 
    [112.500, 125.000) = 9 
    [125.000, 137.500) = 0 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.994 ms/op
     p(50.0000) =      3.514 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =     24.335 ms/op
     p(99.9000) =    113.069 ms/op
     p(99.9900) =    118.358 ms/op
     p(99.9990) =    118.358 ms/op
     p(99.9999) =    118.358 ms/op
    p(100.0000) =    118.358 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt    Score   Error   Units
ClientSimple.createUser                      thrpt           7.145          ops/ms
ClientSimple.existUser                       thrpt          13.685          ops/ms
ClientSimple.getUser                         thrpt          11.836          ops/ms
ClientSimple.listUser                        thrpt           9.182          ops/ms
ClientSimple.createUser                       avgt           2.090           ms/op
ClientSimple.existUser                        avgt           2.007           ms/op
ClientSimple.getUser                          avgt           2.044           ms/op
ClientSimple.listUser                         avgt           3.272           ms/op
ClientSimple.createUser                     sample  16249    1.967 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample           0.578           ms/op
ClientSimple.createUser:createUser·p0.50    sample           1.780           ms/op
ClientSimple.createUser:createUser·p0.90    sample           2.339           ms/op
ClientSimple.createUser:createUser·p0.95    sample           2.646           ms/op
ClientSimple.createUser:createUser·p0.99    sample           6.099           ms/op
ClientSimple.createUser:createUser·p0.999   sample          16.413           ms/op
ClientSimple.createUser:createUser·p0.9999  sample          17.474           ms/op
ClientSimple.createUser:createUser·p1.00    sample          17.596           ms/op
ClientSimple.existUser                      sample  17136    1.881 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample           0.636           ms/op
ClientSimple.existUser:existUser·p0.50      sample           1.786           ms/op
ClientSimple.existUser:existUser·p0.90      sample           2.290           ms/op
ClientSimple.existUser:existUser·p0.95      sample           2.507           ms/op
ClientSimple.existUser:existUser·p0.99      sample           2.927           ms/op
ClientSimple.existUser:existUser·p0.999     sample          15.843           ms/op
ClientSimple.existUser:existUser·p0.9999    sample          15.974           ms/op
ClientSimple.existUser:existUser·p1.00      sample          16.056           ms/op
ClientSimple.getUser                        sample  15610    2.056 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample           0.425           ms/op
ClientSimple.getUser:getUser·p0.50          sample           1.950           ms/op
ClientSimple.getUser:getUser·p0.90          sample           2.609           ms/op
ClientSimple.getUser:getUser·p0.95          sample           2.785           ms/op
ClientSimple.getUser:getUser·p0.99          sample           3.931           ms/op
ClientSimple.getUser:getUser·p0.999         sample          18.523           ms/op
ClientSimple.getUser:getUser·p0.9999        sample          19.606           ms/op
ClientSimple.getUser:getUser·p1.00          sample          19.661           ms/op
ClientSimple.listUser                       sample   7793    4.140 ± 0.279   ms/op
ClientSimple.listUser:listUser·p0.00        sample           0.994           ms/op
ClientSimple.listUser:listUser·p0.50        sample           3.514           ms/op
ClientSimple.listUser:listUser·p0.90        sample           4.301           ms/op
ClientSimple.listUser:listUser·p0.95        sample           4.719           ms/op
ClientSimple.listUser:listUser·p0.99        sample          24.335           ms/op
ClientSimple.listUser:listUser·p0.999       sample         113.069           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         118.358           ms/op
ClientSimple.listUser:listUser·p1.00        sample         118.358           ms/op

Benchmark result is saved to 1724501171892.json
