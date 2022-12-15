# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.075 ops/ms
Iteration   1: 2.143 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.143 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 3.195 ops/ms
Iteration   1: 7.019 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  7.019 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 1.896 ops/ms
Iteration   1: 5.093 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.093 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.049 ops/ms
Iteration   1: 1.442 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.442 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 15.670 ±(99.9%) 0.284 ms/op
Iteration   1: 7.598 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  7.598 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.478 ±(99.9%) 0.077 ms/op
Iteration   1: 3.590 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.590 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 12.004 ±(99.9%) 0.131 ms/op
Iteration   1: 4.609 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.609 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 29.255 ±(99.9%) 0.463 ms/op
Iteration   1: 15.334 ±(99.9%) 0.060 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  15.334 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.727 ±(99.9%) 0.322 ms/op
Iteration   1: 6.257 ±(99.9%) 0.143 ms/op
                 createUser·p0.00:   1.622 ms/op
                 createUser·p0.50:   5.898 ms/op
                 createUser·p0.90:   6.668 ms/op
                 createUser·p0.95:   7.266 ms/op
                 createUser·p0.99:   14.991 ms/op
                 createUser·p0.999:  43.647 ms/op
                 createUser·p0.9999: 45.089 ms/op
                 createUser·p1.00:   45.089 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5118
  mean =      6.257 ±(99.9%) 0.143 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 240 
    [ 5.000, 10.000) = 4755 
    [10.000, 15.000) = 77 
    [15.000, 20.000) = 11 
    [20.000, 25.000) = 3 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 15 
    [40.000, 45.000) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.622 ms/op
     p(50.0000) =      5.898 ms/op
     p(90.0000) =      6.668 ms/op
     p(95.0000) =      7.266 ms/op
     p(99.0000) =     14.991 ms/op
     p(99.9000) =     43.647 ms/op
     p(99.9900) =     45.089 ms/op
     p(99.9990) =     45.089 ms/op
     p(99.9999) =     45.089 ms/op
    p(100.0000) =     45.089 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 8.108 ±(99.9%) 0.288 ms/op
Iteration   1: 3.897 ±(99.9%) 0.051 ms/op
                 existUser·p0.00:   1.231 ms/op
                 existUser·p0.50:   3.690 ms/op
                 existUser·p0.90:   4.137 ms/op
                 existUser·p0.95:   4.489 ms/op
                 existUser·p0.99:   12.435 ms/op
                 existUser·p0.999:  15.528 ms/op
                 existUser·p0.9999: 19.399 ms/op
                 existUser·p1.00:   19.399 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 8217
  mean =      3.897 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 80 
    [ 2.500,  3.750) = 4889 
    [ 3.750,  5.000) = 2921 
    [ 5.000,  6.250) = 64 
    [ 6.250,  7.500) = 99 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.231 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.137 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =     12.435 ms/op
     p(99.9000) =     15.528 ms/op
     p(99.9900) =     19.399 ms/op
     p(99.9990) =     19.399 ms/op
     p(99.9999) =     19.399 ms/op
    p(100.0000) =     19.399 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 9.338 ±(99.9%) 0.314 ms/op
Iteration   1: 4.396 ±(99.9%) 0.077 ms/op
                 getUser·p0.00:   1.380 ms/op
                 getUser·p0.50:   4.002 ms/op
                 getUser·p0.90:   5.358 ms/op
                 getUser·p0.95:   6.554 ms/op
                 getUser·p0.99:   10.141 ms/op
                 getUser·p0.999:  27.656 ms/op
                 getUser·p0.9999: 30.409 ms/op
                 getUser·p1.00:   30.409 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7400
  mean =      4.396 ±(99.9%) 0.077 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26 
    [ 2.500,  5.000) = 6534 
    [ 5.000,  7.500) = 651 
    [ 7.500, 10.000) = 110 
    [10.000, 12.500) = 15 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.380 ms/op
     p(50.0000) =      4.002 ms/op
     p(90.0000) =      5.358 ms/op
     p(95.0000) =      6.554 ms/op
     p(99.0000) =     10.141 ms/op
     p(99.9000) =     27.656 ms/op
     p(99.9900) =     30.409 ms/op
     p(99.9990) =     30.409 ms/op
     p(99.9999) =     30.409 ms/op
    p(100.0000) =     30.409 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 26.926 ±(99.9%) 0.817 ms/op
