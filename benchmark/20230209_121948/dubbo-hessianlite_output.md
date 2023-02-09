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
# Warmup Iteration   1: 0.623 ops/ms
Iteration   1: 1.547 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  1.547 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.863 ops/ms
Iteration   1: 5.024 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  5.024 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.198 ops/ms
Iteration   1: 3.762 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.762 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:07
# Fork: 1 of 1
# Warmup Iteration   1: 0.758 ops/ms
Iteration   1: 1.004 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.004 ops/ms


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

# Run progress: 33.33% complete, ETA 00:01:00
# Fork: 1 of 1
# Warmup Iteration   1: 24.192 ±(99.9%) 0.402 ms/op
Iteration   1: 12.078 ±(99.9%) 0.042 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  12.078 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:52
# Fork: 1 of 1
# Warmup Iteration   1: 13.990 ±(99.9%) 0.257 ms/op
Iteration   1: 5.629 ±(99.9%) 0.037 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  5.629 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:45
# Fork: 1 of 1
# Warmup Iteration   1: 17.297 ±(99.9%) 0.368 ms/op
Iteration   1: 6.634 ±(99.9%) 0.066 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  6.634 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:37
# Fork: 1 of 1
# Warmup Iteration   1: 35.207 ±(99.9%) 0.999 ms/op
Iteration   1: 24.639 ±(99.9%) 0.253 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  24.639 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:29
# Fork: 1 of 1
# Warmup Iteration   1: 20.846 ±(99.9%) 0.723 ms/op
Iteration   1: 8.774 ±(99.9%) 0.293 ms/op
                 createUser·p0.00:   3.465 ms/op
                 createUser·p0.50:   8.331 ms/op
                 createUser·p0.90:   14.428 ms/op
                 createUser·p0.95:   18.317 ms/op
                 createUser·p0.99:   26.247 ms/op
                 createUser·p0.999:  46.580 ms/op
                 createUser·p0.9999: 53.084 ms/op
                 createUser·p1.00:   53.084 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 3623
  mean =      8.774 ±(99.9%) 0.293 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 811 
    [ 5.000, 10.000) = 2175 
    [10.000, 15.000) = 339 
    [15.000, 20.000) = 171 
    [20.000, 25.000) = 41 
    [25.000, 30.000) = 53 
    [30.000, 35.000) = 1 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 16 
    [45.000, 50.000) = 15 
    [50.000, 55.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      3.465 ms/op
     p(50.0000) =      8.331 ms/op
     p(90.0000) =     14.428 ms/op
     p(95.0000) =     18.317 ms/op
     p(99.0000) =     26.247 ms/op
     p(99.9000) =     46.580 ms/op
     p(99.9900) =     53.084 ms/op
     p(99.9990) =     53.084 ms/op
     p(99.9999) =     53.084 ms/op
    p(100.0000) =     53.084 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.114 ±(99.9%) 0.511 ms/op
Iteration   1: 4.278 ±(99.9%) 0.086 ms/op
                 existUser·p0.00:   0.880 ms/op
                 existUser·p0.50:   3.985 ms/op
                 existUser·p0.90:   4.969 ms/op
                 existUser·p0.95:   5.816 ms/op
                 existUser·p0.99:   15.489 ms/op
                 existUser·p0.999:  27.001 ms/op
                 existUser·p0.9999: 28.213 ms/op
                 existUser·p1.00:   28.213 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 7536
  mean =      4.278 ±(99.9%) 0.086 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 324 
    [ 2.500,  5.000) = 6466 
    [ 5.000,  7.500) = 460 
    [ 7.500, 10.000) = 102 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.880 ms/op
     p(50.0000) =      3.985 ms/op
     p(90.0000) =      4.969 ms/op
     p(95.0000) =      5.816 ms/op
     p(99.0000) =     15.489 ms/op
     p(99.9000) =     27.001 ms/op
     p(99.9900) =     28.213 ms/op
     p(99.9990) =     28.213 ms/op
     p(99.9999) =     28.213 ms/op
    p(100.0000) =     28.213 ms/op


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
# Warmup Iteration   1: 13.265 ±(99.9%) 0.483 ms/op
Iteration   1: 7.270 ±(99.9%) 0.124 ms/op
                 getUser·p0.00:   2.810 ms/op
                 getUser·p0.50:   6.865 ms/op
                 getUser·p0.90:   9.257 ms/op
                 getUser·p0.95:   10.437 ms/op
                 getUser·p0.99:   20.290 ms/op
                 getUser·p0.999:  28.868 ms/op
                 getUser·p0.9999: 32.506 ms/op
                 getUser·p1.00:   32.506 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 4514
  mean =      7.270 ±(99.9%) 0.124 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 152 
    [ 5.000,  7.500) = 2836 
    [ 7.500, 10.000) = 1255 
    [10.000, 12.500) = 196 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 6 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.810 ms/op
     p(50.0000) =      6.865 ms/op
     p(90.0000) =      9.257 ms/op
     p(95.0000) =     10.437 ms/op
     p(99.0000) =     20.290 ms/op
     p(99.9000) =     28.868 ms/op
     p(99.9900) =     32.506 ms/op
     p(99.9990) =     32.506 ms/op
     p(99.9999) =     32.506 ms/op
    p(100.0000) =     32.506 ms/op


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
# Warmup Iteration   1: 32.142 ±(99.9%) 0.888 ms/op
Iteration   1: 21.064 ±(99.9%) 0.351 ms/op
                 listUser·p0.00:   8.061 ms/op
                 listUser·p0.50:   20.054 ms/op
                 listUser·p0.90:   27.401 ms/op
                 listUser·p0.95:   30.840 ms/op
                 listUser·p0.99:   35.062 ms/op
                 listUser·p0.999:  36.887 ms/op
                 listUser·p0.9999: 37.421 ms/op
                 listUser·p1.00:   37.421 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1508
  mean =     21.064 ±(99.9%) 0.351 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 6 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 124 
    [17.500, 20.000) = 572 
    [20.000, 22.500) = 490 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 74 
    [27.500, 30.000) = 66 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 28 
    [35.000, 37.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      8.061 ms/op
     p(50.0000) =     20.054 ms/op
     p(90.0000) =     27.401 ms/op
     p(95.0000) =     30.840 ms/op
     p(99.0000) =     35.062 ms/op
     p(99.9000) =     36.887 ms/op
     p(99.9900) =     37.421 ms/op
     p(99.9990) =     37.421 ms/op
     p(99.9999) =     37.421 ms/op
    p(100.0000) =     37.421 ms/op


# Run complete. Total time: 00:01:30

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         1.547          ops/ms
Client.existUser                       thrpt         5.024          ops/ms
Client.getUser                         thrpt         3.762          ops/ms
Client.listUser                        thrpt         1.004          ops/ms
Client.createUser                       avgt        12.078           ms/op
Client.existUser                        avgt         5.629           ms/op
Client.getUser                          avgt         6.634           ms/op
Client.listUser                         avgt        24.639           ms/op
Client.createUser                     sample  3623   8.774 ± 0.293   ms/op
Client.createUser:createUser·p0.00    sample         3.465           ms/op
Client.createUser:createUser·p0.50    sample         8.331           ms/op
Client.createUser:createUser·p0.90    sample        14.428           ms/op
Client.createUser:createUser·p0.95    sample        18.317           ms/op
Client.createUser:createUser·p0.99    sample        26.247           ms/op
Client.createUser:createUser·p0.999   sample        46.580           ms/op
Client.createUser:createUser·p0.9999  sample        53.084           ms/op
Client.createUser:createUser·p1.00    sample        53.084           ms/op
Client.existUser                      sample  7536   4.278 ± 0.086   ms/op
Client.existUser:existUser·p0.00      sample         0.880           ms/op
Client.existUser:existUser·p0.50      sample         3.985           ms/op
Client.existUser:existUser·p0.90      sample         4.969           ms/op
Client.existUser:existUser·p0.95      sample         5.816           ms/op
Client.existUser:existUser·p0.99      sample        15.489           ms/op
Client.existUser:existUser·p0.999     sample        27.001           ms/op
Client.existUser:existUser·p0.9999    sample        28.213           ms/op
Client.existUser:existUser·p1.00      sample        28.213           ms/op
Client.getUser                        sample  4514   7.270 ± 0.124   ms/op
Client.getUser:getUser·p0.00          sample         2.810           ms/op
Client.getUser:getUser·p0.50          sample         6.865           ms/op
Client.getUser:getUser·p0.90          sample         9.257           ms/op
Client.getUser:getUser·p0.95          sample        10.437           ms/op
Client.getUser:getUser·p0.99          sample        20.290           ms/op
Client.getUser:getUser·p0.999         sample        28.868           ms/op
Client.getUser:getUser·p0.9999        sample        32.506           ms/op
Client.getUser:getUser·p1.00          sample        32.506           ms/op
Client.listUser                       sample  1508  21.064 ± 0.351   ms/op
Client.listUser:listUser·p0.00        sample         8.061           ms/op
Client.listUser:listUser·p0.50        sample        20.054           ms/op
Client.listUser:listUser·p0.90        sample        27.401           ms/op
Client.listUser:listUser·p0.95        sample        30.840           ms/op
Client.listUser:listUser·p0.99        sample        35.062           ms/op
Client.listUser:listUser·p0.999       sample        36.887           ms/op
Client.listUser:listUser·p0.9999      sample        37.421           ms/op
Client.listUser:listUser·p1.00        sample        37.421           ms/op
