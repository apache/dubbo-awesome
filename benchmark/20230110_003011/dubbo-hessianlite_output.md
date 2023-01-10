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
# Warmup Iteration   1: 1.372 ops/ms
Iteration   1: 2.829 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.829 ops/ms


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
# Warmup Iteration   1: 2.578 ops/ms
Iteration   1: 9.206 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  9.206 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 1.999 ops/ms
Iteration   1: 5.657 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.657 ops/ms


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
# Warmup Iteration   1: 0.954 ops/ms
Iteration   1: 1.431 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.431 ops/ms


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
# Warmup Iteration   1: 14.492 ±(99.9%) 0.147 ms/op
Iteration   1: 6.454 ±(99.9%) 0.045 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.454 ms/op


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
# Warmup Iteration   1: 6.658 ±(99.9%) 0.065 ms/op
Iteration   1: 3.197 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.197 ms/op


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
# Warmup Iteration   1: 8.886 ±(99.9%) 0.096 ms/op
Iteration   1: 4.288 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.288 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 28.295 ±(99.9%) 0.765 ms/op
Iteration   1: 15.087 ±(99.9%) 0.079 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  15.087 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.960 ±(99.9%) 0.392 ms/op
Iteration   1: 5.747 ±(99.9%) 0.096 ms/op
                 createUser·p0.00:   1.460 ms/op
                 createUser·p0.50:   5.546 ms/op
                 createUser·p0.90:   7.913 ms/op
                 createUser·p0.95:   10.961 ms/op
                 createUser·p0.99:   14.270 ms/op
                 createUser·p0.999:  15.892 ms/op
                 createUser·p0.9999: 17.302 ms/op
                 createUser·p1.00:   17.302 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5672
  mean =      5.747 ±(99.9%) 0.096 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 269 
    [ 2.500,  3.750) = 420 
    [ 3.750,  5.000) = 920 
    [ 5.000,  6.250) = 3015 
    [ 6.250,  7.500) = 440 
    [ 7.500,  8.750) = 176 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 166 
    [11.250, 12.500) = 72 
    [12.500, 13.750) = 45 
    [13.750, 15.000) = 89 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.460 ms/op
     p(50.0000) =      5.546 ms/op
     p(90.0000) =      7.913 ms/op
     p(95.0000) =     10.961 ms/op
     p(99.0000) =     14.270 ms/op
     p(99.9000) =     15.892 ms/op
     p(99.9900) =     17.302 ms/op
     p(99.9990) =     17.302 ms/op
     p(99.9999) =     17.302 ms/op
    p(100.0000) =     17.302 ms/op


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
# Warmup Iteration   1: 5.673 ±(99.9%) 0.177 ms/op
Iteration   1: 3.577 ±(99.9%) 0.063 ms/op
                 existUser·p0.00:   0.984 ms/op
                 existUser·p0.50:   3.617 ms/op
                 existUser·p0.90:   4.276 ms/op
                 existUser·p0.95:   4.456 ms/op
                 existUser·p0.99:   11.327 ms/op
                 existUser·p0.999:  22.348 ms/op
                 existUser·p0.9999: 23.986 ms/op
                 existUser·p1.00:   23.986 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 8962
  mean =      3.577 ±(99.9%) 0.063 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1998 
    [ 2.500,  5.000) = 6650 
    [ 5.000,  7.500) = 63 
    [ 7.500, 10.000) = 137 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.984 ms/op
     p(50.0000) =      3.617 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =     11.327 ms/op
     p(99.9000) =     22.348 ms/op
     p(99.9900) =     23.986 ms/op
     p(99.9990) =     23.986 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


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
# Warmup Iteration   1: 8.396 ±(99.9%) 0.267 ms/op
Iteration   1: 4.443 ±(99.9%) 0.046 ms/op
                 getUser·p0.00:   1.249 ms/op
                 getUser·p0.50:   4.407 ms/op
                 getUser·p0.90:   5.243 ms/op
                 getUser·p0.95:   5.521 ms/op
                 getUser·p0.99:   8.995 ms/op
                 getUser·p0.999:  14.616 ms/op
                 getUser·p0.9999: 16.335 ms/op
                 getUser·p1.00:   16.335 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7224
  mean =      4.443 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 143 
    [ 2.500,  3.750) = 1503 
    [ 3.750,  5.000) = 4222 
    [ 5.000,  6.250) = 1126 
    [ 6.250,  7.500) = 103 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 20 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.249 ms/op
     p(50.0000) =      4.407 ms/op
     p(90.0000) =      5.243 ms/op
     p(95.0000) =      5.521 ms/op
     p(99.0000) =      8.995 ms/op
     p(99.9000) =     14.616 ms/op
     p(99.9900) =     16.335 ms/op
     p(99.9990) =     16.335 ms/op
     p(99.9999) =     16.335 ms/op
    p(100.0000) =     16.335 ms/op


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
# Warmup Iteration   1: 25.364 ±(99.9%) 0.762 ms/op
Iteration   1: 16.314 ±(99.9%) 0.314 ms/op
                 listUser·p0.00:   4.538 ms/op
                 listUser·p0.50:   16.024 ms/op
                 listUser·p0.90:   18.907 ms/op
                 listUser·p0.95:   27.001 ms/op
                 listUser·p0.99:   30.384 ms/op
                 listUser·p0.999:  37.867 ms/op
                 listUser·p0.9999: 39.059 ms/op
                 listUser·p1.00:   39.059 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1957
  mean =     16.314 ±(99.9%) 0.314 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 9 
    [ 5.000,  7.500) = 10 
    [ 7.500, 10.000) = 23 
    [10.000, 12.500) = 223 
    [12.500, 15.000) = 537 
    [15.000, 17.500) = 466 
    [17.500, 20.000) = 529 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 53 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      4.538 ms/op
     p(50.0000) =     16.024 ms/op
     p(90.0000) =     18.907 ms/op
     p(95.0000) =     27.001 ms/op
     p(99.0000) =     30.384 ms/op
     p(99.9000) =     37.867 ms/op
     p(99.9900) =     39.059 ms/op
     p(99.9990) =     39.059 ms/op
     p(99.9999) =     39.059 ms/op
    p(100.0000) =     39.059 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.829          ops/ms
