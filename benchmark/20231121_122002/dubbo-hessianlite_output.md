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
# Warmup Iteration   1: 2.567 ops/ms
Iteration   1: 6.365 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.365 ops/ms


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
# Warmup Iteration   1: 5.527 ops/ms
Iteration   1: 12.462 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.462 ops/ms


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
# Warmup Iteration   1: 4.118 ops/ms
Iteration   1: 8.472 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.472 ops/ms


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
# Warmup Iteration   1: 2.578 ops/ms
Iteration   1: 3.452 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.452 ops/ms


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
# Warmup Iteration   1: 5.204 ±(99.9%) 0.108 ms/op
Iteration   1: 2.836 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.836 ms/op


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
# Warmup Iteration   1: 3.284 ±(99.9%) 0.040 ms/op
Iteration   1: 1.980 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.980 ms/op


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
# Warmup Iteration   1: 4.475 ±(99.9%) 0.051 ms/op
Iteration   1: 2.994 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.994 ms/op


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
# Warmup Iteration   1: 12.880 ±(99.9%) 0.290 ms/op
Iteration   1: 8.348 ±(99.9%) 0.101 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.348 ms/op


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
# Warmup Iteration   1: 4.745 ±(99.9%) 0.081 ms/op
Iteration   1: 2.897 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   1.155 ms/op
                 createUser·p0.50:   2.695 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   5.195 ms/op
                 createUser·p0.999:  14.057 ms/op
                 createUser·p0.9999: 14.251 ms/op
                 createUser·p1.00:   14.270 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11187
  mean =      2.897 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 2605 
    [ 2.500,  3.750) = 7943 
    [ 3.750,  5.000) = 495 
    [ 5.000,  6.250) = 88 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.155 ms/op
     p(50.0000) =      2.695 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      5.195 ms/op
     p(99.9000) =     14.057 ms/op
     p(99.9900) =     14.251 ms/op
     p(99.9990) =     14.270 ms/op
     p(99.9999) =     14.270 ms/op
    p(100.0000) =     14.270 ms/op


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
# Warmup Iteration   1: 2.987 ±(99.9%) 0.066 ms/op
Iteration   1: 1.874 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.668 ms/op
                 existUser·p0.50:   1.735 ms/op
                 existUser·p0.90:   2.515 ms/op
                 existUser·p0.95:   2.798 ms/op
                 existUser·p0.99:   3.448 ms/op
                 existUser·p0.999:  6.189 ms/op
                 existUser·p0.9999: 6.954 ms/op
                 existUser·p1.00:   7.012 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17106
  mean =      1.874 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 188 
    [1.000, 1.500) = 2736 
    [1.500, 2.000) = 9275 
    [2.000, 2.500) = 3118 
    [2.500, 3.000) = 1347 
    [3.000, 3.500) = 285 
    [3.500, 4.000) = 15 
    [4.000, 4.500) = 10 
    [4.500, 5.000) = 20 
    [5.000, 5.500) = 53 
    [5.500, 6.000) = 37 
    [6.000, 6.500) = 14 
    [6.500, 7.000) = 7 
    [7.000, 7.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.668 ms/op
     p(50.0000) =      1.735 ms/op
     p(90.0000) =      2.515 ms/op
     p(95.0000) =      2.798 ms/op
     p(99.0000) =      3.448 ms/op
     p(99.9000) =      6.189 ms/op
     p(99.9900) =      6.954 ms/op
     p(99.9990) =      7.012 ms/op
     p(99.9999) =      7.012 ms/op
    p(100.0000) =      7.012 ms/op


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
# Warmup Iteration   1: 4.574 ±(99.9%) 0.094 ms/op
Iteration   1: 3.030 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.892 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.858 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   5.677 ms/op
                 getUser·p0.999:  12.712 ms/op
                 getUser·p0.9999: 12.812 ms/op
                 getUser·p1.00:   12.812 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10560
  mean =      3.030 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 17 
    [ 1.250,  2.500) = 2540 
    [ 2.500,  3.750) = 6759 
    [ 3.750,  5.000) = 1055 
    [ 5.000,  6.250) = 95 
    [ 6.250,  7.500) = 58 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.892 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =     12.712 ms/op
     p(99.9900) =     12.812 ms/op
     p(99.9990) =     12.812 ms/op
     p(99.9999) =     12.812 ms/op
    p(100.0000) =     12.812 ms/op


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
# Warmup Iteration   1: 11.352 ±(99.9%) 0.427 ms/op
Iteration   1: 7.102 ±(99.9%) 0.121 ms/op
                 listUser·p0.00:   2.159 ms/op
                 listUser·p0.50:   6.775 ms/op
                 listUser·p0.90:   8.897 ms/op
                 listUser·p0.95:   10.265 ms/op
                 listUser·p0.99:   19.232 ms/op
                 listUser·p0.999:  27.610 ms/op
                 listUser·p0.9999: 41.288 ms/op
                 listUser·p1.00:   41.288 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4508
  mean =      7.102 ±(99.9%) 0.121 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 408 
    [ 5.000, 10.000) = 3847 
    [10.000, 15.000) = 163 
    [15.000, 20.000) = 58 
    [20.000, 25.000) = 27 
    [25.000, 30.000) = 2 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.159 ms/op
     p(50.0000) =      6.775 ms/op
     p(90.0000) =      8.897 ms/op
     p(95.0000) =     10.265 ms/op
     p(99.0000) =     19.232 ms/op
     p(99.9000) =     27.610 ms/op
     p(99.9900) =     41.288 ms/op
     p(99.9990) =     41.288 ms/op
     p(99.9999) =     41.288 ms/op
    p(100.0000) =     41.288 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.365          ops/ms
Client.existUser                       thrpt         12.462          ops/ms
Client.getUser                         thrpt          8.472          ops/ms
Client.listUser                        thrpt          3.452          ops/ms
Client.createUser                       avgt          2.836           ms/op
Client.existUser                        avgt          1.980           ms/op
Client.getUser                          avgt          2.994           ms/op
Client.listUser                         avgt          8.348           ms/op
Client.createUser                     sample  11187   2.897 ± 0.025   ms/op
Client.createUser:createUser·p0.00    sample          1.155           ms/op
Client.createUser:createUser·p0.50    sample          2.695           ms/op
Client.createUser:createUser·p0.90    sample          3.559           ms/op
Client.createUser:createUser·p0.95    sample          3.789           ms/op
Client.createUser:createUser·p0.99    sample          5.195           ms/op
Client.createUser:createUser·p0.999   sample         14.057           ms/op
Client.createUser:createUser·p0.9999  sample         14.251           ms/op
Client.createUser:createUser·p1.00    sample         14.270           ms/op
Client.existUser                      sample  17106   1.874 ± 0.014   ms/op
Client.existUser:existUser·p0.00      sample          0.668           ms/op
Client.existUser:existUser·p0.50      sample          1.735           ms/op
Client.existUser:existUser·p0.90      sample          2.515           ms/op
Client.existUser:existUser·p0.95      sample          2.798           ms/op
Client.existUser:existUser·p0.99      sample          3.448           ms/op
Client.existUser:existUser·p0.999     sample          6.189           ms/op
Client.existUser:existUser·p0.9999    sample          6.954           ms/op
Client.existUser:existUser·p1.00      sample          7.012           ms/op
Client.getUser                        sample  10560   3.030 ± 0.029   ms/op
Client.getUser:getUser·p0.00          sample          0.892           ms/op
Client.getUser:getUser·p0.50          sample          2.974           ms/op
Client.getUser:getUser·p0.90          sample          3.858           ms/op
Client.getUser:getUser·p0.95          sample          4.252           ms/op
Client.getUser:getUser·p0.99          sample          5.677           ms/op
Client.getUser:getUser·p0.999         sample         12.712           ms/op
Client.getUser:getUser·p0.9999        sample         12.812           ms/op
Client.getUser:getUser·p1.00          sample         12.812           ms/op
Client.listUser                       sample   4508   7.102 ± 0.121   ms/op
Client.listUser:listUser·p0.00        sample          2.159           ms/op
Client.listUser:listUser·p0.50        sample          6.775           ms/op
Client.listUser:listUser·p0.90        sample          8.897           ms/op
Client.listUser:listUser·p0.95        sample         10.265           ms/op
Client.listUser:listUser·p0.99        sample         19.232           ms/op
Client.listUser:listUser·p0.999       sample         27.610           ms/op
Client.listUser:listUser·p0.9999      sample         41.288           ms/op
Client.listUser:listUser·p1.00        sample         41.288           ms/op
