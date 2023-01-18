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
# Warmup Iteration   1: 1.088 ops/ms
Iteration   1: 2.347 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.347 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.688 ops/ms
Iteration   1: 5.491 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  5.491 ops/ms


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
# Warmup Iteration   1: 2.103 ops/ms
Iteration   1: 5.412 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.412 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 0.858 ops/ms
Iteration   1: 1.395 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.395 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:58
# Fork: 1 of 1
# Warmup Iteration   1: 18.846 ±(99.9%) 0.313 ms/op
Iteration   1: 7.849 ±(99.9%) 0.032 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  7.849 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:50
# Fork: 1 of 1
# Warmup Iteration   1: 7.845 ±(99.9%) 0.140 ms/op
Iteration   1: 4.082 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.082 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:43
# Fork: 1 of 1
# Warmup Iteration   1: 8.859 ±(99.9%) 0.147 ms/op
Iteration   1: 4.812 ±(99.9%) 0.030 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.812 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:36
# Fork: 1 of 1
# Warmup Iteration   1: 31.633 ±(99.9%) 0.578 ms/op
Iteration   1: 15.597 ±(99.9%) 0.045 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  15.597 ms/op


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
# Warmup Iteration   1: 10.319 ±(99.9%) 0.307 ms/op
Iteration   1: 5.742 ±(99.9%) 0.111 ms/op
                 createUser·p0.00:   2.005 ms/op
                 createUser·p0.50:   6.324 ms/op
                 createUser·p0.90:   7.274 ms/op
                 createUser·p0.95:   7.619 ms/op
                 createUser·p0.99:   13.337 ms/op
                 createUser·p0.999:  27.658 ms/op
                 createUser·p0.9999: 28.639 ms/op
                 createUser·p1.00:   28.639 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5568
  mean =      5.742 ±(99.9%) 0.111 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 409 
    [ 2.500,  5.000) = 1513 
    [ 5.000,  7.500) = 3333 
    [ 7.500, 10.000) = 142 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      2.005 ms/op
     p(50.0000) =      6.324 ms/op
     p(90.0000) =      7.274 ms/op
     p(95.0000) =      7.619 ms/op
     p(99.0000) =     13.337 ms/op
     p(99.9000) =     27.658 ms/op
     p(99.9900) =     28.639 ms/op
     p(99.9990) =     28.639 ms/op
     p(99.9999) =     28.639 ms/op
    p(100.0000) =     28.639 ms/op


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
# Warmup Iteration   1: 7.571 ±(99.9%) 0.253 ms/op
Iteration   1: 3.851 ±(99.9%) 0.082 ms/op
                 existUser·p0.00:   0.657 ms/op
                 existUser·p0.50:   3.621 ms/op
                 existUser·p0.90:   4.284 ms/op
                 existUser·p0.95:   5.743 ms/op
                 existUser·p0.99:   15.586 ms/op
                 existUser·p0.999:  26.018 ms/op
                 existUser·p0.9999: 26.608 ms/op
                 existUser·p1.00:   26.608 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 8317
  mean =      3.851 ±(99.9%) 0.082 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 789 
    [ 2.500,  5.000) = 6962 
    [ 5.000,  7.500) = 313 
    [ 7.500, 10.000) = 63 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.657 ms/op
     p(50.0000) =      3.621 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      5.743 ms/op
     p(99.0000) =     15.586 ms/op
     p(99.9000) =     26.018 ms/op
     p(99.9900) =     26.608 ms/op
     p(99.9990) =     26.608 ms/op
     p(99.9999) =     26.608 ms/op
    p(100.0000) =     26.608 ms/op


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
# Warmup Iteration   1: 11.102 ±(99.9%) 0.457 ms/op
Iteration   1: 4.713 ±(99.9%) 0.083 ms/op
                 getUser·p0.00:   1.178 ms/op
                 getUser·p0.50:   4.268 ms/op
                 getUser·p0.90:   6.308 ms/op
                 getUser·p0.95:   7.774 ms/op
                 getUser·p0.99:   14.094 ms/op
                 getUser·p0.999:  20.321 ms/op
                 getUser·p0.9999: 21.299 ms/op
                 getUser·p1.00:   21.299 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6839
  mean =      4.713 ±(99.9%) 0.083 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 89 
    [ 2.500,  5.000) = 4974 
    [ 5.000,  7.500) = 1368 
    [ 7.500, 10.000) = 217 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.178 ms/op
     p(50.0000) =      4.268 ms/op
     p(90.0000) =      6.308 ms/op
     p(95.0000) =      7.774 ms/op
     p(99.0000) =     14.094 ms/op
     p(99.9000) =     20.321 ms/op
     p(99.9900) =     21.299 ms/op
     p(99.9990) =     21.299 ms/op
     p(99.9999) =     21.299 ms/op
    p(100.0000) =     21.299 ms/op


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
# Warmup Iteration   1: 27.012 ±(99.9%) 0.696 ms/op
Iteration   1: 15.502 ±(99.9%) 0.169 ms/op
                 listUser·p0.00:   8.503 ms/op
                 listUser·p0.50:   14.959 ms/op
                 listUser·p0.90:   18.186 ms/op
                 listUser·p0.95:   19.300 ms/op
                 listUser·p0.99:   23.072 ms/op
                 listUser·p0.999:  28.738 ms/op
                 listUser·p0.9999: 29.164 ms/op
                 listUser·p1.00:   29.164 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2098
  mean =     15.502 ±(99.9%) 0.169 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 17 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 993 
    [15.000, 17.500) = 660 
    [17.500, 20.000) = 305 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      8.503 ms/op
     p(50.0000) =     14.959 ms/op
     p(90.0000) =     18.186 ms/op
     p(95.0000) =     19.300 ms/op
     p(99.0000) =     23.072 ms/op
     p(99.9000) =     28.738 ms/op
     p(99.9900) =     29.164 ms/op
     p(99.9990) =     29.164 ms/op
     p(99.9999) =     29.164 ms/op
    p(100.0000) =     29.164 ms/op


