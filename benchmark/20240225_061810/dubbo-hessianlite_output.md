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
# Warmup Iteration   1: 2.224 ops/ms
Iteration   1: 5.891 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.891 ops/ms


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
# Warmup Iteration   1: 5.606 ops/ms
Iteration   1: 12.179 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.179 ops/ms


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
# Warmup Iteration   1: 4.285 ops/ms
Iteration   1: 8.143 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.143 ops/ms


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
# Warmup Iteration   1: 2.191 ops/ms
Iteration   1: 3.248 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.248 ops/ms


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
# Warmup Iteration   1: 5.435 ±(99.9%) 0.074 ms/op
Iteration   1: 3.418 ±(99.9%) 0.063 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.418 ms/op


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
# Warmup Iteration   1: 3.000 ±(99.9%) 0.034 ms/op
Iteration   1: 1.829 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.829 ms/op


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
# Warmup Iteration   1: 4.960 ±(99.9%) 0.061 ms/op
Iteration   1: 3.144 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.144 ms/op


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
# Warmup Iteration   1: 11.769 ±(99.9%) 0.192 ms/op
Iteration   1: 8.230 ±(99.9%) 0.059 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.230 ms/op


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
# Warmup Iteration   1: 4.922 ±(99.9%) 0.096 ms/op
Iteration   1: 3.224 ±(99.9%) 0.047 ms/op
                 createUser·p0.00:   1.015 ms/op
                 createUser·p0.50:   2.904 ms/op
                 createUser·p0.90:   4.301 ms/op
                 createUser·p0.95:   4.719 ms/op
                 createUser·p0.99:   10.666 ms/op
                 createUser·p0.999:  17.099 ms/op
                 createUser·p0.9999: 17.891 ms/op
                 createUser·p1.00:   17.891 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10179
  mean =      3.224 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 15 
    [ 1.250,  2.500) = 1781 
    [ 2.500,  3.750) = 6538 
    [ 3.750,  5.000) = 1436 
    [ 5.000,  6.250) = 154 
    [ 6.250,  7.500) = 41 
    [ 7.500,  8.750) = 66 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 64 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.015 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =     10.666 ms/op
     p(99.9000) =     17.099 ms/op
     p(99.9900) =     17.891 ms/op
     p(99.9990) =     17.891 ms/op
     p(99.9999) =     17.891 ms/op
    p(100.0000) =     17.891 ms/op


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
# Warmup Iteration   1: 3.038 ±(99.9%) 0.077 ms/op
Iteration   1: 1.791 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.761 ms/op
                 existUser·p0.50:   1.692 ms/op
                 existUser·p0.90:   2.359 ms/op
                 existUser·p0.95:   2.561 ms/op
                 existUser·p0.99:   3.228 ms/op
                 existUser·p0.999:  8.872 ms/op
                 existUser·p0.9999: 9.249 ms/op
                 existUser·p1.00:   9.339 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17836
  mean =      1.791 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 134 
    [ 1.000,  2.000) = 13550 
    [ 2.000,  3.000) = 3880 
    [ 3.000,  4.000) = 201 
    [ 4.000,  5.000) = 7 
    [ 5.000,  6.000) = 29 
    [ 6.000,  7.000) = 16 
    [ 7.000,  8.000) = 0 
    [ 8.000,  9.000) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.761 ms/op
     p(50.0000) =      1.692 ms/op
     p(90.0000) =      2.359 ms/op
     p(95.0000) =      2.561 ms/op
     p(99.0000) =      3.228 ms/op
     p(99.9000) =      8.872 ms/op
     p(99.9900) =      9.249 ms/op
     p(99.9990) =      9.339 ms/op
     p(99.9999) =      9.339 ms/op
    p(100.0000) =      9.339 ms/op


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
# Warmup Iteration   1: 4.511 ±(99.9%) 0.104 ms/op
Iteration   1: 3.145 ±(99.9%) 0.030 ms/op
                 getUser·p0.00:   0.805 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.912 ms/op
                 getUser·p0.95:   4.155 ms/op
                 getUser·p0.99:   4.964 ms/op
                 getUser·p0.999:  14.841 ms/op
                 getUser·p0.9999: 17.952 ms/op
                 getUser·p1.00:   17.957 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10169
  mean =      3.145 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 23 
    [ 1.250,  2.500) = 1426 
    [ 2.500,  3.750) = 7121 
    [ 3.750,  5.000) = 1508 
    [ 5.000,  6.250) = 46 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.805 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.155 ms/op
     p(99.0000) =      4.964 ms/op
     p(99.9000) =     14.841 ms/op
     p(99.9900) =     17.952 ms/op
     p(99.9990) =     17.957 ms/op
     p(99.9999) =     17.957 ms/op
    p(100.0000) =     17.957 ms/op


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
# Warmup Iteration   1: 11.778 ±(99.9%) 0.358 ms/op
Iteration   1: 8.440 ±(99.9%) 0.122 ms/op
                 listUser·p0.00:   2.195 ms/op
                 listUser·p0.50:   8.086 ms/op
                 listUser·p0.90:   11.403 ms/op
                 listUser·p0.95:   12.763 ms/op
                 listUser·p0.99:   15.761 ms/op
                 listUser·p0.999:  18.505 ms/op
                 listUser·p0.9999: 20.513 ms/op
                 listUser·p1.00:   20.513 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3786
  mean =      8.440 ±(99.9%) 0.122 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 114 
    [ 5.000,  7.500) = 1272 
    [ 7.500, 10.000) = 1612 
    [10.000, 12.500) = 584 
    [12.500, 15.000) = 147 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.195 ms/op
     p(50.0000) =      8.086 ms/op
     p(90.0000) =     11.403 ms/op
     p(95.0000) =     12.763 ms/op
     p(99.0000) =     15.761 ms/op
     p(99.9000) =     18.505 ms/op
     p(99.9900) =     20.513 ms/op
     p(99.9990) =     20.513 ms/op
     p(99.9999) =     20.513 ms/op
    p(100.0000) =     20.513 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.891          ops/ms
