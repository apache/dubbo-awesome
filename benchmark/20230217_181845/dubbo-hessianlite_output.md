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
# Warmup Iteration   1: 1.102 ops/ms
Iteration   1: 2.836 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.836 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 3.203 ops/ms
Iteration   1: 7.642 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  7.642 ops/ms


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
# Warmup Iteration   1: 1.721 ops/ms
Iteration   1: 5.051 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.051 ops/ms


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
# Warmup Iteration   1: 0.887 ops/ms
Iteration   1: 1.371 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.371 ops/ms


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
# Warmup Iteration   1: 19.610 ±(99.9%) 0.277 ms/op
Iteration   1: 6.505 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.505 ms/op


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
# Warmup Iteration   1: 6.449 ±(99.9%) 0.062 ms/op
Iteration   1: 3.087 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.087 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.131 ±(99.9%) 0.154 ms/op
Iteration   1: 4.828 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.828 ms/op


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
# Warmup Iteration   1: 24.576 ±(99.9%) 0.512 ms/op
Iteration   1: 16.200 ±(99.9%) 0.030 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  16.200 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 12.491 ±(99.9%) 0.546 ms/op
Iteration   1: 5.479 ±(99.9%) 0.088 ms/op
                 createUser·p0.00:   3.199 ms/op
                 createUser·p0.50:   5.423 ms/op
                 createUser·p0.90:   6.074 ms/op
                 createUser·p0.95:   6.373 ms/op
                 createUser·p0.99:   13.976 ms/op
                 createUser·p0.999:  30.097 ms/op
                 createUser·p0.9999: 33.161 ms/op
                 createUser·p1.00:   33.161 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5835
  mean =      5.479 ±(99.9%) 0.088 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 1020 
    [ 5.000,  7.500) = 4734 
    [ 7.500, 10.000) = 17 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.199 ms/op
     p(50.0000) =      5.423 ms/op
     p(90.0000) =      6.074 ms/op
     p(95.0000) =      6.373 ms/op
     p(99.0000) =     13.976 ms/op
     p(99.9000) =     30.097 ms/op
     p(99.9900) =     33.161 ms/op
     p(99.9990) =     33.161 ms/op
     p(99.9999) =     33.161 ms/op
    p(100.0000) =     33.161 ms/op


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
# Warmup Iteration   1: 7.373 ±(99.9%) 0.238 ms/op
Iteration   1: 3.818 ±(99.9%) 0.053 ms/op
                 existUser·p0.00:   0.966 ms/op
                 existUser·p0.50:   3.625 ms/op
                 existUser·p0.90:   4.043 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   7.479 ms/op
                 existUser·p0.999:  25.461 ms/op
                 existUser·p0.9999: 27.394 ms/op
                 existUser·p1.00:   27.394 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 8525
  mean =      3.818 ±(99.9%) 0.053 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 173 
    [ 2.500,  5.000) = 8115 
    [ 5.000,  7.500) = 170 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.966 ms/op
     p(50.0000) =      3.625 ms/op
     p(90.0000) =      4.043 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      7.479 ms/op
     p(99.9000) =     25.461 ms/op
     p(99.9900) =     27.394 ms/op
     p(99.9990) =     27.394 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


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
# Warmup Iteration   1: 8.446 ±(99.9%) 0.323 ms/op
Iteration   1: 4.745 ±(99.9%) 0.064 ms/op
                 getUser·p0.00:   1.380 ms/op
                 getUser·p0.50:   4.497 ms/op
                 getUser·p0.90:   5.366 ms/op
                 getUser·p0.95:   6.807 ms/op
                 getUser·p0.99:   10.600 ms/op
                 getUser·p0.999:  18.891 ms/op
                 getUser·p0.9999: 19.628 ms/op
                 getUser·p1.00:   19.628 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6750
  mean =      4.745 ±(99.9%) 0.064 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 63 
    [ 2.500,  3.750) = 476 
    [ 3.750,  5.000) = 5127 
    [ 5.000,  6.250) = 648 
    [ 6.250,  7.500) = 228 
    [ 7.500,  8.750) = 66 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 40 

  Percentiles, ms/op:
      p(0.0000) =      1.380 ms/op
     p(50.0000) =      4.497 ms/op
     p(90.0000) =      5.366 ms/op
     p(95.0000) =      6.807 ms/op
     p(99.0000) =     10.600 ms/op
     p(99.9000) =     18.891 ms/op
     p(99.9900) =     19.628 ms/op
     p(99.9990) =     19.628 ms/op
     p(99.9999) =     19.628 ms/op
    p(100.0000) =     19.628 ms/op


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
# Warmup Iteration   1: 24.292 ±(99.9%) 0.772 ms/op
Iteration   1: 18.802 ±(99.9%) 0.340 ms/op
                 listUser·p0.00:   2.605 ms/op
                 listUser·p0.50:   18.088 ms/op
                 listUser·p0.90:   23.314 ms/op
                 listUser·p0.95:   28.770 ms/op
                 listUser·p0.99:   33.636 ms/op
                 listUser·p0.999:  39.402 ms/op
                 listUser·p0.9999: 39.584 ms/op
                 listUser·p1.00:   39.584 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1694
  mean =     18.802 ±(99.9%) 0.340 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 9 
    [ 5.000,  7.500) = 6 
    [ 7.500, 10.000) = 9 
    [10.000, 12.500) = 12 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 376 
    [17.500, 20.000) = 884 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 81 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      2.605 ms/op
     p(50.0000) =     18.088 ms/op
     p(90.0000) =     23.314 ms/op
     p(95.0000) =     28.770 ms/op
     p(99.0000) =     33.636 ms/op
     p(99.9000) =     39.402 ms/op
     p(99.9900) =     39.584 ms/op
     p(99.9990) =     39.584 ms/op
     p(99.9999) =     39.584 ms/op
    p(100.0000) =     39.584 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.836          ops/ms
