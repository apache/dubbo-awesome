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
# Warmup Iteration   1: 2.113 ops/ms
Iteration   1: 6.174 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.174 ops/ms


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
# Warmup Iteration   1: 4.820 ops/ms
Iteration   1: 11.411 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.411 ops/ms


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
# Warmup Iteration   1: 3.761 ops/ms
Iteration   1: 7.760 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.760 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.276 ops/ms
Iteration   1: 3.863 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.863 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.681 ±(99.9%) 0.092 ms/op
Iteration   1: 3.064 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.064 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.459 ±(99.9%) 0.047 ms/op
Iteration   1: 1.843 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.843 ms/op


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
# Warmup Iteration   1: 5.022 ±(99.9%) 0.052 ms/op
Iteration   1: 3.114 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.114 ms/op


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
# Warmup Iteration   1: 12.503 ±(99.9%) 0.214 ms/op
Iteration   1: 8.102 ±(99.9%) 0.096 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.102 ms/op


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
# Warmup Iteration   1: 5.150 ±(99.9%) 0.133 ms/op
Iteration   1: 2.949 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   1.184 ms/op
                 createUser·p0.50:   2.773 ms/op
                 createUser·p0.90:   3.428 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   7.242 ms/op
                 createUser·p0.999:  14.434 ms/op
                 createUser·p0.9999: 20.244 ms/op
                 createUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11039
  mean =      2.949 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2190 
    [ 2.500,  5.000) = 8622 
    [ 5.000,  7.500) = 122 
    [ 7.500, 10.000) = 15 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.184 ms/op
     p(50.0000) =      2.773 ms/op
     p(90.0000) =      3.428 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      7.242 ms/op
     p(99.9000) =     14.434 ms/op
     p(99.9900) =     20.244 ms/op
     p(99.9990) =     20.251 ms/op
     p(99.9999) =     20.251 ms/op
    p(100.0000) =     20.251 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.261 ±(99.9%) 0.081 ms/op
Iteration   1: 2.009 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.471 ms/op
                 existUser·p0.50:   1.858 ms/op
                 existUser·p0.90:   2.494 ms/op
                 existUser·p0.95:   2.699 ms/op
                 existUser·p0.99:   3.498 ms/op
                 existUser·p0.999:  14.598 ms/op
                 existUser·p0.9999: 15.125 ms/op
                 existUser·p1.00:   15.794 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15918
  mean =      2.009 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 357 
    [ 1.250,  2.500) = 13992 
    [ 2.500,  3.750) = 1445 
    [ 3.750,  5.000) = 11 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 64 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.471 ms/op
     p(50.0000) =      1.858 ms/op
     p(90.0000) =      2.494 ms/op
     p(95.0000) =      2.699 ms/op
     p(99.0000) =      3.498 ms/op
     p(99.9000) =     14.598 ms/op
     p(99.9900) =     15.125 ms/op
     p(99.9990) =     15.794 ms/op
     p(99.9999) =     15.794 ms/op
    p(100.0000) =     15.794 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.585 ±(99.9%) 0.106 ms/op
