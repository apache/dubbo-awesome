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
# Warmup Iteration   1: 1.060 ops/ms
Iteration   1: 2.091 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.091 ops/ms


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
# Warmup Iteration   1: 2.271 ops/ms
Iteration   1: 6.014 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.014 ops/ms


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
# Warmup Iteration   1: 2.562 ops/ms
Iteration   1: 3.884 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.884 ops/ms


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
# Warmup Iteration   1: 0.865 ops/ms
Iteration   1: 1.258 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.258 ops/ms


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
# Warmup Iteration   1: 17.675 ±(99.9%) 0.238 ms/op
Iteration   1: 9.723 ±(99.9%) 0.049 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  9.723 ms/op


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
# Warmup Iteration   1: 7.760 ±(99.9%) 0.157 ms/op
Iteration   1: 4.665 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.665 ms/op


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
# Warmup Iteration   1: 11.788 ±(99.9%) 0.131 ms/op
Iteration   1: 5.082 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.082 ms/op


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
# Warmup Iteration   1: 32.781 ±(99.9%) 0.567 ms/op
Iteration   1: 19.652 ±(99.9%) 0.089 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  19.652 ms/op


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
# Warmup Iteration   1: 10.163 ±(99.9%) 0.359 ms/op
Iteration   1: 7.287 ±(99.9%) 0.166 ms/op
                 createUser·p0.00:   1.616 ms/op
                 createUser·p0.50:   7.021 ms/op
                 createUser·p0.90:   7.586 ms/op
                 createUser·p0.95:   8.061 ms/op
                 createUser·p0.99:   14.294 ms/op
                 createUser·p0.999:  48.401 ms/op
                 createUser·p0.9999: 48.693 ms/op
                 createUser·p1.00:   48.693 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4457
  mean =      7.287 ±(99.9%) 0.166 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 157 
    [ 5.000, 10.000) = 4168 
    [10.000, 15.000) = 100 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 14 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.616 ms/op
     p(50.0000) =      7.021 ms/op
     p(90.0000) =      7.586 ms/op
     p(95.0000) =      8.061 ms/op
     p(99.0000) =     14.294 ms/op
     p(99.9000) =     48.401 ms/op
     p(99.9900) =     48.693 ms/op
     p(99.9990) =     48.693 ms/op
     p(99.9999) =     48.693 ms/op
    p(100.0000) =     48.693 ms/op


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
# Warmup Iteration   1: 7.747 ±(99.9%) 0.213 ms/op
Iteration   1: 4.237 ±(99.9%) 0.066 ms/op
                 existUser·p0.00:   0.811 ms/op
                 existUser·p0.50:   3.990 ms/op
                 existUser·p0.90:   4.792 ms/op
                 existUser·p0.95:   5.864 ms/op
                 existUser·p0.99:   13.943 ms/op
                 existUser·p0.999:  19.923 ms/op
                 existUser·p0.9999: 19.956 ms/op
                 existUser·p1.00:   19.956 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 7542
  mean =      4.237 ±(99.9%) 0.066 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 16 
    [ 1.250,  2.500) = 305 
    [ 2.500,  3.750) = 2278 
    [ 3.750,  5.000) = 4381 
    [ 5.000,  6.250) = 253 
    [ 6.250,  7.500) = 79 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 64 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.811 ms/op
     p(50.0000) =      3.990 ms/op
     p(90.0000) =      4.792 ms/op
     p(95.0000) =      5.864 ms/op
     p(99.0000) =     13.943 ms/op
     p(99.9000) =     19.923 ms/op
     p(99.9900) =     19.956 ms/op
     p(99.9990) =     19.956 ms/op
     p(99.9999) =     19.956 ms/op
    p(100.0000) =     19.956 ms/op


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
# Warmup Iteration   1: 8.443 ±(99.9%) 0.329 ms/op
Iteration   1: 5.170 ±(99.9%) 0.079 ms/op
                 getUser·p0.00:   1.280 ms/op
                 getUser·p0.50:   5.104 ms/op
                 getUser·p0.90:   6.177 ms/op
                 getUser·p0.95:   7.004 ms/op
                 getUser·p0.99:   18.579 ms/op
                 getUser·p0.999:  20.218 ms/op
                 getUser·p0.9999: 20.972 ms/op
                 getUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6281
  mean =      5.170 ±(99.9%) 0.079 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 66 
    [ 2.500,  5.000) = 2703 
    [ 5.000,  7.500) = 3299 
    [ 7.500, 10.000) = 84 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.280 ms/op
     p(50.0000) =      5.104 ms/op
     p(90.0000) =      6.177 ms/op
     p(95.0000) =      7.004 ms/op
     p(99.0000) =     18.579 ms/op
     p(99.9000) =     20.218 ms/op
     p(99.9900) =     20.972 ms/op
     p(99.9990) =     20.972 ms/op
     p(99.9999) =     20.972 ms/op
    p(100.0000) =     20.972 ms/op


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
# Warmup Iteration   1: 30.999 ±(99.9%) 1.063 ms/op
Iteration   1: 20.051 ±(99.9%) 0.254 ms/op
                 listUser·p0.00:   8.815 ms/op
                 listUser·p0.50:   20.152 ms/op
                 listUser·p0.90:   22.839 ms/op
                 listUser·p0.95:   24.386 ms/op
                 listUser·p0.99:   30.877 ms/op
                 listUser·p0.999:  40.821 ms/op
                 listUser·p0.9999: 41.419 ms/op
                 listUser·p1.00:   41.419 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1607
  mean =     20.051 ±(99.9%) 0.254 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 0 
    [ 5.000, 10.000) = 5 
    [10.000, 15.000) = 75 
    [15.000, 20.000) = 691 
    [20.000, 25.000) = 770 
    [25.000, 30.000) = 47 
    [30.000, 35.000) = 13 
    [35.000, 40.000) = 4 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      8.815 ms/op
     p(50.0000) =     20.152 ms/op
     p(90.0000) =     22.839 ms/op
     p(95.0000) =     24.386 ms/op
     p(99.0000) =     30.877 ms/op
     p(99.9000) =     40.821 ms/op
     p(99.9900) =     41.419 ms/op
     p(99.9990) =     41.419 ms/op
     p(99.9999) =     41.419 ms/op
    p(100.0000) =     41.419 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.091          ops/ms
