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
# Warmup Iteration   1: 0.655 ops/ms
Iteration   1: 1.503 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  1.503 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:25
# Fork: 1 of 1
# Warmup Iteration   1: 1.333 ops/ms
Iteration   1: 3.306 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.306 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 1.153 ops/ms
Iteration   1: 2.331 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.331 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 0.586 ops/ms
Iteration   1: 0.866 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  0.866 ops/ms


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

# Run progress: 33.33% complete, ETA 00:01:01
# Fork: 1 of 1
# Warmup Iteration   1: 28.719 ±(99.9%) 0.526 ms/op
Iteration   1: 17.858 ±(99.9%) 0.094 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  17.858 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:53
# Fork: 1 of 1
# Warmup Iteration   1: 17.432 ±(99.9%) 0.333 ms/op
Iteration   1: 7.661 ±(99.9%) 0.084 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  7.661 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:46
# Fork: 1 of 1
# Warmup Iteration   1: 26.824 ±(99.9%) 0.673 ms/op
Iteration   1: 10.174 ±(99.9%) 0.094 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  10.174 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:38
# Fork: 1 of 1
# Warmup Iteration   1: 44.265 ±(99.9%) 0.562 ms/op
Iteration   1: 26.428 ±(99.9%) 0.268 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  26.428 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:30
# Fork: 1 of 1
# Warmup Iteration   1: 25.380 ±(99.9%) 1.308 ms/op
Iteration   1: 10.536 ±(99.9%) 0.278 ms/op
                 createUser·p0.00:   4.383 ms/op
                 createUser·p0.50:   10.158 ms/op
                 createUser·p0.90:   14.336 ms/op
                 createUser·p0.95:   20.188 ms/op
                 createUser·p0.99:   33.136 ms/op
                 createUser·p0.999:  35.011 ms/op
                 createUser·p0.9999: 43.975 ms/op
                 createUser·p1.00:   43.975 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 2977
  mean =     10.536 ±(99.9%) 0.278 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 10 
    [ 5.000, 10.000) = 1289 
    [10.000, 15.000) = 1424 
    [15.000, 20.000) = 99 
    [20.000, 25.000) = 83 
    [25.000, 30.000) = 37 
    [30.000, 35.000) = 33 
    [35.000, 40.000) = 1 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      4.383 ms/op
     p(50.0000) =     10.158 ms/op
     p(90.0000) =     14.336 ms/op
     p(95.0000) =     20.188 ms/op
     p(99.0000) =     33.136 ms/op
     p(99.9000) =     35.011 ms/op
     p(99.9900) =     43.975 ms/op
     p(99.9990) =     43.975 ms/op
     p(99.9999) =     43.975 ms/op
    p(100.0000) =     43.975 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:23
# Fork: 1 of 1
# Warmup Iteration   1: 13.805 ±(99.9%) 0.407 ms/op
Iteration   1: 9.029 ±(99.9%) 0.192 ms/op
                 existUser·p0.00:   1.466 ms/op
                 existUser·p0.50:   8.880 ms/op
                 existUser·p0.90:   11.354 ms/op
                 existUser·p0.95:   13.334 ms/op
                 existUser·p0.99:   24.941 ms/op
                 existUser·p0.999:  28.495 ms/op
                 existUser·p0.9999: 30.769 ms/op
                 existUser·p1.00:   30.769 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 3542
  mean =      9.029 ±(99.9%) 0.192 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 59 
    [ 2.500,  5.000) = 224 
    [ 5.000,  7.500) = 410 
    [ 7.500, 10.000) = 2174 
    [10.000, 12.500) = 455 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.466 ms/op
     p(50.0000) =      8.880 ms/op
     p(90.0000) =     11.354 ms/op
     p(95.0000) =     13.334 ms/op
     p(99.0000) =     24.941 ms/op
     p(99.9000) =     28.495 ms/op
     p(99.9900) =     30.769 ms/op
     p(99.9990) =     30.769 ms/op
     p(99.9999) =     30.769 ms/op
    p(100.0000) =     30.769 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:15