Client.existUser                       thrpt         7.642          ops/ms
Client.getUser                         thrpt         5.051          ops/ms
Client.listUser                        thrpt         1.371          ops/ms
Client.createUser                       avgt         6.505           ms/op
Client.existUser                        avgt         3.087           ms/op
Client.getUser                          avgt         4.828           ms/op
Client.listUser                         avgt        16.200           ms/op
Client.createUser                     sample  5835   5.479 ± 0.088   ms/op
Client.createUser:createUser·p0.00    sample         3.199           ms/op
Client.createUser:createUser·p0.50    sample         5.423           ms/op
Client.createUser:createUser·p0.90    sample         6.074           ms/op
Client.createUser:createUser·p0.95    sample         6.373           ms/op
Client.createUser:createUser·p0.99    sample        13.976           ms/op
Client.createUser:createUser·p0.999   sample        30.097           ms/op
Client.createUser:createUser·p0.9999  sample        33.161           ms/op
Client.createUser:createUser·p1.00    sample        33.161           ms/op
Client.existUser                      sample  8525   3.818 ± 0.053   ms/op
Client.existUser:existUser·p0.00      sample         0.966           ms/op
Client.existUser:existUser·p0.50      sample         3.625           ms/op
Client.existUser:existUser·p0.90      sample         4.043           ms/op
Client.existUser:existUser·p0.95      sample         4.219           ms/op
Client.existUser:existUser·p0.99      sample         7.479           ms/op
Client.existUser:existUser·p0.999     sample        25.461           ms/op
Client.existUser:existUser·p0.9999    sample        27.394           ms/op
Client.existUser:existUser·p1.00      sample        27.394           ms/op
Client.getUser                        sample  6750   4.745 ± 0.064   ms/op
Client.getUser:getUser·p0.00          sample         1.380           ms/op
Client.getUser:getUser·p0.50          sample         4.497           ms/op
Client.getUser:getUser·p0.90          sample         5.366           ms/op
Client.getUser:getUser·p0.95          sample         6.807           ms/op
Client.getUser:getUser·p0.99          sample        10.600           ms/op
Client.getUser:getUser·p0.999         sample        18.891           ms/op
Client.getUser:getUser·p0.9999        sample        19.628           ms/op
Client.getUser:getUser·p1.00          sample        19.628           ms/op
Client.listUser                       sample  1694  18.802 ± 0.340   ms/op
Client.listUser:listUser·p0.00        sample         2.605           ms/op
Client.listUser:listUser·p0.50        sample        18.088           ms/op
Client.listUser:listUser·p0.90        sample        23.314           ms/op
Client.listUser:listUser·p0.95        sample        28.770           ms/op
Client.listUser:listUser·p0.99        sample        33.636           ms/op
Client.listUser:listUser·p0.999       sample        39.402           ms/op
Client.listUser:listUser·p0.9999      sample        39.584           ms/op
Client.listUser:listUser·p1.00        sample        39.584           ms/op
