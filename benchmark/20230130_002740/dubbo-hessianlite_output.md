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
# Warmup Iteration   1: 1.083 ops/ms
Iteration   1: 2.361 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.361 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.795 ops/ms
Iteration   1: 6.249 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.249 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 1.623 ops/ms
Iteration   1: 4.029 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.029 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 0.856 ops/ms
Iteration   1: 1.409 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.409 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 17.429 ±(99.9%) 0.237 ms/op
Iteration   1: 8.530 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  8.530 ms/op


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
# Warmup Iteration   1: 8.291 ±(99.9%) 0.122 ms/op
Iteration   1: 4.293 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.293 ms/op


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
# Warmup Iteration   1: 13.472 ±(99.9%) 0.194 ms/op
Iteration   1: 4.892 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.892 ms/op


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
# Warmup Iteration   1: 29.357 ±(99.9%) 0.553 ms/op
Iteration   1: 18.312 ±(99.9%) 0.126 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  18.312 ms/op


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
# Warmup Iteration   1: 12.682 ±(99.9%) 0.438 ms/op
Iteration   1: 6.551 ±(99.9%) 0.096 ms/op
                 createUser·p0.00:   1.976 ms/op
                 createUser·p0.50:   6.578 ms/op
                 createUser·p0.90:   7.373 ms/op
                 createUser·p0.95:   9.712 ms/op
                 createUser·p0.99:   15.366 ms/op
                 createUser·p0.999:  19.366 ms/op
                 createUser·p0.9999: 19.399 ms/op
                 createUser·p1.00:   19.399 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4903
  mean =      6.551 ±(99.9%) 0.096 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 10 
    [ 2.500,  3.750) = 132 
    [ 3.750,  5.000) = 763 
    [ 5.000,  6.250) = 701 
    [ 6.250,  7.500) = 2860 
    [ 7.500,  8.750) = 180 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 36 
    [11.250, 12.500) = 79 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 49 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.976 ms/op
     p(50.0000) =      6.578 ms/op
     p(90.0000) =      7.373 ms/op
     p(95.0000) =      9.712 ms/op
     p(99.0000) =     15.366 ms/op
     p(99.9000) =     19.366 ms/op
     p(99.9900) =     19.399 ms/op
     p(99.9990) =     19.399 ms/op
     p(99.9999) =     19.399 ms/op
    p(100.0000) =     19.399 ms/op


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
# Warmup Iteration   1: 7.657 ±(99.9%) 0.220 ms/op
Iteration   1: 4.122 ±(99.9%) 0.109 ms/op
                 existUser·p0.00:   0.844 ms/op
                 existUser·p0.50:   3.666 ms/op
                 existUser·p0.90:   4.817 ms/op
                 existUser·p0.95:   7.149 ms/op
                 existUser·p0.99:   15.085 ms/op
                 existUser·p0.999:  35.127 ms/op
                 existUser·p0.9999: 35.389 ms/op
                 existUser·p1.00:   35.389 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 8048
  mean =      4.122 ±(99.9%) 0.109 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1093 
    [ 2.500,  5.000) = 6229 
    [ 5.000,  7.500) = 359 
    [ 7.500, 10.000) = 64 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 28 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.844 ms/op
     p(50.0000) =      3.666 ms/op
     p(90.0000) =      4.817 ms/op
     p(95.0000) =      7.149 ms/op
     p(99.0000) =     15.085 ms/op
     p(99.9000) =     35.127 ms/op
     p(99.9900) =     35.389 ms/op
     p(99.9990) =     35.389 ms/op
     p(99.9999) =     35.389 ms/op
    p(100.0000) =     35.389 ms/op


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
# Warmup Iteration   1: 9.454 ±(99.9%) 0.381 ms/op
Iteration   1: 4.894 ±(99.9%) 0.080 ms/op
                 getUser·p0.00:   1.053 ms/op
                 getUser·p0.50:   4.661 ms/op
                 getUser·p0.90:   5.500 ms/op
                 getUser·p0.95:   6.414 ms/op
                 getUser·p0.99:   14.252 ms/op
                 getUser·p0.999:  33.817 ms/op
                 getUser·p0.9999: 33.948 ms/op
                 getUser·p1.00:   33.948 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6655
  mean =      4.894 ±(99.9%) 0.080 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27 
    [ 2.500,  5.000) = 4957 
    [ 5.000,  7.500) = 1465 
    [ 7.500, 10.000) = 91 
    [10.000, 12.500) = 19 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.053 ms/op
     p(50.0000) =      4.661 ms/op
     p(90.0000) =      5.500 ms/op
     p(95.0000) =      6.414 ms/op
     p(99.0000) =     14.252 ms/op
     p(99.9000) =     33.817 ms/op
     p(99.9900) =     33.948 ms/op
     p(99.9990) =     33.948 ms/op
     p(99.9999) =     33.948 ms/op
    p(100.0000) =     33.948 ms/op


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
# Warmup Iteration   1: 31.975 ±(99.9%) 1.013 ms/op
Iteration   1: 19.760 ±(99.9%) 0.319 ms/op
                 listUser·p0.00:   9.191 ms/op
                 listUser·p0.50:   19.825 ms/op
                 listUser·p0.90:   23.003 ms/op
                 listUser·p0.95:   24.379 ms/op
                 listUser·p0.99:   35.652 ms/op
                 listUser·p0.999:  46.268 ms/op
                 listUser·p0.9999: 47.120 ms/op
                 listUser·p1.00:   47.120 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1649
  mean =     19.760 ±(99.9%) 0.319 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 0 
    [ 5.000, 10.000) = 6 
    [10.000, 15.000) = 178 
    [15.000, 20.000) = 726 
    [20.000, 25.000) = 665 
    [25.000, 30.000) = 44 
    [30.000, 35.000) = 13 
    [35.000, 40.000) = 10 
    [40.000, 45.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      9.191 ms/op
     p(50.0000) =     19.825 ms/op
     p(90.0000) =     23.003 ms/op
     p(95.0000) =     24.379 ms/op
     p(99.0000) =     35.652 ms/op
     p(99.9000) =     46.268 ms/op
     p(99.9900) =     47.120 ms/op
     p(99.9990) =     47.120 ms/op
     p(99.9999) =     47.120 ms/op
    p(100.0000) =     47.120 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.361          ops/ms
Client.existUser                       thrpt         6.249          ops/ms
Client.getUser                         thrpt         4.029          ops/ms
Client.listUser                        thrpt         1.409          ops/ms
Client.createUser                       avgt         8.530           ms/op
Client.existUser                        avgt         4.293           ms/op
Client.getUser                          avgt         4.892           ms/op
Client.listUser                         avgt        18.312           ms/op
Client.createUser                     sample  4903   6.551 ± 0.096   ms/op
Client.createUser:createUser·p0.00    sample         1.976           ms/op
Client.createUser:createUser·p0.50    sample         6.578           ms/op
Client.createUser:createUser·p0.90    sample         7.373           ms/op
Client.createUser:createUser·p0.95    sample         9.712           ms/op
Client.createUser:createUser·p0.99    sample        15.366           ms/op
Client.createUser:createUser·p0.999   sample        19.366           ms/op
Client.createUser:createUser·p0.9999  sample        19.399           ms/op
Client.createUser:createUser·p1.00    sample        19.399           ms/op
Client.existUser                      sample  8048   4.122 ± 0.109   ms/op
Client.existUser:existUser·p0.00      sample         0.844           ms/op
Client.existUser:existUser·p0.50      sample         3.666           ms/op
Client.existUser:existUser·p0.90      sample         4.817           ms/op
Client.existUser:existUser·p0.95      sample         7.149           ms/op
Client.existUser:existUser·p0.99      sample        15.085           ms/op
Client.existUser:existUser·p0.999     sample        35.127           ms/op
Client.existUser:existUser·p0.9999    sample        35.389           ms/op
Client.existUser:existUser·p1.00      sample        35.389           ms/op
Client.getUser                        sample  6655   4.894 ± 0.080   ms/op
Client.getUser:getUser·p0.00          sample         1.053           ms/op
Client.getUser:getUser·p0.50          sample         4.661           ms/op
Client.getUser:getUser·p0.90          sample         5.500           ms/op
Client.getUser:getUser·p0.95          sample         6.414           ms/op
Client.getUser:getUser·p0.99          sample        14.252           ms/op
Client.getUser:getUser·p0.999         sample        33.817           ms/op
Client.getUser:getUser·p0.9999        sample        33.948           ms/op
Client.getUser:getUser·p1.00          sample        33.948           ms/op
Client.listUser                       sample  1649  19.760 ± 0.319   ms/op
Client.listUser:listUser·p0.00        sample         9.191           ms/op
Client.listUser:listUser·p0.50        sample        19.825           ms/op
Client.listUser:listUser·p0.90        sample        23.003           ms/op
Client.listUser:listUser·p0.95        sample        24.379           ms/op
Client.listUser:listUser·p0.99        sample        35.652           ms/op
Client.listUser:listUser·p0.999       sample        46.268           ms/op
Client.listUser:listUser·p0.9999      sample        47.120           ms/op
Client.listUser:listUser·p1.00        sample        47.120           ms/op
