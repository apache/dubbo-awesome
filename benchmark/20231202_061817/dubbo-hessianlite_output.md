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
# Warmup Iteration   1: 2.430 ops/ms
Iteration   1: 5.829 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.829 ops/ms


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
# Warmup Iteration   1: 6.066 ops/ms
Iteration   1: 14.376 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  14.376 ops/ms


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
# Warmup Iteration   1: 4.157 ops/ms
Iteration   1: 7.262 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.262 ops/ms


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
# Warmup Iteration   1: 1.971 ops/ms
Iteration   1: 3.552 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.552 ops/ms


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
# Warmup Iteration   1: 5.862 ±(99.9%) 0.117 ms/op
Iteration   1: 3.217 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.217 ms/op


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
# Warmup Iteration   1: 3.521 ±(99.9%) 0.037 ms/op
Iteration   1: 2.098 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.098 ms/op


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
# Warmup Iteration   1: 5.268 ±(99.9%) 0.063 ms/op
Iteration   1: 3.898 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.898 ms/op


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
# Warmup Iteration   1: 13.975 ±(99.9%) 0.236 ms/op
Iteration   1: 9.275 ±(99.9%) 0.123 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.275 ms/op


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
# Warmup Iteration   1: 5.136 ±(99.9%) 0.098 ms/op
Iteration   1: 2.921 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.055 ms/op
                 createUser·p0.50:   2.851 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   3.858 ms/op
                 createUser·p0.99:   5.251 ms/op
                 createUser·p0.999:  6.390 ms/op
                 createUser·p0.9999: 7.992 ms/op
                 createUser·p1.00:   8.028 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11094
  mean =      2.921 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 22 
    [1.500, 2.000) = 395 
    [2.000, 2.500) = 2698 
    [2.500, 3.000) = 3322 
    [3.000, 3.500) = 2905 
    [3.500, 4.000) = 1328 
    [4.000, 4.500) = 235 
    [4.500, 5.000) = 73 
    [5.000, 5.500) = 16 
    [5.500, 6.000) = 30 
    [6.000, 6.500) = 66 
    [6.500, 7.000) = 2 
    [7.000, 7.500) = 0 
    [7.500, 8.000) = 1 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.055 ms/op
     p(50.0000) =      2.851 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      5.251 ms/op
     p(99.9000) =      6.390 ms/op
     p(99.9900) =      7.992 ms/op
     p(99.9990) =      8.028 ms/op
     p(99.9999) =      8.028 ms/op
    p(100.0000) =      8.028 ms/op


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
# Warmup Iteration   1: 3.113 ±(99.9%) 0.065 ms/op
Iteration   1: 1.802 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.767 ms/op
                 existUser·p0.50:   1.726 ms/op
                 existUser·p0.90:   2.091 ms/op
                 existUser·p0.95:   2.245 ms/op
                 existUser·p0.99:   3.043 ms/op
                 existUser·p0.999:  16.499 ms/op
                 existUser·p0.9999: 16.612 ms/op
                 existUser·p1.00:   16.663 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17745
  mean =      1.802 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 186 
    [ 1.250,  2.500) = 17109 
    [ 2.500,  3.750) = 358 
    [ 3.750,  5.000) = 14 
    [ 5.000,  6.250) = 45 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.767 ms/op
     p(50.0000) =      1.726 ms/op
     p(90.0000) =      2.091 ms/op
     p(95.0000) =      2.245 ms/op
     p(99.0000) =      3.043 ms/op
     p(99.9000) =     16.499 ms/op
     p(99.9900) =     16.612 ms/op
     p(99.9990) =     16.663 ms/op
     p(99.9999) =     16.663 ms/op
    p(100.0000) =     16.663 ms/op


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
# Warmup Iteration   1: 4.612 ±(99.9%) 0.112 ms/op
Iteration   1: 3.041 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.779 ms/op
                 getUser·p0.50:   2.867 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   4.133 ms/op
                 getUser·p0.99:   5.231 ms/op
                 getUser·p0.999:  11.264 ms/op
                 getUser·p0.9999: 11.305 ms/op
                 getUser·p1.00:   11.305 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10514
  mean =      3.041 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 15 
    [ 1.250,  2.500) = 1452 
    [ 2.500,  3.750) = 7774 
    [ 3.750,  5.000) = 1149 
    [ 5.000,  6.250) = 78 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.779 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.133 ms/op
     p(99.0000) =      5.231 ms/op
     p(99.9000) =     11.264 ms/op
     p(99.9900) =     11.305 ms/op
     p(99.9990) =     11.305 ms/op
     p(99.9999) =     11.305 ms/op
    p(100.0000) =     11.305 ms/op


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
# Warmup Iteration   1: 13.635 ±(99.9%) 0.499 ms/op
Iteration   1: 8.716 ±(99.9%) 0.279 ms/op
                 listUser·p0.00:   1.413 ms/op
                 listUser·p0.50:   8.102 ms/op
                 listUser·p0.90:   10.876 ms/op
                 listUser·p0.95:   11.813 ms/op
                 listUser·p0.99:   16.471 ms/op
                 listUser·p0.999:  79.539 ms/op
                 listUser·p0.9999: 84.541 ms/op
                 listUser·p1.00:   84.541 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3721
  mean =      8.716 ±(99.9%) 0.279 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 120 
    [ 5.000, 10.000) = 3000 
    [10.000, 15.000) = 550 
    [15.000, 20.000) = 18 
    [20.000, 25.000) = 1 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 2 
    [45.000, 50.000) = 9 
    [50.000, 55.000) = 4 
    [55.000, 60.000) = 2 
    [60.000, 65.000) = 7 
    [65.000, 70.000) = 1 
    [70.000, 75.000) = 2 
    [75.000, 80.000) = 3 
    [80.000, 85.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.413 ms/op
     p(50.0000) =      8.102 ms/op
     p(90.0000) =     10.876 ms/op
     p(95.0000) =     11.813 ms/op
     p(99.0000) =     16.471 ms/op
     p(99.9000) =     79.539 ms/op
     p(99.9900) =     84.541 ms/op
     p(99.9990) =     84.541 ms/op
     p(99.9999) =     84.541 ms/op
    p(100.0000) =     84.541 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.829          ops/ms
Client.existUser                       thrpt         14.376          ops/ms
Client.getUser                         thrpt          7.262          ops/ms
Client.listUser                        thrpt          3.552          ops/ms
Client.createUser                       avgt          3.217           ms/op
Client.existUser                        avgt          2.098           ms/op
Client.getUser                          avgt          3.898           ms/op
Client.listUser                         avgt          9.275           ms/op
Client.createUser                     sample  11094   2.921 ± 0.021   ms/op
Client.createUser:createUser·p0.00    sample          1.055           ms/op
Client.createUser:createUser·p0.50    sample          2.851           ms/op
Client.createUser:createUser·p0.90    sample          3.682           ms/op
Client.createUser:createUser·p0.95    sample          3.858           ms/op
Client.createUser:createUser·p0.99    sample          5.251           ms/op
Client.createUser:createUser·p0.999   sample          6.390           ms/op
Client.createUser:createUser·p0.9999  sample          7.992           ms/op
Client.createUser:createUser·p1.00    sample          8.028           ms/op
Client.existUser                      sample  17745   1.802 ± 0.018   ms/op
Client.existUser:existUser·p0.00      sample          0.767           ms/op
Client.existUser:existUser·p0.50      sample          1.726           ms/op
Client.existUser:existUser·p0.90      sample          2.091           ms/op
Client.existUser:existUser·p0.95      sample          2.245           ms/op
Client.existUser:existUser·p0.99      sample          3.043           ms/op
Client.existUser:existUser·p0.999     sample         16.499           ms/op
Client.existUser:existUser·p0.9999    sample         16.612           ms/op
Client.existUser:existUser·p1.00      sample         16.663           ms/op
Client.getUser                        sample  10514   3.041 ± 0.024   ms/op
Client.getUser:getUser·p0.00          sample          0.779           ms/op
Client.getUser:getUser·p0.50          sample          2.867           ms/op
Client.getUser:getUser·p0.90          sample          3.850           ms/op
Client.getUser:getUser·p0.95          sample          4.133           ms/op
Client.getUser:getUser·p0.99          sample          5.231           ms/op
Client.getUser:getUser·p0.999         sample         11.264           ms/op
Client.getUser:getUser·p0.9999        sample         11.305           ms/op
Client.getUser:getUser·p1.00          sample         11.305           ms/op
Client.listUser                       sample   3721   8.716 ± 0.279   ms/op
Client.listUser:listUser·p0.00        sample          1.413           ms/op
Client.listUser:listUser·p0.50        sample          8.102           ms/op
Client.listUser:listUser·p0.90        sample         10.876           ms/op
Client.listUser:listUser·p0.95        sample         11.813           ms/op
Client.listUser:listUser·p0.99        sample         16.471           ms/op
Client.listUser:listUser·p0.999       sample         79.539           ms/op
Client.listUser:listUser·p0.9999      sample         84.541           ms/op
Client.listUser:listUser·p1.00        sample         84.541           ms/op
