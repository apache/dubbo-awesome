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
# Warmup Iteration   1: 2.304 ops/ms
Iteration   1: 5.981 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.981 ops/ms


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
# Warmup Iteration   1: 5.374 ops/ms
Iteration   1: 11.455 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.455 ops/ms


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
# Warmup Iteration   1: 4.136 ops/ms
Iteration   1: 8.764 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.764 ops/ms


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
# Warmup Iteration   1: 2.023 ops/ms
Iteration   1: 3.621 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.621 ops/ms


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
# Warmup Iteration   1: 5.228 ±(99.9%) 0.064 ms/op
Iteration   1: 3.451 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.451 ms/op


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
# Warmup Iteration   1: 3.110 ±(99.9%) 0.034 ms/op
Iteration   1: 1.991 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.991 ms/op


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
# Warmup Iteration   1: 4.760 ±(99.9%) 0.071 ms/op
Iteration   1: 2.925 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.925 ms/op


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
# Warmup Iteration   1: 12.030 ±(99.9%) 0.193 ms/op
Iteration   1: 7.663 ±(99.9%) 0.092 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.663 ms/op


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
# Warmup Iteration   1: 5.331 ±(99.9%) 0.146 ms/op
Iteration   1: 2.989 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   1.137 ms/op
                 createUser·p0.50:   2.839 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   4.104 ms/op
                 createUser·p0.99:   5.927 ms/op
                 createUser·p0.999:  9.683 ms/op
                 createUser·p0.9999: 11.364 ms/op
                 createUser·p1.00:   11.469 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10680
  mean =      2.989 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 1362 
    [ 2.500,  3.750) = 8445 
    [ 3.750,  5.000) = 625 
    [ 5.000,  6.250) = 145 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.137 ms/op
     p(50.0000) =      2.839 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      4.104 ms/op
     p(99.0000) =      5.927 ms/op
     p(99.9000) =      9.683 ms/op
     p(99.9900) =     11.364 ms/op
     p(99.9990) =     11.469 ms/op
     p(99.9999) =     11.469 ms/op
    p(100.0000) =     11.469 ms/op


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
# Warmup Iteration   1: 3.149 ±(99.9%) 0.074 ms/op
Iteration   1: 1.839 ±(99.9%) 0.034 ms/op
                 existUser·p0.00:   0.518 ms/op
                 existUser·p0.50:   1.784 ms/op
                 existUser·p0.90:   2.208 ms/op
                 existUser·p0.95:   2.355 ms/op
                 existUser·p0.99:   2.749 ms/op
                 existUser·p0.999:  31.531 ms/op
                 existUser·p0.9999: 32.171 ms/op
                 existUser·p1.00:   32.244 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17377
  mean =      1.839 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16944 
    [ 2.500,  5.000) = 364 
    [ 5.000,  7.500) = 37 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.518 ms/op
     p(50.0000) =      1.784 ms/op
     p(90.0000) =      2.208 ms/op
     p(95.0000) =      2.355 ms/op
     p(99.0000) =      2.749 ms/op
     p(99.9000) =     31.531 ms/op
     p(99.9900) =     32.171 ms/op
     p(99.9990) =     32.244 ms/op
     p(99.9999) =     32.244 ms/op
    p(100.0000) =     32.244 ms/op


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
# Warmup Iteration   1: 4.526 ±(99.9%) 0.106 ms/op
Iteration   1: 3.400 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.931 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   4.096 ms/op
                 getUser·p0.95:   4.399 ms/op
                 getUser·p0.99:   6.709 ms/op
                 getUser·p0.999:  10.790 ms/op
                 getUser·p0.9999: 10.928 ms/op
                 getUser·p1.00:   10.928 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9409
  mean =      3.400 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 1 
    [ 1.000,  2.000) = 149 
    [ 2.000,  3.000) = 2437 
    [ 3.000,  4.000) = 5562 
    [ 4.000,  5.000) = 1006 
    [ 5.000,  6.000) = 109 
    [ 6.000,  7.000) = 76 
    [ 7.000,  8.000) = 33 
    [ 8.000,  9.000) = 3 
    [ 9.000, 10.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.931 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      4.096 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      6.709 ms/op
     p(99.9000) =     10.790 ms/op
     p(99.9900) =     10.928 ms/op
     p(99.9990) =     10.928 ms/op
     p(99.9999) =     10.928 ms/op
    p(100.0000) =     10.928 ms/op


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
# Warmup Iteration   1: 10.891 ±(99.9%) 0.350 ms/op
Iteration   1: 8.317 ±(99.9%) 0.149 ms/op
                 listUser·p0.00:   3.035 ms/op
                 listUser·p0.50:   7.815 ms/op
                 listUser·p0.90:   10.833 ms/op
                 listUser·p0.95:   12.157 ms/op
                 listUser·p0.99:   18.889 ms/op
                 listUser·p0.999:  29.000 ms/op
                 listUser·p0.9999: 30.441 ms/op
                 listUser·p1.00:   30.441 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3853
  mean =      8.317 ±(99.9%) 0.149 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 99 
    [ 5.000,  7.500) = 1525 
    [ 7.500, 10.000) = 1636 
    [10.000, 12.500) = 426 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.035 ms/op
     p(50.0000) =      7.815 ms/op
     p(90.0000) =     10.833 ms/op
     p(95.0000) =     12.157 ms/op
     p(99.0000) =     18.889 ms/op
     p(99.9000) =     29.000 ms/op
     p(99.9900) =     30.441 ms/op
     p(99.9990) =     30.441 ms/op
     p(99.9999) =     30.441 ms/op
    p(100.0000) =     30.441 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.981          ops/ms
Client.existUser                       thrpt         11.455          ops/ms
Client.getUser                         thrpt          8.764          ops/ms
Client.listUser                        thrpt          3.621          ops/ms
Client.createUser                       avgt          3.451           ms/op
Client.existUser                        avgt          1.991           ms/op
Client.getUser                          avgt          2.925           ms/op
Client.listUser                         avgt          7.663           ms/op
Client.createUser                     sample  10680   2.989 ± 0.024   ms/op
Client.createUser:createUser·p0.00    sample          1.137           ms/op
Client.createUser:createUser·p0.50    sample          2.839           ms/op
Client.createUser:createUser·p0.90    sample          3.641           ms/op
Client.createUser:createUser·p0.95    sample          4.104           ms/op
Client.createUser:createUser·p0.99    sample          5.927           ms/op
Client.createUser:createUser·p0.999   sample          9.683           ms/op
Client.createUser:createUser·p0.9999  sample         11.364           ms/op
Client.createUser:createUser·p1.00    sample         11.469           ms/op
Client.existUser                      sample  17377   1.839 ± 0.034   ms/op
Client.existUser:existUser·p0.00      sample          0.518           ms/op
Client.existUser:existUser·p0.50      sample          1.784           ms/op
Client.existUser:existUser·p0.90      sample          2.208           ms/op
Client.existUser:existUser·p0.95      sample          2.355           ms/op
Client.existUser:existUser·p0.99      sample          2.749           ms/op
Client.existUser:existUser·p0.999     sample         31.531           ms/op
Client.existUser:existUser·p0.9999    sample         32.171           ms/op
Client.existUser:existUser·p1.00      sample         32.244           ms/op
Client.getUser                        sample   9409   3.400 ± 0.029   ms/op
Client.getUser:getUser·p0.00          sample          0.931           ms/op
Client.getUser:getUser·p0.50          sample          3.379           ms/op
Client.getUser:getUser·p0.90          sample          4.096           ms/op
Client.getUser:getUser·p0.95          sample          4.399           ms/op
Client.getUser:getUser·p0.99          sample          6.709           ms/op
Client.getUser:getUser·p0.999         sample         10.790           ms/op
Client.getUser:getUser·p0.9999        sample         10.928           ms/op
Client.getUser:getUser·p1.00          sample         10.928           ms/op
Client.listUser                       sample   3853   8.317 ± 0.149   ms/op
Client.listUser:listUser·p0.00        sample          3.035           ms/op
Client.listUser:listUser·p0.50        sample          7.815           ms/op
Client.listUser:listUser·p0.90        sample         10.833           ms/op
Client.listUser:listUser·p0.95        sample         12.157           ms/op
Client.listUser:listUser·p0.99        sample         18.889           ms/op
Client.listUser:listUser·p0.999       sample         29.000           ms/op
Client.listUser:listUser·p0.9999      sample         30.441           ms/op
Client.listUser:listUser·p1.00        sample         30.441           ms/op
