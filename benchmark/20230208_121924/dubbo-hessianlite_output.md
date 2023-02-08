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
# Warmup Iteration   1: 1.036 ops/ms
Iteration   1: 2.518 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.518 ops/ms


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
# Warmup Iteration   1: 2.962 ops/ms
Iteration   1: 6.835 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.835 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.267 ops/ms
Iteration   1: 4.375 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.375 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 0.900 ops/ms
Iteration   1: 1.477 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.477 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 19.706 ±(99.9%) 0.211 ms/op
Iteration   1: 9.002 ±(99.9%) 0.033 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  9.002 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 6.747 ±(99.9%) 0.084 ms/op
Iteration   1: 3.371 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.371 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 9.622 ±(99.9%) 0.142 ms/op
Iteration   1: 4.620 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.620 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 26.208 ±(99.9%) 0.382 ms/op
Iteration   1: 15.381 ±(99.9%) 0.068 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  15.381 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 12.129 ±(99.9%) 0.495 ms/op
Iteration   1: 4.882 ±(99.9%) 0.066 ms/op
                 createUser·p0.00:   2.929 ms/op
                 createUser·p0.50:   4.596 ms/op
                 createUser·p0.90:   5.022 ms/op
                 createUser·p0.95:   5.841 ms/op
                 createUser·p0.99:   10.502 ms/op
                 createUser·p0.999:  22.479 ms/op
                 createUser·p0.9999: 22.479 ms/op
                 createUser·p1.00:   22.479 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 6615
  mean =      4.882 ±(99.9%) 0.066 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 5909 
    [ 5.000,  7.500) = 483 
    [ 7.500, 10.000) = 148 
    [10.000, 12.500) = 10 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.929 ms/op
     p(50.0000) =      4.596 ms/op
     p(90.0000) =      5.022 ms/op
     p(95.0000) =      5.841 ms/op
     p(99.0000) =     10.502 ms/op
     p(99.9000) =     22.479 ms/op
     p(99.9900) =     22.479 ms/op
     p(99.9990) =     22.479 ms/op
     p(99.9999) =     22.479 ms/op
    p(100.0000) =     22.479 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 5.637 ±(99.9%) 0.183 ms/op
Iteration   1: 3.316 ±(99.9%) 0.054 ms/op
                 existUser·p0.00:   0.612 ms/op
                 existUser·p0.50:   3.101 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   4.547 ms/op
                 existUser·p0.99:   12.502 ms/op
                 existUser·p0.999:  18.250 ms/op
                 existUser·p0.9999: 21.496 ms/op
                 existUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 9673
  mean =      3.316 ±(99.9%) 0.054 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1000 
    [ 2.500,  5.000) = 8244 
    [ 5.000,  7.500) = 94 
    [ 7.500, 10.000) = 175 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.612 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =     12.502 ms/op
     p(99.9000) =     18.250 ms/op
     p(99.9900) =     21.496 ms/op
     p(99.9990) =     21.496 ms/op
     p(99.9999) =     21.496 ms/op
    p(100.0000) =     21.496 ms/op


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
# Warmup Iteration   1: 11.338 ±(99.9%) 0.361 ms/op
Iteration   1: 4.996 ±(99.9%) 0.082 ms/op
                 getUser·p0.00:   1.053 ms/op
                 getUser·p0.50:   4.907 ms/op
                 getUser·p0.90:   5.636 ms/op
                 getUser·p0.95:   6.218 ms/op
                 getUser·p0.99:   13.124 ms/op
                 getUser·p0.999:  27.918 ms/op
                 getUser·p0.9999: 28.049 ms/op
                 getUser·p1.00:   28.049 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6408
  mean =      4.996 ±(99.9%) 0.082 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 145 
    [ 2.500,  5.000) = 3918 
    [ 5.000,  7.500) = 2195 
    [ 7.500, 10.000) = 41 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.053 ms/op
     p(50.0000) =      4.907 ms/op
     p(90.0000) =      5.636 ms/op
     p(95.0000) =      6.218 ms/op
     p(99.0000) =     13.124 ms/op
     p(99.9000) =     27.918 ms/op
     p(99.9900) =     28.049 ms/op
     p(99.9990) =     28.049 ms/op
     p(99.9999) =     28.049 ms/op
    p(100.0000) =     28.049 ms/op


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
# Warmup Iteration   1: 24.422 ±(99.9%) 0.639 ms/op
Iteration   1: 16.081 ±(99.9%) 0.279 ms/op
                 listUser·p0.00:   5.145 ms/op
                 listUser·p0.50:   15.016 ms/op
                 listUser·p0.90:   20.251 ms/op
                 listUser·p0.95:   22.807 ms/op
                 listUser·p0.99:   30.019 ms/op
                 listUser·p0.999:  38.931 ms/op
                 listUser·p0.9999: 39.125 ms/op
                 listUser·p1.00:   39.125 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1988
  mean =     16.081 ±(99.9%) 0.279 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 10 
    [ 7.500, 10.000) = 25 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 889 
    [15.000, 17.500) = 507 
    [17.500, 20.000) = 245 
    [20.000, 22.500) = 137 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      5.145 ms/op
     p(50.0000) =     15.016 ms/op
     p(90.0000) =     20.251 ms/op
     p(95.0000) =     22.807 ms/op
     p(99.0000) =     30.019 ms/op
     p(99.9000) =     38.931 ms/op
     p(99.9900) =     39.125 ms/op
     p(99.9990) =     39.125 ms/op
     p(99.9999) =     39.125 ms/op
    p(100.0000) =     39.125 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.518          ops/ms
