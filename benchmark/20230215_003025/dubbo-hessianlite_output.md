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
# Warmup Iteration   1: 0.589 ops/ms
Iteration   1: 0.963 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  0.963 ops/ms


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
# Warmup Iteration   1: 1.285 ops/ms
Iteration   1: 3.444 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.444 ops/ms


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
# Warmup Iteration   1: 1.060 ops/ms
Iteration   1: 1.867 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  1.867 ops/ms


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
# Warmup Iteration   1: 0.532 ops/ms
Iteration   1: 0.877 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  0.877 ops/ms


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
# Warmup Iteration   1: 35.380 ±(99.9%) 1.541 ms/op
Iteration   1: 16.865 ±(99.9%) 0.129 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  16.865 ms/op


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
# Warmup Iteration   1: 21.565 ±(99.9%) 0.377 ms/op
Iteration   1: 10.379 ±(99.9%) 0.115 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  10.379 ms/op


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
# Warmup Iteration   1: 27.476 ±(99.9%) 0.452 ms/op
Iteration   1: 11.558 ±(99.9%) 0.221 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  11.558 ms/op


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
# Warmup Iteration   1: 46.882 ±(99.9%) 1.444 ms/op
Iteration   1: 32.138 ±(99.9%) 0.409 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  32.138 ms/op


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
# Warmup Iteration   1: 25.164 ±(99.9%) 0.984 ms/op
Iteration   1: 13.797 ±(99.9%) 0.540 ms/op
                 createUser·p0.00:   3.248 ms/op
                 createUser·p0.50:   11.715 ms/op
                 createUser·p0.90:   20.677 ms/op
                 createUser·p0.95:   28.561 ms/op
                 createUser·p0.99:   51.970 ms/op
                 createUser·p0.999:  55.377 ms/op
                 createUser·p0.9999: 55.509 ms/op
                 createUser·p1.00:   55.509 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 2335
  mean =     13.797 ±(99.9%) 0.540 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 124 
    [ 5.000, 10.000) = 384 
    [10.000, 15.000) = 1276 
    [15.000, 20.000) = 275 
    [20.000, 25.000) = 110 
    [25.000, 30.000) = 54 
    [30.000, 35.000) = 47 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 28 
    [45.000, 50.000) = 5 
    [50.000, 55.000) = 28 

  Percentiles, ms/op:
      p(0.0000) =      3.248 ms/op
     p(50.0000) =     11.715 ms/op
     p(90.0000) =     20.677 ms/op
     p(95.0000) =     28.561 ms/op
     p(99.0000) =     51.970 ms/op
     p(99.9000) =     55.377 ms/op
     p(99.9900) =     55.509 ms/op
     p(99.9990) =     55.509 ms/op
     p(99.9999) =     55.509 ms/op
    p(100.0000) =     55.509 ms/op


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
# Warmup Iteration   1: 14.426 ±(99.9%) 0.348 ms/op
Iteration   1: 9.563 ±(99.9%) 0.272 ms/op
                 existUser·p0.00:   1.473 ms/op
                 existUser·p0.50:   8.323 ms/op
                 existUser·p0.90:   15.155 ms/op
                 existUser·p0.95:   19.333 ms/op
                 existUser·p0.99:   29.734 ms/op
                 existUser·p0.999:  38.288 ms/op
                 existUser·p0.9999: 41.878 ms/op
                 existUser·p1.00:   41.878 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 3352
  mean =      9.563 ±(99.9%) 0.272 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 225 
    [ 5.000, 10.000) = 2141 
    [10.000, 15.000) = 616 
    [15.000, 20.000) = 228 
    [20.000, 25.000) = 63 
    [25.000, 30.000) = 51 
    [30.000, 35.000) = 15 
    [35.000, 40.000) = 11 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.473 ms/op
     p(50.0000) =      8.323 ms/op
     p(90.0000) =     15.155 ms/op
     p(95.0000) =     19.333 ms/op
     p(99.0000) =     29.734 ms/op
     p(99.9000) =     38.288 ms/op
     p(99.9900) =     41.878 ms/op
     p(99.9990) =     41.878 ms/op
     p(99.9999) =     41.878 ms/op
    p(100.0000) =     41.878 ms/op


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
# Warmup Iteration   1: 22.114 ±(99.9%) 0.770 ms/op
Iteration   1: 9.434 ±(99.9%) 0.220 ms/op
                 getUser·p0.00:   2.433 ms/op
                 getUser·p0.50:   8.749 ms/op
                 getUser·p0.90:   13.238 ms/op
                 getUser·p0.95:   16.928 ms/op
                 getUser·p0.99:   27.143 ms/op
                 getUser·p0.999:  34.546 ms/op
                 getUser·p0.9999: 35.127 ms/op
                 getUser·p1.00:   35.127 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 3373
  mean =      9.434 ±(99.9%) 0.220 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 94 
    [ 5.000,  7.500) = 911 
    [ 7.500, 10.000) = 1409 
    [10.000, 12.500) = 560 
    [12.500, 15.000) = 190 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 19 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.433 ms/op
     p(50.0000) =      8.749 ms/op
     p(90.0000) =     13.238 ms/op
     p(95.0000) =     16.928 ms/op
     p(99.0000) =     27.143 ms/op
     p(99.9000) =     34.546 ms/op
     p(99.9900) =     35.127 ms/op
     p(99.9990) =     35.127 ms/op
     p(99.9999) =     35.127 ms/op
    p(100.0000) =     35.127 ms/op


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
# Warmup Iteration   1: 43.676 ±(99.9%) 1.225 ms/op
Iteration   1: 28.950 ±(99.9%) 0.745 ms/op
                 listUser·p0.00:   11.272 ms/op
                 listUser·p0.50:   27.296 ms/op
                 listUser·p0.90:   38.470 ms/op
                 listUser·p0.95:   47.448 ms/op
                 listUser·p0.99:   54.591 ms/op
                 listUser·p0.999:  64.664 ms/op
                 listUser·p0.9999: 65.733 ms/op
                 listUser·p1.00:   65.733 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1099
  mean =     28.950 ±(99.9%) 0.745 ms/op

  Histogram, ms/op:
    [10.000, 15.000) = 6 
    [15.000, 20.000) = 12 
    [20.000, 25.000) = 374 
    [25.000, 30.000) = 410 
    [30.000, 35.000) = 131 
    [35.000, 40.000) = 62 
    [40.000, 45.000) = 43 
    [45.000, 50.000) = 22 
    [50.000, 55.000) = 36 
    [55.000, 60.000) = 2 
    [60.000, 65.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =     11.272 ms/op
     p(50.0000) =     27.296 ms/op
     p(90.0000) =     38.470 ms/op
     p(95.0000) =     47.448 ms/op
     p(99.0000) =     54.591 ms/op
     p(99.9000) =     64.664 ms/op
     p(99.9900) =     65.733 ms/op
     p(99.9990) =     65.733 ms/op
     p(99.9999) =     65.733 ms/op
    p(100.0000) =     65.733 ms/op


# Run complete. Total time: 00:01:35

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         0.963          ops/ms
Client.existUser                       thrpt         3.444          ops/ms
Client.getUser                         thrpt         1.867          ops/ms
Client.listUser                        thrpt         0.877          ops/ms
Client.createUser                       avgt        16.865           ms/op
Client.existUser                        avgt        10.379           ms/op
Client.getUser                          avgt        11.558           ms/op
Client.listUser                         avgt        32.138           ms/op
Client.createUser                     sample  2335  13.797 ± 0.540   ms/op
Client.createUser:createUser·p0.00    sample         3.248           ms/op
Client.createUser:createUser·p0.50    sample        11.715           ms/op
Client.createUser:createUser·p0.90    sample        20.677           ms/op
Client.createUser:createUser·p0.95    sample        28.561           ms/op
Client.createUser:createUser·p0.99    sample        51.970           ms/op
Client.createUser:createUser·p0.999   sample        55.377           ms/op
Client.createUser:createUser·p0.9999  sample        55.509           ms/op
Client.createUser:createUser·p1.00    sample        55.509           ms/op
Client.existUser                      sample  3352   9.563 ± 0.272   ms/op
Client.existUser:existUser·p0.00      sample         1.473           ms/op
Client.existUser:existUser·p0.50      sample         8.323           ms/op
Client.existUser:existUser·p0.90      sample        15.155           ms/op
Client.existUser:existUser·p0.95      sample        19.333           ms/op
Client.existUser:existUser·p0.99      sample        29.734           ms/op
Client.existUser:existUser·p0.999     sample        38.288           ms/op
Client.existUser:existUser·p0.9999    sample        41.878           ms/op
Client.existUser:existUser·p1.00      sample        41.878           ms/op
Client.getUser                        sample  3373   9.434 ± 0.220   ms/op
Client.getUser:getUser·p0.00          sample         2.433           ms/op
Client.getUser:getUser·p0.50          sample         8.749           ms/op
Client.getUser:getUser·p0.90          sample        13.238           ms/op
Client.getUser:getUser·p0.95          sample        16.928           ms/op
Client.getUser:getUser·p0.99          sample        27.143           ms/op
Client.getUser:getUser·p0.999         sample        34.546           ms/op
Client.getUser:getUser·p0.9999        sample        35.127           ms/op
Client.getUser:getUser·p1.00          sample        35.127           ms/op
Client.listUser                       sample  1099  28.950 ± 0.745   ms/op
Client.listUser:listUser·p0.00        sample        11.272           ms/op
Client.listUser:listUser·p0.50        sample        27.296           ms/op
Client.listUser:listUser·p0.90        sample        38.470           ms/op
Client.listUser:listUser·p0.95        sample        47.448           ms/op
Client.listUser:listUser·p0.99        sample        54.591           ms/op
Client.listUser:listUser·p0.999       sample        64.664           ms/op
Client.listUser:listUser·p0.9999      sample        65.733           ms/op
Client.listUser:listUser·p1.00        sample        65.733           ms/op
