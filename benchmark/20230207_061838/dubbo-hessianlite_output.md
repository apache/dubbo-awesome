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
# Warmup Iteration   1: 1.229 ops/ms
Iteration   1: 2.801 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.801 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 3.691 ops/ms
Iteration   1: 5.854 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  5.854 ops/ms


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
# Warmup Iteration   1: 2.961 ops/ms
Iteration   1: 5.517 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.517 ops/ms


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
# Warmup Iteration   1: 0.874 ops/ms
Iteration   1: 1.452 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.452 ops/ms


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
# Warmup Iteration   1: 15.887 ±(99.9%) 0.297 ms/op
Iteration   1: 6.649 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.649 ms/op


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
# Warmup Iteration   1: 6.954 ±(99.9%) 0.094 ms/op
Iteration   1: 3.771 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.771 ms/op


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
# Warmup Iteration   1: 8.402 ±(99.9%) 0.136 ms/op
Iteration   1: 4.002 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.002 ms/op


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
# Warmup Iteration   1: 30.687 ±(99.9%) 0.296 ms/op
Iteration   1: 14.587 ±(99.9%) 0.030 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  14.587 ms/op


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
# Warmup Iteration   1: 10.563 ±(99.9%) 0.322 ms/op
Iteration   1: 6.282 ±(99.9%) 0.077 ms/op
                 createUser·p0.00:   2.552 ms/op
                 createUser·p0.50:   5.988 ms/op
                 createUser·p0.90:   7.293 ms/op
                 createUser·p0.95:   10.043 ms/op
                 createUser·p0.99:   13.127 ms/op
                 createUser·p0.999:  18.776 ms/op
                 createUser·p0.9999: 19.628 ms/op
                 createUser·p1.00:   19.628 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5077
  mean =      6.282 ±(99.9%) 0.077 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 0 
    [ 2.500,  3.750) = 1 
    [ 3.750,  5.000) = 0 
    [ 5.000,  6.250) = 3989 
    [ 6.250,  7.500) = 640 
    [ 7.500,  8.750) = 80 
    [ 8.750, 10.000) = 96 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 115 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 33 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.552 ms/op
     p(50.0000) =      5.988 ms/op
     p(90.0000) =      7.293 ms/op
     p(95.0000) =     10.043 ms/op
     p(99.0000) =     13.127 ms/op
     p(99.9000) =     18.776 ms/op
     p(99.9900) =     19.628 ms/op
     p(99.9990) =     19.628 ms/op
     p(99.9999) =     19.628 ms/op
    p(100.0000) =     19.628 ms/op


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
# Warmup Iteration   1: 6.801 ±(99.9%) 0.209 ms/op
Iteration   1: 3.196 ±(99.9%) 0.055 ms/op
                 existUser·p0.00:   0.680 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   4.293 ms/op
                 existUser·p0.99:   9.781 ms/op
                 existUser·p0.999:  24.473 ms/op
                 existUser·p0.9999: 24.870 ms/op
                 existUser·p1.00:   24.871 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 10146
  mean =      3.196 ±(99.9%) 0.055 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1154 
    [ 2.500,  5.000) = 8654 
    [ 5.000,  7.500) = 142 
    [ 7.500, 10.000) = 101 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.680 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      9.781 ms/op
     p(99.9000) =     24.473 ms/op
     p(99.9900) =     24.870 ms/op
     p(99.9990) =     24.871 ms/op
     p(99.9999) =     24.871 ms/op
    p(100.0000) =     24.871 ms/op


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
# Warmup Iteration   1: 8.476 ±(99.9%) 0.338 ms/op
Iteration   1: 3.851 ±(99.9%) 0.046 ms/op
                 getUser·p0.00:   0.920 ms/op
                 getUser·p0.50:   3.719 ms/op
                 getUser·p0.90:   4.899 ms/op
                 getUser·p0.95:   5.235 ms/op
                 getUser·p0.99:   8.706 ms/op
                 getUser·p0.999:  16.777 ms/op
                 getUser·p0.9999: 16.843 ms/op
                 getUser·p1.00:   16.843 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 8379
  mean =      3.851 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 11 
    [ 1.250,  2.500) = 393 
    [ 2.500,  3.750) = 3946 
    [ 3.750,  5.000) = 3353 
    [ 5.000,  6.250) = 498 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 77 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.920 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.899 ms/op
     p(95.0000) =      5.235 ms/op
     p(99.0000) =      8.706 ms/op
     p(99.9000) =     16.777 ms/op
     p(99.9900) =     16.843 ms/op
     p(99.9990) =     16.843 ms/op
     p(99.9999) =     16.843 ms/op
    p(100.0000) =     16.843 ms/op


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
# Warmup Iteration   1: 23.136 ±(99.9%) 0.904 ms/op
Iteration   1: 15.471 ±(99.9%) 0.200 ms/op
                 listUser·p0.00:   7.422 ms/op
                 listUser·p0.50:   15.073 ms/op
                 listUser·p0.90:   17.688 ms/op
                 listUser·p0.95:   19.949 ms/op
                 listUser·p0.99:   28.776 ms/op
                 listUser·p0.999:  34.926 ms/op
                 listUser·p0.9999: 35.455 ms/op
                 listUser·p1.00:   35.455 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2081
  mean =     15.471 ±(99.9%) 0.200 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 1 
    [ 7.500, 10.000) = 39 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 883 
    [15.000, 17.500) = 860 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      7.422 ms/op
     p(50.0000) =     15.073 ms/op
     p(90.0000) =     17.688 ms/op
     p(95.0000) =     19.949 ms/op
     p(99.0000) =     28.776 ms/op
     p(99.9000) =     34.926 ms/op
     p(99.9900) =     35.455 ms/op
     p(99.9990) =     35.455 ms/op
     p(99.9999) =     35.455 ms/op
    p(100.0000) =     35.455 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          2.801          ops/ms