# Fork: 1 of 1
# Warmup Iteration   1: 21.453 ±(99.9%) 0.611 ms/op
Iteration   1: 8.973 ±(99.9%) 0.213 ms/op
                 getUser·p0.00:   1.090 ms/op
                 getUser·p0.50:   7.905 ms/op
                 getUser·p0.90:   13.373 ms/op
                 getUser·p0.95:   15.548 ms/op
                 getUser·p0.99:   28.520 ms/op
                 getUser·p0.999:  31.311 ms/op
                 getUser·p0.9999: 35.455 ms/op
                 getUser·p1.00:   35.455 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 3587
  mean =      8.973 ±(99.9%) 0.213 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 33 
    [ 5.000,  7.500) = 1519 
    [ 7.500, 10.000) = 1157 
    [10.000, 12.500) = 483 
    [12.500, 15.000) = 167 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.090 ms/op
     p(50.0000) =      7.905 ms/op
     p(90.0000) =     13.373 ms/op
     p(95.0000) =     15.548 ms/op
     p(99.0000) =     28.520 ms/op
     p(99.9000) =     31.311 ms/op
     p(99.9900) =     35.455 ms/op
     p(99.9990) =     35.455 ms/op
     p(99.9999) =     35.455 ms/op
    p(100.0000) =     35.455 ms/op


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
# Warmup Iteration   1: 40.262 ±(99.9%) 1.186 ms/op
Iteration   1: 26.719 ±(99.9%) 0.749 ms/op
                 listUser·p0.00:   16.646 ms/op
                 listUser·p0.50:   22.741 ms/op
                 listUser·p0.90:   37.028 ms/op
                 listUser·p0.95:   40.993 ms/op
                 listUser·p0.99:   54.768 ms/op
                 listUser·p0.999:  62.409 ms/op
                 listUser·p0.9999: 62.521 ms/op
                 listUser·p1.00:   62.521 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1189
  mean =     26.719 ±(99.9%) 0.749 ms/op

  Histogram, ms/op:
    [10.000, 15.000) = 0 
    [15.000, 20.000) = 71 
    [20.000, 25.000) = 634 
    [25.000, 30.000) = 86 
    [30.000, 35.000) = 217 
    [35.000, 40.000) = 110 
    [40.000, 45.000) = 38 
    [45.000, 50.000) = 12 
    [50.000, 55.000) = 10 
    [55.000, 60.000) = 8 
    [60.000, 65.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =     16.646 ms/op
     p(50.0000) =     22.741 ms/op
     p(90.0000) =     37.028 ms/op
     p(95.0000) =     40.993 ms/op
     p(99.0000) =     54.768 ms/op
     p(99.9000) =     62.409 ms/op
     p(99.9900) =     62.521 ms/op
     p(99.9990) =     62.521 ms/op
     p(99.9999) =     62.521 ms/op
    p(100.0000) =     62.521 ms/op


# Run complete. Total time: 00:01:33

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         1.503          ops/ms
Client.existUser                       thrpt         3.306          ops/ms
Client.getUser                         thrpt         2.331          ops/ms
Client.listUser                        thrpt         0.866          ops/ms
Client.createUser                       avgt        17.858           ms/op
Client.existUser                        avgt         7.661           ms/op
Client.getUser                          avgt        10.174           ms/op
Client.listUser                         avgt        26.428           ms/op
Client.createUser                     sample  2977  10.536 ± 0.278   ms/op
Client.createUser:createUser·p0.00    sample         4.383           ms/op
Client.createUser:createUser·p0.50    sample        10.158           ms/op
Client.createUser:createUser·p0.90    sample        14.336           ms/op
Client.createUser:createUser·p0.95    sample        20.188           ms/op
Client.createUser:createUser·p0.99    sample        33.136           ms/op
Client.createUser:createUser·p0.999   sample        35.011           ms/op
Client.createUser:createUser·p0.9999  sample        43.975           ms/op
Client.createUser:createUser·p1.00    sample        43.975           ms/op
Client.existUser                      sample  3542   9.029 ± 0.192   ms/op
Client.existUser:existUser·p0.00      sample         1.466           ms/op
Client.existUser:existUser·p0.50      sample         8.880           ms/op
Client.existUser:existUser·p0.90      sample        11.354           ms/op
Client.existUser:existUser·p0.95      sample        13.334           ms/op
Client.existUser:existUser·p0.99      sample        24.941           ms/op
Client.existUser:existUser·p0.999     sample        28.495           ms/op
Client.existUser:existUser·p0.9999    sample        30.769           ms/op
Client.existUser:existUser·p1.00      sample        30.769           ms/op
Client.getUser                        sample  3587   8.973 ± 0.213   ms/op
Client.getUser:getUser·p0.00          sample         1.090           ms/op
Client.getUser:getUser·p0.50          sample         7.905           ms/op
Client.getUser:getUser·p0.90          sample        13.373           ms/op
Client.getUser:getUser·p0.95          sample        15.548           ms/op
Client.getUser:getUser·p0.99          sample        28.520           ms/op
Client.getUser:getUser·p0.999         sample        31.311           ms/op
Client.getUser:getUser·p0.9999        sample        35.455           ms/op
Client.getUser:getUser·p1.00          sample        35.455           ms/op
Client.listUser                       sample  1189  26.719 ± 0.749   ms/op
Client.listUser:listUser·p0.00        sample        16.646           ms/op
Client.listUser:listUser·p0.50        sample        22.741           ms/op
Client.listUser:listUser·p0.90        sample        37.028           ms/op
Client.listUser:listUser·p0.95        sample        40.993           ms/op
Client.listUser:listUser·p0.99        sample        54.768           ms/op
Client.listUser:listUser·p0.999       sample        62.409           ms/op
Client.listUser:listUser·p0.9999      sample        62.521           ms/op
Client.listUser:listUser·p1.00        sample        62.521           ms/op
