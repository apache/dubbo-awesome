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
# Warmup Iteration   1: 2.159 ops/ms
Iteration   1: 5.301 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.301 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.381 ops/ms
Iteration   1: 11.374 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.374 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.809 ops/ms
Iteration   1: 9.011 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.011 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.489 ops/ms
Iteration   1: 4.028 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  4.028 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:54
# Fork: 1 of 1
# Warmup Iteration   1: 5.161 ±(99.9%) 0.072 ms/op
Iteration   1: 3.030 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.030 ms/op


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
# Warmup Iteration   1: 3.223 ±(99.9%) 0.039 ms/op
Iteration   1: 2.095 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.095 ms/op


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
# Warmup Iteration   1: 4.665 ±(99.9%) 0.056 ms/op
Iteration   1: 3.118 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.118 ms/op


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
# Warmup Iteration   1: 11.927 ±(99.9%) 0.274 ms/op
Iteration   1: 8.708 ±(99.9%) 0.102 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.708 ms/op


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
# Warmup Iteration   1: 5.284 ±(99.9%) 0.126 ms/op
Iteration   1: 3.006 ±(99.9%) 0.057 ms/op
                 createUser·p0.00:   0.898 ms/op
                 createUser·p0.50:   2.732 ms/op
                 createUser·p0.90:   3.412 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   12.184 ms/op
                 createUser·p0.999:  21.463 ms/op
                 createUser·p0.9999: 23.437 ms/op
                 createUser·p1.00:   23.560 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10636
  mean =      3.006 ±(99.9%) 0.057 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2512 
    [ 2.500,  5.000) = 7837 
    [ 5.000,  7.500) = 92 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.898 ms/op
     p(50.0000) =      2.732 ms/op
     p(90.0000) =      3.412 ms/op
     p(95.0000) =      4.067 ms/op
     p(99.0000) =     12.184 ms/op
     p(99.9000) =     21.463 ms/op
     p(99.9900) =     23.437 ms/op
     p(99.9990) =     23.560 ms/op
     p(99.9999) =     23.560 ms/op
    p(100.0000) =     23.560 ms/op


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
# Warmup Iteration   1: 3.282 ±(99.9%) 0.115 ms/op
Iteration   1: 1.801 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.748 ms/op
                 existUser·p0.50:   1.745 ms/op
                 existUser·p0.90:   2.138 ms/op
                 existUser·p0.95:   2.413 ms/op
                 existUser·p0.99:   2.946 ms/op
                 existUser·p0.999:  5.802 ms/op
                 existUser·p0.9999: 6.809 ms/op
                 existUser·p1.00:   8.651 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17780
  mean =      1.801 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 34 
    [1.000, 1.500) = 1651 
    [1.500, 2.000) = 13391 
    [2.000, 2.500) = 2047 
    [2.500, 3.000) = 497 
    [3.000, 3.500) = 58 
    [3.500, 4.000) = 25 
    [4.000, 4.500) = 0 
    [4.500, 5.000) = 37 
    [5.000, 5.500) = 20 
    [5.500, 6.000) = 12 
    [6.000, 6.500) = 7 
    [6.500, 7.000) = 0 
    [7.000, 7.500) = 0 
    [7.500, 8.000) = 0 
    [8.000, 8.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.748 ms/op
     p(50.0000) =      1.745 ms/op
     p(90.0000) =      2.138 ms/op
     p(95.0000) =      2.413 ms/op
     p(99.0000) =      2.946 ms/op
     p(99.9000) =      5.802 ms/op
     p(99.9900) =      6.809 ms/op
     p(99.9990) =      8.651 ms/op
     p(99.9999) =      8.651 ms/op
    p(100.0000) =      8.651 ms/op


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
# Warmup Iteration   1: 4.463 ±(99.9%) 0.097 ms/op
Iteration   1: 2.810 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   1.128 ms/op
                 getUser·p0.50:   2.650 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.928 ms/op
                 getUser·p0.99:   5.055 ms/op
                 getUser·p0.999:  14.107 ms/op
                 getUser·p0.9999: 17.353 ms/op
                 getUser·p1.00:   17.367 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11391
  mean =      2.810 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 4558 
    [ 2.500,  3.750) = 6097 
    [ 3.750,  5.000) = 607 
    [ 5.000,  6.250) = 86 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.128 ms/op
     p(50.0000) =      2.650 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      5.055 ms/op
     p(99.9000) =     14.107 ms/op
     p(99.9900) =     17.353 ms/op
     p(99.9990) =     17.367 ms/op
     p(99.9999) =     17.367 ms/op
    p(100.0000) =     17.367 ms/op


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
# Warmup Iteration   1: 13.004 ±(99.9%) 0.395 ms/op
Iteration   1: 8.921 ±(99.9%) 0.136 ms/op
                 listUser·p0.00:   3.142 ms/op
                 listUser·p0.50:   8.602 ms/op
                 listUser·p0.90:   12.190 ms/op
                 listUser·p0.95:   13.091 ms/op
                 listUser·p0.99:   16.335 ms/op
                 listUser·p0.999:  23.024 ms/op
                 listUser·p0.9999: 25.002 ms/op
                 listUser·p1.00:   25.002 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3590
  mean =      8.921 ±(99.9%) 0.136 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 71 
    [ 5.000,  7.500) = 1099 
    [ 7.500, 10.000) = 1333 
    [10.000, 12.500) = 775 
    [12.500, 15.000) = 253 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      3.142 ms/op
     p(50.0000) =      8.602 ms/op
     p(90.0000) =     12.190 ms/op
     p(95.0000) =     13.091 ms/op
     p(99.0000) =     16.335 ms/op
     p(99.9000) =     23.024 ms/op
     p(99.9900) =     25.002 ms/op
     p(99.9990) =     25.002 ms/op
     p(99.9999) =     25.002 ms/op
    p(100.0000) =     25.002 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.301          ops/ms
Client.existUser                       thrpt         11.374          ops/ms
Client.getUser                         thrpt          9.011          ops/ms
Client.listUser                        thrpt          4.028          ops/ms
Client.createUser                       avgt          3.030           ms/op
Client.existUser                        avgt          2.095           ms/op
Client.getUser                          avgt          3.118           ms/op
Client.listUser                         avgt          8.708           ms/op
Client.createUser                     sample  10636   3.006 ± 0.057   ms/op
Client.createUser:createUser·p0.00    sample          0.898           ms/op
Client.createUser:createUser·p0.50    sample          2.732           ms/op
Client.createUser:createUser·p0.90    sample          3.412           ms/op
Client.createUser:createUser·p0.95    sample          4.067           ms/op
Client.createUser:createUser·p0.99    sample         12.184           ms/op
Client.createUser:createUser·p0.999   sample         21.463           ms/op
Client.createUser:createUser·p0.9999  sample         23.437           ms/op
Client.createUser:createUser·p1.00    sample         23.560           ms/op
Client.existUser                      sample  17780   1.801 ± 0.009   ms/op
Client.existUser:existUser·p0.00      sample          0.748           ms/op
Client.existUser:existUser·p0.50      sample          1.745           ms/op
Client.existUser:existUser·p0.90      sample          2.138           ms/op
Client.existUser:existUser·p0.95      sample          2.413           ms/op
Client.existUser:existUser·p0.99      sample          2.946           ms/op
Client.existUser:existUser·p0.999     sample          5.802           ms/op
Client.existUser:existUser·p0.9999    sample          6.809           ms/op
Client.existUser:existUser·p1.00      sample          8.651           ms/op
Client.getUser                        sample  11391   2.810 ± 0.027   ms/op
Client.getUser:getUser·p0.00          sample          1.128           ms/op
Client.getUser:getUser·p0.50          sample          2.650           ms/op
Client.getUser:getUser·p0.90          sample          3.527           ms/op
Client.getUser:getUser·p0.95          sample          3.928           ms/op
Client.getUser:getUser·p0.99          sample          5.055           ms/op
Client.getUser:getUser·p0.999         sample         14.107           ms/op
Client.getUser:getUser·p0.9999        sample         17.353           ms/op
Client.getUser:getUser·p1.00          sample         17.367           ms/op
Client.listUser                       sample   3590   8.921 ± 0.136   ms/op
Client.listUser:listUser·p0.00        sample          3.142           ms/op
Client.listUser:listUser·p0.50        sample          8.602           ms/op
Client.listUser:listUser·p0.90        sample         12.190           ms/op
Client.listUser:listUser·p0.95        sample         13.091           ms/op
Client.listUser:listUser·p0.99        sample         16.335           ms/op
Client.listUser:listUser·p0.999       sample         23.024           ms/op
Client.listUser:listUser·p0.9999      sample         25.002           ms/op
Client.listUser:listUser·p1.00        sample         25.002           ms/op
