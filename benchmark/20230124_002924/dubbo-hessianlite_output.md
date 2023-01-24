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
# Warmup Iteration   1: 0.996 ops/ms
Iteration   1: 2.608 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.608 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 3.559 ops/ms
Iteration   1: 7.508 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  7.508 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.388 ops/ms
Iteration   1: 4.911 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.911 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 0.876 ops/ms
Iteration   1: 1.318 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.318 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 18.592 ±(99.9%) 0.302 ms/op
Iteration   1: 7.291 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  7.291 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 6.208 ±(99.9%) 0.072 ms/op
Iteration   1: 3.101 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.101 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.210 ±(99.9%) 0.103 ms/op
Iteration   1: 4.892 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.892 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 27.137 ±(99.9%) 0.741 ms/op
Iteration   1: 15.268 ±(99.9%) 0.044 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  15.268 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.142 ±(99.9%) 0.333 ms/op
Iteration   1: 6.181 ±(99.9%) 0.083 ms/op
                 createUser·p0.00:   3.777 ms/op
                 createUser·p0.50:   5.784 ms/op
                 createUser·p0.90:   6.480 ms/op
                 createUser·p0.95:   9.675 ms/op
                 createUser·p0.99:   15.237 ms/op
                 createUser·p0.999:  20.545 ms/op
                 createUser·p0.9999: 21.070 ms/op
                 createUser·p1.00:   21.070 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5169
  mean =      6.181 ±(99.9%) 0.083 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 147 
    [ 5.000,  7.500) = 4688 
    [ 7.500, 10.000) = 85 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.777 ms/op
     p(50.0000) =      5.784 ms/op
     p(90.0000) =      6.480 ms/op
     p(95.0000) =      9.675 ms/op
     p(99.0000) =     15.237 ms/op
     p(99.9000) =     20.545 ms/op
     p(99.9900) =     21.070 ms/op
     p(99.9990) =     21.070 ms/op
     p(99.9999) =     21.070 ms/op
    p(100.0000) =     21.070 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 6.625 ±(99.9%) 0.180 ms/op
Iteration   1: 3.949 ±(99.9%) 0.058 ms/op
                 existUser·p0.00:   0.934 ms/op
                 existUser·p0.50:   3.772 ms/op
                 existUser·p0.90:   4.186 ms/op
                 existUser·p0.95:   4.383 ms/op
                 existUser·p0.99:   11.676 ms/op
                 existUser·p0.999:  25.616 ms/op
                 existUser·p0.9999: 25.985 ms/op
                 existUser·p1.00:   25.985 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 8133
  mean =      3.949 ±(99.9%) 0.058 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 191 
    [ 2.500,  5.000) = 7738 
    [ 5.000,  7.500) = 108 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.934 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.186 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =     11.676 ms/op
     p(99.9000) =     25.616 ms/op
     p(99.9900) =     25.985 ms/op
     p(99.9990) =     25.985 ms/op
     p(99.9999) =     25.985 ms/op
    p(100.0000) =     25.985 ms/op


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
# Warmup Iteration   1: 8.646 ±(99.9%) 0.245 ms/op
Iteration   1: 4.017 ±(99.9%) 0.051 ms/op
                 getUser·p0.00:   1.311 ms/op
                 getUser·p0.50:   3.834 ms/op
                 getUser·p0.90:   5.177 ms/op
                 getUser·p0.95:   5.661 ms/op
                 getUser·p0.99:   7.537 ms/op
                 getUser·p0.999:  18.088 ms/op
                 getUser·p0.9999: 18.612 ms/op
                 getUser·p1.00:   18.612 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7967
  mean =      4.017 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 365 
    [ 2.500,  3.750) = 3284 
    [ 3.750,  5.000) = 3328 
    [ 5.000,  6.250) = 739 
    [ 6.250,  7.500) = 160 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.311 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      5.177 ms/op
     p(95.0000) =      5.661 ms/op
     p(99.0000) =      7.537 ms/op
     p(99.9000) =     18.088 ms/op
     p(99.9900) =     18.612 ms/op
     p(99.9990) =     18.612 ms/op
     p(99.9999) =     18.612 ms/op
    p(100.0000) =     18.612 ms/op


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
# Warmup Iteration   1: 28.207 ±(99.9%) 0.956 ms/op
Iteration   1: 15.268 ±(99.9%) 0.263 ms/op
                 listUser·p0.00:   7.250 ms/op
                 listUser·p0.50:   14.049 ms/op
                 listUser·p0.90:   19.831 ms/op
                 listUser·p0.95:   24.055 ms/op
                 listUser·p0.99:   28.574 ms/op
                 listUser·p0.999:  34.459 ms/op
                 listUser·p0.9999: 35.127 ms/op
                 listUser·p1.00:   35.127 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2098
  mean =     15.268 ±(99.9%) 0.263 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 2 
    [ 7.500, 10.000) = 12 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 1360 
    [15.000, 17.500) = 361 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 35 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      7.250 ms/op
     p(50.0000) =     14.049 ms/op
     p(90.0000) =     19.831 ms/op
     p(95.0000) =     24.055 ms/op
     p(99.0000) =     28.574 ms/op
     p(99.9000) =     34.459 ms/op
     p(99.9900) =     35.127 ms/op
     p(99.9990) =     35.127 ms/op
     p(99.9999) =     35.127 ms/op
    p(100.0000) =     35.127 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.608          ops/ms
