# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.350 ops/ms
Iteration   1: 2.964 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.964 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 3.934 ops/ms
Iteration   1: 7.544 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  7.544 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.423 ops/ms
Iteration   1: 4.591 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.591 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 0.963 ops/ms
Iteration   1: 1.382 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.382 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 14.623 ±(99.9%) 0.171 ms/op
Iteration   1: 6.761 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.761 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.995 ±(99.9%) 0.063 ms/op
Iteration   1: 3.441 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.441 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.692 ±(99.9%) 0.133 ms/op
Iteration   1: 4.755 ±(99.9%) 0.034 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.755 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 25.340 ±(99.9%) 0.415 ms/op
Iteration   1: 15.698 ±(99.9%) 0.070 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  15.698 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.245 ±(99.9%) 0.284 ms/op
Iteration   1: 5.473 ±(99.9%) 0.097 ms/op
                 createUser·p0.00:   1.800 ms/op
                 createUser·p0.50:   5.120 ms/op
                 createUser·p0.90:   5.710 ms/op
                 createUser·p0.95:   6.287 ms/op
                 createUser·p0.99:   15.073 ms/op
                 createUser·p0.999:  32.907 ms/op
                 createUser·p0.9999: 33.128 ms/op
                 createUser·p1.00:   33.128 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5871
  mean =      5.473 ±(99.9%) 0.097 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 1923 
    [ 5.000,  7.500) = 3677 
    [ 7.500, 10.000) = 103 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.800 ms/op
     p(50.0000) =      5.120 ms/op
     p(90.0000) =      5.710 ms/op
     p(95.0000) =      6.287 ms/op
     p(99.0000) =     15.073 ms/op
     p(99.9000) =     32.907 ms/op
     p(99.9900) =     33.128 ms/op
     p(99.9990) =     33.128 ms/op
     p(99.9999) =     33.128 ms/op
    p(100.0000) =     33.128 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 5.778 ±(99.9%) 0.182 ms/op
Iteration   1: 3.301 ±(99.9%) 0.044 ms/op
                 existUser·p0.00:   0.556 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.695 ms/op
                 existUser·p0.95:   3.912 ms/op
                 existUser·p0.99:   9.978 ms/op
                 existUser·p0.999:  17.727 ms/op
                 existUser·p0.9999: 17.727 ms/op
                 existUser·p1.00:   17.727 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 9702
  mean =      3.301 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 83 
    [ 1.250,  2.500) = 443 
    [ 2.500,  3.750) = 8465 
    [ 3.750,  5.000) = 444 
    [ 5.000,  6.250) = 11 
    [ 6.250,  7.500) = 66 
    [ 7.500,  8.750) = 51 
    [ 8.750, 10.000) = 43 
    [10.000, 11.250) = 60 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.556 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.695 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      9.978 ms/op
     p(99.9000) =     17.727 ms/op
     p(99.9900) =     17.727 ms/op
     p(99.9990) =     17.727 ms/op
     p(99.9999) =     17.727 ms/op
    p(100.0000) =     17.727 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 10.629 ±(99.9%) 0.427 ms/op
Iteration   1: 4.473 ±(99.9%) 0.036 ms/op
                 getUser·p0.00:   1.784 ms/op
                 getUser·p0.50:   4.325 ms/op
                 getUser·p0.90:   5.038 ms/op
                 getUser·p0.95:   5.415 ms/op
                 getUser·p0.99:   6.566 ms/op
                 getUser·p0.999:  13.484 ms/op
                 getUser·p0.9999: 13.517 ms/op
                 getUser·p1.00:   13.517 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7150
  mean =      4.473 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 11 
    [ 2.500,  3.750) = 375 
    [ 3.750,  5.000) = 6004 
    [ 5.000,  6.250) = 649 
    [ 6.250,  7.500) = 42 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.784 ms/op
     p(50.0000) =      4.325 ms/op
     p(90.0000) =      5.038 ms/op
     p(95.0000) =      5.415 ms/op
     p(99.0000) =      6.566 ms/op
     p(99.9000) =     13.484 ms/op
     p(99.9900) =     13.517 ms/op
     p(99.9990) =     13.517 ms/op
     p(99.9999) =     13.517 ms/op
    p(100.0000) =     13.517 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 23.597 ±(99.9%) 0.705 ms/op
