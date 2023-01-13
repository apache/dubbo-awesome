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
# Warmup Iteration   1: 1.276 ops/ms
Iteration   1: 2.614 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.614 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.368 ops/ms
Iteration   1: 9.245 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  9.245 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 1.858 ops/ms
Iteration   1: 5.465 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.465 ops/ms


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
# Warmup Iteration   1: 1.010 ops/ms
Iteration   1: 1.506 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.506 ops/ms


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
# Warmup Iteration   1: 16.379 ±(99.9%) 0.300 ms/op
Iteration   1: 6.839 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.839 ms/op


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
# Warmup Iteration   1: 7.066 ±(99.9%) 0.111 ms/op
Iteration   1: 3.850 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.850 ms/op


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
# Warmup Iteration   1: 9.664 ±(99.9%) 0.166 ms/op
Iteration   1: 4.490 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.490 ms/op


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
# Warmup Iteration   1: 25.247 ±(99.9%) 0.374 ms/op
Iteration   1: 16.108 ±(99.9%) 0.053 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  16.108 ms/op


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
# Warmup Iteration   1: 8.687 ±(99.9%) 0.380 ms/op
Iteration   1: 5.695 ±(99.9%) 0.119 ms/op
                 createUser·p0.00:   1.827 ms/op
                 createUser·p0.50:   5.349 ms/op
                 createUser·p0.90:   6.537 ms/op
                 createUser·p0.95:   10.509 ms/op
                 createUser·p0.99:   13.697 ms/op
                 createUser·p0.999:  32.952 ms/op
                 createUser·p0.9999: 33.456 ms/op
                 createUser·p1.00:   33.456 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5691
  mean =      5.695 ±(99.9%) 0.119 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 200 
    [ 2.500,  5.000) = 845 
    [ 5.000,  7.500) = 4127 
    [ 7.500, 10.000) = 201 
    [10.000, 12.500) = 203 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.827 ms/op
     p(50.0000) =      5.349 ms/op
     p(90.0000) =      6.537 ms/op
     p(95.0000) =     10.509 ms/op
     p(99.0000) =     13.697 ms/op
     p(99.9000) =     32.952 ms/op
     p(99.9900) =     33.456 ms/op
     p(99.9990) =     33.456 ms/op
     p(99.9999) =     33.456 ms/op
    p(100.0000) =     33.456 ms/op


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
# Warmup Iteration   1: 6.687 ±(99.9%) 0.208 ms/op
Iteration   1: 3.820 ±(99.9%) 0.053 ms/op
                 existUser·p0.00:   0.801 ms/op
                 existUser·p0.50:   4.092 ms/op
                 existUser·p0.90:   4.432 ms/op
                 existUser·p0.95:   4.506 ms/op
                 existUser·p0.99:   5.964 ms/op
                 existUser·p0.999:  21.742 ms/op
                 existUser·p0.9999: 21.889 ms/op
                 existUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 8476
  mean =      3.820 ±(99.9%) 0.053 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1262 
    [ 2.500,  5.000) = 7050 
    [ 5.000,  7.500) = 99 
    [ 7.500, 10.000) = 34 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.801 ms/op
     p(50.0000) =      4.092 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      5.964 ms/op
     p(99.9000) =     21.742 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 8.881 ±(99.9%) 0.318 ms/op
