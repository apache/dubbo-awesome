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
# Warmup Iteration   1: 2.054 ops/ms
Iteration   1: 6.097 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.097 ops/ms


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
# Warmup Iteration   1: 5.805 ops/ms
Iteration   1: 12.088 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.088 ops/ms


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
# Warmup Iteration   1: 3.577 ops/ms
Iteration   1: 8.381 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.381 ops/ms


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
# Warmup Iteration   1: 1.872 ops/ms
Iteration   1: 3.434 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.434 ops/ms


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
# Warmup Iteration   1: 6.533 ±(99.9%) 0.104 ms/op
Iteration   1: 3.583 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.583 ms/op


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
# Warmup Iteration   1: 3.617 ±(99.9%) 0.047 ms/op
Iteration   1: 1.925 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.925 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.560 ±(99.9%) 0.053 ms/op
Iteration   1: 2.871 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.871 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 13.518 ±(99.9%) 0.233 ms/op
Iteration   1: 9.811 ±(99.9%) 0.093 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.811 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 5.347 ±(99.9%) 0.107 ms/op
Iteration   1: 2.914 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   1.133 ms/op
                 createUser·p0.50:   2.683 ms/op
                 createUser·p0.90:   3.695 ms/op
                 createUser·p0.95:   4.225 ms/op
                 createUser·p0.99:   5.612 ms/op
                 createUser·p0.999:  15.499 ms/op
                 createUser·p0.9999: 16.269 ms/op
                 createUser·p1.00:   16.335 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10963
  mean =      2.914 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 2990 
    [ 2.500,  3.750) = 6979 
    [ 3.750,  5.000) = 743 
    [ 5.000,  6.250) = 175 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.133 ms/op
     p(50.0000) =      2.683 ms/op
     p(90.0000) =      3.695 ms/op
     p(95.0000) =      4.225 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =     15.499 ms/op
     p(99.9900) =     16.269 ms/op
     p(99.9990) =     16.335 ms/op
     p(99.9999) =     16.335 ms/op
    p(100.0000) =     16.335 ms/op


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
# Warmup Iteration   1: 3.246 ±(99.9%) 0.080 ms/op
Iteration   1: 1.879 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   0.377 ms/op
                 existUser·p0.50:   1.800 ms/op
                 existUser·p0.90:   2.322 ms/op
                 existUser·p0.95:   2.499 ms/op
                 existUser·p0.99:   3.944 ms/op
                 existUser·p0.999:  24.837 ms/op
                 existUser·p0.9999: 25.883 ms/op
                 existUser·p1.00:   25.952 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17024
  mean =      1.879 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16180 
    [ 2.500,  5.000) = 709 
    [ 5.000,  7.500) = 103 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.377 ms/op
     p(50.0000) =      1.800 ms/op
     p(90.0000) =      2.322 ms/op
     p(95.0000) =      2.499 ms/op
     p(99.0000) =      3.944 ms/op
     p(99.9000) =     24.837 ms/op
     p(99.9900) =     25.883 ms/op
     p(99.9990) =     25.952 ms/op
     p(99.9999) =     25.952 ms/op
    p(100.0000) =     25.952 ms/op


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
# Warmup Iteration   1: 4.584 ±(99.9%) 0.110 ms/op
Iteration   1: 3.131 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.873 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   4.108 ms/op
                 getUser·p0.95:   4.407 ms/op
                 getUser·p0.99:   5.104 ms/op
                 getUser·p0.999:  6.771 ms/op
                 getUser·p0.9999: 8.945 ms/op
                 getUser·p1.00:   8.946 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10229
  mean =      3.131 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 1 
    [1.000, 1.500) = 32 
    [1.500, 2.000) = 359 
    [2.000, 2.500) = 1691 
    [2.500, 3.000) = 2791 
    [3.000, 3.500) = 2386 
    [3.500, 4.000) = 1706 
    [4.000, 4.500) = 881 
    [4.500, 5.000) = 232 
    [5.000, 5.500) = 86 
    [5.500, 6.000) = 13 
    [6.000, 6.500) = 26 
    [6.500, 7.000) = 20 
    [7.000, 7.500) = 0 
    [7.500, 8.000) = 0 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.873 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      4.108 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.104 ms/op
     p(99.9000) =      6.771 ms/op
     p(99.9900) =      8.945 ms/op
     p(99.9990) =      8.946 ms/op
     p(99.9999) =      8.946 ms/op
    p(100.0000) =      8.946 ms/op


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
# Warmup Iteration   1: 13.096 ±(99.9%) 0.446 ms/op
Iteration   1: 8.566 ±(99.9%) 0.126 ms/op
                 listUser·p0.00:   1.974 ms/op
                 listUser·p0.50:   8.311 ms/op
                 listUser·p0.90:   11.387 ms/op
                 listUser·p0.95:   12.386 ms/op
                 listUser·p0.99:   15.734 ms/op
                 listUser·p0.999:  21.692 ms/op
                 listUser·p0.9999: 26.345 ms/op
                 listUser·p1.00:   26.345 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3782
  mean =      8.566 ±(99.9%) 0.126 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 108 
    [ 5.000,  7.500) = 1103 
    [ 7.500, 10.000) = 1813 
    [10.000, 12.500) = 582 
    [12.500, 15.000) = 130 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.974 ms/op
     p(50.0000) =      8.311 ms/op
     p(90.0000) =     11.387 ms/op
     p(95.0000) =     12.386 ms/op
     p(99.0000) =     15.734 ms/op
     p(99.9000) =     21.692 ms/op
     p(99.9900) =     26.345 ms/op
     p(99.9990) =     26.345 ms/op
     p(99.9999) =     26.345 ms/op
    p(100.0000) =     26.345 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.097          ops/ms
