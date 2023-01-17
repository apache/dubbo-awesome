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
# Warmup Iteration   1: 1.080 ops/ms
Iteration   1: 3.174 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.174 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 3.889 ops/ms
Iteration   1: 9.460 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  9.460 ops/ms


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
# Warmup Iteration   1: 1.859 ops/ms
Iteration   1: 4.637 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.637 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 0.890 ops/ms
Iteration   1: 1.530 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.530 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 15.863 ±(99.9%) 0.181 ms/op
Iteration   1: 7.785 ±(99.9%) 0.070 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  7.785 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 7.751 ±(99.9%) 0.279 ms/op
Iteration   1: 4.253 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.253 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.686 ±(99.9%) 0.124 ms/op
Iteration   1: 5.056 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.056 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 27.887 ±(99.9%) 0.453 ms/op
Iteration   1: 17.420 ±(99.9%) 0.065 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  17.420 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 12.291 ±(99.9%) 0.391 ms/op
Iteration   1: 5.657 ±(99.9%) 0.075 ms/op
                 createUser·p0.00:   2.867 ms/op
                 createUser·p0.50:   5.218 ms/op
                 createUser·p0.90:   6.196 ms/op
                 createUser·p0.95:   10.109 ms/op
                 createUser·p0.99:   14.172 ms/op
                 createUser·p0.999:  15.073 ms/op
                 createUser·p0.9999: 15.090 ms/op
                 createUser·p1.00:   15.090 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5736
  mean =      5.657 ±(99.9%) 0.075 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 0 
    [ 2.500,  3.750) = 10 
    [ 3.750,  5.000) = 1487 
    [ 5.000,  6.250) = 3694 
    [ 6.250,  7.500) = 161 
    [ 7.500,  8.750) = 62 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 88 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 120 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.867 ms/op
     p(50.0000) =      5.218 ms/op
     p(90.0000) =      6.196 ms/op
     p(95.0000) =     10.109 ms/op
     p(99.0000) =     14.172 ms/op
     p(99.9000) =     15.073 ms/op
     p(99.9900) =     15.090 ms/op
     p(99.9990) =     15.090 ms/op
     p(99.9999) =     15.090 ms/op
    p(100.0000) =     15.090 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 5.552 ±(99.9%) 0.162 ms/op
Iteration   1: 3.933 ±(99.9%) 0.194 ms/op
                 existUser·p0.00:   0.388 ms/op
                 existUser·p0.50:   3.572 ms/op
                 existUser·p0.90:   4.162 ms/op
                 existUser·p0.95:   5.163 ms/op
                 existUser·p0.99:   12.394 ms/op
                 existUser·p0.999:  85.590 ms/op
                 existUser·p0.9999: 88.998 ms/op
                 existUser·p1.00:   88.998 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 8154
  mean =      3.933 ±(99.9%) 0.194 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 7711 
    [ 5.000, 10.000) = 279 
    [10.000, 15.000) = 132 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 0 
    [60.000, 65.000) = 0 
    [65.000, 70.000) = 0 
    [70.000, 75.000) = 0 
    [75.000, 80.000) = 0 
    [80.000, 85.000) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.388 ms/op
     p(50.0000) =      3.572 ms/op
     p(90.0000) =      4.162 ms/op
     p(95.0000) =      5.163 ms/op
     p(99.0000) =     12.394 ms/op
     p(99.9000) =     85.590 ms/op
     p(99.9900) =     88.998 ms/op
     p(99.9990) =     88.998 ms/op
     p(99.9999) =     88.998 ms/op
    p(100.0000) =     88.998 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 8.781 ±(99.9%) 0.358 ms/op
Iteration   1: 4.527 ±(99.9%) 0.043 ms/op
                 getUser·p0.00:   1.454 ms/op
                 getUser·p0.50:   4.399 ms/op
                 getUser·p0.90:   5.407 ms/op
                 getUser·p0.95:   5.775 ms/op
                 getUser·p0.99:   8.101 ms/op
                 getUser·p0.999:  16.775 ms/op
                 getUser·p0.9999: 20.087 ms/op
                 getUser·p1.00:   20.087 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7080
  mean =      4.527 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 86 
    [ 2.500,  5.000) = 5473 
    [ 5.000,  7.500) = 1446 
    [ 7.500, 10.000) = 43 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.454 ms/op
     p(50.0000) =      4.399 ms/op
     p(90.0000) =      5.407 ms/op
     p(95.0000) =      5.775 ms/op
     p(99.0000) =      8.101 ms/op
     p(99.9000) =     16.775 ms/op
     p(99.9900) =     20.087 ms/op
     p(99.9990) =     20.087 ms/op
     p(99.9999) =     20.087 ms/op
    p(100.0000) =     20.087 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 24.632 ±(99.9%) 0.813 ms/op
