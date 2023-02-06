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
# Warmup Iteration   1: 0.853 ops/ms
Iteration   1: 1.521 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  1.521 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:22
# Fork: 1 of 1
# Warmup Iteration   1: 2.051 ops/ms
Iteration   1: 3.959 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.959 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:13
# Fork: 1 of 1
# Warmup Iteration   1: 1.463 ops/ms
Iteration   1: 2.823 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.823 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 0.667 ops/ms
Iteration   1: 0.961 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  0.961 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:59
# Fork: 1 of 1
# Warmup Iteration   1: 23.350 ±(99.9%) 0.428 ms/op
Iteration   1: 14.104 ±(99.9%) 0.069 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  14.104 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:51
# Fork: 1 of 1
# Warmup Iteration   1: 11.787 ±(99.9%) 0.165 ms/op
Iteration   1: 7.153 ±(99.9%) 0.106 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  7.153 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:44
# Fork: 1 of 1
# Warmup Iteration   1: 17.790 ±(99.9%) 0.327 ms/op
Iteration   1: 6.761 ±(99.9%) 0.069 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  6.761 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:36
# Fork: 1 of 1
# Warmup Iteration   1: 42.665 ±(99.9%) 0.749 ms/op
Iteration   1: 23.960 ±(99.9%) 0.320 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  23.960 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:29
# Fork: 1 of 1
# Warmup Iteration   1: 19.691 ±(99.9%) 0.630 ms/op
Iteration   1: 11.574 ±(99.9%) 0.295 ms/op
                 createUser·p0.00:   3.391 ms/op
                 createUser·p0.50:   11.600 ms/op
                 createUser·p0.90:   13.304 ms/op
                 createUser·p0.95:   18.547 ms/op
                 createUser·p0.99:   30.736 ms/op
                 createUser·p0.999:  36.831 ms/op
                 createUser·p0.9999: 42.992 ms/op
                 createUser·p1.00:   42.992 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 2750
  mean =     11.574 ±(99.9%) 0.295 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 183 
    [ 5.000, 10.000) = 414 
    [10.000, 15.000) = 1954 
    [15.000, 20.000) = 69 
    [20.000, 25.000) = 42 
    [25.000, 30.000) = 57 
    [30.000, 35.000) = 5 
    [35.000, 40.000) = 25 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      3.391 ms/op
     p(50.0000) =     11.600 ms/op
     p(90.0000) =     13.304 ms/op
     p(95.0000) =     18.547 ms/op
     p(99.0000) =     30.736 ms/op
     p(99.9000) =     36.831 ms/op
     p(99.9900) =     42.992 ms/op
     p(99.9990) =     42.992 ms/op
     p(99.9999) =     42.992 ms/op
    p(100.0000) =     42.992 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:22