Client.existUser                       thrpt         6.014          ops/ms
Client.getUser                         thrpt         3.884          ops/ms
Client.listUser                        thrpt         1.258          ops/ms
Client.createUser                       avgt         9.723           ms/op
Client.existUser                        avgt         4.665           ms/op
Client.getUser                          avgt         5.082           ms/op
Client.listUser                         avgt        19.652           ms/op
Client.createUser                     sample  4457   7.287 ± 0.166   ms/op
Client.createUser:createUser·p0.00    sample         1.616           ms/op
Client.createUser:createUser·p0.50    sample         7.021           ms/op
Client.createUser:createUser·p0.90    sample         7.586           ms/op
Client.createUser:createUser·p0.95    sample         8.061           ms/op
Client.createUser:createUser·p0.99    sample        14.294           ms/op
Client.createUser:createUser·p0.999   sample        48.401           ms/op
Client.createUser:createUser·p0.9999  sample        48.693           ms/op
Client.createUser:createUser·p1.00    sample        48.693           ms/op
Client.existUser                      sample  7542   4.237 ± 0.066   ms/op
Client.existUser:existUser·p0.00      sample         0.811           ms/op
Client.existUser:existUser·p0.50      sample         3.990           ms/op
Client.existUser:existUser·p0.90      sample         4.792           ms/op
Client.existUser:existUser·p0.95      sample         5.864           ms/op
Client.existUser:existUser·p0.99      sample        13.943           ms/op
Client.existUser:existUser·p0.999     sample        19.923           ms/op
Client.existUser:existUser·p0.9999    sample        19.956           ms/op
Client.existUser:existUser·p1.00      sample        19.956           ms/op
Client.getUser                        sample  6281   5.170 ± 0.079   ms/op
Client.getUser:getUser·p0.00          sample         1.280           ms/op
Client.getUser:getUser·p0.50          sample         5.104           ms/op
Client.getUser:getUser·p0.90          sample         6.177           ms/op
Client.getUser:getUser·p0.95          sample         7.004           ms/op
Client.getUser:getUser·p0.99          sample        18.579           ms/op
Client.getUser:getUser·p0.999         sample        20.218           ms/op
Client.getUser:getUser·p0.9999        sample        20.972           ms/op
Client.getUser:getUser·p1.00          sample        20.972           ms/op
Client.listUser                       sample  1607  20.051 ± 0.254   ms/op
Client.listUser:listUser·p0.00        sample         8.815           ms/op
Client.listUser:listUser·p0.50        sample        20.152           ms/op
Client.listUser:listUser·p0.90        sample        22.839           ms/op
Client.listUser:listUser·p0.95        sample        24.386           ms/op
Client.listUser:listUser·p0.99        sample        30.877           ms/op
Client.listUser:listUser·p0.999       sample        40.821           ms/op
Client.listUser:listUser·p0.9999      sample        41.419           ms/op
Client.listUser:listUser·p1.00        sample        41.419           ms/op
