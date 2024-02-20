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
# Warmup Iteration   1: 2.376 ops/ms
Iteration   1: 5.646 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.646 ops/ms


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
# Warmup Iteration   1: 6.325 ops/ms
Iteration   1: 12.382 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.382 ops/ms


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
# Warmup Iteration   1: 3.999 ops/ms
Iteration   1: 8.345 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.345 ops/ms


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
# Warmup Iteration   1: 2.157 ops/ms
Iteration   1: 3.291 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.291 ops/ms


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
# Warmup Iteration   1: 5.613 ±(99.9%) 0.075 ms/op
Iteration   1: 3.175 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.175 ms/op


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
# Warmup Iteration   1: 3.130 ±(99.9%) 0.029 ms/op
Iteration   1: 1.953 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.953 ms/op


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
# Warmup Iteration   1: 5.221 ±(99.9%) 0.055 ms/op
Iteration   1: 2.954 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.954 ms/op


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
# Warmup Iteration   1: 12.135 ±(99.9%) 0.199 ms/op
Iteration   1: 8.713 ±(99.9%) 0.122 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.713 ms/op


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
# Warmup Iteration   1: 5.101 ±(99.9%) 0.110 ms/op
Iteration   1: 2.978 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   1.303 ms/op
                 createUser·p0.50:   2.707 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   4.342 ms/op
                 createUser·p0.99:   9.863 ms/op
                 createUser·p0.999:  13.730 ms/op
                 createUser·p0.9999: 13.810 ms/op
                 createUser·p1.00:   13.812 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10739
  mean =      2.978 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 2328 
    [ 2.500,  3.750) = 7339 
    [ 3.750,  5.000) = 763 
    [ 5.000,  6.250) = 149 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 51 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.303 ms/op
     p(50.0000) =      2.707 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      9.863 ms/op
     p(99.9000) =     13.730 ms/op
     p(99.9900) =     13.810 ms/op
     p(99.9990) =     13.812 ms/op
     p(99.9999) =     13.812 ms/op
    p(100.0000) =     13.812 ms/op


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
# Warmup Iteration   1: 3.019 ±(99.9%) 0.079 ms/op
Iteration   1: 1.898 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.509 ms/op
                 existUser·p0.50:   1.806 ms/op
                 existUser·p0.90:   2.437 ms/op
                 existUser·p0.95:   2.621 ms/op
                 existUser·p0.99:   3.453 ms/op
                 existUser·p0.999:  8.266 ms/op
                 existUser·p0.9999: 8.487 ms/op
                 existUser·p1.00:   8.487 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16998
  mean =      1.898 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 83 
    [1.000, 1.500) = 2757 
    [1.500, 2.000) = 8583 
    [2.000, 2.500) = 4210 
    [2.500, 3.000) = 1082 
    [3.000, 3.500) = 130 
    [3.500, 4.000) = 25 
    [4.000, 4.500) = 16 
    [4.500, 5.000) = 31 
    [5.000, 5.500) = 8 
    [5.500, 6.000) = 37 
    [6.000, 6.500) = 4 
    [6.500, 7.000) = 0 
    [7.000, 7.500) = 0 
    [7.500, 8.000) = 0 
    [8.000, 8.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.509 ms/op
     p(50.0000) =      1.806 ms/op
     p(90.0000) =      2.437 ms/op
     p(95.0000) =      2.621 ms/op
     p(99.0000) =      3.453 ms/op
     p(99.9000) =      8.266 ms/op
     p(99.9900) =      8.487 ms/op
     p(99.9990) =      8.487 ms/op
     p(99.9999) =      8.487 ms/op
    p(100.0000) =      8.487 ms/op


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
# Warmup Iteration   1: 4.707 ±(99.9%) 0.118 ms/op
Iteration   1: 3.109 ±(99.9%) 0.031 ms/op
                 getUser·p0.00:   0.787 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.887 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   6.278 ms/op
                 getUser·p0.999:  14.565 ms/op
                 getUser·p0.9999: 15.335 ms/op
                 getUser·p1.00:   15.352 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10282
  mean =      3.109 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 2266 
    [ 2.500,  3.750) = 6579 
    [ 3.750,  5.000) = 1255 
    [ 5.000,  6.250) = 71 
    [ 6.250,  7.500) = 69 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.787 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      6.278 ms/op
     p(99.9000) =     14.565 ms/op
     p(99.9900) =     15.335 ms/op
     p(99.9990) =     15.352 ms/op
     p(99.9999) =     15.352 ms/op
    p(100.0000) =     15.352 ms/op


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
# Warmup Iteration   1: 12.249 ±(99.9%) 0.410 ms/op
Iteration   1: 9.328 ±(99.9%) 0.140 ms/op
                 listUser·p0.00:   3.326 ms/op
                 listUser·p0.50:   9.224 ms/op
                 listUser·p0.90:   12.239 ms/op
                 listUser·p0.95:   13.107 ms/op
                 listUser·p0.99:   16.719 ms/op
                 listUser·p0.999:  20.979 ms/op
                 listUser·p0.9999: 24.183 ms/op
                 listUser·p1.00:   24.183 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3417
  mean =      9.328 ±(99.9%) 0.140 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 55 
    [ 5.000,  7.500) = 826 
    [ 7.500, 10.000) = 1241 
    [10.000, 12.500) = 1002 
    [12.500, 15.000) = 199 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.326 ms/op
     p(50.0000) =      9.224 ms/op
     p(90.0000) =     12.239 ms/op
     p(95.0000) =     13.107 ms/op
     p(99.0000) =     16.719 ms/op
     p(99.9000) =     20.979 ms/op
     p(99.9900) =     24.183 ms/op
     p(99.9990) =     24.183 ms/op
     p(99.9999) =     24.183 ms/op
    p(100.0000) =     24.183 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.646          ops/ms
Client.existUser                       thrpt         12.382          ops/ms
Client.getUser                         thrpt          8.345          ops/ms
Client.listUser                        thrpt          3.291          ops/ms
Client.createUser                       avgt          3.175           ms/op
Client.existUser                        avgt          1.953           ms/op
Client.getUser                          avgt          2.954           ms/op
Client.listUser                         avgt          8.713           ms/op
Client.createUser                     sample  10739   2.978 ± 0.036   ms/op
Client.createUser:createUser·p0.00    sample          1.303           ms/op
Client.createUser:createUser·p0.50    sample          2.707           ms/op
Client.createUser:createUser·p0.90    sample          3.748           ms/op
Client.createUser:createUser·p0.95    sample          4.342           ms/op
Client.createUser:createUser·p0.99    sample          9.863           ms/op
Client.createUser:createUser·p0.999   sample         13.730           ms/op
Client.createUser:createUser·p0.9999  sample         13.810           ms/op
Client.createUser:createUser·p1.00    sample         13.812           ms/op
Client.existUser                      sample  16998   1.898 ± 0.014   ms/op
Client.existUser:existUser·p0.00      sample          0.509           ms/op
Client.existUser:existUser·p0.50      sample          1.806           ms/op
Client.existUser:existUser·p0.90      sample          2.437           ms/op
Client.existUser:existUser·p0.95      sample          2.621           ms/op
Client.existUser:existUser·p0.99      sample          3.453           ms/op
Client.existUser:existUser·p0.999     sample          8.266           ms/op
Client.existUser:existUser·p0.9999    sample          8.487           ms/op
Client.existUser:existUser·p1.00      sample          8.487           ms/op
Client.getUser                        sample  10282   3.109 ± 0.031   ms/op
Client.getUser:getUser·p0.00          sample          0.787           ms/op
Client.getUser:getUser·p0.50          sample          3.076           ms/op
Client.getUser:getUser·p0.90          sample          3.887           ms/op
Client.getUser:getUser·p0.95          sample          4.194           ms/op
Client.getUser:getUser·p0.99          sample          6.278           ms/op
Client.getUser:getUser·p0.999         sample         14.565           ms/op
Client.getUser:getUser·p0.9999        sample         15.335           ms/op
Client.getUser:getUser·p1.00          sample         15.352           ms/op
Client.listUser                       sample   3417   9.328 ± 0.140   ms/op
Client.listUser:listUser·p0.00        sample          3.326           ms/op
Client.listUser:listUser·p0.50        sample          9.224           ms/op
Client.listUser:listUser·p0.90        sample         12.239           ms/op
Client.listUser:listUser·p0.95        sample         13.107           ms/op
Client.listUser:listUser·p0.99        sample         16.719           ms/op
Client.listUser:listUser·p0.999       sample         20.979           ms/op
Client.listUser:listUser·p0.9999      sample         24.183           ms/op
Client.listUser:listUser·p1.00        sample         24.183           ms/op
