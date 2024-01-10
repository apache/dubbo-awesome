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
# Warmup Iteration   1: 2.150 ops/ms
Iteration   1: 5.867 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.867 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.325 ops/ms
Iteration   1: 11.715 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.715 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.998 ops/ms
Iteration   1: 9.245 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.245 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.067 ops/ms
Iteration   1: 3.633 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.633 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.383 ±(99.9%) 0.071 ms/op
Iteration   1: 3.187 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.187 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.180 ±(99.9%) 0.118 ms/op
Iteration   1: 2.014 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.014 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.437 ±(99.9%) 0.063 ms/op
Iteration   1: 3.084 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.084 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 12.089 ±(99.9%) 0.260 ms/op
Iteration   1: 7.985 ±(99.9%) 0.105 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.985 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 5.374 ±(99.9%) 0.163 ms/op
Iteration   1: 3.236 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   1.028 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   4.080 ms/op
                 createUser·p0.95:   4.489 ms/op
                 createUser·p0.99:   6.210 ms/op
                 createUser·p0.999:  9.126 ms/op
                 createUser·p0.9999: 10.338 ms/op
                 createUser·p1.00:   10.338 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9880
  mean =      3.236 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 180 
    [ 2.000,  3.000) = 3821 
    [ 3.000,  4.000) = 4720 
    [ 4.000,  5.000) = 878 
    [ 5.000,  6.000) = 165 
    [ 6.000,  7.000) = 74 
    [ 7.000,  8.000) = 10 
    [ 8.000,  9.000) = 13 
    [ 9.000, 10.000) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.028 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      4.080 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      6.210 ms/op
     p(99.9000) =      9.126 ms/op
     p(99.9900) =     10.338 ms/op
     p(99.9990) =     10.338 ms/op
     p(99.9999) =     10.338 ms/op
    p(100.0000) =     10.338 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.128 ±(99.9%) 0.076 ms/op
Iteration   1: 1.920 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.421 ms/op
                 existUser·p0.50:   1.788 ms/op
                 existUser·p0.90:   2.425 ms/op
                 existUser·p0.95:   2.679 ms/op
                 existUser·p0.99:   3.999 ms/op
                 existUser·p0.999:  22.970 ms/op
                 existUser·p0.9999: 23.724 ms/op
                 existUser·p1.00:   23.855 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16661
  mean =      1.920 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15347 
    [ 2.500,  5.000) = 1207 
    [ 5.000,  7.500) = 48 
    [ 7.500, 10.000) = 27 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.421 ms/op
     p(50.0000) =      1.788 ms/op
     p(90.0000) =      2.425 ms/op
     p(95.0000) =      2.679 ms/op
     p(99.0000) =      3.999 ms/op
     p(99.9000) =     22.970 ms/op
     p(99.9900) =     23.724 ms/op
     p(99.9990) =     23.855 ms/op
     p(99.9999) =     23.855 ms/op
    p(100.0000) =     23.855 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.673 ±(99.9%) 0.128 ms/op
