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
# Warmup Iteration   1: 1.075 ops/ms
Iteration   1: 2.628 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.628 ops/ms


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
# Warmup Iteration   1: 3.344 ops/ms
Iteration   1: 7.138 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  7.138 ops/ms


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
# Warmup Iteration   1: 2.471 ops/ms
Iteration   1: 5.418 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.418 ops/ms


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
# Warmup Iteration   1: 0.998 ops/ms
Iteration   1: 1.809 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.809 ops/ms


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
# Warmup Iteration   1: 14.535 ±(99.9%) 0.196 ms/op
Iteration   1: 6.754 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.754 ms/op


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
# Warmup Iteration   1: 6.496 ±(99.9%) 0.055 ms/op
Iteration   1: 3.522 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.522 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.496 ±(99.9%) 0.129 ms/op
Iteration   1: 5.302 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.302 ms/op


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
# Warmup Iteration   1: 30.122 ±(99.9%) 0.607 ms/op
Iteration   1: 17.166 ±(99.9%) 0.067 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  17.166 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.570 ±(99.9%) 0.438 ms/op
Iteration   1: 5.659 ±(99.9%) 0.121 ms/op
                 createUser·p0.00:   0.423 ms/op
                 createUser·p0.50:   5.169 ms/op
                 createUser·p0.90:   6.775 ms/op
                 createUser·p0.95:   8.077 ms/op
                 createUser·p0.99:   18.250 ms/op
                 createUser·p0.999:  35.147 ms/op
                 createUser·p0.9999: 35.455 ms/op
                 createUser·p1.00:   35.455 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5703
  mean =      5.659 ±(99.9%) 0.121 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 2403 
    [ 5.000,  7.500) = 2921 
    [ 7.500, 10.000) = 142 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.423 ms/op
     p(50.0000) =      5.169 ms/op
     p(90.0000) =      6.775 ms/op
     p(95.0000) =      8.077 ms/op
     p(99.0000) =     18.250 ms/op
     p(99.9000) =     35.147 ms/op
     p(99.9900) =     35.455 ms/op
     p(99.9990) =     35.455 ms/op
     p(99.9999) =     35.455 ms/op
    p(100.0000) =     35.455 ms/op


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
# Warmup Iteration   1: 5.962 ±(99.9%) 0.190 ms/op
Iteration   1: 3.460 ±(99.9%) 0.040 ms/op
                 existUser·p0.00:   0.800 ms/op
                 existUser·p0.50:   3.502 ms/op
                 existUser·p0.90:   3.789 ms/op
                 existUser·p0.95:   3.944 ms/op
                 existUser·p0.99:   11.928 ms/op
                 existUser·p0.999:  13.271 ms/op
                 existUser·p0.9999: 13.287 ms/op
                 existUser·p1.00:   13.287 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 9240
  mean =      3.460 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 31 
    [ 1.250,  2.500) = 1031 
    [ 2.500,  3.750) = 6973 
    [ 3.750,  5.000) = 958 
    [ 5.000,  6.250) = 56 
    [ 6.250,  7.500) = 63 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.800 ms/op
     p(50.0000) =      3.502 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =     11.928 ms/op
     p(99.9000) =     13.271 ms/op
     p(99.9900) =     13.287 ms/op
     p(99.9990) =     13.287 ms/op
     p(99.9999) =     13.287 ms/op
    p(100.0000) =     13.287 ms/op


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
# Warmup Iteration   1: 7.519 ±(99.9%) 0.292 ms/op
Iteration   1: 4.378 ±(99.9%) 0.053 ms/op
                 getUser·p0.00:   1.190 ms/op
                 getUser·p0.50:   4.407 ms/op
                 getUser·p0.90:   5.161 ms/op
                 getUser·p0.95:   5.603 ms/op
                 getUser·p0.99:   10.699 ms/op
                 getUser·p0.999:  17.445 ms/op
                 getUser·p0.9999: 17.662 ms/op
                 getUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7305
  mean =      4.378 ±(99.9%) 0.053 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 140 
    [ 2.500,  3.750) = 1703 
    [ 3.750,  5.000) = 4573 
    [ 5.000,  6.250) = 620 
    [ 6.250,  7.500) = 104 
    [ 7.500,  8.750) = 51 
    [ 8.750, 10.000) = 14 
    [10.000, 11.250) = 37 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.190 ms/op
     p(50.0000) =      4.407 ms/op
     p(90.0000) =      5.161 ms/op
     p(95.0000) =      5.603 ms/op
     p(99.0000) =     10.699 ms/op
     p(99.9000) =     17.445 ms/op
     p(99.9900) =     17.662 ms/op
     p(99.9990) =     17.662 ms/op
     p(99.9999) =     17.662 ms/op
    p(100.0000) =     17.662 ms/op


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
# Warmup Iteration   1: 25.182 ±(99.9%) 0.826 ms/op
Iteration   1: 15.269 ±(99.9%) 0.133 ms/op
                 listUser·p0.00:   11.452 ms/op
                 listUser·p0.50:   14.746 ms/op
                 listUser·p0.90:   15.991 ms/op
                 listUser·p0.95:   18.022 ms/op
                 listUser·p0.99:   25.297 ms/op
                 listUser·p0.999:  25.662 ms/op
                 listUser·p0.9999: 25.887 ms/op
                 listUser·p1.00:   25.887 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2105
  mean =     15.269 ±(99.9%) 0.133 ms/op

  Histogram, ms/op:
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 1409 
    [15.000, 16.250) = 478 
    [16.250, 17.500) = 64 
    [17.500, 18.750) = 36 
    [18.750, 20.000) = 4 
    [20.000, 21.250) = 23 
    [21.250, 22.500) = 6 
    [22.500, 23.750) = 22 
    [23.750, 25.000) = 8 
    [25.000, 26.250) = 29 
    [26.250, 27.500) = 0 
    [27.500, 28.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =     11.452 ms/op
     p(50.0000) =     14.746 ms/op
     p(90.0000) =     15.991 ms/op
     p(95.0000) =     18.022 ms/op
     p(99.0000) =     25.297 ms/op
     p(99.9000) =     25.662 ms/op
     p(99.9900) =     25.887 ms/op
     p(99.9990) =     25.887 ms/op
     p(99.9999) =     25.887 ms/op
    p(100.0000) =     25.887 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.628          ops/ms
Client.existUser                       thrpt         7.138          ops/ms
Client.getUser                         thrpt         5.418          ops/ms
Client.listUser                        thrpt         1.809          ops/ms
Client.createUser                       avgt         6.754           ms/op
Client.existUser                        avgt         3.522           ms/op
Client.getUser                          avgt         5.302           ms/op
Client.listUser                         avgt        17.166           ms/op
Client.createUser                     sample  5703   5.659 ± 0.121   ms/op
Client.createUser:createUser·p0.00    sample         0.423           ms/op
Client.createUser:createUser·p0.50    sample         5.169           ms/op
Client.createUser:createUser·p0.90    sample         6.775           ms/op
Client.createUser:createUser·p0.95    sample         8.077           ms/op
Client.createUser:createUser·p0.99    sample        18.250           ms/op
Client.createUser:createUser·p0.999   sample        35.147           ms/op
Client.createUser:createUser·p0.9999  sample        35.455           ms/op
Client.createUser:createUser·p1.00    sample        35.455           ms/op
Client.existUser                      sample  9240   3.460 ± 0.040   ms/op
Client.existUser:existUser·p0.00      sample         0.800           ms/op
Client.existUser:existUser·p0.50      sample         3.502           ms/op
Client.existUser:existUser·p0.90      sample         3.789           ms/op
Client.existUser:existUser·p0.95      sample         3.944           ms/op
Client.existUser:existUser·p0.99      sample        11.928           ms/op
Client.existUser:existUser·p0.999     sample        13.271           ms/op
Client.existUser:existUser·p0.9999    sample        13.287           ms/op
Client.existUser:existUser·p1.00      sample        13.287           ms/op
Client.getUser                        sample  7305   4.378 ± 0.053   ms/op
Client.getUser:getUser·p0.00          sample         1.190           ms/op
Client.getUser:getUser·p0.50          sample         4.407           ms/op
Client.getUser:getUser·p0.90          sample         5.161           ms/op
Client.getUser:getUser·p0.95          sample         5.603           ms/op
Client.getUser:getUser·p0.99          sample        10.699           ms/op
Client.getUser:getUser·p0.999         sample        17.445           ms/op
Client.getUser:getUser·p0.9999        sample        17.662           ms/op
Client.getUser:getUser·p1.00          sample        17.662           ms/op
Client.listUser                       sample  2105  15.269 ± 0.133   ms/op
Client.listUser:listUser·p0.00        sample        11.452           ms/op
Client.listUser:listUser·p0.50        sample        14.746           ms/op
Client.listUser:listUser·p0.90        sample        15.991           ms/op
Client.listUser:listUser·p0.95        sample        18.022           ms/op
Client.listUser:listUser·p0.99        sample        25.297           ms/op
Client.listUser:listUser·p0.999       sample        25.662           ms/op
Client.listUser:listUser·p0.9999      sample        25.887           ms/op
Client.listUser:listUser·p1.00        sample        25.887           ms/op