Iteration   1: 15.309 ±(99.9%) 0.254 ms/op
                 listUser·p0.00:   8.913 ms/op
                 listUser·p0.50:   15.794 ms/op
                 listUser·p0.90:   17.433 ms/op
                 listUser·p0.95:   19.936 ms/op
                 listUser·p0.99:   32.796 ms/op
                 listUser·p0.999:  38.111 ms/op
                 listUser·p0.9999: 38.928 ms/op
                 listUser·p1.00:   38.928 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2091
  mean =     15.309 ±(99.9%) 0.254 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 7 
    [10.000, 12.500) = 546 
    [12.500, 15.000) = 407 
    [15.000, 17.500) = 940 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 8 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      8.913 ms/op
     p(50.0000) =     15.794 ms/op
     p(90.0000) =     17.433 ms/op
     p(95.0000) =     19.936 ms/op
     p(99.0000) =     32.796 ms/op
     p(99.9000) =     38.111 ms/op
     p(99.9900) =     38.928 ms/op
     p(99.9990) =     38.928 ms/op
     p(99.9999) =     38.928 ms/op
    p(100.0000) =     38.928 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.964          ops/ms
Client.existUser                       thrpt         7.544          ops/ms
Client.getUser                         thrpt         4.591          ops/ms
Client.listUser                        thrpt         1.382          ops/ms
Client.createUser                       avgt         6.761           ms/op
Client.existUser                        avgt         3.441           ms/op
Client.getUser                          avgt         4.755           ms/op
Client.listUser                         avgt        15.698           ms/op
Client.createUser                     sample  5871   5.473 ± 0.097   ms/op
Client.createUser:createUser·p0.00    sample         1.800           ms/op
Client.createUser:createUser·p0.50    sample         5.120           ms/op
Client.createUser:createUser·p0.90    sample         5.710           ms/op
Client.createUser:createUser·p0.95    sample         6.287           ms/op
Client.createUser:createUser·p0.99    sample        15.073           ms/op
Client.createUser:createUser·p0.999   sample        32.907           ms/op
Client.createUser:createUser·p0.9999  sample        33.128           ms/op
Client.createUser:createUser·p1.00    sample        33.128           ms/op
Client.existUser                      sample  9702   3.301 ± 0.044   ms/op
Client.existUser:existUser·p0.00      sample         0.556           ms/op
Client.existUser:existUser·p0.50      sample         3.084           ms/op
Client.existUser:existUser·p0.90      sample         3.695           ms/op
Client.existUser:existUser·p0.95      sample         3.912           ms/op
Client.existUser:existUser·p0.99      sample         9.978           ms/op
Client.existUser:existUser·p0.999     sample        17.727           ms/op
Client.existUser:existUser·p0.9999    sample        17.727           ms/op
Client.existUser:existUser·p1.00      sample        17.727           ms/op
Client.getUser                        sample  7150   4.473 ± 0.036   ms/op
Client.getUser:getUser·p0.00          sample         1.784           ms/op
Client.getUser:getUser·p0.50          sample         4.325           ms/op
Client.getUser:getUser·p0.90          sample         5.038           ms/op
Client.getUser:getUser·p0.95          sample         5.415           ms/op
Client.getUser:getUser·p0.99          sample         6.566           ms/op
Client.getUser:getUser·p0.999         sample        13.484           ms/op
Client.getUser:getUser·p0.9999        sample        13.517           ms/op
Client.getUser:getUser·p1.00          sample        13.517           ms/op
Client.listUser                       sample  2091  15.309 ± 0.254   ms/op
Client.listUser:listUser·p0.00        sample         8.913           ms/op
Client.listUser:listUser·p0.50        sample        15.794           ms/op
Client.listUser:listUser·p0.90        sample        17.433           ms/op
Client.listUser:listUser·p0.95        sample        19.936           ms/op
Client.listUser:listUser·p0.99        sample        32.796           ms/op
Client.listUser:listUser·p0.999       sample        38.111           ms/op
Client.listUser:listUser·p0.9999      sample        38.928           ms/op
Client.listUser:listUser·p1.00        sample        38.928           ms/op
