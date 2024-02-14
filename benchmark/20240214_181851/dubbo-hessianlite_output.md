# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.208 ops/ms
Iteration   1: 5.965 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.965 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.638 ops/ms
Iteration   1: 13.828 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.828 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.495 ops/ms
Iteration   1: 8.199 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.199 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.048 ops/ms
Iteration   1: 3.400 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.400 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.519 ±(99.9%) 0.074 ms/op
Iteration   1: 3.346 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.346 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 4.235 ±(99.9%) 0.041 ms/op
Iteration   1: 2.136 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.136 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.950 ±(99.9%) 0.066 ms/op
Iteration   1: 3.900 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.900 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 12.000 ±(99.9%) 0.337 ms/op
Iteration   1: 8.062 ±(99.9%) 0.160 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.062 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.193 ±(99.9%) 0.118 ms/op
Iteration   1: 3.040 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   1.313 ms/op
                 createUser·p0.50:   2.875 ms/op
                 createUser·p0.90:   3.895 ms/op
                 createUser·p0.95:   4.162 ms/op
                 createUser·p0.99:   5.571 ms/op
                 createUser·p0.999:  10.093 ms/op
                 createUser·p0.9999: 14.669 ms/op
                 createUser·p1.00:   14.680 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10494
  mean =      3.040 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1755 
    [ 2.500,  3.750) = 7379 
    [ 3.750,  5.000) = 1227 
    [ 5.000,  6.250) = 53 
    [ 6.250,  7.500) = 41 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 11 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.313 ms/op
     p(50.0000) =      2.875 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.162 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =     10.093 ms/op
     p(99.9900) =     14.669 ms/op
     p(99.9990) =     14.680 ms/op
     p(99.9999) =     14.680 ms/op
    p(100.0000) =     14.680 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.019 ±(99.9%) 0.062 ms/op
Iteration   1: 2.145 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.460 ms/op
                 existUser·p0.50:   1.964 ms/op
                 existUser·p0.90:   2.818 ms/op
                 existUser·p0.95:   3.174 ms/op
                 existUser·p0.99:   5.267 ms/op
                 existUser·p0.999:  13.826 ms/op
                 existUser·p0.9999: 17.186 ms/op
                 existUser·p1.00:   17.629 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15108
  mean =      2.145 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 360 
    [ 1.250,  2.500) = 11819 
    [ 2.500,  3.750) = 2437 
    [ 3.750,  5.000) = 319 
    [ 5.000,  6.250) = 62 
    [ 6.250,  7.500) = 42 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.460 ms/op
     p(50.0000) =      1.964 ms/op
     p(90.0000) =      2.818 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      5.267 ms/op
     p(99.9000) =     13.826 ms/op
     p(99.9900) =     17.186 ms/op
     p(99.9990) =     17.629 ms/op
     p(99.9999) =     17.629 ms/op
    p(100.0000) =     17.629 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.279 ±(99.9%) 0.106 ms/op
