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
# Warmup Iteration   1: 2.245 ops/ms
Iteration   1: 6.365 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.365 ops/ms


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
# Warmup Iteration   1: 5.776 ops/ms
Iteration   1: 11.111 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.111 ops/ms


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
# Warmup Iteration   1: 4.196 ops/ms
Iteration   1: 8.959 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.959 ops/ms


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
# Warmup Iteration   1: 1.883 ops/ms
Iteration   1: 3.345 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.345 ops/ms


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
# Warmup Iteration   1: 5.786 ±(99.9%) 0.134 ms/op
Iteration   1: 3.150 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.150 ms/op


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
# Warmup Iteration   1: 3.195 ±(99.9%) 0.042 ms/op
Iteration   1: 1.939 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.939 ms/op


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
# Warmup Iteration   1: 4.851 ±(99.9%) 0.064 ms/op
Iteration   1: 3.254 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.254 ms/op


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
# Warmup Iteration   1: 13.808 ±(99.9%) 0.283 ms/op
Iteration   1: 9.256 ±(99.9%) 0.158 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.256 ms/op


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
# Warmup Iteration   1: 5.463 ±(99.9%) 0.169 ms/op
Iteration   1: 3.042 ±(99.9%) 0.042 ms/op
                 createUser·p0.00:   1.231 ms/op
                 createUser·p0.50:   2.775 ms/op
                 createUser·p0.90:   3.949 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   9.978 ms/op
                 createUser·p0.999:  15.417 ms/op
                 createUser·p0.9999: 16.200 ms/op
                 createUser·p1.00:   16.204 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10540
  mean =      3.042 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 2875 
    [ 2.500,  3.750) = 6246 
    [ 3.750,  5.000) = 1155 
    [ 5.000,  6.250) = 70 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 15 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 36 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.231 ms/op
     p(50.0000) =      2.775 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      9.978 ms/op
     p(99.9000) =     15.417 ms/op
     p(99.9900) =     16.200 ms/op
     p(99.9990) =     16.204 ms/op
     p(99.9999) =     16.204 ms/op
    p(100.0000) =     16.204 ms/op


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
# Warmup Iteration   1: 3.050 ±(99.9%) 0.077 ms/op
Iteration   1: 1.824 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.591 ms/op
                 existUser·p0.50:   1.741 ms/op
                 existUser·p0.90:   2.191 ms/op
                 existUser·p0.95:   2.415 ms/op
                 existUser·p0.99:   3.657 ms/op
                 existUser·p0.999:  12.911 ms/op
                 existUser·p0.9999: 14.094 ms/op
                 existUser·p1.00:   14.205 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17528
  mean =      1.824 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 881 
    [ 1.250,  2.500) = 15944 
    [ 2.500,  3.750) = 544 
    [ 3.750,  5.000) = 33 
    [ 5.000,  6.250) = 50 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.591 ms/op
     p(50.0000) =      1.741 ms/op
     p(90.0000) =      2.191 ms/op
     p(95.0000) =      2.415 ms/op
     p(99.0000) =      3.657 ms/op
     p(99.9000) =     12.911 ms/op
     p(99.9900) =     14.094 ms/op
     p(99.9990) =     14.205 ms/op
     p(99.9999) =     14.205 ms/op
    p(100.0000) =     14.205 ms/op


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
# Warmup Iteration   1: 4.857 ±(99.9%) 0.110 ms/op
Iteration   1: 3.056 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.993 ms/op
                 getUser·p0.50:   2.937 ms/op
                 getUser·p0.90:   4.014 ms/op
                 getUser·p0.95:   4.260 ms/op
                 getUser·p0.99:   5.032 ms/op
                 getUser·p0.999:  6.248 ms/op
                 getUser·p0.9999: 10.141 ms/op
                 getUser·p1.00:   10.191 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10472
  mean =      3.056 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 1 
    [ 1.000,  2.000) = 444 
    [ 2.000,  3.000) = 5075 
    [ 3.000,  4.000) = 3865 
    [ 4.000,  5.000) = 974 
    [ 5.000,  6.000) = 98 
    [ 6.000,  7.000) = 10 
    [ 7.000,  8.000) = 0 
    [ 8.000,  9.000) = 3 
    [ 9.000, 10.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.993 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      4.014 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      5.032 ms/op
     p(99.9000) =      6.248 ms/op
     p(99.9900) =     10.141 ms/op
     p(99.9990) =     10.191 ms/op
     p(99.9999) =     10.191 ms/op
    p(100.0000) =     10.191 ms/op


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
# Warmup Iteration   1: 13.219 ±(99.9%) 0.451 ms/op
Iteration   1: 8.748 ±(99.9%) 0.122 ms/op
                 listUser·p0.00:   2.748 ms/op
                 listUser·p0.50:   8.471 ms/op
                 listUser·p0.90:   11.354 ms/op
                 listUser·p0.95:   12.647 ms/op
                 listUser·p0.99:   17.286 ms/op
                 listUser·p0.999:  22.174 ms/op
                 listUser·p0.9999: 25.985 ms/op
                 listUser·p1.00:   25.985 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3661
  mean =      8.748 ±(99.9%) 0.122 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 63 
    [ 5.000,  7.500) = 995 
    [ 7.500, 10.000) = 1833 
    [10.000, 12.500) = 569 
    [12.500, 15.000) = 132 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.748 ms/op
     p(50.0000) =      8.471 ms/op
     p(90.0000) =     11.354 ms/op
     p(95.0000) =     12.647 ms/op
     p(99.0000) =     17.286 ms/op
     p(99.9000) =     22.174 ms/op
     p(99.9900) =     25.985 ms/op
     p(99.9990) =     25.985 ms/op
     p(99.9999) =     25.985 ms/op
    p(100.0000) =     25.985 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.365          ops/ms
Client.existUser                       thrpt         11.111          ops/ms
Client.getUser                         thrpt          8.959          ops/ms
Client.listUser                        thrpt          3.345          ops/ms
Client.createUser                       avgt          3.150           ms/op
Client.existUser                        avgt          1.939           ms/op
Client.getUser                          avgt          3.254           ms/op
Client.listUser                         avgt          9.256           ms/op
Client.createUser                     sample  10540   3.042 ± 0.042   ms/op
Client.createUser:createUser·p0.00    sample          1.231           ms/op
Client.createUser:createUser·p0.50    sample          2.775           ms/op
Client.createUser:createUser·p0.90    sample          3.949           ms/op
Client.createUser:createUser·p0.95    sample          4.268           ms/op
Client.createUser:createUser·p0.99    sample          9.978           ms/op
Client.createUser:createUser·p0.999   sample         15.417           ms/op
Client.createUser:createUser·p0.9999  sample         16.200           ms/op
Client.createUser:createUser·p1.00    sample         16.204           ms/op
Client.existUser                      sample  17528   1.824 ± 0.018   ms/op
Client.existUser:existUser·p0.00      sample          0.591           ms/op
Client.existUser:existUser·p0.50      sample          1.741           ms/op
Client.existUser:existUser·p0.90      sample          2.191           ms/op
Client.existUser:existUser·p0.95      sample          2.415           ms/op
Client.existUser:existUser·p0.99      sample          3.657           ms/op
Client.existUser:existUser·p0.999     sample         12.911           ms/op
Client.existUser:existUser·p0.9999    sample         14.094           ms/op
Client.existUser:existUser·p1.00      sample         14.205           ms/op
Client.getUser                        sample  10472   3.056 ± 0.024   ms/op
Client.getUser:getUser·p0.00          sample          0.993           ms/op
Client.getUser:getUser·p0.50          sample          2.937           ms/op
Client.getUser:getUser·p0.90          sample          4.014           ms/op
Client.getUser:getUser·p0.95          sample          4.260           ms/op
Client.getUser:getUser·p0.99          sample          5.032           ms/op
Client.getUser:getUser·p0.999         sample          6.248           ms/op
Client.getUser:getUser·p0.9999        sample         10.141           ms/op
Client.getUser:getUser·p1.00          sample         10.191           ms/op
Client.listUser                       sample   3661   8.748 ± 0.122   ms/op
Client.listUser:listUser·p0.00        sample          2.748           ms/op
Client.listUser:listUser·p0.50        sample          8.471           ms/op
Client.listUser:listUser·p0.90        sample         11.354           ms/op
Client.listUser:listUser·p0.95        sample         12.647           ms/op
Client.listUser:listUser·p0.99        sample         17.286           ms/op
Client.listUser:listUser·p0.999       sample         22.174           ms/op
Client.listUser:listUser·p0.9999      sample         25.985           ms/op
Client.listUser:listUser·p1.00        sample         25.985           ms/op
