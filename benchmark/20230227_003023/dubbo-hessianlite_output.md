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
# Warmup Iteration   1: 0.362 ops/ms
Iteration   1: 0.962 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  0.962 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:28
# Fork: 1 of 1
# Warmup Iteration   1: 1.527 ops/ms
Iteration   1: 3.307 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.307 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 0.999 ops/ms
Iteration   1: 2.073 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.073 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 0.519 ops/ms
Iteration   1: 0.610 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  0.610 ops/ms


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

# Run progress: 33.33% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 25.451 ±(99.9%) 0.523 ms/op
Iteration   1: 18.473 ±(99.9%) 0.158 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  18.473 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 19.263 ±(99.9%) 0.375 ms/op
Iteration   1: 9.439 ±(99.9%) 0.099 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  9.439 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:47
# Fork: 1 of 1
# Warmup Iteration   1: 32.684 ±(99.9%) 0.800 ms/op
Iteration   1: 12.266 ±(99.9%) 0.103 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  12.266 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:39
# Fork: 1 of 1
# Warmup Iteration   1: 43.004 ±(99.9%) 0.789 ms/op
Iteration   1: 31.551 ±(99.9%) 0.382 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  31.551 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:31
# Fork: 1 of 1
# Warmup Iteration   1: 27.704 ±(99.9%) 0.929 ms/op
Iteration   1: 14.824 ±(99.9%) 0.430 ms/op
                 createUser·p0.00:   4.899 ms/op
                 createUser·p0.50:   12.599 ms/op
                 createUser·p0.90:   23.527 ms/op
                 createUser·p0.95:   27.643 ms/op
                 createUser·p0.99:   33.882 ms/op
                 createUser·p0.999:  49.021 ms/op
                 createUser·p0.9999: 49.611 ms/op
                 createUser·p1.00:   49.611 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 2091
  mean =     14.824 ±(99.9%) 0.430 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 1 
    [ 5.000, 10.000) = 172 
    [10.000, 15.000) = 1272 
    [15.000, 20.000) = 352 
    [20.000, 25.000) = 137 
    [25.000, 30.000) = 62 
    [30.000, 35.000) = 85 
    [35.000, 40.000) = 3 
    [40.000, 45.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      4.899 ms/op
     p(50.0000) =     12.599 ms/op
     p(90.0000) =     23.527 ms/op
     p(95.0000) =     27.643 ms/op
     p(99.0000) =     33.882 ms/op
     p(99.9000) =     49.021 ms/op
     p(99.9900) =     49.611 ms/op
     p(99.9990) =     49.611 ms/op
     p(99.9999) =     49.611 ms/op
    p(100.0000) =     49.611 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:23
# Fork: 1 of 1
# Warmup Iteration   1: 18.531 ±(99.9%) 0.579 ms/op
Iteration   1: 9.936 ±(99.9%) 0.279 ms/op
                 existUser·p0.00:   2.245 ms/op
                 existUser·p0.50:   9.486 ms/op
                 existUser·p0.90:   11.944 ms/op
                 existUser·p0.95:   21.463 ms/op
                 existUser·p0.99:   32.401 ms/op
                 existUser·p0.999:  37.511 ms/op
                 existUser·p0.9999: 37.683 ms/op
                 existUser·p1.00:   37.683 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 3206
  mean =      9.936 ±(99.9%) 0.279 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 170 
    [ 5.000,  7.500) = 548 
    [ 7.500, 10.000) = 1429 
    [10.000, 12.500) = 784 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 49 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.245 ms/op
     p(50.0000) =      9.486 ms/op
     p(90.0000) =     11.944 ms/op
     p(95.0000) =     21.463 ms/op
     p(99.0000) =     32.401 ms/op
     p(99.9000) =     37.511 ms/op
     p(99.9900) =     37.683 ms/op
     p(99.9990) =     37.683 ms/op
     p(99.9999) =     37.683 ms/op
    p(100.0000) =     37.683 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:15
# Fork: 1 of 1
# Warmup Iteration   1: 23.331 ±(99.9%) 0.862 ms/op
Iteration   1: 13.676 ±(99.9%) 0.357 ms/op
                 getUser·p0.00:   4.235 ms/op
                 getUser·p0.50:   12.763 ms/op
                 getUser·p0.90:   18.727 ms/op
                 getUser·p0.95:   21.307 ms/op
                 getUser·p0.99:   36.825 ms/op
                 getUser·p0.999:  41.729 ms/op
                 getUser·p0.9999: 42.664 ms/op
                 getUser·p1.00:   42.664 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 2354
  mean =     13.676 ±(99.9%) 0.357 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 3 
    [ 5.000, 10.000) = 504 
    [10.000, 15.000) = 1080 
    [15.000, 20.000) = 639 
    [20.000, 25.000) = 63 
    [25.000, 30.000) = 4 
    [30.000, 35.000) = 25 
    [35.000, 40.000) = 25 
    [40.000, 45.000) = 11 

  Percentiles, ms/op:
      p(0.0000) =      4.235 ms/op
     p(50.0000) =     12.763 ms/op
     p(90.0000) =     18.727 ms/op
     p(95.0000) =     21.307 ms/op
     p(99.0000) =     36.825 ms/op
     p(99.9000) =     41.729 ms/op
     p(99.9900) =     42.664 ms/op
     p(99.9990) =     42.664 ms/op
     p(99.9999) =     42.664 ms/op
    p(100.0000) =     42.664 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:08
# Fork: 1 of 1
# Warmup Iteration   1: 40.910 ±(99.9%) 1.606 ms/op
Iteration   1: 26.644 ±(99.9%) 0.629 ms/op
                 listUser·p0.00:   3.265 ms/op
                 listUser·p0.50:   26.051 ms/op
                 listUser·p0.90:   31.621 ms/op
                 listUser·p0.95:   34.518 ms/op
                 listUser·p0.99:   60.893 ms/op
                 listUser·p0.999:  69.386 ms/op
                 listUser·p0.9999: 69.599 ms/op
                 listUser·p1.00:   69.599 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1202
  mean =     26.644 ±(99.9%) 0.629 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 5 
    [ 5.000, 10.000) = 5 
    [10.000, 15.000) = 18 
    [15.000, 20.000) = 41 
    [20.000, 25.000) = 378 
    [25.000, 30.000) = 526 
    [30.000, 35.000) = 172 
    [35.000, 40.000) = 22 
    [40.000, 45.000) = 10 
    [45.000, 50.000) = 9 
    [50.000, 55.000) = 2 
    [55.000, 60.000) = 2 
    [60.000, 65.000) = 6 

  Percentiles, ms/op:
      p(0.0000) =      3.265 ms/op
     p(50.0000) =     26.051 ms/op
     p(90.0000) =     31.621 ms/op
     p(95.0000) =     34.518 ms/op
     p(99.0000) =     60.893 ms/op
     p(99.9000) =     69.386 ms/op
     p(99.9900) =     69.599 ms/op
     p(99.9990) =     69.599 ms/op
     p(99.9999) =     69.599 ms/op
    p(100.0000) =     69.599 ms/op


# Run complete. Total time: 00:01:36

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         0.962          ops/ms
Client.existUser                       thrpt         3.307          ops/ms
Client.getUser                         thrpt         2.073          ops/ms
Client.listUser                        thrpt         0.610          ops/ms
Client.createUser                       avgt        18.473           ms/op
Client.existUser                        avgt         9.439           ms/op
Client.getUser                          avgt        12.266           ms/op
Client.listUser                         avgt        31.551           ms/op
Client.createUser                     sample  2091  14.824 ± 0.430   ms/op
Client.createUser:createUser·p0.00    sample         4.899           ms/op
Client.createUser:createUser·p0.50    sample        12.599           ms/op
Client.createUser:createUser·p0.90    sample        23.527           ms/op
Client.createUser:createUser·p0.95    sample        27.643           ms/op
Client.createUser:createUser·p0.99    sample        33.882           ms/op
Client.createUser:createUser·p0.999   sample        49.021           ms/op
Client.createUser:createUser·p0.9999  sample        49.611           ms/op
Client.createUser:createUser·p1.00    sample        49.611           ms/op
Client.existUser                      sample  3206   9.936 ± 0.279   ms/op
Client.existUser:existUser·p0.00      sample         2.245           ms/op
Client.existUser:existUser·p0.50      sample         9.486           ms/op
Client.existUser:existUser·p0.90      sample        11.944           ms/op
Client.existUser:existUser·p0.95      sample        21.463           ms/op
Client.existUser:existUser·p0.99      sample        32.401           ms/op
Client.existUser:existUser·p0.999     sample        37.511           ms/op
Client.existUser:existUser·p0.9999    sample        37.683           ms/op
Client.existUser:existUser·p1.00      sample        37.683           ms/op
Client.getUser                        sample  2354  13.676 ± 0.357   ms/op
Client.getUser:getUser·p0.00          sample         4.235           ms/op
Client.getUser:getUser·p0.50          sample        12.763           ms/op
Client.getUser:getUser·p0.90          sample        18.727           ms/op
Client.getUser:getUser·p0.95          sample        21.307           ms/op
Client.getUser:getUser·p0.99          sample        36.825           ms/op
Client.getUser:getUser·p0.999         sample        41.729           ms/op
Client.getUser:getUser·p0.9999        sample        42.664           ms/op
Client.getUser:getUser·p1.00          sample        42.664           ms/op
Client.listUser                       sample  1202  26.644 ± 0.629   ms/op
Client.listUser:listUser·p0.00        sample         3.265           ms/op
Client.listUser:listUser·p0.50        sample        26.051           ms/op
Client.listUser:listUser·p0.90        sample        31.621           ms/op
Client.listUser:listUser·p0.95        sample        34.518           ms/op
Client.listUser:listUser·p0.99        sample        60.893           ms/op
Client.listUser:listUser·p0.999       sample        69.386           ms/op
Client.listUser:listUser·p0.9999      sample        69.599           ms/op
Client.listUser:listUser·p1.00        sample        69.599           ms/op