Client.existUser                       thrpt          5.854          ops/ms
Client.getUser                         thrpt          5.517          ops/ms
Client.listUser                        thrpt          1.452          ops/ms
Client.createUser                       avgt          6.649           ms/op
Client.existUser                        avgt          3.771           ms/op
Client.getUser                          avgt          4.002           ms/op
Client.listUser                         avgt         14.587           ms/op
Client.createUser                     sample   5077   6.282 ± 0.077   ms/op
Client.createUser:createUser·p0.00    sample          2.552           ms/op
Client.createUser:createUser·p0.50    sample          5.988           ms/op
Client.createUser:createUser·p0.90    sample          7.293           ms/op
Client.createUser:createUser·p0.95    sample         10.043           ms/op
Client.createUser:createUser·p0.99    sample         13.127           ms/op
Client.createUser:createUser·p0.999   sample         18.776           ms/op
Client.createUser:createUser·p0.9999  sample         19.628           ms/op
Client.createUser:createUser·p1.00    sample         19.628           ms/op
Client.existUser                      sample  10146   3.196 ± 0.055   ms/op
Client.existUser:existUser·p0.00      sample          0.680           ms/op
Client.existUser:existUser·p0.50      sample          2.974           ms/op
Client.existUser:existUser·p0.90      sample          3.494           ms/op
Client.existUser:existUser·p0.95      sample          4.293           ms/op
Client.existUser:existUser·p0.99      sample          9.781           ms/op
Client.existUser:existUser·p0.999     sample         24.473           ms/op
Client.existUser:existUser·p0.9999    sample         24.870           ms/op
Client.existUser:existUser·p1.00      sample         24.871           ms/op
Client.getUser                        sample   8379   3.851 ± 0.046   ms/op
Client.getUser:getUser·p0.00          sample          0.920           ms/op
Client.getUser:getUser·p0.50          sample          3.719           ms/op
Client.getUser:getUser·p0.90          sample          4.899           ms/op
Client.getUser:getUser·p0.95          sample          5.235           ms/op
Client.getUser:getUser·p0.99          sample          8.706           ms/op
Client.getUser:getUser·p0.999         sample         16.777           ms/op
Client.getUser:getUser·p0.9999        sample         16.843           ms/op
Client.getUser:getUser·p1.00          sample         16.843           ms/op
Client.listUser                       sample   2081  15.471 ± 0.200   ms/op
Client.listUser:listUser·p0.00        sample          7.422           ms/op
Client.listUser:listUser·p0.50        sample         15.073           ms/op
Client.listUser:listUser·p0.90        sample         17.688           ms/op
Client.listUser:listUser·p0.95        sample         19.949           ms/op
Client.listUser:listUser·p0.99        sample         28.776           ms/op
Client.listUser:listUser·p0.999       sample         34.926           ms/op
Client.listUser:listUser·p0.9999      sample         35.455           ms/op
Client.listUser:listUser·p1.00        sample         35.455           ms/op
