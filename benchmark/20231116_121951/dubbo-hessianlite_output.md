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
# Warmup Iteration   1: 2.578 ops/ms
Iteration   1: 6.179 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.179 ops/ms


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
# Warmup Iteration   1: 7.020 ops/ms
Iteration   1: 14.488 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  14.488 ops/ms


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
# Warmup Iteration   1: 4.392 ops/ms
Iteration   1: 8.861 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.861 ops/ms


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
# Warmup Iteration   1: 2.320 ops/ms
Iteration   1: 3.699 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.699 ops/ms


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
# Warmup Iteration   1: 5.209 ±(99.9%) 0.068 ms/op
Iteration   1: 3.053 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.053 ms/op


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
# Warmup Iteration   1: 3.150 ±(99.9%) 0.029 ms/op
Iteration   1: 1.946 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.946 ms/op


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
# Warmup Iteration   1: 4.128 ±(99.9%) 0.045 ms/op
Iteration   1: 3.002 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.002 ms/op


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
# Warmup Iteration   1: 13.610 ±(99.9%) 0.266 ms/op
Iteration   1: 6.859 ±(99.9%) 0.066 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  6.859 ms/op


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
# Warmup Iteration   1: 4.920 ±(99.9%) 0.108 ms/op
Iteration   1: 3.268 ±(99.9%) 0.049 ms/op
                 createUser·p0.00:   0.923 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.887 ms/op
                 createUser·p0.95:   4.116 ms/op
                 createUser·p0.99:   7.104 ms/op
                 createUser·p0.999:  23.109 ms/op
                 createUser·p0.9999: 24.183 ms/op
                 createUser·p1.00:   24.183 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9779
  mean =      3.268 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1025 
    [ 2.500,  5.000) = 8598 
    [ 5.000,  7.500) = 60 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.923 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.116 ms/op
     p(99.0000) =      7.104 ms/op
     p(99.9000) =     23.109 ms/op
     p(99.9900) =     24.183 ms/op
     p(99.9990) =     24.183 ms/op
     p(99.9999) =     24.183 ms/op
    p(100.0000) =     24.183 ms/op


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
# Warmup Iteration   1: 3.042 ±(99.9%) 0.058 ms/op
Iteration   1: 1.678 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.758 ms/op
                 existUser·p0.50:   1.581 ms/op
                 existUser·p0.90:   2.191 ms/op
                 existUser·p0.95:   2.473 ms/op
                 existUser·p0.99:   3.338 ms/op
                 existUser·p0.999:  9.764 ms/op
                 existUser·p0.9999: 10.326 ms/op
                 existUser·p1.00:   11.141 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 19042
  mean =      1.678 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2149 
    [ 1.250,  2.500) = 16004 
    [ 2.500,  3.750) = 780 
    [ 3.750,  5.000) = 66 
    [ 5.000,  6.250) = 11 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 16 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.758 ms/op
     p(50.0000) =      1.581 ms/op
     p(90.0000) =      2.191 ms/op
     p(95.0000) =      2.473 ms/op
     p(99.0000) =      3.338 ms/op
     p(99.9000) =      9.764 ms/op
     p(99.9900) =     10.326 ms/op
     p(99.9990) =     11.141 ms/op
     p(99.9999) =     11.141 ms/op
    p(100.0000) =     11.141 ms/op


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
# Warmup Iteration   1: 4.284 ±(99.9%) 0.084 ms/op
Iteration   1: 2.984 ±(99.9%) 0.040 ms/op
                 getUser·p0.00:   1.077 ms/op
                 getUser·p0.50:   2.781 ms/op
                 getUser·p0.90:   3.615 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   5.569 ms/op
                 getUser·p0.999:  17.507 ms/op
                 getUser·p0.9999: 17.624 ms/op
                 getUser·p1.00:   17.629 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10724
  mean =      2.984 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 2710 
    [ 2.500,  3.750) = 7323 
    [ 3.750,  5.000) = 568 
    [ 5.000,  6.250) = 45 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 54 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.077 ms/op
     p(50.0000) =      2.781 ms/op
     p(90.0000) =      3.615 ms/op
     p(95.0000) =      3.854 ms/op
     p(99.0000) =      5.569 ms/op
     p(99.9000) =     17.507 ms/op
     p(99.9900) =     17.624 ms/op
     p(99.9990) =     17.629 ms/op
     p(99.9999) =     17.629 ms/op
    p(100.0000) =     17.629 ms/op


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
# Warmup Iteration   1: 10.381 ±(99.9%) 0.311 ms/op
Iteration   1: 8.129 ±(99.9%) 0.227 ms/op
                 listUser·p0.00:   2.761 ms/op
                 listUser·p0.50:   7.381 ms/op
                 listUser·p0.90:   10.371 ms/op
                 listUser·p0.95:   11.731 ms/op
                 listUser·p0.99:   26.923 ms/op
                 listUser·p0.999:  53.263 ms/op
                 listUser·p0.9999: 64.160 ms/op
                 listUser·p1.00:   64.160 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3937
  mean =      8.129 ±(99.9%) 0.227 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 177 
    [ 5.000, 10.000) = 3262 
    [10.000, 15.000) = 412 
    [15.000, 20.000) = 12 
    [20.000, 25.000) = 18 
    [25.000, 30.000) = 23 
    [30.000, 35.000) = 1 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 23 
    [45.000, 50.000) = 3 
    [50.000, 55.000) = 4 
    [55.000, 60.000) = 0 
    [60.000, 65.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.761 ms/op
     p(50.0000) =      7.381 ms/op
     p(90.0000) =     10.371 ms/op
     p(95.0000) =     11.731 ms/op
     p(99.0000) =     26.923 ms/op
     p(99.9000) =     53.263 ms/op
     p(99.9900) =     64.160 ms/op
     p(99.9990) =     64.160 ms/op
     p(99.9999) =     64.160 ms/op
    p(100.0000) =     64.160 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.179          ops/ms
Client.existUser                       thrpt         14.488          ops/ms
Client.getUser                         thrpt          8.861          ops/ms
Client.listUser                        thrpt          3.699          ops/ms
Client.createUser                       avgt          3.053           ms/op
Client.existUser                        avgt          1.946           ms/op
Client.getUser                          avgt          3.002           ms/op
Client.listUser                         avgt          6.859           ms/op
Client.createUser                     sample   9779   3.268 ± 0.049   ms/op
Client.createUser:createUser·p0.00    sample          0.923           ms/op
Client.createUser:createUser·p0.50    sample          3.121           ms/op
Client.createUser:createUser·p0.90    sample          3.887           ms/op
Client.createUser:createUser·p0.95    sample          4.116           ms/op
Client.createUser:createUser·p0.99    sample          7.104           ms/op
Client.createUser:createUser·p0.999   sample         23.109           ms/op
Client.createUser:createUser·p0.9999  sample         24.183           ms/op
Client.createUser:createUser·p1.00    sample         24.183           ms/op
Client.existUser                      sample  19042   1.678 ± 0.013   ms/op
Client.existUser:existUser·p0.00      sample          0.758           ms/op
Client.existUser:existUser·p0.50      sample          1.581           ms/op
Client.existUser:existUser·p0.90      sample          2.191           ms/op
Client.existUser:existUser·p0.95      sample          2.473           ms/op
Client.existUser:existUser·p0.99      sample          3.338           ms/op
Client.existUser:existUser·p0.999     sample          9.764           ms/op
Client.existUser:existUser·p0.9999    sample         10.326           ms/op
Client.existUser:existUser·p1.00      sample         11.141           ms/op
Client.getUser                        sample  10724   2.984 ± 0.040   ms/op
Client.getUser:getUser·p0.00          sample          1.077           ms/op
Client.getUser:getUser·p0.50          sample          2.781           ms/op
Client.getUser:getUser·p0.90          sample          3.615           ms/op
Client.getUser:getUser·p0.95          sample          3.854           ms/op
Client.getUser:getUser·p0.99          sample          5.569           ms/op
Client.getUser:getUser·p0.999         sample         17.507           ms/op
Client.getUser:getUser·p0.9999        sample         17.624           ms/op
Client.getUser:getUser·p1.00          sample         17.629           ms/op
Client.listUser                       sample   3937   8.129 ± 0.227   ms/op
Client.listUser:listUser·p0.00        sample          2.761           ms/op
Client.listUser:listUser·p0.50        sample          7.381           ms/op
Client.listUser:listUser·p0.90        sample         10.371           ms/op
Client.listUser:listUser·p0.95        sample         11.731           ms/op
Client.listUser:listUser·p0.99        sample         26.923           ms/op
Client.listUser:listUser·p0.999       sample         53.263           ms/op
Client.listUser:listUser·p0.9999      sample         64.160           ms/op
Client.listUser:listUser·p1.00        sample         64.160           ms/op
