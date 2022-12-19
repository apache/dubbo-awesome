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
# Warmup Iteration   1: 1.041 ops/ms
Iteration   1: 3.070 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.070 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 2.532 ops/ms
Iteration   1: 6.664 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.664 ops/ms


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
# Warmup Iteration   1: 1.988 ops/ms
Iteration   1: 3.654 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.654 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 0.864 ops/ms
Iteration   1: 1.239 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.239 ops/ms


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
# Warmup Iteration   1: 20.083 ±(99.9%) 0.253 ms/op
Iteration   1: 9.677 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  9.677 ms/op


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
# Warmup Iteration   1: 9.327 ±(99.9%) 0.078 ms/op
Iteration   1: 3.862 ±(99.9%) 0.031 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.862 ms/op


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
# Warmup Iteration   1: 11.098 ±(99.9%) 0.122 ms/op
Iteration   1: 5.752 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.752 ms/op


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
# Warmup Iteration   1: 27.988 ±(99.9%) 0.745 ms/op
Iteration   1: 18.188 ±(99.9%) 0.181 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  18.188 ms/op


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
# Warmup Iteration   1: 15.047 ±(99.9%) 0.651 ms/op
Iteration   1: 7.619 ±(99.9%) 0.173 ms/op
                 createUser·p0.00:   1.446 ms/op
                 createUser·p0.50:   6.906 ms/op
                 createUser·p0.90:   10.512 ms/op
                 createUser·p0.95:   13.612 ms/op
                 createUser·p0.99:   19.333 ms/op
                 createUser·p0.999:  33.739 ms/op
                 createUser·p0.9999: 34.275 ms/op
                 createUser·p1.00:   34.275 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4181
  mean =      7.619 ±(99.9%) 0.173 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 86 
    [ 2.500,  5.000) = 247 
    [ 5.000,  7.500) = 2934 
    [ 7.500, 10.000) = 440 
    [10.000, 12.500) = 185 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.446 ms/op
     p(50.0000) =      6.906 ms/op
     p(90.0000) =     10.512 ms/op
     p(95.0000) =     13.612 ms/op
     p(99.0000) =     19.333 ms/op
     p(99.9000) =     33.739 ms/op
     p(99.9900) =     34.275 ms/op
     p(99.9990) =     34.275 ms/op
     p(99.9999) =     34.275 ms/op
    p(100.0000) =     34.275 ms/op


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
# Warmup Iteration   1: 6.927 ±(99.9%) 0.263 ms/op
Iteration   1: 3.930 ±(99.9%) 0.090 ms/op
                 existUser·p0.00:   0.672 ms/op
                 existUser·p0.50:   3.400 ms/op
                 existUser·p0.90:   5.766 ms/op
                 existUser·p0.95:   7.586 ms/op
                 existUser·p0.99:   14.051 ms/op
                 existUser·p0.999:  26.505 ms/op
                 existUser·p0.9999: 27.361 ms/op
                 existUser·p1.00:   27.361 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 8140
  mean =      3.930 ±(99.9%) 0.090 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1947 
    [ 2.500,  5.000) = 3974 
    [ 5.000,  7.500) = 1762 
    [ 7.500, 10.000) = 214 
    [10.000, 12.500) = 133 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.672 ms/op
     p(50.0000) =      3.400 ms/op
     p(90.0000) =      5.766 ms/op
     p(95.0000) =      7.586 ms/op
     p(99.0000) =     14.051 ms/op
     p(99.9000) =     26.505 ms/op
     p(99.9900) =     27.361 ms/op
     p(99.9990) =     27.361 ms/op
     p(99.9999) =     27.361 ms/op
    p(100.0000) =     27.361 ms/op


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
# Warmup Iteration   1: 10.441 ±(99.9%) 0.331 ms/op
Iteration   1: 4.803 ±(99.9%) 0.059 ms/op
                 getUser·p0.00:   2.019 ms/op
                 getUser·p0.50:   4.637 ms/op
                 getUser·p0.90:   5.480 ms/op
                 getUser·p0.95:   5.816 ms/op
                 getUser·p0.99:   13.276 ms/op
                 getUser·p0.999:  19.377 ms/op
                 getUser·p0.9999: 19.562 ms/op
                 getUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6669
  mean =      4.803 ±(99.9%) 0.059 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 18 
    [ 2.500,  3.750) = 462 
    [ 3.750,  5.000) = 4205 
    [ 5.000,  6.250) = 1752 
    [ 6.250,  7.500) = 110 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      2.019 ms/op
     p(50.0000) =      4.637 ms/op
     p(90.0000) =      5.480 ms/op
     p(95.0000) =      5.816 ms/op
     p(99.0000) =     13.276 ms/op
     p(99.9000) =     19.377 ms/op
     p(99.9900) =     19.562 ms/op
     p(99.9990) =     19.562 ms/op
     p(99.9999) =     19.562 ms/op
    p(100.0000) =     19.562 ms/op


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
# Warmup Iteration   1: 27.648 ±(99.9%) 0.773 ms/op
Iteration   1: 18.126 ±(99.9%) 0.304 ms/op
                 listUser·p0.00:   9.519 ms/op
                 listUser·p0.50:   17.924 ms/op
                 listUser·p0.90:   20.506 ms/op
                 listUser·p0.95:   25.133 ms/op
                 listUser·p0.99:   34.734 ms/op
                 listUser·p0.999:  36.258 ms/op
                 listUser·p0.9999: 36.307 ms/op
                 listUser·p1.00:   36.307 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1751
  mean =     18.126 ±(99.9%) 0.304 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 6 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 289 
    [15.000, 17.500) = 314 
    [17.500, 20.000) = 759 
    [20.000, 22.500) = 226 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      9.519 ms/op
     p(50.0000) =     17.924 ms/op
     p(90.0000) =     20.506 ms/op
     p(95.0000) =     25.133 ms/op
     p(99.0000) =     34.734 ms/op
     p(99.9000) =     36.258 ms/op
     p(99.9900) =     36.307 ms/op
     p(99.9990) =     36.307 ms/op
     p(99.9999) =     36.307 ms/op
    p(100.0000) =     36.307 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         3.070          ops/ms
