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
# Warmup Iteration   1: 2.329 ops/ms
Iteration   1: 5.810 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.810 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.664 ops/ms
Iteration   1: 13.982 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.982 ops/ms


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
# Warmup Iteration   1: 4.245 ops/ms
Iteration   1: 8.545 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.545 ops/ms


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
# Warmup Iteration   1: 1.945 ops/ms
Iteration   1: 3.168 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.168 ops/ms


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
# Warmup Iteration   1: 5.901 ±(99.9%) 0.084 ms/op
Iteration   1: 3.269 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.269 ms/op


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
# Warmup Iteration   1: 3.232 ±(99.9%) 0.036 ms/op
Iteration   1: 1.988 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.988 ms/op


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
# Warmup Iteration   1: 4.889 ±(99.9%) 0.059 ms/op
Iteration   1: 2.909 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.909 ms/op


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
# Warmup Iteration   1: 11.387 ±(99.9%) 0.245 ms/op
Iteration   1: 8.823 ±(99.9%) 0.089 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.823 ms/op


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
# Warmup Iteration   1: 4.893 ±(99.9%) 0.129 ms/op
Iteration   1: 2.974 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   1.104 ms/op
                 createUser·p0.50:   2.879 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   5.147 ms/op
                 createUser·p0.999:  14.909 ms/op
                 createUser·p0.9999: 15.152 ms/op
                 createUser·p1.00:   15.155 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10823
  mean =      2.974 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 2204 
    [ 2.500,  3.750) = 7832 
    [ 3.750,  5.000) = 668 
    [ 5.000,  6.250) = 43 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.104 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      5.147 ms/op
     p(99.9000) =     14.909 ms/op
     p(99.9900) =     15.152 ms/op
     p(99.9990) =     15.155 ms/op
     p(99.9999) =     15.155 ms/op
    p(100.0000) =     15.155 ms/op


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
# Warmup Iteration   1: 3.147 ±(99.9%) 0.070 ms/op
Iteration   1: 2.038 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.729 ms/op
                 existUser·p0.50:   1.968 ms/op
                 existUser·p0.90:   2.519 ms/op
                 existUser·p0.95:   2.724 ms/op
                 existUser·p0.99:   3.237 ms/op
                 existUser·p0.999:  13.304 ms/op
                 existUser·p0.9999: 14.036 ms/op
                 existUser·p1.00:   14.385 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15766
  mean =      2.038 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 208 
    [ 1.250,  2.500) = 13880 
    [ 2.500,  3.750) = 1558 
    [ 3.750,  5.000) = 43 
    [ 5.000,  6.250) = 41 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.729 ms/op
     p(50.0000) =      1.968 ms/op
     p(90.0000) =      2.519 ms/op
     p(95.0000) =      2.724 ms/op
     p(99.0000) =      3.237 ms/op
     p(99.9000) =     13.304 ms/op
     p(99.9900) =     14.036 ms/op
     p(99.9990) =     14.385 ms/op
     p(99.9999) =     14.385 ms/op
    p(100.0000) =     14.385 ms/op


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
# Warmup Iteration   1: 4.739 ±(99.9%) 0.113 ms/op
Iteration   1: 3.240 ±(99.9%) 0.049 ms/op
                 getUser·p0.00:   1.041 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.822 ms/op
                 getUser·p0.95:   4.096 ms/op
                 getUser·p0.99:   4.989 ms/op
                 getUser·p0.999:  26.722 ms/op
                 getUser·p0.9999: 30.343 ms/op
                 getUser·p1.00:   30.343 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9833
  mean =      3.240 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1296 
    [ 2.500,  5.000) = 8442 
    [ 5.000,  7.500) = 61 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.041 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.096 ms/op
     p(99.0000) =      4.989 ms/op
     p(99.9000) =     26.722 ms/op
     p(99.9900) =     30.343 ms/op
     p(99.9990) =     30.343 ms/op
     p(99.9999) =     30.343 ms/op
    p(100.0000) =     30.343 ms/op


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
# Warmup Iteration   1: 12.848 ±(99.9%) 0.420 ms/op
Iteration   1: 7.964 ±(99.9%) 0.106 ms/op
                 listUser·p0.00:   2.142 ms/op
                 listUser·p0.50:   7.709 ms/op
                 listUser·p0.90:   10.699 ms/op
                 listUser·p0.95:   11.760 ms/op
                 listUser·p0.99:   14.286 ms/op
                 listUser·p0.999:  16.744 ms/op
                 listUser·p0.9999: 17.531 ms/op
                 listUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4004
  mean =      7.964 ±(99.9%) 0.106 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 2 
    [ 2.500,  3.750) = 19 
    [ 3.750,  5.000) = 124 
    [ 5.000,  6.250) = 626 
    [ 6.250,  7.500) = 1065 
    [ 7.500,  8.750) = 999 
    [ 8.750, 10.000) = 608 
    [10.000, 11.250) = 279 
    [11.250, 12.500) = 166 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 55 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.142 ms/op
     p(50.0000) =      7.709 ms/op
     p(90.0000) =     10.699 ms/op
     p(95.0000) =     11.760 ms/op
     p(99.0000) =     14.286 ms/op
     p(99.9000) =     16.744 ms/op
     p(99.9900) =     17.531 ms/op
     p(99.9990) =     17.531 ms/op
     p(99.9999) =     17.531 ms/op
    p(100.0000) =     17.531 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.810          ops/ms