Client.existUser                       thrpt         12.088          ops/ms
Client.getUser                         thrpt          8.381          ops/ms
Client.listUser                        thrpt          3.434          ops/ms
Client.createUser                       avgt          3.583           ms/op
Client.existUser                        avgt          1.925           ms/op
Client.getUser                          avgt          2.871           ms/op
Client.listUser                         avgt          9.811           ms/op
Client.createUser                     sample  10963   2.914 ± 0.030   ms/op
Client.createUser:createUser·p0.00    sample          1.133           ms/op
Client.createUser:createUser·p0.50    sample          2.683           ms/op
Client.createUser:createUser·p0.90    sample          3.695           ms/op
Client.createUser:createUser·p0.95    sample          4.225           ms/op
Client.createUser:createUser·p0.99    sample          5.612           ms/op
Client.createUser:createUser·p0.999   sample         15.499           ms/op
Client.createUser:createUser·p0.9999  sample         16.269           ms/op
Client.createUser:createUser·p1.00    sample         16.335           ms/op
Client.existUser                      sample  17024   1.879 ± 0.028   ms/op
Client.existUser:existUser·p0.00      sample          0.377           ms/op
Client.existUser:existUser·p0.50      sample          1.800           ms/op
Client.existUser:existUser·p0.90      sample          2.322           ms/op
Client.existUser:existUser·p0.95      sample          2.499           ms/op
Client.existUser:existUser·p0.99      sample          3.944           ms/op
Client.existUser:existUser·p0.999     sample         24.837           ms/op
Client.existUser:existUser·p0.9999    sample         25.883           ms/op
Client.existUser:existUser·p1.00      sample         25.952           ms/op
Client.getUser                        sample  10229   3.131 ± 0.025   ms/op
Client.getUser:getUser·p0.00          sample          0.873           ms/op
Client.getUser:getUser·p0.50          sample          3.052           ms/op
Client.getUser:getUser·p0.90          sample          4.108           ms/op
Client.getUser:getUser·p0.95          sample          4.407           ms/op
Client.getUser:getUser·p0.99          sample          5.104           ms/op
Client.getUser:getUser·p0.999         sample          6.771           ms/op
Client.getUser:getUser·p0.9999        sample          8.945           ms/op
Client.getUser:getUser·p1.00          sample          8.946           ms/op
Client.listUser                       sample   3782   8.566 ± 0.126   ms/op
Client.listUser:listUser·p0.00        sample          1.974           ms/op
Client.listUser:listUser·p0.50        sample          8.311           ms/op
Client.listUser:listUser·p0.90        sample         11.387           ms/op
Client.listUser:listUser·p0.95        sample         12.386           ms/op
Client.listUser:listUser·p0.99        sample         15.734           ms/op
Client.listUser:listUser·p0.999       sample         21.692           ms/op
Client.listUser:listUser·p0.9999      sample         26.345           ms/op
Client.listUser:listUser·p1.00        sample         26.345           ms/op