Iteration   1: 2.744 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.102 ms/op
                 getUser·p0.50:   2.601 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.843 ms/op
                 getUser·p0.99:   4.637 ms/op
                 getUser·p0.999:  6.242 ms/op
                 getUser·p0.9999: 7.352 ms/op
                 getUser·p1.00:   7.356 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11812
  mean =      2.744 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 33 
    [1.500, 2.000) = 773 
    [2.000, 2.500) = 4327 
    [2.500, 3.000) = 3017 
    [3.000, 3.500) = 2230 
    [3.500, 4.000) = 960 
    [4.000, 4.500) = 296 
    [4.500, 5.000) = 147 
    [5.000, 5.500) = 11 
    [5.500, 6.000) = 4 
    [6.000, 6.500) = 6 
    [6.500, 7.000) = 1 
    [7.000, 7.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.102 ms/op
     p(50.0000) =      2.601 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.843 ms/op
     p(99.0000) =      4.637 ms/op
     p(99.9000) =      6.242 ms/op
     p(99.9900) =      7.352 ms/op
     p(99.9990) =      7.356 ms/op
     p(99.9999) =      7.356 ms/op
    p(100.0000) =      7.356 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 13.045 ±(99.9%) 0.474 ms/op
Iteration   1: 9.041 ±(99.9%) 0.153 ms/op
                 listUser·p0.00:   2.560 ms/op
                 listUser·p0.50:   8.733 ms/op
                 listUser·p0.90:   11.764 ms/op
                 listUser·p0.95:   13.206 ms/op
                 listUser·p0.99:   19.832 ms/op
                 listUser·p0.999:  26.876 ms/op
                 listUser·p0.9999: 28.312 ms/op
                 listUser·p1.00:   28.312 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3562
  mean =      9.041 ±(99.9%) 0.153 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 89 
    [ 5.000,  7.500) = 812 
    [ 7.500, 10.000) = 1742 
    [10.000, 12.500) = 671 
    [12.500, 15.000) = 159 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      2.560 ms/op
     p(50.0000) =      8.733 ms/op
     p(90.0000) =     11.764 ms/op
     p(95.0000) =     13.206 ms/op
     p(99.0000) =     19.832 ms/op
     p(99.9000) =     26.876 ms/op
     p(99.9900) =     28.312 ms/op
     p(99.9990) =     28.312 ms/op
     p(99.9999) =     28.312 ms/op
    p(100.0000) =     28.312 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.867          ops/ms
Client.existUser                       thrpt         11.715          ops/ms
Client.getUser                         thrpt          9.245          ops/ms
Client.listUser                        thrpt          3.633          ops/ms
Client.createUser                       avgt          3.187           ms/op
Client.existUser                        avgt          2.014           ms/op
Client.getUser                          avgt          3.084           ms/op
Client.listUser                         avgt          7.985           ms/op
Client.createUser                     sample   9880   3.236 ± 0.027   ms/op
Client.createUser:createUser·p0.00    sample          1.028           ms/op
Client.createUser:createUser·p0.50    sample          3.183           ms/op
Client.createUser:createUser·p0.90    sample          4.080           ms/op
Client.createUser:createUser·p0.95    sample          4.489           ms/op
Client.createUser:createUser·p0.99    sample          6.210           ms/op
Client.createUser:createUser·p0.999   sample          9.126           ms/op
Client.createUser:createUser·p0.9999  sample         10.338           ms/op
Client.createUser:createUser·p1.00    sample         10.338           ms/op
Client.existUser                      sample  16661   1.920 ± 0.027   ms/op
Client.existUser:existUser·p0.00      sample          0.421           ms/op
Client.existUser:existUser·p0.50      sample          1.788           ms/op
Client.existUser:existUser·p0.90      sample          2.425           ms/op
Client.existUser:existUser·p0.95      sample          2.679           ms/op
Client.existUser:existUser·p0.99      sample          3.999           ms/op
Client.existUser:existUser·p0.999     sample         22.970           ms/op
Client.existUser:existUser·p0.9999    sample         23.724           ms/op
Client.existUser:existUser·p1.00      sample         23.855           ms/op
Client.getUser                        sample  11812   2.744 ± 0.019   ms/op
Client.getUser:getUser·p0.00          sample          1.102           ms/op
Client.getUser:getUser·p0.50          sample          2.601           ms/op
Client.getUser:getUser·p0.90          sample          3.564           ms/op
Client.getUser:getUser·p0.95          sample          3.843           ms/op
Client.getUser:getUser·p0.99          sample          4.637           ms/op
Client.getUser:getUser·p0.999         sample          6.242           ms/op
Client.getUser:getUser·p0.9999        sample          7.352           ms/op
Client.getUser:getUser·p1.00          sample          7.356           ms/op
Client.listUser                       sample   3562   9.041 ± 0.153   ms/op
Client.listUser:listUser·p0.00        sample          2.560           ms/op
Client.listUser:listUser·p0.50        sample          8.733           ms/op
Client.listUser:listUser·p0.90        sample         11.764           ms/op
Client.listUser:listUser·p0.95        sample         13.206           ms/op
Client.listUser:listUser·p0.99        sample         19.832           ms/op
Client.listUser:listUser·p0.999       sample         26.876           ms/op
Client.listUser:listUser·p0.9999      sample         28.312           ms/op
Client.listUser:listUser·p1.00        sample         28.312           ms/op
