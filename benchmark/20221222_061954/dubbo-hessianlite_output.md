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
# Warmup Iteration   1: 1.094 ops/ms
Iteration   1: 2.325 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.325 ops/ms


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
# Warmup Iteration   1: 3.177 ops/ms
Iteration   1: 7.617 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  7.617 ops/ms


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
# Warmup Iteration   1: 2.360 ops/ms
Iteration   1: 5.206 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.206 ops/ms


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
# Warmup Iteration   1: 0.973 ops/ms
Iteration   1: 1.561 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.561 ops/ms


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
# Warmup Iteration   1: 13.438 ±(99.9%) 0.216 ms/op
Iteration   1: 7.231 ±(99.9%) 0.032 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  7.231 ms/op


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
# Warmup Iteration   1: 6.159 ±(99.9%) 0.059 ms/op
Iteration   1: 3.264 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.264 ms/op


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
# Warmup Iteration   1: 8.769 ±(99.9%) 0.143 ms/op
Iteration   1: 4.819 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.819 ms/op


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
# Warmup Iteration   1: 28.321 ±(99.9%) 0.623 ms/op
Iteration   1: 15.437 ±(99.9%) 0.056 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  15.437 ms/op


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
# Warmup Iteration   1: 12.608 ±(99.9%) 0.474 ms/op
Iteration   1: 6.091 ±(99.9%) 0.110 ms/op
                 createUser·p0.00:   0.378 ms/op
                 createUser·p0.50:   6.062 ms/op
                 createUser·p0.90:   6.742 ms/op
                 createUser·p0.95:   7.176 ms/op
                 createUser·p0.99:   13.981 ms/op
                 createUser·p0.999:  32.342 ms/op
                 createUser·p0.9999: 32.375 ms/op
                 createUser·p1.00:   32.375 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5265
  mean =      6.091 ±(99.9%) 0.110 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 1363 
    [ 5.000,  7.500) = 3638 
    [ 7.500, 10.000) = 155 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 63 
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
      p(0.0000) =      0.378 ms/op
     p(50.0000) =      6.062 ms/op
     p(90.0000) =      6.742 ms/op
     p(95.0000) =      7.176 ms/op
     p(99.0000) =     13.981 ms/op
     p(99.9000) =     32.342 ms/op
     p(99.9900) =     32.375 ms/op
     p(99.9990) =     32.375 ms/op
     p(99.9999) =     32.375 ms/op
    p(100.0000) =     32.375 ms/op


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
# Warmup Iteration   1: 5.472 ±(99.9%) 0.170 ms/op
Iteration   1: 3.488 ±(99.9%) 0.066 ms/op
                 existUser·p0.00:   0.650 ms/op
                 existUser·p0.50:   3.035 ms/op
                 existUser·p0.90:   4.211 ms/op
                 existUser·p0.95:   5.335 ms/op
                 existUser·p0.99:   12.730 ms/op
                 existUser·p0.999:  24.019 ms/op
                 existUser·p0.9999: 24.740 ms/op
                 existUser·p1.00:   24.740 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 9173
  mean =      3.488 ±(99.9%) 0.066 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1250 
    [ 2.500,  5.000) = 7398 
    [ 5.000,  7.500) = 205 
    [ 7.500, 10.000) = 113 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.650 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      5.335 ms/op
     p(99.0000) =     12.730 ms/op
     p(99.9000) =     24.019 ms/op
     p(99.9900) =     24.740 ms/op
     p(99.9990) =     24.740 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


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
# Warmup Iteration   1: 10.531 ±(99.9%) 0.465 ms/op
Iteration   1: 4.520 ±(99.9%) 0.072 ms/op
                 getUser·p0.00:   1.427 ms/op
                 getUser·p0.50:   4.268 ms/op
                 getUser·p0.90:   5.317 ms/op
                 getUser·p0.95:   5.923 ms/op
                 getUser·p0.99:   15.450 ms/op
                 getUser·p0.999:  21.459 ms/op
                 getUser·p0.9999: 21.889 ms/op
                 getUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7112
  mean =      4.520 ±(99.9%) 0.072 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 52 
    [ 2.500,  5.000) = 6042 
    [ 5.000,  7.500) = 851 
    [ 7.500, 10.000) = 69 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.427 ms/op
     p(50.0000) =      4.268 ms/op
     p(90.0000) =      5.317 ms/op
     p(95.0000) =      5.923 ms/op
     p(99.0000) =     15.450 ms/op
     p(99.9000) =     21.459 ms/op
     p(99.9900) =     21.889 ms/op
     p(99.9990) =     21.889 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


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
# Warmup Iteration   1: 25.682 ±(99.9%) 0.637 ms/op
Iteration   1: 16.231 ±(99.9%) 0.284 ms/op
                 listUser·p0.00:   5.480 ms/op
                 listUser·p0.50:   15.909 ms/op
                 listUser·p0.90:   21.168 ms/op
                 listUser·p0.95:   22.413 ms/op
                 listUser·p0.99:   29.839 ms/op
                 listUser·p0.999:  35.586 ms/op
                 listUser·p0.9999: 35.586 ms/op
                 listUser·p1.00:   35.586 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1991
  mean =     16.231 ±(99.9%) 0.284 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 1 
    [ 7.500, 10.000) = 46 
    [10.000, 12.500) = 212 
    [12.500, 15.000) = 580 
    [15.000, 17.500) = 448 
    [17.500, 20.000) = 434 
    [20.000, 22.500) = 174 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      5.480 ms/op
     p(50.0000) =     15.909 ms/op
     p(90.0000) =     21.168 ms/op
     p(95.0000) =     22.413 ms/op
     p(99.0000) =     29.839 ms/op
     p(99.9000) =     35.586 ms/op
     p(99.9900) =     35.586 ms/op
     p(99.9990) =     35.586 ms/op
     p(99.9999) =     35.586 ms/op
    p(100.0000) =     35.586 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.325          ops/ms
