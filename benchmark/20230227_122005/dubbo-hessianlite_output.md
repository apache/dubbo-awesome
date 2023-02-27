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
# Warmup Iteration   1: 1.066 ops/ms
Iteration   1: 3.340 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.340 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 3.508 ops/ms
Iteration   1: 5.670 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  5.670 ops/ms


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
# Warmup Iteration   1: 2.659 ops/ms
Iteration   1: 5.634 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.634 ops/ms


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
# Warmup Iteration   1: 0.901 ops/ms
Iteration   1: 1.699 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.699 ops/ms


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
# Warmup Iteration   1: 17.225 ±(99.9%) 0.433 ms/op
Iteration   1: 7.708 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  7.708 ms/op


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
# Warmup Iteration   1: 7.020 ±(99.9%) 0.299 ms/op
Iteration   1: 4.233 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.233 ms/op


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
# Warmup Iteration   1: 12.171 ±(99.9%) 0.138 ms/op
Iteration   1: 4.671 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.671 ms/op


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
# Warmup Iteration   1: 25.205 ±(99.9%) 0.280 ms/op
Iteration   1: 17.764 ±(99.9%) 0.148 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  17.764 ms/op


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
# Warmup Iteration   1: 10.553 ±(99.9%) 0.341 ms/op
Iteration   1: 4.889 ±(99.9%) 0.150 ms/op
                 createUser·p0.00:   1.268 ms/op
                 createUser·p0.50:   4.051 ms/op
                 createUser·p0.90:   6.187 ms/op
                 createUser·p0.95:   9.406 ms/op
                 createUser·p0.99:   20.522 ms/op
                 createUser·p0.999:  40.587 ms/op
                 createUser·p0.9999: 41.222 ms/op
                 createUser·p1.00:   41.222 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 6517
  mean =      4.889 ±(99.9%) 0.150 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 3920 
    [ 5.000, 10.000) = 2295 
    [10.000, 15.000) = 174 
    [15.000, 20.000) = 51 
    [20.000, 25.000) = 45 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 15 
    [40.000, 45.000) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.268 ms/op
     p(50.0000) =      4.051 ms/op
     p(90.0000) =      6.187 ms/op
     p(95.0000) =      9.406 ms/op
     p(99.0000) =     20.522 ms/op
     p(99.9000) =     40.587 ms/op
     p(99.9900) =     41.222 ms/op
     p(99.9990) =     41.222 ms/op
     p(99.9999) =     41.222 ms/op
    p(100.0000) =     41.222 ms/op


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
# Warmup Iteration   1: 5.615 ±(99.9%) 0.171 ms/op
Iteration   1: 3.491 ±(99.9%) 0.043 ms/op
                 existUser·p0.00:   0.650 ms/op
                 existUser·p0.50:   3.437 ms/op
                 existUser·p0.90:   3.932 ms/op
                 existUser·p0.95:   5.056 ms/op
                 existUser·p0.99:   9.863 ms/op
                 existUser·p0.999:  12.833 ms/op
                 existUser·p0.9999: 15.254 ms/op
                 existUser·p1.00:   15.254 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 9176
  mean =      3.491 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 509 
    [ 2.500,  3.750) = 7334 
    [ 3.750,  5.000) = 824 
    [ 5.000,  6.250) = 205 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 47 
    [ 8.750, 10.000) = 113 
    [10.000, 11.250) = 47 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.650 ms/op
     p(50.0000) =      3.437 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      5.056 ms/op
     p(99.0000) =      9.863 ms/op
     p(99.9000) =     12.833 ms/op
     p(99.9900) =     15.254 ms/op
     p(99.9990) =     15.254 ms/op
     p(99.9999) =     15.254 ms/op
    p(100.0000) =     15.254 ms/op


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
# Warmup Iteration   1: 9.060 ±(99.9%) 0.372 ms/op
Iteration   1: 4.508 ±(99.9%) 0.084 ms/op
                 getUser·p0.00:   1.311 ms/op
                 getUser·p0.50:   3.969 ms/op
                 getUser·p0.90:   6.341 ms/op
                 getUser·p0.95:   7.816 ms/op
                 getUser·p0.99:   11.223 ms/op
                 getUser·p0.999:  24.997 ms/op
                 getUser·p0.9999: 25.428 ms/op
                 getUser·p1.00:   25.428 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7138
  mean =      4.508 ±(99.9%) 0.084 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 173 
    [ 2.500,  5.000) = 4840 
    [ 5.000,  7.500) = 1753 
    [ 7.500, 10.000) = 238 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.311 ms/op
     p(50.0000) =      3.969 ms/op
     p(90.0000) =      6.341 ms/op
     p(95.0000) =      7.816 ms/op
     p(99.0000) =     11.223 ms/op
     p(99.9000) =     24.997 ms/op
     p(99.9900) =     25.428 ms/op
     p(99.9990) =     25.428 ms/op
     p(99.9999) =     25.428 ms/op
    p(100.0000) =     25.428 ms/op


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
# Warmup Iteration   1: 25.637 ±(99.9%) 0.887 ms/op
Iteration   1: 17.697 ±(99.9%) 0.274 ms/op
                 listUser·p0.00:   5.046 ms/op
                 listUser·p0.50:   18.022 ms/op
                 listUser·p0.90:   20.480 ms/op
                 listUser·p0.95:   22.086 ms/op
                 listUser·p0.99:   28.541 ms/op
                 listUser·p0.999:  38.492 ms/op
                 listUser·p0.9999: 39.191 ms/op
                 listUser·p1.00:   39.191 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1819
  mean =     17.697 ±(99.9%) 0.274 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 10 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 239 
    [15.000, 17.500) = 395 
    [17.500, 20.000) = 821 
    [20.000, 22.500) = 176 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      5.046 ms/op
     p(50.0000) =     18.022 ms/op
     p(90.0000) =     20.480 ms/op
     p(95.0000) =     22.086 ms/op
     p(99.0000) =     28.541 ms/op
     p(99.9000) =     38.492 ms/op
     p(99.9900) =     39.191 ms/op
     p(99.9990) =     39.191 ms/op
     p(99.9999) =     39.191 ms/op
    p(100.0000) =     39.191 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         3.340          ops/ms