# Fork: 1 of 1
# Warmup Iteration   1: 12.014 ±(99.9%) 0.350 ms/op
Iteration   1: 7.007 ±(99.9%) 0.158 ms/op
                 existUser·p0.00:   1.493 ms/op
                 existUser·p0.50:   6.824 ms/op
                 existUser·p0.90:   8.777 ms/op
                 existUser·p0.95:   13.088 ms/op
                 existUser·p0.99:   16.155 ms/op
                 existUser·p0.999:  33.218 ms/op
                 existUser·p0.9999: 34.537 ms/op
                 existUser·p1.00:   34.537 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 4562
  mean =      7.007 ±(99.9%) 0.158 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 1165 
    [ 5.000,  7.500) = 1694 
    [ 7.500, 10.000) = 1355 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 165 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.493 ms/op
     p(50.0000) =      6.824 ms/op
     p(90.0000) =      8.777 ms/op
     p(95.0000) =     13.088 ms/op
     p(99.0000) =     16.155 ms/op
     p(99.9000) =     33.218 ms/op
     p(99.9900) =     34.537 ms/op
     p(99.9990) =     34.537 ms/op
     p(99.9999) =     34.537 ms/op
    p(100.0000) =     34.537 ms/op


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
# Warmup Iteration   1: 14.495 ±(99.9%) 0.457 ms/op
Iteration   1: 7.062 ±(99.9%) 0.125 ms/op
                 getUser·p0.00:   1.972 ms/op
                 getUser·p0.50:   6.513 ms/op
                 getUser·p0.90:   9.011 ms/op
                 getUser·p0.95:   11.616 ms/op
                 getUser·p0.99:   21.398 ms/op
                 getUser·p0.999:  23.510 ms/op
                 getUser·p0.9999: 24.117 ms/op
                 getUser·p1.00:   24.117 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 4542
  mean =      7.062 ±(99.9%) 0.125 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 330 
    [ 5.000,  7.500) = 3103 
    [ 7.500, 10.000) = 743 
    [10.000, 12.500) = 228 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.972 ms/op
     p(50.0000) =      6.513 ms/op
     p(90.0000) =      9.011 ms/op
     p(95.0000) =     11.616 ms/op
     p(99.0000) =     21.398 ms/op
     p(99.9000) =     23.510 ms/op
     p(99.9900) =     24.117 ms/op
     p(99.9990) =     24.117 ms/op
     p(99.9999) =     24.117 ms/op
    p(100.0000) =     24.117 ms/op


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
# Warmup Iteration   1: 32.639 ±(99.9%) 1.097 ms/op
Iteration   1: 22.028 ±(99.9%) 0.503 ms/op
                 listUser·p0.00:   11.239 ms/op
                 listUser·p0.50:   19.251 ms/op
                 listUser·p0.90:   30.248 ms/op
                 listUser·p0.95:   33.882 ms/op
                 listUser·p0.99:   42.953 ms/op
                 listUser·p0.999:  49.062 ms/op
                 listUser·p0.9999: 49.152 ms/op
                 listUser·p1.00:   49.152 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1458
  mean =     22.028 ±(99.9%) 0.503 ms/op

  Histogram, ms/op:
    [10.000, 12.500) = 10 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 200 
    [17.500, 20.000) = 642 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 156 
    [25.000, 27.500) = 137 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 68 
    [32.500, 35.000) = 47 
    [35.000, 37.500) = 19 
    [37.500, 40.000) = 8 
    [40.000, 42.500) = 1 
    [42.500, 45.000) = 14 
    [45.000, 47.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =     11.239 ms/op
     p(50.0000) =     19.251 ms/op
     p(90.0000) =     30.248 ms/op
     p(95.0000) =     33.882 ms/op
     p(99.0000) =     42.953 ms/op
     p(99.9000) =     49.062 ms/op
     p(99.9900) =     49.152 ms/op
     p(99.9990) =     49.152 ms/op
     p(99.9999) =     49.152 ms/op
    p(100.0000) =     49.152 ms/op


# Run complete. Total time: 00:01:29

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         1.521          ops/ms
Client.existUser                       thrpt         3.959          ops/ms
Client.getUser                         thrpt         2.823          ops/ms
Client.listUser                        thrpt         0.961          ops/ms
Client.createUser                       avgt        14.104           ms/op
Client.existUser                        avgt         7.153           ms/op
Client.getUser                          avgt         6.761           ms/op
Client.listUser                         avgt        23.960           ms/op
Client.createUser                     sample  2750  11.574 ± 0.295   ms/op
Client.createUser:createUser·p0.00    sample         3.391           ms/op
Client.createUser:createUser·p0.50    sample        11.600           ms/op
Client.createUser:createUser·p0.90    sample        13.304           ms/op
Client.createUser:createUser·p0.95    sample        18.547           ms/op
Client.createUser:createUser·p0.99    sample        30.736           ms/op
Client.createUser:createUser·p0.999   sample        36.831           ms/op
Client.createUser:createUser·p0.9999  sample        42.992           ms/op
Client.createUser:createUser·p1.00    sample        42.992           ms/op
Client.existUser                      sample  4562   7.007 ± 0.158   ms/op
Client.existUser:existUser·p0.00      sample         1.493           ms/op
Client.existUser:existUser·p0.50      sample         6.824           ms/op
Client.existUser:existUser·p0.90      sample         8.777           ms/op
Client.existUser:existUser·p0.95      sample        13.088           ms/op
Client.existUser:existUser·p0.99      sample        16.155           ms/op
Client.existUser:existUser·p0.999     sample        33.218           ms/op
Client.existUser:existUser·p0.9999    sample        34.537           ms/op
Client.existUser:existUser·p1.00      sample        34.537           ms/op
Client.getUser                        sample  4542   7.062 ± 0.125   ms/op
Client.getUser:getUser·p0.00          sample         1.972           ms/op
Client.getUser:getUser·p0.50          sample         6.513           ms/op
Client.getUser:getUser·p0.90          sample         9.011           ms/op
Client.getUser:getUser·p0.95          sample        11.616           ms/op
Client.getUser:getUser·p0.99          sample        21.398           ms/op
Client.getUser:getUser·p0.999         sample        23.510           ms/op
Client.getUser:getUser·p0.9999        sample        24.117           ms/op
Client.getUser:getUser·p1.00          sample        24.117           ms/op
Client.listUser                       sample  1458  22.028 ± 0.503   ms/op
Client.listUser:listUser·p0.00        sample        11.239           ms/op
Client.listUser:listUser·p0.50        sample        19.251           ms/op
Client.listUser:listUser·p0.90        sample        30.248           ms/op
Client.listUser:listUser·p0.95        sample        33.882           ms/op
Client.listUser:listUser·p0.99        sample        42.953           ms/op
Client.listUser:listUser·p0.999       sample        49.062           ms/op
Client.listUser:listUser·p0.9999      sample        49.152           ms/op
Client.listUser:listUser·p1.00        sample        49.152           ms/op
