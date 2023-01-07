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
# Warmup Iteration   1: 1.085 ops/ms
Iteration   1: 3.076 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.076 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.083 ops/ms
Iteration   1: 8.368 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  8.368 ops/ms


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
# Warmup Iteration   1: 2.457 ops/ms
Iteration   1: 5.612 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.612 ops/ms


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
# Warmup Iteration   1: 1.011 ops/ms
Iteration   1: 1.627 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.627 ops/ms


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
# Warmup Iteration   1: 19.073 ±(99.9%) 0.922 ms/op
Iteration   1: 7.641 ±(99.9%) 0.030 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  7.641 ms/op


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
# Warmup Iteration   1: 6.510 ±(99.9%) 0.072 ms/op
Iteration   1: 4.296 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.296 ms/op


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
# Warmup Iteration   1: 10.828 ±(99.9%) 0.183 ms/op
Iteration   1: 4.997 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.997 ms/op


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
# Warmup Iteration   1: 32.354 ±(99.9%) 0.473 ms/op
Iteration   1: 17.968 ±(99.9%) 0.090 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  17.968 ms/op


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
# Warmup Iteration   1: 10.430 ±(99.9%) 0.298 ms/op
Iteration   1: 5.997 ±(99.9%) 0.110 ms/op
                 createUser·p0.00:   2.408 ms/op
                 createUser·p0.50:   5.595 ms/op
                 createUser·p0.90:   5.997 ms/op
                 createUser·p0.95:   6.324 ms/op
                 createUser·p0.99:   20.519 ms/op
                 createUser·p0.999:  27.699 ms/op
                 createUser·p0.9999: 27.853 ms/op
                 createUser·p1.00:   27.853 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5339
  mean =      5.997 ±(99.9%) 0.110 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 164 
    [ 5.000,  7.500) = 4976 
    [ 7.500, 10.000) = 38 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      2.408 ms/op
     p(50.0000) =      5.595 ms/op
     p(90.0000) =      5.997 ms/op
     p(95.0000) =      6.324 ms/op
     p(99.0000) =     20.519 ms/op
     p(99.9000) =     27.699 ms/op
     p(99.9900) =     27.853 ms/op
     p(99.9990) =     27.853 ms/op
     p(99.9999) =     27.853 ms/op
    p(100.0000) =     27.853 ms/op


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
# Warmup Iteration   1: 4.683 ±(99.9%) 0.156 ms/op
Iteration   1: 3.110 ±(99.9%) 0.052 ms/op
                 existUser·p0.00:   1.178 ms/op
                 existUser·p0.50:   3.068 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   4.649 ms/op
                 existUser·p0.99:   10.878 ms/op
                 existUser·p0.999:  20.546 ms/op
                 existUser·p0.9999: 20.578 ms/op
                 existUser·p1.00:   20.578 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 10304
  mean =      3.110 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3335 
    [ 2.500,  5.000) = 6498 
    [ 5.000,  7.500) = 215 
    [ 7.500, 10.000) = 137 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.178 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      4.649 ms/op
     p(99.0000) =     10.878 ms/op
     p(99.9000) =     20.546 ms/op
     p(99.9900) =     20.578 ms/op
     p(99.9990) =     20.578 ms/op
     p(99.9999) =     20.578 ms/op
    p(100.0000) =     20.578 ms/op


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
# Warmup Iteration   1: 10.153 ±(99.9%) 0.329 ms/op
Iteration   1: 4.790 ±(99.9%) 0.049 ms/op
                 getUser·p0.00:   2.228 ms/op
                 getUser·p0.50:   4.637 ms/op
                 getUser·p0.90:   6.029 ms/op
                 getUser·p0.95:   6.382 ms/op
                 getUser·p0.99:   10.169 ms/op
                 getUser·p0.999:  13.894 ms/op
                 getUser·p0.9999: 13.910 ms/op
                 getUser·p1.00:   13.910 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6682
  mean =      4.790 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 2 
    [ 2.500,  3.750) = 899 
    [ 3.750,  5.000) = 3829 
    [ 5.000,  6.250) = 1549 
    [ 6.250,  7.500) = 242 
    [ 7.500,  8.750) = 68 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 55 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.228 ms/op
     p(50.0000) =      4.637 ms/op
     p(90.0000) =      6.029 ms/op
     p(95.0000) =      6.382 ms/op
     p(99.0000) =     10.169 ms/op
     p(99.9000) =     13.894 ms/op
     p(99.9900) =     13.910 ms/op
     p(99.9990) =     13.910 ms/op
     p(99.9999) =     13.910 ms/op
    p(100.0000) =     13.910 ms/op


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
# Warmup Iteration   1: 26.739 ±(99.9%) 1.084 ms/op
Iteration   1: 15.651 ±(99.9%) 0.223 ms/op
                 listUser·p0.00:   9.388 ms/op
                 listUser·p0.50:   14.828 ms/op
                 listUser·p0.90:   17.662 ms/op
                 listUser·p0.95:   23.737 ms/op
                 listUser·p0.99:   29.208 ms/op
                 listUser·p0.999:  30.538 ms/op
                 listUser·p0.9999: 30.933 ms/op
                 listUser·p1.00:   30.933 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2065
  mean =     15.651 ±(99.9%) 0.223 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 14 
    [10.000, 12.500) = 48 
    [12.500, 15.000) = 1102 
    [15.000, 17.500) = 691 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 40 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      9.388 ms/op
     p(50.0000) =     14.828 ms/op
     p(90.0000) =     17.662 ms/op
     p(95.0000) =     23.737 ms/op
     p(99.0000) =     29.208 ms/op
     p(99.9000) =     30.538 ms/op
     p(99.9900) =     30.933 ms/op
     p(99.9990) =     30.933 ms/op
     p(99.9999) =     30.933 ms/op
    p(100.0000) =     30.933 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          3.076          ops/ms