Client.existUser                       thrpt         6.835          ops/ms
Client.getUser                         thrpt         4.375          ops/ms
Client.listUser                        thrpt         1.477          ops/ms
Client.createUser                       avgt         9.002           ms/op
Client.existUser                        avgt         3.371           ms/op
Client.getUser                          avgt         4.620           ms/op
Client.listUser                         avgt        15.381           ms/op
Client.createUser                     sample  6615   4.882 ± 0.066   ms/op
Client.createUser:createUser·p0.00    sample         2.929           ms/op
Client.createUser:createUser·p0.50    sample         4.596           ms/op
Client.createUser:createUser·p0.90    sample         5.022           ms/op
Client.createUser:createUser·p0.95    sample         5.841           ms/op
Client.createUser:createUser·p0.99    sample        10.502           ms/op
Client.createUser:createUser·p0.999   sample        22.479           ms/op
Client.createUser:createUser·p0.9999  sample        22.479           ms/op
Client.createUser:createUser·p1.00    sample        22.479           ms/op
Client.existUser                      sample  9673   3.316 ± 0.054   ms/op
Client.existUser:existUser·p0.00      sample         0.612           ms/op
Client.existUser:existUser·p0.50      sample         3.101           ms/op
Client.existUser:existUser·p0.90      sample         3.539           ms/op
Client.existUser:existUser·p0.95      sample         4.547           ms/op
Client.existUser:existUser·p0.99      sample        12.502           ms/op
Client.existUser:existUser·p0.999     sample        18.250           ms/op
Client.existUser:existUser·p0.9999    sample        21.496           ms/op
Client.existUser:existUser·p1.00      sample        21.496           ms/op
Client.getUser                        sample  6408   4.996 ± 0.082   ms/op
Client.getUser:getUser·p0.00          sample         1.053           ms/op
Client.getUser:getUser·p0.50          sample         4.907           ms/op
Client.getUser:getUser·p0.90          sample         5.636           ms/op
Client.getUser:getUser·p0.95          sample         6.218           ms/op
Client.getUser:getUser·p0.99          sample        13.124           ms/op
Client.getUser:getUser·p0.999         sample        27.918           ms/op
Client.getUser:getUser·p0.9999        sample        28.049           ms/op
Client.getUser:getUser·p1.00          sample        28.049           ms/op
Client.listUser                       sample  1988  16.081 ± 0.279   ms/op
Client.listUser:listUser·p0.00        sample         5.145           ms/op
Client.listUser:listUser·p0.50        sample        15.016           ms/op
Client.listUser:listUser·p0.90        sample        20.251           ms/op
Client.listUser:listUser·p0.95        sample        22.807           ms/op
Client.listUser:listUser·p0.99        sample        30.019           ms/op
Client.listUser:listUser·p0.999       sample        38.931           ms/op
Client.listUser:listUser·p0.9999      sample        39.125           ms/op
Client.listUser:listUser·p1.00        sample        39.125           ms/op
