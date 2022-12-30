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
# Warmup Iteration   1: 1.163 ops/ms
Iteration   1: 2.543 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.543 ops/ms


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
# Warmup Iteration   1: 3.639 ops/ms
Iteration   1: 6.882 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.882 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 1.920 ops/ms
Iteration   1: 5.293 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.293 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 0.948 ops/ms
Iteration   1: 1.323 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.323 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 14.858 ±(99.9%) 0.196 ms/op
Iteration   1: 6.138 ±(99.9%) 0.037 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.138 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 6.671 ±(99.9%) 0.114 ms/op
Iteration   1: 3.776 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.776 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.692 ±(99.9%) 0.081 ms/op
Iteration   1: 4.654 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.654 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 28.437 ±(99.9%) 0.414 ms/op
Iteration   1: 18.652 ±(99.9%) 0.095 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  18.652 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.948 ±(99.9%) 0.264 ms/op
Iteration   1: 5.985 ±(99.9%) 0.126 ms/op
                 createUser·p0.00:   1.710 ms/op
                 createUser·p0.50:   5.726 ms/op
                 createUser·p0.90:   8.765 ms/op
                 createUser·p0.95:   12.435 ms/op
                 createUser·p0.99:   17.334 ms/op
                 createUser·p0.999:  20.418 ms/op
                 createUser·p0.9999: 21.234 ms/op
                 createUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5391
  mean =      5.985 ±(99.9%) 0.126 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 491 
    [ 2.500,  5.000) = 721 
    [ 5.000,  7.500) = 3422 
    [ 7.500, 10.000) = 323 
    [10.000, 12.500) = 183 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.710 ms/op
     p(50.0000) =      5.726 ms/op
     p(90.0000) =      8.765 ms/op
     p(95.0000) =     12.435 ms/op
     p(99.0000) =     17.334 ms/op
     p(99.9000) =     20.418 ms/op
     p(99.9900) =     21.234 ms/op
     p(99.9990) =     21.234 ms/op
     p(99.9999) =     21.234 ms/op
    p(100.0000) =     21.234 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 5.358 ±(99.9%) 0.155 ms/op
Iteration   1: 2.850 ±(99.9%) 0.038 ms/op
                 existUser·p0.00:   0.502 ms/op
                 existUser·p0.50:   2.712 ms/op
                 existUser·p0.90:   3.815 ms/op
                 existUser·p0.95:   4.506 ms/op
                 existUser·p0.99:   8.815 ms/op
                 existUser·p0.999:  13.457 ms/op
                 existUser·p0.9999: 14.826 ms/op
                 existUser·p1.00:   14.828 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 11224
  mean =      2.850 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 299 
    [ 1.250,  2.500) = 2859 
    [ 2.500,  3.750) = 6893 
    [ 3.750,  5.000) = 781 
    [ 5.000,  6.250) = 145 
    [ 6.250,  7.500) = 58 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 104 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.502 ms/op
     p(50.0000) =      2.712 ms/op
     p(90.0000) =      3.815 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      8.815 ms/op
     p(99.9000) =     13.457 ms/op
     p(99.9900) =     14.826 ms/op
     p(99.9990) =     14.828 ms/op
     p(99.9999) =     14.828 ms/op
    p(100.0000) =     14.828 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 7.052 ±(99.9%) 0.229 ms/op
