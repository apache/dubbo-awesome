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
# Warmup Iteration   1: 2.540 ops/ms
Iteration   1: 5.677 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.677 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.928 ops/ms
Iteration   1: 12.138 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.138 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.361 ops/ms
Iteration   1: 9.732 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.732 ops/ms


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
# Warmup Iteration   1: 2.295 ops/ms
Iteration   1: 3.364 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.364 ops/ms


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
# Warmup Iteration   1: 5.268 ±(99.9%) 0.063 ms/op
Iteration   1: 2.839 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.839 ms/op


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
# Warmup Iteration   1: 3.097 ±(99.9%) 0.035 ms/op
Iteration   1: 1.971 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.971 ms/op


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
# Warmup Iteration   1: 4.774 ±(99.9%) 0.067 ms/op
Iteration   1: 2.649 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.649 ms/op


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
# Warmup Iteration   1: 11.854 ±(99.9%) 0.321 ms/op
Iteration   1: 8.408 ±(99.9%) 0.106 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.408 ms/op


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
# Warmup Iteration   1: 5.152 ±(99.9%) 0.102 ms/op
Iteration   1: 3.284 ±(99.9%) 0.064 ms/op
                 createUser·p0.00:   1.031 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   4.108 ms/op
                 createUser·p0.95:   4.579 ms/op
                 createUser·p0.99:   6.761 ms/op
                 createUser·p0.999:  32.801 ms/op
                 createUser·p0.9999: 33.620 ms/op
                 createUser·p1.00:   33.620 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9769
  mean =      3.284 ±(99.9%) 0.064 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1999 
    [ 2.500,  5.000) = 7443 
    [ 5.000,  7.500) = 246 
    [ 7.500, 10.000) = 33 
    [10.000, 12.500) = 16 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.031 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      4.108 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      6.761 ms/op
     p(99.9000) =     32.801 ms/op
     p(99.9900) =     33.620 ms/op
     p(99.9990) =     33.620 ms/op
     p(99.9999) =     33.620 ms/op
    p(100.0000) =     33.620 ms/op


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
# Warmup Iteration   1: 2.968 ±(99.9%) 0.057 ms/op
Iteration   1: 1.837 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.510 ms/op
                 existUser·p0.50:   1.774 ms/op
                 existUser·p0.90:   2.351 ms/op
                 existUser·p0.95:   2.523 ms/op
                 existUser·p0.99:   2.977 ms/op
                 existUser·p0.999:  4.373 ms/op
                 existUser·p0.9999: 6.380 ms/op
                 existUser·p1.00:   6.406 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18127
  mean =      1.837 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 84 
    [1.000, 1.500) = 3496 
    [1.500, 2.000) = 9028 
    [2.000, 2.500) = 4506 
    [2.500, 3.000) = 842 
    [3.000, 3.500) = 80 
    [3.500, 4.000) = 43 
    [4.000, 4.500) = 36 
    [4.500, 5.000) = 2 
    [5.000, 5.500) = 0 
    [5.500, 6.000) = 6 
    [6.000, 6.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.510 ms/op
     p(50.0000) =      1.774 ms/op
     p(90.0000) =      2.351 ms/op
     p(95.0000) =      2.523 ms/op
     p(99.0000) =      2.977 ms/op
     p(99.9000) =      4.373 ms/op
     p(99.9900) =      6.380 ms/op
     p(99.9990) =      6.406 ms/op
     p(99.9999) =      6.406 ms/op
    p(100.0000) =      6.406 ms/op


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
# Warmup Iteration   1: 4.463 ±(99.9%) 0.110 ms/op
Iteration   1: 3.211 ±(99.9%) 0.063 ms/op
                 getUser·p0.00:   0.950 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.928 ms/op
                 getUser·p0.95:   4.370 ms/op
                 getUser·p0.99:   6.358 ms/op
                 getUser·p0.999:  34.406 ms/op
                 getUser·p0.9999: 35.062 ms/op
                 getUser·p1.00:   35.062 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9990
  mean =      3.211 ±(99.9%) 0.063 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2124 
    [ 2.500,  5.000) = 7600 
    [ 5.000,  7.500) = 195 
    [ 7.500, 10.000) = 39 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.950 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.370 ms/op
     p(99.0000) =      6.358 ms/op
     p(99.9000) =     34.406 ms/op
     p(99.9900) =     35.062 ms/op
     p(99.9990) =     35.062 ms/op
     p(99.9999) =     35.062 ms/op
    p(100.0000) =     35.062 ms/op


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
# Warmup Iteration   1: 12.539 ±(99.9%) 0.405 ms/op
Iteration   1: 8.200 ±(99.9%) 0.128 ms/op
                 listUser·p0.00:   1.337 ms/op
                 listUser·p0.50:   7.791 ms/op
                 listUser·p0.90:   10.953 ms/op
                 listUser·p0.95:   12.009 ms/op
                 listUser·p0.99:   16.283 ms/op
                 listUser·p0.999:  22.537 ms/op
                 listUser·p0.9999: 22.938 ms/op
                 listUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3904
  mean =      8.200 ±(99.9%) 0.128 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 134 
    [ 5.000,  7.500) = 1575 
    [ 7.500, 10.000) = 1484 
    [10.000, 12.500) = 555 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.337 ms/op
     p(50.0000) =      7.791 ms/op
     p(90.0000) =     10.953 ms/op
     p(95.0000) =     12.009 ms/op
     p(99.0000) =     16.283 ms/op
     p(99.9000) =     22.537 ms/op
     p(99.9900) =     22.938 ms/op
     p(99.9990) =     22.938 ms/op
     p(99.9999) =     22.938 ms/op
    p(100.0000) =     22.938 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.677          ops/ms
Client.existUser                       thrpt         12.138          ops/ms
Client.getUser                         thrpt          9.732          ops/ms
Client.listUser                        thrpt          3.364          ops/ms
Client.createUser                       avgt          2.839           ms/op
Client.existUser                        avgt          1.971           ms/op
Client.getUser                          avgt          2.649           ms/op
Client.listUser                         avgt          8.408           ms/op
Client.createUser                     sample   9769   3.284 ± 0.064   ms/op
Client.createUser:createUser·p0.00    sample          1.031           ms/op
Client.createUser:createUser·p0.50    sample          3.056           ms/op
Client.createUser:createUser·p0.90    sample          4.108           ms/op
Client.createUser:createUser·p0.95    sample          4.579           ms/op
Client.createUser:createUser·p0.99    sample          6.761           ms/op
Client.createUser:createUser·p0.999   sample         32.801           ms/op
Client.createUser:createUser·p0.9999  sample         33.620           ms/op
Client.createUser:createUser·p1.00    sample         33.620           ms/op
Client.existUser                      sample  18127   1.837 ± 0.010   ms/op
Client.existUser:existUser·p0.00      sample          0.510           ms/op
Client.existUser:existUser·p0.50      sample          1.774           ms/op
Client.existUser:existUser·p0.90      sample          2.351           ms/op
Client.existUser:existUser·p0.95      sample          2.523           ms/op
Client.existUser:existUser·p0.99      sample          2.977           ms/op
Client.existUser:existUser·p0.999     sample          4.373           ms/op
Client.existUser:existUser·p0.9999    sample          6.380           ms/op
Client.existUser:existUser·p1.00      sample          6.406           ms/op
Client.getUser                        sample   9990   3.211 ± 0.063   ms/op
Client.getUser:getUser·p0.00          sample          0.950           ms/op
Client.getUser:getUser·p0.50          sample          3.064           ms/op
Client.getUser:getUser·p0.90          sample          3.928           ms/op
Client.getUser:getUser·p0.95          sample          4.370           ms/op
Client.getUser:getUser·p0.99          sample          6.358           ms/op
Client.getUser:getUser·p0.999         sample         34.406           ms/op
Client.getUser:getUser·p0.9999        sample         35.062           ms/op
Client.getUser:getUser·p1.00          sample         35.062           ms/op
Client.listUser                       sample   3904   8.200 ± 0.128   ms/op
Client.listUser:listUser·p0.00        sample          1.337           ms/op
Client.listUser:listUser·p0.50        sample          7.791           ms/op
Client.listUser:listUser·p0.90        sample         10.953           ms/op
Client.listUser:listUser·p0.95        sample         12.009           ms/op
Client.listUser:listUser·p0.99        sample         16.283           ms/op
Client.listUser:listUser·p0.999       sample         22.537           ms/op
Client.listUser:listUser·p0.9999      sample         22.938           ms/op
Client.listUser:listUser·p1.00        sample         22.938           ms/op
