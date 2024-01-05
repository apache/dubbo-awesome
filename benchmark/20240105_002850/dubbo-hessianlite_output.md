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
# Warmup Iteration   1: 2.056 ops/ms
Iteration   1: 6.315 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.315 ops/ms


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
# Warmup Iteration   1: 5.465 ops/ms
Iteration   1: 11.788 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.788 ops/ms


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
# Warmup Iteration   1: 3.850 ops/ms
Iteration   1: 9.079 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.079 ops/ms


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
# Warmup Iteration   1: 2.045 ops/ms
Iteration   1: 3.380 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.380 ops/ms


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
# Warmup Iteration   1: 5.934 ±(99.9%) 0.067 ms/op
Iteration   1: 3.735 ±(99.9%) 0.050 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.735 ms/op


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
# Warmup Iteration   1: 3.768 ±(99.9%) 0.039 ms/op
Iteration   1: 2.103 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.103 ms/op


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
# Warmup Iteration   1: 5.296 ±(99.9%) 0.088 ms/op
Iteration   1: 3.256 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.256 ms/op


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
# Warmup Iteration   1: 13.563 ±(99.9%) 0.231 ms/op
Iteration   1: 8.560 ±(99.9%) 0.066 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.560 ms/op


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
# Warmup Iteration   1: 5.765 ±(99.9%) 0.144 ms/op
Iteration   1: 3.004 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   0.956 ms/op
                 createUser·p0.50:   2.867 ms/op
                 createUser·p0.90:   3.740 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   5.319 ms/op
                 createUser·p0.999:  7.398 ms/op
                 createUser·p0.9999: 8.913 ms/op
                 createUser·p1.00:   8.913 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10634
  mean =      3.004 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 4 
    [1.000, 1.500) = 30 
    [1.500, 2.000) = 61 
    [2.000, 2.500) = 1948 
    [2.500, 3.000) = 4354 
    [3.000, 3.500) = 2509 
    [3.500, 4.000) = 983 
    [4.000, 4.500) = 385 
    [4.500, 5.000) = 183 
    [5.000, 5.500) = 94 
    [5.500, 6.000) = 35 
    [6.000, 6.500) = 9 
    [6.500, 7.000) = 5 
    [7.000, 7.500) = 25 
    [7.500, 8.000) = 7 
    [8.000, 8.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.956 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      5.319 ms/op
     p(99.9000) =      7.398 ms/op
     p(99.9900) =      8.913 ms/op
     p(99.9990) =      8.913 ms/op
     p(99.9999) =      8.913 ms/op
    p(100.0000) =      8.913 ms/op


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
# Warmup Iteration   1: 3.332 ±(99.9%) 0.097 ms/op
Iteration   1: 2.027 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.502 ms/op
                 existUser·p0.50:   1.901 ms/op
                 existUser·p0.90:   2.707 ms/op
                 existUser·p0.95:   3.015 ms/op
                 existUser·p0.99:   5.079 ms/op
                 existUser·p0.999:  7.250 ms/op
                 existUser·p0.9999: 8.009 ms/op
                 existUser·p1.00:   8.086 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15841
  mean =      2.027 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 15 
    [1.000, 1.500) = 1544 
    [1.500, 2.000) = 8078 
    [2.000, 2.500) = 4082 
    [2.500, 3.000) = 1305 
    [3.000, 3.500) = 507 
    [3.500, 4.000) = 47 
    [4.000, 4.500) = 43 
    [4.500, 5.000) = 45 
    [5.000, 5.500) = 61 
    [5.500, 6.000) = 67 
    [6.000, 6.500) = 13 
    [6.500, 7.000) = 8 
    [7.000, 7.500) = 20 
    [7.500, 8.000) = 5 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.502 ms/op
     p(50.0000) =      1.901 ms/op
     p(90.0000) =      2.707 ms/op
     p(95.0000) =      3.015 ms/op
     p(99.0000) =      5.079 ms/op
     p(99.9000) =      7.250 ms/op
     p(99.9900) =      8.009 ms/op
     p(99.9990) =      8.086 ms/op
     p(99.9999) =      8.086 ms/op
    p(100.0000) =      8.086 ms/op


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
# Warmup Iteration   1: 5.239 ±(99.9%) 0.150 ms/op
Iteration   1: 3.369 ±(99.9%) 0.045 ms/op
                 getUser·p0.00:   1.163 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   4.202 ms/op
                 getUser·p0.95:   4.899 ms/op
                 getUser·p0.99:   8.520 ms/op
                 getUser·p0.999:  19.645 ms/op
                 getUser·p0.9999: 20.742 ms/op
                 getUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9487
  mean =      3.369 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 742 
    [ 2.500,  5.000) = 8327 
    [ 5.000,  7.500) = 311 
    [ 7.500, 10.000) = 44 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.163 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.899 ms/op
     p(99.0000) =      8.520 ms/op
     p(99.9000) =     19.645 ms/op
     p(99.9900) =     20.742 ms/op
     p(99.9990) =     20.742 ms/op
     p(99.9999) =     20.742 ms/op
    p(100.0000) =     20.742 ms/op


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
# Warmup Iteration   1: 14.113 ±(99.9%) 0.571 ms/op
Iteration   1: 9.479 ±(99.9%) 0.184 ms/op
                 listUser·p0.00:   3.592 ms/op
                 listUser·p0.50:   8.733 ms/op
                 listUser·p0.90:   12.596 ms/op
                 listUser·p0.95:   14.713 ms/op
                 listUser·p0.99:   24.179 ms/op
                 listUser·p0.999:  29.046 ms/op
                 listUser·p0.9999: 31.883 ms/op
                 listUser·p1.00:   31.883 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3411
  mean =      9.479 ±(99.9%) 0.184 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 23 
    [ 5.000,  7.500) = 777 
    [ 7.500, 10.000) = 1588 
    [10.000, 12.500) = 668 
    [12.500, 15.000) = 197 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 17 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.592 ms/op
     p(50.0000) =      8.733 ms/op
     p(90.0000) =     12.596 ms/op
     p(95.0000) =     14.713 ms/op
     p(99.0000) =     24.179 ms/op
     p(99.9000) =     29.046 ms/op
     p(99.9900) =     31.883 ms/op
     p(99.9990) =     31.883 ms/op
     p(99.9999) =     31.883 ms/op
    p(100.0000) =     31.883 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.315          ops/ms
Client.existUser                       thrpt         11.788          ops/ms
Client.getUser                         thrpt          9.079          ops/ms
Client.listUser                        thrpt          3.380          ops/ms
Client.createUser                       avgt          3.735           ms/op
Client.existUser                        avgt          2.103           ms/op
Client.getUser                          avgt          3.256           ms/op
Client.listUser                         avgt          8.560           ms/op
Client.createUser                     sample  10634   3.004 ± 0.021   ms/op
Client.createUser:createUser·p0.00    sample          0.956           ms/op
Client.createUser:createUser·p0.50    sample          2.867           ms/op
Client.createUser:createUser·p0.90    sample          3.740           ms/op
Client.createUser:createUser·p0.95    sample          4.260           ms/op
Client.createUser:createUser·p0.99    sample          5.319           ms/op
Client.createUser:createUser·p0.999   sample          7.398           ms/op
Client.createUser:createUser·p0.9999  sample          8.913           ms/op
Client.createUser:createUser·p1.00    sample          8.913           ms/op
Client.existUser                      sample  15841   2.027 ± 0.016   ms/op
Client.existUser:existUser·p0.00      sample          0.502           ms/op
Client.existUser:existUser·p0.50      sample          1.901           ms/op
Client.existUser:existUser·p0.90      sample          2.707           ms/op
Client.existUser:existUser·p0.95      sample          3.015           ms/op
Client.existUser:existUser·p0.99      sample          5.079           ms/op
Client.existUser:existUser·p0.999     sample          7.250           ms/op
Client.existUser:existUser·p0.9999    sample          8.009           ms/op
Client.existUser:existUser·p1.00      sample          8.086           ms/op
Client.getUser                        sample   9487   3.369 ± 0.045   ms/op
Client.getUser:getUser·p0.00          sample          1.163           ms/op
Client.getUser:getUser·p0.50          sample          3.113           ms/op
Client.getUser:getUser·p0.90          sample          4.202           ms/op
Client.getUser:getUser·p0.95          sample          4.899           ms/op
Client.getUser:getUser·p0.99          sample          8.520           ms/op
Client.getUser:getUser·p0.999         sample         19.645           ms/op
Client.getUser:getUser·p0.9999        sample         20.742           ms/op
Client.getUser:getUser·p1.00          sample         20.742           ms/op
Client.listUser                       sample   3411   9.479 ± 0.184   ms/op
Client.listUser:listUser·p0.00        sample          3.592           ms/op
Client.listUser:listUser·p0.50        sample          8.733           ms/op
Client.listUser:listUser·p0.90        sample         12.596           ms/op
Client.listUser:listUser·p0.95        sample         14.713           ms/op
Client.listUser:listUser·p0.99        sample         24.179           ms/op
Client.listUser:listUser·p0.999       sample         29.046           ms/op
Client.listUser:listUser·p0.9999      sample         31.883           ms/op
Client.listUser:listUser·p1.00        sample         31.883           ms/op
