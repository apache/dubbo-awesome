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
# Warmup Iteration   1: 1.480 ops/ms
Iteration   1: 2.580 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.580 ops/ms


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
# Warmup Iteration   1: 2.671 ops/ms
Iteration   1: 9.359 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  9.359 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.426 ops/ms
Iteration   1: 5.716 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.716 ops/ms


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
# Warmup Iteration   1: 0.928 ops/ms
Iteration   1: 1.455 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.455 ops/ms


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
# Warmup Iteration   1: 14.801 ±(99.9%) 0.172 ms/op
Iteration   1: 6.187 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.187 ms/op


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
# Warmup Iteration   1: 6.282 ±(99.9%) 0.072 ms/op
Iteration   1: 3.920 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.920 ms/op


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
# Warmup Iteration   1: 8.281 ±(99.9%) 0.139 ms/op
Iteration   1: 4.328 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.328 ms/op


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
# Warmup Iteration   1: 25.562 ±(99.9%) 0.365 ms/op
Iteration   1: 16.283 ±(99.9%) 0.096 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  16.283 ms/op


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
# Warmup Iteration   1: 9.627 ±(99.9%) 0.327 ms/op
Iteration   1: 5.497 ±(99.9%) 0.137 ms/op
                 createUser·p0.00:   1.927 ms/op
                 createUser·p0.50:   5.112 ms/op
                 createUser·p0.90:   6.062 ms/op
                 createUser·p0.95:   9.535 ms/op
                 createUser·p0.99:   28.001 ms/op
                 createUser·p0.999:  34.218 ms/op
                 createUser·p0.9999: 34.406 ms/op
                 createUser·p1.00:   34.406 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5873
  mean =      5.497 ±(99.9%) 0.137 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 108 
    [ 2.500,  5.000) = 2391 
    [ 5.000,  7.500) = 2979 
    [ 7.500, 10.000) = 128 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.927 ms/op
     p(50.0000) =      5.112 ms/op
     p(90.0000) =      6.062 ms/op
     p(95.0000) =      9.535 ms/op
     p(99.0000) =     28.001 ms/op
     p(99.9000) =     34.218 ms/op
     p(99.9900) =     34.406 ms/op
     p(99.9990) =     34.406 ms/op
     p(99.9999) =     34.406 ms/op
    p(100.0000) =     34.406 ms/op


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
# Warmup Iteration   1: 5.701 ±(99.9%) 0.195 ms/op
Iteration   1: 3.206 ±(99.9%) 0.052 ms/op
                 existUser·p0.00:   0.592 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   4.481 ms/op
                 existUser·p0.95:   4.817 ms/op
                 existUser·p0.99:   8.385 ms/op
                 existUser·p0.999:  14.468 ms/op
                 existUser·p0.9999: 14.991 ms/op
                 existUser·p1.00:   14.991 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 9972
  mean =      3.206 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 294 
    [ 1.250,  2.500) = 3946 
    [ 2.500,  3.750) = 1398 
    [ 3.750,  5.000) = 3903 
    [ 5.000,  6.250) = 109 
    [ 6.250,  7.500) = 169 
    [ 7.500,  8.750) = 57 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.592 ms/op
     p(50.0000) =      2.863 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      4.817 ms/op
     p(99.0000) =      8.385 ms/op
     p(99.9000) =     14.468 ms/op
     p(99.9900) =     14.991 ms/op
     p(99.9990) =     14.991 ms/op
     p(99.9999) =     14.991 ms/op
    p(100.0000) =     14.991 ms/op


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
# Warmup Iteration   1: 8.829 ±(99.9%) 0.325 ms/op
Iteration   1: 4.087 ±(99.9%) 0.046 ms/op
                 getUser·p0.00:   1.026 ms/op
                 getUser·p0.50:   4.100 ms/op
                 getUser·p0.90:   5.161 ms/op
                 getUser·p0.95:   5.857 ms/op
                 getUser·p0.99:   9.232 ms/op
                 getUser·p0.999:  13.959 ms/op
                 getUser·p0.9999: 13.976 ms/op
                 getUser·p1.00:   13.976 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7951
  mean =      4.087 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 15 
    [ 1.250,  2.500) = 423 
    [ 2.500,  3.750) = 2379 
    [ 3.750,  5.000) = 4294 
    [ 5.000,  6.250) = 617 
    [ 6.250,  7.500) = 69 
    [ 7.500,  8.750) = 51 
    [ 8.750, 10.000) = 51 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.026 ms/op
     p(50.0000) =      4.100 ms/op
     p(90.0000) =      5.161 ms/op
     p(95.0000) =      5.857 ms/op
     p(99.0000) =      9.232 ms/op
     p(99.9000) =     13.959 ms/op
     p(99.9900) =     13.976 ms/op
     p(99.9990) =     13.976 ms/op
     p(99.9999) =     13.976 ms/op
    p(100.0000) =     13.976 ms/op


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
# Warmup Iteration   1: 25.276 ±(99.9%) 0.861 ms/op
Iteration   1: 15.231 ±(99.9%) 0.206 ms/op
                 listUser·p0.00:   5.251 ms/op
                 listUser·p0.50:   14.418 ms/op
                 listUser·p0.90:   17.662 ms/op
                 listUser·p0.95:   20.850 ms/op
                 listUser·p0.99:   28.093 ms/op
                 listUser·p0.999:  33.445 ms/op
                 listUser·p0.9999: 39.059 ms/op
                 listUser·p1.00:   39.059 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2133
  mean =     15.231 ±(99.9%) 0.206 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 8 
    [ 7.500, 10.000) = 7 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 1296 
    [15.000, 17.500) = 572 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 26 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      5.251 ms/op
     p(50.0000) =     14.418 ms/op
     p(90.0000) =     17.662 ms/op
     p(95.0000) =     20.850 ms/op
     p(99.0000) =     28.093 ms/op
     p(99.9000) =     33.445 ms/op
     p(99.9900) =     39.059 ms/op
     p(99.9990) =     39.059 ms/op
     p(99.9999) =     39.059 ms/op
    p(100.0000) =     39.059 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.580          ops/ms
