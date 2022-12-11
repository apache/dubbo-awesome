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
# Warmup Iteration   1: 1.080 ops/ms
Iteration   1: 2.949 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.949 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 3.646 ops/ms
Iteration   1: 6.027 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.027 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.185 ops/ms
Iteration   1: 6.260 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  6.260 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 0.901 ops/ms
Iteration   1: 1.449 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.449 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 12.598 ±(99.9%) 0.206 ms/op
Iteration   1: 7.179 ±(99.9%) 0.042 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  7.179 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 7.032 ±(99.9%) 0.090 ms/op
Iteration   1: 3.866 ±(99.9%) 0.050 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.866 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 9.191 ±(99.9%) 0.102 ms/op
Iteration   1: 4.903 ±(99.9%) 0.042 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.903 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 26.357 ±(99.9%) 0.631 ms/op
Iteration   1: 16.912 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  16.912 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.255 ±(99.9%) 0.264 ms/op
Iteration   1: 6.358 ±(99.9%) 0.093 ms/op
                 createUser·p0.00:   3.154 ms/op
                 createUser·p0.50:   6.226 ms/op
                 createUser·p0.90:   6.627 ms/op
                 createUser·p0.95:   8.502 ms/op
                 createUser·p0.99:   15.827 ms/op
                 createUser·p0.999:  24.314 ms/op
                 createUser·p0.9999: 24.347 ms/op
                 createUser·p1.00:   24.347 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5092
  mean =      6.358 ±(99.9%) 0.093 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 465 
    [ 5.000,  7.500) = 4333 
    [ 7.500, 10.000) = 74 
    [10.000, 12.500) = 124 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.154 ms/op
     p(50.0000) =      6.226 ms/op
     p(90.0000) =      6.627 ms/op
     p(95.0000) =      8.502 ms/op
     p(99.0000) =     15.827 ms/op
     p(99.9000) =     24.314 ms/op
     p(99.9900) =     24.347 ms/op
     p(99.9990) =     24.347 ms/op
     p(99.9999) =     24.347 ms/op
    p(100.0000) =     24.347 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 6.250 ±(99.9%) 0.196 ms/op
Iteration   1: 3.056 ±(99.9%) 0.067 ms/op
                 existUser·p0.00:   1.229 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.528 ms/op
                 existUser·p0.95:   4.628 ms/op
                 existUser·p0.99:   11.125 ms/op
                 existUser·p0.999:  29.101 ms/op
                 existUser·p0.9999: 29.555 ms/op
                 existUser·p1.00:   29.557 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 10457
  mean =      3.056 ±(99.9%) 0.067 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2971 
    [ 2.500,  5.000) = 7025 
    [ 5.000,  7.500) = 214 
    [ 7.500, 10.000) = 119 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.229 ms/op
     p(50.0000) =      2.851 ms/op
     p(90.0000) =      3.528 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =     11.125 ms/op
     p(99.9000) =     29.101 ms/op
     p(99.9900) =     29.555 ms/op
     p(99.9990) =     29.557 ms/op
     p(99.9999) =     29.557 ms/op
    p(100.0000) =     29.557 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 10.163 ±(99.9%) 0.354 ms/op