Iteration   1: 3.110 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.908 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.817 ms/op
                 getUser·p0.95:   4.219 ms/op
                 getUser·p0.99:   5.065 ms/op
                 getUser·p0.999:  6.889 ms/op
                 getUser·p0.9999: 7.601 ms/op
                 getUser·p1.00:   7.610 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10275
  mean =      3.110 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 1 
    [1.000, 1.500) = 51 
    [1.500, 2.000) = 521 
    [2.000, 2.500) = 1109 
    [2.500, 3.000) = 2466 
    [3.000, 3.500) = 3833 
    [3.500, 4.000) = 1584 
    [4.000, 4.500) = 425 
    [4.500, 5.000) = 177 
    [5.000, 5.500) = 35 
    [5.500, 6.000) = 18 
    [6.000, 6.500) = 22 
    [6.500, 7.000) = 27 
    [7.000, 7.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.908 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      5.065 ms/op
     p(99.9000) =      6.889 ms/op
     p(99.9900) =      7.601 ms/op
     p(99.9990) =      7.610 ms/op
     p(99.9999) =      7.610 ms/op
    p(100.0000) =      7.610 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 11.926 ±(99.9%) 0.433 ms/op
Iteration   1: 8.099 ±(99.9%) 0.109 ms/op
                 listUser·p0.00:   2.413 ms/op
                 listUser·p0.50:   7.971 ms/op
                 listUser·p0.90:   10.617 ms/op
                 listUser·p0.95:   11.289 ms/op
                 listUser·p0.99:   13.996 ms/op
                 listUser·p0.999:  22.807 ms/op
                 listUser·p0.9999: 23.462 ms/op
                 listUser·p1.00:   23.462 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3950
  mean =      8.099 ±(99.9%) 0.109 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 117 
    [ 5.000,  7.500) = 1461 
    [ 7.500, 10.000) = 1779 
    [10.000, 12.500) = 528 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.413 ms/op
     p(50.0000) =      7.971 ms/op
     p(90.0000) =     10.617 ms/op
     p(95.0000) =     11.289 ms/op
     p(99.0000) =     13.996 ms/op
     p(99.9000) =     22.807 ms/op
     p(99.9900) =     23.462 ms/op
     p(99.9990) =     23.462 ms/op
     p(99.9999) =     23.462 ms/op
    p(100.0000) =     23.462 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.965          ops/ms
Client.existUser                       thrpt         13.828          ops/ms
Client.getUser                         thrpt          8.199          ops/ms
Client.listUser                        thrpt          3.400          ops/ms
Client.createUser                       avgt          3.346           ms/op
Client.existUser                        avgt          2.136           ms/op
Client.getUser                          avgt          3.900           ms/op
Client.listUser                         avgt          8.062           ms/op
Client.createUser                     sample  10494   3.040 ± 0.025   ms/op
Client.createUser:createUser·p0.00    sample          1.313           ms/op
Client.createUser:createUser·p0.50    sample          2.875           ms/op
Client.createUser:createUser·p0.90    sample          3.895           ms/op
Client.createUser:createUser·p0.95    sample          4.162           ms/op
Client.createUser:createUser·p0.99    sample          5.571           ms/op
Client.createUser:createUser·p0.999   sample         10.093           ms/op
Client.createUser:createUser·p0.9999  sample         14.669           ms/op
Client.createUser:createUser·p1.00    sample         14.680           ms/op
Client.existUser                      sample  15108   2.145 ± 0.027   ms/op
Client.existUser:existUser·p0.00      sample          0.460           ms/op
Client.existUser:existUser·p0.50      sample          1.964           ms/op
Client.existUser:existUser·p0.90      sample          2.818           ms/op
Client.existUser:existUser·p0.95      sample          3.174           ms/op
Client.existUser:existUser·p0.99      sample          5.267           ms/op
Client.existUser:existUser·p0.999     sample         13.826           ms/op
Client.existUser:existUser·p0.9999    sample         17.186           ms/op
Client.existUser:existUser·p1.00      sample         17.629           ms/op
Client.getUser                        sample  10275   3.110 ± 0.022   ms/op
Client.getUser:getUser·p0.00          sample          0.908           ms/op
Client.getUser:getUser·p0.50          sample          3.133           ms/op
Client.getUser:getUser·p0.90          sample          3.817           ms/op
Client.getUser:getUser·p0.95          sample          4.219           ms/op
Client.getUser:getUser·p0.99          sample          5.065           ms/op
Client.getUser:getUser·p0.999         sample          6.889           ms/op
Client.getUser:getUser·p0.9999        sample          7.601           ms/op
Client.getUser:getUser·p1.00          sample          7.610           ms/op
Client.listUser                       sample   3950   8.099 ± 0.109   ms/op
Client.listUser:listUser·p0.00        sample          2.413           ms/op
Client.listUser:listUser·p0.50        sample          7.971           ms/op
Client.listUser:listUser·p0.90        sample         10.617           ms/op
Client.listUser:listUser·p0.95        sample         11.289           ms/op
Client.listUser:listUser·p0.99        sample         13.996           ms/op
Client.listUser:listUser·p0.999       sample         22.807           ms/op
Client.listUser:listUser·p0.9999      sample         23.462           ms/op
Client.listUser:listUser·p1.00        sample         23.462           ms/op