Iteration   1: 2.745 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.010 ms/op
                 getUser·p0.50:   2.621 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.915 ms/op
                 getUser·p0.999:  6.196 ms/op
                 getUser·p0.9999: 7.485 ms/op
                 getUser·p1.00:   7.520 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11652
  mean =      2.745 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 22 
    [1.500, 2.000) = 537 
    [2.000, 2.500) = 4081 
    [2.500, 3.000) = 3867 
    [3.000, 3.500) = 1872 
    [3.500, 4.000) = 920 
    [4.000, 4.500) = 174 
    [4.500, 5.000) = 69 
    [5.000, 5.500) = 30 
    [5.500, 6.000) = 62 
    [6.000, 6.500) = 16 
    [6.500, 7.000) = 0 
    [7.000, 7.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.010 ms/op
     p(50.0000) =      2.621 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      4.915 ms/op
     p(99.9000) =      6.196 ms/op
     p(99.9900) =      7.485 ms/op
     p(99.9990) =      7.520 ms/op
     p(99.9999) =      7.520 ms/op
    p(100.0000) =      7.520 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 12.104 ±(99.9%) 0.457 ms/op
Iteration   1: 7.959 ±(99.9%) 0.105 ms/op
                 listUser·p0.00:   2.630 ms/op
                 listUser·p0.50:   7.700 ms/op
                 listUser·p0.90:   10.191 ms/op
                 listUser·p0.95:   10.928 ms/op
                 listUser·p0.99:   14.101 ms/op
                 listUser·p0.999:  21.756 ms/op
                 listUser·p0.9999: 22.512 ms/op
                 listUser·p1.00:   22.512 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4015
  mean =      7.959 ±(99.9%) 0.105 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 114 
    [ 5.000,  7.500) = 1719 
    [ 7.500, 10.000) = 1699 
    [10.000, 12.500) = 407 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.630 ms/op
     p(50.0000) =      7.700 ms/op
     p(90.0000) =     10.191 ms/op
     p(95.0000) =     10.928 ms/op
     p(99.0000) =     14.101 ms/op
     p(99.9000) =     21.756 ms/op
     p(99.9900) =     22.512 ms/op
     p(99.9990) =     22.512 ms/op
     p(99.9999) =     22.512 ms/op
    p(100.0000) =     22.512 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.174          ops/ms
Client.existUser                       thrpt         11.411          ops/ms
Client.getUser                         thrpt          7.760          ops/ms
Client.listUser                        thrpt          3.863          ops/ms
Client.createUser                       avgt          3.064           ms/op
Client.existUser                        avgt          1.843           ms/op
Client.getUser                          avgt          3.114           ms/op
Client.listUser                         avgt          8.102           ms/op
Client.createUser                     sample  11039   2.949 ± 0.034   ms/op
Client.createUser:createUser·p0.00    sample          1.184           ms/op
Client.createUser:createUser·p0.50    sample          2.773           ms/op
Client.createUser:createUser·p0.90    sample          3.428           ms/op
Client.createUser:createUser·p0.95    sample          3.801           ms/op
Client.createUser:createUser·p0.99    sample          7.242           ms/op
Client.createUser:createUser·p0.999   sample         14.434           ms/op
Client.createUser:createUser·p0.9999  sample         20.244           ms/op
Client.createUser:createUser·p1.00    sample         20.251           ms/op
Client.existUser                      sample  15918   2.009 ± 0.022   ms/op
Client.existUser:existUser·p0.00      sample          0.471           ms/op
Client.existUser:existUser·p0.50      sample          1.858           ms/op
Client.existUser:existUser·p0.90      sample          2.494           ms/op
Client.existUser:existUser·p0.95      sample          2.699           ms/op
Client.existUser:existUser·p0.99      sample          3.498           ms/op
Client.existUser:existUser·p0.999     sample         14.598           ms/op
Client.existUser:existUser·p0.9999    sample         15.125           ms/op
Client.existUser:existUser·p1.00      sample         15.794           ms/op
Client.getUser                        sample  11652   2.745 ± 0.019   ms/op
Client.getUser:getUser·p0.00          sample          1.010           ms/op
Client.getUser:getUser·p0.50          sample          2.621           ms/op
Client.getUser:getUser·p0.90          sample          3.531           ms/op
Client.getUser:getUser·p0.95          sample          3.805           ms/op
Client.getUser:getUser·p0.99          sample          4.915           ms/op
Client.getUser:getUser·p0.999         sample          6.196           ms/op
Client.getUser:getUser·p0.9999        sample          7.485           ms/op
Client.getUser:getUser·p1.00          sample          7.520           ms/op
Client.listUser                       sample   4015   7.959 ± 0.105   ms/op
Client.listUser:listUser·p0.00        sample          2.630           ms/op
Client.listUser:listUser·p0.50        sample          7.700           ms/op
Client.listUser:listUser·p0.90        sample         10.191           ms/op
Client.listUser:listUser·p0.95        sample         10.928           ms/op
Client.listUser:listUser·p0.99        sample         14.101           ms/op
Client.listUser:listUser·p0.999       sample         21.756           ms/op
Client.listUser:listUser·p0.9999      sample         22.512           ms/op
Client.listUser:listUser·p1.00        sample         22.512           ms/op
