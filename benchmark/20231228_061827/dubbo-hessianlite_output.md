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
# Warmup Iteration   1: 2.629 ops/ms
Iteration   1: 6.401 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.401 ops/ms


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
# Warmup Iteration   1: 6.152 ops/ms
Iteration   1: 12.389 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.389 ops/ms


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
# Warmup Iteration   1: 3.756 ops/ms
Iteration   1: 7.523 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.523 ops/ms


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
# Warmup Iteration   1: 2.330 ops/ms
Iteration   1: 3.598 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.598 ops/ms


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
# Warmup Iteration   1: 5.558 ±(99.9%) 0.062 ms/op
Iteration   1: 2.699 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.699 ms/op


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
# Warmup Iteration   1: 2.970 ±(99.9%) 0.027 ms/op
Iteration   1: 1.835 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.835 ms/op


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
# Warmup Iteration   1: 4.667 ±(99.9%) 0.055 ms/op
Iteration   1: 2.820 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.820 ms/op


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
# Warmup Iteration   1: 11.446 ±(99.9%) 0.170 ms/op
Iteration   1: 8.466 ±(99.9%) 0.120 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.466 ms/op


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
# Warmup Iteration   1: 5.068 ±(99.9%) 0.096 ms/op
Iteration   1: 2.841 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.968 ms/op
                 createUser·p0.50:   2.679 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   4.165 ms/op
                 createUser·p0.99:   6.590 ms/op
                 createUser·p0.999:  12.333 ms/op
                 createUser·p0.9999: 12.698 ms/op
                 createUser·p1.00:   12.698 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11262
  mean =      2.841 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 30 
    [ 1.250,  2.500) = 4130 
    [ 2.500,  3.750) = 6102 
    [ 3.750,  5.000) = 774 
    [ 5.000,  6.250) = 114 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 22 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.968 ms/op
     p(50.0000) =      2.679 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      4.165 ms/op
     p(99.0000) =      6.590 ms/op
     p(99.9000) =     12.333 ms/op
     p(99.9900) =     12.698 ms/op
     p(99.9990) =     12.698 ms/op
     p(99.9999) =     12.698 ms/op
    p(100.0000) =     12.698 ms/op


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
# Warmup Iteration   1: 2.973 ±(99.9%) 0.070 ms/op
Iteration   1: 1.693 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.507 ms/op
                 existUser·p0.50:   1.638 ms/op
                 existUser·p0.90:   2.030 ms/op
                 existUser·p0.95:   2.191 ms/op
                 existUser·p0.99:   2.650 ms/op
                 existUser·p0.999:  5.916 ms/op
                 existUser·p0.9999: 6.323 ms/op
                 existUser·p1.00:   6.578 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18890
  mean =      1.693 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 104 
    [1.000, 1.500) = 4366 
    [1.500, 2.000) = 12249 
    [2.000, 2.500) = 1858 
    [2.500, 3.000) = 187 
    [3.000, 3.500) = 72 
    [3.500, 4.000) = 17 
    [4.000, 4.500) = 4 
    [4.500, 5.000) = 1 
    [5.000, 5.500) = 0 
    [5.500, 6.000) = 28 
    [6.000, 6.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.507 ms/op
     p(50.0000) =      1.638 ms/op
     p(90.0000) =      2.030 ms/op
     p(95.0000) =      2.191 ms/op
     p(99.0000) =      2.650 ms/op
     p(99.9000) =      5.916 ms/op
     p(99.9900) =      6.323 ms/op
     p(99.9990) =      6.578 ms/op
     p(99.9999) =      6.578 ms/op
    p(100.0000) =      6.578 ms/op


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
# Warmup Iteration   1: 4.873 ±(99.9%) 0.118 ms/op
Iteration   1: 2.995 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.916 ms/op
                 getUser·p0.50:   2.937 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   4.061 ms/op
                 getUser·p0.99:   5.866 ms/op
                 getUser·p0.999:  7.348 ms/op
                 getUser·p0.9999: 9.857 ms/op
                 getUser·p1.00:   9.994 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10688
  mean =      2.995 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 3 
    [ 1.000,  2.000) = 273 
    [ 2.000,  3.000) = 5498 
    [ 3.000,  4.000) = 4320 
    [ 4.000,  5.000) = 407 
    [ 5.000,  6.000) = 95 
    [ 6.000,  7.000) = 65 
    [ 7.000,  8.000) = 26 
    [ 8.000,  9.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.916 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      4.061 ms/op
     p(99.0000) =      5.866 ms/op
     p(99.9000) =      7.348 ms/op
     p(99.9900) =      9.857 ms/op
     p(99.9990) =      9.994 ms/op
     p(99.9999) =      9.994 ms/op
    p(100.0000) =      9.994 ms/op


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
# Warmup Iteration   1: 12.807 ±(99.9%) 0.461 ms/op
Iteration   1: 8.215 ±(99.9%) 0.113 ms/op
                 listUser·p0.00:   2.687 ms/op
                 listUser·p0.50:   7.987 ms/op
                 listUser·p0.90:   10.650 ms/op
                 listUser·p0.95:   11.518 ms/op
                 listUser·p0.99:   16.095 ms/op
                 listUser·p0.999:  18.057 ms/op
                 listUser·p0.9999: 18.874 ms/op
                 listUser·p1.00:   18.874 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3893
  mean =      8.215 ±(99.9%) 0.113 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 0 
    [ 2.500,  3.750) = 17 
    [ 3.750,  5.000) = 140 
    [ 5.000,  6.250) = 482 
    [ 6.250,  7.500) = 843 
    [ 7.500,  8.750) = 1032 
    [ 8.750, 10.000) = 763 
    [10.000, 11.250) = 384 
    [11.250, 12.500) = 95 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 62 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      2.687 ms/op
     p(50.0000) =      7.987 ms/op
     p(90.0000) =     10.650 ms/op
     p(95.0000) =     11.518 ms/op
     p(99.0000) =     16.095 ms/op
     p(99.9000) =     18.057 ms/op
     p(99.9900) =     18.874 ms/op
     p(99.9990) =     18.874 ms/op
     p(99.9999) =     18.874 ms/op
    p(100.0000) =     18.874 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.401          ops/ms
Client.existUser                       thrpt         12.389          ops/ms
Client.getUser                         thrpt          7.523          ops/ms
Client.listUser                        thrpt          3.598          ops/ms
Client.createUser                       avgt          2.699           ms/op
Client.existUser                        avgt          1.835           ms/op
Client.getUser                          avgt          2.820           ms/op
Client.listUser                         avgt          8.466           ms/op
Client.createUser                     sample  11262   2.841 ± 0.030   ms/op
Client.createUser:createUser·p0.00    sample          0.968           ms/op
Client.createUser:createUser·p0.50    sample          2.679           ms/op
Client.createUser:createUser·p0.90    sample          3.674           ms/op
Client.createUser:createUser·p0.95    sample          4.165           ms/op
Client.createUser:createUser·p0.99    sample          6.590           ms/op
Client.createUser:createUser·p0.999   sample         12.333           ms/op
Client.createUser:createUser·p0.9999  sample         12.698           ms/op
Client.createUser:createUser·p1.00    sample         12.698           ms/op
Client.existUser                      sample  18890   1.693 ± 0.008   ms/op
Client.existUser:existUser·p0.00      sample          0.507           ms/op
Client.existUser:existUser·p0.50      sample          1.638           ms/op
Client.existUser:existUser·p0.90      sample          2.030           ms/op
Client.existUser:existUser·p0.95      sample          2.191           ms/op
Client.existUser:existUser·p0.99      sample          2.650           ms/op
Client.existUser:existUser·p0.999     sample          5.916           ms/op
Client.existUser:existUser·p0.9999    sample          6.323           ms/op
Client.existUser:existUser·p1.00      sample          6.578           ms/op
Client.getUser                        sample  10688   2.995 ± 0.023   ms/op
Client.getUser:getUser·p0.00          sample          0.916           ms/op
Client.getUser:getUser·p0.50          sample          2.937           ms/op
Client.getUser:getUser·p0.90          sample          3.744           ms/op
Client.getUser:getUser·p0.95          sample          4.061           ms/op
Client.getUser:getUser·p0.99          sample          5.866           ms/op
Client.getUser:getUser·p0.999         sample          7.348           ms/op
Client.getUser:getUser·p0.9999        sample          9.857           ms/op
Client.getUser:getUser·p1.00          sample          9.994           ms/op
Client.listUser                       sample   3893   8.215 ± 0.113   ms/op
Client.listUser:listUser·p0.00        sample          2.687           ms/op
Client.listUser:listUser·p0.50        sample          7.987           ms/op
Client.listUser:listUser·p0.90        sample         10.650           ms/op
Client.listUser:listUser·p0.95        sample         11.518           ms/op
Client.listUser:listUser·p0.99        sample         16.095           ms/op
Client.listUser:listUser·p0.999       sample         18.057           ms/op
Client.listUser:listUser·p0.9999      sample         18.874           ms/op
Client.listUser:listUser·p1.00        sample         18.874           ms/op