Client.existUser                       thrpt         7.508          ops/ms
Client.getUser                         thrpt         4.911          ops/ms
Client.listUser                        thrpt         1.318          ops/ms
Client.createUser                       avgt         7.291           ms/op
Client.existUser                        avgt         3.101           ms/op
Client.getUser                          avgt         4.892           ms/op
Client.listUser                         avgt        15.268           ms/op
Client.createUser                     sample  5169   6.181 ± 0.083   ms/op
Client.createUser:createUser·p0.00    sample         3.777           ms/op
Client.createUser:createUser·p0.50    sample         5.784           ms/op
Client.createUser:createUser·p0.90    sample         6.480           ms/op
Client.createUser:createUser·p0.95    sample         9.675           ms/op
Client.createUser:createUser·p0.99    sample        15.237           ms/op
Client.createUser:createUser·p0.999   sample        20.545           ms/op
Client.createUser:createUser·p0.9999  sample        21.070           ms/op
Client.createUser:createUser·p1.00    sample        21.070           ms/op
Client.existUser                      sample  8133   3.949 ± 0.058   ms/op
Client.existUser:existUser·p0.00      sample         0.934           ms/op
Client.existUser:existUser·p0.50      sample         3.772           ms/op
Client.existUser:existUser·p0.90      sample         4.186           ms/op
Client.existUser:existUser·p0.95      sample         4.383           ms/op
Client.existUser:existUser·p0.99      sample        11.676           ms/op
Client.existUser:existUser·p0.999     sample        25.616           ms/op
Client.existUser:existUser·p0.9999    sample        25.985           ms/op
Client.existUser:existUser·p1.00      sample        25.985           ms/op
Client.getUser                        sample  7967   4.017 ± 0.051   ms/op
Client.getUser:getUser·p0.00          sample         1.311           ms/op
Client.getUser:getUser·p0.50          sample         3.834           ms/op
Client.getUser:getUser·p0.90          sample         5.177           ms/op
Client.getUser:getUser·p0.95          sample         5.661           ms/op
Client.getUser:getUser·p0.99          sample         7.537           ms/op
Client.getUser:getUser·p0.999         sample        18.088           ms/op
Client.getUser:getUser·p0.9999        sample        18.612           ms/op
Client.getUser:getUser·p1.00          sample        18.612           ms/op
Client.listUser                       sample  2098  15.268 ± 0.263   ms/op
Client.listUser:listUser·p0.00        sample         7.250           ms/op
Client.listUser:listUser·p0.50        sample        14.049           ms/op
Client.listUser:listUser·p0.90        sample        19.831           ms/op
Client.listUser:listUser·p0.95        sample        24.055           ms/op
Client.listUser:listUser·p0.99        sample        28.574           ms/op
Client.listUser:listUser·p0.999       sample        34.459           ms/op
Client.listUser:listUser·p0.9999      sample        35.127           ms/op
Client.listUser:listUser·p1.00        sample        35.127           ms/op