Client.existUser                       thrpt         9.359          ops/ms
Client.getUser                         thrpt         5.716          ops/ms
Client.listUser                        thrpt         1.455          ops/ms
Client.createUser                       avgt         6.187           ms/op
Client.existUser                        avgt         3.920           ms/op
Client.getUser                          avgt         4.328           ms/op
Client.listUser                         avgt        16.283           ms/op
Client.createUser                     sample  5873   5.497 ± 0.137   ms/op
Client.createUser:createUser·p0.00    sample         1.927           ms/op
Client.createUser:createUser·p0.50    sample         5.112           ms/op
Client.createUser:createUser·p0.90    sample         6.062           ms/op
Client.createUser:createUser·p0.95    sample         9.535           ms/op
Client.createUser:createUser·p0.99    sample        28.001           ms/op
Client.createUser:createUser·p0.999   sample        34.218           ms/op
Client.createUser:createUser·p0.9999  sample        34.406           ms/op
Client.createUser:createUser·p1.00    sample        34.406           ms/op
Client.existUser                      sample  9972   3.206 ± 0.052   ms/op
Client.existUser:existUser·p0.00      sample         0.592           ms/op
Client.existUser:existUser·p0.50      sample         2.863           ms/op
Client.existUser:existUser·p0.90      sample         4.481           ms/op
Client.existUser:existUser·p0.95      sample         4.817           ms/op
Client.existUser:existUser·p0.99      sample         8.385           ms/op
Client.existUser:existUser·p0.999     sample        14.468           ms/op
Client.existUser:existUser·p0.9999    sample        14.991           ms/op
Client.existUser:existUser·p1.00      sample        14.991           ms/op
Client.getUser                        sample  7951   4.087 ± 0.046   ms/op
Client.getUser:getUser·p0.00          sample         1.026           ms/op
Client.getUser:getUser·p0.50          sample         4.100           ms/op
Client.getUser:getUser·p0.90          sample         5.161           ms/op
Client.getUser:getUser·p0.95          sample         5.857           ms/op
Client.getUser:getUser·p0.99          sample         9.232           ms/op
Client.getUser:getUser·p0.999         sample        13.959           ms/op
Client.getUser:getUser·p0.9999        sample        13.976           ms/op
Client.getUser:getUser·p1.00          sample        13.976           ms/op
Client.listUser                       sample  2133  15.231 ± 0.206   ms/op
Client.listUser:listUser·p0.00        sample         5.251           ms/op
Client.listUser:listUser·p0.50        sample        14.418           ms/op
Client.listUser:listUser·p0.90        sample        17.662           ms/op
Client.listUser:listUser·p0.95        sample        20.850           ms/op
Client.listUser:listUser·p0.99        sample        28.093           ms/op
Client.listUser:listUser·p0.999       sample        33.445           ms/op
Client.listUser:listUser·p0.9999      sample        39.059           ms/op
Client.listUser:listUser·p1.00        sample        39.059           ms/op
