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
# Warmup Iteration   1: 0.630 ops/ms
Iteration   1: 1.131 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  1.131 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:26
# Fork: 1 of 1
# Warmup Iteration   1: 1.243 ops/ms
Iteration   1: 3.252 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.252 ops/ms


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
# Warmup Iteration   1: 1.096 ops/ms
Iteration   1: 2.527 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.527 ops/ms


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
# Warmup Iteration   1: 0.593 ops/ms
Iteration   1: 0.805 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  0.805 ops/ms


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

# Run progress: 33.33% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 28.349 ±(99.9%) 0.824 ms/op
Iteration   1: 16.712 ±(99.9%) 0.094 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  16.712 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:54
# Fork: 1 of 1
# Warmup Iteration   1: 25.106 ±(99.9%) 0.360 ms/op
Iteration   1: 9.842 ±(99.9%) 0.094 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  9.842 ms/op


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
# Warmup Iteration   1: 24.846 ±(99.9%) 0.586 ms/op
Iteration   1: 8.472 ±(99.9%) 0.059 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.472 ms/op


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
# Warmup Iteration   1: 40.552 ±(99.9%) 0.963 ms/op
Iteration   1: 25.094 ±(99.9%) 0.219 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  25.094 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:31
# Fork: 1 of 1
# Warmup Iteration   1: 23.161 ±(99.9%) 0.837 ms/op
Iteration   1: 13.387 ±(99.9%) 0.413 ms/op
                 createUser·p0.00:   2.056 ms/op
                 createUser·p0.50:   11.370 ms/op
                 createUser·p0.90:   22.020 ms/op
                 createUser·p0.95:   27.034 ms/op
                 createUser·p0.99:   36.635 ms/op
                 createUser·p0.999:  38.326 ms/op
                 createUser·p0.9999: 38.470 ms/op
                 createUser·p1.00:   38.470 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 2395
  mean =     13.387 ±(99.9%) 0.413 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 2 
    [ 5.000,  7.500) = 146 
    [ 7.500, 10.000) = 320 
    [10.000, 12.500) = 1080 
    [12.500, 15.000) = 352 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 62 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 33 
    [35.000, 37.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      2.056 ms/op
     p(50.0000) =     11.370 ms/op
     p(90.0000) =     22.020 ms/op
     p(95.0000) =     27.034 ms/op
     p(99.0000) =     36.635 ms/op
     p(99.9000) =     38.326 ms/op
     p(99.9900) =     38.470 ms/op
     p(99.9990) =     38.470 ms/op
     p(99.9999) =     38.470 ms/op
    p(100.0000) =     38.470 ms/op


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
# Warmup Iteration   1: 16.377 ±(99.9%) 0.521 ms/op
Iteration   1: 6.313 ±(99.9%) 0.128 ms/op
                 existUser·p0.00:   1.094 ms/op
                 existUser·p0.50:   5.661 ms/op
                 existUser·p0.90:   9.175 ms/op
                 existUser·p0.95:   11.561 ms/op
                 existUser·p0.99:   16.366 ms/op
                 existUser·p0.999:  24.794 ms/op
                 existUser·p0.9999: 26.051 ms/op
                 existUser·p1.00:   26.051 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 5103
  mean =      6.313 ±(99.9%) 0.128 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42 
    [ 2.500,  5.000) = 1748 
    [ 5.000,  7.500) = 2085 
    [ 7.500, 10.000) = 873 
    [10.000, 12.500) = 168 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.094 ms/op
     p(50.0000) =      5.661 ms/op
     p(90.0000) =      9.175 ms/op
     p(95.0000) =     11.561 ms/op
     p(99.0000) =     16.366 ms/op
     p(99.9000) =     24.794 ms/op
     p(99.9900) =     26.051 ms/op
     p(99.9990) =     26.051 ms/op
     p(99.9999) =     26.051 ms/op
    p(100.0000) =     26.051 ms/op


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
# Warmup Iteration   1: 15.962 ±(99.9%) 0.564 ms/op
Iteration   1: 8.631 ±(99.9%) 0.292 ms/op
                 getUser·p0.00:   2.953 ms/op
                 getUser·p0.50:   7.471 ms/op
                 getUser·p0.90:   12.730 ms/op
                 getUser·p0.95:   15.662 ms/op
                 getUser·p0.99:   22.938 ms/op
                 getUser·p0.999:  59.178 ms/op
                 getUser·p0.9999: 66.519 ms/op
                 getUser·p1.00:   66.519 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 3666
  mean =      8.631 ±(99.9%) 0.292 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 175 
    [ 5.000, 10.000) = 2739 
    [10.000, 15.000) = 528 
    [15.000, 20.000) = 174 
    [20.000, 25.000) = 18 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 19 
    [55.000, 60.000) = 10 
    [60.000, 65.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.953 ms/op
     p(50.0000) =      7.471 ms/op
     p(90.0000) =     12.730 ms/op
     p(95.0000) =     15.662 ms/op
     p(99.0000) =     22.938 ms/op
     p(99.9000) =     59.178 ms/op
     p(99.9900) =     66.519 ms/op
     p(99.9990) =     66.519 ms/op
     p(99.9999) =     66.519 ms/op
    p(100.0000) =     66.519 ms/op


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
# Warmup Iteration   1: 45.452 ±(99.9%) 2.146 ms/op
Iteration   1: 26.454 ±(99.9%) 0.615 ms/op
                 listUser·p0.00:   8.421 ms/op
                 listUser·p0.50:   26.837 ms/op
                 listUser·p0.90:   32.860 ms/op
                 listUser·p0.95:   37.972 ms/op
                 listUser·p0.99:   47.275 ms/op
                 listUser·p0.999:  54.420 ms/op
                 listUser·p0.9999: 54.526 ms/op
                 listUser·p1.00:   54.526 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1231
  mean =     26.454 ±(99.9%) 0.615 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 0 
    [ 5.000, 10.000) = 5 
    [10.000, 15.000) = 30 
    [15.000, 20.000) = 131 
    [20.000, 25.000) = 376 
    [25.000, 30.000) = 415 
    [30.000, 35.000) = 176 
    [35.000, 40.000) = 57 
    [40.000, 45.000) = 15 
    [45.000, 50.000) = 17 
    [50.000, 55.000) = 9 

  Percentiles, ms/op:
      p(0.0000) =      8.421 ms/op
     p(50.0000) =     26.837 ms/op
     p(90.0000) =     32.860 ms/op
     p(95.0000) =     37.972 ms/op
     p(99.0000) =     47.275 ms/op
     p(99.9000) =     54.420 ms/op
     p(99.9900) =     54.526 ms/op
     p(99.9990) =     54.526 ms/op
     p(99.9999) =     54.526 ms/op
    p(100.0000) =     54.526 ms/op


# Run complete. Total time: 00:01:34

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         1.131          ops/ms
Client.existUser                       thrpt         3.252          ops/ms
Client.getUser                         thrpt         2.527          ops/ms
Client.listUser                        thrpt         0.805          ops/ms
Client.createUser                       avgt        16.712           ms/op
Client.existUser                        avgt         9.842           ms/op
Client.getUser                          avgt         8.472           ms/op
Client.listUser                         avgt        25.094           ms/op
Client.createUser                     sample  2395  13.387 ± 0.413   ms/op
Client.createUser:createUser·p0.00    sample         2.056           ms/op
Client.createUser:createUser·p0.50    sample        11.370           ms/op
Client.createUser:createUser·p0.90    sample        22.020           ms/op
Client.createUser:createUser·p0.95    sample        27.034           ms/op
Client.createUser:createUser·p0.99    sample        36.635           ms/op
Client.createUser:createUser·p0.999   sample        38.326           ms/op
Client.createUser:createUser·p0.9999  sample        38.470           ms/op
Client.createUser:createUser·p1.00    sample        38.470           ms/op
Client.existUser                      sample  5103   6.313 ± 0.128   ms/op
Client.existUser:existUser·p0.00      sample         1.094           ms/op
Client.existUser:existUser·p0.50      sample         5.661           ms/op
Client.existUser:existUser·p0.90      sample         9.175           ms/op
Client.existUser:existUser·p0.95      sample        11.561           ms/op
Client.existUser:existUser·p0.99      sample        16.366           ms/op
Client.existUser:existUser·p0.999     sample        24.794           ms/op
Client.existUser:existUser·p0.9999    sample        26.051           ms/op
Client.existUser:existUser·p1.00      sample        26.051           ms/op
Client.getUser                        sample  3666   8.631 ± 0.292   ms/op
Client.getUser:getUser·p0.00          sample         2.953           ms/op
Client.getUser:getUser·p0.50          sample         7.471           ms/op
Client.getUser:getUser·p0.90          sample        12.730           ms/op
Client.getUser:getUser·p0.95          sample        15.662           ms/op
Client.getUser:getUser·p0.99          sample        22.938           ms/op
Client.getUser:getUser·p0.999         sample        59.178           ms/op
Client.getUser:getUser·p0.9999        sample        66.519           ms/op
Client.getUser:getUser·p1.00          sample        66.519           ms/op
Client.listUser                       sample  1231  26.454 ± 0.615   ms/op
Client.listUser:listUser·p0.00        sample         8.421           ms/op
Client.listUser:listUser·p0.50        sample        26.837           ms/op
Client.listUser:listUser·p0.90        sample        32.860           ms/op
Client.listUser:listUser·p0.95        sample        37.972           ms/op
Client.listUser:listUser·p0.99        sample        47.275           ms/op
Client.listUser:listUser·p0.999       sample        54.420           ms/op
Client.listUser:listUser·p0.9999      sample        54.526           ms/op
Client.listUser:listUser·p1.00        sample        54.526           ms/op
