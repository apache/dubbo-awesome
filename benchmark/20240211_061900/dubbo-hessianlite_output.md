# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.139 ops/ms
Iteration   1: 5.655 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.655 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.782 ops/ms
Iteration   1: 13.574 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.574 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.388 ops/ms
Iteration   1: 8.574 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.574 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.043 ops/ms
Iteration   1: 3.651 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.651 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.492 ±(99.9%) 0.064 ms/op
Iteration   1: 3.381 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.381 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.278 ±(99.9%) 0.037 ms/op
Iteration   1: 1.831 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.831 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 5.282 ±(99.9%) 0.080 ms/op
Iteration   1: 3.490 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.490 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 14.393 ±(99.9%) 0.382 ms/op
Iteration   1: 9.521 ±(99.9%) 0.172 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.521 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.322 ±(99.9%) 0.118 ms/op
Iteration   1: 3.203 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.665 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   4.043 ms/op
                 createUser·p0.95:   4.383 ms/op
                 createUser·p0.99:   5.230 ms/op
                 createUser·p0.999:  6.144 ms/op
                 createUser·p0.9999: 6.291 ms/op
                 createUser·p1.00:   6.291 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9980
  mean =      3.203 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 0 
    [1.500, 2.000) = 31 
    [2.000, 2.500) = 1099 
    [2.500, 3.000) = 2858 
    [3.000, 3.500) = 3519 
    [3.500, 4.000) = 1375 
    [4.000, 4.500) = 725 
    [4.500, 5.000) = 225 
    [5.000, 5.500) = 80 
    [5.500, 6.000) = 32 
    [6.000, 6.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      1.665 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      4.043 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.230 ms/op
     p(99.9000) =      6.144 ms/op
     p(99.9900) =      6.291 ms/op
     p(99.9990) =      6.291 ms/op
     p(99.9999) =      6.291 ms/op
    p(100.0000) =      6.291 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.094 ±(99.9%) 0.068 ms/op
Iteration   1: 1.770 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.831 ms/op
                 existUser·p0.50:   1.686 ms/op
                 existUser·p0.90:   2.024 ms/op
                 existUser·p0.95:   2.212 ms/op
                 existUser·p0.99:   2.953 ms/op
                 existUser·p0.999:  20.054 ms/op
                 existUser·p0.9999: 21.481 ms/op
                 existUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18065
  mean =      1.770 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17679 
    [ 2.500,  5.000) = 353 
    [ 5.000,  7.500) = 1 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.831 ms/op
     p(50.0000) =      1.686 ms/op
     p(90.0000) =      2.024 ms/op
     p(95.0000) =      2.212 ms/op
     p(99.0000) =      2.953 ms/op
     p(99.9000) =     20.054 ms/op
     p(99.9900) =     21.481 ms/op
     p(99.9990) =     21.692 ms/op
     p(99.9999) =     21.692 ms/op
    p(100.0000) =     21.692 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.678 ±(99.9%) 0.110 ms/op
Iteration   1: 3.353 ±(99.9%) 0.031 ms/op
                 getUser·p0.00:   1.116 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   4.080 ms/op
                 getUser·p0.95:   4.399 ms/op
                 getUser·p0.99:   5.914 ms/op
                 getUser·p0.999:  14.214 ms/op
                 getUser·p0.9999: 14.369 ms/op
                 getUser·p1.00:   14.369 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9604
  mean =      3.353 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 863 
    [ 2.500,  3.750) = 6603 
    [ 3.750,  5.000) = 1935 
    [ 5.000,  6.250) = 125 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.116 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      4.080 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.914 ms/op
     p(99.9000) =     14.214 ms/op
     p(99.9900) =     14.369 ms/op
     p(99.9990) =     14.369 ms/op
     p(99.9999) =     14.369 ms/op
    p(100.0000) =     14.369 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 12.137 ±(99.9%) 0.446 ms/op
Iteration   1: 8.535 ±(99.9%) 0.120 ms/op
                 listUser·p0.00:   1.673 ms/op
                 listUser·p0.50:   8.258 ms/op
                 listUser·p0.90:   11.108 ms/op
                 listUser·p0.95:   12.141 ms/op
                 listUser·p0.99:   18.068 ms/op
                 listUser·p0.999:  20.334 ms/op
                 listUser·p0.9999: 21.463 ms/op
                 listUser·p1.00:   21.463 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3729
  mean =      8.535 ±(99.9%) 0.120 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 56 
    [ 5.000,  7.500) = 1138 
    [ 7.500, 10.000) = 1844 
    [10.000, 12.500) = 525 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.673 ms/op
     p(50.0000) =      8.258 ms/op
     p(90.0000) =     11.108 ms/op
     p(95.0000) =     12.141 ms/op
     p(99.0000) =     18.068 ms/op
     p(99.9000) =     20.334 ms/op
     p(99.9900) =     21.463 ms/op
     p(99.9990) =     21.463 ms/op
     p(99.9999) =     21.463 ms/op
    p(100.0000) =     21.463 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.655          ops/ms
Client.existUser                       thrpt         13.574          ops/ms
Client.getUser                         thrpt          8.574          ops/ms
Client.listUser                        thrpt          3.651          ops/ms
Client.createUser                       avgt          3.381           ms/op
Client.existUser                        avgt          1.831           ms/op
Client.getUser                          avgt          3.490           ms/op
Client.listUser                         avgt          9.521           ms/op
Client.createUser                     sample   9980   3.203 ± 0.021   ms/op
Client.createUser:createUser·p0.00    sample          1.665           ms/op
Client.createUser:createUser·p0.50    sample          3.138           ms/op
Client.createUser:createUser·p0.90    sample          4.043           ms/op
Client.createUser:createUser·p0.95    sample          4.383           ms/op
Client.createUser:createUser·p0.99    sample          5.230           ms/op
Client.createUser:createUser·p0.999   sample          6.144           ms/op
Client.createUser:createUser·p0.9999  sample          6.291           ms/op
Client.createUser:createUser·p1.00    sample          6.291           ms/op
Client.existUser                      sample  18065   1.770 ± 0.020   ms/op
Client.existUser:existUser·p0.00      sample          0.831           ms/op
Client.existUser:existUser·p0.50      sample          1.686           ms/op
Client.existUser:existUser·p0.90      sample          2.024           ms/op
Client.existUser:existUser·p0.95      sample          2.212           ms/op
Client.existUser:existUser·p0.99      sample          2.953           ms/op
Client.existUser:existUser·p0.999     sample         20.054           ms/op
Client.existUser:existUser·p0.9999    sample         21.481           ms/op
Client.existUser:existUser·p1.00      sample         21.692           ms/op
Client.getUser                        sample   9604   3.353 ± 0.031   ms/op
Client.getUser:getUser·p0.00          sample          1.116           ms/op
Client.getUser:getUser·p0.50          sample          3.297           ms/op
Client.getUser:getUser·p0.90          sample          4.080           ms/op
Client.getUser:getUser·p0.95          sample          4.399           ms/op
Client.getUser:getUser·p0.99          sample          5.914           ms/op
Client.getUser:getUser·p0.999         sample         14.214           ms/op
Client.getUser:getUser·p0.9999        sample         14.369           ms/op
Client.getUser:getUser·p1.00          sample         14.369           ms/op
Client.listUser                       sample   3729   8.535 ± 0.120   ms/op
Client.listUser:listUser·p0.00        sample          1.673           ms/op
Client.listUser:listUser·p0.50        sample          8.258           ms/op
Client.listUser:listUser·p0.90        sample         11.108           ms/op
Client.listUser:listUser·p0.95        sample         12.141           ms/op
Client.listUser:listUser·p0.99        sample         18.068           ms/op
Client.listUser:listUser·p0.999       sample         20.334           ms/op
Client.listUser:listUser·p0.9999      sample         21.463           ms/op
Client.listUser:listUser·p1.00        sample         21.463           ms/op