Iteration   1: 4.912 ±(99.9%) 0.072 ms/op
                 getUser·p0.00:   1.526 ms/op
                 getUser·p0.50:   4.809 ms/op
                 getUser·p0.90:   5.559 ms/op
                 getUser·p0.95:   6.214 ms/op
                 getUser·p0.99:   12.705 ms/op
                 getUser·p0.999:  22.184 ms/op
                 getUser·p0.9999: 22.413 ms/op
                 getUser·p1.00:   22.413 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6553
  mean =      4.912 ±(99.9%) 0.072 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 106 
    [ 2.500,  5.000) = 4134 
    [ 5.000,  7.500) = 2123 
    [ 7.500, 10.000) = 72 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.526 ms/op
     p(50.0000) =      4.809 ms/op
     p(90.0000) =      5.559 ms/op
     p(95.0000) =      6.214 ms/op
     p(99.0000) =     12.705 ms/op
     p(99.9000) =     22.184 ms/op
     p(99.9900) =     22.413 ms/op
     p(99.9990) =     22.413 ms/op
     p(99.9999) =     22.413 ms/op
    p(100.0000) =     22.413 ms/op


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
# Warmup Iteration   1: 27.753 ±(99.9%) 0.862 ms/op
Iteration   1: 16.268 ±(99.9%) 0.182 ms/op
                 listUser·p0.00:   3.793 ms/op
                 listUser·p0.50:   15.860 ms/op
                 listUser·p0.90:   17.924 ms/op
                 listUser·p0.95:   18.494 ms/op
                 listUser·p0.99:   28.150 ms/op
                 listUser·p0.999:  30.901 ms/op
                 listUser·p0.9999: 30.999 ms/op
                 listUser·p1.00:   30.999 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1991
  mean =     16.268 ±(99.9%) 0.182 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 4 
    [ 5.000,  7.500) = 20 
    [ 7.500, 10.000) = 10 
    [10.000, 12.500) = 18 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 1576 
    [17.500, 20.000) = 232 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.793 ms/op
     p(50.0000) =     15.860 ms/op
     p(90.0000) =     17.924 ms/op
     p(95.0000) =     18.494 ms/op
     p(99.0000) =     28.150 ms/op
     p(99.9000) =     30.901 ms/op
     p(99.9900) =     30.999 ms/op
     p(99.9990) =     30.999 ms/op
     p(99.9999) =     30.999 ms/op
    p(100.0000) =     30.999 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.614          ops/ms
Client.existUser                       thrpt         9.245          ops/ms
Client.getUser                         thrpt         5.465          ops/ms
Client.listUser                        thrpt         1.506          ops/ms
Client.createUser                       avgt         6.839           ms/op
Client.existUser                        avgt         3.850           ms/op
Client.getUser                          avgt         4.490           ms/op
Client.listUser                         avgt        16.108           ms/op
Client.createUser                     sample  5691   5.695 ± 0.119   ms/op
Client.createUser:createUser·p0.00    sample         1.827           ms/op
Client.createUser:createUser·p0.50    sample         5.349           ms/op
Client.createUser:createUser·p0.90    sample         6.537           ms/op
Client.createUser:createUser·p0.95    sample        10.509           ms/op
Client.createUser:createUser·p0.99    sample        13.697           ms/op
Client.createUser:createUser·p0.999   sample        32.952           ms/op
Client.createUser:createUser·p0.9999  sample        33.456           ms/op
Client.createUser:createUser·p1.00    sample        33.456           ms/op
Client.existUser                      sample  8476   3.820 ± 0.053   ms/op
Client.existUser:existUser·p0.00      sample         0.801           ms/op
Client.existUser:existUser·p0.50      sample         4.092           ms/op
Client.existUser:existUser·p0.90      sample         4.432           ms/op
Client.existUser:existUser·p0.95      sample         4.506           ms/op
Client.existUser:existUser·p0.99      sample         5.964           ms/op
Client.existUser:existUser·p0.999     sample        21.742           ms/op
Client.existUser:existUser·p0.9999    sample        21.889           ms/op
Client.existUser:existUser·p1.00      sample        21.889           ms/op
Client.getUser                        sample  6553   4.912 ± 0.072   ms/op
Client.getUser:getUser·p0.00          sample         1.526           ms/op
Client.getUser:getUser·p0.50          sample         4.809           ms/op
Client.getUser:getUser·p0.90          sample         5.559           ms/op
Client.getUser:getUser·p0.95          sample         6.214           ms/op
Client.getUser:getUser·p0.99          sample        12.705           ms/op
Client.getUser:getUser·p0.999         sample        22.184           ms/op
Client.getUser:getUser·p0.9999        sample        22.413           ms/op
Client.getUser:getUser·p1.00          sample        22.413           ms/op
Client.listUser                       sample  1991  16.268 ± 0.182   ms/op
Client.listUser:listUser·p0.00        sample         3.793           ms/op
Client.listUser:listUser·p0.50        sample        15.860           ms/op
Client.listUser:listUser·p0.90        sample        17.924           ms/op
Client.listUser:listUser·p0.95        sample        18.494           ms/op
Client.listUser:listUser·p0.99        sample        28.150           ms/op
Client.listUser:listUser·p0.999       sample        30.901           ms/op
Client.listUser:listUser·p0.9999      sample        30.999           ms/op
Client.listUser:listUser·p1.00        sample        30.999           ms/op
