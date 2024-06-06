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
# Warmup Iteration   1: 1.586 ops/ms
Iteration   1: 6.059 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.059 ops/ms


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
# Warmup Iteration   1: 5.353 ops/ms
Iteration   1: 11.818 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.818 ops/ms


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
# Warmup Iteration   1: 4.246 ops/ms
Iteration   1: 10.188 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.188 ops/ms


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
# Warmup Iteration   1: 4.621 ops/ms
Iteration   1: 9.114 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.114 ops/ms


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
# Warmup Iteration   1: 4.184 ±(99.9%) 0.072 ms/op
Iteration   1: 2.172 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.172 ms/op


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
# Warmup Iteration   1: 3.091 ±(99.9%) 0.052 ms/op
Iteration   1: 2.015 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.015 ms/op


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
# Warmup Iteration   1: 3.444 ±(99.9%) 0.057 ms/op
Iteration   1: 2.111 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.111 ms/op


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
# Warmup Iteration   1: 5.039 ±(99.9%) 0.112 ms/op
Iteration   1: 3.517 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.517 ms/op


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
# Warmup Iteration   1: 3.450 ±(99.9%) 0.095 ms/op
Iteration   1: 2.071 ±(99.9%) 0.045 ms/op
                 createUser·p0.00:   0.552 ms/op
                 createUser·p0.50:   1.843 ms/op
                 createUser·p0.90:   2.347 ms/op
                 createUser·p0.95:   3.025 ms/op
                 createUser·p0.99:   7.668 ms/op
                 createUser·p0.999:  27.230 ms/op
                 createUser·p0.9999: 32.831 ms/op
                 createUser·p1.00:   33.260 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15449
  mean =      2.071 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14337 
    [ 2.500,  5.000) = 882 
    [ 5.000,  7.500) = 73 
    [ 7.500, 10.000) = 50 
    [10.000, 12.500) = 11 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.552 ms/op
     p(50.0000) =      1.843 ms/op
     p(90.0000) =      2.347 ms/op
     p(95.0000) =      3.025 ms/op
     p(99.0000) =      7.668 ms/op
     p(99.9000) =     27.230 ms/op
     p(99.9900) =     32.831 ms/op
     p(99.9990) =     33.260 ms/op
     p(99.9999) =     33.260 ms/op
    p(100.0000) =     33.260 ms/op


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
# Warmup Iteration   1: 3.015 ±(99.9%) 0.090 ms/op
Iteration   1: 1.847 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.333 ms/op
                 existUser·p0.50:   1.788 ms/op
                 existUser·p0.90:   2.462 ms/op
                 existUser·p0.95:   2.580 ms/op
                 existUser·p0.99:   2.961 ms/op
                 existUser·p0.999:  12.609 ms/op
                 existUser·p0.9999: 12.907 ms/op
                 existUser·p1.00:   12.993 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17427
  mean =      1.847 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1165 
    [ 1.250,  2.500) = 14856 
    [ 2.500,  3.750) = 1341 
    [ 3.750,  5.000) = 14 
    [ 5.000,  6.250) = 18 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.333 ms/op
     p(50.0000) =      1.788 ms/op
     p(90.0000) =      2.462 ms/op
     p(95.0000) =      2.580 ms/op
     p(99.0000) =      2.961 ms/op
     p(99.9000) =     12.609 ms/op
     p(99.9900) =     12.907 ms/op
     p(99.9990) =     12.993 ms/op
     p(99.9999) =     12.993 ms/op
    p(100.0000) =     12.993 ms/op


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
# Warmup Iteration   1: 3.135 ±(99.9%) 0.083 ms/op
Iteration   1: 1.944 ±(99.9%) 0.031 ms/op
                 getUser·p0.00:   0.722 ms/op
                 getUser·p0.50:   1.786 ms/op
                 getUser·p0.90:   2.433 ms/op
                 getUser·p0.95:   2.683 ms/op
                 getUser·p0.99:   4.468 ms/op
                 getUser·p0.999:  22.577 ms/op
                 getUser·p0.9999: 23.398 ms/op
                 getUser·p1.00:   23.462 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16454
  mean =      1.944 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15105 
    [ 2.500,  5.000) = 1207 
    [ 5.000,  7.500) = 46 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.722 ms/op
     p(50.0000) =      1.786 ms/op
     p(90.0000) =      2.433 ms/op
     p(95.0000) =      2.683 ms/op
     p(99.0000) =      4.468 ms/op
     p(99.9000) =     22.577 ms/op
     p(99.9900) =     23.398 ms/op
     p(99.9990) =     23.462 ms/op
     p(99.9999) =     23.462 ms/op
    p(100.0000) =     23.462 ms/op


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
# Warmup Iteration   1: 4.677 ±(99.9%) 0.160 ms/op
Iteration   1: 3.089 ±(99.9%) 0.045 ms/op
                 listUser·p0.00:   0.698 ms/op
                 listUser·p0.50:   2.773 ms/op
                 listUser·p0.90:   3.990 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   6.022 ms/op
                 listUser·p0.999:  24.510 ms/op
                 listUser·p0.9999: 26.184 ms/op
                 listUser·p1.00:   26.247 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10394
  mean =      3.089 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1376 
    [ 2.500,  5.000) = 8829 
    [ 5.000,  7.500) = 157 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.698 ms/op
     p(50.0000) =      2.773 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      6.022 ms/op
     p(99.9000) =     24.510 ms/op
     p(99.9900) =     26.184 ms/op
     p(99.9990) =     26.247 ms/op
     p(99.9999) =     26.247 ms/op
    p(100.0000) =     26.247 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.059          ops/ms
ClientSimple.existUser                       thrpt         11.818          ops/ms
ClientSimple.getUser                         thrpt         10.188          ops/ms
ClientSimple.listUser                        thrpt          9.114          ops/ms
ClientSimple.createUser                       avgt          2.172           ms/op
ClientSimple.existUser                        avgt          2.015           ms/op
ClientSimple.getUser                          avgt          2.111           ms/op
ClientSimple.listUser                         avgt          3.517           ms/op
ClientSimple.createUser                     sample  15449   2.071 ± 0.045   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.552           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.843           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.347           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.025           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.668           ms/op
ClientSimple.createUser:createUser·p0.999   sample         27.230           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         32.831           ms/op
ClientSimple.createUser:createUser·p1.00    sample         33.260           ms/op
ClientSimple.existUser                      sample  17427   1.847 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.333           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.788           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.462           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.580           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.961           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.609           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.907           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.993           ms/op
ClientSimple.getUser                        sample  16454   1.944 ± 0.031   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.722           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.786           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.433           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.683           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.468           ms/op
ClientSimple.getUser:getUser·p0.999         sample         22.577           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         23.398           ms/op
ClientSimple.getUser:getUser·p1.00          sample         23.462           ms/op
ClientSimple.listUser                       sample  10394   3.089 ± 0.045   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.698           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.773           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.990           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.268           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.022           ms/op
ClientSimple.listUser:listUser·p0.999       sample         24.510           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         26.184           ms/op
ClientSimple.listUser:listUser·p1.00        sample         26.247           ms/op

Benchmark result is saved to 1717675607163.json
