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
# Warmup Iteration   1: 2.193 ops/ms
Iteration   1: 6.043 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.043 ops/ms


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
# Warmup Iteration   1: 6.292 ops/ms
Iteration   1: 12.825 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.825 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.625 ops/ms
Iteration   1: 8.588 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.588 ops/ms


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
# Warmup Iteration   1: 2.147 ops/ms
Iteration   1: 3.850 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.850 ops/ms


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
# Warmup Iteration   1: 4.924 ±(99.9%) 0.067 ms/op
Iteration   1: 2.941 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.941 ms/op


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
# Warmup Iteration   1: 3.288 ±(99.9%) 0.034 ms/op
Iteration   1: 2.017 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.017 ms/op


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
# Warmup Iteration   1: 4.922 ±(99.9%) 0.069 ms/op
Iteration   1: 2.824 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.824 ms/op


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
# Warmup Iteration   1: 12.243 ±(99.9%) 0.221 ms/op
Iteration   1: 7.941 ±(99.9%) 0.101 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.941 ms/op


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
# Warmup Iteration   1: 5.083 ±(99.9%) 0.101 ms/op
Iteration   1: 3.039 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   1.139 ms/op
                 createUser·p0.50:   2.818 ms/op
                 createUser·p0.90:   3.936 ms/op
                 createUser·p0.95:   4.544 ms/op
                 createUser·p0.99:   9.060 ms/op
                 createUser·p0.999:  11.678 ms/op
                 createUser·p0.9999: 13.056 ms/op
                 createUser·p1.00:   13.058 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10526
  mean =      3.039 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 2537 
    [ 2.500,  3.750) = 6841 
    [ 3.750,  5.000) = 794 
    [ 5.000,  6.250) = 169 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 55 
    [10.000, 11.250) = 35 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.139 ms/op
     p(50.0000) =      2.818 ms/op
     p(90.0000) =      3.936 ms/op
     p(95.0000) =      4.544 ms/op
     p(99.0000) =      9.060 ms/op
     p(99.9000) =     11.678 ms/op
     p(99.9900) =     13.056 ms/op
     p(99.9990) =     13.058 ms/op
     p(99.9999) =     13.058 ms/op
    p(100.0000) =     13.058 ms/op


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
# Warmup Iteration   1: 2.973 ±(99.9%) 0.059 ms/op
Iteration   1: 1.939 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.501 ms/op
                 existUser·p0.50:   1.917 ms/op
                 existUser·p0.90:   2.494 ms/op
                 existUser·p0.95:   2.720 ms/op
                 existUser·p0.99:   3.080 ms/op
                 existUser·p0.999:  3.929 ms/op
                 existUser·p0.9999: 6.239 ms/op
                 existUser·p1.00:   6.717 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16493
  mean =      1.939 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 242 
    [1.000, 1.500) = 2282 
    [1.500, 2.000) = 6881 
    [2.000, 2.500) = 5466 
    [2.500, 3.000) = 1401 
    [3.000, 3.500) = 168 
    [3.500, 4.000) = 38 
    [4.000, 4.500) = 6 
    [4.500, 5.000) = 2 
    [5.000, 5.500) = 0 
    [5.500, 6.000) = 6 
    [6.000, 6.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.501 ms/op
     p(50.0000) =      1.917 ms/op
     p(90.0000) =      2.494 ms/op
     p(95.0000) =      2.720 ms/op
     p(99.0000) =      3.080 ms/op
     p(99.9000) =      3.929 ms/op
     p(99.9900) =      6.239 ms/op
     p(99.9990) =      6.717 ms/op
     p(99.9999) =      6.717 ms/op
    p(100.0000) =      6.717 ms/op


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
# Warmup Iteration   1: 4.728 ±(99.9%) 0.116 ms/op
Iteration   1: 2.789 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.967 ms/op
                 getUser·p0.50:   2.732 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  5.879 ms/op
                 getUser·p0.9999: 6.474 ms/op
                 getUser·p1.00:   6.480 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11475
  mean =      2.789 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 1 
    [1.000, 1.500) = 68 
    [1.500, 2.000) = 577 
    [2.000, 2.500) = 3858 
    [2.500, 3.000) = 2906 
    [3.000, 3.500) = 2584 
    [3.500, 4.000) = 1112 
    [4.000, 4.500) = 261 
    [4.500, 5.000) = 65 
    [5.000, 5.500) = 20 
    [5.500, 6.000) = 17 
    [6.000, 6.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.967 ms/op
     p(50.0000) =      2.732 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      5.879 ms/op
     p(99.9900) =      6.474 ms/op
     p(99.9990) =      6.480 ms/op
     p(99.9999) =      6.480 ms/op
    p(100.0000) =      6.480 ms/op


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
# Warmup Iteration   1: 11.967 ±(99.9%) 0.459 ms/op
Iteration   1: 7.469 ±(99.9%) 0.128 ms/op
                 listUser·p0.00:   2.699 ms/op
                 listUser·p0.50:   7.033 ms/op
                 listUser·p0.90:   9.585 ms/op
                 listUser·p0.95:   10.665 ms/op
                 listUser·p0.99:   19.890 ms/op
                 listUser·p0.999:  27.148 ms/op
                 listUser·p0.9999: 32.178 ms/op
                 listUser·p1.00:   32.178 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4300
  mean =      7.469 ±(99.9%) 0.128 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 237 
    [ 5.000,  7.500) = 2392 
    [ 7.500, 10.000) = 1342 
    [10.000, 12.500) = 215 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 22 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.699 ms/op
     p(50.0000) =      7.033 ms/op
     p(90.0000) =      9.585 ms/op
     p(95.0000) =     10.665 ms/op
     p(99.0000) =     19.890 ms/op
     p(99.9000) =     27.148 ms/op
     p(99.9900) =     32.178 ms/op
     p(99.9990) =     32.178 ms/op
     p(99.9999) =     32.178 ms/op
    p(100.0000) =     32.178 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.043          ops/ms
Client.existUser                       thrpt         12.825          ops/ms
Client.getUser                         thrpt          8.588          ops/ms
Client.listUser                        thrpt          3.850          ops/ms
Client.createUser                       avgt          2.941           ms/op
Client.existUser                        avgt          2.017           ms/op
Client.getUser                          avgt          2.824           ms/op
Client.listUser                         avgt          7.941           ms/op
Client.createUser                     sample  10526   3.039 ± 0.035   ms/op
Client.createUser:createUser·p0.00    sample          1.139           ms/op
Client.createUser:createUser·p0.50    sample          2.818           ms/op
Client.createUser:createUser·p0.90    sample          3.936           ms/op
Client.createUser:createUser·p0.95    sample          4.544           ms/op
Client.createUser:createUser·p0.99    sample          9.060           ms/op
Client.createUser:createUser·p0.999   sample         11.678           ms/op
Client.createUser:createUser·p0.9999  sample         13.056           ms/op
Client.createUser:createUser·p1.00    sample         13.058           ms/op
Client.existUser                      sample  16493   1.939 ± 0.012   ms/op
Client.existUser:existUser·p0.00      sample          0.501           ms/op
Client.existUser:existUser·p0.50      sample          1.917           ms/op
Client.existUser:existUser·p0.90      sample          2.494           ms/op
Client.existUser:existUser·p0.95      sample          2.720           ms/op
Client.existUser:existUser·p0.99      sample          3.080           ms/op
Client.existUser:existUser·p0.999     sample          3.929           ms/op
Client.existUser:existUser·p0.9999    sample          6.239           ms/op
Client.existUser:existUser·p1.00      sample          6.717           ms/op
Client.getUser                        sample  11475   2.789 ± 0.019   ms/op
Client.getUser:getUser·p0.00          sample          0.967           ms/op
Client.getUser:getUser·p0.50          sample          2.732           ms/op
Client.getUser:getUser·p0.90          sample          3.588           ms/op
Client.getUser:getUser·p0.95          sample          3.817           ms/op
Client.getUser:getUser·p0.99          sample          4.415           ms/op
Client.getUser:getUser·p0.999         sample          5.879           ms/op
Client.getUser:getUser·p0.9999        sample          6.474           ms/op
Client.getUser:getUser·p1.00          sample          6.480           ms/op
Client.listUser                       sample   4300   7.469 ± 0.128   ms/op
Client.listUser:listUser·p0.00        sample          2.699           ms/op
Client.listUser:listUser·p0.50        sample          7.033           ms/op
Client.listUser:listUser·p0.90        sample          9.585           ms/op
Client.listUser:listUser·p0.95        sample         10.665           ms/op
Client.listUser:listUser·p0.99        sample         19.890           ms/op
Client.listUser:listUser·p0.999       sample         27.148           ms/op
Client.listUser:listUser·p0.9999      sample         32.178           ms/op
Client.listUser:listUser·p1.00        sample         32.178           ms/op