Client.existUser                       thrpt         9.206          ops/ms
Client.getUser                         thrpt         5.657          ops/ms
Client.listUser                        thrpt         1.431          ops/ms
Client.createUser                       avgt         6.454           ms/op
Client.existUser                        avgt         3.197           ms/op
Client.getUser                          avgt         4.288           ms/op
Client.listUser                         avgt        15.087           ms/op
Client.createUser                     sample  5672   5.747 ± 0.096   ms/op
Client.createUser:createUser·p0.00    sample         1.460           ms/op
Client.createUser:createUser·p0.50    sample         5.546           ms/op
Client.createUser:createUser·p0.90    sample         7.913           ms/op
Client.createUser:createUser·p0.95    sample        10.961           ms/op
Client.createUser:createUser·p0.99    sample        14.270           ms/op
Client.createUser:createUser·p0.999   sample        15.892           ms/op
Client.createUser:createUser·p0.9999  sample        17.302           ms/op
Client.createUser:createUser·p1.00    sample        17.302           ms/op
Client.existUser                      sample  8962   3.577 ± 0.063   ms/op
Client.existUser:existUser·p0.00      sample         0.984           ms/op
Client.existUser:existUser·p0.50      sample         3.617           ms/op
Client.existUser:existUser·p0.90      sample         4.276           ms/op
Client.existUser:existUser·p0.95      sample         4.456           ms/op
Client.existUser:existUser·p0.99      sample        11.327           ms/op
Client.existUser:existUser·p0.999     sample        22.348           ms/op
Client.existUser:existUser·p0.9999    sample        23.986           ms/op
Client.existUser:existUser·p1.00      sample        23.986           ms/op
Client.getUser                        sample  7224   4.443 ± 0.046   ms/op
Client.getUser:getUser·p0.00          sample         1.249           ms/op
Client.getUser:getUser·p0.50          sample         4.407           ms/op
Client.getUser:getUser·p0.90          sample         5.243           ms/op
Client.getUser:getUser·p0.95          sample         5.521           ms/op
Client.getUser:getUser·p0.99          sample         8.995           ms/op
Client.getUser:getUser·p0.999         sample        14.616           ms/op
Client.getUser:getUser·p0.9999        sample        16.335           ms/op
Client.getUser:getUser·p1.00          sample        16.335           ms/op
Client.listUser                       sample  1957  16.314 ± 0.314   ms/op
Client.listUser:listUser·p0.00        sample         4.538           ms/op
Client.listUser:listUser·p0.50        sample        16.024           ms/op
Client.listUser:listUser·p0.90        sample        18.907           ms/op
Client.listUser:listUser·p0.95        sample        27.001           ms/op
Client.listUser:listUser·p0.99        sample        30.384           ms/op
Client.listUser:listUser·p0.999       sample        37.867           ms/op
Client.listUser:listUser·p0.9999      sample        39.059           ms/op
Client.listUser:listUser·p1.00        sample        39.059           ms/op