Iteration   1: 17.431 ±(99.9%) 0.249 ms/op
                 listUser·p0.00:   4.768 ms/op
                 listUser·p0.50:   17.596 ms/op
                 listUser·p0.90:   20.578 ms/op
                 listUser·p0.95:   20.972 ms/op
                 listUser·p0.99:   27.578 ms/op
                 listUser·p0.999:  37.704 ms/op
                 listUser·p0.9999: 37.814 ms/op
                 listUser·p1.00:   37.814 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1841
  mean =     17.431 ±(99.9%) 0.249 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 1 
    [ 5.000,  7.500) = 10 
    [ 7.500, 10.000) = 23 
    [10.000, 12.500) = 25 
    [12.500, 15.000) = 322 
    [15.000, 17.500) = 477 
    [17.500, 20.000) = 705 
    [20.000, 22.500) = 224 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      4.768 ms/op
     p(50.0000) =     17.596 ms/op
     p(90.0000) =     20.578 ms/op
     p(95.0000) =     20.972 ms/op
     p(99.0000) =     27.578 ms/op
     p(99.9000) =     37.704 ms/op
     p(99.9900) =     37.814 ms/op
     p(99.9990) =     37.814 ms/op
     p(99.9999) =     37.814 ms/op
    p(100.0000) =     37.814 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.143          ops/ms
Client.existUser                       thrpt         7.019          ops/ms
Client.getUser                         thrpt         5.093          ops/ms
Client.listUser                        thrpt         1.442          ops/ms
Client.createUser                       avgt         7.598           ms/op
Client.existUser                        avgt         3.590           ms/op
Client.getUser                          avgt         4.609           ms/op
Client.listUser                         avgt        15.334           ms/op
Client.createUser                     sample  5118   6.257 ± 0.143   ms/op
Client.createUser:createUser·p0.00    sample         1.622           ms/op
Client.createUser:createUser·p0.50    sample         5.898           ms/op
Client.createUser:createUser·p0.90    sample         6.668           ms/op
Client.createUser:createUser·p0.95    sample         7.266           ms/op
Client.createUser:createUser·p0.99    sample        14.991           ms/op
Client.createUser:createUser·p0.999   sample        43.647           ms/op
Client.createUser:createUser·p0.9999  sample        45.089           ms/op
Client.createUser:createUser·p1.00    sample        45.089           ms/op
Client.existUser                      sample  8217   3.897 ± 0.051   ms/op
Client.existUser:existUser·p0.00      sample         1.231           ms/op
Client.existUser:existUser·p0.50      sample         3.690           ms/op
Client.existUser:existUser·p0.90      sample         4.137           ms/op
Client.existUser:existUser·p0.95      sample         4.489           ms/op
Client.existUser:existUser·p0.99      sample        12.435           ms/op
Client.existUser:existUser·p0.999     sample        15.528           ms/op
Client.existUser:existUser·p0.9999    sample        19.399           ms/op
Client.existUser:existUser·p1.00      sample        19.399           ms/op
Client.getUser                        sample  7400   4.396 ± 0.077   ms/op
Client.getUser:getUser·p0.00          sample         1.380           ms/op
Client.getUser:getUser·p0.50          sample         4.002           ms/op
Client.getUser:getUser·p0.90          sample         5.358           ms/op
Client.getUser:getUser·p0.95          sample         6.554           ms/op
Client.getUser:getUser·p0.99          sample        10.141           ms/op
Client.getUser:getUser·p0.999         sample        27.656           ms/op
Client.getUser:getUser·p0.9999        sample        30.409           ms/op
Client.getUser:getUser·p1.00          sample        30.409           ms/op
Client.listUser                       sample  1841  17.431 ± 0.249   ms/op
Client.listUser:listUser·p0.00        sample         4.768           ms/op
Client.listUser:listUser·p0.50        sample        17.596           ms/op
Client.listUser:listUser·p0.90        sample        20.578           ms/op
Client.listUser:listUser·p0.95        sample        20.972           ms/op
Client.listUser:listUser·p0.99        sample        27.578           ms/op
Client.listUser:listUser·p0.999       sample        37.704           ms/op
Client.listUser:listUser·p0.9999      sample        37.814           ms/op
Client.listUser:listUser·p1.00        sample        37.814           ms/op