Client.existUser                       thrpt         6.664          ops/ms
Client.getUser                         thrpt         3.654          ops/ms
Client.listUser                        thrpt         1.239          ops/ms
Client.createUser                       avgt         9.677           ms/op
Client.existUser                        avgt         3.862           ms/op
Client.getUser                          avgt         5.752           ms/op
Client.listUser                         avgt        18.188           ms/op
Client.createUser                     sample  4181   7.619 ± 0.173   ms/op
Client.createUser:createUser·p0.00    sample         1.446           ms/op
Client.createUser:createUser·p0.50    sample         6.906           ms/op
Client.createUser:createUser·p0.90    sample        10.512           ms/op
Client.createUser:createUser·p0.95    sample        13.612           ms/op
Client.createUser:createUser·p0.99    sample        19.333           ms/op
Client.createUser:createUser·p0.999   sample        33.739           ms/op
Client.createUser:createUser·p0.9999  sample        34.275           ms/op
Client.createUser:createUser·p1.00    sample        34.275           ms/op
Client.existUser                      sample  8140   3.930 ± 0.090   ms/op
Client.existUser:existUser·p0.00      sample         0.672           ms/op
Client.existUser:existUser·p0.50      sample         3.400           ms/op
Client.existUser:existUser·p0.90      sample         5.766           ms/op
Client.existUser:existUser·p0.95      sample         7.586           ms/op
Client.existUser:existUser·p0.99      sample        14.051           ms/op
Client.existUser:existUser·p0.999     sample        26.505           ms/op
Client.existUser:existUser·p0.9999    sample        27.361           ms/op
Client.existUser:existUser·p1.00      sample        27.361           ms/op
Client.getUser                        sample  6669   4.803 ± 0.059   ms/op
Client.getUser:getUser·p0.00          sample         2.019           ms/op
Client.getUser:getUser·p0.50          sample         4.637           ms/op
Client.getUser:getUser·p0.90          sample         5.480           ms/op
Client.getUser:getUser·p0.95          sample         5.816           ms/op
Client.getUser:getUser·p0.99          sample        13.276           ms/op
Client.getUser:getUser·p0.999         sample        19.377           ms/op
Client.getUser:getUser·p0.9999        sample        19.562           ms/op
Client.getUser:getUser·p1.00          sample        19.562           ms/op
Client.listUser                       sample  1751  18.126 ± 0.304   ms/op
Client.listUser:listUser·p0.00        sample         9.519           ms/op
Client.listUser:listUser·p0.50        sample        17.924           ms/op
Client.listUser:listUser·p0.90        sample        20.506           ms/op
Client.listUser:listUser·p0.95        sample        25.133           ms/op
Client.listUser:listUser·p0.99        sample        34.734           ms/op
Client.listUser:listUser·p0.999       sample        36.258           ms/op
Client.listUser:listUser·p0.9999      sample        36.307           ms/op
Client.listUser:listUser·p1.00        sample        36.307           ms/op