# Run complete. Total time: 00:01:27

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.347          ops/ms
Client.existUser                       thrpt         5.491          ops/ms
Client.getUser                         thrpt         5.412          ops/ms
Client.listUser                        thrpt         1.395          ops/ms
Client.createUser                       avgt         7.849           ms/op
Client.existUser                        avgt         4.082           ms/op
Client.getUser                          avgt         4.812           ms/op
Client.listUser                         avgt        15.597           ms/op
Client.createUser                     sample  5568   5.742 ± 0.111   ms/op
Client.createUser:createUser·p0.00    sample         2.005           ms/op
Client.createUser:createUser·p0.50    sample         6.324           ms/op
Client.createUser:createUser·p0.90    sample         7.274           ms/op
Client.createUser:createUser·p0.95    sample         7.619           ms/op
Client.createUser:createUser·p0.99    sample        13.337           ms/op
Client.createUser:createUser·p0.999   sample        27.658           ms/op
Client.createUser:createUser·p0.9999  sample        28.639           ms/op
Client.createUser:createUser·p1.00    sample        28.639           ms/op
Client.existUser                      sample  8317   3.851 ± 0.082   ms/op
Client.existUser:existUser·p0.00      sample         0.657           ms/op
Client.existUser:existUser·p0.50      sample         3.621           ms/op
Client.existUser:existUser·p0.90      sample         4.284           ms/op
Client.existUser:existUser·p0.95      sample         5.743           ms/op
Client.existUser:existUser·p0.99      sample        15.586           ms/op
Client.existUser:existUser·p0.999     sample        26.018           ms/op
Client.existUser:existUser·p0.9999    sample        26.608           ms/op
Client.existUser:existUser·p1.00      sample        26.608           ms/op
Client.getUser                        sample  6839   4.713 ± 0.083   ms/op
Client.getUser:getUser·p0.00          sample         1.178           ms/op
Client.getUser:getUser·p0.50          sample         4.268           ms/op
Client.getUser:getUser·p0.90          sample         6.308           ms/op
Client.getUser:getUser·p0.95          sample         7.774           ms/op
Client.getUser:getUser·p0.99          sample        14.094           ms/op
Client.getUser:getUser·p0.999         sample        20.321           ms/op
Client.getUser:getUser·p0.9999        sample        21.299           ms/op
Client.getUser:getUser·p1.00          sample        21.299           ms/op
Client.listUser                       sample  2098  15.502 ± 0.169   ms/op
Client.listUser:listUser·p0.00        sample         8.503           ms/op
Client.listUser:listUser·p0.50        sample        14.959           ms/op
Client.listUser:listUser·p0.90        sample        18.186           ms/op
Client.listUser:listUser·p0.95        sample        19.300           ms/op
Client.listUser:listUser·p0.99        sample        23.072           ms/op
Client.listUser:listUser·p0.999       sample        28.738           ms/op
Client.listUser:listUser·p0.9999      sample        29.164           ms/op
Client.listUser:listUser·p1.00        sample        29.164           ms/op