Iteration   1: 4.572 ±(99.9%) 0.048 ms/op
                 getUser·p0.00:   1.575 ms/op
                 getUser·p0.50:   4.506 ms/op
                 getUser·p0.90:   5.222 ms/op
                 getUser·p0.95:   5.620 ms/op
                 getUser·p0.99:   9.286 ms/op
                 getUser·p0.999:  17.727 ms/op
                 getUser·p0.9999: 18.317 ms/op
                 getUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7164
  mean =      4.572 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 51 
    [ 2.500,  3.750) = 1091 
    [ 3.750,  5.000) = 4886 
    [ 5.000,  6.250) = 923 
    [ 6.250,  7.500) = 117 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.575 ms/op
     p(50.0000) =      4.506 ms/op
     p(90.0000) =      5.222 ms/op
     p(95.0000) =      5.620 ms/op
     p(99.0000) =      9.286 ms/op
     p(99.9000) =     17.727 ms/op
     p(99.9900) =     18.317 ms/op
     p(99.9990) =     18.317 ms/op
     p(99.9999) =     18.317 ms/op
    p(100.0000) =     18.317 ms/op


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
# Warmup Iteration   1: 25.559 ±(99.9%) 0.923 ms/op
Iteration   1: 15.582 ±(99.9%) 0.114 ms/op
                 listUser·p0.00:   8.118 ms/op
                 listUser·p0.50:   15.188 ms/op
                 listUser·p0.90:   16.810 ms/op
                 listUser·p0.95:   17.975 ms/op
                 listUser·p0.99:   22.891 ms/op
                 listUser·p0.999:  25.295 ms/op
                 listUser·p0.9999: 25.428 ms/op
                 listUser·p1.00:   25.428 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2042
  mean =     15.582 ±(99.9%) 0.114 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 12 
    [12.500, 15.000) = 764 
    [15.000, 17.500) = 1137 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      8.118 ms/op
     p(50.0000) =     15.188 ms/op
     p(90.0000) =     16.810 ms/op
     p(95.0000) =     17.975 ms/op
     p(99.0000) =     22.891 ms/op
     p(99.9000) =     25.295 ms/op
     p(99.9900) =     25.428 ms/op
     p(99.9990) =     25.428 ms/op
     p(99.9999) =     25.428 ms/op
    p(100.0000) =     25.428 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          2.949          ops/ms
Client.existUser                       thrpt          6.027          ops/ms
Client.getUser                         thrpt          6.260          ops/ms
Client.listUser                        thrpt          1.449          ops/ms
Client.createUser                       avgt          7.179           ms/op
Client.existUser                        avgt          3.866           ms/op
Client.getUser                          avgt          4.903           ms/op
Client.listUser                         avgt         16.912           ms/op
Client.createUser                     sample   5092   6.358 ± 0.093   ms/op
Client.createUser:createUser·p0.00    sample          3.154           ms/op
Client.createUser:createUser·p0.50    sample          6.226           ms/op
Client.createUser:createUser·p0.90    sample          6.627           ms/op
Client.createUser:createUser·p0.95    sample          8.502           ms/op
Client.createUser:createUser·p0.99    sample         15.827           ms/op
Client.createUser:createUser·p0.999   sample         24.314           ms/op
Client.createUser:createUser·p0.9999  sample         24.347           ms/op
Client.createUser:createUser·p1.00    sample         24.347           ms/op
Client.existUser                      sample  10457   3.056 ± 0.067   ms/op
Client.existUser:existUser·p0.00      sample          1.229           ms/op
Client.existUser:existUser·p0.50      sample          2.851           ms/op
Client.existUser:existUser·p0.90      sample          3.528           ms/op
Client.existUser:existUser·p0.95      sample          4.628           ms/op
Client.existUser:existUser·p0.99      sample         11.125           ms/op
Client.existUser:existUser·p0.999     sample         29.101           ms/op
Client.existUser:existUser·p0.9999    sample         29.555           ms/op
Client.existUser:existUser·p1.00      sample         29.557           ms/op
Client.getUser                        sample   7164   4.572 ± 0.048   ms/op
Client.getUser:getUser·p0.00          sample          1.575           ms/op
Client.getUser:getUser·p0.50          sample          4.506           ms/op
Client.getUser:getUser·p0.90          sample          5.222           ms/op
Client.getUser:getUser·p0.95          sample          5.620           ms/op
Client.getUser:getUser·p0.99          sample          9.286           ms/op
Client.getUser:getUser·p0.999         sample         17.727           ms/op
Client.getUser:getUser·p0.9999        sample         18.317           ms/op
Client.getUser:getUser·p1.00          sample         18.317           ms/op
Client.listUser                       sample   2042  15.582 ± 0.114   ms/op
Client.listUser:listUser·p0.00        sample          8.118           ms/op
Client.listUser:listUser·p0.50        sample         15.188           ms/op
Client.listUser:listUser·p0.90        sample         16.810           ms/op
Client.listUser:listUser·p0.95        sample         17.975           ms/op
Client.listUser:listUser·p0.99        sample         22.891           ms/op
Client.listUser:listUser·p0.999       sample         25.295           ms/op
Client.listUser:listUser·p0.9999      sample         25.428           ms/op
Client.listUser:listUser·p1.00        sample         25.428           ms/op