Iteration   1: 4.268 ±(99.9%) 0.035 ms/op
                 getUser·p0.00:   1.960 ms/op
                 getUser·p0.50:   4.121 ms/op
                 getUser·p0.90:   5.022 ms/op
                 getUser·p0.95:   5.317 ms/op
                 getUser·p0.99:   7.945 ms/op
                 getUser·p0.999:  14.025 ms/op
                 getUser·p0.9999: 14.582 ms/op
                 getUser·p1.00:   14.582 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7601
  mean =      4.268 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 25 
    [ 2.500,  3.750) = 1706 
    [ 3.750,  5.000) = 5079 
    [ 5.000,  6.250) = 684 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 15 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.960 ms/op
     p(50.0000) =      4.121 ms/op
     p(90.0000) =      5.022 ms/op
     p(95.0000) =      5.317 ms/op
     p(99.0000) =      7.945 ms/op
     p(99.9000) =     14.025 ms/op
     p(99.9900) =     14.582 ms/op
     p(99.9990) =     14.582 ms/op
     p(99.9999) =     14.582 ms/op
    p(100.0000) =     14.582 ms/op


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
# Warmup Iteration   1: 24.560 ±(99.9%) 0.615 ms/op
Iteration   1: 15.517 ±(99.9%) 0.226 ms/op
                 listUser·p0.00:   5.472 ms/op
                 listUser·p0.50:   14.942 ms/op
                 listUser·p0.90:   18.252 ms/op
                 listUser·p0.95:   21.725 ms/op
                 listUser·p0.99:   29.635 ms/op
                 listUser·p0.999:  32.912 ms/op
                 listUser·p0.9999: 33.489 ms/op
                 listUser·p1.00:   33.489 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2059
  mean =     15.517 ±(99.9%) 0.226 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 18 
    [ 7.500, 10.000) = 9 
    [10.000, 12.500) = 21 
    [12.500, 15.000) = 1048 
    [15.000, 17.500) = 750 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      5.472 ms/op
     p(50.0000) =     14.942 ms/op
     p(90.0000) =     18.252 ms/op
     p(95.0000) =     21.725 ms/op
     p(99.0000) =     29.635 ms/op
     p(99.9000) =     32.912 ms/op
     p(99.9900) =     33.489 ms/op
     p(99.9990) =     33.489 ms/op
     p(99.9999) =     33.489 ms/op
    p(100.0000) =     33.489 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          2.543          ops/ms
Client.existUser                       thrpt          6.882          ops/ms
Client.getUser                         thrpt          5.293          ops/ms
Client.listUser                        thrpt          1.323          ops/ms
Client.createUser                       avgt          6.138           ms/op
Client.existUser                        avgt          3.776           ms/op
Client.getUser                          avgt          4.654           ms/op
Client.listUser                         avgt         18.652           ms/op
Client.createUser                     sample   5391   5.985 ± 0.126   ms/op
Client.createUser:createUser·p0.00    sample          1.710           ms/op
Client.createUser:createUser·p0.50    sample          5.726           ms/op
Client.createUser:createUser·p0.90    sample          8.765           ms/op
Client.createUser:createUser·p0.95    sample         12.435           ms/op
Client.createUser:createUser·p0.99    sample         17.334           ms/op
Client.createUser:createUser·p0.999   sample         20.418           ms/op
Client.createUser:createUser·p0.9999  sample         21.234           ms/op
Client.createUser:createUser·p1.00    sample         21.234           ms/op
Client.existUser                      sample  11224   2.850 ± 0.038   ms/op
Client.existUser:existUser·p0.00      sample          0.502           ms/op
Client.existUser:existUser·p0.50      sample          2.712           ms/op
Client.existUser:existUser·p0.90      sample          3.815           ms/op
Client.existUser:existUser·p0.95      sample          4.506           ms/op
Client.existUser:existUser·p0.99      sample          8.815           ms/op
Client.existUser:existUser·p0.999     sample         13.457           ms/op
Client.existUser:existUser·p0.9999    sample         14.826           ms/op
Client.existUser:existUser·p1.00      sample         14.828           ms/op
Client.getUser                        sample   7601   4.268 ± 0.035   ms/op
Client.getUser:getUser·p0.00          sample          1.960           ms/op
Client.getUser:getUser·p0.50          sample          4.121           ms/op
Client.getUser:getUser·p0.90          sample          5.022           ms/op
Client.getUser:getUser·p0.95          sample          5.317           ms/op
Client.getUser:getUser·p0.99          sample          7.945           ms/op
Client.getUser:getUser·p0.999         sample         14.025           ms/op
Client.getUser:getUser·p0.9999        sample         14.582           ms/op
Client.getUser:getUser·p1.00          sample         14.582           ms/op
Client.listUser                       sample   2059  15.517 ± 0.226   ms/op
Client.listUser:listUser·p0.00        sample          5.472           ms/op
Client.listUser:listUser·p0.50        sample         14.942           ms/op
Client.listUser:listUser·p0.90        sample         18.252           ms/op
Client.listUser:listUser·p0.95        sample         21.725           ms/op
Client.listUser:listUser·p0.99        sample         29.635           ms/op
Client.listUser:listUser·p0.999       sample         32.912           ms/op
Client.listUser:listUser·p0.9999      sample         33.489           ms/op
Client.listUser:listUser·p1.00        sample         33.489           ms/op