Iteration   1: 17.375 ±(99.9%) 0.252 ms/op
                 listUser·p0.00:   5.046 ms/op
                 listUser·p0.50:   17.138 ms/op
                 listUser·p0.90:   20.441 ms/op
                 listUser·p0.95:   24.756 ms/op
                 listUser·p0.99:   28.869 ms/op
                 listUser·p0.999:  30.249 ms/op
                 listUser·p0.9999: 32.539 ms/op
                 listUser·p1.00:   32.539 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1841
  mean =     17.375 ±(99.9%) 0.252 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 8 
    [ 7.500, 10.000) = 10 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 263 
    [15.000, 17.500) = 882 
    [17.500, 20.000) = 451 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 49 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      5.046 ms/op
     p(50.0000) =     17.138 ms/op
     p(90.0000) =     20.441 ms/op
     p(95.0000) =     24.756 ms/op
     p(99.0000) =     28.869 ms/op
     p(99.9000) =     30.249 ms/op
     p(99.9900) =     32.539 ms/op
     p(99.9990) =     32.539 ms/op
     p(99.9999) =     32.539 ms/op
    p(100.0000) =     32.539 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         3.174          ops/ms
Client.existUser                       thrpt         9.460          ops/ms
Client.getUser                         thrpt         4.637          ops/ms
Client.listUser                        thrpt         1.530          ops/ms
Client.createUser                       avgt         7.785           ms/op
Client.existUser                        avgt         4.253           ms/op
Client.getUser                          avgt         5.056           ms/op
Client.listUser                         avgt        17.420           ms/op
Client.createUser                     sample  5736   5.657 ± 0.075   ms/op
Client.createUser:createUser·p0.00    sample         2.867           ms/op
Client.createUser:createUser·p0.50    sample         5.218           ms/op
Client.createUser:createUser·p0.90    sample         6.196           ms/op
Client.createUser:createUser·p0.95    sample        10.109           ms/op
Client.createUser:createUser·p0.99    sample        14.172           ms/op
Client.createUser:createUser·p0.999   sample        15.073           ms/op
Client.createUser:createUser·p0.9999  sample        15.090           ms/op
Client.createUser:createUser·p1.00    sample        15.090           ms/op
Client.existUser                      sample  8154   3.933 ± 0.194   ms/op
Client.existUser:existUser·p0.00      sample         0.388           ms/op
Client.existUser:existUser·p0.50      sample         3.572           ms/op
Client.existUser:existUser·p0.90      sample         4.162           ms/op
Client.existUser:existUser·p0.95      sample         5.163           ms/op
Client.existUser:existUser·p0.99      sample        12.394           ms/op
Client.existUser:existUser·p0.999     sample        85.590           ms/op
Client.existUser:existUser·p0.9999    sample        88.998           ms/op
Client.existUser:existUser·p1.00      sample        88.998           ms/op
Client.getUser                        sample  7080   4.527 ± 0.043   ms/op
Client.getUser:getUser·p0.00          sample         1.454           ms/op
Client.getUser:getUser·p0.50          sample         4.399           ms/op
Client.getUser:getUser·p0.90          sample         5.407           ms/op
Client.getUser:getUser·p0.95          sample         5.775           ms/op
Client.getUser:getUser·p0.99          sample         8.101           ms/op
Client.getUser:getUser·p0.999         sample        16.775           ms/op
Client.getUser:getUser·p0.9999        sample        20.087           ms/op
Client.getUser:getUser·p1.00          sample        20.087           ms/op
Client.listUser                       sample  1841  17.375 ± 0.252   ms/op
Client.listUser:listUser·p0.00        sample         5.046           ms/op
Client.listUser:listUser·p0.50        sample        17.138           ms/op
Client.listUser:listUser·p0.90        sample        20.441           ms/op
Client.listUser:listUser·p0.95        sample        24.756           ms/op
Client.listUser:listUser·p0.99        sample        28.869           ms/op
Client.listUser:listUser·p0.999       sample        30.249           ms/op
Client.listUser:listUser·p0.9999      sample        32.539           ms/op
Client.listUser:listUser·p1.00        sample        32.539           ms/op