Client.existUser                       thrpt         5.670          ops/ms
Client.getUser                         thrpt         5.634          ops/ms
Client.listUser                        thrpt         1.699          ops/ms
Client.createUser                       avgt         7.708           ms/op
Client.existUser                        avgt         4.233           ms/op
Client.getUser                          avgt         4.671           ms/op
Client.listUser                         avgt        17.764           ms/op
Client.createUser                     sample  6517   4.889 ± 0.150   ms/op
Client.createUser:createUser·p0.00    sample         1.268           ms/op
Client.createUser:createUser·p0.50    sample         4.051           ms/op
Client.createUser:createUser·p0.90    sample         6.187           ms/op
Client.createUser:createUser·p0.95    sample         9.406           ms/op
Client.createUser:createUser·p0.99    sample        20.522           ms/op
Client.createUser:createUser·p0.999   sample        40.587           ms/op
Client.createUser:createUser·p0.9999  sample        41.222           ms/op
Client.createUser:createUser·p1.00    sample        41.222           ms/op
Client.existUser                      sample  9176   3.491 ± 0.043   ms/op
Client.existUser:existUser·p0.00      sample         0.650           ms/op
Client.existUser:existUser·p0.50      sample         3.437           ms/op
Client.existUser:existUser·p0.90      sample         3.932           ms/op
Client.existUser:existUser·p0.95      sample         5.056           ms/op
Client.existUser:existUser·p0.99      sample         9.863           ms/op
Client.existUser:existUser·p0.999     sample        12.833           ms/op
Client.existUser:existUser·p0.9999    sample        15.254           ms/op
Client.existUser:existUser·p1.00      sample        15.254           ms/op
Client.getUser                        sample  7138   4.508 ± 0.084   ms/op
Client.getUser:getUser·p0.00          sample         1.311           ms/op
Client.getUser:getUser·p0.50          sample         3.969           ms/op
Client.getUser:getUser·p0.90          sample         6.341           ms/op
Client.getUser:getUser·p0.95          sample         7.816           ms/op
Client.getUser:getUser·p0.99          sample        11.223           ms/op
Client.getUser:getUser·p0.999         sample        24.997           ms/op
Client.getUser:getUser·p0.9999        sample        25.428           ms/op
Client.getUser:getUser·p1.00          sample        25.428           ms/op
Client.listUser                       sample  1819  17.697 ± 0.274   ms/op
Client.listUser:listUser·p0.00        sample         5.046           ms/op
Client.listUser:listUser·p0.50        sample        18.022           ms/op
Client.listUser:listUser·p0.90        sample        20.480           ms/op
Client.listUser:listUser·p0.95        sample        22.086           ms/op
Client.listUser:listUser·p0.99        sample        28.541           ms/op
Client.listUser:listUser·p0.999       sample        38.492           ms/op
Client.listUser:listUser·p0.9999      sample        39.191           ms/op
Client.listUser:listUser·p1.00        sample        39.191           ms/op
