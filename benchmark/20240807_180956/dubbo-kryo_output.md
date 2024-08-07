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
# Warmup Iteration   1: 1.939 ops/ms
Iteration   1: 6.442 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.442 ops/ms


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
# Warmup Iteration   1: 5.823 ops/ms
Iteration   1: 12.452 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.452 ops/ms


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
# Warmup Iteration   1: 5.331 ops/ms
Iteration   1: 13.475 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.475 ops/ms


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
# Warmup Iteration   1: 4.839 ops/ms
Iteration   1: 8.308 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.308 ops/ms


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
# Warmup Iteration   1: 3.537 ±(99.9%) 0.066 ms/op
Iteration   1: 2.399 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.399 ms/op


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
# Warmup Iteration   1: 3.404 ±(99.9%) 0.057 ms/op
Iteration   1: 1.801 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.801 ms/op


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
# Warmup Iteration   1: 3.167 ±(99.9%) 0.055 ms/op
Iteration   1: 2.116 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.116 ms/op


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
# Warmup Iteration   1: 5.212 ±(99.9%) 0.106 ms/op
Iteration   1: 3.462 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.462 ms/op


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
# Warmup Iteration   1: 3.565 ±(99.9%) 0.102 ms/op
Iteration   1: 2.282 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.616 ms/op
                 createUser·p0.50:   2.066 ms/op
                 createUser·p0.90:   2.953 ms/op
                 createUser·p0.95:   3.267 ms/op
                 createUser·p0.99:   5.562 ms/op
                 createUser·p0.999:  18.841 ms/op
                 createUser·p0.9999: 23.430 ms/op
                 createUser·p1.00:   25.625 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14009
  mean =      2.282 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10588 
    [ 2.500,  5.000) = 3250 
    [ 5.000,  7.500) = 55 
    [ 7.500, 10.000) = 39 
    [10.000, 12.500) = 13 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.616 ms/op
     p(50.0000) =      2.066 ms/op
     p(90.0000) =      2.953 ms/op
     p(95.0000) =      3.267 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =     18.841 ms/op
     p(99.9900) =     23.430 ms/op
     p(99.9990) =     25.625 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


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
# Warmup Iteration   1: 3.106 ±(99.9%) 0.072 ms/op
Iteration   1: 1.706 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.791 ms/op
                 existUser·p0.50:   1.616 ms/op
                 existUser·p0.90:   1.919 ms/op
                 existUser·p0.95:   2.085 ms/op
                 existUser·p0.99:   2.593 ms/op
                 existUser·p0.999:  20.587 ms/op
                 existUser·p0.9999: 21.263 ms/op
                 existUser·p1.00:   21.463 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18741
  mean =      1.706 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18495 
    [ 2.500,  5.000) = 182 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.791 ms/op
     p(50.0000) =      1.616 ms/op
     p(90.0000) =      1.919 ms/op
     p(95.0000) =      2.085 ms/op
     p(99.0000) =      2.593 ms/op
     p(99.9000) =     20.587 ms/op
     p(99.9900) =     21.263 ms/op
     p(99.9990) =     21.463 ms/op
     p(99.9999) =     21.463 ms/op
    p(100.0000) =     21.463 ms/op


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
# Warmup Iteration   1: 3.201 ±(99.9%) 0.080 ms/op
Iteration   1: 1.931 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.628 ms/op
                 getUser·p0.50:   1.831 ms/op
                 getUser·p0.90:   2.494 ms/op
                 getUser·p0.95:   2.695 ms/op
                 getUser·p0.99:   3.151 ms/op
                 getUser·p0.999:  11.492 ms/op
                 getUser·p0.9999: 12.420 ms/op
                 getUser·p1.00:   12.517 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16572
  mean =      1.931 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 325 
    [ 1.250,  2.500) = 14634 
    [ 2.500,  3.750) = 1506 
    [ 3.750,  5.000) = 33 
    [ 5.000,  6.250) = 41 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.628 ms/op
     p(50.0000) =      1.831 ms/op
     p(90.0000) =      2.494 ms/op
     p(95.0000) =      2.695 ms/op
     p(99.0000) =      3.151 ms/op
     p(99.9000) =     11.492 ms/op
     p(99.9900) =     12.420 ms/op
     p(99.9990) =     12.517 ms/op
     p(99.9999) =     12.517 ms/op
    p(100.0000) =     12.517 ms/op


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
# Warmup Iteration   1: 4.545 ±(99.9%) 0.139 ms/op
Iteration   1: 2.969 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.085 ms/op
                 listUser·p0.50:   2.695 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.141 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  13.701 ms/op
                 listUser·p0.9999: 13.876 ms/op
                 listUser·p1.00:   13.877 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10761
  mean =      2.969 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 1782 
    [ 2.500,  3.750) = 7655 
    [ 3.750,  5.000) = 1097 
    [ 5.000,  6.250) = 159 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.085 ms/op
     p(50.0000) =      2.695 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.141 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =     13.701 ms/op
     p(99.9900) =     13.876 ms/op
     p(99.9990) =     13.877 ms/op
     p(99.9999) =     13.877 ms/op
    p(100.0000) =     13.877 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.442          ops/ms
ClientSimple.existUser                       thrpt         12.452          ops/ms
ClientSimple.getUser                         thrpt         13.475          ops/ms
ClientSimple.listUser                        thrpt          8.308          ops/ms
ClientSimple.createUser                       avgt          2.399           ms/op
ClientSimple.existUser                        avgt          1.801           ms/op
ClientSimple.getUser                          avgt          2.116           ms/op
ClientSimple.listUser                         avgt          3.462           ms/op
ClientSimple.createUser                     sample  14009   2.282 ± 0.036   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.616           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.066           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.953           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.267           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.562           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.841           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.430           ms/op
ClientSimple.createUser:createUser·p1.00    sample         25.625           ms/op
ClientSimple.existUser                      sample  18741   1.706 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.791           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.616           ms/op
ClientSimple.existUser:existUser·p0.90      sample          1.919           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.085           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.593           ms/op
ClientSimple.existUser:existUser·p0.999     sample         20.587           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         21.263           ms/op
ClientSimple.existUser:existUser·p1.00      sample         21.463           ms/op
ClientSimple.getUser                        sample  16572   1.931 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.628           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.831           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.494           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.695           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.151           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.492           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.420           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.517           ms/op
ClientSimple.listUser                       sample  10761   2.969 ± 0.027   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.085           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.695           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.838           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.141           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.644           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.701           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         13.876           ms/op
ClientSimple.listUser:listUser·p1.00        sample         13.877           ms/op

Benchmark result is saved to 1723053924880.json