Client.existUser                       thrpt         7.617          ops/ms
Client.getUser                         thrpt         5.206          ops/ms
Client.listUser                        thrpt         1.561          ops/ms
Client.createUser                       avgt         7.231           ms/op
Client.existUser                        avgt         3.264           ms/op
Client.getUser                          avgt         4.819           ms/op
Client.listUser                         avgt        15.437           ms/op
Client.createUser                     sample  5265   6.091 ± 0.110   ms/op
Client.createUser:createUser·p0.00    sample         0.378           ms/op
Client.createUser:createUser·p0.50    sample         6.062           ms/op
Client.createUser:createUser·p0.90    sample         6.742           ms/op
Client.createUser:createUser·p0.95    sample         7.176           ms/op
Client.createUser:createUser·p0.99    sample        13.981           ms/op
Client.createUser:createUser·p0.999   sample        32.342           ms/op
Client.createUser:createUser·p0.9999  sample        32.375           ms/op
Client.createUser:createUser·p1.00    sample        32.375           ms/op
Client.existUser                      sample  9173   3.488 ± 0.066   ms/op
Client.existUser:existUser·p0.00      sample         0.650           ms/op
Client.existUser:existUser·p0.50      sample         3.035           ms/op
Client.existUser:existUser·p0.90      sample         4.211           ms/op
Client.existUser:existUser·p0.95      sample         5.335           ms/op
Client.existUser:existUser·p0.99      sample        12.730           ms/op
Client.existUser:existUser·p0.999     sample        24.019           ms/op
Client.existUser:existUser·p0.9999    sample        24.740           ms/op
Client.existUser:existUser·p1.00      sample        24.740           ms/op
Client.getUser                        sample  7112   4.520 ± 0.072   ms/op
Client.getUser:getUser·p0.00          sample         1.427           ms/op
Client.getUser:getUser·p0.50          sample         4.268           ms/op
Client.getUser:getUser·p0.90          sample         5.317           ms/op
Client.getUser:getUser·p0.95          sample         5.923           ms/op
Client.getUser:getUser·p0.99          sample        15.450           ms/op
Client.getUser:getUser·p0.999         sample        21.459           ms/op
Client.getUser:getUser·p0.9999        sample        21.889           ms/op
Client.getUser:getUser·p1.00          sample        21.889           ms/op
Client.listUser                       sample  1991  16.231 ± 0.284   ms/op
Client.listUser:listUser·p0.00        sample         5.480           ms/op
Client.listUser:listUser·p0.50        sample        15.909           ms/op
Client.listUser:listUser·p0.90        sample        21.168           ms/op
Client.listUser:listUser·p0.95        sample        22.413           ms/op
Client.listUser:listUser·p0.99        sample        29.839           ms/op
Client.listUser:listUser·p0.999       sample        35.586           ms/op
Client.listUser:listUser·p0.9999      sample        35.586           ms/op
Client.listUser:listUser·p1.00        sample        35.586           ms/op