Client.existUser                       thrpt          8.368          ops/ms
Client.getUser                         thrpt          5.612          ops/ms
Client.listUser                        thrpt          1.627          ops/ms
Client.createUser                       avgt          7.641           ms/op
Client.existUser                        avgt          4.296           ms/op
Client.getUser                          avgt          4.997           ms/op
Client.listUser                         avgt         17.968           ms/op
Client.createUser                     sample   5339   5.997 ± 0.110   ms/op
Client.createUser:createUser·p0.00    sample          2.408           ms/op
Client.createUser:createUser·p0.50    sample          5.595           ms/op
Client.createUser:createUser·p0.90    sample          5.997           ms/op
Client.createUser:createUser·p0.95    sample          6.324           ms/op
Client.createUser:createUser·p0.99    sample         20.519           ms/op
Client.createUser:createUser·p0.999   sample         27.699           ms/op
Client.createUser:createUser·p0.9999  sample         27.853           ms/op
Client.createUser:createUser·p1.00    sample         27.853           ms/op
Client.existUser                      sample  10304   3.110 ± 0.052   ms/op
Client.existUser:existUser·p0.00      sample          1.178           ms/op
Client.existUser:existUser·p0.50      sample          3.068           ms/op
Client.existUser:existUser·p0.90      sample          3.564           ms/op
Client.existUser:existUser·p0.95      sample          4.649           ms/op
Client.existUser:existUser·p0.99      sample         10.878           ms/op
Client.existUser:existUser·p0.999     sample         20.546           ms/op
Client.existUser:existUser·p0.9999    sample         20.578           ms/op
Client.existUser:existUser·p1.00      sample         20.578           ms/op
Client.getUser                        sample   6682   4.790 ± 0.049   ms/op
Client.getUser:getUser·p0.00          sample          2.228           ms/op
Client.getUser:getUser·p0.50          sample          4.637           ms/op
Client.getUser:getUser·p0.90          sample          6.029           ms/op
Client.getUser:getUser·p0.95          sample          6.382           ms/op
Client.getUser:getUser·p0.99          sample         10.169           ms/op
Client.getUser:getUser·p0.999         sample         13.894           ms/op
Client.getUser:getUser·p0.9999        sample         13.910           ms/op
Client.getUser:getUser·p1.00          sample         13.910           ms/op
Client.listUser                       sample   2065  15.651 ± 0.223   ms/op
Client.listUser:listUser·p0.00        sample          9.388           ms/op
Client.listUser:listUser·p0.50        sample         14.828           ms/op
Client.listUser:listUser·p0.90        sample         17.662           ms/op
Client.listUser:listUser·p0.95        sample         23.737           ms/op
Client.listUser:listUser·p0.99        sample         29.208           ms/op
Client.listUser:listUser·p0.999       sample         30.538           ms/op
Client.listUser:listUser·p0.9999      sample         30.933           ms/op
Client.listUser:listUser·p1.00        sample         30.933           ms/op