Client.existUser                       thrpt         12.179          ops/ms
Client.getUser                         thrpt          8.143          ops/ms
Client.listUser                        thrpt          3.248          ops/ms
Client.createUser                       avgt          3.418           ms/op
Client.existUser                        avgt          1.829           ms/op
Client.getUser                          avgt          3.144           ms/op
Client.listUser                         avgt          8.230           ms/op
Client.createUser                     sample  10179   3.224 ± 0.047   ms/op
Client.createUser:createUser·p0.00    sample          1.015           ms/op
Client.createUser:createUser·p0.50    sample          2.904           ms/op
Client.createUser:createUser·p0.90    sample          4.301           ms/op
Client.createUser:createUser·p0.95    sample          4.719           ms/op
Client.createUser:createUser·p0.99    sample         10.666           ms/op
Client.createUser:createUser·p0.999   sample         17.099           ms/op
Client.createUser:createUser·p0.9999  sample         17.891           ms/op
Client.createUser:createUser·p1.00    sample         17.891           ms/op
Client.existUser                      sample  17836   1.791 ± 0.013   ms/op
Client.existUser:existUser·p0.00      sample          0.761           ms/op
Client.existUser:existUser·p0.50      sample          1.692           ms/op
Client.existUser:existUser·p0.90      sample          2.359           ms/op
Client.existUser:existUser·p0.95      sample          2.561           ms/op
Client.existUser:existUser·p0.99      sample          3.228           ms/op
Client.existUser:existUser·p0.999     sample          8.872           ms/op
Client.existUser:existUser·p0.9999    sample          9.249           ms/op
Client.existUser:existUser·p1.00      sample          9.339           ms/op
Client.getUser                        sample  10169   3.145 ± 0.030   ms/op
Client.getUser:getUser·p0.00          sample          0.805           ms/op
Client.getUser:getUser·p0.50          sample          3.015           ms/op
Client.getUser:getUser·p0.90          sample          3.912           ms/op
Client.getUser:getUser·p0.95          sample          4.155           ms/op
Client.getUser:getUser·p0.99          sample          4.964           ms/op
Client.getUser:getUser·p0.999         sample         14.841           ms/op
Client.getUser:getUser·p0.9999        sample         17.952           ms/op
Client.getUser:getUser·p1.00          sample         17.957           ms/op
Client.listUser                       sample   3786   8.440 ± 0.122   ms/op
Client.listUser:listUser·p0.00        sample          2.195           ms/op
Client.listUser:listUser·p0.50        sample          8.086           ms/op
Client.listUser:listUser·p0.90        sample         11.403           ms/op
Client.listUser:listUser·p0.95        sample         12.763           ms/op
Client.listUser:listUser·p0.99        sample         15.761           ms/op
Client.listUser:listUser·p0.999       sample         18.505           ms/op
Client.listUser:listUser·p0.9999      sample         20.513           ms/op
Client.listUser:listUser·p1.00        sample         20.513           ms/op
