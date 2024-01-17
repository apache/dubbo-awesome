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
# Warmup Iteration   1: 1.906 ops/ms
Iteration   1: 5.566 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.566 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.697 ops/ms
Iteration   1: 12.263 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.263 ops/ms


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
# Warmup Iteration   1: 4.295 ops/ms
Iteration   1: 7.580 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.580 ops/ms


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
# Warmup Iteration   1: 2.016 ops/ms
Iteration   1: 3.486 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.486 ops/ms


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
# Warmup Iteration   1: 5.970 ±(99.9%) 0.095 ms/op
Iteration   1: 3.262 ±(99.9%) 0.032 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.262 ms/op


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
# Warmup Iteration   1: 3.220 ±(99.9%) 0.028 ms/op
Iteration   1: 2.156 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.156 ms/op


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
# Warmup Iteration   1: 4.966 ±(99.9%) 0.067 ms/op
Iteration   1: 3.050 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.050 ms/op


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
# Warmup Iteration   1: 11.641 ±(99.9%) 0.217 ms/op
Iteration   1: 8.101 ±(99.9%) 0.088 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.101 ms/op


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
# Warmup Iteration   1: 5.499 ±(99.9%) 0.140 ms/op
Iteration   1: 3.326 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   1.114 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   4.227 ms/op
                 createUser·p0.95:   4.760 ms/op
                 createUser·p0.99:   8.946 ms/op
                 createUser·p0.999:  11.524 ms/op
                 createUser·p0.9999: 11.862 ms/op
                 createUser·p1.00:   11.862 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9601
  mean =      3.326 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 477 
    [ 2.500,  3.750) = 7412 
    [ 3.750,  5.000) = 1317 
    [ 5.000,  6.250) = 123 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 93 
    [ 8.750, 10.000) = 77 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.114 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      8.946 ms/op
     p(99.9000) =     11.524 ms/op
     p(99.9900) =     11.862 ms/op
     p(99.9990) =     11.862 ms/op
     p(99.9999) =     11.862 ms/op
    p(100.0000) =     11.862 ms/op


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
# Warmup Iteration   1: 3.356 ±(99.9%) 0.075 ms/op
Iteration   1: 1.791 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.758 ms/op
                 existUser·p0.50:   1.753 ms/op
                 existUser·p0.90:   2.281 ms/op
                 existUser·p0.95:   2.454 ms/op
                 existUser·p0.99:   2.986 ms/op
                 existUser·p0.999:  4.910 ms/op
                 existUser·p0.9999: 7.920 ms/op
                 existUser·p1.00:   7.946 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18134
  mean =      1.791 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 74 
    [1.000, 1.500) = 4643 
    [1.500, 2.000) = 8669 
    [2.000, 2.500) = 4000 
    [2.500, 3.000) = 570 
    [3.000, 3.500) = 68 
    [3.500, 4.000) = 82 
    [4.000, 4.500) = 9 
    [4.500, 5.000) = 2 
    [5.000, 5.500) = 0 
    [5.500, 6.000) = 1 
    [6.000, 6.500) = 4 
    [6.500, 7.000) = 8 
    [7.000, 7.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.758 ms/op
     p(50.0000) =      1.753 ms/op
     p(90.0000) =      2.281 ms/op
     p(95.0000) =      2.454 ms/op
     p(99.0000) =      2.986 ms/op
     p(99.9000) =      4.910 ms/op
     p(99.9900) =      7.920 ms/op
     p(99.9990) =      7.946 ms/op
     p(99.9999) =      7.946 ms/op
    p(100.0000) =      7.946 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.591 ±(99.9%) 0.109 ms/op
Iteration   1: 2.949 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.950 ms/op
                 getUser·p0.50:   2.810 ms/op
                 getUser·p0.90:   3.899 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   6.414 ms/op
                 getUser·p0.999:  7.692 ms/op
                 getUser·p0.9999: 7.964 ms/op
                 getUser·p1.00:   7.979 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10857
  mean =      2.949 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 1 
    [1.000, 1.500) = 39 
    [1.500, 2.000) = 797 
    [2.000, 2.500) = 2711 
    [2.500, 3.000) = 2972 
    [3.000, 3.500) = 2059 
    [3.500, 4.000) = 1343 
    [4.000, 4.500) = 538 
    [4.500, 5.000) = 125 
    [5.000, 5.500) = 41 
    [5.500, 6.000) = 78 
    [6.000, 6.500) = 71 
    [6.500, 7.000) = 44 
    [7.000, 7.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.950 ms/op
     p(50.0000) =      2.810 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      6.414 ms/op
     p(99.9000) =      7.692 ms/op
     p(99.9900) =      7.964 ms/op
     p(99.9990) =      7.979 ms/op
     p(99.9999) =      7.979 ms/op
    p(100.0000) =      7.979 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 12.130 ±(99.9%) 0.439 ms/op
Iteration   1: 8.554 ±(99.9%) 0.137 ms/op
                 listUser·p0.00:   1.733 ms/op
                 listUser·p0.50:   8.315 ms/op
                 listUser·p0.90:   11.174 ms/op
                 listUser·p0.95:   12.075 ms/op
                 listUser·p0.99:   17.831 ms/op
                 listUser·p0.999:  26.043 ms/op
                 listUser·p0.9999: 32.899 ms/op
                 listUser·p1.00:   32.899 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3747
  mean =      8.554 ±(99.9%) 0.137 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 137 
    [ 5.000,  7.500) = 1030 
    [ 7.500, 10.000) = 1799 
    [10.000, 12.500) = 635 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.733 ms/op
     p(50.0000) =      8.315 ms/op
     p(90.0000) =     11.174 ms/op
     p(95.0000) =     12.075 ms/op
     p(99.0000) =     17.831 ms/op
     p(99.9000) =     26.043 ms/op
     p(99.9900) =     32.899 ms/op
     p(99.9990) =     32.899 ms/op
     p(99.9999) =     32.899 ms/op
    p(100.0000) =     32.899 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.566          ops/ms
Client.existUser                       thrpt         12.263          ops/ms
Client.getUser                         thrpt          7.580          ops/ms
Client.listUser                        thrpt          3.486          ops/ms
Client.createUser                       avgt          3.262           ms/op
Client.existUser                        avgt          2.156           ms/op
Client.getUser                          avgt          3.050           ms/op
Client.listUser                         avgt          8.101           ms/op
Client.createUser                     sample   9601   3.326 ± 0.038   ms/op
Client.createUser:createUser·p0.00    sample          1.114           ms/op
Client.createUser:createUser·p0.50    sample          3.019           ms/op
Client.createUser:createUser·p0.90    sample          4.227           ms/op
Client.createUser:createUser·p0.95    sample          4.760           ms/op
Client.createUser:createUser·p0.99    sample          8.946           ms/op
Client.createUser:createUser·p0.999   sample         11.524           ms/op
Client.createUser:createUser·p0.9999  sample         11.862           ms/op
Client.createUser:createUser·p1.00    sample         11.862           ms/op
Client.existUser                      sample  18134   1.791 ± 0.011   ms/op
Client.existUser:existUser·p0.00      sample          0.758           ms/op
Client.existUser:existUser·p0.50      sample          1.753           ms/op
Client.existUser:existUser·p0.90      sample          2.281           ms/op
Client.existUser:existUser·p0.95      sample          2.454           ms/op
Client.existUser:existUser·p0.99      sample          2.986           ms/op
Client.existUser:existUser·p0.999     sample          4.910           ms/op
Client.existUser:existUser·p0.9999    sample          7.920           ms/op
Client.existUser:existUser·p1.00      sample          7.946           ms/op
Client.getUser                        sample  10857   2.949 ± 0.027   ms/op
Client.getUser:getUser·p0.00          sample          0.950           ms/op
Client.getUser:getUser·p0.50          sample          2.810           ms/op
Client.getUser:getUser·p0.90          sample          3.899           ms/op
Client.getUser:getUser·p0.95          sample          4.284           ms/op
Client.getUser:getUser·p0.99          sample          6.414           ms/op
Client.getUser:getUser·p0.999         sample          7.692           ms/op
Client.getUser:getUser·p0.9999        sample          7.964           ms/op
Client.getUser:getUser·p1.00          sample          7.979           ms/op
Client.listUser                       sample   3747   8.554 ± 0.137   ms/op
Client.listUser:listUser·p0.00        sample          1.733           ms/op
Client.listUser:listUser·p0.50        sample          8.315           ms/op
Client.listUser:listUser·p0.90        sample         11.174           ms/op
Client.listUser:listUser·p0.95        sample         12.075           ms/op
Client.listUser:listUser·p0.99        sample         17.831           ms/op
Client.listUser:listUser·p0.999       sample         26.043           ms/op
Client.listUser:listUser·p0.9999      sample         32.899           ms/op
Client.listUser:listUser·p1.00        sample         32.899           ms/op
