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
# Warmup Iteration   1: 1.029 ops/ms
Iteration   1: 1.759 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  1.759 ops/ms


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
# Warmup Iteration   1: 2.636 ops/ms
Iteration   1: 6.006 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.006 ops/ms


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
Iteration   1: 3.911 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.911 ops/ms


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
# Warmup Iteration   1: 0.815 ops/ms
Iteration   1: 1.112 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.112 ops/ms


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
# Warmup Iteration   1: 19.542 ±(99.9%) 0.271 ms/op
Iteration   1: 8.926 ±(99.9%) 0.043 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  8.926 ms/op


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
# Warmup Iteration   1: 8.070 ±(99.9%) 0.109 ms/op
Iteration   1: 5.037 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  5.037 ms/op


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
# Warmup Iteration   1: 13.488 ±(99.9%) 0.230 ms/op
Iteration   1: 5.376 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.376 ms/op


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
# Warmup Iteration   1: 33.790 ±(99.9%) 0.837 ms/op
Iteration   1: 19.016 ±(99.9%) 0.123 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  19.016 ms/op


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
# Warmup Iteration   1: 16.312 ±(99.9%) 0.759 ms/op
Iteration   1: 7.557 ±(99.9%) 0.154 ms/op
                 createUser·p0.00:   1.712 ms/op
                 createUser·p0.50:   6.889 ms/op
                 createUser·p0.90:   8.895 ms/op
                 createUser·p0.95:   12.323 ms/op
                 createUser·p0.99:   23.003 ms/op
                 createUser·p0.999:  26.338 ms/op
                 createUser·p0.9999: 37.421 ms/op
                 createUser·p1.00:   37.421 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4110
  mean =      7.557 ±(99.9%) 0.154 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 63 
    [ 2.500,  5.000) = 103 
    [ 5.000,  7.500) = 2570 
    [ 7.500, 10.000) = 1107 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 24 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.712 ms/op
     p(50.0000) =      6.889 ms/op
     p(90.0000) =      8.895 ms/op
     p(95.0000) =     12.323 ms/op
     p(99.0000) =     23.003 ms/op
     p(99.9000) =     26.338 ms/op
     p(99.9900) =     37.421 ms/op
     p(99.9990) =     37.421 ms/op
     p(99.9999) =     37.421 ms/op
    p(100.0000) =     37.421 ms/op


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
# Warmup Iteration   1: 8.040 ±(99.9%) 0.257 ms/op
Iteration   1: 4.404 ±(99.9%) 0.123 ms/op
                 existUser·p0.00:   1.178 ms/op
                 existUser·p0.50:   4.104 ms/op
                 existUser·p0.90:   4.547 ms/op
                 existUser·p0.95:   6.786 ms/op
                 existUser·p0.99:   11.977 ms/op
                 existUser·p0.999:  48.781 ms/op
                 existUser·p0.9999: 49.807 ms/op
                 existUser·p1.00:   49.807 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 7330
  mean =      4.404 ±(99.9%) 0.123 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 6876 
    [ 5.000, 10.000) = 320 
    [10.000, 15.000) = 102 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.178 ms/op
     p(50.0000) =      4.104 ms/op
     p(90.0000) =      4.547 ms/op
     p(95.0000) =      6.786 ms/op
     p(99.0000) =     11.977 ms/op
     p(99.9000) =     48.781 ms/op
     p(99.9900) =     49.807 ms/op
     p(99.9990) =     49.807 ms/op
     p(99.9999) =     49.807 ms/op
    p(100.0000) =     49.807 ms/op


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
# Warmup Iteration   1: 9.585 ±(99.9%) 0.377 ms/op
Iteration   1: 5.197 ±(99.9%) 0.170 ms/op
                 getUser·p0.00:   2.075 ms/op
                 getUser·p0.50:   4.424 ms/op
                 getUser·p0.90:   6.603 ms/op
                 getUser·p0.95:   9.994 ms/op
                 getUser·p0.99:   19.204 ms/op
                 getUser·p0.999:  55.640 ms/op
                 getUser·p0.9999: 60.490 ms/op
                 getUser·p1.00:   60.490 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6165
  mean =      5.197 ±(99.9%) 0.170 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 4285 
    [ 5.000, 10.000) = 1575 
    [10.000, 15.000) = 233 
    [15.000, 20.000) = 27 
    [20.000, 25.000) = 13 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 19 
    [50.000, 55.000) = 3 
    [55.000, 60.000) = 9 
    [60.000, 65.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.075 ms/op
     p(50.0000) =      4.424 ms/op
     p(90.0000) =      6.603 ms/op
     p(95.0000) =      9.994 ms/op
     p(99.0000) =     19.204 ms/op
     p(99.9000) =     55.640 ms/op
     p(99.9900) =     60.490 ms/op
     p(99.9990) =     60.490 ms/op
     p(99.9999) =     60.490 ms/op
    p(100.0000) =     60.490 ms/op


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
# Warmup Iteration   1: 29.014 ±(99.9%) 1.139 ms/op
Iteration   1: 18.763 ±(99.9%) 0.259 ms/op
                 listUser·p0.00:   7.004 ms/op
                 listUser·p0.50:   18.088 ms/op
                 listUser·p0.90:   22.282 ms/op
                 listUser·p0.95:   25.376 ms/op
                 listUser·p0.99:   32.564 ms/op
                 listUser·p0.999:  37.916 ms/op
                 listUser·p0.9999: 38.011 ms/op
                 listUser·p1.00:   38.011 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1722
  mean =     18.763 ±(99.9%) 0.259 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 3 
    [ 7.500, 10.000) = 7 
    [10.000, 12.500) = 6 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 522 
    [17.500, 20.000) = 874 
    [20.000, 22.500) = 146 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 35 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      7.004 ms/op
     p(50.0000) =     18.088 ms/op
     p(90.0000) =     22.282 ms/op
     p(95.0000) =     25.376 ms/op
     p(99.0000) =     32.564 ms/op
     p(99.9000) =     37.916 ms/op
     p(99.9900) =     38.011 ms/op
     p(99.9990) =     38.011 ms/op
     p(99.9999) =     38.011 ms/op
    p(100.0000) =     38.011 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         1.759          ops/ms
Client.existUser                       thrpt         6.006          ops/ms
Client.getUser                         thrpt         3.911          ops/ms
Client.listUser                        thrpt         1.112          ops/ms
Client.createUser                       avgt         8.926           ms/op
Client.existUser                        avgt         5.037           ms/op
Client.getUser                          avgt         5.376           ms/op
Client.listUser                         avgt        19.016           ms/op
Client.createUser                     sample  4110   7.557 ± 0.154   ms/op
Client.createUser:createUser·p0.00    sample         1.712           ms/op
Client.createUser:createUser·p0.50    sample         6.889           ms/op
Client.createUser:createUser·p0.90    sample         8.895           ms/op
Client.createUser:createUser·p0.95    sample        12.323           ms/op
Client.createUser:createUser·p0.99    sample        23.003           ms/op
Client.createUser:createUser·p0.999   sample        26.338           ms/op
Client.createUser:createUser·p0.9999  sample        37.421           ms/op
Client.createUser:createUser·p1.00    sample        37.421           ms/op
Client.existUser                      sample  7330   4.404 ± 0.123   ms/op
Client.existUser:existUser·p0.00      sample         1.178           ms/op
Client.existUser:existUser·p0.50      sample         4.104           ms/op
Client.existUser:existUser·p0.90      sample         4.547           ms/op
Client.existUser:existUser·p0.95      sample         6.786           ms/op
Client.existUser:existUser·p0.99      sample        11.977           ms/op
Client.existUser:existUser·p0.999     sample        48.781           ms/op
Client.existUser:existUser·p0.9999    sample        49.807           ms/op
Client.existUser:existUser·p1.00      sample        49.807           ms/op
Client.getUser                        sample  6165   5.197 ± 0.170   ms/op
Client.getUser:getUser·p0.00          sample         2.075           ms/op
Client.getUser:getUser·p0.50          sample         4.424           ms/op
Client.getUser:getUser·p0.90          sample         6.603           ms/op
Client.getUser:getUser·p0.95          sample         9.994           ms/op
Client.getUser:getUser·p0.99          sample        19.204           ms/op
Client.getUser:getUser·p0.999         sample        55.640           ms/op
Client.getUser:getUser·p0.9999        sample        60.490           ms/op
Client.getUser:getUser·p1.00          sample        60.490           ms/op
Client.listUser                       sample  1722  18.763 ± 0.259   ms/op
Client.listUser:listUser·p0.00        sample         7.004           ms/op
Client.listUser:listUser·p0.50        sample        18.088           ms/op
Client.listUser:listUser·p0.90        sample        22.282           ms/op
Client.listUser:listUser·p0.95        sample        25.376           ms/op
Client.listUser:listUser·p0.99        sample        32.564           ms/op
Client.listUser:listUser·p0.999       sample        37.916           ms/op
Client.listUser:listUser·p0.9999      sample        38.011           ms/op
Client.listUser:listUser·p1.00        sample        38.011           ms/op
