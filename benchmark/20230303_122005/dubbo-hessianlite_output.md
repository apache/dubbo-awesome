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
# Warmup Iteration   1: 1.231 ops/ms
Iteration   1: 2.867 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.867 ops/ms


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
# Warmup Iteration   1: 3.198 ops/ms
Iteration   1: 7.357 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  7.357 ops/ms


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
# Warmup Iteration   1: 1.718 ops/ms
Iteration   1: 5.112 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.112 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.027 ops/ms
Iteration   1: 1.699 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.699 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 14.064 ±(99.9%) 0.304 ms/op
Iteration   1: 7.041 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  7.041 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 6.281 ±(99.9%) 0.083 ms/op
Iteration   1: 3.446 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.446 ms/op


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
# Warmup Iteration   1: 8.633 ±(99.9%) 0.091 ms/op
Iteration   1: 4.727 ±(99.9%) 0.032 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.727 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 23.309 ±(99.9%) 0.429 ms/op
Iteration   1: 15.896 ±(99.9%) 0.069 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  15.896 ms/op


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
# Warmup Iteration   1: 9.871 ±(99.9%) 0.348 ms/op
Iteration   1: 6.398 ±(99.9%) 0.128 ms/op
                 createUser·p0.00:   1.790 ms/op
                 createUser·p0.50:   5.775 ms/op
                 createUser·p0.90:   9.798 ms/op
                 createUser·p0.95:   13.748 ms/op
                 createUser·p0.99:   15.843 ms/op
                 createUser·p0.999:  20.742 ms/op
                 createUser·p0.9999: 21.004 ms/op
                 createUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4997
  mean =      6.398 ±(99.9%) 0.128 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 144 
    [ 2.500,  5.000) = 480 
    [ 5.000,  7.500) = 3760 
    [ 7.500, 10.000) = 122 
    [10.000, 12.500) = 163 
    [12.500, 15.000) = 165 
    [15.000, 17.500) = 138 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.790 ms/op
     p(50.0000) =      5.775 ms/op
     p(90.0000) =      9.798 ms/op
     p(95.0000) =     13.748 ms/op
     p(99.0000) =     15.843 ms/op
     p(99.9000) =     20.742 ms/op
     p(99.9900) =     21.004 ms/op
     p(99.9990) =     21.004 ms/op
     p(99.9999) =     21.004 ms/op
    p(100.0000) =     21.004 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 6.410 ±(99.9%) 0.211 ms/op
Iteration   1: 3.721 ±(99.9%) 0.057 ms/op
                 existUser·p0.00:   0.986 ms/op
                 existUser·p0.50:   3.564 ms/op
                 existUser·p0.90:   3.858 ms/op
                 existUser·p0.95:   4.067 ms/op
                 existUser·p0.99:   14.702 ms/op
                 existUser·p0.999:  17.918 ms/op
                 existUser·p0.9999: 22.938 ms/op
                 existUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 8588
  mean =      3.721 ±(99.9%) 0.057 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 261 
    [ 2.500,  5.000) = 8164 
    [ 5.000,  7.500) = 3 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.986 ms/op
     p(50.0000) =      3.564 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.067 ms/op
     p(99.0000) =     14.702 ms/op
     p(99.9000) =     17.918 ms/op
     p(99.9900) =     22.938 ms/op
     p(99.9990) =     22.938 ms/op
     p(99.9999) =     22.938 ms/op
    p(100.0000) =     22.938 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 8.283 ±(99.9%) 0.275 ms/op
