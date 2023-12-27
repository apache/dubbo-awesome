# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.273 ops/ms
Iteration   1: 5.721 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.721 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.838 ops/ms
Iteration   1: 12.588 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.588 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.581 ops/ms
Iteration   1: 9.466 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.466 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.398 ops/ms
Iteration   1: 3.764 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.764 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.091 ±(99.9%) 0.084 ms/op
Iteration   1: 3.095 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.095 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.311 ±(99.9%) 0.034 ms/op
Iteration   1: 1.900 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.900 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.344 ±(99.9%) 0.057 ms/op
Iteration   1: 3.059 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.059 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 11.839 ±(99.9%) 0.214 ms/op
Iteration   1: 8.637 ±(99.9%) 0.084 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.637 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.178 ±(99.9%) 0.113 ms/op
Iteration   1: 2.885 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.081 ms/op
                 createUser·p0.50:   2.753 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   4.212 ms/op
                 createUser·p0.99:   5.174 ms/op
                 createUser·p0.999:  8.224 ms/op
                 createUser·p0.9999: 9.678 ms/op
                 createUser·p1.00:   9.683 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11035
  mean =      2.885 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 29 
    [ 1.500,  2.000) = 165 
    [ 2.000,  2.500) = 2458 
    [ 2.500,  3.000) = 5468 
    [ 3.000,  3.500) = 1518 
    [ 3.500,  4.000) = 626 
    [ 4.000,  4.500) = 442 
    [ 4.500,  5.000) = 174 
    [ 5.000,  5.500) = 84 
    [ 5.500,  6.000) = 32 
    [ 6.000,  6.500) = 8 
    [ 6.500,  7.000) = 12 
    [ 7.000,  7.500) = 4 
    [ 7.500,  8.000) = 2 
    [ 8.000,  8.500) = 5 
    [ 8.500,  9.000) = 5 
    [ 9.000,  9.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.081 ms/op
     p(50.0000) =      2.753 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      4.212 ms/op
     p(99.0000) =      5.174 ms/op
     p(99.9000) =      8.224 ms/op
     p(99.9900) =      9.678 ms/op
     p(99.9990) =      9.683 ms/op
     p(99.9999) =      9.683 ms/op
    p(100.0000) =      9.683 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.111 ±(99.9%) 0.080 ms/op
Iteration   1: 1.762 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.681 ms/op
                 existUser·p0.50:   1.673 ms/op
                 existUser·p0.90:   2.212 ms/op
                 existUser·p0.95:   2.373 ms/op
                 existUser·p0.99:   2.936 ms/op
                 existUser·p0.999:  4.383 ms/op
                 existUser·p0.9999: 5.785 ms/op
                 existUser·p1.00:   5.792 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18212
  mean =      1.762 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 44 
    [1.000, 1.500) = 3568 
    [1.500, 2.000) = 10738 
    [2.000, 2.500) = 3237 
    [2.500, 3.000) = 476 
    [3.000, 3.500) = 69 
    [3.500, 4.000) = 10 
    [4.000, 4.500) = 55 
    [4.500, 5.000) = 8 
    [5.000, 5.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.681 ms/op
     p(50.0000) =      1.673 ms/op
     p(90.0000) =      2.212 ms/op
     p(95.0000) =      2.373 ms/op
     p(99.0000) =      2.936 ms/op
     p(99.9000) =      4.383 ms/op
     p(99.9900) =      5.785 ms/op
     p(99.9990) =      5.792 ms/op
     p(99.9999) =      5.792 ms/op
    p(100.0000) =      5.792 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.094 ±(99.9%) 0.098 ms/op
Iteration   1: 3.109 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.948 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   4.166 ms/op
                 getUser·p0.99:   5.218 ms/op
                 getUser·p0.999:  7.690 ms/op
                 getUser·p0.9999: 8.435 ms/op
                 getUser·p1.00:   8.438 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10291
  mean =      3.109 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 2 
    [1.000, 1.500) = 28 
    [1.500, 2.000) = 211 
    [2.000, 2.500) = 1478 
    [2.500, 3.000) = 2832 
    [3.000, 3.500) = 3600 
    [3.500, 4.000) = 1372 
    [4.000, 4.500) = 515 
    [4.500, 5.000) = 117 
    [5.000, 5.500) = 53 
    [5.500, 6.000) = 13 
    [6.000, 6.500) = 7 
    [6.500, 7.000) = 7 
    [7.000, 7.500) = 17 
    [7.500, 8.000) = 36 
    [8.000, 8.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.948 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.166 ms/op
     p(99.0000) =      5.218 ms/op
     p(99.9000) =      7.690 ms/op
     p(99.9900) =      8.435 ms/op
     p(99.9990) =      8.438 ms/op
     p(99.9999) =      8.438 ms/op
    p(100.0000) =      8.438 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 12.312 ±(99.9%) 0.491 ms/op
Iteration   1: 7.557 ±(99.9%) 0.115 ms/op
                 listUser·p0.00:   2.109 ms/op
                 listUser·p0.50:   7.225 ms/op
                 listUser·p0.90:   9.699 ms/op
                 listUser·p0.95:   10.732 ms/op
                 listUser·p0.99:   17.795 ms/op
                 listUser·p0.999:  24.873 ms/op
                 listUser·p0.9999: 26.903 ms/op
                 listUser·p1.00:   26.903 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4376
  mean =      7.557 ±(99.9%) 0.115 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 198 
    [ 5.000,  7.500) = 2345 
    [ 7.500, 10.000) = 1473 
    [10.000, 12.500) = 259 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      2.109 ms/op
     p(50.0000) =      7.225 ms/op
     p(90.0000) =      9.699 ms/op
     p(95.0000) =     10.732 ms/op
     p(99.0000) =     17.795 ms/op
     p(99.9000) =     24.873 ms/op
     p(99.9900) =     26.903 ms/op
     p(99.9990) =     26.903 ms/op
     p(99.9999) =     26.903 ms/op
    p(100.0000) =     26.903 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.721          ops/ms
Client.existUser                       thrpt         12.588          ops/ms
Client.getUser                         thrpt          9.466          ops/ms
Client.listUser                        thrpt          3.764          ops/ms
Client.createUser                       avgt          3.095           ms/op
Client.existUser                        avgt          1.900           ms/op
Client.getUser                          avgt          3.059           ms/op
Client.listUser                         avgt          8.637           ms/op
Client.createUser                     sample  11035   2.885 ± 0.021   ms/op
Client.createUser:createUser·p0.00    sample          1.081           ms/op
Client.createUser:createUser·p0.50    sample          2.753           ms/op
Client.createUser:createUser·p0.90    sample          3.686           ms/op
Client.createUser:createUser·p0.95    sample          4.212           ms/op
Client.createUser:createUser·p0.99    sample          5.174           ms/op
Client.createUser:createUser·p0.999   sample          8.224           ms/op
Client.createUser:createUser·p0.9999  sample          9.678           ms/op
Client.createUser:createUser·p1.00    sample          9.683           ms/op
Client.existUser                      sample  18212   1.762 ± 0.009   ms/op
Client.existUser:existUser·p0.00      sample          0.681           ms/op
Client.existUser:existUser·p0.50      sample          1.673           ms/op
Client.existUser:existUser·p0.90      sample          2.212           ms/op
Client.existUser:existUser·p0.95      sample          2.373           ms/op
Client.existUser:existUser·p0.99      sample          2.936           ms/op
Client.existUser:existUser·p0.999     sample          4.383           ms/op
Client.existUser:existUser·p0.9999    sample          5.785           ms/op
Client.existUser:existUser·p1.00      sample          5.792           ms/op
Client.getUser                        sample  10291   3.109 ± 0.022   ms/op
Client.getUser:getUser·p0.00          sample          0.948           ms/op
Client.getUser:getUser·p0.50          sample          3.080           ms/op
Client.getUser:getUser·p0.90          sample          3.846           ms/op
Client.getUser:getUser·p0.95          sample          4.166           ms/op
Client.getUser:getUser·p0.99          sample          5.218           ms/op
Client.getUser:getUser·p0.999         sample          7.690           ms/op
Client.getUser:getUser·p0.9999        sample          8.435           ms/op
Client.getUser:getUser·p1.00          sample          8.438           ms/op
Client.listUser                       sample   4376   7.557 ± 0.115   ms/op
Client.listUser:listUser·p0.00        sample          2.109           ms/op
Client.listUser:listUser·p0.50        sample          7.225           ms/op
Client.listUser:listUser·p0.90        sample          9.699           ms/op
Client.listUser:listUser·p0.95        sample         10.732           ms/op
Client.listUser:listUser·p0.99        sample         17.795           ms/op
Client.listUser:listUser·p0.999       sample         24.873           ms/op
Client.listUser:listUser·p0.9999      sample         26.903           ms/op
Client.listUser:listUser·p1.00        sample         26.903           ms/op