Client.existUser                       thrpt         13.982          ops/ms
Client.getUser                         thrpt          8.545          ops/ms
Client.listUser                        thrpt          3.168          ops/ms
Client.createUser                       avgt          3.269           ms/op
Client.existUser                        avgt          1.988           ms/op
Client.getUser                          avgt          2.909           ms/op
Client.listUser                         avgt          8.823           ms/op
Client.createUser                     sample  10823   2.974 ± 0.028   ms/op
Client.createUser:createUser·p0.00    sample          1.104           ms/op
Client.createUser:createUser·p0.50    sample          2.879           ms/op
Client.createUser:createUser·p0.90    sample          3.600           ms/op
Client.createUser:createUser·p0.95    sample          3.969           ms/op
Client.createUser:createUser·p0.99    sample          5.147           ms/op
Client.createUser:createUser·p0.999   sample         14.909           ms/op
Client.createUser:createUser·p0.9999  sample         15.152           ms/op
Client.createUser:createUser·p1.00    sample         15.155           ms/op
Client.existUser                      sample  15766   2.038 ± 0.018   ms/op
Client.existUser:existUser·p0.00      sample          0.729           ms/op
Client.existUser:existUser·p0.50      sample          1.968           ms/op
Client.existUser:existUser·p0.90      sample          2.519           ms/op
Client.existUser:existUser·p0.95      sample          2.724           ms/op
Client.existUser:existUser·p0.99      sample          3.237           ms/op
Client.existUser:existUser·p0.999     sample         13.304           ms/op
Client.existUser:existUser·p0.9999    sample         14.036           ms/op
Client.existUser:existUser·p1.00      sample         14.385           ms/op
Client.getUser                        sample   9833   3.240 ± 0.049   ms/op
Client.getUser:getUser·p0.00          sample          1.041           ms/op
Client.getUser:getUser·p0.50          sample          3.207           ms/op
Client.getUser:getUser·p0.90          sample          3.822           ms/op
Client.getUser:getUser·p0.95          sample          4.096           ms/op
Client.getUser:getUser·p0.99          sample          4.989           ms/op
Client.getUser:getUser·p0.999         sample         26.722           ms/op
Client.getUser:getUser·p0.9999        sample         30.343           ms/op
Client.getUser:getUser·p1.00          sample         30.343           ms/op
Client.listUser                       sample   4004   7.964 ± 0.106   ms/op
Client.listUser:listUser·p0.00        sample          2.142           ms/op
Client.listUser:listUser·p0.50        sample          7.709           ms/op
Client.listUser:listUser·p0.90        sample         10.699           ms/op
Client.listUser:listUser·p0.95        sample         11.760           ms/op
Client.listUser:listUser·p0.99        sample         14.286           ms/op
Client.listUser:listUser·p0.999       sample         16.744           ms/op
Client.listUser:listUser·p0.9999      sample         17.531           ms/op
Client.listUser:listUser·p1.00        sample         17.531           ms/op