Iteration   1: 4.148 ±(99.9%) 0.052 ms/op
                 getUser·p0.00:   1.481 ms/op
                 getUser·p0.50:   3.748 ms/op
                 getUser·p0.90:   5.628 ms/op
                 getUser·p0.95:   6.421 ms/op
                 getUser·p0.99:   10.060 ms/op
                 getUser·p0.999:  14.143 ms/op
                 getUser·p0.9999: 14.500 ms/op
                 getUser·p1.00:   14.500 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7783
  mean =      4.148 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 64 
    [ 2.500,  3.750) = 3841 
    [ 3.750,  5.000) = 2517 
    [ 5.000,  6.250) = 926 
    [ 6.250,  7.500) = 219 
    [ 7.500,  8.750) = 91 
    [ 8.750, 10.000) = 44 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.481 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      5.628 ms/op
     p(95.0000) =      6.421 ms/op
     p(99.0000) =     10.060 ms/op
     p(99.9000) =     14.143 ms/op
     p(99.9900) =     14.500 ms/op
     p(99.9990) =     14.500 ms/op
     p(99.9999) =     14.500 ms/op
    p(100.0000) =     14.500 ms/op


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
# Warmup Iteration   1: 25.663 ±(99.9%) 0.821 ms/op
Iteration   1: 16.570 ±(99.9%) 0.276 ms/op
                 listUser·p0.00:   6.496 ms/op
                 listUser·p0.50:   15.827 ms/op
                 listUser·p0.90:   21.266 ms/op
                 listUser·p0.95:   23.688 ms/op
                 listUser·p0.99:   27.904 ms/op
                 listUser·p0.999:  29.837 ms/op
                 listUser·p0.9999: 30.048 ms/op
                 listUser·p1.00:   30.048 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1921
  mean =     16.570 ±(99.9%) 0.276 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 4 
    [ 7.500, 10.000) = 29 
    [10.000, 12.500) = 207 
    [12.500, 15.000) = 269 
    [15.000, 17.500) = 824 
    [17.500, 20.000) = 298 
    [20.000, 22.500) = 166 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 47 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      6.496 ms/op
     p(50.0000) =     15.827 ms/op
     p(90.0000) =     21.266 ms/op
     p(95.0000) =     23.688 ms/op
     p(99.0000) =     27.904 ms/op
     p(99.9000) =     29.837 ms/op
     p(99.9900) =     30.048 ms/op
     p(99.9990) =     30.048 ms/op
     p(99.9999) =     30.048 ms/op
    p(100.0000) =     30.048 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.867          ops/ms
Client.existUser                       thrpt         7.357          ops/ms
Client.getUser                         thrpt         5.112          ops/ms
Client.listUser                        thrpt         1.699          ops/ms
Client.createUser                       avgt         7.041           ms/op
Client.existUser                        avgt         3.446           ms/op
Client.getUser                          avgt         4.727           ms/op
Client.listUser                         avgt        15.896           ms/op
Client.createUser                     sample  4997   6.398 ± 0.128   ms/op
Client.createUser:createUser·p0.00    sample         1.790           ms/op
Client.createUser:createUser·p0.50    sample         5.775           ms/op
Client.createUser:createUser·p0.90    sample         9.798           ms/op
Client.createUser:createUser·p0.95    sample        13.748           ms/op
Client.createUser:createUser·p0.99    sample        15.843           ms/op
Client.createUser:createUser·p0.999   sample        20.742           ms/op
Client.createUser:createUser·p0.9999  sample        21.004           ms/op
Client.createUser:createUser·p1.00    sample        21.004           ms/op
Client.existUser                      sample  8588   3.721 ± 0.057   ms/op
Client.existUser:existUser·p0.00      sample         0.986           ms/op
Client.existUser:existUser·p0.50      sample         3.564           ms/op
Client.existUser:existUser·p0.90      sample         3.858           ms/op
Client.existUser:existUser·p0.95      sample         4.067           ms/op
Client.existUser:existUser·p0.99      sample        14.702           ms/op
Client.existUser:existUser·p0.999     sample        17.918           ms/op
Client.existUser:existUser·p0.9999    sample        22.938           ms/op
Client.existUser:existUser·p1.00      sample        22.938           ms/op
Client.getUser                        sample  7783   4.148 ± 0.052   ms/op
Client.getUser:getUser·p0.00          sample         1.481           ms/op
Client.getUser:getUser·p0.50          sample         3.748           ms/op
Client.getUser:getUser·p0.90          sample         5.628           ms/op
Client.getUser:getUser·p0.95          sample         6.421           ms/op
Client.getUser:getUser·p0.99          sample        10.060           ms/op
Client.getUser:getUser·p0.999         sample        14.143           ms/op
Client.getUser:getUser·p0.9999        sample        14.500           ms/op
Client.getUser:getUser·p1.00          sample        14.500           ms/op
Client.listUser                       sample  1921  16.570 ± 0.276   ms/op
Client.listUser:listUser·p0.00        sample         6.496           ms/op
Client.listUser:listUser·p0.50        sample        15.827           ms/op
Client.listUser:listUser·p0.90        sample        21.266           ms/op
Client.listUser:listUser·p0.95        sample        23.688           ms/op
Client.listUser:listUser·p0.99        sample        27.904           ms/op
Client.listUser:listUser·p0.999       sample        29.837           ms/op
Client.listUser:listUser·p0.9999      sample        30.048           ms/op
Client.listUser:listUser·p1.00        sample        30.048           ms/op
